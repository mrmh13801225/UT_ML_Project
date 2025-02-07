Sure! Here’s your `README.md` written in markdown format so you can copy it directly:  

---

# UT ML Project - Speaker Gender Classification & Voice Authentication

This repository contains the implementation of a **Speaker Gender Classification and Voice Authentication** project as part of the UT Machine Learning course. The project involves processing speech signals, extracting features, and applying machine learning models to classify speaker gender and authenticate speaker identity.

## 📌 Project Description

The goal of this project is to develop a machine learning model capable of:

1. **Gender Classification** – Determining whether a given speech sample belongs to a male or female speaker.  
2. **Voice Authentication** – Identifying a speaker based on extracted features from their speech signal.  

## 🔧 Implementation Details

- **Feature Extraction**:  
  - Audio is segmented into **10-second** windows with a **1-second overlap**.  
  - Extracted features include **MFCC, Spectral Centroid, Zero-Crossing Rate, and more**.  
- **Machine Learning Models**:  
  - Classification algorithms: **SVM, Logistic Regression, MLP, AdaBoost, XGBoost**.  
  - Clustering for authentication: **K-Means, Hierarchical Clustering**.  
- **Evaluation Metrics**:  
  - Performance measured using **F1-score, Confusion Matrix, ROC Curve**.  

## 📦 Setup & Installation

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/mrmh13801225/UT_ML_Project.git
cd UT_ML_Project
```

### 3️⃣ Run the Jupyter Notebook
```sh
jupyter notebook FinalProject.ipynb
```

## 📊 Dataset

The dataset consists of **speech recordings** in the format:

```
HWx_Qy_Student-ID_gender.mp3
```

Each file represents a speaker's voice, and the dataset is used for both **gender classification** and **voice authentication** tasks.

## 🚀 Contributors

- **[Mohammadreza Mohammadhashemi](https://github.com/mrmh13801225)**
- **[Roshak Masoudi-Nejad](https://github.com/Rmasoudin)**
- **[Niusha Zand](https://github.com/niushazand)**

## 📜 License

This project is licensed under the **MIT License**.

---

Feel free to modify or extend this `README.md` based on additional features you implement! 🚀

---

Now you can just copy and paste this directly into your `README.md` file! Let me know if you need any edits. 🚀
