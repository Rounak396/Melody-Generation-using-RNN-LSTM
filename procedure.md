# Melody Generation Problem
1. Treat Melody as time series
2. Time-Series Prediction Problem
3. Vocabulary of notes

# Melody Generation Procedure
1. We pass in chunks of melodies
2. Then we ask the LSTM to predict the next node
Basically, we start with a seed melody and fit into the model and the model then predicts the next node. We append the next node to the initial node. The new generated node is then fit into the neural network and the next node is predicted. And, the iteration continues.

# Why do we use RNN LSTM?
1. Melodies have long-term structural pattern.
2. LSTMs can capture long-term temporal dependencies.