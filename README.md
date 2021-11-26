# cnn_lstm_trading_strategy

This project contains a Python notebook attempting to implement a cnn/lstm based strategy for trading currency pairs.
The work must be considered as a combined exercise to utilize learnings achieved through studying Jeff Heaton 
from Washington University St. Lois modules for:
"Applications of Deep Neural Networks" https://github.com/jeffheaton/t81_558_deep_learning

The notebook implements;
- Data sourcing (getting tradning data throug the IG.com APIs)
- Various feature engineering e.g. generating columns for weighted moving average, average true range,
  windowing and more.
- Building category labels
- Normalizing data
- Splitting the datasets in to traning, validation and test sets
- Implementing a couple of Tensorflow/Keras models for cnn and lstm combined

Originally the notebook was created using Amazon SageMaker Notebooks
