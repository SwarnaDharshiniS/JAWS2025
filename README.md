# 🛰️ JAWS2025 – NASA Exoplanet Classifier

## 🌌 Overview
**JAWS2025** is an AI-powered exoplanet classification system developed for the **NASA Space Apps Challenge 2025** under the theme _“A World Away – Exoplanet Hunting with AI”_.  
The project uses NASA’s **Kepler Object of Interest (KOI) dataset** to predict whether a celestial object is a **Confirmed Planet**, **Candidate**, or **False Positive**.

## 🚀 Motivation
Identifying exoplanets is a complex and time-consuming process involving thousands of observational data points. By leveraging open NASA data and machine learning, JAWS2025 aims to support astronomers and researchers with a fast, interpretable, and accessible tool for preliminary classification of exoplanet candidates.

## 🧠 How It Works
- Downloads NASA’s **Kepler KOI cumulative dataset** from the [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/).
- Preprocesses and cleans data, selects relevant planetary features.
- Trains a **Random Forest Classifier** on features like period, radius, depth, and temperature.
- Predicts the likelihood of an object being a confirmed exoplanet, candidate, or false positive.
- Provides an interactive **Gradio web app** for real-time classification.

## 🔍 Tools & Technologies
- **Languages:** Python 3.12  
- **Libraries:** pandas, numpy, scikit-learn, xgboost, gradio, matplotlib, seaborn, joblib  
- **Data Source:** [NASA Exoplanet Archive – Kepler KOI Dataset](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/nstedAPI/nph-nstedAPI?table=cumulative&format=csv)

## 🧩 Features
- High-accuracy classification of exoplanet candidates  
- Interactive user interface for predictions  
- Visualizations for confusion matrix and performance metrics  
- Model artifacts saved for reproducibility (`joblib` format)

## 🧠 Use of Artificial Intelligence
JAWS2025 employs a **Random Forest AI model** for multi-class classification. Additionally, AI tools (ChatGPT, GitHub Copilot) were used to assist in documentation and optimization, with all outputs reviewed by the development team.

## 👩‍💻 Team
**Team Name:** JAWS2025  
**Members:**  
- Swarna Dharshini S  
- Sri Janani S
  
_M.Tech Computer Science and Engineering, Amrita Vishwa Vidyapeetham, Coimbatore_

## 🌐 Demo Link
👉 [Gradio Live App](https://49f39b37d599362aac.gradio.live)

## 📊 Results
The model achieved **high accuracy** on test data with strong differentiation between Confirmed, Candidate, and False Positive classes. The confusion matrix and metrics highlight robust model performance.

## 🛰️ NASA Data Used
- **Dataset:** Kepler Object of Interest (KOI) Cumulative Table  
- **URL:** https://exoplanetarchive.ipac.caltech.edu/cgi-bin/nstedAPI/nph-nstedAPI?table=cumulative&format=csv  

## 💡 Future Work
- Expand to include **TESS** and **JWST** datasets for better generalization.  
- Integrate explainable AI (XAI) techniques for transparency in predictions.  
- Deploy on cloud platforms with API endpoints for real-time astronomical analysis.

---
© 2025 Team JAWS2025 | NASA Space Apps Challenge Submission
