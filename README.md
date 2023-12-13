# Next_word_Predictor
### This project based on Long sort term memory[LSTM] based algorithm.
I approched by multi classification method.

Step 1 ) Tokenized the given set of data 

Tokenized means assign the numeric data for every unique text in our dataset

step 2) Split the dataset into 2D list according to there tokenizer

step 3) Find the maximum length of list which are present in 2D tokenized list

step 4) Equalized the dimension of the every lsit of list by pad_sequences method

step 5) Separate our dataset into to parts , first is input_data that is X and output data that is Y

step 6) I approched this problem by multi classification method so, apply the one hot encoding e.g. to_categorical method

step 7) Finally make the model ,
                             A) Transfer the vector data in Embedding Layer
                             B) LSTM Layer [150 nodes(sigma or tanh)]
                             C) Dense layer [283 node]
step 8) Compile our model by loss is categorical_crossentropy , optimizer = 'Adam' , metrics = 'Accuracy'

step 9) Fit our model with 100 epochs

step 10) Check the performance of our model
