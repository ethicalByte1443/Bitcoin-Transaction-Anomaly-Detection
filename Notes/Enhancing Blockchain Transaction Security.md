# 🧠 Research Notes: Hybrid ML for Blockchain Transaction Security

## 🗺️ Flowchart Overview

![Flowchart](https://drive.google.com/uc?export=view&id=1KvOD3tfaiRkMxaoRUpiBfgAD2pvEPTfq)


This flowchart represents the conceptual framework for the research project:  
**"Enhancing Blockchain Transaction Security: A Hybrid Machine Learning Approach for Fraud Detection."**

---

## 📑 Key Notes from the Research Paper

### 🔍 Motivation
- Blockchain, though secure, is not immune to fraud such as **Sybil attacks**.
- There’s a pressing need for adaptive, robust fraud detection methods as traditional models fall short against evolving threats.

### 🧪 Problem Definition
- Detect malicious behaviors such as Sybil attacks using a **hybrid ML system**.
- Improve detection accuracy and adaptability to both known and novel threats.

---

## 📚 Literature Review

| Category              | Details |
|----------------------|---------|
| Supervised Learning  | Logistic Regression, Neural Networks, Random Forest, XGBoost |
| Unsupervised Learning| Autoencoders, K-Means |
| Hybrid Approaches    | Stacked/ensemble systems combining both methodologies |
| Emerging Tech        | BERT-based transformers for temporal and behavioral analysis |

---

## 🏗️ Model Training Workflow

- Data split into training (80%) and testing (20%).
- Key models used:
  - **Random Forest** (for classification)
  - **Autoencoder** (for feature compression)
  - **Hybrid System**: Combines RF + Autoencoder

---

## 📈 Performance Highlights

### ✅ Results from AUC Score (Area Under Curve):
- Random Forest: **0.88**
- Autoencoder: **0.86**
- Hybrid System: **0.91** → Best performance
- K-Means Clustering: **0.75** → Lowest

### 📊 Evaluation Metrics Table

| Model        | Precision | Recall | F1 Score | Accuracy |
|--------------|-----------|--------|----------|----------|
| Random Forest| 0.85      | 0.87   | 0.86     | 0.88     |
| Autoencoder  | 0.81      | 0.83   | 0.82     | 0.84     |
| Hybrid System| **0.89**  | **0.90**| **0.89** | **0.91** |
| K-Means      | 0.67      | 0.71   | 0.69     | 0.73     |

---

## 🧠 General Findings

- Supervised methods detect known fraud well but struggle with novel patterns.
- Unsupervised methods are good for unknown anomalies but suffer with imbalance.
- **Hybrid models offer the best of both worlds** — higher adaptability and performance.
- Emerging techniques like **FinBERT** and explainable AI frameworks offer future potential.

---

> 📌 *This summary is based on the core insights extracted from the research paper and visualized above.*
