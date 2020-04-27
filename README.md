# Udacity_DL_Project3_Generating_a_script

This is the 3rd project for Udacity Deep Learning nanodegree. The aim of the project is to build a recurrent neuron network (RNN) and generate a script based on the model. 

The repository includes: 

the python notebook file for training the data and generate the script using the trained model. (Adapted from Udacity DL Nanodegree Project: Generate a TV script.); 
a downloaded html file to show the results; 
a saved model to generate the script;
other files for deployment and supportive files

You can load the model to generate your own result without training a new one ab initio. 

The parameters for training the model are:

num_epochs = 10
learning_rate = 0.001
vocab_size = len(vocab_to_int)
output_size = vocab_size
embedding_dim = 256
hidden_dim = 512
n_layers = 3
show_every_n_batches = 500
