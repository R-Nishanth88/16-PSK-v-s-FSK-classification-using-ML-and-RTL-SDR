# 16-PSK-v-s-FSK-classification-using-ML-and-RTL-SDR
We created  2 block diagrams of 16PSK and FSK in the gnu radio which are connected to the rtl-sdr source and we conect the rtl-sdr device to recieve the signals and then executing when we excuitng the block diagram we'll keep the audio sink to recieve the signals from the input device and then we have file sink which convert the data into csv which we give as 16PSK.csv and FSk.csv in that all the binary enocding inputs are present we will then convert them into the numerical values and then we merge both converted_data_with_16psk.csv and converted_data_with_fsk.csv theese are create by converting into numerica and then limiting the dataset size to 20,000 for both in the next we merge the both data and keep it as merged_data_randomized.csv because we randomly assign the places for the values and we have 2 feature in all 1. values that have numerical values 2. signal_type, which has data of whether it have 16PSK or FSK for that value like that we have in the mereged file whereas in other as u know later we handled missing values and we applied ML classifiers 
Support Vector Machine (SVM)
Random Forest Classifier
K-Nearest Neighbors (KNN)
Logistic Regression
Gradient Boosting Classifier
decision tree
xgboost
adaboost
Voting Classifier
