# Suspicious Transaction Detection Using Machine Learning

This project utilizes machine learning models to detect suspicious transactions in a dataset, specifically for **anti-money laundering (AML)** purposes. We implement **One-Class SVM** and **Isolation Forest** models to identify anomalies in financial transactions. The goal of this project is to detect potentially suspicious transactions in real-time and flag them for further investigation.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Setup & Installation](#setup-installation)
4. [Model Implementation](#model-implementation)
5. [Running the Application](#running-the-application)
6. [Results & Evaluation](#results-evaluation)
7. [Future Scope](#future-scope)
8. [References](#references)

---

## Project Overview

This project involves detecting suspicious transactions using a **synthetic dataset**. The key tasks include:

- **Data Preprocessing:** Clean and prepare the data for analysis.
- **Exploratory Data Analysis (EDA):** Analyze the transaction data and identify patterns.
- **Model Selection & Training:** Use machine learning models like **One-Class SVM** and **Isolation Forest** to detect anomalies.
- **Deployment:** Create a **Streamlit web application** that predicts whether a transaction is suspicious based on user input.

The models are trained using features like the **Amount**, **Sender Account**, and **Receiver Account** to predict whether a transaction is **Suspicious** or **Normal**.

---

## Dataset

The dataset used in this project is the **Synthetic Transaction Monitoring Dataset for AML** available on Kaggle. This dataset contains synthetic financial transaction data designed to mimic real-world transaction monitoring systems used for anti-money laundering (AML) purposes.

### How to Download the Dataset

Follow these steps to download the dataset:

1. **Install Kaggle API:**

   If you haven’t installed the Kaggle API, install it by running:
   ```bash
   pip install kaggle
