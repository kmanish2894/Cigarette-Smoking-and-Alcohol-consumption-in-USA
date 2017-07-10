# Cigarette Smoking and Alcohol consumption in USA
Alcohol and cigarettes are very closely linked. Thus, not only are people who drink alcohol more likely to smoke (and vice versa) but also people who drink larger amounts of alcohol tend to smoke more cigarettes. Smokers are more likely than those who have never smoked to report engaging in poor lifestyle choices, including drinking above the guidelines and binge drinking as well as not eating the recommended amounts of fruit and vegetables, according to a new study out today. Coffee, alcohol and cigarette consumption are potential protective factors for the development of Parkinson disease. Parkinson disease a neurological problem which effects the nerves and the brain in the human body. It effects the movements of the body parts. 


In this project, research is based on connections between smokers and alcohol consumption individuals and find the patterns that occur amongst different age groups of both men and women. Mainly concentrated areas of interest are dependency between alcohol consumption and cigarette smoking. How likely they are dependent and what will be the factors that are dependent on each other. The various conditions that can be taken into consideration are the drinking status, how often a person drinks in one year, smoking status, usual quantity when smoked cigarettes and the duration (days) of usual cigarette smoking. When you look at the dataset you find a lot variables, values etc., So it is important on what values to find and what to eliminate. Once the data eliminated is it is important to perform data management. Categorizing the age groups, sex etc., Visualizing the dataset is also important as you will get an idea on what data you are working.


The dataset used in this project is <b>U.S. National Epidemiological Survey on Alcohol and Related Conditions (NESARC)</b> is a survey designed to determine the magnitude of alcohol use and psychiatric disorders in the U.S. population. It is a representative sample of the non-institutionalized population 18 years and older. there are 3008 attributes and 43093 instances from the original dataset only a part of this is considered for analysis. 


## Visualizing the dataset:
Data visualization is the presentation of data in a pictorial or graphical format. A primary goal of data visualization is to communicate information clearly and efficiently via statistical graphics, plots and information graphics. Numerical data may be encoded using dots, lines, or bars, to visually communicate a quantitative message. One of the most important benefits of visualization is that it allows us visual access to massive amounts of data in easily digestible visuals. Well-designed data graphics are usually the simplest and at the same time, the most powerful. For this project data visualization is important because it helps in identifying the factors that need attention. Variables which effects other variables. This helps in clarification of which variables to be placed where and when the analysis to be done. 

