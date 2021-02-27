### Requirments to Get Started
 <p>✔ Python V3. </p>
 <p>✔ Virtualenv - to house all python library that you need (Recommended).  </p>
 
 #### Installation
 -   Python
 -   virtualenv using pip install virtualenv.
   -  env to check if the virtual env creatred.
   
  [Installation_Video_Tutorial](https://www.youtube.com/watch?v=IMG4r03G6g8) 
 
--- 
#### Creating a project
  - `mkdir HQAForm` (its a folder name `HQAForm` and it can be any names) create a folder that holds env and Django code.
  - cd into that directory. 
  - Create virtual enviroment using `virtualenv env` command inside that folder.
  - activate my Virtual Python Environment For Mac OS    
       - source env/bin/activate.
  - Install Django  `pip install django.` 
  - `run django-admin startproject mysite`.
    - This will create a `mysite` directory in your current directory.
  
  - Run ls
      -  You should see your projrct name listed.
   
  - Let’s verify your Django project works. 
   - `cd  mysite` , (manage.py  inside that folder) Change into the outer mysite directory, if you haven’t already,
  -  and run the following commands
    -   `python manage.py runserver`
    -   By default, the runserver command starts the development server on the internal IP at port 8000.


### activate my Virtual Python Environment For Mac OS    
    - source env/bin/activate    

### Install Django
  - pip install django.

### To create a Project (Inside Env)
  - django-admin startproject dj 

---


### Create a App

 ▶ To create a new App inside Django project use the startapp command `python manage.py startapp appname'.
 ▶ First,go to main App (project) --> setting.py --> Installed_Apps (What apps are installed on this project) --> add  your new app/appname to the list.
 ▶ Inorder to create a view in Django, we are going to define a function that representing my. view.
    ▶ request arquement represent an http request that the user made in order. 

### For each new APP , we need to do the following:
 ▶ Add the new appName to setting.py file.
   ▶ main App (project) --> setting.py --> Installed_Apps (What apps are installed on this project) --> add  your new app/appname to the list.
 ▶ Create a view and each view represent a method. 
   ▶ Like def index (request): .........   
 ▶ create a `urls.py` file for this particular app.
   ▶ urlpatterns=[] list of all the allowable URLs that can be accessed fo this particular app.
   ▶ path (""), views.index,name="index"). ===>a view called index


#### Files
<li> `urls.py` sort of table of contents for our web Application</li>
<li>`view.py` something user want to see </li>
<li> </li>
<li> </li>
<li> </li>
