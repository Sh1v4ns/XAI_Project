# **ViaSHAP - Prediction via Shapley Value Regression**

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-red.svg)](#python)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

## **Description:**
This repository hosts the implementation of ViaSHAP, a novel approach that learns a function to compute Shapley values, from which the predictions can be derived directly by summation. We explore two learning approaches based on the universal approximation theorem and the Kolmogorov-Arnold representation theorem. ViaSHAP using Kolmogorov-Arnold Networks performs on par with state-of-the-art algorithms for tabular data. The explanations obtained using ViaSHAP are significantly more accurate than other popular approximators, e.g., FastSHAP on both tabular data and images. All the experiments have been conducted in a Python 3.10 environment.
## **Usage:**
1. Clone the Repository: Clone this repository to your local machine using the following command:
   ```
   git clone https://github.com/Sh1v4ns/XAI_Project.git
   ```
2. Install Dependencies: Ensure that you have the necessary dependencies installed. You can install them using `pip`:
   ```
   pip install -r requirements.txt
   ```
3. We have used the MLP model for our implementation

 
4. The XAI method used is ViaSHAP (mlpshap.py)

   
6. Dataset used is Elevators Dataset(tabular regression)

   
7. Results reproduced :
    1. Prediction performance : RMSE / Accuracy
        
    2. SHAP quality metric : Cosine similarity with true Shapley values

    3. Feature importance ranking :Compare important features
  
       
    4. Also includes : AUC / performance and similarity to true Shapley values


    
     
