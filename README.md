# DNA imputation

Multi-layer Recurrent Neural Network (LSTM) for imputation of missing DNA fragments. This model was trained on a large collection of plasmids. DNA imputer takes one DNA sequence seed as input and can predict the next amino acid character in a sequence. Furthermore, the RNN can then be used to generate amino acid character by character that will look like the original training data. This code was developed to impute missing DNA to close circular plasmids and is therefore learned on plasmid sequences. 

# usage

to predict the next 100 amino acids that are likely followed by *ATACT*: 

```
th sample.lua model/plasmids.t7 -gpuid -1 -primetext "ATACT" -length 100
```


# install

see https://github.com/karpathy/char-rnn for installation guide

