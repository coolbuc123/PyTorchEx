# Network construction
Template network for treasury interest prediction is made.  
Three models of rnn, cnn, rnn+attention are uploaded.  
rnn+attention includes rnn model, but there are several parameters in a model,  
so it would be easier to find base model with rnn and apply it to rnn+attention.  
It would be nice if you can find results larger than mid fifties.  

## things to do
* run model with newly obtained economy information and get good model settings
* Find good observation by changing predicting period and input window size

## not implemented functions
You can implement below functions  
* early stopping : automatically stop learning
* make target as binary or multiple classification variables 

## Parameters to adjust
* technical input selection 
    * difference variables are added
    * need to check they are effective 
* introduce technical indicators    
* adequate predicting period and input window size
* network construction : number of layer, elements, ...
* network hyper-parameter : hidden layer dimension, dropout rate, learning rate, epoch
* good normalization method 

## etc 
* we can add visualization for learning and result
* we can change accuracy format like f1_score

## Note
* accuracy should be evenly distributed in classes

