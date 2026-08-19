# Django Blog Project

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-663399?style=for-the-badge&logo=css&logoColor=white)

A fully functional web application built while learning backend web development with Python and Django. This project implements key web concepts including dynamic routing, templates, ORM databases, and user authentication systems.

## Purpose

The purpose of the project was to learn Django, and it serves as a practical milestone transitioning my skills from basic Python scripting into full-stack web application development.

---

## Tutorial Attribution

This project was built following the **Python Django for Beginners Full Course** by [Dave Gray](https://github.com/gitdagray). 
*   **Original Tutorial Repository:** [gitdagray/django-course](https://github.com/gitdagray/django-course)
*   **Topics Covered:** Apps, Templates, Models, Migrations, ORM, Admin, User Authorization, and Custom Forms

---

## How to Run This Project Locally

Follow these sequential steps to set up and run the application on your local machine.

### Prerequisites
Make sure you have Python 3 installed. You will also need the terminal commands listed below.

### 1. Clone the Repository
Clone your project to your local directory and navigate inside it:
```bash
git clone https://github.com/kshuang04/Django-Blog-Web-App.git
cd myproject
```

### 2. Set Up a Virtual Environment
Create and activate an isolated Python environment:
*   **macOS / Linux:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```
*   **Windows (Command Prompt):**
    ```bash
    python -m venv venv
    venv\Scripts\activate
    ```

### 3. Install the Project Dependencies
Use the `requirements.txt` file to instantly download all required packages (including Django and python-dotenv):
```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables
Because sensitive configuration data is hidden from GitHub, you must create a local configuration file:
1. Create a file named `.env` in the root folder (same level as `manage.py`).
2. Add your local configuration values inside it:
   ```env
   DJANGO_SECRET_KEY="your-django-secret-key"
   ```

### 5. Run Database Migrations
Set up your local SQLite database structure by running:
```bash
python manage.py migrate
```

### 6. Start the Local Server
Launch the development server:
```bash
python manage.py runserver
```

Open your browser and navigate to `http://127.0.0` or `localhost` to see the running web app.

---

## Tech Stack Used

*   **Language:** Python
*   **Framework:** Django 
*   **Database:** SQLite (Local)
*   **Frontend:** HTML, CSS, JavaScript
