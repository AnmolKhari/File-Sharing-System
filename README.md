# File-Sharing System

Welcome! This repository provides an easy-to-use setup guide for running the application locally.
![Screenshot (2854)](https://github.com/user-attachments/assets/5a0ecb78-49b9-400a-b4d9-1f00da6eaf78)

## Git Repository

The project can be found at: [File-Sharing System GitHub Repository](https://github.com/AnmolKhari/File-Sharing-System)

## Setup Guide

Follow these steps to set up the project locally:

1.**The setup process handles all migrations.**
run: python manage.py makemigrations
run: python manage.py migrate
run: python manage.py runserver

2. **Test the API Endpoints:**
   A. User Signup (POST Request)
   ```url
   http://127.0.0.1:8000/api/signup/
 B.User Login (POST Request)
   ```url
   http://127.0.0.1:8000/api/login/
C. Upload File (POST Request)
   ```url
            http://127.0.0.1:8000/api/upload/
  D. Download File (GET Request)
   ```url
            http://127.0.0.1:8000/api/download/

3. **Run the Server**
   python manage.py runserver
