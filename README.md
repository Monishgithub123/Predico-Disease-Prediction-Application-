# Predico-Disease-Prediction-Application-

Powered by Python , Django and PostgreSql

## Overview  
This project is designed to predict diseases based on symptoms provided by the user. It utilizes a machine learning model trained on a dataset and is integrated with a Django backend. PostgreSQL is used as the database to store application data.

---

## Prerequisites  
Before setting up the application, ensure the following are installed on your system:  
1. **PostgreSQL**: A robust relational database management system.  
2. **pgAdmin**: A GUI tool for managing PostgreSQL databases.  

---

## Installation Steps  

### 1. **Database Setup**  
- Create a new database instance in PostgreSQL and name it `predico`.  
- You can use pgAdmin for this step.

### 2. **Environment Setup**  
- Create a new virtual environment (recommended) to isolate dependencies:  
  ```bash
  python -m venv venv
  source venv/bin/activate    # For Linux/Mac
  venv\Scripts\activate       # For Windows


3. Install Dependencies
Install all required dependencies by running:

pip install -r requirements.txt

4. Database Migrations
Apply the database migrations:

python manage.py makemigrations
python manage.py migrate

5. Run the Development Server
Start the Django development server:

python manage.py runserver


6. Navigate to the application in your browser:
http://127.0.0.1:8000/





7. Dataset Used
The machine learning model is trained using the following dataset:
Disease Prediction Dataset


Project Owner
[Monish Yedlewar]

Email: yedlewarmonish@gmail.com
Github: https://github.com/Monishgithub123


Future Scope
[Adding more advanced machine learning algorithms.]
[Enhancing the user interface for better usability.]
[Deploying the application for public access.]
