# 🧠 Big Data & Deep Learning Models Project

This project showcases a collection of machine learning and deep learning solutions applied to classification, regression, natural language processing (NLP), and image recognition tasks. It highlights experimentation with different models, including cutting-edge techniques like TabPFN, and evaluates performance using various metrics across tasks.

## 📁 Project Structure

### 🔤 `classification.ipynb`
A comparative analysis of multiple classification models on a structured dataset:
- Logistic Regression
- Random Forest
- Gradient Boosting
- XGBoost
- CatBoost
- TabPFN classifier (used on a reduced dataset due to resource constraints)

**Key highlights**:
- Preprocessing using standard scaling and encoding
- Evaluation based on accuracy, F1-score, and classification report
- Visual comparisons and analysis of overfitting/underfitting behavior

---

### 📈 `regression.ipynb`
Performs regression analysis using:
- Linear Regression
- Ridge and Lasso
- XGBoost Regressor
- CatBoost Regressor
- TabPFN Regressor (trained and evaluated on a small sample subset)

**Key features**:
- Performance metrics: MAE, MSE, RMSE, and R²
- Comparison between models based on both train and test results
- Additional scaling and visualization for performance comparison

---

### 🧾 `NLPs.ipynb`
Focuses on text classification using NLP techniques:
- Text preprocessing and tokenization
- TF-IDF vectorization
- Model training for text classification
- Evaluation with standard classification metrics

---

### 🧠 `CNN.ipynb`
Applies image classification using:
- A standard Feedforward Neural Network (as a baseline)
- A Convolutional Neural Network (CNN) for improved image representation

**Key elements**:
- 80/20 train-test split
- Use of `ImageDataGenerator` for preprocessing
- Visualization of training history (accuracy/loss)
- Evaluation with `classification_report`

---

## 🧪 Models & Techniques Explored
- Models for classification/regression prediction
- Regularization and dropout for neural networks
- Batch normalization for stability
- Use of early stopping and validation split
- Evaluation using appropriate metrics for both classification and regression tasks

---

## ⚙️ How to Run
All notebooks and installations are built in Jupyter. Make sure to install the following key dependencies:
