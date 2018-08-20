## Week One - Module 2 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week (which is a TON!).

Note: When you're done, submit a PR.

### Week 1 Questions

1. List the five common HTTP verbs and what the purpose is of each verb.
Get
Put
Patch
Post
Delete

2. What is Sinatra?
  A lightweight ruby web framework
3. What is MVC?
  A way of organizng your code 
  MVC is model view control 
4. Why do we follow conventions when creating our actions/path names in our Sinatra routes?

To make code more readable 

5. What types of variables are accessible in our view templates without explicitly passing them?

Instance Variables . 

6. Given the following block of code, how would I pass an instance variable `count` with a value of `1` to my `index.erb` template?

  ```ruby
  get '/horses' do
   @count =1 
  name = 'Mr. Ed' 
   erb :index
   
  end
  ```

7. In the same code block, how would I pass a local variable `name` with a value of `Mr. Ed` to the view?

8. What's the purpose of ERB?
It emmbeds ruby, it describes how data should be used to create HTML

9. Why do I need a development AND test database?
*********
10. What is CRUD and why is it important?
CRUD is Create Read Update Delete 

11. What does HTTP stand for?
Hyper Text Transfel Protocol

12. What are the two ways to interpolate Ruby in an ERB view template? What's the difference between these two ways?
<% >% This one doesn't print the return value 
<%= > This one prints the return Value 

13. What's an ORM? What does it do?
Object Relational Map, it wraps our data in ruby objects so we can manipulate them. 

14. What's the most commonly used ORM in ruby (Sinatra & Rails)?
ActiveRecord

15. Let's say we have an application with restaurants. There are seven verb + path combinations necessary to provide full CRUD functionality for our restaurant application. List each of the seven combinations, and explain what each is for.

16. What's a migration?
 It allows you to create and modify database schema
17. When you create a migration, does it automatically modify your database?
rake db:migrate

18. How does a model relate to a database?
*********
19. What is the difference between `#new` and `#create`?
Create will save the new instance

20. Given a table named `animals`, What is the SQL query that will return all info from that table?<br>


    SELECT * FROM animals;

    `id     name        number_of_legs
    -----   ------      --------------
      1     panda       4
      2     giraffe     4
      3     whale       0
      4     bird        2

21. Using the same table, What is the SQL query that will return only the animals that has 4 legs?<br>
SELECT * FROM animals WHERE number_of_legs = 4;


### Review Questions:  
22. Given a CSV file (“films.csv”) with these headers [id, title, description], how would you load these into your database to create new instances of Film?  You would need to create a class with these attributes and use file.io 

23. Given the following hash:
```
activities = {
  hiking: {cost: $0, supplies: ['hiking shoes', 'water', 'compass']},
  karaoke: {cost: $10, supplies: ['courage', 'microphone']},
  brunch: {cost: $35, supplies: ['mimosa flutes']},
  antiquing: {cost: $200, supplies: ['list of antique stores']}
}
```
How would I add 'granola bar' to things you should have when hiking?
hiking[:supplies] << 'granola bar'

24. What are the 4 Principles of OOP? Give a one sentence explanation of each.

encapsulation- database protection, your code should only know about other code it absolutely needs to know about
inheritance- classes inherit behavior from superclasses
polymorphism-  allows you to invoke the same method on different objects and get different results.
abstraction-  handles complexity by hiding uneccessary details from the user. 


### Self Assessment:
Choose One: (erase the others)
* I was able to answer a few questions independently, but relied heavily on outside resources

Choose One:
* I feel comfortable with the content presented this week
* I feel overwhelmed by the content presented this week
Both?
