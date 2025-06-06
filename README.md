# Customer Churn Prediction using ANN

## Project Overview
This project aims to predict customer churn using an **Artificial Neural Network (ANN)**. The goal is to help businesses identify which customers are likely to leave (churn), based on features like **Age**, **Balance**, **Credit Score**, and other relevant customer data. By predicting churn, businesses can take proactive actions to improve customer retention.

## Technologies Used
- **Python** 3.x
- **Pandas**, **Numpy** for data handling and manipulation
- **Matplotlib**, **Seaborn** for data visualization
- **Scikit-learn** for machine learning tools
- **TensorFlow**, **Keras** for building and training the neural network model

## Model Overview
The model uses an **Artificial Neural Network (ANN)** with:
- 2 hidden layers with 11 neurons each
- **Sigmoid activation** functions for non-linearity
- **Binary classification** for predicting customer churn (1 = churn, 0 = not churn)

The model was trained using historical customer data and evaluated on test data, achieving **~79.75% accuracy**.

## Dataset
The dataset used in this project was sourced from Kaggle. You can access the dataset [here](https://www.kaggle.com/datasets/rjmanoj/credit-card-customer-churn-prediction).

## Installation
### Step 1: Clone the repository
git clone https://github.com/yourusername/customer-churn-prediction-using-ann.git

### Step 2: Install dependencies
pip install -r requirements.txt

### Alternatively, you can install manually
pip install pandas numpy scikit-learn tensorflow matplotlib seaborn

### Step 3: Run the Jupyter Notebook
jupyter notebook customer-churn-prediction-using-ann.ipynb


## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
