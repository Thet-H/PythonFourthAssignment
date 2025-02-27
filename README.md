# 📚 Student Management System
A simple Student Management System built with Django. This project allows you to add, view, edit, and delete student records through a user-friendly web interface.


## ✨ Features
- ✅ Add Student
- ✅ Edit Student Information
- ✅ Delete Student Record
- ✅ View Students Lists
- ✅ Simple & Clean UI
## ⚙️ Technologies Used

- 🐍 Python 3.13
- 🌐 Django 5.1
- 🎨 HTML & CSS

## 📂 Folder Structure

```
student_project/
    ├── student_app/
    │   ├── migrations/
    │   ├── templates/
    │   │   ├── student_app/
    │   │   │   ├── student_list.html
    │   │   │   ├── add_student.html
    │   │   │   ├── edit_student.html 
    │   ├── __init__.py
    │   ├── admin.py
    │   ├── apps.py
    │   ├── models.py
    │   ├── views.py
    │   ├── urls.py
    │   ├── forms.py
    │
    ├── student_project/
    │   ├── __init__.py
    │   ├── asgi.py
    │   ├── settings.py
    │   ├── urls.py
    │   ├── wsgi.py
    │
    ├── manage.py
    └── README.md
```
# 🚀 How to Run the Project
### 1.clone the repository
```
git clone https://github.com/Thet-H/student-management.git
cd student-management
```
### 2.Create Virtual Environment 
```
python -m venv venv
source venv/bin/activate
```
### 3.Run Migrations
```
python manage.py makemigrations
python manage.py migrate
```
### 4.Start Development Server
python manage.py runserver
### 5.Access the App
Open your browser and visit:
👉 http://127.0.0.1:8000








