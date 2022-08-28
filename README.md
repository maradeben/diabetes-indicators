# (PISA Data Exploration)
## by Ebenezer Maradesa


## Dataset

The Diabetes Health Indicators Dataset was gotten from, and can be found [here on Kaggle](https://kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset). It was derived/engineered by Alex Teboul from a series of datasets of the Behavioral Risk Factor Surveillance System (BRFSS). Specifically, `the diabetes_012_health_indicators_BRFSS2015.csv` is used here.

It contains 250,000+ records and 22 variables/columns, 21 features and 1 target, and the target is Diabetes classification/diagnosis which could be 0 (non-diabetic), 1 (prediabetic), or 2 (diabetic). 


## Summary of Findings

Several variables have been taen from the dataset through several variations of visualizations in this Exploratory Visualization process, including Univariate, Bivariate and Multivariate Visualizations.

There were several insights gathered in the process, and they are summarized thus:

While more females seem to have higher BMI's generally, an age-wise comparison shows that males have higher BMI's than females of the same age group. Also, BMI distribution for both sexes is unimodal, tapering towards each end. Another interesting trend in BMI distribution is that most BMI's fall into the Overweight and Obese categories, and fewer people than these actually have Healthy Weight.

On relating with Diabetes, it was found that underweight persons have no risk of Diabetes. The general trend of BMI with Diabetes is that the risk of Diabetes increases with increasing BMI, with higher BMI means for prediabetes and diabetes respectively. This pattern holds true across age groups and across both sexes.

On age, it is noteworthy that the risk for Diabetes also increases with Age. The mean BMI for diabetics in an age group increased initially till about the middle-ages, then increasingly decreased with age. Simply put, the BMI for an average young person with no risk of diabetes is a risk for diabetes for an older person.

There was only a slight difference when comparing Diabetes between males and females, but the trend leaned toward more Diabetes recorded in males.

There were interesting findings with the other variables too. For instance, I found out that Heavy Alcohol drinkers have lower BMI's, and this seems to also suggest a lower risk for diabetes, so it was not explored further. Also, it was strange that more people who had health coverage reported not being able to afford healthcare at least once in the past year.


## Key Insights for Presentation

The major takeaway from the exploration is the ultimate relationship of all four variables of interest.
For non-diabetics, the BMI of the males is consistently higher than that of the females.
For prediabetics, average BMI is about the same, except for a spike in BMI's of females at about age category 3. This is the category for ages 25-29, which is around the childbearing age, suggesting some relationship to Gestational Diabetes.
In the diabetic plot column, the trend is reversed compared with non-diabetic. Here, diabetic women have consistently higher BMI's than diabetic men.

Summarily, it can be safely inferred that the risk of Diabetes increases with increasing Age and BMI.