# README

IMLS Final Project description: 
### Libraries
The following libraries were used for the project: 
OS, pathlib - for file manipulation 
Statistics for maths operations
Pandas - for working with dataframes
NumPy - for working with image arrays
random - for randomly splitting datasets into training and test sets
TensorFlow for deep learning modelling
tensorflow.keras.models for Model, layers, losses 
sklearn.metrics for accuracy_score, precision_score, recall_score, roc_curve, auc
The RandomForest was implemented using Scikit-learn library
tqdm - a Python library used to display smart progress bars that show the progress of Python code execution.

### Other required files 
Other requirements for running the models:


2. IMLS Final Project File Organisation: 
$ -- MLforPDThesis

README.md (this file)
MSc_Project_LitRev_Report_SGrant_2020_11062021.docx
MSc_Project_Interim Report_SGrant_2020.docx
MSc_Project_Final_Report_SGrant_2020
2DNNModelDyskinesiaBig.ipynb
LSTMModelDyskinesiaMetrics.ipynb
RandomForestModelDyskinesia.ipynb
SynapseDataPrepLabels.ipynb 
|--saved_model (contains saved CNN model)
|--|--my_CNN_model
|--|--|--|assets
|--|--|--|variables
|--|--keras_metadata.pb
|--|--saved_model.pb
|--|--my_LSTM_model
|--|--|--|assets
|--|--|--|variables
|--|--keras_metadata.pb
|--|--saved_model.pb
|--|--RandomForest.joblib
|--TFLite_models (contains saved CNN and LSTM TFLite models)
|--|--CNNModel1.tflite
|--|--LSTmodel1.tflite
|--|--LSTMmodel2.tflite
|--Training (training data sets -- these files are not shared on Github due to access restrictions imposed by Synapse site.) 
|--|--3_BOS_LeftLowerLimb
|--|--|--rawData_Day1.csv 
|--|--|--rawData_Day4.csv 
|--|--4_BOS_LeftLowerLimb
|--|--|--rawData_Day1.csv 
|--|--|--rawData_Day4.csv 
|--|--5_BOS_LeftLowerLimb
|--|--|--rawData_Day1.csv 
|--|--|--rawData_Day4.csv 
|--|--6_BOS_LeftLowerLimb
|--|--|--rawData_Day1.csv 
|--|--|--rawData_Day4.csv 
|--|--7_BOS_LeftLowerLimb
|--|--|--rawData_Day1.csv 
|--|--|--rawData_Day4.csv
|--|--8_BOS_LeftLowerLimb
|--|--|--rawData_Day1.csv 
|--|--|--rawData_Day4.csv  
|--|--9_BOS_LeftLowerLimb
|--|--|--rawData_Day1.csv 
|--|--|--rawData_Day4.csv 
|--|--10_BOS_LeftLowerLimb
|--|--|--rawData_Day1.csv 
|--|--|--rawData_Day4.csv 
|--|--13_BOS_LeftLowerLimb
|--|--|--rawData_Day1.csv 
|--|--|--rawData_Day4.csv 
|--|--16_BOS_LeftLowerLimb
|--|--|--rawData_Day1.csv 
|--|--|--rawData_Day4.csv 
|--|--17_BOS_LeftLowerLimb
|--|--|--rawData_Day1.csv 
|--|--|--rawData_Day4.csv 

|--11_BOS_LeftLowerLimb
|--|--rawData_Day1.csv 
|--|--rawData_Day4.csv 
|--12_BOS_LeftLowerLimb
|--|--rawData_Day1.csv 
|--|--rawData_Day4.csv 
|--18_BOS_LeftLowerLimb
|--|--rawData_Day1.csv 
|--|--rawData_Day4.csv 
|--19_BOS_LeftLowerLimb
|--|--rawData_Day1.csv 
|--|--rawData_Day4.csv 