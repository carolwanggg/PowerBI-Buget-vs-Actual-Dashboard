# Buget-vs-Actual-Dashboard

1. Objectives:

Build a dashboard to update the budget vs Actual sales, demonstrate the variance analysis to show the differences betweet actual and budgeted sales by project category.
Presenting this dashboard to senior manager and project manager for them to capture the key infomation.

2. Dataset

I have three different sources of info:
Budget: the info we prepared and discussed together with project manager/budget owner,including phasing of budget(month), project code(ID) and budget amount.

Project Management: the info stored in SAP cloud, including project type(category),project id and projet name.

Sales: sale amount,project id and date.

3. Model

Based on the dataset I have, I recognized the primary key/foreign key in each table and build the relationship model.

To better use the date function, I created also the table date dimension.

![image](https://user-images.githubusercontent.com/129491801/232889878-5fff55c3-aced-49bf-93d1-db917f4f03c6.png)


4.Design

![image](https://user-images.githubusercontent.com/129491801/232890099-7177272e-d02f-4cb5-a2df-3f5d298b2894.png)





