# 🍎 CalorieCounter - Daily Calorie Estimator & Tracker

Welcome to CalorieCounter! This is a web application built with Python to estimate the number of calories a person needs to consume each day. This tool also helps users keep track of their daily calorie consumption.

# ✨ Features

* **Interactive Dashboard:** A dashboard where the user can view the required calories for her/him and the consumed calories daily.
* **User Authentication:** Built-in views for Login (username/email and password) and Registration (username, email, password, confirm password) pages.
* **Calorie Management:** Features Django forms to take input for user metrics (Name, Age, Gender, Height, Weight etc.) and daily consumed calories (Item name, Calorie consumed).
* **BMR Calculation:** Calculates base calories utilizing specific formulas for both males and females.
* **Health Guidelines:** This calculator can also provide some simple guidelines for gaining or losing weight.

# 🛠️ Technologies Used

* **Frontend:** HTML, CSS, Django Templates
* **Backend:** Python, Django Framework
* **Database:** SQLite (Default)

# 📋 Project Requirements

**Job 1: Develop a Calorie Counter** Develop a Calorie Counter that can be used to estimate the number of calories a person needs to consume each day. Users can also keep track of how many calories he/she needs and how much he/she consumes in a day.

**Job Specification information:** 1. Create a new Django project named Name_ID_CaloryCounter and a Calorie Counter app.
2. Define your Calorie Counter models.
3. Create views for Login (username/email and password) and Registration (username, email, password, confirm password) pages.
4. Create a django-form to take input Name, Age, Gender, Height, Weight etc.
5. Create a Django form to take input daily consumed calories (Item name, Calorie consumed).
6. Create a dashboard where the user can view the required calories for her/him and the consumed calories daily.
7. Define URL Patterns and configure project-level URLs.
8. Implement the required Function and Logic in the view.py file.

**Additional Job Specification information:** * a. Create a new Django project (Naming Convention: Name_ID_CaloryCounter).
* b. Run migration to create the data tables.
* c. Create a super user (username: admin, password: 1234).
* d. Register your models to the Django admin.

---

# Install the app now!
## 🚀 Step-by-Step Setup Guidelines

Follow these instructions to get a local copy of the project up and running on your machine.

### Prerequisites

* Make sure you have Python installed on your system. You can download it from python.org.
* Basic knowledge of using the command line or terminal.

**1. Clone the repository**
Open your terminal and run the following command to clone the project:
`git clone https://github.com/nazmulalibiswas/CalorieCounter.git`

**2. Navigate to the project directory**
`cd nazmulalibiswas_2026_CalorieCounter`

**3. Create a Virtual Environment** (It is recommended to use a virtual environment to manage dependencies.)
`python -m venv env`

**4. Activate the Virtual Environment**
*(On Windows:)*
`env\Scripts\activate`

*(On MAC/Linux:)*
`source env/bin/activate`

**5. Install Dependencies** (Install all the required Python packages):
*(Ensure you have created a `requirements.txt` file before running this, or install Django manually using `pip install django`)*
`pip install -r requirements.txt`

**6. Apply Database Migrations** (Set up the database tables by running the following command):
`python manage.py migrate` 

**7. Create a Superuser** (Optional but recommended - To access the Django Admin panel, create an admin account):
`python manage.py createsuperuser` 

**8. Run the Development Server** (Finally, start the Django development server):
`python manage.py runserver`

**9. Open the Web App**
Open your favorite web browser and go to the following URL:
`http://127.0.0.1:8000/`

---

## 🔑 Quick Info for Database Access

* **Admin Login:** Username: admin | Password: 1234 

---

## 🤝 Contributing

Contributions are always welcome! Feel free to fork this repository, create a new branch, and submit a pull request.

## 👤 Author

**Md. Nazmul Ali Biswas**
Fullstack Engineer & Tech Enthusiast
Contact: nazmulalibiswas.dev@gmail.com

## 📬 Contacts

* **Web:** www.nazmulalibiswas.com
* **Email:** nazmulalibiswas.dev@gmail.com