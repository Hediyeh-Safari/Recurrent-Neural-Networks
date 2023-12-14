# Recurrent-Neural-Networks

You've got a stock price dataset spanning 5 years, one entry per day. The goal is to predict the opening price for the next day using the past three days' Open, High, Low prices, and volume, making each sample have 12 features. Here's a breakdown of what you need to do:

1-Dataset Creation and Splitting:

Initially, create a dataset using the latest 3 days' features and the following day's opening price as the target.
Randomize this data and divide it into 70% for training and 30% for testing. Save these as 'train_data_RNN.csv' and 'test_data_RNN.csv' in the data directory. Comment out this part of the code.

2-Training RNN:

Fill out the 'train_RNN.py' file to read 'train_data_RNN.csv', preprocess the data, and train your RNN model.
Save your trained model as 'YOUR_ID_RNN_model' in the models directory. Ensure the test data is never used in this file after model saving.

3-Testing RNN:

Complete the 'test_RNN.py' file to read 'test_data_RNN.csv' and run predictions using your trained model.
Display the loss on your test data and plot the true vs. predicted values, labeling the axes and legend.

4-Report Details:

Your report should cover the dataset creation methodology, preprocessing steps, and the process of selecting the optimal network design.
Explain your final network architecture, including details like epochs, batch size (if applicable), loss function, training algorithm, etc.
Present the output of the training loop with comments and insights.
Display the testing output, including the final plot, and provide your observations on it.
Discuss the potential impact of using more days for features, and if possible, experiment without uploading new datasets.
Ensure that both 'train_RNN.py' and 'test_RNN.py' run independently from the command line without additional inputs. Your report should encompass the steps taken, the reasoning behind your decisions, and the outcomes obtained during training and testing.
