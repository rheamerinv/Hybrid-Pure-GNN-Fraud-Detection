# Hybrid & Pure GNN Fraud Detection

## 🚀 Project Overview
This project implements **financial fraud detection** using **Graph Neural Networks (GNNs)** on two datasets: **PaySim** (synthetic mobile transactions) and **Credit Card Transactions** (real-world dataset).  

The project was developed as part of my **MSc in Computer Science** at **[Your University Name]**, where I focus on **AI, machine learning, and data analytics**.  

We address the limitations of conventional fraud detection models by developing a **hybrid system** that combines **data-driven GNNs** with **symbolic AI rules**, leveraging both predictive power and interpretable reasoning.  

---

## 📊 Datasets
Both datasets are publicly available on Kaggle:

1. **PaySim (synthetic mobile transactions)**  
   [Link to dataset](https://www.kaggle.com/datasets/ealaxi/paysim1)  
   - Simulates mobile financial transactions with labeled fraud cases.

2. **Credit Card Transactions**  
   [Link to dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
   - Real-world credit card transactions with highly imbalanced classes.  

---

## 🧠 Models

### **Credit Card Dataset (CCD)**
- Pure GNN: **GCN, GAT, GraphSAGE**  
- Hybrid: **GNN + symbolic rules** (incorporates domain rules for fraud patterns)

### **PaySim Dataset**
- Pure GNN: **GCN, GAT, GraphSAGE**  
- Hybrid: **GNN + symbolic rules** (detects dynamic fraud rings in real-time streaming)

---

## 🎬 Real-Time Demo
- **Kafka-based streaming simulation**  
- **Streamlit dashboard** with live fraud scores and visualization of fraud rings  
- Demonstrates **hybrid GNN + symbolic AI** applied to PaySim transactions


---

## 🏫 Academic Context
- Developed as part of my **MSc in Computer Science** at **[Your University Name]**  
- Focused on **Advanced Machine Learning, Graph Neural Networks, and AI for Financial Fraud Detection**  
- Combines research skills (literature review, symbolic AI) with **practical engineering** (Kafka, Streamlit, Python)

---

## 🗂 Project Structure

project-folder/
├── demo/ # End-to-end demo: dataset prep, model, streaming
├── eda/ # Exploratory Data Analysis for PaySim & Credit Card datasets
├── models/ccd/ # Credit Card dataset: Pure & Hybrid GNN models
├── models/paysim/ # PaySim dataset: Pure & Hybrid GNN models
├── requirements.txt # Python dependencies
├── README.md

---

## Tech Stack 
![Python](https://img.shields.io/badge/-Python-333333?style=flat&logo=python) 
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch) 
![Kafka](https://img.shields.io/badge/-Kafka-231F20?style=flat&logo=apachekafka) 
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat&logo=streamlit) 



