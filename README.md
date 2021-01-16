Features 
=
- User Registration
- User Login & Logout
- User Profile
- Create, Update, Edit & Delete Posts
- Comments
- Search
- User Change Password
- Password Reset
- Customized admin panel

How To Use
=
## Clone project & Install Requirements
> Make sure you have already installed python and git.

$ git clone https://github.com/ImJac0b/django-blog.git && cd django-blog

## Migrate
```
$ cd src && python manage.py makemigrate 
$ python manage.py migrate
```
## Create Admin User
```
$ python manage.py createsuperuser
```
## Run Server
```
$ python manage.py runserver
```
> Enter on your browser http://127.0.0.1:8000/. You can login via admin in http://127.0.0.1:8000/admin or your url predefined 

