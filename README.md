PyTorch Implementation for Regression and Classification Tasks

This repository contains two end-to-end machine learning projects built using PyTorch. It demonstrates how to solve both regression and classification problems using neural networks.

📌 Projects Included

The repository is divided into two separate tasks:

1️⃣ Regression Task — Medical Insurance Cost Prediction

Dataset: Medical Cost Personal Dataset
Goal: Predict the medical insurance charges of a person using personal details such as:

Age
Gender
BMI
Number of Children
Smoking Status
Region
🧠 Model Architecture

A Feedforward Neural Network:

Linear → ReLU → Linear → ReLU → Linear
📊 Evaluation Metrics
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² Score
📁 Folder
regression - Medical insurance bill predictor
2️⃣ Classification Task — Iris Species Prediction

Dataset: Iris Flower Dataset (loaded using scikit-learn)

Goal: Classify flowers into three species:

Setosa
Versicolor
Virginica

Using features:

Sepal Length
Sepal Width
Petal Length
Petal Width
🧠 Model Architecture

A Multiclass Neural Network:

Linear → ReLU → Linear → ReLU → Linear
⚙️ Loss Function
CrossEntropyLoss
📊 Evaluation Metrics
Accuracy
Precision
Recall
F1-Score
📁 Folder
classification - Iris species predictor
🚀 Installation & Setup
1. Clone Repository
git clone https://github.com/Mohit-cmd-jpg/Regression-and-Classification-Project.git
cd Regression-and-Classification-Project
2. Install Dependencies
pip install torch pandas scikit-learn matplotlib numpy
▶️ Run the Projects
Run Regression Model
cd "regression - Medical insurance bill predictor"
python train_regression.py
Run Classification Model
cd "classification - Iris species predictor"
python train_classification.py
📌 Assignment Requirements Completed

✅ PyTorch implementation for Regression Task
✅ PyTorch implementation for Classification Task
✅ Data preprocessing included
✅ Neural Network model architecture implemented
✅ Training and Testing scripts included
✅ Evaluation metrics calculated
✅ Separate project structure maintained
✅ README with execution instructions

🛠 Technologies Used
PyTorch
Python
Pandas
NumPy
Matplotlib
scikit-learn
