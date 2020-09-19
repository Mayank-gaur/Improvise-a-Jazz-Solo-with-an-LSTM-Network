# Improvise-a-Jazz-Solo-with-an-LSTM-Network
Generates new  Jazz music  via sampling .  Any other music can also be generated  by this model just by changing the training set.
Algortithm used:
I trained a model that predicts the next note in a style that is similar to the jazz music that it's trained on. The training is contained in the weights and biases of the model.
In Part 3, I used those weights and biases in a new model which predicts a series of notes, using the previous note to predict the next note.
The weights and biases are transferred to the new model using 'global shared layers' described below"

Dont forget to import these resources in your notebook:  https://vouauswzkajtndklcrhfno.coursera-apps.org/tree/Week%201/Jazz%20improvisation%20with%20LSTM
