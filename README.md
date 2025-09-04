# Meal-Plannner

Meal Planner App
Project Status
Status: In Development (MVP)

This project is a full-stack Progressive Web App (PWA) designed to help users plan their meals efficiently. The application is built to be responsive and accessible on both desktop and mobile devices.

Features
User Authentication: Secure user accounts managed via Google OAuth.

Recipe Database: A large, searchable database of recipes from the MealDB API.

Meal Planning Calendar: An intuitive calendar interface where users can drag and drop or add recipes to specific days.

Shopping List Generator: Automatically generates a consolidated grocery list from the week's planned meals.

Technologies Used
Frontend
JavaScript: For the application's logic.

React: A JavaScript library for building the user interface.

HTML/CSS: For the app's structure and styling.

Backend
Python: The primary programming language for the server-side logic.

Flask: A lightweight Python web framework used to build the RESTful API.

PostgreSQL: A powerful and open-source relational database used to store user data and meal plans.

Getting Started
To get a local copy up and running, follow these steps.

Prerequisites
Python 3.x

Node.js & npm

PostgreSQL

A Google Cloud account for API keys

Installation
Clone the repository:

Bash

git clone https://github.com/YourGitHub/Meal-Planner.git
cd Meal-PlannerRepo
Set up the Backend:



# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt
Configure Database:

Ensure your PostgreSQL server is running.

Update the database connection string in your configuration file (config.py).

Run the database migration scripts to create the tables.

Set up the Frontend:

Bash

# Navigate to the frontend directory
cd frontend

# Install dependencies
npm install
Run the application:

Start the backend server in one terminal.

Start the frontend server in another terminal.

Contact
If you have any questions or feedback, please contact me at dhyan.sur@gmail.com
