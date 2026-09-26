
📊 Customer Segmentation Analysis

An interactive Machine Learning web application built using Streamlit and Scikit-Learn that segments customers into distinct behavioral groups using the K-Means Clustering algorithm.

🔗Live App Demo:
[Customer Segmentation Web App](https://sonamyadav-123-customer-segment-analysis-segmentation-f1etkc.streamlit.app/)


📌 Project Overview
Customer segmentation is a crucial strategy in marketing to understand consumer behavior and tailor targeting strategies. This project analyzes customer data (including Age, Annual Income, and Spending Score) and deploys an intuitive interface where users can input customer metrics to identify their corresponding cluster in real time.


🛠️ Key Features
- Machine Learning Pipeline:- Data preprocessing, feature scaling (`StandardScaler`), and optimal cluster selection using K-Means.
- Interactive UI:- Built with Streamlit for real-time user input and cluster predictions.
- Model Persistence:- Pre-trained model (`kmeans_model.pkl`) and scaler (`scaler.pkl`) saved using `joblib` for instant deployment.

---

📂 Repository Structure
```text
├── Segmentation.py                   # Streamlit web app interface and inference logic
├── Customer Segment Analysis.ipynb   # Jupyter notebook for EDA and model training
├── customer_segmentation.csv         # Dataset used for clustering analysis
├── kmeans_model.pkl                  # Trained K-Means clustering model
├── scaler.pkl                        # StandardScaler object
├── requirements.txt                  # Python dependencies for deployment
└── README.md                         # Project documentation
