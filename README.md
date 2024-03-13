Happpy to share my new Blog App Food Recipes

Technologies used in building that Applicaion 
"MERN STACK TECHNOLOGIES"

BACKEND SETUP:-
first we are creating backend server using commmand
"npm init -y"
then we are creating index.js file in this file we have creating route also 
and we are using .env file to access mongodb cluster for database 

then we are creating routes like
SignUp:   LogIn : AllBlogs:  AllBlogs/add: AllBlogs/:id: AllBlogs/Delete/:id: AllBlogs/edit/:id: 

we are using middleware cors, bodyParser, 

we are using gensalt and jsonWeb Token and secrete key  
we are using bcrypt for hashing password and comparing verifying

FROTEND SETUP :- 
first we are creating frontend react app using commmand
"npx create-react-app blogs"

then we have source folder we are creating components folder in that file 
we have Navbar, LogIn, SignUp, Home, AddBlog, EditBlogs, Blogs, Footer, NotFound reusable components
we are creating index.js and index.css file we are linking the file index.css by importing it

LOGIN:-
      we are have login form in this we have heading, label, inputs, and Submit Button 
      when we clicking on submit button if we are authorize user so data of user is 
      (username, email, password) is stored in localStorage 
      we also have the text link for new user to navigate to SIGNUP page

SIGNUP:- 
      we are have signup form in this we have heading, label, inputs, and Submit Button 
      we also have the text link for new user to navigate to LOGIN page.

HOME:- 
      we are having Navbar and blogs page in this page we are showing all blogs using the data from 
      data base then we are fetching data and after that and showing the data with the help of html code  
      for styling we have index.css file we have addButton when we are clicking on it we are navigate to 
      addBlogs component form with the help of LINK by react-router-dom and  when ew are clicking on blogs
      image are text we are navigate to blog page 
      
BLOG:- 
      we are having Image recipes text and author name , and two buttons we are using react-icons for this
      when clicking on delete button the blog are deleted and we are navigate to home page and when we are 
      click edit icon we are navigate to edit form 

Edit: 
      we are having edit form and back button to return home page and submit button to submit the all 
      the recipes details.
      
Navbar:- 
      we are having navbar components on top of home components we have logo blogs we having 
      diferent page Link on it and we have avatar image when we clicking on it we have 
      seen popup screen in this we have user image, name , email











      


















