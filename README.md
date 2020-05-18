# MiniProject
Textual entailment task - UiS data Mining project

This project is using a dataset from a Kaggle competition already closed : https://www.kaggle.com/c/fake-news-pair-classification-challenge/data
And also the SNLI dataset, Samuel R. Bowman, Gabor Angeli, Christopher Potts, and Christopher D. Manning. 2015. A large annotated corpus for learning natural language inference. In Proceedings of the 2015 Conference on Empirical Methods in Natural Language Processing (EMNLP). Available here : https://nlp.stanford.edu/projects/snli/
This is a supervised task.

# Input
We will use at least these 2 datasets :

The first is from a Kaggle competition (already over).
Task: Fake News Classification
Given the title of a fake news article A and the title of a coming news article B, participants are asked to classify B into one of the three categories.
agreed: B talks about the same fake news as A
disagreed: B refutes the fake news in A
unrelated: B is unrelated to A

The second data set is described as follow :
The SNLI corpus (version 1.0) is a collection of 570k human-written English sentence pairs manually labeled for balanced classification with the labels entailment, contradiction, and neutral, supporting the task of natural language inference (NLI), also known as recognizing textual entailment (RTE). We aim for it to serve both as a benchmark for evaluating representational systems for text, especially including those induced by representation learning methods, as well as a resource for developing NLP models of any kind.

# Potential challenges
Build the right Neural Network model. Deal with acccuracy.
Deep learning requires a good GPU to train the model, not always easy, even with google colab to get a good GPU to compute faster.

# Methods used
BERT, LSTM and GRU. 
BERT achieved 86% accuracy on test data
LSTM and GRU : 85% accuracy on training data - 73% accuracy on test data

# Possible improvements
For LSTM and GRU, use Glove 840B 300D for embedding layer
