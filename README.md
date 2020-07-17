# Stock_Price_Prediction

### Stock prediction:
                  Stock market prediction is the act of trying to determine the future 
                  value of a company stock or other financial instrument traded on an exchange. 
                  The successful prediction of a stock's future price could yield significant profit. 
                  The efficient-market hypothesis suggests that stock prices reflect all currently available
                  information and any price changes that are not based on newly revealed information thus are 
                  inherently unpredictable. 
                  
                  
### Description:
                Problem statement was to predict increase or decrease in stock price for next day.
                I addressed this as classification problem. There are many classification algorithms in neural
                network such as SVM, LSTM and Backpropagation algorithm . Here I have used Long Short Term Memory (LSTM).


### Approach:
             Our approach to for this project consist of major steps:
                 1.	Dataset creation
                 2.	Implementation of algorithm


### Dataset creation:
             For data collection I used yahoo finance. Yahoo Finance is a database with stock prices for various 
             companies.The stock data obtained from yahoo contains the following parameters:
      
                   *  •	Date
                   *  •	Open
                   *  •	High
                   *  •	Low
                   *  •	Close
                   *  •	Adj Close
                   *  •	Volume
           I took the daily closing values of each of the stock as the stock value for a day.


### Algorithm:
               LSTM stands for Long Short Term memory. It is building block of a neural network (like perceptron). 
               LSTM blocks are used to build a recurrent neural network. An RNN is a type of neural network where 
               the output of a block is fed as input to the next iteration. An LSTM block is composed of four main 
               components: a cell, an input gate, an output gate and a forget gate. The cell is responsible for
               "remembering" values over arbitrary time intervals; hence the word "memory" in LSTM. 
               Each of the three gates can be thought of as a "conventional" artificial neuron, as in a multi-layer
               (or feedforward) neural network: that is, they compute an activation (using an activation function) 
               of a weighted sum. Intuitively, they can be thought as regulators of the flow of values 
               that goes through the connections of the LSTM; hence the denotation "gate". 
               There are connections between these gates and the cell. Some of the connections are recurrent, 
               some of them are not.
                   As mentioned earlier stock prediction is a time series problem. LSTM can be used for time series
                predictions. LSTM don’t have the vanishing gradient problem which a traditional RNN has.


### Software and Python libraries:
      *  •	Python 2.7
      *  •	NumPy
      *  •	Pandas
      *  •	scikit-learn
      *  •	matplotlib
      *  •	math
      *  •	keras

### Conclusion:
                 In this project, I have demonstrated a machine learning approach to predict stock market trend using neural
                 network called Long Short Term Memory(LSTM). Result shows how I can use history data to predict stock movement
                 with reasonable accuracy.
