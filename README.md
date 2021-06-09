# A Basic Blog Project
This web application is a basic blog site using Dijango and CSS for styling. 
There is Admin access to ease the user to add titles and articles of their choosing. 
The Admin is able to allow other bloggers to post articles along with the published times

Through this project I've used the Anaconda Prompt with django, and Anaconda Spyder django environment for editing. 

## Quick start
1. Set up the Python development environment with `pip install Django`
2. Creat a directory `Blog Project` and navigate to it
3. Run the command in your shell to create the Django Project `django-admin startproject BlogProject`
4. Navigate to the outer `manage.py` script and run `cd blog` and `python manage.py startapp blog`
5. Open the `settings.py` and add your add name
6. Make migrations `python manage.py migrate` and run server `python manage.py runserver`
7. Create a superuser `python manage.py createsuperuser` and follow the prompts for a username and password
8. To open the admin site, open the brower `http://127.0.0.1:8000/admin`
9. Creat a new article and allow access to other bloggers if you have any.
10. Open another brower tab with `http://127.0.0.1:8000/` to see the main webpage.
