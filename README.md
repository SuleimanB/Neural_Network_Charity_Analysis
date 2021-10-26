# Neural_Network_Charity_Analysis

Overview of the analysis
The purpose of this analysis is to report on the performance of the deep learning model that was created for AlphabetSoup. I will outline my brief experience and what could have been done to improve the model if I was not met with time constraints

Results
Data Processing
The variables that are considered target for this data neural network would be the "IS_SUCCESSFUL" column that was created after the merge took place. It also served to be the feature of this model as it aimed to predict whether approvals would take place or not. Lastly, the unnecessary identification columns for EIN and NAME were removed since they were not a requirement.

Compiling, Training, and Evaluating the Model
The most successful model included the following properties. Amount of neurons that were made up of layer 1 featuring 80 nodes and layer 2 featuring 30 nodes with the first and second layer featuring the relu activation method and the output layer featuring sigmoid activation. The peak efficiency I was able to reach was 70 percent as attempts to modify the model and data did not yield positive results up until the tweaking of the original structure that was made. All other attempts of dropping what was seemingly unnecessary columns, adding layers and neurons and changing activation functions yielded no improvements but with more time and research I believe a higher score was more then achievable.

Summary
In summary the model I created was close to the 75 percent accuracy score that was aimed for but as a result of unnecessary changes and not having a structured enough layer structure. I believe with additional changes to the dataset to comb out any columns that were not linked to the "IS_SUCCESSFUL" column and having a bit more time to iron out the layers and neurons that are in the model, it would have led to the desired accuracy score.
