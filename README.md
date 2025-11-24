# Arabic Hope & Hate Speech Detection (MAHED 2025)

[![Conference](https://img.shields.io/badge/Accepted-ArabicNLP%202025-blue)](https://sites.google.com/view/arabicnlp2025)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8%2B-green)](https://www.python.org/)

> **Official implementation** of the paper: *"[INSERT YOUR EXACT PAPER TITLE HERE]"* > **Accepted at:** The 3rd ArabicNLP Workshop (co-located with EMNLP 2025).

## 📄 Abstract
This repository contains the system description and code for our submission to the **MAHED Shared Task** (Subtask 1). We developed a deep learning pipeline to classify Multi-dialect Arabic tweets into three categories: **Hope**, **Hate**, or **Neither**.

Our approach leverages **[Insert Model Name, e.g., AraBERT/Marbert]** fine-tuned on the MAHED dataset, utilizing **[mention any special technique, e.g., data augmentation, class balancing, or hyperparameter tuning]**.

## 🚀 Key Features
* **Transformer-Based:** Fine-tuned on state-of-the-art Arabic Language Models (AraBERT/MARBERT).
* **Preprocessing Pipeline:** Custom cleaning for Arabic text (normalization, stop-word removal, emoji handling).
* **Reproducibility:** Full training notebooks and inference scripts included.

## 📊 Performance (Results)
Our system achieved the following results on the MAHED test set:

| Model | Accuracy | Macro F1-Score |
| :--- | :---: | :---: |
| **Our System (Best Run)** | **[00.00]%** | **[00.00]%** |
| Baseline | [00.00]% | [00.00]% |

## 🛠️ Installation & Usage

### 1. Clone the repository
```bash
git clone [https://github.com/Ebad-urRehman/Arabic-Hope-Hate-Detection.git](https://github.com/Ebad-urRehman/Arabic-Hope-Hate-Detection.git)
cd Arabic-Hope-Hate-Detection
