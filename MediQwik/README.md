# MediQwik

MediQwik is a web-based healthcare management application developed using Django. It provides a centralized platform for healthcare-related services such as appointments, hospitals, emergency assistance, medical history, health surveys, medicine delivery, and insurance information.

## Technologies Used

- Python
- Django 5.1.6
- MySQL
- HTML5
- CSS3
- JavaScript
- Django Templates

## Features

- User registration and login
- User dashboard
- Hospital information
- Appointment management
- Emergency assistance
- Medical history
- Health surveys
- Medicine delivery
- Insurance information

## Setup

1. Create a virtual environment:
```bash
python -m venv venv
venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install django mysqlclient
```

3. Create a MySQL database named `MediQwik`.

4. Create a `.env` file from `.env.example` and add your own credentials.

5. Run migrations:
```bash
python manage.py makemigrations
python manage.py migrate
```

6. Start the server:
```bash
python manage.py runserver
```

Open `http://127.0.0.1:8000/`.

## Security

Sensitive credentials are loaded through environment variables. Do not commit `.env` or real passwords/secret keys to GitHub.

## Author

**Sai Vamshi K**  
B.Tech – Computer Science Engineering
