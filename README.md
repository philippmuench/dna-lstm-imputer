# dna-rnn

This code implements multi-layer Recurrent Neural Network (RNN, LSTM, and GRU) for training/sampling from character-level language models. In other words the model takes one FASTA file as input and trains a Recurrent Neural Network that learns to predict the next amino acid character in a sequence. The RNN can then be used to generate amino acid character by character that will look like the original training data.
