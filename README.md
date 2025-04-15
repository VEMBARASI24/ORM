# Ex02 Django ORM Web Application
## Date: 15.04.2025
## NAME:VEMBARASI.A.R
## REGISTER NUMBER:212224220120

## AIM
To develop a Django application to store and retrieve data from a Movies Database using Object Relational Mapping(ORM).

## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM
```
admin.py

from django.contrib import admin
from.models import Movie,MovieAdmin
admin.site.register(Movie,MovieAdmin)

models.py


from django.db import models
from django.contrib import admin
class Movie (models.Model):
    mid=models.IntegerField()
    mname=models.CharField(max_length=100)
    collection=models.IntegerField()
    year=models.IntegerField()
    rating=models.FloatField(max_length=10.0)


class MovieAdmin(admin.ModelAdmin):
    list_display=('mid', 'mname', 'collection', 'year', 'rating')

```


## OUTPUT
![Screenshot 2025-04-15 112649](https://github.com/user-attachments/assets/aabd5d62-ef0d-4d79-82c3-9970d3b2db0d)
![Screenshot 2025-04-15 112431](https://github.com/user-attachments/assets/2c809e16-d0ad-461d-b834-5ee1391bac99)




## RESULT
Thus the program for creating movies database using ORM hass been executed successfully
