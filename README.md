# Credit Card Fraud Detection using Neural Networks

![Project Banner/Image](path/to/your/image.png) 
## 🚀 Project Overview

This project focuses on building a deep learning model to accurately detect fraudulent credit card transactions. The primary challenge was handling the highly imbalanced dataset where fraudulent cases are extremely rare. This repository contains the complete workflow, from data exploration and preprocessing in a Jupyter Notebook to model building and evaluation using TensorFlow/Keras.

**Dataset:** [Link to the dataset on Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:**
    * Pandas & NumPy (for data manipulation)
    * Matplotlib & Seaborn (for visualization)
    * Scikit-learn (for preprocessing and metrics)
    * TensorFlow & Keras (for building the neural network)
* **Environment:** Google Colab

## ⚙️ Installation & Setup

To replicate this project on your local machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd your-repository-name
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## 📖 How to Use

The primary analysis and model development are contained within the Jupyter Notebook:
`credit_card_fraud_detection.ipynb`.

You can open and run this notebook in a Jupyter environment or upload it back to Google Colab to see the step-by-step process.

## 📊 Results & Evaluation

The final model was evaluated on the test set and achieved the following performance:

* **Precision:** 0.85 (Correctly identified 85% of predicted fraud cases)
* **Recall:** 0.92 (Found 92% of all actual fraud cases)
* **AUC-ROC Score:** 0.97

Here is the confusion matrix, which shows the model's performance on the test data:

![Confusion Matrix]("C:\Users\User\OneDrive\Pictures\Screenshots\confusion matrix.png.png") 
## ✅ Future Improvements

* Experiment with advanced techniques like SMOTE to handle class imbalance.
* Deploy the trained model as a simple web API using Flask or FastAPI.
