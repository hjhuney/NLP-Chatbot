# Chatbot-Kirill
Notes and code from Kirill Eremenko's NLP / Chatbot Course

# Bag of Words Model
* Sparse vector (e.g. 20K words, assign value for number of time each word used)
* Special words are last element
* Train examples with sparse vectors to create model
* Model examples: logistic regression (e.g. predict "yes" or "no" response), neural network

## Issues with Bag of Words Model
* Fixed vector size input
* Order of words not taken into account
* Fixed sized output

# Seq2Seq
* Uses RNNs
