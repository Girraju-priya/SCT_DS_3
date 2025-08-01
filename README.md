# 🌳 SCT_DS_03

**Internship Task 03 – Decision Tree Classification on Bank Marketing Dataset using Python**  
💼 SkillCraft Technology | 📅 July 2025  

---

## 📌 Overview

- Build a Decision Tree Classifier to predict whether a customer will purchase a product or service.  
- Use demographic and behavioral data from the Bank Marketing dataset.  
- Implemented using Python libraries: `pandas`, `scikit-learn`, `matplotlib`.  
- Goal: derive actionable insights and evaluate model performance.

---

## 📁 Dataset Details

**Source**: UCI Bank Marketing Dataset  

**Key Columns Used**:  
- `y`: Subscription status (Target: 0 = No, 1 = Yes)  
- `age`: Age of customer  
- `job`, `marital`, `education`: Demographics  
- `default`, `housing`, `loan`: Financial indicators  
- `contact`, `month`, `day`: Contact attributes  
- `duration`, `campaign`, `pdays`, `previous`: Campaign interactions  
- `poutcome`: Previous marketing outcome

---

## 📊 Model Features

- ✅ Label Encoding – Categorical variables transformed using LabelEncoder  
- ✅ Train-Test Split – 70/30 split for model training and validation  
- ✅ Classifier – Decision Tree using `entropy` as splitting criterion  
- ✅ Metrics – Confusion Matrix, Accuracy Score, Classification Report  
- ✅ Visualization – Decision Tree plotted using `plot_tree()`



---

## ✅ Summary of Insights

- 🌟 Customers with **longer call durations** are more likely to subscribe.  
- 🏠 **Housing and loan status** influence purchasing behavior.  
- 📞 Subscription rates vary by **contact method** and **month**.  
- 📊 **First-time contacted customers** show lower conversion rates.

---

## 🧠 Learnings

- 🛠 Built an end-to-end classifier using Python.  
- 📈 Learned to handle categorical data and perform feature encoding.  
- 🧮 Understood entropy-based splits in Decision Trees.  
- 📊 Gained experience in model evaluation and interpretation.

---

## ▶ How to Run

1. Clone the repository or create a Python project in VS Code.  
2. Place `bank-full.csv` inside your project folder.  
3. Run the script `bank_decision_tree.py`.  
4. View model accuracy, confusion matrix, and classification report in the terminal.  
5. See the Decision Tree plot in a matplotlib window.  
6. Optionally tune parameters or try other classification models.

---
