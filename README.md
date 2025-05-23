Weather App
------------

# 🌤️ Weather App

A beginner-friendly weather application built using **HTML**, **CSS**, and **JavaScript**. It allows users to check real-time weather data of any city using the **OpenWeatherMap API**. The app displays current temperature, humidity, wind speed, and dynamically updates weather icons based on the weather conditions.

---

## 📌 Project Overview

This project demonstrates:

- 🌐 Integration of third-party APIs (OpenWeatherMap)  
- 🔍 Handling user input and search queries  
- ⚙️ Making asynchronous API requests using `fetch()`  
- 🧠 Dynamic DOM manipulation based on API responses  
- ❗ Graceful error handling for invalid inputs  
- 🖥️ Responsive and clean user interface design  

---

## 🔧 Features

| Feature                | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| 🔍 City Search         | Enter any city name to fetch real-time weather data                        |
| 🌡️ Temperature         | Displays the current temperature in Celsius                                 |
| 💧 Humidity            | Shows humidity percentage                                                   |
| 💨 Wind Speed          | Displays current wind speed in km/h                                         |
| 🌥️ Weather Icon       | Dynamically changes icon based on weather condition (e.g., Rain, Clear)    |
| ❌ Error Handling      | Displays error message for invalid city entries                             |
| 📱 Responsive Layout   | Works seamlessly across different devices                                   |

---

## 🚀 Technologies Used

| Technology         | Purpose                               |
|--------------------|-------------------------------------|
| **HTML5**          | Structure of the app                 |
| **CSS3**           | Styling and responsive layout       |
| **JavaScript (ES6)**| Application logic & API interaction |
| **OpenWeatherMap API** | Real-time weather data             |

---

## 🛠️ How It Works

1. **User Input**  
   - User types a city name and clicks the search button.  
2. **API Request**  
   - The app sends a `fetch()` request to the OpenWeatherMap API with the city name.  
3. **Display Data**  
   - If the city is found:  
     - Displays temperature, humidity, wind speed, and corresponding weather icon.  
     - Shows the weather information section.  
4. **Handle Errors**  
   - If the city is not found:  
     - Shows an error message.  
     - Hides the weather information to avoid confusion.  

---

## 📁 Live Demo & Source Code

- **Live Demo:** [http://127.0.0.1:5501/index1.html]  
- **Source Code:** [https://github.com/Anushamudumba/Weather-App]  

---


