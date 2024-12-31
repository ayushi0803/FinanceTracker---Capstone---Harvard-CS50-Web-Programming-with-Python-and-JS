# Finance Tracker

This is a simple yet powerful web application designed to help you keep track of your finances. Whether you're managing your savings, monitoring your expenses, or simply organizing your finances, **Finance Tracker** ensures that you have full visibility over your spending and saving habits.

Finance Tracker is my final project for **CS50’s Web Programming with Python and JavaScript** course. It combines a clean and simple user interface with powerful backend logic to keep track of your total amount and expenses, ensuring financial clarity.

## Distinctiveness and Complexity

Finance Tracker is a unique and complex project that satisfies the requirements for a web application built with Django and JavaScript. Here’s how it stands out:

1. **Backend with Django**: 
   - The application uses Django models to manage users, expenses, and total amounts. 
   - Three models are employed:
     - `User`: Manages user information by extending Django’s `AbstractUser`.
     - `Expense`: Stores records of all user expenses, including details like amount, description, date, and category.
     - `TotalAmount`: Keeps track of the user's current balance.
   
2. **User Authentication**: 
   - Implemented server-side authentication ensures that each user has a unique login and is able to securely track their finances.

3. **JavaScript Integration**: 
   - On the client side, JavaScript is used to ensure a smooth user experience. By dynamically adding money and recording expenses without reloading the page, the app provides a seamless experience.

4. **Mobile-Responsive Design**: 
   - The website is fully responsive, ensuring a smooth user experience across all devices, whether desktop, tablet, or mobile.

The combination of these backend and frontend technologies ensures a robust, scalable, and user-friendly application, fulfilling all the criteria for a capstone project.

## Overview

The following files make up the application:

| Filename                        | Description |
|----------------------------------|-------------|
| `tracker/models.py`              | Contains Django models for User, Expense, and TotalAmount. |
| `tracker/views.py`               | Contains the logic for views and handling requests. |
| `tracker/urls.py`                | Lists all the URLs and APIs used in the application. |
| `tracker/static/index.js`        | JavaScript code for handling add-money and add-expense features. |
| `tracker/static/ExpenseView.js`  | JavaScript for loading and displaying expenses on the track record page. |
| `tracker/static/style.css`       | CSS for styling the web pages. |
| `tracker/static/about.css`       | CSS for animations on the About page. |
| `tracker/templates/`             | HTML templates for various pages like index, about, and login. |

## Built With

- [![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/docs)
- [![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)](https://docs.djangoproject.com/en/4.1/)
- [![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)](https://www.sqlite.org/index.html)
- [![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org/)

## How to Run

To run the Finance Tracker locally:

1. Clone or download the repository.
2. Open a terminal and navigate to the folder containing `manage.py`.
3. Ensure you have Python and Django installed.
4. Install dependencies using:
   ```bash
   pip install -r requirements.txt
   ```
5. Run the Django development server:
   ```bash
   python manage.py runserver
   ```
6. Open your browser and go to:
   ```bash
   127.0.0.1:8000
   ```

## How to Use

1. **Login or Register**:
   - Go to the homepage and log in to your account. If you're a new user, you can register by clicking the “Register” link at the bottom.

2. **Add Money**:
   - Once logged in, you can add money to your total amount. Simply enter an amount and click to add it.

3. **Add Expense**:
   - You can record an expense by specifying the amount, name, description, and date. Note that you can only add expenses if you have enough funds in your total amount.

4. **Track Expenses**:
   - View all your recorded expenses on the track record page. Expenses are listed with their name, amount, description, and date.

## Acknowledgements and References

- [Django Documentation](https://docs.djangoproject.com/en/)
- [CS50 Web Programming with Python and JavaScript](https://cs50.harvard.edu/web/)
- [Bootstrap](https://getbootstrap.com/)
- [FontAwesome](https://fontawesome.com/)
- [CodePen](https://codepen.io/)
