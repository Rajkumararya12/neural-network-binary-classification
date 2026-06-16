# neural-network-binary-classification
Deep learning binary classification project using TensorFlow and Keras.

# 🧠 Crime Classification Using Neural Network

A Deep Learning project that uses an Artificial Neural Network (ANN) to classify crime incidents into Violent and Non-Violent categories using historical crime data.

## 📌 Project Overview

This project focuses on building a neural network based classification model that learns patterns from crime attributes such as crime type, location, time, arrest status, and other features to predict whether a crime is violent or non-violent.

## 🎯 Objective

To develop a deep learning model capable of predicting crime violence categories from historical crime records.

## 📂 Dataset

The dataset contains crime-related information including:

- Crime description
- Location details
- Arrest information
- Domestic crime indicator
- Date and time features
- Crime categories

Target Variable:

- `violent`
  - 0 → Non-Violent Crime
  - 1 → Violent Crime

## 🔍 Exploratory Data Analysis

Performed analysis:

- Crime distribution
- Crime category frequency
- Location based patterns
- Time based trends
- Class distribution analysis

## ⚙️ Data Preprocessing

Steps performed:

- Data cleaning
- Missing value handling
- Date feature extraction
- Feature engineering
- One Hot Encoding for categorical variables
- Standard scaling for numerical features

Generated time features:

- Year
- Month
- Day
- Hour

## 🧠 Neural Network Model

The model is developed using TensorFlow/Keras.

Architecture:

Input Layer
↓
Dense Layers
↓
ReLU Activation
↓
Dropout Regularization
↓
Sigmoid Output Layer

Model features:

- Binary classification
- Adam optimizer
- Binary cross entropy loss
- Early stopping
- Dropout layers

## 📊 Evaluation

Model evaluation includes:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1 Score

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras

## 📁 Project Structure

```
Crime-Classification-Neural-Network/
│
├── crime_classification_neural_network.ipynb
├── README.md
└── Dataset/
    └── crime_data.csv
```

## 🚀 Installation

Clone repository:

```bash
git clone https://github.com/yourusername/Crime-Classification-Neural-Network.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Running the Project

Open notebook:

```bash
jupyter notebook crime_classification_neural_network.ipynb
```

Run all cells to reproduce data analysis and model training.

## 🔮 Future Improvements

- Hyperparameter tuning
- Advanced deep learning models
- Better handling of class imbalance
- Deployment as a web application
- Real-time crime prediction system

## 👨‍💻 Author

Rajkumar Arya

GitHub:
https://github.com/Rajkumararya12

