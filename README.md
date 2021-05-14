# Sales Data Analysis Using Power BI
* In this project, I built a Power BI dashboard that provides real-time sales insights for a company.
It is not a good practice to connect directly with the database as it may cause some issues such as a potential slowdown in the system( instead a data warehouse should be established), but for simplicity, I avoided this part. 

* For data modeling, after I formed the relationships, I obtain a star schema where all the events occur in the sales transaction table.

![modeling](https://user-images.githubusercontent.com/67188835/118291545-67147500-b4e0-11eb-9f56-3e4ed99c899e.PNG)

* After this, I did data cleaning and ETL (Extract, transform, load), particularly focused on currency normalization, handling invalid values such as negative numbers for the sales_amount column, and handling records where some cells are empty. 

![cleaning](https://user-images.githubusercontent.com/67188835/118291986-d8ecbe80-b4e0-11eb-8a45-119fcd9bd99e.PNG)



* the pipeline performed to the transaction table:



![pipeline](https://user-images.githubusercontent.com/67188835/118292350-341eb100-b4e1-11eb-8b04-0fa56287f8e6.PNG)





* The dashboard built to generate sales insights:
![Dashbord](https://user-images.githubusercontent.com/67188835/118292606-79db7980-b4e1-11eb-9624-cb2b6cc06a5e.PNG)

* Then I published the dashboard to the cloud, Using the Microsoft website for the power BI application to access it either using the web or through the Power BI mobile application.
![publish](https://user-images.githubusercontent.com/67188835/118293152-071ece00-b4e2-11eb-9a48-0986c4219ac0.PNG)




