# Student-Management-Django

* A web application for student management
* Add new student with information like roll number, name, department etc.
* View all students
* Edit student information
* Delete student

 <br>
___

Project is created with: 
* Django 4
* Bootstrap 5


## How to run this app on your machine? <br>
### 1. Extract and open the project, then install the requirements.txt using pip
```
pip install -r requirements.txt
```
### 2. Generate a secret key from [djecrety.ir](https://djecrety.ir/) and create a .env file under django_project directory
```
MY_SECRET_KEY = 'Your Secret Key'
DATABASE_URL = Your Database Location Path
```

### 3. For migrations, type this on your terminal
```
python manage.py makemigrations
python manage.py migrate
```

### 4. Run the server using the following command
```
python manage.py runserver
```

Your Django project is **LIVE** now on your localhost. <br>
Open your browser and type **127.0.0.1:8000** on address bar.<br>
<br>
