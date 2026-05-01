A real-time User Activity Monitoring Dashboard built with Python and Flask.

This project tracks the currently active application on a Windows system and displays it on a live web dashboard with recent activity logs.

## Features

* Real-time active window tracking
* Live dashboard interface
* Recent activity log with timestamps
* Background monitoring using threading
* REST API for frontend communication

## Technologies Used

* Python
* Flask
* HTML, CSS, JavaScript
* Windows API (ctypes)

## How it Works

The system continuously monitors the foreground window using Windows API.
Whenever the active window changes, it logs the data and updates the dashboard in real time using API calls.

## Run the Project

1. Install dependencies:
   pip install -r requirements.txt

2. Run the application:
   python app.py

3. Open browser:
   http://127.0.0.1:5000/
