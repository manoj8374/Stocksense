# **📊 Personalized Stock Market Summary Platform**

🚀 **An AI-driven platform that delivers personalized stock market insights, real-time financial data, and chatbot assistance.**

![Tech Stack](https://img.shields.io/badge/Backend-FastAPI-blue?style=for-the-badge&logo=fastapi) ![Frontend](https://img.shields.io/badge/Frontend-React%20%7C%20TypeScript-61DAFB?style=for-the-badge&logo=react) ![AI](https://img.shields.io/badge/AI-LLaMA--3.3--70B-red?style=for-the-badge) ![Database](https://img.shields.io/badge/Vector%20DB-Qdrant-purple?style=for-the-badge) ![Programming Language](https://img.shields.io/badge/Language-Python-green?style=for-the-badge&logo=python)

---

## **🌟 Features**

👉 **Daily Personalized Summaries** – AI-generated stock market insights tailored to user preferences.  
👉 **Real-Time Market Chatbot** – Ask questions about stocks, trends, and financial events.  
👉 **Stock Price & Commodity Tracking** – Fetch latest stock prices, commodity data, GDP, and crypto exchange rates.  
👉 **Important Market Alerts** – Get notified about critical financial updates.

---

## **📂 Tech Stack**

### **Frontend:**

👉 **React.js + TypeScript** – For building an interactive UI  
👉 **Tailwind CSS** – Modern, responsive styling

### **Backend:**

👉 **FastAPI** – High-performance API development

### **AI & Data Processing:**

👉 **LLaMA-3.3-70B (Groq API)** – AI-powered summarization & chatbot  
👉 **SentenceTransformer** – Converts news articles into vector embeddings  
👉 **Qdrant (Vector DB)** – Stores news embeddings for fast retrieval  
👉 **Alpha Vantage & EODHD APIs** – Fetches real-time stock, commodity, and economic data

---

## **🌟 Installation & Setup**

### **🛠 Backend (FastAPI) Setup**

```bash
# Clone the repository
git clone [https://github.com/yourusername/personalized-stock-summary.git](https://github.com/NikhilDendeti/Stock_Sense.git)

# Navigate to backend directory
cd backend

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt

# Set up environment variables (create .env file)
cp .env.example .env

# Run FastAPI server
uvicorn main:app --reload
```

The backend will run at: **`http://127.0.0.1:8000`**

---

### **🖥️ Frontend (React + TypeScript) Setup**

```bash
# Navigate to frontend directory
cd frontend

# Install dependencies
npm install

# Start the frontend
npm run dev
```

The frontend will be available at: **`http://localhost:3000`**

---

## **🔧 Environment Variables (.env file)**

Create a **`.env`** file in the `backend` folder with the following:

```ini
# Groq API Key
GROQ_API_KEY=your_groq_api_key

# Alpha Vantage API Key
ALPHA_VANTAGE_API_KEY=your_alpha_vantage_api_key

# EODHD API Key
EODHD_API_KEY=your_eodhd_api_key

# Qdrant Config
QDRANT_API_KEY=your_qdrant_api_key
QDRANT_URL=https://your-qdrant-instance.com

# JWT Secret Key
JWT_SECRET=your_secret_key
```

---

## **📈 API Endpoints (Backend)**

### **Stock Market Summaries**

👉 `GET /summary/daily` – Fetch personalized daily stock summary  
👉 `GET /summary/history` – Retrieve past summaries

### **Stock & Financial Data**

👉 `GET /stock/{symbol}` – Get real-time stock price  
👉 `GET /commodities/{commodity}` – Fetch commodity data  
👉 `GET /crypto/{from_currency}/{to_currency}` – Get crypto exchange rates

### **AI Chatbot**

👉 `POST /chat/query` – Ask market-related questions

---

## **🎉 Future Enhancements**

👉 **Real-time Market Dashboard** – Live stock tracking 📊  
👉 **Portfolio Tracking** – Manage personal investments 💰  
👉 **Stock Price Prediction** – AI-driven forecasts 🔮  
👉 **Multi-Language Support** – Expand accessibility 🌐

---

## **Application Doc**

👉 [bit.ly/42Rg8Lf](https://bit.ly/42Rg8Lf)

## **💪 Contributing**

💡 **Want to contribute?** Fork the repository and submit a PR!

```bash
# Clone the forked repository
git clone https://github.com/yourusername/personalized-stock-summary.git

# Create a new branch
git checkout -b feature-new-enhancement

# Make changes and commit
git commit -m "Added a new feature"

# Push changes
git push origin feature-new-enhancement

'''


# Submit a Pull Request!
```

---
