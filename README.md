# Surrounding Vehicle Trajectory Prediction using RNN-LSTM

<p align="center">
  <img src="https://github.com/sanketsalunkhe12/RNN-LSTM/blob/main/readme_data/ezgif.com-gif-maker%20(1).gif">
</p>

### Recurrent Neural Network (RNN):

<p align="justify"> RNN is a class of NN which uses previous output as input. It takes sequential data/time-series data and generate future predicted sequence. RNNs are distinguished by their “memory” as they take information from prior inputs to influence the current input and output. The output of recurrent neural networks depends on the prior elements within the sequence. Also RNN share parameters across each layer of the network. But RNNs tend to run into two problems, known as <b> exploding gradients </b> and <b> vanishing gradients. </b> It is difficult to capture long-term dependencies because of the multiplicative gradients that can be exponentially decreasing/increasing with respect to the number of layers. This problems cab be solved by methods like LSTM and GRU.</p>

<p align="center">
  <img src="https://github.com/sanketsalunkhe12/RNN-LSTM/blob/main/readme_data/Screenshot%20from%202022-08-03%2009-59-45.png" width="350">
  <img src="https://github.com/sanketsalunkhe12/RNN-LSTM/blob/main/readme_data/Screenshot%20from%202022-08-03%2010-49-11.png" width="550">
</p>

### Long Short Term Memory (LSTM):

<p align="justify"> It is a solution to the vanishing gradient problem and long-term dependencies. If the previous state that is influencing the current prediction is not in the recent past, the RNN model may not be able to accurately predict the current state. LSTMs have <b> cells </b> in the hidden layers of the neural network, which have three gates–an <b> input gate, an output gate, and a forget gate. </b> These gates control the flow of information which is needed to predict the output in the network. 

RNN are networks with loops in them, allowing information to persist. </p>
