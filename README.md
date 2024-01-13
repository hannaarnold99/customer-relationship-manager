# Customer Relationship Manager

This application was created using Django, HTML5, CSS, and Bootstrap. It's purpose is to display a list of customers from a database, and the admin can view each customer's record, update the record, or delete the record from the database. 

<img width="1437" alt="crm_index jpeg" src="https://github.com/hannaarnold99/customer-relationship-manager/assets/145307349/3a5b0370-1a3f-428e-b8e6-8adbf5e4ddd0">

<img width="1437" alt="crm_add jpeg" src="https://github.com/hannaarnold99/customer-relationship-manager/assets/145307349/b0f8622a-8d1f-46a5-a592-e410a93fd872">



## Installation
#### *Python must be installed on your device.*

### 1. Create Virtual Environment
From the **root** directory, run:
```
python -m venv venv
```

### 2. Activate Virtual Environment
From the **root** directory, run:
```
source venv/bin/activate
```

### 3. Install Dependencies
From the **root** directory, run:
```
pip install -r requirements.txt
```

### 4. Migrations
From the **root** directory, run:
```
python manage.py makemigrations
```
```
python manage.py migrate
```

### 5. Create Admin Account
From the **root** directory, run:
```
python manage.py createsuperuser
```
Enter a username, email, and password.

### 6. Run the Application
From the **root** directory, run:
```
python manage.py runserver
```

### 7. View the Application
#### Go to http://127.0.0.1:8000/ to view the application.
#### Go to http://127.0.0.1:8000/admin to view Django's admin interface.
