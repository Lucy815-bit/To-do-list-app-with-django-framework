# To-do-list-app-with-django-framework
This project helps create a to do app with the python django framework
 where you can add to do list in sqlite database and delete as well.
 In order to make this work for you you need to
 1. install python3
 2. install django in a virtual environment, if you are using windows, 
 follow the steps below to install Django
 
Type cmd at your windows start button 
click to run the command line as administrator
cd.. (so that you dont create a folder in your windows)
md editdojo  (this helps you to create a directory called editdojo)
cd editdojo (to allow you get inside the folder
python -m venv env (run this command to create a virtual environment called env)
cls
env\Scripts\activate(run this command to activate the virtual environment)
pip install django (run this command to install django)
Django-admin startproject editdojo_project(run this command to create a project called edidojo_project)
python manage.py runserver (run this command to set up server )
copy the url in your command line and search it on 
your browser to be sure your django is set up successfuly
python manage.py createsuperuser (run this command in you cmd in order to create a super user)
provide a username, email address and password for the same
python manage.py runserver (run this command to set up server ) browse the url provided and with \admin to view the created user)
you can add users as you wish

Now
Download and unzip my editdojo folder

Now open your vscode and open the project editdojo_project within it.
python manage.py startapp todo (run this command on you cmd and check vscode to confirm that app has been created and added)
now click on your todo app and create a folder templates
click on the templates folder and create a file known as todo.html
click to open my editdojo_project
open models.py and copy the code
open your models.py in the vscode and paste my code
go back to the cmd and run the following codes
1. python manage.py makemigrations
2. python manage.py migrations
This will make migrations and set up sqlite database

Now open edidojo_project get todo.html code and copy the code
if you cant see this, open the todo browser and right click on it, click open sourse code and copy the code
now paste this code in your todo.html in the vscode

open editdojo_project and copy the code in my views.py
paste it on your views.py

open edidojo_project and copy the urls.py code
paste it on your urls.py (tell django where to send requests from the browser)
save all the codes you have pasted.
refresh your browser.
you are now able to add to do list and deletecongratulations
