# MyBlog_FinalProject-CS50

This is my Final CS50 Project. This Web application is based on Python, HTML, CSS and Flask framework. For Deployment I used Microsoft Azure together with GitHub. You can view the screen recording of how my app works by following the link, or follow this link yourself to see the app itself https://myflaskblogcs50.azurewebsites.net/. 

#### Video Demo:  <URL HERE>

### Description:
## How does the web application work?

With the help of my application, I wanted to implement a mini-blog project. Unregistered users can go to the All posts page and see the post posted there. If the user is already registered, he can log in. To do this, click on the Login button and fill out the form. You can also register: to do this, click on the Register button and fill out the form. To do this, you will need a username, email and password, which will need to be confirmed.

After logging, if you click on the picture of a cat at the top of the navbar, you will be redirected to your Account. If you are not logged in, you will be redirected to the Login page. In the Account using special buttons and forms you can change the username, email and profile picture. When registering, sets the defaul.jpg. After logging in, you can also create New Posts. To do this, click on the create button New Post, enter the title and the text of the post itself click on the confirmation button. If you are the author of a particular post, you can Update or Delete it. To do this, click on the title of the post, and then select the button with the action. When deleting, the web application will ask you to confirm the action. This is necessary to avoid accidental deletion. On the page all posts you can view all posts from all authors, but delete or update - only your own.
 
### Features:
  
  Register
 
  Login
 
  Logout
 
  Create new post
 
  View all posts
 
  Updating username, email, profile picture
 
  Updating title and text of your own posts
 
  Delete your own posts
 
  
  
### For MAC and LINUX
  
cd [path to app.py]
  
export API_KEY=[your api key]
  
export FLASK_APP=app.py
  
flask run

#### Optional
  
export FLASK_ENV=development
  
export FLASK_DEBUG=1

### For Windows
  
cd [path to app.py]
  
set API_KEY=[your api key]
  
set FLASK_APP=app
  
flask run

#### Optional
  
set FLASK_ENV=development
  
set FLASK_DEBUG=1

### For more information you can visit:

https://cs50.harvard.edu/x/2022/
  
https://portal.azure.com/
  
https://flask.palletsprojects.com/en/2.2.x/
  
