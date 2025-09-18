# Consumer-Financial-Complaints-Analysis📌 Project Overview

This project analyzes consumer financial complaints filed with the Consumer Financial Protection Bureau (CFPB). The objective is to explore how companies respond to complaints, identify common issues across financial products, and understand consumer response patterns.

🗂 Dataset

Source: CFPB Consumer Complaints Database

Raw Files Used:

complaints.csv (full dataset)

X_train.csv, X_test.csv (features)

y_train.csv, y_test.csv (labels)

Sample: 100,000 complaints (stratified sample)

Target Variable: company_response_to_consumer

Text Field: consumer_complaint_narrative

🎯 Objectives

Clean and preprocess raw complaint data

Perform exploratory data analysis (EDA) on complaints and company responses

Visualize complaint distributions across products and response categories

Prepare data for future Natural Language Processing (NLP) modeling

🔑 Key Features of the Notebook

Standardized column names and filtered rows with both text and response labels

Stratified sampling to create a balanced 100K dataset

Exploratory analysis with distribution plots for:

Company response categories

Top financial products with the most complaints

Length of complaint narratives

Exported a cleaned dataset (cfpb_clean_100k.csv) for modeling

📊 Sample Insights

Companies show varied response behaviors: e.g., “Closed with explanation” is the most common response.

Credit reporting, debt collection, and mortgages receive the highest number of complaints.

Complaint narratives range widely in length, with most between 50–200 words, making them suitable for text-based ML models.

🛠️ Tech Stack

Python

Libraries: pandas, numpy, matplotlib, seaborn,
