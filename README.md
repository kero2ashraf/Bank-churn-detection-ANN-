# Bank-churn-detection-ANN-

# Bank-churn-detection-ANN-

The objective of the Bank-churn-detection-ANN project is to build an artificial neural network (ANN) model that can predict whether a customer is likely to leave the bank. This is a challenging task, as there are many factors that can influence a customer's decision to leave, such as the quality of service, the fees charged, and the products and services offered.

The ANN model will be trained on a dataset of historical data that includes information about customers who have left the bank and those who have not. The model will learn to identify the patterns in the data that are associated with customer churn.

Once the model is trained, it can be used to predict whether a new customer is likely to leave the bank. This information can be used by the bank to take steps to prevent customer churn, such as offering better products and services, or improving the quality of customer service.

Here are some of the steps involved in the Bank-churn-detection-ANN project:

Collect the data. The first step is to collect data about customers who have left the bank and those who have not. This data can be collected from a variety of sources, such as customer surveys, transaction records, and social media data.
Prepare the data. The data needs to be prepared before it can be used to train the ANN model. This involves cleaning the data, removing any missing values, and transforming the data into a format that the model can understand.
Choose the ANN architecture. There are many different ANN architectures that can be used for customer churn prediction. The best architecture will depend on the specific data set and the desired accuracy of the model.
Train the model. The ANN model is trained on the prepared data. This process involves adjusting the weights and biases of the model until it can accurately predict customer churn.
Evaluate the model. The performance of the model is evaluated on a holdout data set. This data set was not used to train the model, so it provides an unbiased assessment of the model's accuracy.
Deploy the model. The model can be deployed to production once it has been evaluated and found to be accurate. The model can be used to predict customer churn in real time.
The Bank-churn-detection-ANN project is a challenging but important task. By building an accurate ANN model, banks can prevent customer churn and improve their bottom line.


python packages :
1) numpy
2) pandas
3) matplotlib.pyplot
4) seaborn
5) dataprep
6) tensorflow
7) from keras.models import Sequential
8) from keras.layers import Dense
9) from sklearn.preprocessing import MinMaxScaler
10) from sklearn.model_selection import train_test_split
11) from sklearn.preprocessing import StandardScaler
12) from sklearn.metrics import confusion_matrix,accuracy_score

questions :

1) Overview of the data ?
2) Get the statistical summary of the data ?
3) plot the correlation between the features ?
4) plot the missing value of the data ?
5) plot the data and get the insights and statistics and visualizations?
6) check the duplicated value?
7) plot a pie chart to get the percentages of the exited and no exited?
8) Get a heatmap about the correlation?
9) Get the x and y ?
10) use label encoder to encode the categorical data ?
11) using column transformer to transfrom using encoder and one hot encoder?
12) splitting the dataset into training and test set?
13) make a feature scaling using standard scaler?
14) bulid the first ANN ( deep learning model) ?
15) add the input layer and the first hidden layer ?
16) add the second hidden layer and output layer ?
17) train the ANN model with epochs 100 and get the accuracy of every epoch?
18) get the predictions of the model ?
19) get the confusion matrix ?
20) get the accuracy of the final deep learning model?
