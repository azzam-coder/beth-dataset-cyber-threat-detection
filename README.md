# BETH Cyber Threat Detection

**A comprehensive cybersecurity project combining SOC analysis, threat hunting, and deep learning to detect suspicious host activity using the BETH dataset.**

---

## 📁 Project Structure
```
beth-dataset-cyber-threat-detection/
│
├── README.md
├── requirements.txt
│
├── data/
│   ├── raw/
│   │   ├── labelled_2021may-ip-10-100-1-105.csv
│   │   ├── labelled_2021may-ip-10-100-1-186.csv
│   │   ├── labelled_2021may-ip-10-100-1-26.csv
│   │   ├── labelled_2021may-ip-10-100-1-4.csv
│   │   ├── labelled_2021may-ip-10-100-1-95.csv
│   │   ├── labelled_2021may-ubuntu.csv
│   │
│   ├── processed/
│       ├── combined_beth.csv
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_soc_analysis.ipynb
│   ├── 03_preprocessing_and_feature_engineering.ipynb
│   ├── 04_model_training_pytorch.ipynb
│   ├── 05_evaluation_and_visualizations.ipynb
│   ├── 06_detection_pipeline_demo.ipynb
│
├── src/
│   ├── data_loader.py
│   ├── preprocessing.py
│   ├── model.py
│   ├── train.py
│   ├── evaluate.py
│   ├── utils.py
│
└── visuals/
├── class_distribution.png
├── confusion_matrix.png
├── suspicious_users.png
├── process_tree_heatmap.png  

```
---

## 📌 Overview

This project analyzes the **BETH dataset**, a real-world labeled cybersecurity dataset containing system-level events from multiple hosts.  
It includes:

- SOC-style threat analysis  
- Parent/child process investigation  
- Suspicious user behavior analysis  
- Deep learning classification using PyTorch  
- A full detection pipeline  

---

## 🧠 Goals

- Detect suspicious host activity  
- Understand malicious process behavior  
- Build a machine learning model for threat detection  
- Create a SOC-ready analysis workflow  

---

## 🛠️ Technologies

- Python  
- Pandas  
- PyTorch  
- Scikit-learn  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## 🚀 Status

Project in progress — notebooks and analysis being added step by step.
