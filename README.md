# Smartphone Sales Prediction and Recommendation System

## Project Overview

The Smartphone Sales Prediction and Recommendation System is a machine learning–based web application designed to analyze smartphone market data and predict future sales. In addition to sales prediction, the system allows users to compare smartphones based on specifications and provides a platform to buy and sell second-hand smartphones.

The smartphone market is highly dynamic, with frequent product launches, changing customer preferences, and fluctuating prices. Traditional sales forecasting methods often fail to capture these patterns. This project addresses these challenges by using data-driven machine learning models to make accurate predictions and assist decision-making for both businesses and consumers.

---

## Problem Statement

Smartphone manufacturers and retailers face difficulties in:
- Predicting future sales accurately
- Managing inventory efficiently
- Understanding customer preferences
- Providing fair pricing in the second-hand market

Consumers also struggle to:
- Compare smartphones effectively
- Decide the best phone within their budget
- Determine fair resale value for used smartphones

This system provides a unified solution to these problems.

---

## Objectives

- Predict smartphone sales using machine learning algorithms
- Analyze historical sales and product specifications
- Help businesses optimize inventory and pricing strategies
- Enable users to compare smartphones easily
- Provide a secure buy/sell platform for second-hand smartphones
- Visualize market trends using charts and dashboards

---

## Features

### Sales Prediction
The system uses historical sales data and smartphone specifications to predict future demand. Machine learning models identify patterns such as price impact, feature popularity, and seasonal trends.

### Smartphone Comparison
Users can compare smartphones side by side based on:
- Price
- RAM and storage
- Battery capacity
- Camera specifications
- Ratings and reviews

This helps users make informed purchasing decisions.

### Buy and Sell Marketplace
Users can list used smartphones for sale and browse available listings. The system provides basic price guidance based on market data to ensure fair valuation.

### Data Visualization
Graphs and charts are used to display:
- Sales trends
- Demand patterns
- Model prediction results

These visualizations make complex data easy to understand.

---

## Machine Learning Models Used

- Linear Regression  
  Used as a baseline model for predicting sales trends.

- Decision Tree Regressor  
  Captures non-linear relationships in sales data.

- Random Forest Regressor  
  Improves accuracy by combining multiple decision trees.

- Support Vector Regression (SVR)  
  Handles complex relationships between features and sales.

These models are trained and evaluated using standard performance metrics.

---

## Technology Stack and Frameworks

### Frontend Technologies

HTML  
Used to structure the web pages.

CSS  
Used to design and style the user interface.

JavaScript  
Used to handle dynamic behavior and user interaction.

Bootstrap  
Provides responsive design to ensure the application works on different screen sizes.

Chart.js  
Used to create interactive charts and graphs for data visualization.

---

### Backend Framework

Flask (Python)  
Flask is a lightweight web framework used to:
- Handle HTTP requests
- Connect frontend and backend
- Execute machine learning models
- Serve prediction results through APIs

---

### Machine Learning and Data Processing Libraries

Scikit-learn  
Used to build and train machine learning models.

Pandas  
Used for data cleaning, preprocessing, and analysis.

NumPy  
Used for numerical computations and matrix operations.

Matplotlib  
Used during model development for visualizing results.

---

### Database and Storage

CSV Files  
Used to store large historical datasets related to smartphone sales and specifications.

SQLite  
A lightweight relational database used to store user data and marketplace listings.

---

### Development Tools

- Jupyter Notebook for data analysis and model training
- Visual Studio Code for application development
- GitHub for version control

---

## System Architecture

User Interface (HTML, CSS, JavaScript)  
↓  
Flask Backend (API Layer)  
↓  
Machine Learning Models  
↓  
CSV Files / SQLite Database  

This layered architecture ensures separation of concerns and easy scalability.

---

## Installation and Execution Steps

### Step 1: Clone the Repository
### Step 2: .\run_all.bat
### Step 3: python -m http.server --directory main 8000
### Step 4: run on http://127.0.0.1:8000
