# Task-6-K-Nearest-Neighbors-KNN-Classification
# 🌸 K-Nearest Neighbors (KNN) on Iris Dataset

This project performs K-Nearest Neighbors (KNN) classification on the classic **Iris dataset** using Python and scikit-learn.

## Task Overview

**Task 6: KNN Classifier**
1.  Choose a classification dataset and normalize features  
2.  Use `KNeighborsClassifier` from `sklearn`  
3.  Experiment with different values of K  
4.  Evaluate model using accuracy and confusion matrix  
5. Visualize decision boundaries  

## Dataset Used

- **Name**: Iris Dataset  
- **Source**: UCI Machine Learning Repository  
- **Target Variable**: `Species` (Iris-setosa, Iris-versicolor, Iris-virginica)  
- **Features**:
  - SepalLengthCm
  - SepalWidthCm
  - PetalLengthCm
  - PetalWidthCm

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

## How It Works

1. Loaded the Iris dataset and removed the ID column.
2. Split the dataset into training and test sets.
3. Standardized features using `StandardScaler`.
4. Trained the KNN classifier with K values from 1 to 10.
5. Plotted the accuracy vs K graph to find the best K.
6. Evaluated the best model using a confusion matrix.
7. Visualized decision boundaries using `PetalLengthCm` and `PetalWidthCm`.
## Output

- **Best Accuracy:** 100% for K = 3  
- **Confusion Matrix** showing perfect classification  
- **Decision Boundary Plot** clearly shows separation of the three species
