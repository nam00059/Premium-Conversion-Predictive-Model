# Freemium to Premium Conversion Prediction

This project builds a machine learning model to identify **freemium users** who are most likely to convert to **premium subscribers** in the next marketing campaign. The goal is to optimize marketing spend by targeting users with the highest probability of adoption, based on behavioral and demographic data.

---

## 🎯 Objective

- Predict which free users are most likely to subscribe to a premium plan
- Prioritize marketing efforts to reduce cost and improve conversion rates

---

## 📊 Tools Used

- **R / RStudio (`.Rmd`)**: Data preprocessing, feature engineering, model building
- **Randomforest Model**: Classification modeling
- **AUC Evaluation**: ROC curves to assess model effectiveness

---

## 📈 Key Insights

- Model achieved **AUC: 0.7718**, indicating strong performance for targeting in an imbalanced dataset
- Model captured **65% of adopters** by targeting only **25% of users**
- **Cost per user decreased by ~50%** compared to random targeting

---

## 📄 Files Included

| File | Description |
|------|-------------|
| `conversion_model.Rmd` | R code for model development (cleaned version) |
| `Premium_Conversion_Slides.pdf` | Project summary slides |
| `XYZData.csv` | Used dataset |

---

## 🔄 Evaluation Framework

We included a **cost-sensitive confusion matrix analysis**, assuming:
- $10/user marketing cost
- $120 lifetime premium revenue per user

This helped minimize **false positives** (wrongly targeted non-adopters), which have higher business cost than false negatives.

---

## 📌 Business Application

- Enables targeted marketing instead of random campaigns
- Improves ROI of user acquisition
- Allows feature-focused messaging (e.g., social features, recommendation system)

---

## 📄 License

This repository is for **educational and portfolio purposes only**.  
All modeling logic and documents were created for academic demonstration and are **not for commercial use**.

---

