# BG FASHION STORE: SALES ANALYSIS
This is an analysis to better drive the decision making for BG fashion store.
![Store](https://github.com/Kioyar/BG-FASHION-STORE-ANALYSIS/assets/106233340/63d39cf3-26a1-40fb-9598-369c7943a913)

### INTRODUCTION
I came across this dataset in an online learning class section and was amazed at how rich the data is. I have been eagerly looking forward to getting my hands dirty with a very comprehensive dataset to practice my skills in data cleaning, analysis, modeling, and visualization.

#### PowerBi Concepts Applied
Data Modelling: Star Schema

### PROBLEM STATEMENT
- What is the total sales made in the year?
- Which city made most sales and which city made less sales?
- Total annual sales per selling area.
- Demostrate a critical awareness of the impact of data.
- Any other relevant data-driven insights into our sales.

### DATA SOURCING.
The data was gotten from an online learning platform (Utiva). I then downloaded the csv files and extracted it into **PowerBi** for **cleaning, analysis and visualization.**
It contains 3 sheets/Tables.
- Competitive Territory with 11 rows and 2 columns.
- Names with 104 rows and 3 columns.
- Shop territory with 104 rows and 3 columns.

### DATA TRANSFORMATION / CLEANING.
The data was efficiently cleaned and transformed with the power query editor of PowerBi.

### Data Modelling

Powerbi automatically connected related tables resulting in a star schema model. 'The competitive territory' and 'Shop territory' tables are connected to the 'Name' table via the common column 'Territory and ShopID' respectively.
The name table is the fact table of the model while the remaining two are the dimension tables.
![Data_model](https://github.com/Kioyar/BG-FASHION-STORE-ANALYSIS/assets/106233340/6494cb16-e4fb-44b3-ad68-406419f80e9e)

### DATA ANALYSIS AND VISUALS: ![Data_visual](https://github.com/Kioyar/BG-FASHION-STORE-ANALYSIS/assets/106233340/6f8c8caf-e87d-4f7e-bb1f-5b6ae2550a23)
From the dashboard, it is observed that.
1. The total sales per selling Area is **$5.31k.**
2. Total annual sales is **$112.56M.**
3. Sales is highest in the city of **LAUREL** with **$2.4M** while **CHAMBERSBURG** made the least number of sales with **$0.23M.**

While the focus of the analysis was carried out the dashboard below gives room for furthur questions and answers to obtained.![Question](https://github.com/Kioyar/BG-FASHION-STORE-ANALYSIS/assets/106233340/58fb110b-060f-4f43-8278-f16b83e4805b)
## CONCLUSION & RECOMMENDATION
- The total annual sales of **$112.56M** was made.
- A whooping amount of **$2.4M** was made in **LAUREL**, making it the city the highest sales.
- By chains, **Fashion Direct** made more sales with **$48.02M** which is more than 60% sales of the total sales by chain.
- **OH** is the territory with the highest sales of **$16.5M**

### RECOMMENDATION
1. More attention should be on **LAUREL**, the city with the highest number with $2.4M on sales. With this, as much as possible, there shouldn't be a bridge in customer service, service level agreement (SLA) for a better customer satisfaction.
2. More awareness. adequate follow up on customers and an excellent customer service should be adopted in **Chambersburg**, the city with the lowest sales of $0.23M.

![Thank you](https://github.com/Kioyar/BG-FASHION-STORE-ANALYSIS/assets/106233340/fbe8bed9-0d56-4768-8b9c-ad48ef6f8517)
**THANK YOU**
