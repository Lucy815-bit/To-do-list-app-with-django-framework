# To-do-list-app-with-django-framework
This project helps create a to do app with the python django framework
 where you can add to do list in sqlite database and delete as well.
 In order to make this work for you, you need to
 1. install python3
 2.  Install sqlite database
 3. install django in a virtual environment, if you are using windows 10, 
 
follow the steps below to install Django
 
Type cmd at your windows start button, 
click to run the command line as administrator
run the following commands
cd.. 
md editdojo  (this helps you to create a directory called editdojo)
cd editdojo 
             (to allow you get inside the folder
python -m venv env 
(run this command to create a virtual environment called env)
cls
env\Scripts\activate 
(run this command to activate the virtual environment)
pip install django
 (run this command to install django)
Django-admin startproject editdojo_project
(run this command to create a project called edidojo_project)
python manage.py runserver 
(run this command to set up server )

copy the url in your command line and search  on 
your browser to be sure your django is set up successfuly

python manage.py createsuperuser 
(run this command in you cmd in order to create a super user)

provide a username, email address and password for the same
python manage.py runserver 

(run this command to set up server ) browse the url provided and with \admin to view the created user)
you can add users as you wish

Now
Download and unzip my editdojo folder

open your vscode and open the project editdojo_project within it.


open models.py and save it then go back to command line and type 
1. python manage.py makemigrationspavbnm,./
2. python manage.py migratione
This will make migrations and set up sqlite database

In the vscode get todo.html code save it as well


open  my views.py save it as well                                                                

open urls.py  svae it as well(tell django where to send requests from the browser)


refresh your browser.
you are now able to add to do list and delete
congratulations
