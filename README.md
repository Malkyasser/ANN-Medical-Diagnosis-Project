# ANN-Medical-Diagnosis-Project
# Load Breast Cancer dataset # Split data into training, validation, and testing # Build ANN model using PyTorch # Train model and calculate accuracy # Plot loss and accuracy graphs
# Neural Networks Project
# Neural Networks Project
- Breast Cancer Dataset from sklearn
- Number of samples: 569
- Number of features: 30

Dataset Link:
https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html

---

## Technologies Used
- PyTorch
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## Project Steps
1. Import libraries
2. Load dataset
3. Split data into training, validation, and testing sets
4. Apply StandardScaler preprocessing
5. Convert data to PyTorch tensors
6. Build ANN model using nn.Sequential
7. Train the model
8. Evaluate model accuracy and loss
9. Plot training and validation graphs
10. Compare two experiments

---

## ANN Architecture
- Input Layer: 30 neurons
- Hidden Layer 1: 16 neurons + ReLU
- Hidden Layer 2: 8 neurons + ReLU
- Output Layer: 1 neuron + Sigmoid

---

## Experiments
### Experiment 1
- Activation Function: ReLU
- Learning Rate: 0.001

### Experiment 2
- Activation Function: Tanh
- Learning Rate: 0.0005

---

## Results
The model achieved good performance on the testing dataset.
Training and validation loss decreased during training.
Training and validation accuracy improved over epochs.

---

## Graphs Included
- Training vs Validation Loss
- Training vs Validation Accuracy

---

## How to Run
1. Open Google Colab
2. Copy the project code
3. Run all cells
4. View graphs and final accuracy
