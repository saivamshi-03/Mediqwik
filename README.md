# MediQwik



MediQwik is a web-based healthcare management application developed using Django. It provides a centralized platform for users to access healthcare-related services such as hospitals, appointments, emergency assistance, medical history, health surveys, medicine delivery, and insurance information.



## Features



- User registration and login

- User dashboard

- User profile management

- Hospital listing and information

- Appointment management

- Emergency assistance

- Medical history

- Health surveys

- Medicine delivery

- Insurance information

- Responsive healthcare-focused interface



## Technologies Used



### Frontend

- HTML5

- CSS3

- JavaScript

- Django Templates



### Backend

- Python

- Django



### Database

- MySQL



## Project Structure



```text

MediQwik/

│

├── manage.py

├── MediQwik/

│   ├── settings.py

│   ├── urls.py

│   ├── asgi.py

│   └── wsgi.py

│

├── accounts/

│   ├── migrations/

│   ├── models.py

│   ├── views.py

│   ├── urls.py

│   └── admin.py

│

├── templates/

│   ├── index.html

│   ├── login.html

│   ├── register.html

│   ├── dashboard.html

│   ├── appointments.html

│   ├── emergency.html

│   ├── hospitals.html

│   ├── hospital\_list.html

│   ├── medicalhistory.html

│   ├── healthsurveys.html

│   ├── medicinedelivery.html

│   └── insurance.html

│

└── static/

&#x20;   └── images/

```



## Installation and Setup



### 1. Clone the repository



```bash

git clone https://github.com/saivamshi-03/Mediqwik.git

cd Mediqwik

```



### 2. Create a virtual environment



```bash

python -m venv venv

```



Activate it on Windows:



```bash

venv\\Scripts\\activate

```



### 3. Install dependencies



```bash

pip install django mysqlclient

```



### 4. Configure the database



Create a MySQL database and configure the required database environment variables.



Do not add passwords, secret keys, API keys, or other sensitive credentials to GitHub.



### 5. Run migrations



```bash

python manage.py makemigrations

python manage.py migrate

```



### 6. Start the development server



```bash

python manage.py runserver

```



Open the application at:



```text

http://127.0.0.1:8000/

```



## Main Modules



| Module | Description |

|---|---|

| Registration | Allows users to create accounts |

| Login | Handles user authentication |

| Dashboard | Main user interface |

| Hospitals | Displays hospital information |

| Appointments | Appointment-related functionality |

| Emergency | Emergency-related services |

| Medical History | Medical history information |

| Health Surveys | Health survey functionality |

| Medicine Delivery | Medicine delivery functionality |

| Insurance | Insurance-related information |



## Future Enhancements



- Online doctor consultation

- Real-time appointment availability

- Payment gateway integration

- Email and SMS notifications

- Doctor search and filtering

- Hospital search and filtering

- AI-based healthcare recommendations

- Role-based access for patients, doctors, and administrators

- Production deployment



## Project Status



MediQwik is currently under development. The frontend interface and core Django application structure have been implemented, with additional backend functionality and enhancements planned.



## Author



**Sai Vamshi K**



B.Tech – Computer Science Engineering

