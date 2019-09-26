# <center> Fair or Not: Evidence from HMDA Data </center>

## <center> Anji Zhao, Chenghao Li, Yiwei Zhang </center>
In this project, we propose to apply machine learning algorithms we learned from the course ORIE 4741 to explore **the Home Mortgage Disclosure Act (HMDA)** Data. We try to answer the following question: *Which type of the applicants is more likely to get credits and whether our model is unfair to some particular individuals or ethnicity groups?* In order to answer this question, we plan to first clean the dataset and do some descriptive statistics to see if there are any patterns. Then we will implement supervised learning algorithms to do predictions for the mortgage applications. Also, we will do Principle Component Analysis to figure out particular features that are important to the predictions. Finally, we will examine the prediction results by different ethnicity groups to see whether our model is fair or not.

Housing mortgage loan is one of the most important financial instruments that enable borrowing a property without paying the whole type. During the year of 2007 to 2008, mortgage loan was known as a crucial cause to the global financial crisis. Housing mortgage loan granting procesure theoretically relies on applicants' background information, and it is important for the banks to predict whether an applicant should be approved in order to avoid default risk. However, one model may not fit all people in this country. Different races, ethnicities, genders are supposed to have equal opportunities to get approved, therefore, it is also crucial to ensure the model takes only financial conditions into account.

Since we focus on home mortgage opportunities in this project, the data set we plan to use is the Home Mortgage Disclosure Act (HMDA) listed in www.consumerfinance.gov from 2007 to 2012. The data set contains many valuable variables, such as denial reason, loan purpose, loan type, which can extract interesting information through appropriate modeling. Moreover, the HMDA data set contains variables about race, ethnicity and sex, which allows us to explore in depth whether the our fitted model is fair or not. In addition, our data set covers both the subprime mortgage crisis and the post-crisis period, so we can study the impact of the crisis over the housing mortgage system.