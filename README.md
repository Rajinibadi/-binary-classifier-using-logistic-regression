# 🧪 Logistic Regression Classification - Breast Cancer Detection

## 📌 Objective
Build a Logistic Regression model to classify whether a tumor is **Benign** or **Malignant** using the **Breast Cancer** dataset.

---

## 📁 Dataset
- Binary Classification Dataset from UCI (via sklearn or CSV)
- Features: cell size, shape, texture, etc.
- Target:  
  - `0`: Benign  
  - `1`: Malignant

---

## 🔧 Steps Performed

1. **Loaded the dataset** using Pandas.
2. **Explored and visualized data** using graphs.
3. **Split into train and test sets** (80/20).
4. **Standardized features** using `StandardScaler`.
5. **Trained** a Logistic Regression model.
6. **Evaluated** model using:
   - Confusion Matrix
   - Accuracy, Precision, Recall, F1-Score
   - ROC-AUC Curve
7. **Plotted the Sigmoid Function** to understand how probabilities are predicted.

---

## 📉 Sigmoid Function Explained

> The Sigmoid function maps any input number (positive or negative) into a value between 0 and 1.

- Very Negative Input → Output close to **0** → Predicts **Benign**
- Very Positive Input → Output close to **1** → Predicts **Malignant**
- Input near 0 → Output near **0.5** → Model is **unsure**

📈 The sigmoid curve helps in converting model outputs into **probabilities**, which are then **thresholded** (usually at 0.5) to make binary predictions.

---

## 📊 Model Performance Summary

- **Confusion Matrix** shows correct vs incorrect classifications.
- **ROC-AUC** curve indicates how well the model separates the two classes.
- Model performance metrics like:
  - **Accuracy**: How often the model is correct.
  - **Precision**: When it predicts Malignant, how often is it correct?
  - **Recall**: How many actual Malignant cases did it detect?

---

## ✅ Conclusion

- The Logistic Regression model performed well on the dataset.
- The sigmoid function plays a key role in decision-making.
- The model can effectively predict tumor type based on input features.

---

## 📚 Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn

---

## 📌 Note
Thresholds (like 0.5) can be adjusted depending on the need — for example, increasing **Recall** is important in cancer detection to minimize false negatives.

---

## 🔍 Future Scope
- Try other classifiers like Random Forest or SVM.
- Apply cross-validation.
- Perform hyperparameter tuning.

