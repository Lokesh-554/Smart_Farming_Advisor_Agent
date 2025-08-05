# 🌾 AI Agent for Smart Farming Advice

A capstone project developed as part of the IBM Skills Build AI & Cloud Internship, this AI-powered agent provides localized, real-time agricultural advice to small-scale farmers using IBM Granite with RAG (Retrieval-Augmented Generation).

---

## 📌 Problem Statement

Small-scale farmers often lack access to real-time, trustworthy, and localized agricultural information. This project solves this challenge with an AI agent that can answer farmer queries like:

- "What crop should I plant this season?"
- "What is today’s mandi rate for tomatoes?"

The AI retrieves data from reliable sources such as government portals, weather APIs, and agricultural databases to deliver accurate insights in multiple languages.

---

## ✅ Proposed Solution

- Build an AI assistant using IBM Granite models with RAG.
- Interact with farmers in regional languages.
- Retrieve real-time data on:
  - Crop recommendations
  - Weather forecasts
  - Pest control
  - Soil health
  - Market (mandi) prices

---

## 🛠️ Technologies & Tools

- **IBM Cloud Lite and its Services**
- **IBM Watsonx.ai**
- **Granite-3-8 Model** (for LLM)
- **RAG (Retrieval-Augmented Generation)**
- **OpenWeatherMap API**
- **Agmarknet**
- **Python / Jupyter Notebooks**
- **Git / GitHub**

---

## 🧠 Model & Deployment

- Chosen LLM: `granite-3-3-8-b instruct`
- Converts agricultural datasets and documents to vector format for retrieval.
- Deployed via IBM Watsonx with proper API key, deployment space, and preview.
- Multilingual prompt handling (Hindi, Telugu, Tamil, Kannada).
- Live integration with weather and mandi APIs.

---

## ✅ Results

### 🧪 Sample Queries and Responses:

- **Q**: “What crop should I plant in Kharif in Karnataka with red sandy soil?”  
  **A**: “Millets and groundnut are recommended for Kharif in Karnataka with red sandy soil due to low water needs and good profitability.”

- **Q**: “आज गुंटूर में टमाटर का मुंडी भाव क्या है?”  
  **A**: “आज गुंटूर में टमाटर का औसत मुंडी भाव ₹1450 प्रति टन है।”

### 🔍 Key Outcomes

- Real-time, multilingual, localized responses
- Integrated with live APIs
- Context-aware retrieval with RAG
- Simple and useful advice for farmers

---

## 🚀 Future Scope

- Integrate with IoT sensors for real-time soil/weather data
- Add more regional languages
- Build an offline mobile app for rural areas
- Predictive analytics for crop yield and pest infestations
- Integration with government subsidy and insurance platforms

---

> "Empowering farmers with AI for a smarter, sustainable tomorrow." 🌱
