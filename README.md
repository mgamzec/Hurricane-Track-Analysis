# Hurricane-Track-Analysis
Forecasting hurricane movements - A machine learning approach

This submodule contains a notebook which provides 6h forecasts of the next positions of hurricanes in the Atlantic Ocean. Taking into account the motion history of the hurricanes recorded up to that point as well as their current properties, feature sets are created that are then used to train and evaluate a suite of machine learning models including a random forest regressor, support vector machine and a multi layer perceptron.

The notebook can be tested in a Google Colab Environment, even though it is strongly recommended to run it locally. This is because the training and especially hyperparameter tuning of the machine learning models poses requirements on the number of CPU cores that exceed the possibilities provided by Google Colab. Note that executing the whole script on a machine with 16 cores already takes about 2.5 hours. Reducing the number of iterations for the hyperparameter tuning will greatly reduce the necessary processing time though.

<img width="1087" height="694" alt="map_all" src="https://github.com/user-attachments/assets/6f380508-8a13-43df-8bc4-85f6e3180dd0" />

