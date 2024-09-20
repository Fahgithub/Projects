# College-ERP
A college management system developed using the Django framework, facilitating interactions between students and teachers. Key features include attendance tracking, marks management, and timetable scheduling.

## Installation

Ensure Python and Django are installed on your system:


```bash
pip install django
```

```
pip install -r requirements.txt
 ```

## Usage

Go to the College-ERP folder and run

```bash
python manage.py runserver
```

Then, open your browser and visit **http://127.0.0.1:8000/.**




## Login
Both students and teachers share a common login page.
Usernames are their names, and the default password for all users is ** 'project123' **.



Example usernames:  
student- 'Student'  
teacher- 'Teacher'  

You can access the django admin page at **http://127.0.0.1:8000/admin** and login with username 'admin' and the above password.

Also a new admin user can be created using

```bash
python manage.py createsuperuser
```

## Users

New students and teachers can be added through the admin page. A new user needs to be created for each. 

The admin page is used to modify all tables such as Students, Teachers, Departments, Courses, Classes etc.


This is present in Django Admin -> Attendance (http://127.0.0.1:8000/admin/info/attendanceclass/).  
Start Date: Start Date of Attendance period  
End Date: End Date of Attendance period

This will delete all present attendance data and create new attendance objects for the given time range. 
