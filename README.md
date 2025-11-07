# ❤️ ML pentru Estimarea Riscului Coronarian & PIR Vision

![Python](https://img.shields.io/badge/language-Python-blue.svg)
![ML](https://img.shields.io/badge/ML-Machine%20Learning-orange.svg)
![Status](https://img.shields.io/badge/status-Completed-success.svg)

---

### 🧠 Descriere

Acest proiect implementează un **pipeline complet de Machine Learning** pentru două tipuri de seturi de date:

1. **Risc Coronarian** ❤️ – predicția probabilității apariției bolilor coronariene.
2. **PIR Vision** 👀 – detectarea prezenței într-un spațiu fizic folosind senzori **Passive Infrared (PIR)**.

Proiectul include explorare de date, preprocesare, antrenarea și evaluarea mai multor modele ML.

🎯 Scopul este de a compara performanța diferitelor algoritme și de a oferi recomandări practice.

---

### 🔍 Explorare și Preprocesare

* Tratarea **valorilor lipsă** și a **outlierilor** 🩺
* Standardizare a variabilelor numerice ⚖️
* **One-Hot Encoding** pentru variabilele categorice 🏷️
* Echilibrare a claselor cu **SMOTE** ⚖️
* Eliminarea atributelor redundante pe baza corelațiilor 🔗

---

### 🤖 Modele de ML utilizate

* **Decision Tree** 🌳
* **Random Forest** 🌲
* **Logistic Regression** 📈
* **Multi-Layer Perceptron (MLP)** 🧠

### ⚙️ Hiperparametri principali

* **Random Forest:** 100 arbori, `max_depth=7`, `class_weight='balanced'`
* **MLP:** două straturi ascunse (50, 25), `early_stopping=True`
* **Decision Tree:** `max_depth=5`, `min_samples_leaf=10`

---

### 📊 Evaluare

* Metrici: **Accuracy, Precision, Recall, F1-score**
* Vizualizări: matrice de confuzie 🗂️, curbe de învățare 📈, barplot-uri comparative 📊
* SMOTE aplicat pentru **echilibrarea clasei minoritare** ⚖️

---

### 🏆 Concluzii

* **Random Forest** 🌲: robust și performant
* **MLP** 🧠: bună generalizare, timp mai mare de antrenare
* **Logistic Regression** 📈: rapid, dar recall mai scăzut pentru clasa minoritară
* **Decision Tree** 🌳: interpretabil, performanță mai slabă

---

### 🚀 Rulare

1. Instalează cerințele:

```bash
pip install -r requirements.txt
```

2. Rulează notebook-urile din `tema.ipynb` pentru a explora și antrena modelele.


---

### 💡 Rezumat conceptual

* ❤️ Detectarea riscului coronarian
* 👀 PIR Vision pentru monitorizarea prezenței
* 🤖 Compararea și optimizarea mai multor modele ML
* 📊 Vizualizări și metrici pentru evaluare comprehensivă
