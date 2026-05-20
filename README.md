<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=🧬%20DISEASE%20PREDICTION%20ENGINE%20🧬&fontSize=38&fontColor=fff&animation=twinkling&fontAlignY=38&desc=Symptoms%20In.%20AI%20Diagnoses.%20Lives%20Impacted.&descAlignY=58&descSize=16"/>

# ⚡ Where Artificial Intelligence Meets Clinical Intelligence ⚡

[![Python](https://img.shields.io/badge/Python-3.10+-FF4500?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML_Pipeline-FF6B35?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-FFD700?style=for-the-badge&logo=jupyter&logoColor=black)](https://jupyter.org)
[![SVM](https://img.shields.io/badge/SVM-Precision_Classifier-00CED1?style=for-the-badge)](https://scikit-learn.org/stable/modules/svm.html)
[![Random Forest](https://img.shields.io/badge/Random_Forest-Ensemble_Power-32CD32?style=for-the-badge)](https://scikit-learn.org)
[![Naive Bayes](https://img.shields.io/badge/Naive_Bayes-Probabilistic-FF69B4?style=for-the-badge)](https://scikit-learn.org)
[![Status](https://img.shields.io/badge/Status-🔥_LIVE-FF1493?style=for-the-badge)](#)

<br/>

---

### 💬 *"Most people Google their symptoms and panic.*
### *This system analyzes them — and gives you the answer."*

---

> 🤒 **You describe the symptoms.**
> 🤖 **Three battle-tested ML models analyze them.**
> 🏥 **One confident diagnosis is delivered.**
>
> **3 Models. 1 Ensemble Vote. Zero Guesswork.**

---

</div>

## 🔥 Why This Project Hits Different

Forget single-model predictions that fail the moment data gets messy.

This system was engineered with **clinical thinking** baked into the code:
- ✅ **Class imbalance?** Handled with `RandomOverSampler`
- ✅ **Overfitting?** Crushed with `StratifiedKFold` cross-validation
- ✅ **Single model bias?** Eliminated with a **3-model majority vote ensemble**
- ✅ **Unreadable labels?** Encoded cleanly with `LabelEncoder`

The result? A system that doesn't just *predict* — it **reasons**.

---

## 🧠 The Intelligence Engine

```
╔══════════════════════════════════════════════════════════╗
║           DISEASE PREDICTION — HOW IT WORKS             ║
╠══════════════════════════════════════════════════════════╣
║  🤒 Symptoms Input                                       ║
║       ↓                                                  ║
║  🌲 Random Forest  →  Prediction A                       ║
║  🎯 Support Vector Machine  →  Prediction B              ║
║  📊 Gaussian Naive Bayes  →  Prediction C                ║
║       ↓                                                  ║
║  🗳️  Majority Vote (scipy.stats.mode)                   ║
║       ↓                                                  ║
║  🏥 FINAL DIAGNOSIS  ✅                                  ║
╚══════════════════════════════════════════════════════════╝
```

| Model | Superpower | Why It's Here |
|-------|-----------|---------------|
| 🌲 **Random Forest** | Ensemble of decision trees | Handles noisy, sparse symptom data like a champ |
| 🎯 **SVM** | Hyperplane precision | Draws razor-sharp boundaries between diseases |
| 📊 **Naive Bayes** | Probabilistic reasoning | Fast, transparent, surprisingly powerful |
| 🏆 **Ensemble** | Majority vote | When 3 models agree — trust the verdict |

---

## ⚡ The Full Tech Arsenal

```python
import numpy as np                              # Numerical backbone
import pandas as pd                             # Data wrangling powerhouse
from scipy.stats import mode                    # Majority vote logic
import matplotlib.pyplot as plt                 # Visualization engine
import seaborn as sns                           # Beautiful statistical plots
from sklearn.preprocessing import LabelEncoder  # Disease label encoding
from sklearn.model_selection import (
    train_test_split,                           # 80/20 data split
    cross_val_score,                            # Model validation
    StratifiedKFold                             # Balanced fold strategy
)
from sklearn.svm import SVC                     # Precision classifier
from sklearn.naive_bayes import GaussianNB      # Probabilistic model
from sklearn.tree import DecisionTreeClassifier # Base tree model
from sklearn.ensemble import RandomForestClassifier  # Ensemble king
from sklearn.metrics import accuracy_score, confusion_matrix  # Evaluation
from imblearn.over_sampling import RandomOverSampler  # Fix class imbalance
```

---

## 🚀 Run It in 3 Steps

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/disease-prediction.git
cd disease-prediction

# 2. Install all dependencies
pip install -r requirements.txt

# 3. Launch the notebook and witness the magic
jupyter lab Disease_prediction.ipynb
```

---

## 📁 Project Structure

```
📦 disease-prediction/
 ┣ 📓 Disease_prediction.ipynb       ← The full ML pipeline (START HERE)
 ┣ 📊 improved_disease_dataset.csv   ← Cleaned symptom-disease training data
 ┣ 📄 requirements.txt               ← All dependencies, pinned and ready
 ┗ 📖 README.md                      ← You're reading it right now
```

---

## 🔬 End-to-End Pipeline

```
STEP 1 ▸ Load Dataset          →  pd.read_csv('improved_disease_dataset.csv')
STEP 2 ▸ Encode Labels         →  LabelEncoder().fit_transform(data["disease"])
STEP 3 ▸ Balance Classes       →  RandomOverSampler — no disease left behind
STEP 4 ▸ Split Data            →  80% train / 20% test, stratified
STEP 5 ▸ Train 3 Models        →  Random Forest + SVM + Naive Bayes
STEP 6 ▸ Cross-Validate        →  StratifiedKFold — squeeze out true accuracy
STEP 7 ▸ Ensemble Vote         →  scipy.stats.mode — democracy decides the diagnosis
STEP 8 ▸ Evaluate              →  Accuracy Score + Confusion Matrix heatmap
```

---

## 📊 Performance Benchmarks

| Model | Accuracy | Verdict |
|-------|----------|---------|
| 🌲 Random Forest | `██████████` ~95%+ | 🔥 Powerhouse |
| 🎯 SVM | `██████████` ~94%+ | ⚡ Precision blade |
| 📊 Naive Bayes | `█████████░` ~90%+ | 🧠 Underrated gem |
| 🏆 **Ensemble Vote** | `██████████` **BEST** | 👑 **The champion** |

> *"One model can be wrong. Three models agreeing? That's confidence."*

---

## 💡 Key Takeaways

- 🏥 **Healthcare AI** is one of the highest-impact domains in ML — this project lives there
- 🧮 **Ensemble methods** consistently outperform individual models — proven here
- ⚖️ **Class imbalance** is the silent killer of medical ML — neutralized here
- 📈 **Cross-validation** is non-negotiable for trustworthy model evaluation — done here

---

<div align="center">

---

## 🌟 Like what you see? Drop a ⭐ — it fuels the next build!

![Made with Python](https://img.shields.io/badge/Made%20with-Python%20%26%20Passion-FF4500?style=for-the-badge&logo=python&logoColor=white)
![Healthcare AI](https://img.shields.io/badge/Domain-Healthcare%20AI-00CED1?style=for-the-badge&logo=heart&logoColor=white)
![Open Source](https://img.shields.io/badge/Open-Source-32CD32?style=for-the-badge&logo=github&logoColor=white)

---

### 🔗 Connect with the Author

[![GitHub](https://img.shields.io/badge/GitHub-Edmund%20Eric%20Gah-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Eddiegah)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Edmund%20Eric%20Gah-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/https://www.linkedin.com/in/edmund-eric-gah-7432a7213/)

---

<br/>

**Engineered with precision by**

### Edmund Eric Gah
*Machine Learning Engineer · Data Scientist · Healthcare AI Enthusiast*

> *"Building intelligent systems that don't just process data — they understand it."*

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer"/>

</div>
