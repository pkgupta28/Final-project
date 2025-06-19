# Final-project

# CommunApp – A Social Community Platform

**CommunApp** is a full-stack web platform designed to bring like-minded individuals together. Users can create and join communities, post content, comment, and engage in discussions around shared interests.

## 🌟 Features

- User registration, login, and profile management  
- Community creation, discovery, and membership  
- Posting, commenting, and real-time discussions  
- Media uploads (profile and post images)  
- MySQL-backed backend with Django REST APIs  
- Responsive, user-friendly interface

## 🛠️ Tech Stack

| Layer      | Tools                                 |
|------------|----------------------------------------|
| Frontend   | Next js., Tailwind Css    |
| Backend    | Python, Django, Django REST Framework  |
| Database   | MySQL                                  |
| Media      | Django media/static file handling      |
| Environment| Virtual Environment (`venv`)           |

## 🚀 Getting Started

 Clone the repository
```bash
git clone https://github.com/your-username/CommunApp.git
cd CommunApp

Set up virtual environment
python -m venv venv
venv\Scripts\activate      # On Windows
source venv/bin/activate  # On macOS/Linux

Install dependencies
pip install -r requirements.txt



Configure MySQL in settings.py
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'your_db_name',
        'USER': 'your_username',
        'PASSWORD': 'your_password',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}



Run Migrations and Launch Server

python manage.py makemigrations
python manage.py migrate
python manage.py runserver












