# Drug-discovery-with-IC50-using-ML-
Machine learning with IC50 data of 104 chemical molecules against the COVID-19 virus

## Introduction:

The "Drug Discovery with IC50 Data Using Machine Learning" project aims to utilize machine learning techniques to discover potential drugs for COVID-19 from a dataset containing information on 104 molecules, including SMILES notation, IC50 values, and other molecular features. The dataset is sourced from Kaggle and is available here.

## Dataset Description:

The dataset consists of molecular information encoded as SMILES notation along with IC50 values, which represent the concentration of a drug required to inhibit 50% of a biological target's activity. Additionally, the dataset contains various molecular features relevant to drug discovery.

## Project Workflow:

### Data Preprocessing:

**Imputation of missing data:** 
Any missing values in the dataset were handled using appropriate imputation techniques to ensure the integrity of the data.

**Feature Scaling:** 
The data was scaled to bring all features to a similar scale, preventing certain features from dominating the model training process.

**Model Training:** 
Several machine learning models were trained using the preprocessed data. These models include:

    Random Forest Regressor
    Ada Boost Regressor
    Support Vector Regressor (SVR)
    Decision Tree Regressor
    KNeighbors Regressor
    Linear Regression
    
The performance of each model was evaluated based on its ability to predict IC50 values accurately.

**Model Evaluation**
The models were evaluated using appropriate evaluation metrics such as accuracy, mean squared error, or R-squared score.
Among the models tested, the SVR model exhibited the best performance with an accuracy of 60%.

**Molecular Structure Transformation:**
The SMILES molecular strings were converted into molecular structures using the RDKit package, allowing for a deeper analysis of the molecular properties.

**Conclusion:**

The project successfully applied machine learning techniques to predict IC50 values for potential COVID-19 drugs using molecular data. The SVR model emerged as the most effective in this context, achieving a 60% accuracy rate. Additionally, the transformation of SMILES strings into molecular structures provided further insights into the chemical properties of the molecules under investigation.

This project lays the groundwork for further exploration and refinement of drug discovery processes using machine learning, potentially contributing to the development of effective treatments for COVID-19 and other diseases.

