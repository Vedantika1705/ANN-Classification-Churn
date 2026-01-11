# ANN Classification – Customer Churn Prediction

This project uses an Artificial Neural Network (ANN) to predict whether a customer will leave (churn) a company based on historical customer data.

The model is built using TensorFlow/Keras and focuses on understanding the complete ANN workflow, including data preprocessing, feature encoding, scaling, model training, and evaluation.

---

The project performs the following steps:
- Loads customer churn dataset
- Handles missing values (if any)
- Encodes categorical variables (Geography, Gender)
- Scales numerical features
- Builds an Artificial Neural Network
- Trains the model using backpropagation
- Evaluates performance on test data
- Predicts churn probability for new customers

---

Results:
- The ANN learns patterns related to customer churn
- Training and validation accuracy improve with epochs
- Model performance depends on:
  - Number of hidden layers
  - Number of neurons
  - Learning rate and optimizer
  - Dataset quality

This project focuses on learning ANN fundamentals rather than business deployment.

---

Example prediction:

Customer details:
Credit Score: 650  
Geography: France  
Gender: Female  
Age: 42  
Balance: 125000  
Estimated Salary: 70000  

Prediction:
Customer is likely to **stay** (Low churn probability)

---

Model limitations:
- ANN does not explain *why* a customer churns
- Performance depends heavily on feature quality
- Class imbalance can affect accuracy
- Not optimized for real-world production use

Techniques like hyperparameter tuning and feature engineering can improve results.

---

Technologies used:
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn

---

How to run the project:

Clone the repository:
git clone https://github.com/Vedantika1705/ANN-Classification-Churn.git
cd ANN-Classification-Churn

Install dependencies:
pip install -r requirements.txt

Run the training script or notebook to train the ANN model.

Use the trained model to predict churn for new customer data.

---

This project demonstrates how Artificial Neural Networks can be applied to binary classification problems like customer churn prediction.

Author:  
Vedantika Varnekar
