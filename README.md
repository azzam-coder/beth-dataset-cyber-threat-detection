# beth-dataset-cyber-threat-detection
“A comprehensive cybersecurity project combining SOC analysis, threat hunting, and deep learning to detect suspicious host activity using the BETH dataset.”

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
