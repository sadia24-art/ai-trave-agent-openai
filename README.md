# ✈️ AI Travel Agent

## Overview

**AI Travel Agent** is an AI-powered web application that helps users plan their travels by offering **personalized travel plans**, **flight recommendations**, and **hotel suggestions**. Built with **Streamlit** and the **OpenAI Agents SDK**, this assistant tailors travel options based on user preferences such as **budget**, **preferred airlines**, and **hotel amenities**.

## 🚀 Features

- **Personalized Travel Plans**: Generate custom travel itineraries based on your preferences.
- **Flight & Hotel Recommendations**: Get tailored suggestions for flights and hotels with key details.
- **Interactive Chat**: Ask about destinations, flights, and hotels in natural language.
- **Save Preferences**: Customize and save your travel preferences for future recommendations.
- **Instant Updates**: Get responses quickly with seamless AI-driven recommendations.

## 🛠️ Technologies

- **Streamlit**: Fast web app development framework.
- **OpenAI Agents SDK**: AI-powered agents for decision-making and recommendations.
- **Asyncio**: Asynchronous programming for efficient handling of tasks.
- **UUID**: Generate unique identifiers for users and sessions.

## 📝 Installation

### Prerequisites

- Python 3.8+
- pip

### Steps to Set Up

1. **Clone the repository**:
   ```bash
   
   cd travel-planner-assistant
   Install dependencies:
   ```
   pip install -r requirements.txt
   Run the app:

streamlit run app.py
Open the app at http://localhost:8501 in your browser.

## 💬 Usage

## How to Interact

Start New Conversation: Reset chat history and start fresh.

Ask About Destinations: “Where should I visit in Europe?”

Flight & Hotel Recommendations: “Find me a flight to New York for June 1st” or “Recommend a hotel in Paris with Wi-Fi and a pool.”

Set Preferences: Choose preferred airlines, hotel amenities, and budget.

## 🔧 Customizing Preferences

Airlines: Choose from top airlines like SkyWays, Delta, and more.

Hotel Amenities: Select must-have amenities like Wi-Fi, Pool, Gym, etc.

Budget: Set your travel budget from budget, mid-range, to luxury.

## 🛠️ Code Overview

app.py: The Streamlit app that handles user input, displays the chat interface, and processes responses.

agents.py: Contains the logic for the AI agent that generates travel plans and recommendations.

v5_guardrails.py: Defines the travel agent and user context, handling interaction with the OpenAI SDK.

## 🌱 Future Enhancements

Real-time Data Integration: Live flight and hotel prices.

User Profiles: Save preferences across sessions.

More Features: Itinerary planning, activity suggestions, and budgeting.

📜 License
MIT License - see the LICENSE file for details.

Powered by OpenAI Agents SDK | Built with Streamlit | ✈️ Plan your next adventure today!


