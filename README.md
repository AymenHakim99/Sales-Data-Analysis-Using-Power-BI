# Sales-Data-Analysis-Using-Power-BI
In this project, i built a power BI dashboard that can provide real time sales insights
It is not a good practice to connect directly with the database as it may cause some issues such as potential slowdown in the system( instead a data warehouse should be established), but for simplicity i avoided this part. 

For data modeling, after i formed the relationships, i obtain a star schema where all the events occur in the sales transaction table.
![modeling](https://user-images.githubusercontent.com/67188835/118291545-67147500-b4e0-11eb-9f56-3e4ed99c899e.PNG)
After this, i did data cleaning and ETL (Extract, transform , load), patricularly i focused on currency normalization, handling invalid values such as negative numbers for sales_amount and handling records where some sells are empty. 
![cleaning](https://user-images.githubusercontent.com/67188835/118291986-d8ecbe80-b4e0-11eb-8a45-119fcd9bd99e.PNG)
the pipline performed to transcation table:
![pipeline](https://user-images.githubusercontent.com/67188835/118292350-341eb100-b4e1-11eb-8b04-0fa56287f8e6.PNG)
The dashbord built to generate sales insights:
![Dashbord](https://user-images.githubusercontent.com/67188835/118292606-79db7980-b4e1-11eb-9624-cb2b6cc06a5e.PNG)
Then I published the dashboard to cloud, Using microsoft website for power BI application to access it either using the web or through power BI mobile application.
![publish](https://user-images.githubusercontent.com/67188835/118293152-071ece00-b4e2-11eb-9a48-0986c4219ac0.PNG)




