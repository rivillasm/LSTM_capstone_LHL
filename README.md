# LSTM_capstone_LHL
Time Series forecast with LSTM networks

The notebooks has to versions of the model, Version A and Version B

# Version A   - Learns the model with the training data once and predicts prices for several days
- load data
- split data in training and test
- training datased scaling and reshaping
- LSTM run   (runs only once learning with the trainind dataset)
- losss & accuracy displays
- get and reshape testing dataset
- forecast
- plot 
- Saving/loading model
- Results


# Version B   - Learns the model with a rolling (daily) training dataset and predicts price only once
- load data
- split data in training and test
- training datased scaling and reshaping
- LSTM run (runs several times , one for each prediction date, training dataset gets updated everyday with the latest price info)
- losss & accuracy displays
- get and reshape testing dataset
- forecast
- prepare data for visualization
- Results
