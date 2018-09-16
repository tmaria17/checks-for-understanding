### Week 5 Questions

Re-pull from this repository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week (which is a TON!).

Note: When you're done, submit a PR.

### Week 5 Questions
1. How do we make flash messages display on a page?
We put flash messages in the conrtroller and you call it in the view, typically the layout. 

2. Where is cart information/temporary information usually stored?
Sessions!

3. What might be some reasons not to store a cart in our database? Are there any reasons why we would want to persist that information?
  We wouldn't want to store a cart in our database because it isn't a good use of space. 

4. What is the purpose of the asset pipeline?
decrease the time it takes for our pages to load. 
5. Why do we precompile our assets?

6. What do each of the following tags do?

```ruby 
<%= stylesheet_link_tag "application" %>
<%= javascript_include_tag "application" %>
<%= image_tag "rails.png" %>
```
They allow us to include certain things in our app folder. Styling, Javascript, and images

7. What are some of the elements of a great read me? What are some of the benefits of taking the time to update a readme for our project?
-Sample code
-images or sceenshots of the project deployed
-good formatting
-doensn't need to be dry
-a link to the project

A benefit would be that employers will know that you can speak at a technical level about your projects.

8. What are the top four accessibility issues that we as developers should be aware of?
-auditory -visual -cognitive - mobility 
 
9. `before_save` is an example of a what? Where in our Rails application would we find a `before_save`?
  a callback, it updates the project
10. Given the following object, how would we create a scope for all users who are active?

```ruby 
User.create(name: "Happy", active: true)
```
User.where(active:true) ?
11. What is the difference between a scope and a class method?

I'm not sure
### Review Questions:  
12. Given the following hash:  

```ruby
{cart: {"17" => 4, "204" => 52, "29" => 22}}
```

  12a. How would you add item with id of 48 with a quantity of 4?  
  hash[:cart]["48"]=4
  12b. How would you increase the quantity of item 29? 
  hash[:cart][29]+= 1
  12c. How would you find out how many items your user is thinking about purchasing?   
  .count
  
13. What is polymorphism? How does it relate to duck-typing? What are two ways you use this in everyday Rails applications? 
Polymorphis is being able to tell different objects the same thing and having the result be different. I am not sure what duck typing is. 
14. How would you clean the string "(630) 854-5483" to "630.854.5483"? 
phone_num =  "(630) 854-5483"
phone_num.tr("()","").tr("-",".")

### Self Assessment:
Choose One:
* I was able to answer most questions independently, but utilized outside resources for a few

Choose One:
* I feel comfortable with the content presented this week
