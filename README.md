# BETH Cyber Threat Detection

A comprehensive cybersecurity project combining SOC analysis, threat hunting, and deep learning to detect suspicious host activity using the BETH dataset.  
This repository demonstrates real-world blue-team skills, including log analysis, anomaly detection, and machine learning–based threat classification.

---

## ✨ Features

- SOC-style investigation of host activity  
- Suspicious user behavior detection  
- Parent/child process tree analysis  
- Deep learning model using PyTorch  
- Full detection pipeline demonstration  
- Visualizations for class distribution, confusion matrix, and process behavior  
- Clean modular code in the `src/` directory  
- Jupyter notebooks for step-by-step analysis  

---





## 📁 Project Structure
```
beth-cyber-threat-detection/
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


---

## 📥 Dataset

This project uses the **BETH (Behavioral Event Trace Host) dataset**, available on Kaggle.

The raw dataset is **not included** in this repository due to size and licensing restrictions.

Download the dataset from Kaggle and place the files in: data/raw

The processed file should be placed in: data/processed/combined_beth.csv



---

## 🛠️ Installation

Install the required Python packages:
pip install -r requirements.txt


---

## 🚀 How to Run

1. Download the BETH dataset from Kaggle  
2. Place raw CSV files in `data/raw/`  
3. Place the processed file in `data/processed/`  
4. Run the notebooks in order:

   - 01_data_exploration.ipynb  
   - 02_soc_analysis.ipynb  
   - 03_preprocessing_and_feature_engineering.ipynb  
   - 04_model_training_pytorch.ipynb  
   - 05_evaluation_and_visualizations.ipynb  
   - 06_detection_pipeline_demo.ipynb  

5. (Optional) Use the Python scripts in `src/` for automation or integration into a pipeline.

---

## 🧠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
- PyTorch  
- Jupyter Notebook  

---

## 📊 Visuals

The `visuals/` directory contains:

- Class distribution plot  
- Confusion matrix  
- Suspicious user activity visualization  
- Process tree heatmap  

These help illustrate model performance and SOC findings.

---

## 📌 Status

This project is actively being developed.  
More analysis, visualizations, and model improvements will be added.

---

## 📄 License

This project is for educational and cybersecurity research purposes.







---


