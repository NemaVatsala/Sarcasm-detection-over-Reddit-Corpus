# Sarcasm-detection-over-Reddit-Corpus

## Course Project for DSE 407 - Natural Language Processing
<sub> by Dr. Tanmay Basu and Dr. Jasabanta patro </sub>

The task was to develop an NLP method that could identify the sarcastic comments perfectly based on the learnings from the labelled dataset. 
We used bag of words model and TF-idf vectorizers and applied 3 classifiers namely, Multinomial Naive Bayes, Logistic regression and Support vector machine to train the machine to learn labelling. We applied different NLP techniques like stop-word removal, lemmatization and stemming on the dataset to test for the accuracy of prediction. Later, we used the best trained model to predict the class 'sarcastic' or 'non-sarcastic' on the given test dataset.

> @inproceedings{khodak2018corpus,
  title={A Large Self-Annotated Corpus for Sarcasm},
  author={Khodak, Mikhail and Saunshi, Nikunj and Vodrahalli, Kiran},
  booktitle={Proceedings of the Linguistic Resource and Evaluation Conference (LREC)},
  year={2018}
}
