# Liver Disease Prediction Using Gated Recurrent Unit Neural Networks

## Project Overview

This project explores the application of Gated Recurrent Unit (GRU) neural networks for predicting liver disease progression. By leveraging the Liver Patient Dataset, we train a GRU model to analyze various patient attributes and identify patterns indicative of disease advancement. Our approach aims to develop a reliable tool for early detection and prognosis of liver disease, providing healthcare professionals with practical strategies to manage individual patients.

## Repository Contents

- `Liver Disease Prediction Using GRU.ipynb`: Jupyter notebook containing the code for data preprocessing, model training, and evaluation.
- `Liver Disease Prediction Using Gated Recurrent Unit Neural Networks.pdf`: Research paper detailing the methodology, experiments, and results of the study.

## Prerequisites

Ensure you have the following libraries installed:

- `numpy`
- `pandas`
- `sklearn`
- `keras`

You can install them using pip:

```bash
pip install numpy pandas scikit-learn keras
```

## Dataset

The Liver Patient Dataset is used for this project. Ensure you have the dataset downloaded and properly formatted before running the notebook.

## Methodology

1. **Data Preprocessing**:
   - Address missing values using imputation techniques.
   - Standardize features for consistent data representation.
   - Split the data into training and testing sets.

2. **Model Architecture**:
   - Utilize the GRU architecture to capture temporal dependencies within the data.
   - Experiment with model hyperparameters to optimize performance.
   - Implement a windowed sequence approach to enhance predictive capabilities.

3. **Training**:
   - Train the GRU model on the preprocessed dataset.
   - Apply regularization and dropout techniques to prevent overfitting.
   - Evaluate the model's performance on the test set.

## Results

- **Test Loss**: 0.294
- **Test Accuracy**: 86%

The model demonstrated high accuracy in classifying patients based on sequential clinical data, showcasing the effectiveness of the GRU architecture for medical prognosis.

## Conclusion

This study demonstrates the potential of GRU neural networks in predicting liver disease progression. By capturing temporal dependencies inpatient data, the model provides a promising tool for early detection and improved management of liver disease. Future work should focus on expanding the dataset and incorporating interpretive approaches for enhanced clinical utility.

## Authors

- Mohammed S. Dabour, Artificial Intelligence Student, King Salman International University
- Mohamed A. Lotfy, Artificial Intelligence Student, King Salman International University
- Mohamed A. AbdElhamid, Artificial Intelligence Student, King Salman International University

## Acknowledgements

We acknowledge the support and resources provided by the Department of CSE at King Salman International University, Sinai, Egypt.
