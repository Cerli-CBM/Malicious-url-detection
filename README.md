# Malicious URL Detection

## Objective
This project aims to build a scalable system using **PySpark** to detect malicious URLs efficiently. The focus is on processing large volumes of data to identify and mitigate potential threats in real-time.

## Dataset
The dataset used for this project is available on Kaggle:
- **Source**: [Tabular Dataset Ready for Malicious URL Detection](https://www.kaggle.com/datasets/pilarpieiro/tabular-dataset-ready-for-malicious-url-detection/data)
- The dataset includes various features relevant for detecting malicious URLs, enabling effective machine learning model training.

## Approach
- **Data Processing**: Leveraged **PySpark** for distributed data processing, which allows the system to efficiently handle big data across multiple nodes.
- **Machine Learning Models**: Implemented algorithms such as **Decision Trees** and **Logistic Regression** to classify URLs as malicious or benign.
- **Feature Extraction**: Focused on extracting relevant features from the URL data, including:
  - Domain length
  - Presence of special characters
  - Other relevant attributes

