# Task_3_Flight_Delay_Prediction
Python code for flight delay prediction model. 
# Before executing the attached code, please upload the two provided Excel files: flight_information.csv and ground_information.csv
This code is composed of five parts:
- Part 1: Experiments with four algorithms: 'GradientBoostingRegressor', 'MLPRegressor', 'RandomForest', and 'XGBRegressor' to train the model.
- Part 2: The 'GradientBoostingRegressor' algorithm, which showed the lowest error, was used to select the most important features using PFI.
- Part 3: The model was retrained using only the selected features from part 2 and the 'XGBRegressor' algorithm.
- Part 4: Calculates and displays the average RMSE and average MAE for each leg.
- Part 5: Generates a bar error plot for the average errors per day for all flights.
