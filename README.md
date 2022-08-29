# Stock_prediction_GRU_Pytorch

We'll be analizing stock market data from https://www.kaggle.com/datasets/paultimothymooney/stock-market-data?utm_medium=social&utm_campaign=kaggle-dataset

specifically the JP Morgan Chase bank data. For that we'll first download the data, check its health, split and prepare it. Then we'll load it into a neural network whose main architecture is comprised of GRU cells and a last layer that will act as a linear sum of all the previous data. 

All of this will be done using pytorch as the library for deep learning along with some other packages for different purposes
