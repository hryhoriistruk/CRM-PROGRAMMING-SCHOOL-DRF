# CRM Programming School (DRF)

This project is a CRM system for a programming school, built on Django Rest Framework (DRF). 
It allows managing students, courses, teachers, and class schedules.

## Features
- **User management** (students, teachers, administrators)
- **CRUD operations** for courses, lessons, and schedules
- **Authentication and authorization** via DRF
- **API for client interactions**

## Technologies
- Python 3
- Django 4
- Django Rest Framework
- PostgreSQL
- Docker

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/hryhoriistruk/CRM-PROGRAMMING-SCHOOL-DRF.git
   cd CRM-PROGRAMMING-SCHOOL-DRF
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Apply migrations:
   ```bash
   python manage.py migrate
   ```
4. Run the server:
   ```bash
   python manage.py runserver
   ```

## Usage
The API is available at: `http://127.0.0.1:8000/api/`

## Docker
To run the project in Docker, execute:
```bash
docker-compose up --build
```

