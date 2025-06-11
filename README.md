# Will_they_subscribe
# 🌳 Will They Subscribe? – Decision Tree Classifier

This project uses the Bank Marketing Dataset to predict whether a customer will subscribe to a term deposit using a Decision Tree Classifier.

## 📊 Features Used:
- Demographics (age, job, marital status, etc.)
- Call duration and history
- Contact method, campaign info

## 🧠 What We Did:
- Cleaned & encoded the data
- Trained a Decision Tree Classifier (depth=4)
- Visualized the decision tree
- Explained 3 logical decision paths

## 🌿 Example Decision Paths:
1. If call duration < 211.5 sec → ❌ No
2. If duration > 211.5 & previous campaign = success → ✅ Yes
3. If duration high but no past success and age < 30 → ❌ No

## 📦 Tools Used:
- Python
- Pandas
- scikit-learn
- Matplotlib

## 📁 Output:
- decision_tree_classifier.ipynb
- Visualized decision tree plot
