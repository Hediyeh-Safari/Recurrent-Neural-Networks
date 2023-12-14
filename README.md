# Recurrent-Neural-Networks

In this project, your task is to build a Recurrent Neural Network (RNN) for stock price prediction using a provided dataset spanning five years, with one sample per day (q2_dataset.py). Follow the specified steps outlined below:

Dataset Creation (train_RNN.py):

Create a dataset using the latest 3 days' Open, High, Low prices, and volume as features, and the next day's opening price as the target.
Randomize the created data and split it into 70% training and 30% testing.
Save the training and testing datasets to 'train_data_RNN.csv' and 'test_data_RNN.csv' in the data directory, respectively.
Comment out this code once completed.
Training Script (train_RNN.py):

Populate the file to read 'train_data_RNN.csv,' preprocess the data, and train your RNN network.
Save the trained model with the name 'YOUR_ID_RNN_model' in the models directory.
Ensure that the test data is not used at any point in this file after saving the model.
Testing Script (test_RNN.py):

Populate the file to read 'test_data_RNN.csv' and run the prediction model.
Print the loss on your test data and generate a plot of the true and predicted values, with appropriate labels for axes and legend.
Command Line Execution:

Ensure that both 'train_RNN.py' and 'test_RNN.py' run from the command line without requiring additional inputs or arguments.
Include the following in your report:

Dataset Creation Explanation:

Describe how you created your dataset, specifying the features and target variable.
Preprocessing Steps:

Outline any preprocessing steps undertaken, such as normalization or scaling.
Network Design:

Detail the design steps taken to find the best network architecture, including the number of epochs, batch size (if applicable), loss function, and training algorithm.
Final Network Architecture:

Provide the architecture of your final network, specifying the chosen parameters.
Training Loop Output:

Display the output of the training loop with comments on the output, highlighting any trends or observations.
Testing Output:

Showcase the output from testing, including the final plot with comments on its interpretation.
Experimentation:

Discuss what would happen if more days were used for features and consider trying it (without uploading the datasets).
By following these steps and providing detailed explanations and outputs in your report, you will create a comprehensive stock price prediction system using an RNN.
