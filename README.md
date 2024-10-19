# Credit Card Fraud Detection with Quantum Computing

## College Name - Team Name
- Team Members: Hasini Bolloji, karthikeya , Madhav

## Problem Statement
Credit card fraud is a significant issue that leads to financial losses for both consumers and financial institutions. Detecting fraudulent transactions in real time is essential to minimize these losses. Current machine learning models often struggle with the imbalanced nature of the data, where normal transactions vastly outnumber fraudulent ones.

To address this issue, we have explored the use of classical machine learning models that analyze the data to identify potential fraud. These models utilize various algorithms to classify transactions based on historical data patterns.

In our project, we introduce the use of quantum computing to enhance the detection of credit card fraud. Quantum computers have the potential to analyze data in new ways, possibly capturing complex relationships that classical models might miss. However, one challenge with quantum computing is that it can be resource-intensive and requires significant computation time. By combining classical and quantum methods, our hybrid approach aims to balance the strengths of both technologies, potentially improving detection rates while mitigating resource demands.

## Approach
Our approach involves using a balanced credit card fraud detection dataset, where most transactions are normal, and a few are fraudulent. We preprocess the data, applying scaling and zero-padding for quantum compatibility. **We then implement a hybrid model combining classical logistic regression with quantum feature encoding using the ZFeatureMap**, enhancing the model's ability to detect complex fraud patterns efficiently. This hybrid approach leverages both classical and quantum techniques for improved detection.

## Instructions on Running the Project
1. **Download the Notebook**: 
   - Get the project notebook file (`your_project_notebook.ipynb`) from the repository.

2. **Install Required Libraries**:
   - Make sure you have Python installed on your computer.
   - Open a terminal or command prompt and run the following commands to install the necessary libraries:

   ```bash
   pip install qiskit
   pip install qiskit-machine-learning
   pip install numpy pandas matplotlib scikit-learn joblib
