## Week Four Recap

### Instructions
Fork or re-pull this repository. Answer the questions to the best of your ability.

Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR with a reflection in the comments about how this exercise went for you.

### Week 4 Questions

1. What is a cookie?
A cookie is a small piece of data stored in the browser for a website. It is how a website can identify a sepcific user. 
2. What’s the difference between a session and a cookie?

3. What’s a flash and when do you want to use flashes?
it is a message that gives the user feedback about their actions "you're password didn't work!" etc. 
4. Why do people say “HTTP is stateless”?
it doesn't remember anything . 
5. What’s authentication? Explain. 
it confirms that the person accessing data is who is supposed to be accessing it. 
6. What’s the difference between authentication and authorization?
authorize is when you need to be a different type of user to access things. User vs admin. 
7. What’s a before filter?
it does things before all the other controller methods. 
8. How do we keep track of a user once they’ve logged in?
with cookies and sessions. 
9. When do you want to namespace a resource? When do you want to nest a resource? What's the differences between those two approaches?

10. At a high level, what tools can you use to implement authorization? How would you use them?
pass word digest, with a gem. 
9. When do you want to namespace a resource? When do you want to nest a resource? What's the differences between those two approaches?
11. What's an enum, and what advantages does it offer? What data type needs to be in your database to use an enum? Where do you declare an enum?
You use it at the model level, 
12. What are some strategies you can use to keep your views DRY?
partials for forms, keep logic out of views, helper methods. 


### Reviews Questions 
13. Given the following array of hashes, how would I print an alphabetical list of holidays?
```ruby
[
 {holiday: {name: "St Patrick's Day", supplies: ["Corned Beef and Cabbage"]}},
 {holiday: {name: "Halloween", supplies: ["Candy", "Costume"]}},
 {holiday: {name: "Hanukkah", supplies: ["Menorah"]}}
] 
```  
14. How would you clean incoming data to ensure "$300" or "300.00" is stored as 300? 


### Self Assessment:
Choose One:
* I was able to answer every question without relying on outside resources
* I was able to answer most questions independently, but utilized outside resources for a few

Choose One:
* I feel comfortable with the content presented this week
* I feel overwhelmed by the content presented this week
