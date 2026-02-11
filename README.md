<!-- Animated Gradient Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1C2D,100:00C2FF&height=200&section=header&text=RetailAI&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Smart%20Demand%20Forecasting%20System&descAlignY=55&descAlign=50" />
</p>

# 🛍️ RetailAI – Smart Demand Forecasting System  
### AI-Powered Demand Prediction for Essential Stores

<p align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Uvicorn](https://img.shields.io/badge/Uvicorn-000000?style=for-the-badge)

</p>

---

## 📌 Overview

RetailAI is an AI-powered web application designed for essential stores and small retail businesses to forecast product demand using historical sales data and machine learning.

The system helps shop owners:

- Reduce stockouts  
- Avoid overstocking  
- Monitor product demand trends  
- Calculate optimal reorder quantity  
- Identify stock risk levels  

---

## ✨ Key Features

### 📊 AI-Based Demand Forecasting
- Linear Regression prediction model  
- 30-day future demand estimation  
- Monthly demand projection  

### 📈 Smart Trend Analysis
- Increasing / Decreasing / Stable trend detection  
- Average daily sales calculation  
- Automatic time-series processing  

### 📦 Intelligent Reorder System
- Safety stock integration  
- Automatic reorder quantity calculation  
- Risk level classification:
  - Critical  
  - Low Stock  
  - Safe  
  - Overstock  

### ⚡ High-Performance Backend
- FastAPI-based REST architecture  
- Modular ML prediction engine  
- Lightweight & scalable  

---

## 🛠️ Tech Stack

| Layer | Technology |
|--------|------------|
| Frontend | HTML, CSS, JavaScript |
| Backend | FastAPI |
| Machine Learning | Scikit-Learn (Linear Regression) |
| Data Processing | Pandas, NumPy |
| Server | Uvicorn |

---

## 📂 Project Structure

```text
Smart-Demand-Forecasting-System/
│
├── main.py                 # FastAPI backend server
├── prediction_engine.py    # ML forecasting logic
├── requirements.txt        # Dependencies
├── frontend/               # Frontend UI
└── README.md               # Documentation
```

---

## 🧠 How It Works

1. Sales history is converted into structured time-series format.  
2. Missing dates are automatically filled for accuracy.  
3. Linear Regression analyzes demand trends.  
4. Next 30 days are projected.  
5. Monthly demand is calculated.  
6. Reorder quantity and risk level are generated intelligently.  

---

## ▶️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/im-mansur/Smart-Demand-Forecasting-System-for-Essential-Store.git
cd Smart-Demand-Forecasting-System-for-Essential-Store
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Server

```bash
python main.py
```

OR

```bash
uvicorn main:app --reload --port 8080
```

If port 8080 is already in use:

```bash
uvicorn main:app --reload --port 8000
```

---

## 🌟 Use Cases

- Grocery stores  
- Essential retail shops  
- Supermarkets  
- Retail analytics learning  
- AI/ML academic projects  
- SaaS startup prototype  

---

## 🔮 Future Enhancements

- Advanced time-series models (ARIMA / LSTM)  
- Seasonal demand detection  
- Multi-store support  
- Cloud database integration  
- Mobile-friendly dashboard  
- Automated low-stock alerts  

---
## 📸 Screenshots

![Dashboard Preview](https://github.com/im-mansur/Smart-Demand-Forecasting-System-for-Essential-Store/blob/main/preview.png)
---

## 🎓 Project Type

AI / Machine Learning / Retail Analytics System  
Portfolio + Real-World Business Prototype  

---

## 📜 License

This project is licensed under the MIT License.  
© 2026 Mansur Ahamed A  

---

<p align="center">
  ⭐ If you like this project, don’t forget to star the repository!
</p>

