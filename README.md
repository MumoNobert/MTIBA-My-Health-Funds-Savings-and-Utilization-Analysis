# A deep dive  into utilization and saving behavior of MTIBA's My Health Funds wallet
This project gives insights by analyzing data from the MTIBA platform on claims and savings in Kenya. It looks into claims utilization patterns for My Health Funds program (a health savings wallet) such as typical claim amount, total claim amount dispersed over time as well as distribution of claims over different counties. It also looks into savings patterns such as savings across different days of the week, savings across gender  and savings by family size.

## Table of Contents
1. [Project Motivation](#motivation)
2. [Installations](#installations)
3. [File Overview](#overview)
4. [Key Results](#results)
5. [Acknowledgements](#acknowledgements)

## <a id="motivation"/> Project Motivation
The motivation of this project was to use Python to get insights into Utilizations and Savings  of members with the My Health Funds wallet. The end result was to have data insights that will communicated back to buisness stakeholders in MTIBA to use for data driven decision making  as well as understand the program better. In particular I wanted to practise using the CRISP-DM process in getting the insights by :
- Identifying and getting the relevant datasets needed from the MTIBA platform
- Gathering necessary business understanding of the My Health Funds program
- Understanding the data on claims and savings
- Preprocessing the data by doing cleaning and data enrichment
- Performing relevant analysis
- Communicating the insights with much simplicity as possible

The business questions that the project seeks to answe are :
- Savings Questions
    1. What is the typical saving amount for a My Health Fund member ?
    2. What is the typical remittance amount to a My Health Funds member
    3. How have savings been doing throughout the years and months ?
    4. How does saving frequency and amount compare across different days of the week ?
    5. How are savings influenced by the size of the family ?
    6. How are savings distributed by gender?
    7. Which age bracket has the higest savings into their wallet ?

- Claims Questions
    1. What is the typical claim amount from My Health Funds
    2. How are claims amounts distributed ? Which is the most frequent claim bucket?
    3. How much cumulative claim amount has been paid out to healthcare providers from My Health Funds wallets?
    4. Which healthcare provider regions are most popular with My Health Funds ?

## <a id="installations"/> Installations
This project mainly utilized Jupyter Notebook using Python; In addition the  following libraties were used :
- pandas
- numpy
- mathplotlib
- seaborn

##  <a id="overview"/> File Overview
Files included in the repository
- My Health Funds Utilization and Savings Insights : Jupyter Notebook with the analysis code
- .png files with plots from the various analysis

Files not included in the repository
- project_udacity_blogspot_claims : claims data were each row is a claim created under the My Health Funds wallet
- project_udacity_blogspot_savings : savings and remittance data where each row is a transaction recorded when someone made a saving to their wallet or a saving remitted to a member's wallet


## <a id="results"/> Key Results
Link to the Insights from this poject : [Medium](https://medium.com/carepay-stories/saving-for-healthcare-a-deep-dive-into-m-tibas-savings-wallet-e0699dee7feb).

## <a id="acknowledgements"/> Licenses and acknowledgements
All the data used for the analysis was from the MTIBA platform owned by CarePay, the company I work for currently. The datasets' cutoff date was 30th September 2020.