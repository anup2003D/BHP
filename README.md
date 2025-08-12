# 🏠 Bangalore House Price Prediction

This project predicts the **average house price in Bangalore** based on user inputs such as:
- **BHK** (Number of Bedrooms)
- **Bath** (Number of Bathrooms)
- **Location**
- **Area (in Square Feet)**

It is built using **Machine Learning** and deployed with a **Flask** backend and a simple web UI.

---

## 📌 Features
- **Interactive Web Interface** – Enter property details and get instant price prediction.
- **Location-Sensitive** – Takes location into account for better accuracy.
- **Trained ML Model** – Uses real Bangalore housing dataset.
- **User-Friendly** – Minimal and clean interface.

---

## 📂 Dataset
The dataset used in this project can be found here:  
[📄 Bangalore House Price Dataset](https://www.kaggle.com/datasets/vedanthbaliga/bangalorehouseprices)

---

## 📷 Screenshots

### Example 1
![Example 1](https://github.com/anup2003D/BHP/blob/main/BHPss1.png)

**Input:**
Area: 1200 sqft
BHK: 2
Bath: 1
Location: 6th phase jp nagar

**Output:**
Estimated Price: ₹ 73.68 Lakh


---

### Example 2
![Example 2](https://github.com/anup2003D/BHP/blob/main/BHPss2.png)

**Input:**
Area: 1600 sqft
BHK: 3
Bath: 2
Location: hoskote

**Output:**
Estimated Price: ₹ 76.46 Lakh


---

## ⚙️ Tech Stack
- **Python 3**
- **Flask** (Backend API)
- **Scikit-learn** (ML Model)
- **Pandas, NumPy** (Data Processing)
- **HTML, CSS, JavaScript** (Frontend)
- **Pickle** (Model Storage)

---

## 📂 Project Structure
BHP/
│-- model/ # ML model files
│-- server/ # Flask backend
│-- client/ # Frontend files
│-- data/ # Dataset
│-- app.py # Flask App
│-- model.py # Model training script
│-- requirements.txt # Python dependencies
│-- README.md # Documentation


---

