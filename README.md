23rd of September,2022 I started the Zuri training cohort  as a Fullstack (Frontend and Python)trainee. 

This repo consists of my week 3 to 5 projects during the training.

This is the [Youtube playlist](....put link to playlist here) for the training's Full-stack track

# Projects
##Week 3

### Python Task: OOP, Classes and Objects Project (Quiz)
This was a python task in week 3. I was given simple questions to answer. this quiz is in week 3 branch on this repo. it is titled as "Python Quiz question". it is a single document on the first page. it is not in an individyual folder.

### Tasks CSS Fundamentals project.
this was a Frontend task. in this task we were required to : 

1. Create a simple portfolio website with the following information: about me section, contact page, services section, project.
2. Using HTML semantics, we were to include a header, main, and footer tag. 
3. Then we should add a navigation menu at the top of the home page. 
4. We should also use inline linking to the sections on the home page and make the other pages, like contact us, open up a new page.
    
    The following should be included in my portfolio: 

My name
A paragraph about myself
Projects (everything I have done, both zuri and outside.)
Services 
Hobbies, priorities, and other skills
Somewhere on the page where it makes sense visually, I am to add a photo of myself.
Name
Email
Message
Hint Searching for designs online will give you a better understanding of a beautiful design.

### HTML and CSS Log in/Registration, Success page project

   1. The user can only access the success or congrats page when they enter the correct info in the fields provided.
   2. The Success and Congrats page is only accessible through the log in / register pages.  
   Create the following pages using HTML CSS

Registration page
Login page
Success register page
Your section of the registration page should include

First name 
Last name
Phone number
Email 
Gender (select field)
Date of birth (date selection option)
Favorite color (color selector)
Your section of the login page should include

Email and
password
If the user uses the correct format for email and password, the user should be navigated to the success page.

Hint Searching for designs online will give you a better understanding of a beautiful design.


   *I used lists, dictionary, if and else statement, string methods, input and arithmetic operands*
   
   [Youtube Link](https://www.youtube.com/watch?v=KuZwwbNBhY0&list=PLxuUHF3OiqfWAITD4gPUHZ1GcYRqmyF7P&index=15) and [Github Link to file](https://github.com/PrechyDev/Zuri/blob/main/mock_atm.py)

   [Updated project](https://github.com/PrechyDev/Zuri/blob/main/updated_mock_atm.py) with login, register and a few other functions
    
    
### [Budget App](https://github.com/PrechyDev/Zuri/blob/main/budget.py)
   Create a Budget class that can instantiate objects based on different budget categories like food, clothing, and entertainment. These objects       should allow for
   1.  Depositing funds to each of the categories
   2.  Withdrawing funds from each category
   3.  Computing category balances
   4.  Transferring balance amounts between categories
   
   
### [Full-scale Mock ATM](https://github.com/PrechyDev/Mock-ATM)
This is a badass update to my initial project mock_atm which is in this repository. Here, I split the various functionalities into several files
importing them when needed as module.

#### Features
1. A `register` function connected to a local file system that creates a new user with a generated account number and saves the user details to a new txt file.

2. A `login` function that authenticates if the user input is a valid account number and if user exists. If password is correct, the user gets sent
to `bank operations`, else they try again.

3. A `banking` module  which has several banking operation functions connected to the local database, reading details from it and updating the account 
balance for every transaction.

4. A `validation` module that checks if the inputed account number is valid based on a few checks.

5. A `database` module that has basic `CRUD` functionalities for creating a new user, reading data from a user_file, updating a user account balance
and checking if a user exists before creating a new one.


### [Blog Project](https://github.com/PrechyDev/Django-Blog)
This project is a simple django blog creating using mainly ClassBasedViews and deployed to heroku.
The database used was SQLite.

#### Features

- A `blog` app which is the main component of the blog adding new posts and comments and displaying them to the user.

- An `accounts` app for registration and login

- A `Post` model that creates a new post with `author', `title` and post `body`.

- A  `Comment` model that creates a new Comment object using `post`, `author` and `comment`.

- A home page showing posts

- A post page showing post title, body and comment section

 -  A delete post page 

 -  An edit post page

 -  A register page (a new user can register, their details stored in a database file). 

-    login (checks in the file and logs them in if they are already registered)

-    reset password

-    logout

-    A comment section, you must be logged in to comment

 **[Check out blog](http://prechy-blog.herokuapp.com)**

