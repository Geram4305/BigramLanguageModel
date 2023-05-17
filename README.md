# LanguageModel
**Bigram Character-Level Language Model**
This section provides an overview of a specific type of language model known as Bigram. A Bigram is essentially a sequence of two characters. In the case of the Bigram character-level language model, it predicts the subsequent character based on the previous character.

The model utilizes the names.txt dataset as input to generate names. To accomplish this, the model is trained using the names.txt dataset. After training, the model samples names, and the quality of the model is evaluated using the negative log-likelihood loss metric.

**The training process involves two approaches:**

Frequency Count and Normalization: 
The model counts and normalizes the frequencies of all the bigrams in the dataset.
Optimization with Negative Log-Likelihood: The model optimizes the counts matrix using negative log-likelihood as a lead to minimize loss in a gradient-based framework. For this purpose, a simple neural network with a single linear layer is employed.
This GitHub repository provides code and resources for implementing the Bigram character-level language model. You can explore both training approaches, generate new names, and evaluate the model's performance using negative log-likelihood loss.

Feel free to contribute, provide feedback, or experiment with different datasets to further enhance the capabilities of the Bigram model.

**Getting Started**

To get started with the Bigram character-level language model, follow these steps:

Clone the repository to your local machine.
Prepare the names.txt dataset or replace it with your own dataset.
Run the training script to train the Bigram model using either the frequency count or the negative log-likelihood optimization approach.
Once training is complete, utilize the model to generate new names.
Evaluate the model's performance using the negative log-likelihood loss.


Contributions, bug reports, and suggestions for improvement are highly appreciated. Enjoy experimenting with the Bigram character-level language model!

**License**
This project is licensed under the MIT License.





