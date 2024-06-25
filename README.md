# Thyroid-Cancer-Recurrence-Prediction

## Project Overview
This project aims to predict the recurrence of well-differentiated thyroid cancer using a dataset of 13 clinicopathologic features collected over a 15-year period. Each patient in the dataset was followed for at least 10 years to monitor the recurrence of cancer.

## Dataset Description
The dataset consists of the following attributes:

1. Age: The age of the patient at the time of diagnosis or treatment.
2. Gender: The gender of the patient (male or female).
3. Smoking: Whether the patient is a smoker or not.
4. Hx Smoking: Smoking history of the patient (e.g., whether they have ever smoked).
5. Hx Radiotherapy: History of radiotherapy treatment for any condition.
6. Thyroid Function: The status of thyroid function, possibly indicating if there are any abnormalities.
7. Physical Examination: Findings from a physical examination of the patient, which may include palpation of the thyroid gland and surrounding structures.
8. Adenopathy: Presence or absence of enlarged lymph nodes (adenopathy) in the neck region.
9. Pathology: Specific types of thyroid cancer as determined by pathology examination of biopsy samples.
10. Focality: Whether the cancer is unifocal (limited to one location) or multifocal (present in multiple locations).
11. Risk: The risk category of the cancer based on various factors, such as tumor size, extent of spread, and histological type.
12. T: Tumor classification based on its size and extent of invasion into nearby structures.
13. N: Nodal classification indicating the involvement of lymph nodes.
14. M: Metastasis classification indicating the presence or absence of distant metastases.
15. Stage: The overall stage of the cancer, typically determined by combining T, N, and M classifications.
16. Response: Response to treatment, indicating whether the cancer responded positively, negatively, or remained stable after treatment.
17. Recurred: Indicates whether the cancer has recurred after initial treatment.

## Project Workflow
- ### Data Collection and cleaning
  1. Collected the dataset from Kaggle.
  2. Performed data cleaning on it.
  3. Used various functions to gain insights from it.
- ### Exploratory Data Analysis (EDA):
  1. Performed detailed EDA to understand the distribution and relationships between the features.
  2. Visualized the data to identify patterns and insights.
- ### Feature Engineering:
  1. Encoded categorical variables to numerical values.
  2. Scaled the features to ensure they are on the same scale for the model training process.
- ### Modeling:
  1. Implemented various machine learning models to fit the dataset.
  2. Evaluated the performance of each model using classification metrics.
  3. Achieved the best results using Support Vector Machine (SVM) with an accuracy of 99%.
 
## Results
The best performing model was the Support Vector Machine (SVM), which achieved an accuracy of 99% in predicting the recurrence of thyroid cancer. The classification report for the SVM model indicated high precision, recall, and F1 scores, demonstrating the model's effectiveness in this predictive task.
