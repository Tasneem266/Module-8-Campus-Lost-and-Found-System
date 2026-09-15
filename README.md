" " "
Campus Lost & Found System

A Django-based web application for managing lost and found items on campus.

Features :

- User Authentication (Register, Login, Logout)
- Create Lost/Found Reports
- View All Reports with Search and Filter
- Edit and Delete Own Reports
- Mark Reports as Resolved
- Request Logging Middleware
- Django Messages System

Project Structure :

campus_lost_found/
├── manage.py
├── db.sqlite3
├── requirements.txt
├── README.md
├── campus_lost_found/
│ ├── init.py
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
├── lost_found/
│ ├── init.py
│ ├── admin.py
│ ├── apps.py
│ ├── models.py
│ ├── views.py
│ ├── urls.py
│ ├── forms.py
│ ├── middleware.py
│ └── migrations/
│ └── init.py
└── templates/
├── base.html
├── home.html
├── register.html
├── login.html
├── report_list.html
├── report_detail.html
├── report_form.html
├── my_reports.html
├── report_confirm_delete.html
└── resolve_confirm.html

" " "
