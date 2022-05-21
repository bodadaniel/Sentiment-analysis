# NLP Thesis ELTE

Title: 
NLP: Sentiment analysis on product reviews at Amazon

Models: 
In the application a bidirectional, multi-layer long short-term memory (LSTM) is developed with Pytorch in which the number of features in the hidden state = 100, the number of recurrent layers = 2 (stacked LSTM) with dropout probability equal to 50%.

In the thesis BERT(BASE) is applied in which total parameters = 110M, the number of layers (Transformers block) = 12, hidden size = 768, number of self-attention head = 16 with a final linear layer for the projection into R2.
