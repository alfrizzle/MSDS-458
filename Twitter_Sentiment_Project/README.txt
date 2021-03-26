**Notes for MSDS 458: Research/Programming Assignment #4**

All files for Assignment #4 are divided into two folders: 1. Paper; 2. Python Code

1. Paper

-This is the research paper for this assignment in .pdf format.

2. Python Code

-The code is divided into six parts. Each part is its own notebook (each available in .py, .ipynb, and .pdf formats). There is a folder for each file format.

-In parts 1-2, I conduct text cleaning, preprocessing, and vectorization. In part 2, I identify the pair of vectorization method and n-gram word sequence models that yield the highest performance. I also determine the best traditional classifier.

-In parts 3-6, I use observations and findings from parts 1 and 2 to train various neural network models:

* EXPERIMENT 1: Fully connected dense neural network (DNN)
* EXPERIMENT 2: Simple RNN
* EXPERIMENT 3: LSTM RNN
* EXPERIMENT 4: 1D CNN

The objective is to see if I can train a neural network model that could perform better than traditional machine learning models, namely logistic regression using a trigram TF-IDF vectorization.

-Pre-trained word embeddings are used in parts 3-6, specifically GloVe's Twitter (2B tweets, 27B tokens, 1.2M vocab, uncased, 200d vectors, 1.42 GB download): glove.twitter.27B.zip. To run the code properly, download this file and save it to your working directory. The file is available for download here: https://github.com/stanfordnlp/GloVe

-All the code is available/accessible via Google Colab. Links to the Colab notebooks are included in the paper appendix.