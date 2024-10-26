# Create a linear regression model for analyzing road accident severity using the relevant dataset related to the scenario. Please specify the dependent variable (the variable you want to predict) and the independent variables (the factors that influence the accident severity). After creating the model, save it for future use. Then, provide an example of using the model to predict accident severity for a hypothetical set of independent variables, and explain how such a model could be beneficial for traffic accident analysis and prevention in underdeveloped countries. Add all relevant screen shots as well from your program. Also share the URL of your GITHUB (Where you have uploaded your work) so that I can simulate the same

## Variables
- Dependent Variable (Target): Accident_severity
## This is what we want to predict: how severe an accident might be based on other conditions.
- Independent Variables (Features):
- These are factors that likely influence accident severity. From the dataset, relevant variables could include:
- Age_band_of_driver: Age range of the driver, like '18-30' or '31-50'.
- Sex_of_driver: Gender of the driver.
- Educational_level: Education level of the driver.
- Driving_experience: Years or level of driving experience.
- Lanes_or_Medians: Type or number of lanes.
- Road_surface_type: Type of road surface (e.g., asphalt).
- Light_conditions: Lighting conditions at the time of the accident.
- Weather_conditions: Weather at the time of the accident

- I am importing the necessary libraries: Pandas for data handling, sklearn for model creation and evaluation and for the joblib to save the trained model. Also i am loading the data.
- Assigning the X and y variables y to the target variable and indepent variables
and converting them into the numeric form
- Diving, training and testing and training them with linearregression and checking the performance using the MSE and R squared values(for accuracy)
- Finally I am saving the so as it can be used again
we are loading the data and use to predict the severity 

# Done By : Omar