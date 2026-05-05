🌍 AI Disaster Intelligence Platform — Bangladesh  
**Real-time Flood Prediction • AI Decision Support • Disaster Response Optimization**

> A national-scale intelligent system designed to **predict floods, visualize risk, and optimize emergency response** using AI, geospatial data, and simulation models.

---

## 🚨 Why This Matters

Bangladesh faces **frequent and devastating floods** impacting millions every year.

This platform bridges the gap between:
- 📡 **Data (satellite + water levels)**
- 🤖 **AI predictions**
- 🧑‍🚒 **Real-world response decisions**

---

## ✨ Key Highlights

- 🔮 **72-hour AI Flood Prediction Engine**
- 🗺️ **Interactive Risk Heatmap (District-level)**
- 📊 **Advanced Analytics Dashboard**
- 🌧️ **What-if Disaster Simulation**
- 📦 **Smart Resource Allocation System**
- 🧾 **Citizen Disaster Reporting**
- 🌊 **Live Water Level Monitoring**
- 🧠 **AI-assisted Decision Support**

---

## 🖼️ Live Preview
## 📌 How to View Screenshots

👉 Click on each link below to open and view the corresponding screenshot in full size.
### 🧭 Dashboard
[Dashboard](screenshots/dashboard.png)

### 🗺️ Flood Risk Map
[Map](screenshots/map.png)

### 📊 Analytics
[Analytics](screenshots/analytics.png)

### 🌧️ Simulation
[Simulation](screenshots/simulation.png)

### 📦 Resource Management
[Resources](screenshots/resources.png)

### 🌊 Water Monitoring
[Water Levels](screenshots/water-levels.png)

### 🧾 Reports
[Reports](screenshots/reports.png)

### 🔐 Login System
[Login](screenshots/login.png)

---

## 🧠 System Architecture

Frontend (React + Leaflet)
        ↓
API Layer (FastAPI)
        ↓
Core Services
 ├── Flood Prediction (ML Models)
 ├── Simulation Engine
 ├── Resource Optimization
 └── Report Processing
        ↓
Database + External APIs

---

## ⚙️ Tech Stack

**Frontend**
- React.js
- Leaflet.js
- TailwindCSS

**Backend**
- FastAPI
- Python

**AI/ML**
- Time-series forecasting
- Risk classification models

**DevOps**
- Docker
- Docker Compose

---

## 🚀 Quick Start

### 🐳 Run with Docker

docker-compose up --build

---

### 💻 Manual Setup

#### Backend

cd backend  
python -m venv venv  
venv\\Scripts\\activate  
pip install -r requirements.txt  
uvicorn app.main:app --reload --port 8000  

#### Frontend

cd frontend  
npm install  
npm run dev  

---

## 🌐 Environment Setup

cp .env.example .env  

Set:

VITE_SATELLITE_TILE_URL=your_google_earth_engine_url  

---

## 📁 Project Structure

disaster-platform/  
├── backend/  
├── frontend/  
├── screenshots/  
├── docker-compose.yml  
└── README.md  

---

## 📊 Real-World Use Case

A district officer logs in → sees rising water levels → AI predicts high flood risk → system suggests resource allocation → simulation estimates impact → response deployed early.

---

## 🛣️ Roadmap

- [ ] Live satellite integration  
- [ ] Mobile app version  
- [ ] Real-time IoT sensor data  
- [ ] Government API integration  
- [ ] AI model accuracy improvements  

---

## 🤝 Contributing

fork → clone → branch → commit → pull request  
