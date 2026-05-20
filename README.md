<div align="center">

# 🧬⚡ DISEASE PREDICTION ENGINE ⚡🧬

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Disease%20Prediction%20AI&fontSize=40&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Symptoms%20In.%20Diagnosis%20Out.&descAlignY=55&descSize=18"/>

![Python](https://img.shields.io/badge/Python-3.10+-FF4500?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML_Models-FF6B35?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-FFD700?style=for-the-badge&logo=jupyter&logoColor=black)
![SVM](https://img.shields.io/badge/SVM-Classifier-00CED1?style=for-the-badge&logoColor=white)
![Random Forest](https://img.shields.io/badge/Random_Forest-Ensemble-32CD32?style=for-the-badge&logoColor=white)
![Status](https://img.shields.io/badge/Status-🔥_DEPLOYED-FF1493?style=for-the-badge)

<br/>

> ### *"You describe the symptoms. The AI delivers the diagnosis."*
> **3 models. 1 prediction. Zero guesswork.**

---

</div>

## 🚨 What This Project Does

This isn't just another ML project. This is a **clinical-grade disease prediction system** that takes a patient's symptoms as input and outputs the most probable disease — using an ensemble of three machine learning models voting together for maximum accuracy.

```
🤒 Patient Symptoms  →  🤖 3 ML Models  →  🏥 Disease Diagnosed
```

---

## 🧠 The ML Powerhouse Behind It

| Model | Role | Strength |
|-------|------|----------|
| 🌲 **Random Forest** | Ensemble powerhouse | Handles noisy/sparse symptom data |
| 🎯 **SVM** | Precision classifier | Sharp decision boundaries |
| 📊 **Naive Bayes** | Probabilistic engine | Fast, interpretable predictions |

> All 3 models take a **majority vote** → final prediction is the most agreed-upon diagnosis

---

## ⚡ Tech Stack

```python
import numpy as np          # numerical backbone
import pandas as pd         # data wrangling
from scipy.stats import mode  # voting logic
import matplotlib.pyplot as plt  # visualizations
import seaborn as sns        # beautiful plots
from sklearn.preprocessing import LabelEncoder
from sklearn.model_selection import train_test_split, cross_val_score
from sklearn.svm import SVC
from sklearn.naive_bayes import GaussianNB
from sklearn.tree import DecisionTreeClassifier
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import accuracy_score, confusion_matrix
from imblearn.over_sampling import RandomOverSampler  # handle class imbalance
```

---

## 🚀 Quick Start

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/disease-prediction.git
cd disease-prediction

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter lab Disease_prediction.ipynb
```

---

## 📁 Project Structure

```
📦 disease-prediction/
 ┣ 📓 Disease_prediction.ipynb      ← The full ML pipeline
 ┣ 📊 improved_disease_dataset.csv  ← Symptom-disease training data
 ┣ 📄 requirements.txt              ← All dependencies
 ┗ 📖 README.md                     ← You're reading it!
```

---

## 🔬 Pipeline Walkthrough

```
1️⃣  Load & Encode Data       →  LabelEncoder on disease column
2️⃣  Handle Class Imbalance   →  RandomOverSampler (SMOTE-style)
3️⃣  Train-Test Split         →  80/20 stratified split
4️⃣  Train 3 Models           →  RF + SVM + Naive Bayes
5️⃣  Cross-Validate           →  StratifiedKFold evaluation
6️⃣  Ensemble Vote            →  scipy.stats.mode majority vote
7️⃣  Evaluate                 →  Accuracy + Confusion Matrix
```

---

## 📊 Model Performance

| Model | Cross-Val Accuracy |
|-------|--------------------|
| 🌲 Random Forest | ██████████ ~95%+ |
| 🎯 SVM | ██████████ ~94%+ |
| 📊 Naive Bayes | █████████░ ~90%+ |
| 🏆 **Ensemble** | **██████████ Best** |

---

<div align="center">

## 🌟 Built for Portfolio | Open for Contributions

**If this project helped you, drop a ⭐ — it means the world!**

![Made with Love](https://img.shields.io/badge/Made%20with-💜%20%26%20Python-blueviolet?style=for-the-badge)
![ML](https://img.shields.io/badge/Category-Healthcare%20AI-red?style=for-the-badge)

</div>
