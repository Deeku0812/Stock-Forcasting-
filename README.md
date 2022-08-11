# Simplilearn Certification Program

# Stock-Forcasting-
Stock Prediction &amp; Future Forecasting Using Stacked LSTM

![image](https://user-images.githubusercontent.com/66784537/183088648-cd18aa47-7bb9-4f6c-adcc-f8855ec654ac.png)

#### Problem Statement: 
We have to predict stock price and forecasting next 60 days stock price using Deep learning method. Based on Brownian Motion, the future variations of stock price are independent of the past. So, it is impossible to predict the exact stock price, but possible to predict and capture the upward and downward trends.

#### Data Collection:
We extracted data using yahoo finance API. 

#### Stacked LSTM: 
A Stacked LSTM architecture can be defined as an LSTM model comprised of multiple LSTM layers. An LSTM layer above provides a sequence output rather than a single value output to the LSTM layer below. Specifically, one output per input time step, rather than one output time step for all input time steps

![image](https://user-images.githubusercontent.com/66784537/183088241-6d389462-49e9-4c97-9906-947097a52761.png)


                                                            
stacked LSTM is to allow for greater model complexity. In case of a simple feedforward net, we stack layers to create a hierarchical feature representation of the input data to then use for some machine learning tasks. The same applies for stacked LSTM's.
At every time step an LSTM, besides the recurrent input. If the input is already the result from an LSTM layer (or a feedforward layer) then the current LSTM can create a more complex feature representation of the current input


#### Prediction: 
 For GAIL Stock
 
![image](https://user-images.githubusercontent.com/66784537/183088568-a4f409e1-8311-4746-ae58-710c2c5ee885.png)


#### Furcating Next 30 Days 
For GAIL stock
![image](https://user-images.githubusercontent.com/66784537/183088648-cd18aa47-7bb9-4f6c-adcc-f8855ec654ac.png)

 


