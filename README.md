# 🧠 Knowledge Distillation Mini Lab

A concise, reproducible experiment on **Knowledge Distillation for Graph Neural Networks (GNNs)** — inspired by the paper **"A Survey on Model Extraction Attacks and Defenses for Large Language Models"**.

This mini-lab demonstrates how **teacher-student distillation** can preserve model performance while reducing model size, and how **soft targets** outperform hard labels during transfer.

---

## 🚀 Highlights

| Model | Accuracy (%) | Agreement with Teacher (%) |
|:------|:-------------:|:--------------------------:|
| **Teacher** | 81.72 | — |
| **Student (Hard Distillation)** | 72.65 | 73.90 |
| **Student (Soft Distillation)** | 73.75 | 74.79 |

✅ **Soft Distillation improves student performance**  
✅ **Reproducible in Colab**  
✅ **Code is clean, lightweight, and research-oriented**

---

## 🧩 Background

This project draws inspiration from:
> *A Survey on Model Extraction Attacks and Defenses for Large Language Models (2023)*

It explores how **knowledge distillation**, originally designed for model compression, can also play a role in **defending against model extraction attacks**.

---

## 🧠 What’s Inside

- `GNN_Knowledge_Distillation_Colab.ipynb`  
  👉 Includes:
  - Teacher & Student GNN definition  
  - Hard vs Soft Distillation pipelines  
  - Evaluation (Accuracy & Teacher Agreement)  
  - Visualization of results  

---

## ▶️ Run in Google Colab

Just click below to start!

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wajason/knowledge-distillation-mini-lab/blob/main/GNN_Knowledge_Distillation_Colab.ipynb)

---

## 📊 Results Summary

Soft Distillation outperformed Hard Distillation with **+1.1% accuracy** and better agreement with the teacher model, showing that **temperature scaling and soft targets help preserve teacher knowledge more effectively**.

---

## 🧠 Future Work

- Explore **feature-based distillation** (e.g., attention transfer)  
- Try **different student architectures** (simplified GCN, GAT, or GraphSAGE)  
- Analyze **robustness under model extraction scenarios**

---

## 💫 Citation (optional)

If this work helps your study or project, please consider citing:
@misc{wajason2025knowledge,
author = {Jason Huang},
title = {Knowledge Distillation Mini Lab},
year = {2025},
url = {https://github.com/wajason/knowledge-distillation-mini-lab}

}
---

## ⭐ Give a Star!

If you find this project interesting or helpful, 
**please give it a ⭐ to support! Thanks~~**

