# 💧 Water Net  
### 🌐 A Network for Monitoring and Assessing Water Quality for Drinking and Irrigation Purposes


---

## 📘 Overview

**Water Net** is an intelligent water quality assessment system powered by AI and deep learning. It monitors vital parameters of water and classifies it as **safe** or **unsafe** for **drinking** 🚰 and **irrigation** 🌾, helping promote health and sustainable agriculture.

---

## 🚀 Features

- 🧪 Real-time water quality monitoring  
- 📊 Dashboard with live analytics  
- 🤖 Machine learning-based classification  
- 📁 Excel report generation  
- 🌱 Separate standards for drinking and irrigation  
- 🔄 Periodic predictions from sensor data  

---

## 🧠 Technologies Used

| Category         | Tools and Libraries                |
|------------------|------------------------------------|
| Programming      | Python                             |
| AI/ML            | scikit-learn, pandas, numpy        |
| Web Framework    | Django                             |
| Reporting        | xlwt                               |
| Visualization    | Matplotlib, Chart.js (frontend)    |
| Integration      | IoT Sensors (Simulated or Real)    |

---

## 🛠️ How It Works

1. 📥 Collects water data from sensors or simulation  
2. 🧹 Preprocesses the data (cleaning, scaling)  
3. 🤖 Uses ML model to classify the water quality  
4. 📊 Displays results on a web dashboard  
5. 📤 Allows exporting reports in Excel format  

---

## 📐 Parameters Used

- pH  
- Turbidity (NTU)  
- Conductivity (µS/cm)  
- Temperature (°C)  
- TDS (ppm)  
- Salinity (ppt)  

---

## ⚙️ Installation

```bash
git clone <project-folder>
cd <project-folder>
pip install -r requirements.txt
python manage.py runserver
