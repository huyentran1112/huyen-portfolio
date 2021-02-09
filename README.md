**Project name** : Personal portfolio

**Description** : This web app showcases all of my data science projects

**Installation** : The steps below serves as a guide to clone the project repository and run in a local machine:

1. Download the Git repository and go to the main directory where manage.py is.
2. Create a virtual environment by typing 'python3 -m venv venv' on the command line.
3. Activate the virtual environment. Type 'source venv/bin/activate' on the command line.
4. Install Django. Type 'pip install Django' on the command line.
5. Run python manage.py make migrations.
6. Run python manage.py migrate.
7. Run python manage.py createsuperuser (enter your email and set your password).
8. Run python manage.py runserver.

**Usage** : I have built a web app with the following features:
* a fully functioning blog: In this application, I create, update, and delete blog posts. Posts will have categories that can be used to sort them. Finally, users will be able to leave comments on posts.
* a portfolio of my work: I will showcase my data science projects here. I have built a gallery style page with clickable links to projects that I have completed.
