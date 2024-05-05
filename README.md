# News Article Classification Using SVM

This repository contains code for a project on news article classification using Support Vector Machines (SVM). The project focuses on classifying news articles from the 20 Newsgroups dataset into four categories: alt.atheism, soc.religion.christian, comp.graphics, and sci.med.

## Overview

The project involves the following key components:

1. **Data Collection and Preprocessing**: The data is sourced from the 20 Newsgroups dataset, a collection of approximately 20,000 newsgroup documents across 20 different topics. The documents are preprocessed to remove irrelevant characters, stopwords, and perform lemmatization. Feature engineering is performed using TF-IDF vectorization, which transforms the text data into numerical vectors based on the importance of words in the document corpus.

2. **Exploratory Data Analysis (EDA)**: Descriptive statistics such as mean, median, and standard deviation are computed to understand the distribution of text data across different categories. Various data visualization techniques such as histograms, word clouds, and bar plots are used to visualize the distribution of words and categories in the dataset. EDA helps in identifying patterns and outliers in the data, which informs subsequent modeling decisions.

3. **Modeling**: Support Vector Machines (SVM) with a linear kernel are chosen as the classification algorithm due to their effectiveness in text classification tasks. The SVM model is trained on TF-IDF vectors obtained from the preprocessed data. Hyperparameters of the SVM model, such as the regularization parameter (C), are tuned using techniques like grid search to optimize model performance.

4. **Results and Evaluation**: Performance metrics such as accuracy, precision, recall, and F1-score are calculated to evaluate the model's performance. The classification report provides insights into how well the model performs for each class. Model comparison with other machine learning algorithms is also performed to assess its effectiveness.

5. **Discussion**: Challenges faced during the project, such as data preprocessing issues and model optimization challenges, are discussed. Limitations of the study, such as dataset size and class imbalance, are acknowledged. Potential improvements, such as using more advanced machine learning techniques and incorporating additional features, are suggested.

6. **Conclusion**: The findings of the project, including the effectiveness of the SVM model in classifying news articles, are summarized. The implications of the study, such as its relevance in real-world applications and potential future research directions, are discussed.

## Requirements

- Python 3
- scikit-learn
- matplotlib
- seaborn
- pandas
- numpy

## Usage

1. Clone the repository:  git clone https://github.com/Piyushagarwal26/News-Article-Classification-Using-SVM.git
2. Install the required dependencies:
3. Run the Jupyter notebook `ISPA_Project.ipynb` to execute the code and reproduce the results.


