# Bellabeat-Case Study 

### About the company
BellaBeat is a high tech company that specializes in manufacturing health focused smart products for women. In addition to not only inspiring women across the globe, the products available also enable various insights and knowledge geared to help monitor and improve individual health aspects. Since 2013, the company has been able to create several products that have contributed to their successes including the “Time” smart watch, the “Leaf” wellness tracker and the “Spring” smart water bottle. All of these products are able to draw and report health and wellness based data on the users through the BellaBeat app.While mostly being based around on digital marketing and traditional advertising media, the Cofounder and CCO ,Urška Sršen, has set a goal to analyze smart device usage data to not only discover insights in regards to the usage but to also bring forth further Company growth.

### Data Analysis steps to be followed :
Ask
Prepare
Process
Analyze
Share
Act


### Ask
The three questions that need to be answered: ​
What are some trends in smart device usage?
How could these trends apply to BellaBeat customers?
How could these trends help influence BellaBeat marketing strategy?

### Prepare
This dataset does follow the ROCCC (data credibility and bias) analysis expectations as followed:

1. Reliable- Low. There are 31 million users of FitBit however the data presented only consists of about 30 people and the time frame consists of two months. According to Central Limit Theorem, 30 is the smallest of sizes for data to be considered as valid enough so essentially speaking, the information given does meet that criteria but having more options to pull from a wider span of data throughout a more elongated time period would have definitely been more helpful in the overall picture and analysis presented.

2. Original- Low. The dataset used is FitBit Fitness Tracker Data. The dataset is stored in Kaggle and was made available through Mobius.in addition to the data being open source, it was also distributed via survey Amazon Mechanical Turk between 03.12.2016–05.12.2016.

3. Comprehensive- Low. In addition to the limitation of 30 users and the time frame of two months (03.12.2016–05.12.2016) to gather information, there is also no real demographic information present about the 30 users, i.e age,height,etc.
4. Current- Low. The information present is from 2016.
5. Cited- Low. Data acquired by unidentified third party Amazon Mechanical Turk.

### Data used
Monthly .csv files were used for this analysis. The information used within the dataset consists of files the `Fitabase Data 4.12.16–5.12.16.` [here]
https://www.kaggle.com/datasets/arashnic/fitbit?datasetId=1041311

### Key tasks followed

1. Downloaded the data and stored it on my computer to a separate file
2. Downloaded the data for 4.12.16- 5.12.16 time frame
3. Uploaded the data to SQL BigQuery under a table titled “BellaBeat”. Individual datasets uploaded are as follows:
Daily_activity, hourlyCalories_merged, hourlyIntensities_merged, hourlySteps_merged, SleepDay_merged, WeightLogInfo_merged
More tables were merged and created from the original tables to gather further conclusions in my process and analysis phases

This project is also available on Medium website. found [here]
https://medium.com/@kdwardd98/bellabeat-case-study-86c66ed4aed4
