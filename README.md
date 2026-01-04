# PyQt5-Weather-App
A real-time weather application built with Python (PyQt5, Requests), integrating the OpenWeatherMap API with robust JSON parsing and HTTP request handling.

This is a personal project I built to learn more about how Python interacts with real-world data via APIs. It's a clean, functional desktop app that lets you check the weather in any city instantly.

Instead of just a simple command-line script, I decided to build a proper Graphical User Interface (GUI) using PyQt5 to make it feel like a real application you'd actually want to use.

## 🚀 What it can do
* **Live Weather Data:** Pulls the current temperature and conditions from OpenWeatherMap.
* **Smart UI:** Displays custom weather icons (Sun, Clouds, Mist, etc.) based on the actual forecast.
* **Error Handling:** I spent extra time making sure the app doesn't just crash. It handles invalid city names, network issues, and even API authentication errors gracefully.

## 🛠️ The Tech I Used
* **Python 3.x:** The core language.
* **PyQt5:** For building the desktop window and interactive elements.
* **Requests:** To handle the HTTP communication with the API.
* **JSON:** For parsing the nested data returned by the weather server.

## 📸 See it in Action

### Success States
<img width="408" height="543" alt="weatherimg1" src="https://github.com/user-attachments/assets/6be95685-2e69-47a9-87dd-3b756a0fb437" />
<img width="408" height="544" alt="weatherimg2" src="https://github.com/user-attachments/assets/ec394d43-0f53-4dba-8e2e-32ae1fc82638" />
<img width="405" height="537" alt="weatherimg3" src="https://github.com/user-attachments/assets/ee7a2ff5-c752-475b-9b43-24f0fd09a1ea" />

### Handling the Edge Cases (Errors):
It was important to me that the app could handle mistakes. Here is how it looks when something goes wrong:
<img width="459" height="630" alt="weather app pic2" src="https://github.com/user-attachments/assets/57ca456b-b4f3-4a73-826e-b5e5ef8ba6b9" />
<img width="431" height="536" alt="weatherimg4" src="https://github.com/user-attachments/assets/be884805-5b29-42d8-8540-3b8782091ddd" />
<img width="408" height="543" alt="weatherimg5" src="https://github.com/user-attachments/assets/d0087479-529f-4d70-aff5-a9fa037489d0" />



## ⚙️ How to get it running
If you want to try it out on your machine, you'll need to install the dependencies first:

1. **Clone the repo:**
   `git clone https://github.com/YOUR_USERNAME/PyQt5-Weather-App.git`

2. **Install Requests and PyQt5:**
   `pip install requests PyQt5`

3. **Get an API Key:**
   Sign up at [OpenWeatherMap](https://openweathermap.org/) and get your free API key.

4. **Run the app:**
   `python main.py`

## 💡 What I learned
This project taught me a lot about handling asynchronous data and the importance of user experience (UX). One of the biggest challenges was making the UI wait for the API response without "freezing" the window—a common issue when working with desktop apps and network calls.

### 📜 Credits & Acknowledgments

Tutorial Reference: [Create a weather with Python](https://youtu.be/Q4377DH5Jso?si=g_EqnVNTT2BgClEt) by Bro Code

Weather Data: OpenWeatherMap API.
