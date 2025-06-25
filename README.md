# 🔐 Behavior-Based Insider Threat Detection

This project is designed to detect insider threats in an organization by analyzing user behavior patterns using machine learning. Unlike traditional security systems that rely on rules or signatures, this approach uses behavioral anomalies to flag potentially malicious users.

---

## 📁 Project Overview

- *Goal:* Identify users with abnormal activity that could indicate insider threats.
- *Input:* User activity logs (login, file access, device usage, etc.).
- *Output:* List of users predicted to be malicious or benign.
- *ML Models Used:*  
  - 🟩 Random Forest (Supervised Classification)  
  - 🟦 LSTM Autoencoder (Unsupervised Anomaly Detection)

---

## 🧠 How It Works

1. The system is trained using a user behavior dataset from *Kaggle*.
2. When a new user log file is uploaded (CSV format), it is:
   - Preprocessed
   - Evaluated by the trained models
3. Users showing behavioral deviations are flagged as potential threats.

---

## 📂 Dataset

The dataset used for this project is publicly available on *Kaggle*, containing simulated user activity logs including:
- Logon/logoff events
- File accesses
- Device connections
- Command line usage

📎 Due to file size, the dataset is hosted externally:  
👉 [Download from Google Drive](https://drive.google.com/your-public-link-here)

---

## 🚀 Features

- Upload user activity logs for prediction
- Dual-model threat detection (Random Forest + LSTM Autoencoder)
- Behavioral pattern analysis instead of static rule-checking
- Built for easy understanding and academic demonstration

---

## 🛠️ Tech Stack

- Python  
- Pandas, NumPy, Scikit-learn  
- TensorFlow / Keras  
- Matplotlib / Seaborn (for visualization)

---

## ⚠️ Note

This project is part of my academic work and personal portfolio.  
Please *do not reuse or submit* this work as your own. It is shared for *educational and demonstration purposes only.*

## 👩‍💻 Author
Nitha N 
