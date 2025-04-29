## **Project Overview**
- ### Objective
    - The objective of this project is to create various classification models capable of accurately predicting the failure of a Air Pressure System (APS) specific component in Scania trucks. 
- ### Relevance 
    - A model capable of accurate prediction of APS-specific failure could be utilized in a predictive maintenance scheme.
    - Analysis of the most important features of classification may allow for strategic refinement of specific components in future truck models.

## **Dataset**
- ### Source
    - This project uses data from APS Failure at Scania Trucks [Dataset]. (2016). UCI Machine Learning Repository. https://doi.org/10.24432/C51S51.
    - This dataset is provided under the GPL License and is sourced from Scania CV AB.
    - See LICENSE in root folder for a full plain-text version.
- ### Summary 
    - Real data is divided into training and testing datasets. 
    - The true feature names of this dataset have been replaced by a combination of identifier and bin id (identifier_bin) for proprietary reasons.
    
## **Classification Models**
- ### Logistic Regression
    - 
- ### Random Forest Classifier
    - 

## **Results & Insights**

## **How to Run**
- ### Dependencies & Setup
    - Create virtual-environment. (optional, but recommended)
    - Load required libraries from 'requirements.txt' with powershell command: `pip install -r requirements.txt`
- ### Data
    - Necessary training and testing data have been committed to the repository.
    - Data will be cleaned and stored locally.
        - `Important Note:` Some data-cleaning, model-training, and result-interpretation processes are computationally intense and may require extended amounts of time.

```markdown
## **Initial Clone File Structure**
.
└── APS-Failure-Classification-Model/
    ├── data/
    │   ├── aps_failure_description.txt
    │   ├── aps_failure_training_set.txt
    │   └── aps_failure_test_set.txt
    ├── data_cleaning/
    │   ├── test_data_imputation.ipynb
    │   └── training_data_imputation.ipynb
    ├── dev/
    │   └── scania_failure_data.ipynb
    ├── models/
    │   ├── logistic_regression.ipynb
    │   └── random_forest_model.ipynb
    ├── models_saved/
    │   └── .gitkeep
    ├── notebooks
    ├── .gitattributes
    ├── .gitignore
    ├── LICENSE
    ├── README.md
    └── requirements.txt

## **Licensing**
- ### Data
    - This dataset is provided under the **GPL License** and is sourced from Scania CV AB.
- ### Project
    - This project is licensed under the **MIT License**.







 
