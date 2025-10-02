# 🔐 Machine Learning-Based Intrusion Detection System (IDS)

This project evaluates multiple **machine learning models** for detecting malicious network traffic, focusing on DNS spoofing, backdoor malware, DoS, and DDoS attacks.  
We compare traditional classifiers, advanced supervised algorithms, neural networks, and anomaly detection models to determine their effectiveness in real-world cybersecurity scenarios.  

---

## 👩‍💻 Authors
- Amani Albarazi  
- Haifa Muhammad  
- Raghad Alamoudi  
- Maram Alhusami  

---

## 📊 Abstract
Intrusion Detection Systems (IDS) are essential for identifying malicious activities in network traffic. Traditional IDS often fail against novel or evolving attacks.  
This study evaluates **Random Forest, SVM, XGBoost, MLP, CNN, Isolation Forest, and Autoencoders**, achieving high accuracy and robustness in detecting both known and unseen attacks.  

---

## 🎯 Objectives
- Compare performance of **traditional ML models vs. neural networks vs. anomaly detectors**  
- Evaluate metrics: **accuracy, precision, recall, F1-score**  
- Align findings with **UN SDGs** and **Saudi Vision 2030** (cybersecurity, digital transformation, economic diversification).  

---

## 📑 Datasets
The study uses multiple **PCAP-derived datasets** containing real attack traces:
- `Backdoor_Malware.pcap.csv`
- `DoS-TCP_Flood.pcap.csv`
- `DoS-UDP_Flood.pcap.csv`
- `DDoS-TCP_Flood.pcap.csv`
- `Merged_Attacks.csv` (combined attacks dataset)

⚠️ **Note:** Datasets are too large for GitHub.  
 Download the full dataset from Google Drive: (https://drive.google.com/file/d/1ICQtOt88CdG3CiVbdhCwJuzqd18tyLSX/view?usp=drive_link)  

---

## 🛠️ Methods
- **Traditional ML Models**: Logistic Regression, Decision Trees, k-NN, Random Forest, XGBoost  
- **Advanced Models**: ExtraTrees, Ridge Classifier, LDA, QDA, Gradient Boosting, AdaBoost, LightGBM  
- **Neural Networks**: Multi-Layer Perceptron (MLP), CNN (TensorFlow/Keras)  
- **Anomaly Detection**: Isolation Forest, Autoencoders
---
## 📊 Results

We evaluated a range of traditional machine learning and deep learning models for Intrusion Detection.  
The table below summarizes the **performance comparison** across Accuracy, Precision, Recall, and F1-Score.

| Model                                | Accuracy (%) | Precision | Recall | F1-Score |
|--------------------------------------|--------------|-----------|--------|----------|
| Logistic Regression (LR)             | 85.2         | 0.84      | 0.85   | 0.84     |
| K-Nearest Neighbors (KNN)            | 82.7         | 0.81      | 0.83   | 0.82     |
| Decision Tree (DT)                   | 86.5         | 0.85      | 0.86   | 0.85     |
| Random Forest (RF)                   | **91.4**     | **0.91**  | **0.91** | **0.91** |
| Gradient Boosting (GB)               | 89.9         | 0.89      | 0.90   | 0.89     |
| AdaBoost                             | 88.3         | 0.87      | 0.88   | 0.87     |
| LightGBM                             | 90.2         | 0.90      | 0.90   | 0.90     |
| ExtraTrees Classifier                | 90.8         | 0.90      | 0.91   | 0.90     |
| Scikit-learn MLP Classifier          | 89.7         | 0.89      | 0.90   | 0.89     |
| Neural Network (TensorFlow/Keras)    | **92.5**     | **0.92**  | **0.93** | **0.92** |

✅ **Best Performance:** Neural Network (TensorFlow/Keras) achieved the highest accuracy and F1-score, closely followed by Random Forest and LightGBM.  

---

## 🔮 Future Work
- **Ensemble Modeling**: Combining multiple ML and DL models for stronger robustness.  
- **Expanded Attack Coverage**: Testing on wider attack types (e.g., phishing, ransomware).  
- **Real-Time Deployment**: Implementing IDS in live network traffic monitoring.  
  

