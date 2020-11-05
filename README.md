# Check-Algorithm-Bias-In-Hiring

- [Exploratory data analysis]():

	Find the distribution of overall rating, the age, gender and race using some histogram, kernal density estimation plot, box plot.
	For example, the distribution of rating in each category of protected attributes, the kernal density estimation of each dimension of assessment given recommend of not.

- [Stat and machine learning model](https://github.com/DwayneLi/Check_Algorithm_Bias_In_Hiring/blob/master/scripts/stat_model_v1_0_.ipynb)：

	Build t-test based on linear regression and random forest algorithm to check if the protect attribute have statistical significant relationship with recommend result and chi-squared test if protect attributes are indenpent to recommend result. The t-test show no significant relationship but chi-squared test implies the protect attributes are not independent to the recommend result.

- [Pivot table](https://github.com/DwayneLi/Check_Algorithm_Bias_In_Hiring/blob/master/scripts/attributes_and_recommend_rate.xlsx):

	Create pivot table in excel listing all combinations of age, race and gender along with corresponding recommend rate. The pivot table tells us that except for attribute combinations with few people, the overall recommend rate show no bias in hiring.

- Cutting-edge algorithms in check and mitigate bias

We applied [FairML](https://github.com/DwayneLi/Check_Algorithm_Bias_In_Hiring/blob/master/scripts/FairMachineLearning.ipynb), Fairlearn, [AI Fairness 360](https://github.com/DwayneLi/Check_Algorithm_Bias_In_Hiring/blob/master/scripts/bias%20mitigation%20v1.1%20base%20model%20v1.0%20.ipynb) to check feature importance, test fairness metrics and build migigate bias pipeline.The 

- Final report and achivement

  We write [final report](https://github.com/DwayneLi/Check_Algorithm_Bias_In_Hiring/blob/master/Final_Report.pdf) and made [final presentation](https://github.com/DwayneLi/Check_Algorithm_Bias_In_Hiring/blob/master/Final_Presentation.pptx) about all the works we have done. The check and mitigate bias model has merged into company’s equal opportunity promotion and has applied to cover more than 90% of company customers.
