# Recurrent-Neural-Networks

Given a 5-year stock price dataset with daily samples, create a Recurrent Neural Network (RNN) to predict the next day's opening price using the past 3 days' Open, High, Low prices, and volume (12 features per sample). Follow these steps:

1. **Data Preparation:**
   - In `train_RNN.py`, create a dataset using the latest 3 days as features and the next day's opening price as the target. Randomize and split the data into 70% training and 30% testing, saving them as 'train_data_RNN.csv' and 'test_data_RNN.csv,' respectively. Comment out this code.

2. **Training RNN:**
   - Populate `train_RNN.py` to read 'train_data_RNN.csv,' preprocess the data, and train the RNN. Save the model as 'YOUR_ID_RNN_model' in the models directory. Ensure the test data is not used in this file after saving.

3. **Testing RNN:**
   - Populate `test_RNN.py` to read 'test_data_RNN.csv' and run predictions. Print the loss on the test data and visualize true vs. predicted values using a plot with appropriate labels.

4. **Command-Line Execution:**
   - Ensure both `train_RNN.py` and `test_RNN.py` can run from the command line without additional inputs.

Report Contents:

- **Dataset Creation:**
  - Explain how the dataset was created.

- **Preprocessing:**
  - Detail any preprocessing steps applied to the data.

- **Network Design:**
  - Describe the steps taken to find the best network design.
  - Explain the architecture of the final network, including the number of epochs, batch size (if applicable), loss function, and training algorithm.

- **Training Output:**
  - Provide the output of the training loop with comments.

- **Testing Output:**
  - Display the output from testing, including the final plot, and provide comments on the results.

- **Experimentation:**
  - Discuss the potential impact of using more days for features, encouraging exploration without uploading datasets.

Ensure clarity and conciseness in presenting your approach and results in the report.
