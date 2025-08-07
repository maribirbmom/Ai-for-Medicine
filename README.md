# 🧠 AI for Medicine: Diagnosis, Prognosis & Treatment Estimation

This repository showcases my work through the [AI for Medicine Specialization](https://www.coursera.org/specializations/ai-for-medicine) by deeplearning.ai, which applies machine learning to real-world medical challenges — from diagnosing diseases in medical images to predicting patient survival and estimating treatment outcomes.

---

## 📌 Why this project?

Healthcare and AI are deeply intertwined, and I wanted to explore how ML models can assist in real clinical decision-making. This project helped me:
- Build deep learning models for **disease diagnosis** using medical imaging
- Predict patient **risk and survival** using statistical and ML models
- Estimate the **effectiveness of treatments** using causal inference
- Learn how to **interpret ML predictions** in healthcare contexts

---

## 💡 What this project does

Across three in-depth courses, I implemented:
- 🩻 Diagnostic CNNs for chest X-rays and MRI segmentation
- 📈 Prognostic models using linear regression, survival trees, and Kaplan-Meier estimators
- 💊 Treatment effect models using T-learners, S-learners, and causal metrics like C-for-benefit
- 🧠 Model explainability using GradCAM, permutation importance, and feature drop methods
- 🔍 NLP for medical label extraction and question-answering systems

---

## 📘 Courses & Core Concepts

### 1️⃣ AI for Medical Diagnosis
**Goal:** Classify diseases from X-ray & MRI scans using deep learning  
**Key Topics:**
- Class imbalance strategies (weighted loss, resampling)
- CNN architectures (DenseNet, Multi-task learning)
- U-Net for brain tumor segmentation
- Evaluation: AUC, ROC curves, sensitivity/specificity

> ✅ Projects: Chest X-ray classification, Brain Tumor Auto-Segmentation  
> 🎯 Grade: 100% (Assignments)

---

### 2️⃣ AI for Medical Prognosis  
**Goal:** Predict patient outcomes and survival probability  
**Key Topics:**
- Linear and tree-based prognostic models
- Time-to-event data and right censoring
- Kaplan-Meier, Cox PH, Nelson-Aalen estimators
- Handling missing data (MCAR, MAR, MNAR)
- Individualized risk predictions

> ✅ Projects: Risk Scoring, Kaplan-Meier Estimation, Tree-based Survival Models  
> 🎯 Grade: 90% – 100%

---

### 3️⃣ AI for Medical Treatment  
**Goal:** Estimate individualized treatment outcomes using ML  
**Key Topics:**
- Randomized control trials & causal inference
- Average & Conditional Treatment Effect (ATE, CATE)
- T-Learner & S-Learner architectures
- C-for-benefit metric
- Interpreting CNNs (GradCAM), Label Extraction with NLP

> ✅ Projects: Treatment Effect Models, Logistic Interpretation, GradCAM, NLP Labeling  
> 🎯 Grade: 100%

---

## 🗂️ Repository Structure

```bash
AI-for-Medicine/
├── 01-AI-for-Medical-Diagnosis/
│   └── X-ray classification, MRI segmentation, model evaluation
├── 02-AI-for-Medical-Prognosis/
│   └── Risk prediction, Survival analysis, Tree models
├── 03-AI-for-Medical-Treatment/
│   └── Causal inference, GradCAM, NLP for label extraction
