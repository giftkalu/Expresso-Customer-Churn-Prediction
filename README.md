
# 📊 Expresso Customer Churn Prediction

A machine learning solution to predict **customer churn** for **Expresso**, an African telecommunications company.
The model identifies customers at risk of becoming inactive (no transactions for 90 days), enabling **proactive retention strategies** to reduce revenue loss and strengthen customer loyalty.

---

## 🚨 Problem Statement

In the competitive telecom industry, **customer churn = lost revenue + higher acquisition costs**.
Expresso needs a predictive system to flag customers at risk of leaving, so they can launch **targeted retention campaigns** before it’s too late.

---

## ⚡ Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/giftkalu/Expresso-Customer-Churn-Prediction.git
cd Expresso-Customer-Churn-Prediction
```

### 2. Set up the environment

```bash
conda env create -f environment.yml
conda activate expresso-churn
```

---

## 🛠️ Requirements

* **Python:** 3.8+
* **Hardware:** 8GB RAM, 4 CPU cores (min)
* **Alternative:** Google Colab (no local setup needed)
* **Dependencies:** Listed in `environment.yml`

---

## ▶️ Usage Workflow

Run the notebook cells in order:

1. **Data Loading & EDA** (\~1–2 mins)
2. **Model Training** (\~3–8 mins)
3. **Model Evaluation** (\~5 mins)

⏱ **Total Runtime:** 9–15 minutes

---

## 📂 Dataset Features

| Feature             | Description                                 |
| ------------------- | ------------------------------------------- |
| **TENURE**          | Length of customer relationship             |
| **DATA\_VOLUME**    | Number of connections by customer           |
| **FREQUENCE**       | Transaction frequency                       |
| **MONTANT**         | Top-up amount                               |
| **FREQUENCE\_RECH** | Recharge frequency                          |
| **ARPU\_SEGMENT**   | Avg. income over 90 days / 3                |
| **REGION**          | Customer location                           |
| **TOP\_PACK**       | Preferred package                           |
| **ON\_NET**         | Inter-Expresso calls                        |
| **ORANGE**          | Calls to Orange network                     |
| **REGULARITY**      | Activity consistency                        |
| **FREQ\_TOP\_PACK** | Preferred package frequency                 |
| **CHURN**           | Target variable (1 = churned, 0 = retained) |

---

## 🤖 Model

* **Algorithm:** Logistic Regression (Scikit-learn Pipeline)
* **Validation:** Cross-validation with log-loss scoring
* **Output:** Probability-based churn predictions (0–1)

---

## 📈 Results

- ✅ Processes customer behavioral & profile data
- ✅ Identifies churn drivers via correlation analysis
- ✅ Outputs churn risk scores for decision-making
- ✅ Interpretable & business-friendly insights

---

## 📁 File Structure

```
├── DSN_HACKATHON FINAL-checkpoint.ipynb # Main notebook
│      
├── Testhackathon.csv    #test data
├── DSN_HACKATHON 10.csv #this was my predicted churn status for each user
├── training data 2.csv #training data was split
├── training data 1.csv
├── assets/
│   └──corr
└── README.md
```

---

## 🤝 Contributing

1. Fork this repository
2. Create a new feature branch
3. Make your changes
4. Submit a pull request

---

## 📜 License

This project was developed as part of the **Microsoft X DSN AI Hackathon**.

---

## 📧 Contact

👤 **Gift Kalu** – Your Creative Data Scientist
🔗 [LinkedIn](https://www.linkedin.com/in/gift-kalu)

