# 🌦️ WeatherGPT — AI-Powered Weather Assistant

WeatherGPT is an intelligent conversational weather assistant that integrates real-time meteorological data with the Google Gemini API to deliver contextual, natural-language forecasts, clothing suggestions, and activity advisories.

Built for **Smart India Hackathon (SIH)** under Team **Pixel**.

---

## 👥 Team Details

* **Team Name:** Pixel
* **Team Leader:** Rishabh Singh
* **Project Track:** Web & Mobile App Development / AI Solution (SIH ID: 26068)

---

## 🚀 Live Demo

* **Live Demo:** [Launch WeatherGPT](https://6c054af59907e0ca36.gradio.live/)

---

## ✨ Key Features

* **Natural Language Queries:** Understands everyday conversational inputs (e.g., *"Should I carry an umbrella today?"* or *"Is it cold enough for a jacket tonight?"*).
* **Real-Time Data Integration:** Dynamic fetching of live temperature, humidity, wind speed, and precipitation via weather APIs.
* **Contextual AI Synthesis:** Leverages Google Gemini to turn raw JSON meteorological data into actionable advice.
* **Interactive UI:** Clean, responsive chat interface built with Gradio for seamless interaction on desktop and mobile.
* **Lightweight & Modular:** Optimized architecture compatible with Google Colab, local virtual environments, and cloud instances.

---

## 🛠️ Tech Stack

* **Language:** Python 3.10+
* **Large Language Model:** Google Gemini API
* **Data Provider:** Real-Time Weather API (OpenWeatherMap / WeatherAPI)
* **Frontend:** Gradio
* **Environment & Tools:** Google Colab, VS Code, Git, GitHub

---

## 🧠 System Architecture

```text
[ User Input Query ]
         │
         ▼
[ Intent & Location Extraction (Gemini LLM) ]
         │
         ▼
[ Real-Time Weather Data Retrieval (REST API) ]
         │
         ▼
[ Contextual Response & Advisory Generation (Gemini LLM) ]
         │
         ▼
[ Interactive Gradio Interface ]
