# The-Learning-Agency-Lab---PII-Data-Detection-Using-NLP
Kaggle Competition

## Description
Students' Personally Identifiable Information (PII) is crucial, especially considering the potential risks posed by releasing this data publicly. Educational databases containing sensitive information like names, addresses, etc. pose a real threat to student privacy if not adequately protected. Acknowledging this challenge, this project aims to create effective methods for detecting and removing Personally Identifiable Information from educational data, while still preserving the usability and reliability of the data.

This project utilizes modern Natural Language Processing model DistilBERT to improve the effectiveness and precision of PII detection. By harnessing this state-of-the-art technology, goal is to pave the way for generating high-quality public education datasets while preserving privacy.

### Seven types of PII Types:
NAME_STUDENT - The full or partial name of a student that is not necessarily the author of the essay. This excludes instructors, authors, and other person names. <br>
EMAIL - A student’s email address. <br>
USERNAME - A student's username on any platform. <br>
ID_NUM - A number or sequence of characters that could be used to identify a student, such as a student ID or a social security number. <br>
PHONE_NUM - A phone number associated with a student. <br>
URL_PERSONAL - A URL that might be used to identify a student. <br>
STREET_ADDRESS - A full or partial street address that is associated with the student, such as their home address. <br>

![DALL·E 2024-06-10 20 48 46 - A colorful and clean image representing different types of Personally Identifiable Information (PII) related to students  Include vibrant icons for ea](https://github.com/ManishaLagisetty/PII-Data-Detection/assets/147951099/3316329b-4bd0-4cad-958b-be25c073e38b)


#### Dataset link
https://www.kaggle.com/competitions/pii-detection-removal-from-educational-data/data

#### Technical Report
ProjectReport.pdf

#### Code implementation
distilbert_model.ipynb

#### Technology Stack
Jupyter Notebook, Deep Learning <br>
Languages: Python (Numpy, Pandas, Matplotlib, Seaborn)
Framework: Pytorch 

#### final ouput csv file for submission
submission_DISTILBERT.csv

<img width="457" alt="image" src="https://github.com/ManishaLagisetty/PII-Data-Detection/assets/147951099/4d3c622d-062d-4f81-9787-40f5ac978545">

