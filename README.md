AI-Enhanced Car Pooling Application
🚗 Project Overview

An AI-powered Car Pooling System developed using Flask and Machine Learning to provide intelligent ride recommendations and booking management. The system allows users to register, post rides, search rides, book rides, and receive ride recommendations using the K-Nearest Neighbors (KNN) algorithm.

✨ Features
User Features
User Registration and Login
Secure Authentication using Flask-Login
Post New Rides
Search Available Rides
Book Rides
View Dashboard
Rate Drivers
Email Notifications
AI Features
KNN-based Ride Recommendation
Ride Match Prediction
Intelligent Ride Compatibility Analysis
📋 Technology Stack
Frontend
HTML
CSS
JavaScript
Jinja2 Templates
Backend
Python Flask
Flask-Login
Flask-Mail
Flask-SQLAlchemy
Database
SQLite
Database File: instance/carpool.db
Machine Learning
Scikit-Learn
K-Nearest Neighbors (KNN)
Pandas
NumPy
Joblib
📁 Project Structure
AI-CarPooling-Project-main/
│
├── app.py
├── requirements.txt
├── runtime.txt
├── Procfile
├── .env
│
├── instance/
│   └── carpool.db
│
├── models/
│   ├── user_model.py
│   ├── ride_model.py
│   ├── booking_model.py
│   ├── notification_model.py
│   └── rating_model.py
│
├── ML/
│   ├── dataset.csv
│   ├── ride_match_model.pkl
│   └── training scripts
│
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── search_rides.html
│   └── ...
│
├── static/
│   ├── css/
│   └── js/
│
└── __pycache__/
🤖 Machine Learning Module

The application uses the K-Nearest Neighbors (KNN) algorithm to predict ride matching levels.

Features Used
Pickup Location
Destination
Time Slot
Available Seats
Price
Driver Rating
Vehicle Type
Output Categories
High Match
Medium Match
Low Match
🗄 Database Tables
Users
Rides
Bookings
Notifications
Ratings
🚀 How to Run
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python app.py

Open:

http://127.0.0.1:5000
