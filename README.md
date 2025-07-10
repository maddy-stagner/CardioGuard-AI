# CardioGuard-AI
Highlights the cardiovascular focus (vital signs monitoring)
Project Overview
WearSenseAI is a digital health technology project built to support low-cost, real-time remote patient monitoring using physiological data collected via wearable sensors. The system classifies abnormal vital signs using a machine learning model and provides intelligent alerts to caregivers. It’s designed especially for use in low-resource clinical and home-care settings, with a focus on equity and accessibility in healthcare.

Key Features
Real-World Dataset: Uses authentic human vital signs data from wearable sensors

ML-Based Abnormality Detection: Trained Random Forest classifier on SpO₂, Heart Rate, Respiratory Rate, and Temperature

Live Vital Signs Simulation: Simulates incoming data streams for real-time risk detection

Smart Alert System: Notifies when patient vitals exceed safe thresholds

Explainable AI (XAI): Integrated SHAP visualizations to explain each prediction

Interactive Dashboard: Real-time health monitor built with Streamlit

Low-Cost & Equitable: Designed for deployment in resource-limited settings

Technologies Used
Tool / Library	Purpose
Python	Core programming language
Pandas, NumPy	Data processing & simulation
scikit-learn	Machine learning
SHAP	Explainable AI
Streamlit	Real-time dashboard
Joblib	Model serialization
