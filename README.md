# PABLO STORES 2019 SALES ANALYSIS

## Table of Contents
- [Problem Statement](#problem-statement)
- [Objectives](#objectives)
- [The Data](#the-data)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Tools](#tools)
- [Insights](#insights)
- [Dashboard](#dashboard)
- [Recommendations](#recommendations) 


### Problem Statement
Pablo Stores faces challenges in its sales data management which has hindered decision making and limited the ability to capitalise on business opportunities. Some of the key issues as communicated by the CEO, Pablo include:

- Lack of an integrated view of best and worst-selling products impedes inventory optimization and targeted marketing.
- Inadequate insights into city-wise sales prevents them from tailoring strategies to regional market variation.
- Absence of dynamic daily and monthly sales trends hinders their ability to respond to market changes and capitalise on emerging opportunities.
- Store outlets rely on manual and time-consuming data compilation processes, resulting in inefficiencies and errors that impedes strategic decision-making and operational efficiency.
- Accessibility restrictions within the stores constrain the sharing of sales data, inhibiting collaboration and the development of a data-driven organizational culture.

### Objectives
This project aims to tackle these challenges by developing a user-friendly Sales Dashboard specifically designed for Pablo Stores, utilizing advanced data analytics and visualization tools. The proposed dashboard will offer insights into product performance, geographic sales variations, and timely trends for the year 2019. This will enable informed decision-making and drive sustainable growth for Pablo Stores. The entire project will be executed using Power BI.

### The Data
The dataset for this project was provided by [Meriskill](https://www.linkedin.com/company/meriskill/). It contains 185,950 rows and 12 columns with the following information:

- An unlabelled column numbered from 0 (Index)
- Order ID
- Product
- Quantity ordered
- Price each
- Order date
- Purchase address
- Day
- Month
- Sales
- City
- Hour

![Screenshot (417)](https://github.com/DanielOladipupo/Sales-Analysis-Project/assets/155446588/dac0ec9b-13f2-4c01-9fc1-dbd84727d8df)

### Data Cleaning and Preparation
I downloaded and imported the data into power bi, I proceeded to clean and prepare it for analysis. Firstly, I created a new version of my data in case I needed to drop some columns or make other changes. In the newly created worksheet, the following steps were taken:
Duplicate check: I made sure to confirm that all the rows in the dataset were unique.
- **Missing values:** I did a thorough check for blanks in all the columns. There were no missing values.
Data types: All columns were in the General format which is fine for what I need to do.
- **Outliers:** I did a check for outliers, resulting in a skewed distribution but that was expected. Also, most of the orders were for a single quantity of a product which is also fine.
- **2020 transactions:** Even though it was a 2019 dataset, the transactions recorded on the first day of 2020 were included. These were deleted to maintain the integrity of the dataset for the specified year.
- **Categorical variables:** I examined the categorical variables for errors in spellings and other unexpected values. Again, everything was fine.
- **Column removal:** Even though I wouldn't need some columns (like the purchase address column) for my current task, I decided to keep them for potential future analysis.

### Tools
- Power Query
- Power BI
  
### Data Exploration and Analysis
With the data now clean and prepared, it was time for exploration and analysis. Pablo wanted to know which products were doing well so, using a pivot table, I extracted the total quantity of products ordered/sold and filtered to get the top 5.
Secondly, I looked at the geographical data. Using the same process as above, I extracted the total sales per city to know which city influenced sales the most and which didn't do too well.
i created dynamic dashboard in order to get more specific information, therefore, I created three slicers:
- A product slicer to get city sales, total monthly sales, and average monthly sales specific to each product.
- A city slicer to get the quantity of products sold, total monthly sales, and average monthly sales specific to each city.
- A month slicer to get the monthly distribution of quantity of products sold and city sales.

### Insights
- **Top 5 Best Selling Products:** AAA Batteries, AA batteries, USB-C Charging Cable, Lightning Charging Cable, and Wired Headphones emerged as the top 5 best-selling products, with AAA Batteries leading at 31,000 units sold.
  ![Screenshot (424)](https://github.com/DanielOladipupo/Sales-Analysis-Project/assets/155446588/ba67d1f1-51ac-4949-9f9b-2043e4719f2a)

- **Sales by Month:** December recorded the highest sales with over 4.6 million dollars, while January had the lowest sales with less than 2 million dollars.
  
  ![Screenshot (425)](https://github.com/DanielOladipupo/Sales-Analysis-Project/assets/155446588/b0afc570-3177-46dd-b5e9-a6ed6f7ae0cd)

- **Average Sales by Month:** May and June recorded the highest sales with the total of 190 dollars, while September had the lowest sale of 180 dollars.
  
  ![Screenshot (429)](https://github.com/DanielOladipupo/Sales-Analysis-Project/assets/155446588/f9bd5ddd-8e69-4f2c-b0b0-4ba46418c672)

- **Top 5 Product by Sales Count:** Macbook Pro Laptop ranked the highest with the total of 8M, while 27in 4k Gaming Monitor was the least with the total of 2M
  
  ![Screenshot (430)](https://github.com/DanielOladipupo/Sales-Analysis-Project/assets/155446588/89961bff-289c-4bd3-a6ff-71f0aefdd3d3)

- **Top 5 Cities by Sales:** San Francisco led in sales by 8,260, followed by Los Angeles with 5452, while Austin recorded the least by 1,819.

  ![Screenshot (432)](https://github.com/DanielOladipupo/Sales-Analysis-Project/assets/155446588/d9f0016a-2f8b-4ed3-b5e1-593518e56233)

### Dashboard 
  ![Screenshot (433)](https://github.com/DanielOladipupo/Sales-Analysis-Project/assets/155446588/344e7118-34f6-475e-a191-868c3ef12ad4)

### Recommendations 
After a thorough analysis of the sales data, the following recommendations are proposed to improve the performance and growth of Pablo Stores:
- Pablo Stores must capitalize on the success of the top-selling products and implement targeted marketing strategies. They can use customer insights to tailor promotions and advertising, maximizing visibility and sales for these high-performing items.
- They should implement strategies to enhance customer engagement, such as loyalty programs, personalized recommendations, or exclusive offers. Building a stronger connection with customers can lead to repeat business and positive word-of-mouth marketing.
- Opportunities for diversification by identifying potential substitutes or complementary products should be explored. Introducing new items that align with customer preferences can contribute to increased sales and provide a more expansive product offering.
- The online presence of Pablo Stores should be expanded by investing in e-commerce capabilities. This will not only broaden the customer reach but also provide valuable data for online sales trends and customer behaviour.










