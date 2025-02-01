# todo-django
A simple todo app built with django

![todo App](https://drive.google.com/file/d/1grqctB_OQGVBfnpgDE5cAgitz-xbcGfc/view?usp=sharing)
### Setup
Clone the repository
```
git clone https://github.com/DevanshArora312/todo-django.git
```
Go to the cloned repo directory and run the following command

```
python manage.py makemigrations
```

This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command
```
python manage.py migrate
```

Create an admin user to run this App. On the terminal, type the following command and provide username, password and email for the admin user
```
python manage.py createsuperuser
```

Now start the server by following command

```
python manage.py runserver
```

Once the server is hosted, head over to http://127.0.0.1:8000/todos for the App.
