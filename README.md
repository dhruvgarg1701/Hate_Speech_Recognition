# Hate_Speech_Recognition

This project has been developed Under the Course of AI Application by
Dhruv Garg
102065034
3NC3

mentored by Dr. Saurabh Sharma

This project is a machine learning model for recognizing hate speech in text data. It is designed to help combat the spread of harmful and derogatory language on social media and other online platforms.

## Table of Contents
Installation
Usage
Data
Model
Results
Contributing
License

## Installation

To run this project locally, you will need to install the following dependencies:

* Python 3
* Pandas
* Scikit-learn
* NLTK

## Data
The model was trained on a dataset of social media tweets that were manually labeled as either containing hate speech or not. The dataset contains tweets in total, with a roughly even split between hate speech and non-hate speech.

## Model
The hate speech recognition model uses a combination of natural language processing techniques and machine learning algorithms to classify text data as hate speech or not. Specifically, it uses a bag-of-words representation with TF-IDF weighting, along with a logistic regression classifier.

The model was trained on the aforementioned dataset using 10-fold cross-validation. The final model achieved an accuracy of 90% on the test set.

## Results
The hate speech recognition model has several potential use cases, including:

* Moderation of social media and other online platforms
* Identification of hate speech trends and patterns
* Research into the prevalence and impact of hate speech online

## Contributing
If you would like to contribute to this project, feel free to submit a pull request or open an issue. We welcome all contributions and feedback!
