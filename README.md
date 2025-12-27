# JPMorgan-Chase-Quant-Research
# Quantitative Research Portfolio (JPMorgan Chase Virtual Experience)

This repository contains my solutions for the quantitative research tasks, focusing on commodities pricing and credit risk modeling.

## 📂 Project Structure

### 1. Natural Gas Price Forecasting (`1_Natural_Gas_Pricing.ipynb`)
* **Problem:** Traders need to predict future gas prices to value storage contracts.
* **Solution:** Built a pricing model using **Linear Regression** for trend analysis and sine-wave decomposition for **seasonality**.
* **Outcome:** Accurate 12-month extrapolation used to value a $1.2M storage contract.

### 2. Credit Risk Modeling (`2_Loan_Default_Prediction.ipynb`)
* **Problem:** The bank needs to estimate the expected loss on a loan portfolio.
* **Solution:** Developed a **Logistic Regression** model to predict Probability of Default (PD) with **99% accuracy**.
* **Outcome:** A robust function to calculate capital requirements based on borrower attributes.

### 3. FICO Score Quantization (`3_FICO_Score_Quantization.ipynb`)
* **Problem:** Raw FICO scores (300-850) are difficult to use in macro-risk models; they need to be bucketed into ratings.
* **Solution:** Implemented a **Dynamic Programming** algorithm to maximize log-likelihood, finding the mathematical optimal cutoff points for credit ratings.
* **Outcome:** A rating map that monotonically separates default risk.

## 🛠️ Tech Stack
* **Python:** Pandas, NumPy, Scikit-Learn, Matplotlib
* **Concepts:** Financial Engineering, Machine Learning, Optimization Algorithms

---
*Note: Completed as part of the JPMorgan Chase & Co. Quantitative Research Virtual Experience on Forage.*
