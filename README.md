# 🌦️Weather App

# 📚Table of Contents
1. Introduction
2. Project Overview
3. Setup
4. Usage
5. Contributing

#  📝Introduction
The Weather App is a simple web-based application that allows users to check real-time weather information for any city. It is built using HTML, CSS, JavaScript, Java Servlet, and JSP. The app integrates with the OpenWeatherMap API to fetch weather data and display it in a user-friendly format.

# 🌍Project Overview
This project demonstrates how to build a dynamic web application using Java technologies. The backend is handled using Java Servlets, and the frontend uses HTML, CSS, and JavaScript to create an interactive user experience.

✅ Key Features
✔️ Search weather by city name
✔️ Display temperature, weather conditions, and city details
✔️ Clean and responsive UI
✔️ Error handling for invalid city names

# 🛠️Setup
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/your-username/WeatherApp.git
2. Open the project in your IDE
Use Eclipse or IntelliJ IDEA
3. Add Tomcat Server
Install Tomcat 10.1.24 and configure it in your IDE
4. Get an OpenWeatherMap API Key
Go to https://openweathermap.org
Create an account and generate an API key
5. Add API Key to Servlet
Update WeatherServlet.java:

java
Copy
Edit
private static final String API_KEY = "YOUR_API_KEY";
6. Build and Deploy
Build the project
Run on Tomcat Server
Open browser → http://localhost:8080/WeatherApp/index.jsp

# 🚀Usage
Open the app in the browser.
Enter a city name in the search bar.
Click "Get Weather."
The app will display:
Temperature
Weather condition
City name
Error message will be shown for invalid cities.


# 🤝Contributing
Contributions are welcome!

Fork the repository
Create a new branch (git checkout -b feature-name)
Commit your changes (git commit -m "Description of changes")
Push to GitHub (git push origin feature-name)
Create a Pull Request



