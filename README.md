## Examples of Programming Project
### * R
### * Python
### * JMP
### * HTML
## Click the title of each project to access code files in GitHub

# [R: Shiny App-CardiovascularDisease](https://github.com/VinniGuan/CVS-disease-R-Shiny-App-Project)

This R project is for MGMT 590 - Using R for Analytics at Krannert School of Management, Purdue University, developed by team: Jiayu Zhang, Jason Chen, Vinni Guan and Rohit Soans.

We build an app to predict the probability of heart disease in a given individual. This app will be an asset in the hands of sales teams for Health Insurance Companies.  Sales agents can use the app during their sales pitches. On hearing what is the probability that they may get a heart attack, most people are likely to be garner strong interest in Health Insurance products. We found a Cardiovascular dataset on Kaggle with 70,000 observations. We explored and transformed our data and build a model to predict the probability of heart disease.

The shiny link: https://chengyuchen.shinyapps.io/Team3Project/ 

YouTube : https://www.youtube.com/watch?v=bvZbR4dr_as

Shiny Template referenced from: https://mogali.shinyapps.io/attritionanalysis/

#### Business Problem
The UnitedHealthcare Consumer Sentiment Survey showed that only 9% of Americans surveyed “showed an understanding” of four basic health insurance terms — health plan premium, health plan deductible, out-of- pocket maximum and co-insurance. Due to the lack of understanding of Insurance Products, most people are less likely to switch their scheme and end up simply renewing their scheme with their current provider, even though those products maybe mispriced or unsuitable. This is one of the key challenges sales teams of health insurance companies face. Hence new customer acquisition in this industry is both difficult and expensive.

#### Analytics Problem
To calculate the predicted probability of heart disease based on key lifestyle indicators such as Age, Height, Weight, Cholesterol, Systolic blood pressure, Diastolic blood pressure, Glucose, Smoking, Alcohol and Physical activity.

#### Data
The dataset consists of 70,000 records of patient’s data in 12 features, such as age, gender, systolic blood pressure, diastolic blood pressure, and etc. The target class "cardio" equals to 1, when patient has cardiovascular disease, and if it is 0, the patient does not have heart disease.

![](/images/Shiny1.png)
![](/images/Shiny2.png)

#### Methodology Selection
The data was examined for missing values and outliers. We further transformed the data using min-max normalization so that there was no single predictor that dominated our results. We looked for variables that had a strong correlation (>0.85) with each other and dropped one of the said variables. We looked for variables that had very little variation as this would not help us explain he overall variance of our model. We have utilized descriptive analysis to understand the distributions of our predictors (lifestyle indicators) as well as our target variable (whether a person gets heart disease or not). We utilized predictive analytics to predict the probability of a heart disease based on given key lifestyle indicators.

#### Model Building
For our analysis, we used a Logistic Regression model for classification, which provided the greatest accuracy among other models tested. Another benefit of the logistic regression model is its interpretability. Clients would be able to understand the impact of each predictor/lifestyle indicator on their cardiovascular health.

#### Functionality
The sales agent can input the lifestyle indicators such as Age, Height, Weight, Cholesterol, Systolic blood pressure, Diastolic blood pressure, Glucose, Smoking, Alcohol and Physical activity. Based on these parameters, the app will predict the probability of heart disease for that individual. The user can also explore various visuals such as boxplots plotting the numeric variables against the target variable (1-heart disease 0- no heart disease) as well as bar plots of categorical variables. These plots will help the user understand the distribution of these variables within the existing dataset. If we had more time and experience, we would have liked to build an optimization model. By using the probability of heart disease as an objective function, we could guide a given client on how he or she can reduce their chances of heart disease below a certain threshold by reducing certain parameters by a defined amount.

#### GUI Design and Functionality
![](/images/Shiny3.png)

# [Python: Superstore Sales](https://github.com/VinniGuan/Superstore-Sales-Python)
Our data set is about superstore data. It includes data from a superstore with several variables, including product information and information about the customer. The business question we are answering is: Does having a discount on each product category, Technology, Furniture, and Office Supplies, respectively, make a difference in sales for each region? We think this question is important because it can help the superstores decide which regions they should target with more products for a certain category, like more products in Technology, for example. 
To evaluate our question, we are testing each region to see if there is a difference in sales when there is a discount compared to when there is no discount. We’re going to run a regression analysis for discounts, regions, and categories. We will also gather some descriptive statistics and do an ANOVA test to show the difference in sales between the regions. 

Our null hypothesis is that there will be no difference in sales of a certain category if there is a discount for each region. Our alternative hypothesis is that there is a difference in sales of a certain category given a discount for each region. 
There is the possibility of multiple outcomes, two of which are that all the regions might respond positively to discounts, or that all the regions respond negatively to discounts. There is also a chance that some regions will respond positively to discounts and others won’t. There might be an interaction effect between the region and category, which would mean that a discount on Office Supplies in one region might lead to an increase in sales there, but the same would not happen in another region. 
Without any limitations, our ideal experiment would include randomly picking superstores within each region, and implementing discount strategies. We would put a discount on some products and see if sales change, then we would have superstores within each region where there are no discounts to compare against the superstores in the same region with discounts.

We ran a regression analysis and found that discounts do not always uniformly impact sales. To our surprise, discounts actually decreased sales by a significant amount in some cases.  For example, in the Central region sales went down when discounts were offered for Technology and Furniture, but increased for Office Supplies. We are concluding that there is a difference in sales for each region when there is a discount, and are rejecting the null hypothesis. We are also concluding that superstores must be cautious with blanket discounts across all categories and regions, and should target higher discounts in regions where the discount has a positive impact. 
![](/images/Superstore1.png)
![](/images/Superstore2.png)
![](/images/Superstore3.png)
![](/images/Superstore4.png)

# [Python: Bunce Ball & Pi estimation with Monte Carlo Method](https://github.com/VinniGuan/Yingyan-Guan-Python-Projects)
* Bunce Ball
* Pi estimation with Monte Carlo method
![](/images/Python2.png)


# JMP and Python Project
![](/images/JMP.png)


# [HTML Project](https://github.com/VinniGuan/Webpage-of-Christie-and-Chris-s-Cooking-Cabin)
Link:https://vinniguan.github.io/Webpage-of-Christie-and-Chris-s-Cooking-Cabin/
![](/images/HTML1.png)
