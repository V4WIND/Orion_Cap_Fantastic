# Orion_Cap_Fantastic
https://towardsdatascience.com/useful-sentiment-analysis-mining-sec-filings-part-1-358942fc98ed

https://www.linkedin.com/learning/python-for-data-science-essential-training/getting-started-with-jupyter?autoplay=true&trk=course_preview&upsellOrderOrigin=trk_default_learning

https://www.hertzler.com/manual/8.9.1/7_Appendices/SPC/CalcNormalityOfDist.htm

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



https://www.datacamp.com/community/tutorials/understanding-logistic-regression-python
https://towardsdatascience.com/logistic-regression-a-simplified-approach-using-python-c4bc81a87c31
https://towardsdatascience.com/building-a-logistic-regression-in-python-step-by-step-becd4d56c9c8

https://www.analyticsvidhya.com/blog/2016/02/7-important-model-evaluation-error-metrics/
https://discuss.analyticsvidhya.com/t/is-concordance-the-best-way-to-predict-logistic-regression-model-reliability/267

