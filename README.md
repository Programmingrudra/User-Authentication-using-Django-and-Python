# User-Authentication-using-Django-and-Python
Created a Simple rest API in Django  for User Authentication with JWT
This project is a Django REST API for User Authenticationn using JWT (JSON Web Token) in Python. It allows users to register, log in, and view dashboard while using JWT for token-based authentication.

Key Features:
1. User Registration - Allows new users to sign up with a username, email, and password.]
2. JWT Authentication - Issues access and refresh tokens upon successful login.
3. Login & Token Generation - Validates user credentials and returns JWT tokens.

TECHNOLOGIES USED:
------------------
-> Django REST Framework (DRF) - For building the REST API
-> Django Simple JWT - For handling JWT Authentication
-> SQLite - For user data storage.


PROJECT STRUCTURE:
-------------------
/djangojwt
│── myapp/
│   ├── views.py      # API views for authentication
│   ├── serializers.py # Serializers for user data
│   ├── urls.py       # Authentication-related API endpoints
│── settings.py       # Configurations for JWT, Redis, and database
│── urls.py           # Main project URLs
│── manage.py         # Django management script



CONCLUSION:
-------------
This Django REST API provides a secure and scalable suthentication system using JWT. It is ideal for modern web and mobile applications requiring token - based authentication.

