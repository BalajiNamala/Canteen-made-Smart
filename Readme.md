# Smart Canteen

## Description
Online ordering offers a range of benefits, including an interactive UI, wider product
selection, and access to product reviews for informed choices. Along with this, our project
addresses this issue by incorporating a sales prediction feature that enables managers to
forecast demand for food items with precision.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Technologies Used](#technologies-used)
- [Additional scope](#Additional-scope)

## Features
- Online ordering
- View daily, weekly, and monthly sales
- Predictions of food items in high demand
- Up-to-date menu
- Online payments
- Ratings and feedback

## Installation
1. **Navigate to the project directory:**
cd Canteen/

2. **Create a virtual environment:**
python -m venv venv_name

3. **Activate the virtual environment:**
- On Windows:
  ```
  venv_name\Scripts\activate
  ```
- On macOS and Linux:
  ```
  source venv_name/bin/activate
  ```
5. **Install dependencies:**
pip install -r requirements.txt

6. **Perform migrations:**
python manage.py migrate

7. **Run the development server:**
python manage.py runserver 7100

8. **Access the application:**
Open a web browser and go to `http://localhost:7100/` or the specified URL.

## Usage
[Provide usage instructions or additional setup/configuration]

## Folder Structure
canteen/
├── webapp/
│   ├── media/
|   ├── migrations/
│   ├── templates/
│   ├── static/
│   ├── admin.py
|   ├── apps.py
|   ├── Freq.py
|   ├── models.py
|   ├── svm_model.sav
|   ├── SVMPrediction.py
|   ├── urls.py
|   ├── views.py
├── manage.py
└── requirements.txt




## Technologies Used
- **Django:** Web framework for building web applications in Python.
- **Python:** Primary programming language used in Django development.
- **HTML/CSS/JavaScript:** Front-end technologies for creating website layouts and interactivity.
- **Database Systems:** PostgreSQL/MySQL for data storage.
- **Machine Learning Libraries:** Scikit-learn, TensorFlow, PyTorch, etc., for developing machine learning models.
- **Git:** Version control system for managing project codebase.
- **Virtual Environments:** `virtualenv` or `conda` for creating isolated Python environments.


## Additional scope
- **Allergen Information:** Include detailed information about allergens present in food items for students with allergies.
- **Integration with Social Media:** Allow users to share their orders or experiences on social media platforms.
