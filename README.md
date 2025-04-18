# PII Data Detection Using NLP
Kaggle Competition

## Description
Students' Personally Identifiable Information (PII) is crucial, especially considering the potential risks posed by releasing this data publicly. Educational databases containing sensitive information like names, addresses, etc. pose a real threat to student privacy if not adequately protected. Acknowledging this challenge, this project aims to create effective methods for detecting and removing Personally Identifiable Information from educational data, while still preserving the usability and reliability of the data.

This project utilizes Natural Language Processing model DistilBERT to improve the effectiveness and precision of PII detection. By harnessing this state-of-the-art technology, the goal is to pave the way for generating high-quality public education datasets while preserving privacy.

### Seven types of PII Types:
NAME_STUDENT - The full or partial name of a student that is not necessarily the author of the essay. This excludes instructors, authors, and other person names. <br>
EMAIL - A student’s email address. <br>
USERNAME - A student's username on any platform. <br>
ID_NUM - A number or sequence of characters that could be used to identify a student, such as a student ID or a social security number. <br>
PHONE_NUM - A phone number associated with a student. <br>
URL_PERSONAL - A URL that might be used to identify a student. <br>
STREET_ADDRESS - A full or partial street address that is associated with the student, such as their home address. <br>

#### Dataset link
https://www.kaggle.com/competitions/pii-detection-removal-from-educational-data/data


#### Code implementation
distilbert_model.ipynb

#### Technology Stack
Jupyter Notebook, Deep Learning <br>
Languages: Python (Numpy, Pandas, Matplotlib, Seaborn)
Framework: Pytorch 

#### final ouput csv file for submission
submission_DISTILBERT.csv


