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

<p align="justify"> It is a solution to the vanishing gradient problem and long-term dependencies. If the previous state that is influencing the current prediction is not in the recent past, the RNN model may not be able to accurately predict the current state. LSTMs have <b> cells </b> in the hidden layers of the neural network, which have three gates–an <b> input gate, an output gate, and a forget gate. </b> These gates control the flow of information which is needed to predict the output in the network. </p>

<p align="center">
  <img src="https://github.com/sanketsalunkhe12/RNN-LSTM/blob/main/readme_data/Screenshot%20from%202022-08-03%2011-45-56.png">
</p>

<p align="justify"> RNN are networks with loops in them, allowing information to persist. RNN connects previous information to the present task. A chunk of the neural network, <b> A, </b> looks at some input <b> Xt </b> and outputs a value <b> ht.</b> A loop allows information to be passed from one step of the network to the next. RNN can be considered as multiple copies of the same network, each passing a message to a successor. This chain-like nature reveals that RNNs are intimately related to sequences and lists types of data i.e time series. </p>

<p align="justify"> When we only need to look at <b> recent information </b> to perform the present task. In such cases, where the gap between the relevant information and the place where it’s needed is small, RNNs can learn to use the past information. But there are also cases where we need more context. It’s entirely possible for the gap between the relevant information and the point where it is needed to become very large. As that gap grows, RNNs become unable to learn to connect the information. In such cases LSTM and GRU comes into picture. LSTM remember information for long periods of time is practically their default behavior. </p>

<p align="justify"> LSTM has a similar chain-like structure but with different architecture. LSTM has the ability to remove or add information to the cell state, via gates. Gates are a way to optionally let information through. </p>

<p align="center">
  <img src="https://github.com/sanketsalunkhe12/RNN-LSTM/blob/main/readme_data/Screenshot%20from%202022-08-03%2012-17-19.png">
</p>


