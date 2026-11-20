# PhiUSIIL Phishing URL Dataset Modelling

This project was completed as part of an introductory data science unit. The project incorporates data processing, exploration, visualisation and modelling. 

## Data Source

The dataset used for this project is the PhiUSIIL Phishing URL Dataset (Prasad & Chandra, 2024a), hosted on the University of California Irvine (UCI) Machine Learning Repository (Prasad & Chandra, 2024b). The dataset contains data relating to 134,850 legitimate URLs and 100,945 phishing URLs. There are 54 dataset features, including attributes of the URLs themselves, the corresponding website HTML code and comparison against a list of popular legitimate websites.

The dataset is available at https://archive.ics.uci.edu/dataset/967/phiusiil+phishing+url+dataset

## Results
The dataset has been modelled using a random forest classifier and a multi-layer perceptron (MLP) classifier, achieving the following performance metrics after threshold tuning:

|           | Random Forest | MLP           |
| --------- | ------------- | ------------- |
| Accuracy  | 99.38 %       | 99.9809 %     |
| Precision | 99.18 %       | 99.9652 %     |
| Recall    | 99.36 %       | 99.9901 %     |
| F1 score  | 99.27 %       | 99.9776 %     |

The project received a high distinction grade.

## View the Project

The project notebook can be viewed at https://github.com/c-attard/PhiUSIIL/blob/main/COS60008-project-106185149.ipynb