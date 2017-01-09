# DNA sequence imputer

Multi-layer Recurrent Neural Network (LSTM) for imputation of missing DNA fragments. This model was trained on a large collection of bacterial chromosomes. DNA imputer takes one DNA sequence seed as input and can predict the next amino acid character in a sequence. Furthermore, the RNN can then be used to generate amino acid character by character that will look like the original training data. This code was developed to impute missing DNA to close circular plasmids and is therefore learned on plasmid sequences. 
