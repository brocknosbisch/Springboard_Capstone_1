# Springboard_Capstone_1

## Springboard Data Science Certification - Capstone 1 Project
Probability of Defaulting
By Brock Nosbisch 

What is the problem you want to solve? 
The problem I am trying to solve is to predict the probability of someone defaulting on payment (>90 days late). I am going to emphasize on several algorithms and review the performance and strengths and weaknesses of each.

Who is your client and why do they care about this problem? In other words, what will your client do or decide based on your analysis that they wouldn’t have done otherwise? 
My client is any bank, credit union, etc. that gives loans to individuals. Predicting whether someone will default on their loan is key to the company deciding on whether to give that loan or to raise the interest rate. 
This model will take an certain inputs (TBD) and output the probability that the person will be 90+ days late making a payment in the next 1 year? 2 years? 

What data are you using? How will you acquire the data? 
The data used for this project comes from an old Kaggle competition. I will be manually downloading the file, extract the files, and then load, parse, and clean the data in python. There are a total of 2 datasets that I will be using to train and test the model. 

Datasets: 
      Credit Scoring: 
            ID 
            Serious Deliquent in 2 Years Flag 
            Utilization of Unsecured Lines 
            Number of Times Past Due (30-59 Days) 
            Debt Ratio 
            Monthly Income 
            Number of Open Loans 
            Number of Times Past Due (90+ Days) 
            Number of Real Estate Loans or Lines 
            Number of Times Past Due (60-89 Days) 
            Number of Dependents 
      Site: https://www.kaggle.com/c/GiveMeSomeCredit 
      Files: cs-training.csv, cs-test.csv, sampleEntry.csv

Briefly outline how you’ll solve this problem. Your approach may change later, but this is a good first step to get you thinking about a method and solution. 
I will first download all file and extract the zip file. I will then do Data Wrangling, EDA, and test different machine learning algorithms to calculate the probability of each person being 90+ Days Late in the next 1 year and 2 years.

What are your deliverables? Typically, this includes code, a paper, or a slide deck. 
My deliverables will be a jupyter notebook and slide deck that will be published to my github account. I will include all my findings and all documented python code.
