# microblog
# Microblog

/***************************************************************************************
Open source code reference
*    Title: <The Flask Mega Tutorial part I-X>
*    Author: < Miguel Grinberg>
*    Date: <December 5, 2017-Nov 11, 2022>
*    Code Version: <Version 0.0-0.22>
*    Availability: https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world
*
***************************************************************************************/

Hello, all

Here you are in our readme wanting to know how to run this application, what these folders and files contain. How they are used in regards to the microblog application which is a blogging website. So, that's what we're going to dive in too.

To start off first you first need to clone the directory to able to have it on your OS and the command to type in on your command line would be: 'git clone https://github.com/khanE11/microblog'

Then to switch to the microblog directory on your command line type in the
command: 'cd microblog'

After that, you would want to set up your virtual environment with the command: 'source venv/bin/activate'

 Then to set the "Flask_APP" environment variable to ultimately be able to import the application onto your command line type in the command on your terminal: 'export FLASK_APP = microblog3.py' 
 
 Finally, to run the application just type in the command: 'flask run'
 
 and then type in or copy and paste the localhost url given in the output of the command to be able to see the application.

The first folder/file we're going to look at is the __init__.py file which sets up the application instance with the flask framework along with setting up the datasbase, login, and migration instance.

In the microblog3.py file the Flask application instance is defined and imported.

Then in the config.py of the micrblog3 application the configurations variables of the application are set.

in the tests3.py file this is where some automated tests are to make sure that different parts of the application work such as password hashing as one example of the functionalities that's implemented in this application

Under the app3 folder in microblog3 you'll see a folder with templates and in that folder you'll see html files such as index3.html, login3.html, register3.html that are used to help render certain functionalities on to the website.

in the routes3.py file this is where the links are implemented for users to access different parts of the website. Along with view functions such as login3, and index3 which are tied to the html files login3.html and index3.html as these html files help render the functionality of being able to login and in the case with index3 it helps to format and show the homepage of the website.

in the models3.py file this is where the models are implemented for the database and how it should store and format information. 

in the errors3.py file there are error handlers implemented for the app that are tied to the 500.html template file and 404.html template file for rendering those error pop ups on the website.

in the forms3.py file this where there are forms implemented for the website such as a registration form for when a user wants to sign up for the website or a login form if the user already has an account.  