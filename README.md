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

## Tables 

number of users and logs 
![# of users and logs ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/2e14843e-ce2b-4f30-ae19-b38f578c46a9)
min max avg active min levels 
![active min level](https://github.com/kdward98/bellabeat-SQL/assets/169955848/5aa51225-371f-48db-aaff-3a97e9ddf7bc)
calories 
![calories ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/6992c35f-3c93-4fe8-9c2b-8c3737c3d0e8)
avg total steps per user type
![avg total steps:user type](https://github.com/kdward98/bellabeat-SQL/assets/169955848/7c8b0568-e7e2-4104-8e73-b8ed8119746a)
total time in bed/ mins asleep
![sleep:total time in bed](https://github.com/kdward98/bellabeat-SQL/assets/169955848/ed6c4ca8-ba7e-410c-8ace-5701de54fc65)
total steps per hour
![total steps per hour ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/937e685e-5842-4afb-8066-b046ba25203d)
min,max and avg distance, calories,total steps 
![total steps:distance ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/58d4169e-c443-4265-b2e5-891f7c05aef5)
avg weight/bmi
![avg weight:bmi](https://github.com/kdward98/bellabeat-SQL/assets/169955848/a8b78d46-1fee-4b6c-8ca9-c77693745a41)
logs for avg weight/bmi
![weight logs](https://github.com/kdward98/bellabeat-SQL/assets/169955848/34835b6a-d46d-4541-b787-94aff9ac8f75)
sum of distance per weekday 
![day of week:sum distance ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/61b3042c-cd56-4f93-9e7c-44cb909829e8)
avg total steps per hour 
![average total steps per hour ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/8f91c40a-40e1-44a4-8c5b-81bd3d35d0f6)
avg calories per day 
![avg calories per day ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/322e579d-4a91-4d92-9283-f6a5d60ab5af)
time in bed/mins asleep per weekday 
![min asleep:time in bed per weekday](https://github.com/kdward98/bellabeat-SQL/assets/169955848/0d37b830-7056-40c8-8aa0-a5d24f32057a)
sleep time per id 
![sleeptime per id ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/8131f56c-4bc1-4569-a4d9-9f737220fd53)
total avg steps per weekday 
![total avg steps per weekday](https://github.com/kdward98/bellabeat-SQL/assets/169955848/80d7483b-b481-428e-aef0-650977162d11)
active mins per week 
![active mins per week](https://github.com/kdward98/bellabeat-SQL/assets/169955848/b6f91b5e-d662-4b21-b9a1-e86b058a1a79)
active mins per weekday 
![active mins per weekday](https://github.com/kdward98/bellabeat-SQL/assets/169955848/25acbe19-7b7d-47df-ac68-4e0f2e04ab5c)
avg mins per id 
![avg min per id ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/4e2dd816-23fc-4ad0-8259-5d4f695b5279)

## Visualizations 

![active mins ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/9ba26333-8933-409f-996c-d8696cfdcfed)

![avg step total ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/fe1e9f50-58b3-426f-baa8-6d8e21fd5166)

![avg step per activity hour ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/67d16aa9-b03e-424c-b4f2-d7089cd8580e)

![calories:fairly active mins ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/0fd60250-0ac1-4c5e-a682-0b7f68f0f5b5)

![calories:light active mins ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/abb0d498-305e-4747-b8df-853c14a91b36)

![calories :very active mins ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/6b553da2-f48a-44bb-905a-8a347bb99857)

![weight logs per id ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/ac9f8f95-18bc-4b66-b599-20f10a628e3a)

![percentage of user types ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/508250a5-c9f4-411d-aa9e-54b8ed83609c)

![avg mins asleep per weekday ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/0cddbde9-a471-4689-8d19-580f8e696116)

![active mins per weekday ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/e1250067-e6b9-4c71-ac28-34ef934ccfc3)

![sleep and nonsleep bedtime ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/8c140d53-c4fd-4ac6-b3c2-36de22d993eb)

![step total per activity hour ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/d262fc99-fac4-41a9-ac0e-3a1fb499f2b7)

![total avg steps per day of week ](https://github.com/kdward98/bellabeat-SQL/assets/169955848/d339e770-98f3-4992-82f2-147ca0e1513c)












