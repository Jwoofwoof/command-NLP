# command-NLP

## Input-Output
Input: two sentences, combined as one and seperated by special token [SEP]
Output: the sentence after applying the command to the input sentence


## Idea of how to implement
 - sequence to sequence model
 
 - Build a transformer model, make sure it works
 - Create data set
     - Use the English sentences from English to French Data set and add special Tokenizer
        - modify them so they become sentence1[SEP]command1, sentence2[SEP]command2 
     - create output sentence (sentence after command) for each input
     - Maybe 10,000 
 - Run model on newly created data set, make sure it works
 - Compared a model and update correctness




