## django-online-polls
*******************************************************
The official tutorial project of django is really awesome! 
Tutorial link: https://docs.djangoproject.com/en/2.1/intro/tutorial01/

Recap for myself:
------------------
1. create git repo and activate virtual environment 
2. install django in the virtual environment
3. create project ($django-admin startproject project_name)
4. add any app ($py manage.py startapp app_name)
5. in the app, add the views and reference it in its urls.py
6. include the app's urls to the project's urls.py
7. run development server to check if the index page is available on http://localhost:8000/app_name
8. set up default db tables by $py manage.py migrate
9. create the models and add app to installed apps in the project's settings.py file  
10. create migrations for the newly added models by $py manage.py makemigrations polls
11. apply the migrations $py manage.py sqlmigrate polls 0001
 