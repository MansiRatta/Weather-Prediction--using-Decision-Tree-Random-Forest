# Weather-Prediction--using-Decision-Tree-Random-Forest

Weather Prediction- Decision Tree & Random Forest 

This repository contains the code for a prediction of weather using Decision Tree and Random Forest algorithm.The dataset includes information about features that affect rainfall like humidity, temperature, wind speed, pressure. The goal of this project is to predict if it’ll rain or not using the Decision Tree & Random Forest Algorithm.

Dependencies

Python 3.x
Jupyter Notebook
pandas
NumPy
scikit-learn
matplotlib

Dataset

The dataset (weatherAUS.csv) contains the following columns:
MinTemp
MaxTemp
Rainfall
WindGustSpeed
WindSpeed9am
WindSpeed3pm
Humidity9am
Humidity3pm
Pressure9am
Pressure3pm
Temp9am
Temp9am
RainToday
RainTomorrow

Description

In this project, we have started by reading the variables to understand them better. 

Moving forward, since the variables “RainToday” & “RainTomorrow” are categorical variables, we have converted them into an integer variable. In that, 0 implies “No” and 1 implies “Yes”. Otherwise our machine learning algorithm won't be able to directly take in those features as inputs. 

So, if RainToday = 0 in a data point, it means that there was no rain that day. 

After having all the features ready, we have built the Decision Tree Model by splitting our data into training and testing data.

In the end, we evaluated our model using the Classification Report and Confusion Matrix to note the precision, recall, f1-score of our model.

After the evaluation, we have created a textual representation of the decision tree model stored in the variable Dtree. The export_text function converts the decision tree into a human-readable text format.

It is useful for inspecting the structure of a decision tree model in a simple, text-based format, which can be helpful for understanding how the model makes predictions and interpreting its behavior.

Post this, we have also created a Random Forest classifier and used it to perform the same prediction.


License

This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments

This analysis is based on the weather data (Australia).

Credits to the contributors of scikit-learn, pandas, NumPy, matplotlib for their invaluable tools for data analysis and machine learning.

Feel free to contribute or provide feedback!

