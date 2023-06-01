# Bigram Character-Level Language Model
This repository contains code for training a Bigram Character-Level Language Model. A Bigram is essentially a sequence of two characters. In the case of the Bigram character-level language model, it predicts the subsequent character based on the previous character. The model is trained on a dataset of the most common 32K names taken from ssa.gov for the year 2018. The purpose of this project is to demonstrate how to train the model, sample from it, and evaluate its quality using negative log likelihood loss.

# Dataset
The names.txt dataset used in this project consists of the 32K most common names from ssa.gov for the year 2018. It serves as an example for training the language model.

# Training the Model
Trained the Bigram Character-Level Language Model using two different approaches.

# Approach 1: Frequency-based Count Matrix

In this approach, the frequency of all the bigrams in the dataset is counted and normalized and then sampling is performed from the model.

# Approach 2: Neural Network with Negative Log-Likelihood Loss

In this approach, a neural network is used to optimize the count matrix by minimizing the negative log-likelihood loss. The network considers the single previous character and feeds it through a single linear layer to calculate the logits and sampling is done to generate new names.


# Evaluating the Model
To evaluate the quality of the trained model, negative log likelihood loss is used. The lower the loss value, the better the model's performance. 

# Credits and Inspiration
This project is inspired by Andrej Karpathy's "make more" series on YouTube. It aims to recreate the work with more explanatory comments and gain a better understanding of language models. You can find more exciting projects and tutorials on the YouTube channel: Andrej Karpathy's "make more" series.






