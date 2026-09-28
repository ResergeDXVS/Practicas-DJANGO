# 🐍 Practicas-DJANGO

## 📖 Description
A collection of Django practice exercises completed while learning backend development with Python. Each numbered folder holds one exercise, progressing from the framework basics to templates, building REST APIs with Django REST Framework (ViewSets, pagination), authentication, and web scraping.

## 🛠️ Technologies used
- **Main language:** Python
- **Framework:** Django, Django REST Framework
- **Topics covered:** Django templates, REST APIs, ViewSets, pagination, authentication, web scraping
- **Tools:** pip, virtual environments (`venv`)

## 📂 Project structure
Each folder is a self-contained practice:

| Folder | Topic |
| --- | --- |
| `Practica51` | Django practice |
| `Practica52` | Django practice |
| `Practica53` | Django practice |
| `Practica54` | Django practice |
| `Practica59` | Django practice |
| `Practica60_DjangoTemplates` | Django templates |
| `Practica61_Intro_a_REST` | Introduction to REST |
| `Practica62_ViewSet` | ViewSets |
| `Practica63_Paginacion_Django_REST` | Pagination in Django REST Framework |
| `Practica64_Autenticacion_Django` | Authentication in Django |
| `Practica65_WebScraping` | Web scraping |

## 🚀 Getting started

### Prerequisites
- Python 3 and pip installed

### Installation
```bash
git clone https://github.com/ResergeDXVS/Practicas-DJANGO.git
cd Practicas-DJANGO
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### Run a practice
Move into the practice folder you want to try, install its dependencies and start the development server:
```bash
cd Practica60_DjangoTemplates
pip install django  # plus any other packages the practice needs
python manage.py migrate
python manage.py runserver
```
Then visit [http://127.0.0.1:8000](http://127.0.0.1:8000).

> ℹ️ Each practice may have its own dependencies (for example, `djangorestframework` for the REST practices), so check the imports in each folder before running it.

## 📌 Status
Ongoing collection of practice exercises.

## 👤 Author
[ResergeDXVS](https://github.com/ResergeDXVS)
