# Assessing the Limits of Algorithmic Fairness: An Empirical Evaluation of Reweighing versus Adversarial Debiasing in Credit Scoring

**Author:** Sai Siddartha Geesa  
**Student ID:** 23101848  
**Supervisor:** Dr. Eric Chiejina  
**Institution:** University of Hertfordshire | School of Physics, Engineering and Computer Science  
**Course:** Advanced Computer Science Masters Project (7COM1039-0206-2025)

---

## 📌 Project Overview
This repository contains the official code implementation and final report for my Master's thesis. The project investigates algorithmic fairness within machine learning models used for credit scoring. Specifically, it provides a comprehensive empirical evaluation comparing two distinct bias-mitigation strategies: **Reweighing** (a pre-processing technique) and **Adversarial Debiasing** (an in-processing technique). 

The core objective is to map out the performance-fairness trade-offs and assess the boundary limits of these techniques when striving to eliminate disparate impact and ensure ethical AI decision-making in financial services.

## 📁 Repository Structure
* **`MSc_Project_py.ipynb`**: The primary Jupyter Notebook containing data preprocessing, implementation of fairness algorithms, evaluation metrics, and comparative visualizations.
* **`project final report.pdf`**: The full academic research paper and report submitted to the University of Hertfordshire.

## 🛠️ Toolkits & Libraries Used
The project utilizes the following critical frameworks to evaluate and mitigate machine learning bias:
* **AIF360 (IBM AI Fairness 360)**: Used for measuring fairness metrics and applying debiasing algorithms.
* **XGBoost & Scikit-learn**: Used to build and optimize the baseline credit scoring classification models.
* **Fairlearn**: Utilized for additional algorithmic fairness constraints and metric visualizations.

---
## 🚀 How to Run the Code
You can execute the complete workflow seamlessly via Google Colab:
1. Open the `MSc_Project_py.ipynb` file in this repository.
2. Click the **"Open in Colab"** badge at the top of the file page.
3. Run the setup cells to automatically pull down the required dependencies (such as `pip install aif360 xgboost fairlearn`).
