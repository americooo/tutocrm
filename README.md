# 📝 Tutocrm

A CRM project built on Django. 
This project is designed to automate user management, system settings, and other business processes.

## 🚀 Technologies

- **Python 3.13**
- **Django**
- **SQLite3 / PostgreSQL** (depending on configuration)
- **Bootstrap / CSS**

## ⚙️ Installation and Startup

1. Clone the repository:
```bash
git clone https://github.com/americooo/tutocrm.git
cd tutocrm
```

2. Create and activate the virtual environment:
```
python -m venv venv
venv\Scripts\activate
```
3. Install the required packages:
```
pip install -r requirements.txt
```
4. Run the migrations and start the server:
```
python manage.py migrate
python manage.py runserver
```
Open in browser:
```
http://127.0.0.1:8000
```
5.📂 Project Structure

accounts/ — user authentication

settingsapp/ — system settings

templates/ — HTML templates

static/ — CSS, JS and images
