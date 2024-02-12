Telecom Customer Potential Churn Prediction
========================================================

## App Introduction

This Shiny app was created to help telecom companies to predict which current existing customers have the potential of churning by using detailed account information of those customers. Through predicting the potential churn, the telecom company may be able to act in advance to try to keep those customers by providing some attractive service promotions or some sort of discounts, this is indeed necessary and essential for business growth in this much competitive and aggressive market. 

The predicton model was trained on the dataset provided by http://www.sgi.com/tech/mlc/db/, all the data are based on claims similar to real world. The accuracy rate of the model prediction is 95.7%, 95% CI from 94.8% to 96.8%, and sensitivity is 99.5%, based on 1667 lines of real testing data also provided by the same site, so the model did a really nice job. 

## Run the App

The App on the site is ready to use, the [snapshot](Selection_002.png) shown is how the App looks like. The left side panel is for users to input the customer account and usage information, through this information the App can predict whether or not the customers have the potential to churn. 

**Users have two options to input the account information:**

1. Upload .csv file: Comes with this App there is an example file named exampleAccounts.csv which could be used as a templet to make your customer account usage file, also the examples in that file could be used to test if the App works; 

2. Manually enter the account information: Under the uploading section sits the manually input section which could be used to manually add account information one by one to do the prediction job, fill in the fields as the page instructed, hit the button "Submit" each time you finished entering one account.

*Explanation of each account field is shown at the bottom.*

**To predict the churn accounts**

Button *Predict*: After either uploading account file or manually entering the data, the accounts information will be displayed right away on the right main panel of the page, by clicking on button "Predict", the App will spit out a list of potentially churn accounts which will be right under the full account list.

Button *Download*: This button is a handy feature which is used to download the predicted churn list to your local drived to be saved as a .csv file.
