# Weather Alert App - Django Project

![image](https://github.com/user-attachments/assets/080433db-ba75-4778-95d9-d577db40fd57)

## Overview
- A Django-based web application that provides real-time weather information for cities worldwide using the OpenWeatherMap API. Users can search for weather conditions by city name and view detailed weather data.

## Features
* Real-time weather data retrieval
* Responsive Bootstrap 4 interface
* Error handling for invalid city names

## Displays:
- Temperature (in Celsius)
- Humidity
- Pressure
- Weather conditions
- Weather icons
- Geographic coordinates

## Prerequisites
- Python 3.6+
- Django 3.0+
- OpenWeatherMap API key (free tier available)

## Installation
Clone the repository:
- git clone https://github.com/Janeanny1/WeatherAlert.git
- cd WeatherAlert

## Create and activate a virtual environment:
* python -m venv venv
* source venv/bin/activate  # On Windows: venv\Scripts\activate

## Install dependencies:
* pip install -r requirements.txt

## Set up environment variables:
- Create a .env file in the project root with

## Run migrations:
- python manage.py migrate

## Start the development server:
- python manage.py runserver

## Project Structure
![image](https://github.com/user-attachments/assets/519ffcb8-ad91-458e-a3dc-9b9936a3f96e)

## API Usage
- The app uses the OpenWeatherMap Current Weather Data API:
* https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}

## Customization
- To modify the app:
* Edit openweather/views.py to change weather data processing
* Modify openweather/templates/openweather/index.html to change the UI
* Update mysite/settings.py for project configuration

## License
- MIT License - see LICENSE for details.

#Happy coding!
