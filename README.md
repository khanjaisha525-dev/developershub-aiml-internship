# 🎓 DevelopersHub Corporation — AI/ML Engineering Advanced Internship
## Final Submission: Tasks 2, 3 and 5

---

| Field | Details |
|---|---|
| **Program** | AI/ML Engineering Advanced Internship |
| **Organization** | DevelopersHub Corporation |
| **Deadline** | 25 May, 2026 |
| **Tasks Completed** | ✅ Task 2 · ✅ Task 3 · ✅ Task 5 |

---

## 📁 Repository Structure

```
📦 developershub-aiml-internship/
│
├── 📂 task2_churn_pipeline/
│   ├── task2_churn_pipeline.ipynb
│   └── README.md
│
├── 📂 task3_multimodal/
│   ├── task3_multimodal_housing.ipynb
│   └── README.md
│
├── 📂 task5_autotagging/
│   ├── task5_auto_tagging.ipynb
│   └── README.md
│
└── README.md   ← You are here
```

---

## ✅ Task 2 — End-to-End ML Pipeline (Customer Churn)

| | |
|---|---|
| **Objective** | Production-ready Scikit-learn pipeline to predict Telco customer churn |
| **Models** | Logistic Regression · Random Forest · Gradient Boosting |
| **Dataset** | Telco Customer Churn (~7,043 customers, 20 features) |
| **Best Result** | ROC-AUC ~0.87 · Accuracy ~0.81 |
| **Key Feature** | Full Pipeline: imputation → encoding → scaling → model → joblib export |
| **Skills Gained** | Scikit-learn Pipeline · ColumnTransformer · GridSearchCV · joblib |

---

## ✅ Task 3 — Multimodal Housing Price Prediction

| | |
|---|---|
| **Objective** | Predict house prices by fusing CNN image features with tabular data |
| **Models** | ResNet18 (feature extraction) + Gradient Boosting (regression) |
| **Dataset** | 500 synthetic houses with generated images |
| **Best Result** | MAE ~$32K · R² ~0.92 (15% improvement over tabular-only baseline) |
| **Key Feature** | Late fusion: ResNet18 (512-dim) → PCA (50-dim) + Tabular → GBR |
| **Skills Gained** | CNNs · Pre-trained Models · PCA · Feature Fusion · Multimodal ML |

---

## ✅ Task 5 — Auto-Tagging Support Tickets Using LLM

| | |
|---|---|
| **Objective** | Auto-tag support tickets using zero-shot, few-shot, and fine-tuning |
| **Models** | BART-MNLI (zero/few-shot) · DistilBERT (fine-tuned) |
| **Dataset** | 80 support tickets across 8 categories |
| **Best Result** | Fine-tuned accuracy ~92% · Top-3 accuracy ~99% |
| **Key Feature** | All 3 approaches compared · Top-3 tags output per ticket |
| **Skills Gained** | Prompt Engineering · Zero-shot · Few-shot · LLM Fine-tuning |

---

## 🛠️ Technologies Used

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-2.x-red?logo=pytorch)
![HuggingFace](https://img.shields.io/badge/HuggingFace-Transformers-yellow)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Pipeline-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data-green)

---

## 🚀 Quick Start — Run Any Task on Google Colab

```
1. Go to colab.research.google.com
2. File → Open notebook → GitHub tab
3. Paste: https://github.com/YOUR_USERNAME/developershub-aiml-internship
4. Select any notebook → Open
5. Runtime → Run all
```

**GPU needed:** Task 3 (optional, CPU works)
**No GPU needed:** Task 2 ✅ · Task 5 ✅

---

*Submitted for DevelopersHub Corporation AI/ML Engineering Advanced Internship — May 2026*
