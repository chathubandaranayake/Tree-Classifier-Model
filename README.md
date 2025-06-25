# 🌳 Tree Classification using Neural Networks

This project demonstrates how to build a neural network using TensorFlow/Keras to classify tree species based on a dataset. It covers the full machine learning pipeline from data loading and preprocessing to model training, evaluation, and saving.

---

## 📁 Dataset

The dataset used is `Tree_Dataset.csv`, which contains features related to tree species.

---

## 🔧 Technologies Used

- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📌 Key Steps

1. **Data Loading**  
   The dataset is read using Pandas and basic exploration is done (`info()`, `describe()`).

2. **Preprocessing**  
   - Features are standardized using `StandardScaler`.  
   - Labels are one-hot encoded for classification.

3. **Model Building**  
   - A sequential neural network with Dense layers is created.  
   - Early stopping and model checkpointing are used to optimize training.

4. **Training & Evaluation**  
   - The model is trained and evaluated on test data.  
   - Accuracy and loss curves are plotted.

5. **Model Saving**  
   - Trained model is saved for future inference.

---
