# 🌍 Air Quality Intelligence Platform

## 📖 Project Overview  
The **Air Quality Intelligence Platform** is a comprehensive system for monitoring and forecasting air quality across India.  
It integrates **real-time air quality data, 5 years of historical data, LSTM-based forecasting models, a RAG-powered chatbot using Google Gemini, and an interactive React dashboard**.  
The system delivers actionable insights into pollution levels, health risks, and future trends across **32 States & Union Territories**, powered by data from **662+ monitoring stations**.  

---

## ✨ Features  
- **Real-time AQI Monitoring** – Live updates from 662+ monitoring stations across India  
- **Interactive Heatmaps** – State-wise and nationwide visualization of air quality  
- **5-Day Forecasting** – LSTM models provide pollutant-wise predictions for all 32 States & UTs  
- **AI Chatbot** – RAG-based assistant (Google Gemini + FAISS) for AQI-related queries  
- **Pollutant Analysis** – Breakdown of 8 pollutants: PM2.5, PM10, CO, SO₂, NO₂, O₃, NO, NH₃  
- **Health Recommendations** – Precautionary measures and health guidelines based on AQI levels  

---
## 🏗️ Project Architecture  
The project is organized into four main components:

```
AQI_Dashboard-main/
├── aqi-real-time-dashboard/    # React frontend for visualization
├── heatmap_backend/            # Backend for heatmap generation
├── prediction_backend/         # Backend for AQI forecasting
└── rag-backend/                # Backend for AI chatbot
```


## 📌 Conclusion  
This platform provides an **end-to-end solution** for air quality monitoring and forecasting in India.  
By combining **real-time monitoring, machine learning predictions, and AI-driven assistance**, it empowers users to understand pollution levels, assess health impacts, and prepare for future air quality scenarios through a user-friendly dashboard.  
