My Simple boilerplate django!

##Project bootstrap  
1- 

    django-admin startproject theprojectname  --template=https://github.com/lffsantos/boilerplatedjango/archive/master.zip

2-  
    
    pip install -r requirements.txt
    

3- open file:

theprojectname/wsgi.py change line 14  
```
os.environ.setdefault("DJANGO_SETTINGS_MODULE", "project_name.settings")  
```
to  
```
os.environ.setdefault("DJANGO_SETTINGS_MODULE", "theprojectname.settings")  
```

