# Django ORM Web Application

## AIM :

To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

![](/DJANGOO.png)


## DESIGN STEPS

### STEP 1:

Clone the repository to theia ide and Start a new app inside the project folder

### STEP 2:

Type the appropriate code for your table and provide appropriate data types to the columns

### STEP 3:

Create a report about your project in readme.md file and upload the django.orm.app folder to your remote repository


## PROGRAM :

from django.db import models

from django.contrib import admin
```
players(models.Model):
name=models.Charfield(max_length=100)
age=models.IntegerField()
strikerate=models.IntegerField()
runs=models.runs()

players(admin.ModelAdmin):

list_display=('name,'age','strikerate','runs')
```
## OUTPUT :

![](/djan.png)

## RESULT :

Hence we developed a Django application to store and retrieve data from a database using Object Relational Mapping (ORM)
