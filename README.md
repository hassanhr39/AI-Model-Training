# 🏠 House Price Prediction with Linear Regression

This project uses a **Linear Regression model** to predict house prices based on features like area, number of bedrooms, and bathrooms. It’s a simple end-to-end machine learning pipeline using **Python**, **pandas**, **scikit-learn**, and **matplotlib**.

---

## 📊 Dataset

The dataset used is a small CSV file named `house_prices.csv`, containing:

| Area (sq ft) | Bedrooms | Bathrooms | Price ($) |
|--------------|----------|-----------|-----------|
| 1000         | 2        | 1         | 150,000   |
| 1200         | 3        | 2         | 180,000   |
| 1500         | 3        | 2         | 200,000   |
| 1800         | 4        | 2         | 250,000   |
| 2000         | 4        | 3         | 300,000   |
| 2500         | 5        | 3         | 360,000   |
| 2700         | 5        | 3         | 400,000   |
| 3000         | 5        | 4         | 450,000   |

---

## ⚙️ Technologies Used

- **Python 3**
- **pandas** – data loading & preprocessing
- **scikit-learn** – model training & evaluation
- **matplotlib** – plotting predictions

---

## 🚀 How It Works

1. The dataset is loaded using `pandas`.
2. Features (`area`, `bedrooms`, `bathrooms`) are separated from the target (`price`).
3. A Linear Regression model is trained using `scikit-learn`.
4. The model makes predictions on:
   - A new house (e.g., `1600 sq ft`, `3 bed`, `2 bath`)
   - The full dataset (for evaluation)
5. It computes the **R² Score** to evaluate model accuracy.
6. A scatter plot shows actual vs predicted prices.

---

## 🔍 Sample Output

```plaintext
Predicted price: $215,714.29
R² Score: 0.98
```
---

## 👨‍💻 Author
Mohammad Hassan
GitHub: @hassanhr39
