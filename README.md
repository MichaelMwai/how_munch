Calorie counting App

# HOWMUNCH

## Overview

HOWMUNCH is a single-page web application built with Django and Python, designed to help users find the calorie content of various foods and visualize nutritional values. This application provides an interactive and user-friendly interface that fetches data from an external API and presents it in an engaging format.

## Features

- **Calorie Finder**: Users can input the name of a food item to find its calorie content.
- **Nutritional Information**: Detailed nutritional values including carbohydrates, cholesterol, saturated fat, sodium, sugar, and more.
- **Visual Representation**: A bar chart generated using Chart.js to provide a pictorial view of nutritional values.
- **Exercise Suggestions**: Provides information on how long various exercises (jogging, yoga, weightlifting, walking) are needed to burn the calories of the food item.
- **Alerts and Icons**: Conditional alerts and icons for high sodium and sugar content.

## Technology Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, Bootstrap
- **Charts**: Chart.js
- **API**: API Ninjas for fetching nutritional data

## Features in Detail

- **User Interface**: The application features a clean and straightforward UI, utilizing Bootstrap for responsiveness and styling.
- **Form Submission**: Users can search for calorie information by entering the food name in a form.
- **Dynamic Content**: Nutritional information is displayed dynamically based on API responses, including conditional images and alerts.
- **Charts Integration**: The application uses Chart.js to create a bar chart visualizing the nutritional values.

## How It Works

1. **User Input**: Enter the name of a food item in the search form.
2. **API Call**: The app makes a POST request to the API Ninjas to fetch nutritional data.
3. **Display Results**: The results are displayed on the page, including a chart and exercise suggestions based on the calorie content.
4. **Conditional Alerts**: Alerts are shown for high sodium and sugar content.

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone [repository-url]
   ```

Install Dependencies:

pip install -r requirements.txt

Run Migrations:
python manage.py migrate

Start the Development Server:
python manage.py runserver

Access the Application: Open your browser and go to http://localhost:8000 to start using HOWMUNCH.

## Learnings

Throughout this project, you will gain hands-on experience with:

Making API calls and handling responses in Django.
Utilizing Django templates for dynamic content rendering.
Implementing JavaScript and Chart.js for data visualization.
Creating a responsive and interactive single-page application.
