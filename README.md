# Medical Transcript Classification using Naive Bayes Classification Model

Naive Bae's Project implements a machine-learning Naive Bayes classification model to classify medical transcriptions according to respective
medical specialties

# Links:
🏆 Intact Data Science Challenge 2023 Winner ($500+ Prize): https://devpost.com/software/intact-naive-bayes-classifier

• Won the Intact Data Science challenge and utilized their dataset of over 4,000 medical transcripts to train the ML model
• Addressed challenges in dataset preprocessing by cleaning and incorporating NLP methods to increase F-Score by 45%
• Implemented Scikit-Learn pipeline to fine-tune parameters to maximize the effectiveness of the Naive Bayes model

![Alt text](ClassificationModels/ProjectPictures/screenshot1.png)

## Table of Contents

- [Background](#background)
- [Data](#data)
- [Methodology](#methodology)
- [Technology Stack](#technology-stack)
- [Usage](#usage)
- [Conclusion](#conclusion)
- [Contributing](#contributing)

## Background

Medical transcription is the process of transcribing medical records from spoken word to text format. In this project, we focused on classifying the medical transcript data and determining the medical specialty to which the transcription should be sent to. The goal is to streamline the process of medical transcription and reduce the time taken to classify the transcription manually.

## Data

We used a dataset of medical transcripts collected from various medical specialties. The dataset consisted of around 4,000 transcripts, and we split the dataset into training and testing datasets. We ensured that both the training and testing datasets had a similar distribution of transcripts across the medical specialties.

## Methodology

We used the Naive Bayes theorem to classify the medical transcript data. Naive Bayes is a probabilistic algorithm that calculates the probability of a given input belonging to a particular class. We used the Multinomial Naive Bayes algorithm, which is commonly used for text classification tasks. 

We preprocessed the data by removing stop words, stemming the words, and converting the text to lowercase. We then used the CountVectorizer function from scikit-learn to convert the text into a matrix of word frequencies. We trained the Multinomial Naive Bayes algorithm on the training data and evaluated its performance on the testing data.

![Alt text](ClassificationModels/ProjectPictures/screenshot2.png)

## Technology Stack

We used the following technologies to build our project:

- Python
- PyTorch
- scikit-learn
- JupyterNotebook
- NLTK (natural language processing tools)

## Usage

Clone the repo and open 'IntactClassificationNLPModel.ipynb'. From there, we have outlined all the steps and commented the code so users can see our process and receive predictions from our model.

The program will load the dataset, preprocess the data, and train the Multinomial Naive Bayes algorithm on the training data. It will then evaluate the performance of the algorithm on the testing data and output the accuracy score.

## Conclusion

In conclusion, our project demonstrates the effectiveness of using the Naive Bayes theorem for medical transcript classification. By automating the process of classifying medical transcripts, we can streamline the process of medical transcription and reduce the time taken to classify the transcription manually.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you would like to contribute to this project.


