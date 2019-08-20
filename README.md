# README
## toxic comments classification


The aim of this project is to detect toxic comments containing hate speech and other forms of discriminating or insulting content.

To do so the data consisting of raw Wikipedia comments is cleaned and brought into vocabulary representation. The data was obtained on Kaggle at the Toxic Comments Classification Challenge.

For the classification task a convolutional neural network using keras is employed. Three different approaches of obtaining word embeddings are tested. While the architecture of the CNN remains the same, first a model initializing all word embeddings randomly is tested (CNNrand). In addition, a model using the word2vec word and keeping them fixed during the training period (CNNfix) is created and finally, another approach allowing to refine the word2vec vectors used during the learning period has been implemented (CNNtrain).

