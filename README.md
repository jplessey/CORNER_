# CORNER_
Web application for writers and journalists.

CORNER_ is a Flask web-application based on the "Python Flask From Scratch" tutorials serie by Traversy Media.

The original purpose of the tutorials consisted on building a generic application for writing, posting and editing articles.
It included features like User Registration,Loging and Access control.

I decided to make some changes to the original genearal application and create a concept that could actually be thought as a real world application. 

Those changes included:
- Updating the navigation bar to the current Bootstrap version (4.3.1). This meant a refreshed look which made it more esthetically pleasent.
- Merging articles page with home. The original application considered two separate pages for home and articles, where the  articles page had a list of articles posted by all users. This meant that the home page was merely a presentation page with no defined purpose so I thought it would be better that the main page of the application had the list of articles so readers could directly see the links a start to read right away. Also the list of articles now has information about authors which originally didn have.
- After each user has registerd and logged in, they can have accees to a dashboard with information about the articles. Originally, all users had access to the information of all articles, whuch meant an user could actually edit or delete an article from another user. I thought that wasn't ok so now each user has access to his own articles so every user sees its own personal dashboard.
- After 
