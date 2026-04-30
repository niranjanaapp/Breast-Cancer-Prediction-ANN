# 🧠 Breast Cancer Prediction using ANN

This project uses an **Artificial Neural Network (ANN)** to classify breast cancer tumors as **malignant** or **benign** based on medical diagnostic features.

---

## 🚀 Project Objective

To build a machine learning model that can accurately predict whether a tumor is cancerous or not, helping in early diagnosis and decision-making.

---

## 📊 Dataset

* Dataset: `breastcancer.csv`
* Source: Kaggle
* Records: ~569 samples
* Features: 30 numerical attributes
* Target Column: `diagnosis`

  * `M` → Malignant (converted to 0)
  * `B` → Benign (converted to 1)

---

## ⚙️ Tools & Libraries

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* TensorFlow / Keras

---

## 🔍 Project Workflow

* 1. Data Loading
* 2. Data Cleaning
* 3. Missing Value Handling
* 4. Data Visualization
* 5. Data Preprocessing
* 6. Model Building (ANN)
* 7. Model Training
* 8. Model Evaluation

---

## 🤖 Model Architecture

```
Input Layer
   ↓
Dense (64 neurons, ReLU)
   ↓
Dense (32 neurons, ReLU)
   ↓
Output Layer (1 neuron, Sigmoid)
```

---

## 📈 Results

* ✔ Accuracy: 98%
* ✔ High precision and recall
* ✔ Reliable classification performance

---

## 📊 Output Interpretation

* Output is a probability between 0 and 1
* If output > 0.5 → Benign
* If output ≤ 0.5 → Malignant

---

## 💡 Key Insights

* Feature scaling significantly improves performance
* ANN handles classification effectively
* Visualization helps understand data patterns

---

## 🎯 Conclusion

This project demonstrates how Artificial Neural Networks can be used for accurate breast cancer prediction, making it a valuable application of deep learning in healthcare.

