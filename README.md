**How Can a Wellness Technology Company Play It Smart?**

(A Google Data Analytics Professional Certificate Capstone Project)

About

Bellabeat is a wellness company that manufactures health-focused smart devices. Their products include smart bracelets, watches and water bottle that monitors daily activities, calories, sleep, steps taken and water intake where the data are collected through their Bellabeat app.

Products:

Bellabeat app: The Bellabeat app provides users with health data related to their activity, sleep, stress, menstrual cycle, and mindfulness habits. This data can help users better understand their current habits and make healthy decisions. The Bellabeat app connects to their line of smart wellness products.

Leaf: Bellabeat’s classic wellness tracker can be worn as a bracelet, necklace, or clip. The Leaf tracker connects to the Bellabeat app to track activity, sleep, and stress.

Time: This wellness watch combines the timeless look of a classic timepiece with smart technology to track user activity, sleep, and stress. The Time watch connects to the Bellabeat app to provide you with insights into your daily wellness.

Spring: This is a water bottle that tracks daily water intake using smart technology to ensure that you are appropriately hydrated throughout the day. The Spring bottle connects to the Bellabeat app to track your hydration levels.

Bellabeat membership: Bellabeat also offers a subscription-based membership program for users. Membership gives users 24/7 access to fully personalized guidance on nutrition, activity, sleep, health and beauty, and mindfulness based on their lifestyle and goals.

It was founded by a Slovenian sculptor Urška Sršen and Croatian Mathematician Sandro Mur where they would like to analyze data from non-Bellabeat device users to check how consumers use these products. Bellabeat believes that analyzing the data would reveal more opportunities for growth.

Business Task

The task is to analyze data from non-Bellabeat device users and ask to compare with one Bellabeat product to discover insights to help the company’s marketing strategies.

Key Stakeholders

Urška Sršen: Bellabeat’s cofounder and Chief Creative Officer

Sando Mu: Mathematician and Bellabeat’s cofounder

The Bellabeat marketing analytics team: a team of data analysts responsible for collecting, analyzing, and reporting data that helps guide Bellabeat’s marketing strategy.

Data Source

Sršen points a specific data set from Kaggle, FitBit Fitness Tracker Data, where it contains personal fitness tracker from thirty fitbit users. Thirty eligible Fitbit users consented to the submission of personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. It includes information about daily activity, steps, and heart rate that can be used to explore users’ habits.
Data Integrity
1.	This was generated via distributed survey by Amazon Mechanical Turk between March 12 to May 12, 2016 so it means the data is about 7 years ago and might not be relevant and FitBit devices already improved. 
2.	The sample size is too small of about 30 users from FitBit and not covering all smart fitness device users.
3.	Since the data was generated through survey, the participant response might not be accurate.
Process
1.	Data chosen and used on the shared dataset were dailyActivity_merged.csv provides summary of steps and burned calories, sleepDay_merged.csv shares the sleep data and weightLogInfo_merged.csv contains the weight data of the users.
2.	Excel was used to analyze and visualize the data.
3.	The data was examined for the parameters contain, blank cells and data formats.
4.	Data analyzed through calculating statistics per feature, visualize steps and activity per day and weight and sleep distribution.
Analysis
Tables below are the statistics for each feature in the dataset:
 
 
 
As summary, the average weight of users is 72.04 kg and BMI of 25.19 with spent their day mostly in light activities average of 193 mins per day and about 460 mins per day total time in bed.
Average Steps and Distance per Day
 
 
It is every Saturday and Tuesday that the users took most steps and getting reduce when it comes to Thursday and Friday. Most least steps taken is every Sunday.



Average Fairly Active Minutes per Day
 
The distribution of fairly active minutes to each day has minimal difference for each day of the week. But it also shows that it is still Saturday the most active and relevant that it is also the day the most steps are being taken by the users. In the contrary, Sunday has the second most active fairly minutes even with the lowest number of steps. This can show that they are not travelling but do home workout or activities.
Total Active Minutes vs Calories Burned
 
Activity minutes is directly proportional to calories burned. The more active you are, the greater calories are burned.

Insights
•	By examining the dataset, no data inputted in the Logged Distance column. It shows that the users don’t manually log their total distance covered and it suggests that is recommended to have the app that automatically collect their distance log.
•	Since it shows that there is decrease in activity during Thursday and Friday, it is highly recommended to have a feature in the app to notify the users to remain active every day.
•	In weight log info, there are only 8 users actively inputting their weight. It suggests that there should be a feature need to be added in the app that will encourage them to input their weight daily or develop a smart weighing scale that will monitor their weight.










 

