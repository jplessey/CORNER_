# CORNER_
Web application for writers and journalists.

CORNER_ is a web-application which was built using Flask. It’s based on the "Python Flask From Scratch" tutorials series by Traversy Media.

The original purpose of the tutorials consisted on building a generic application for writing, posting and editing articles.
It included features like User Registration, Login and Access control.

I decided to make some changes to the original application and create a concept that could actually be thought as a real world application. 

Those changes included:
- Updating the navigation bar to the current Bootstrap version (4.3.1). This meant a refreshed look which made it more aesthetically pleasant.
- Merging articles page with home. The original application considered two separate pages for home and articles, where the  articles page had a list of articles posted by all users. This meant that the home page was merely a presentation with no defined purpose so I thought it would be better that the main page of the application had the list of articles directly so readers could see the links a start reading and looking for articles right away. Also the list of articles now has information about authors which originally didn't.
- After each user has registered and logged in, they can have access to a dashboard with information about the articles. Originally, all users had access to the information of all articles, which meant an user could actually edit or delete an article from another user. I thought that wasn't OK so now each user has access to his own articles so every user sees its own personal dashboard.
- All these changes required to think about the necessary buttons the navigation bar actually needed and how they were going to work. The name of the application on the right side is linked to home. There's an "About" link that gives a brief information about the purpose of the application. "Register" and "Login" buttons on the right side were also present on the original conception of the app, however, now after an user has logged in, a button with the username appears as way to confirm that someone is connected. The username button also works as the link to the personal dashboard.
