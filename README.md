# Analisi del Dataset Titanic — Data Mining Project

Progetto di Data Mining realizzato da **Lorenzo Canocchi** e **Paolo Donati**  
*Istituto Tecnico Statale G. Marconi — A.S. 2024/2025*

---

## Descrizione

Analisi completa del dataset dei passeggeri del Titanic, con l'obiettivo di identificare i fattori che hanno influenzato la sopravvivenza. Il progetto copre l'intero flusso di data mining: dalla preparazione dei dati alla classificazione supervisionata.

---

## Struttura del Progetto

| Fase | Contenuto |
|------|-----------|
| **Data Understanding** | Analisi semantica e statistica, distribuzione delle variabili, valori mancanti, outlier (IQR), matrice di correlazione |
| **Preparazione dati** | Split 60/20/20, normalizzazione (StandardScaler, MinMaxScaler), riduzione dimensionale con PCA |
| **Clustering** | K-Means, DBSCAN, Clustering Gerarchico |
| **Classificazione** | KNN, Logistic Regression, SVM, Decision Tree, Random Forest, Gradient Boosting, MLP |
| **Ottimizzazione** | Grid Search sui migliori 3 modelli (SVM, Random Forest, Gradient Boosting) |

---

## Risultati Principali

Il confronto delle accuratezze sul validation set:

| Modello | Accuratezza |
|---------|-------------|
| Logistic Regression | 0.798 |
| K-Nearest Neighbors | 0.820 |
| **Support Vector Machine** | **0.854** |
| Decision Tree | 0.787 |
| Random Forest | 0.826 |
| Gradient Boosting | 0.848 |
| Neural Network (MLP) | 0.837 |

Il modello migliore dopo Grid Search è risultato **SVM** con accuratezza di validazione **0.8596** e accuratezza sul test set **0.80**.

---

## Tecnologie Utilizzate

- Python 3
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

---

## Dataset

[Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic) — Kaggle
