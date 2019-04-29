# Orion_Cap_Fantastic

11
#Variable Analysis -> loan_amnt (Duplicate Variable - Ignored)
print("% of Missing Values = ",train['loan_amnt'].isnull().sum()/train.shape[0]*100)
print("-----------------------------------------------------------")
print("Distribution Plot:")
sns.distplot( train[train["loan_status"] ==1]["loan_amnt"] , color="red", label="Defaulters",hist=False)
sns.distplot( train[train["loan_status"] ==0]["loan_amnt"] , color="skyblue", label="Non-Defaulters",hist=False)



​%matplotlib inline

import os
os.chdir('C:\\Users\\v113805\\Documents\\Orion_EXL')
os.listdir()
#wd = os.getcwd()
#wd