![ages](https://user-images.githubusercontent.com/20802996/28038276-59481d16-658c-11e7-8166-8e0772b5494a.jpg)



## Data Management:
Before performing any analysis, it is more important to understand what data is taken for analysis and how they are grouped together. It is important to know how many values of each are present in a variable as this is not a direct dataset. This dataset contains values which have different meaning as explained above in the introduction of the dataset. In this the adult age groups i.e., 18-25 in this dataset are categorized into 4 groups which helps in finding which age group smoke more cigarettes. This also helps in finding the variance for future analysis which involve statistical analysis.

## Running analysis of variance

An analysis of variance is a statistical test that evaluates data sets from statistical experiments to see if there are statistically significant differences in the different experimental conditions. In this the data sets are organized by factors and levels. Factors are the different independent variables in your experiment, with each factor being tested at given levels [13]. ANOVA is a statistical technique that assesses potential differences in a scale-level dependent variable by a nominal-level variable having 2 or more categories. This analysis is made because to know association between number of cigarettes smoked per month (response variable) and drank at least one alcoholic drink in life (explanatory variable with 2 levels). Also the association between drinking status (explanatory variable with more than 2 levels) and number of cigarettes smoked per month(response variable). With this analysis OLS regression values can also be detected which help in solving the hypothesis of the test. Ordinary least-squares (OLS) regression is a generalized linear modelling technique that may be used to model a single response variable which has been recorded on at least an interval scale. It is used for estimating the unknown parameters in a linear regression model, with the goal of minimizing the sum of the squares of the differences between the observed responses in the given dataset and those predicted by a linear function of a set of explanatory variables [14]. Here OLS is used to find association between number of cigarettes smoked per month and drank at least one alcoholic drink in life (explanatory variable with 2 levels) and to find association between drinking status (explanatory variable with more than 2 levels) and number of cigarettes smoked per month. Here, the Null hypothesis and Alternate hypothesis are declared as follows,

<b>NULL HYPOTHESIS:(Ho)</b>

There is no association between number of cigarettes smoked per month and drank at least one alcoholic drink in life.

<b>ALTERNATE HYPOTHESIS:(Ha)</b>

There is an association between number of cigarettes smoked per month and drank at least one alcoholic drink in life.

<b>NULL HYPOTHESIS:(Ho)</b>

There is no association between drinking status (i.e., current drinker, ex-drinker and lifetime abstainer) and number of cigarettes smoked per month

<b>ALTERNATE HYPOTHESIS:(Ha)</b>

There is an association between drinking status (i.e., current drinker, ex-drinker and lifetime abstainer) and number of cigarettes smoked per month

## Chi-Square Test of independence:

Chi square test is relating to or denoting a statistical method assessing the goodness of fit between observed values and those expected theoretically. The test is applied when you have two categorical variables from a single population. It is used to determine whether there is a significant association between the two variables [15]. This is used to find how likely it is that an observed distribution is due to chance. It is also called a "goodness of fit" statistic, because it measures how well the observed distribution of data fits with the distribution that is expected if the variables are independent. In this analysis, a categorical variable USEFREQMO which has 6 levels and response variable S2AQ1 drank at least one alcohol drink in last 12 months. This is to find out how many people are addicted to cigarettes and alcohol who drank alcohol in last 12 months.

<b>NULL HYPOTHESIS:(Ho)</b>

There is no association between number of cigarettes smoked per month and drank at least one alcoholic drink in last 12 months.

<b>ALTERNATE HYPOTHESIS:(Ha)</b>

There is an association between number of cigarettes smoked per month and drank at least one alcoholic drink in last 12 months.

## Pearson coefficient
Pearson coefficient is a measure of the linear correlation between two variables X and Y. Pearson's correlation coefficient is the covariance of the two variables divided by the product of their standard deviations. The form of the definition involves a "product moment", that is, the mean of the product of the mean-adjusted random variables. Pearson's correlation coefficient when applied to a sample is commonly represented by the letter r and may be referred to as the sample correlation coefficient. Pearson coefficient is calculated because there are two quantitative variables. The possible research hypotheses are that there is a positive linear relationship between the variables, a negative linear relationship between the variables, or no linear relationship between the variables. 


Here Pearson coefficient is calculated on 

<b>(I)</b> usual quantity when smoked cigarettes(S3AQ3C1) and duration of usual cigarette smoking(S3AQ3D1R)

<b>(II)</b> usual frequency when smoked cigarettes(S3AQ3B1) and duration of usual cigarette smoking(S3AQ3D1R)

## Potential Moderator

Potential moderator is tested based upon the results of Pearson coefficient. In this moderator analysis is made on drank at least one alcoholic drink in past 12 months shows any significant statistical relationship between usual cigarette smoking quantity(USQUAN) and drinking status(CONSUMER).

## ANALYSIS RESULTS:

<b> Running Variance results: </b> 

<b>NULL HYPOTHESIS:(Ho)</b>

There is no association between number of cigarettes smoked per month and drank at least one alcoholic drink in life.

<b>ALTERNATE HYPOTHESIS:(Ha)</b>

There is an association between number of cigarettes smoked per month and drank at least one alcoholic drink in life.

From the output, the F-statistics for the above situation is 0.32 and the p-value is 0.57. Since the p value 0.57>0.05 null hypothesis can be accepted.
This means young adult smokers who drank at least one alcoholic drink in life smoke up to 321.2 cigarettes per month and young adult smokers who did not drank at least one alcoholic drink in life smoke up to 304.7 cigarettes per month.

### Post hoc paired comparisons (i.e. more than two levels of a explanatory variable):

<b>NULL HYPOTHESIS:(Ho)</b>

There is no association between drinking status (i.e., current drinker, ex-drinker and lifetime abstainer) and number of cigarettes smoked per month

<b>ALTERNATE HYPOTHESIS:(Ha)</b>

There is no association between drinking status (i.e., current drinker, ex-drinker and lifetime abstainer) and number of cigarettes smoked per month

The F-statistics and p-value for the above situation is 0.75 and 0.46 respectively. Since the p value 0.46>0.05 we shall accept null hypothesis.

## Chi Sqaure Test results:

From the output, it can be said that there are 68 participants who smoked approximately one day a month with drank at least one alcoholic drink per month and 3 participants smoked one day a month without drinking at least one alcoholic drink in past 12 months.

On the other hand, there are 1242 participants who smoke 30 days in a month and drank at least one alcoholic drink in past 12 months and approximately 18 participants smoked 30 days and did not consume at least one alcoholic drink in past 12 months.

<b>NULL HYPOTHESIS:(Ho)</b>

There is no association between number of cigarettes smoked per month and drank at least one alcoholic drink in last 12 months.

<b>ALTERNATE HYPOTHESIS:(Ha)</b>

There is an association between number of cigarettes smoked per month and drank at least one alcoholic drink in last 12 months.

![kjzdbvzk](https://user-images.githubusercontent.com/20802996/28038387-b7c31738-658c-11e7-9508-d7803a5d069c.jpg)


There is an association between smoking frequency and drank at least one alcoholic drink in past 12 months. From the first output screen the it can be observed that chi square value is 3.81 and associate p value is 0.57. Since there is no significant difference and p value > 0.05 we can accept null hypothesis. Furthermore Bonferroni Adjustment is used and compared all the 6 levels with USEFREQMO. From the bar graph, it can be visualized that there are no much significant changes between all the comparisons except for values 2.5 and 22.0 which are very slightly different. 

## Pearson Correlation results:

The Pearson’s correlation coefficient for association between quantity and duration of cigarette smoking is 0.4033 which indicates that there exists a weak positive relationship between usual quantity when smoked cigarettes and duration of usual cigarette smoking. The square of Pearson’s correlation is 0.162. So, if  the quantity of usual cigarette smoking is known it is easy to predict 16% of the variability in duration of usual cigarette smoking. However, it also means 84% of the variability is unaccounted. The Pearson’s correlation coefficient for association between frequency and duration of cigarette smoking is -0.8257 which is close to -1, that indicates there is a strong negative relationship between frequency and duration of cigarette smoking i.e. as duration of cigarette smoking decreases the usual frequency of cigarette smoking increases. The square of Pearson’s correlation is 0.681. So, if we know the frequency of usual cigarette smoking we can predict 68% of the variability in duration of usual cigarette smoking. However, it also means 32% of the variability is unaccounted.

## CONCLUSION:

From the variance test, it can be concluded that CONSUMER 3 which indicates lifetime abstainer smokes the lowest number of cigarettes per month (304.7) and CONSUMER 2 which indicates ex-drinker smoke the highest number of cigarettes per month (353.3). Also, it can be observed that the multiple comparison of means using Tukey HSD shows reject column as false for all comparisons i.e., Current Drinker (1) Vs Ex-Drinker (2), Current Drinker (1) Vs Lifetime Abstainer (3) and Ex-Drinker (2) Vs Lifetime Abstainer (3). Finally, it can be concluded that there is no association between number of cigarettes smoked per month and drank at least one alcoholic drink in life. Also, there is no association between drinking status and number of cigarettes smoked per month. For the Chi square test, it can be concluded accept null hypothesis i.e., there is no association between smoking frequency and drank at least one alcoholic drink in past 12 months. From the moderator, it is concluded that both young adult smokers who drank at least 1 alcoholic drink in past 12 months and for those who didn’t drink at least 1 alcoholic drink higher levels of smoking behavior is associated with higher rates of drinking status.
The project report can be concluded that alcohol consumption and cigarette smoking does not necessarily have direct relationship. This is because there exists an indirect relationship among decencies of these two. Although there are many who consume alcohol while smoking cigarettes not necessarily all alcohol consuming people will smoke cigarettes.


