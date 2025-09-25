# Causal Inference for Credit Risk Analysis 🔬

## 🎯 Project Overview

In the lending industry, predicting *who* will default is a standard task. However, to create proactive and effective risk mitigation strategies, we needed to understand *why* they default. This project moves beyond traditional predictive modeling to uncover the true causal drivers of loan default.

The goal was to provide the business with a highly explainable model that could serve as the foundation for a new, data-driven intervention strategy to reduce credit losses.

---

## 💡 Solution: From Prediction to Causation

Instead of a standard classification model that only identifies correlations, I researched and implemented an **Auto-Causal Inference (ACI)** model. This advanced technique allowed me to estimate the direct, isolated causal effect of specific borrower characteristics (like Debt-to-Income ratio) on their likelihood of default, while controlling for other confounding factors.

This approach elevated the project from a simple prediction task to a powerful strategic tool.

---

## 🔑 Key Finding & Business Strategy

The causal analysis revealed a powerful and actionable insight:

**A customer's Debt-to-Income (DTI) ratio exceeding a 40% threshold was identified as a key causal driver of default.**

Based on this data-backed insight, I proposed a new, proactive business strategy: instead of just screening applicants, we could intervene. We developed a pilot program to offer optional financial counseling to at-risk applicants with a DTI ratio in the 35-40% range, before they are approved for a loan.

---

## 🚀 Quantified Impact & Results

The new strategy, informed directly by the causal analysis, was projected to have a significant financial impact:

* **✅ 15% Projected Reduction in Default Rate:** The pilot program was forecast to reduce defaults within this specific, targeted customer segment by 15%.
* **✅ From Prediction to Proactive Strategy:** This project demonstrated the ability to deliver not just a model, but a tangible business strategy based on a robust, explainable analysis that a simple predictive model could not have provided.

---

## 🛠️ Tech Stack

* **Data Analysis & Modeling:** `Python`, `Pandas`, `Scikit-learn`, `Auto-Causal Inference Libraries`
* **Data Extraction:** `SQL`
* **Environment:** `Databricks`, `Jupyter Notebook`

---

## 📂 Repository Structure

├── sql_queries/
│   └── extract_default_data.sql
├── notebooks/
│   └── causal_inference_for_default_analysis.ipynb
├── requirements.txt
└── README.md
