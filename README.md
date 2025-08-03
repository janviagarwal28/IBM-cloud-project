# ⚡ Fault Classification in Power Distribution System using Machine Learning

This project aims to detect and classify different types of electrical faults (like Line-to-Ground, Line-to-Line, and Three-Phase faults) using machine learning. The model is trained on electrical measurement data (e.g., voltage and current phasors) and deployed using IBM Watsonx.ai.

---

## 📊 Problem Statement

Faults in power distribution systems can severely affect grid reliability. Timely and accurate detection of these faults is crucial. This project addresses the challenge by developing an ML model that automates fault classification using real-time electrical measurements.

---

## 🎯 Objectives

- Detect and classify different fault types in a power grid
- Build a reliable and accurate ML model using labeled data
- Deploy the model to IBM Watsonx.ai for cloud-based inference

---

## 🧰 Technologies Used

- Watsonx Runtime
- IBM Cloud
  - Watsonx.ai Studio
  - IBM Cloud Object Storage
- Libraries: pandas, matplotlib, seaborn

---

## 📁 Dataset

- **Type**: Electrical measurement dataset (voltage, current, etc.)
- **Features**: Air temp, process temp, rotation speed, torque, tool wear, etc.
- **Label**: Type of fault (`No Failure`, `Heat Dissipation`, `Power Failure`)

*(Note: Dataset used is from a manufacturing process simulation for testing classification performance.)*

---

## 🧠 Model

- Algorithm: Random Forest Classifier (AutoAI selected Batched Tree Ensemble Classifier)
- Accuracy: **99.5%** (Cross-validated)
- Model Type: Multiclass classification
- Fault Classes:
  - No Failure
  - Heat Dissipation Failure
  - Power Failure

---

## 🚀 Deployment

- Model deployed using IBM Watsonx.ai
- Accessed via REST API interface
- Supports CSV or JSON input formats for real-time prediction

---

## 📈 Results

- High precision and recall across all fault categories
- Confidence scores between **80%–100%**
- Visualizations include confusion matrix and prediction breakdown

---

