🚨 Network Intrusion Detection System (NIDS) using Machine Learning

📡 Electronics & Telecommunication Engineering | Machine Learning Project

🚀 Overview
Modern networks are constantly under threat from a variety of cyber-attacks. Proactive detection is critical for safeguarding communication infrastructure. This project aims to build a robust Network Intrusion Detection System (NIDS) leveraging machine learning, to identify and classify malicious network activity and provide early warnings of potential threats.

🏆 Challenge
Design and implement a system that:

Analyzes real network traffic data

Identifies and classifies multiple types of cyber-attacks:

Denial-of-Service (DoS)

Probe Attacks

Remote-to-Local (R2L)

User-to-Root (U2R)

Accurately differentiates between normal and malicious activity

Provides actionable alerts to help secure communication networks

📊 Dataset
We use the extensively referenced Network Intrusion Detection (NID) Dataset from Kaggle.

Dataset Link: https://www.kaggle.com/datasets/sampadab17/network-intrusion-detection

☁️ Cloud Deployment
Deployment Requirement:
The solution must utilize IBM Cloud Lite services for model serving and monitoring.

💡 Features
->Automatic feature extraction from network packets/traffic logs

->Real-time traffic classification and detection

->Early warning system to alert network administrators

->Visual analytics dashboard for monitoring and reporting

⚙️ Technologies Used
->Python

->Jupyter Notebook

->Scikit-learn, Pandas, NumPy

->IBM Cloud Lite (Watson Studio, Cloud Object Storage, Cloud Functions)

->Matplotlib/Seaborn for visualization

📦 Project Structure
text
/
├── data/                   # Raw and processed datasets
├── notebooks/              # Jupyter Notebooks (EDA, Modeling, etc.)
├── src/                    # Source code (preprocessing, ML pipelines)
├── ibm_cloud_deployment/   # Deployment scripts and configs
├── README.md               # Project documentation
└── requirements.txt        # Dependencies
🚧 Steps to Reproduce
1.Download the dataset from Kaggle and place it in the data/ directory.

2.Environment Setup
Install dependencies:

bash
pip install -r requirements.txt

3.Data Preprocessing & EDA
Explore data and preprocess features (see /notebooks/1_data_preprocessing.ipynb)

4.Model Training & Evaluation
Train, evaluate, and tune models (see /notebooks/2_model_training.ipynb)

5.Deploy to IBM Cloud
Follow instructions in /ibm_cloud_deployment/ to serve the model and set up API endpoints.

6.Monitor & Test NIDS
Send test traffic and monitor intrusion detection alerts via dashboard/notebook.

🚦 Results & Performance
->🚀 Detection Accuracy: e.g., 97%+ on test data

->⏱ Real-time inference latency: sub-second for typical batches

->📊 Attack-type breakdown: Precision/Recall per-attack, ROC curves

📝 Contributors
Pratham.r.pasi

Department of Electronics and Telecommunication Engineering

📬 Contact
For questions or suggestions, please open an issue or contact:
prathampasi124@gmail.com

Let’s make networks safer—one packet at a time! 👨💻🛡️

