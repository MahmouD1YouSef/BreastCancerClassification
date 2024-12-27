## Project Overview

Breast cancer is one of the most common cancers worldwide. Early detection and accurate classification can significantly improve patient outcomes.
This project aims to develop a neural network model to classify breast cancer as **Benign** or **Malignant** using publicly available data.

---

####### Steps Involved

### 1. Exploratory Data Analysis (EDA)
- Inspected the dataset for missing values, duplicates, and outliers.
- Analyzed the distribution of features and their correlation with the target variable.

### 2. Data Visualization
- Created visualizations to understand the dataset better, including:
  - Histograms for feature distributions.
  - Correlation heatmaps.
  - Scatter plots for relationships between features.

### 3. Preprocessing
- **Encoding**: Converted categorical data into numerical format (if any).
- **Scaling and Transformation**: Standardized numerical features to ensure all features are on the same scale.
- **Data Splitting**: Divided the dataset into training and testing sets.

### 4. Neural Network Model
- Built a sequential neural network using a framework like TensorFlow/Keras.
- Model architecture:
  - Input layer with the number of features.
  - Hidden layers with appropriate activation functions.
  - Output layer with two nodes (Benign, Malignant) and softmax activation.
- Compiled the model with loss function, optimizer, and evaluation metrics.

### 5. Classification Report
- Evaluated the model using precision, recall, F1-score, and accuracy metrics.
- Displayed the classification report for model performance.

### 6. Accuracy and Loss Plots
- Plotted graphs for:
  - Training and validation accuracy.
  - Training and validation loss.
- These plots helped assess overfitting or underfitting.

### 7. Predictive System
- Built a predictive function to classify new data points based on trained weights.
- Tested the predictive system on unseen data.

### 8. Graphical User Interface (GUI)
- Developed a simple GUI using a library like Tkinter or PyQt.
- Features of the GUI:
  - Input fields for feature values.
  - "Predict" button to classify as **Benign** or **Malignant**.
  - Display the prediction result.
