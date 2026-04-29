🌦️ Rain Alert Service
Automated Weather Notification System


📖 Overview
This project is a functional weather monitoring service designed for residents of Aqaba, Jordan. It connects to the OpenWeatherMap API to analyze the forecast for the next 12 hours. If the system detects rain (based on weather condition codes), it automatically triggers an SMS alert to my phone using the Twilio API.

🚀 Key Features
Targeted Forecasting: Monitors a specific 12-hour window (4 time blocks) to provide timely alerts.

API Optimization: Uses the cnt parameter to fetch only the required data, saving bandwidth and improving processing speed.

Automated SMS: Integrated with Twilio to bridge the gap between cloud data and real-world notifications.

Clean Logic: Built using Python's requests library with robust error handling via raise_for_status().


Shutterstock
Explore
🛠️ Tech Stack
Language: Python 3.13

APIs: OpenWeatherMap (5-Day/3-Hour Forecast), Twilio SMS API

Libraries: requests, twilio

Tools: PyCharm IDE, Git/GitHub

📋 Project Structure
main.py: The core logic for data fetching, parsing, and notification.

.gitignore: Configured to protect environment files and virtual environments
