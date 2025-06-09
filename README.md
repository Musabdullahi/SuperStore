
# *Project Title: SuperStore Analysis*
In this project, I will be using Microsoft Excel to analyse, visualize and draw insights from the Superstore Dataset publicly obtained from Kaggle (https://www.kaggle.com/datasets/vivek468/superstore-dataset-final). The SuperStore dataset spans a period of Four (4) years.


-----------------------------------

[Problem Statement](#Problem-Statement)

[Data Sourcing](#Data-Sourcing)

[Data Transformation](#Data-Transformation)

[Analysis and Findings](#Analysis-and-Findings)

[Dashboard](#Dashboard)


------------------------------------
## Problem Statement
In this step, the business problem is discussed in the form of Business Objective to guide future business decisions...  
Businesss Objectives:  
* Total Sales?  
* Total Orders?  
* Total number of Customers?  
* Total number of Products?  
* Cities with the highest sales record?  
* States with the highest sales record?  
* The Ship mode in order of use?  
* Sales by Category?   
* Sales by Sub-category?
* Sales by Region? 
* The average delivery days from the date of order to ship date?  
* The most valuable customers?
* Top Selling Products?

------------------------------------
# *Data Sourcing*
This step discusses the raw form of the SuperStore dataset as follows:  
* The Superstore dataset is publicly available on Kaggle (https://www.kaggle.com/datasets/vivek468/superstore-dataset-final).  
* It consists of 21 Columns including: Row ID,	Order ID,	Order Date,	Ship Date,	Ship Mode,	Customer ID,	Customer Name,	Segment,	Country,	City,	State,	Postal Code,	Region,	Product ID,	Category,	Sub-Category,	Product Name,	Sales,	Quantity,	Discount &	Profit.
* It consists of 9,994 rows and 1 row as header-row.

------------------------------------
# *Data Transformation*
Power Query from Excel was utilized to clean and transform the data to address:  
* Duplicate values: There was no duplicate row found.
* Missing values or errors: There was none found.
* Inconsistency in datatype: Columns were formatted to appropriate datatype.
* Inconsistency in date formats: Date columns were converted from text to date.
* Removal of unnecessary data: 3 unnecsssary columns were removed; Row ID column was removed since it is the same as Excel column label. Country column was also removed since this data is based in only one country 'United States'. Postal Code column was also removed since it isn't useful for this analysis.

-------------------------------------

# *Analysis and Findings*  
![image](https://github.com/Musabdullahi/DA-Stuffs/assets/99256919/84775fde-9640-4a74-aa4c-79f7adb3207c)
1. Total Sales?  
    There is a total of $2,297,201 sales carried out between 2014 and 2017. In the year 2014, there was a total of $484,247 sales; 2015 has $470,533 sales; while 2016 has $609,206           sales; and 2017 has $733,215 sales.
    Monthly sales deduction shows that sales are usually high towards the end of the year around Q3 and Q4.
2. Total Orders?  
    A total of 9,994 orders was placed between the year 2014 and 2017. While 2014, 2015, 2016, 2017 each has 1,993, 2102, 2,587, 3,312 orders respectively.
3. Total number of Customers?  
    There was a unique count of 793 customers.
4. Total number of Products?  
    There was a total number of 1,862 unique products.  
5. Cities with the highest sales record?  
    In this analysis, New York City has emerged as the leading market, boasting an impressive sales figure of about $256,400 transactions, presenting a significant opportunity for           targeted marketing potential.
6. States with the highest sales record?  
    California has emerged as the top-selling state, recording an impressive $458,000 transactions. This data highlights a valuable chance for focused marketing in the state to tap into     its potential for boosted sales.
7. The Ship mode in order of use?  
    ![image](https://github.com/Musabdullahi/DA-Stuffs/assets/99256919/45930b2c-b360-41ab-b59d-fb63efe4924a)  
   The order of ship mode usage is as follows: 'Standard class' takes the lead due to its affordability, followed by 'Second class' and 'First class,' with 'Same day' being the least       utilized mode.
8. Sales by Category?  
    Among the three categories, 'Technology' emerges as the most patronized, achieving an impressive $836,200 in sales and approximately $145,500 in profit. Followed by 'Furniture' with     approximately $742,000 in sales with a mere profit of $18,500, while 'Office supplies' has about $719,000 in sales with a profit of $122,500 surpassing that of 'Furniture'. Out of       the 3, it is clear that Technology and Office Supplies are the best in terms of profits. 
9. Sales by Sub-category?  
    Out of the 17 subcategories, the biggest saless comes from Phones, Chairs, Storage, Tables and Binders.
10. Sales by Region?  
    ![image](https://github.com/Musabdullahi/DA-Stuffs/assets/99256919/31339af8-158b-4dec-8ab6-0fa45a4d1d13)  
    The West region stands out as a robust force in sales, boasting about $725,500 transactions with about $108,400 profit, Followed by East, Central and South.
11. The average delivery days from the date of order to ship date?  
    ![image](https://github.com/Musabdullahi/DA-Stuffs/assets/99256919/dfdce797-baf7-487e-91ee-fbea29a0eb95)  
    The delivery time frame has consistently ranged from a minimum of same-day delivery to a maximum of 7 days, with an average delivery period of approximately 4 days.
12. The most valuable customers?  
    ![image](https://github.com/Musabdullahi/DA-Stuffs/assets/99256919/19d0e24a-bb8a-4e05-8d81-7711c07f89d3)  
    Prioritizing our loyal customers is paramount, aiming to enhance the value we offer them.  
    It can be deduced that, Sean Miller is the most valuable customer in terms of sales, generating $25,000 in sales. However, it’s important to note that Sean Miller has a negative         profit of -$2,000. Tamara Chand is the second highest in sales with $19,000 and has a profit of $9,000, making him/her potentially more valuable in terms of profitability.
13. Top Selling Products?  
    ![image](https://github.com/Musabdullahi/DA-Stuffs/assets/99256919/cb52899a-c459-40e4-b2c0-91da3959fd9f)  
    Based on the top 10 products in terms of sales: The leading product in terms of sales is the Canon imageCLASS 2200 Advanced Copier, with sales reaching $61.6K and a commendable profit of $25.2K. The Fellowes PB500 Electric Punch Plastic Comb Binding Machine follows with sales of $27.5K, yet it has a comparatively lower profit margin, resulting in profits of $7.8K. Interestingly, the Cisco TelePresence System EX90 Videoconferencing Unit, despite generating sales of $22.6K, shows no profit and indicates a loss with a red bar at -$1.8K. The HON 94000 Series Round Tables exhibit moderate sales at $21.9K, yielding profits of $2.2K. Another noteworthy product is the GBG Electric Binding System, which, despite making sales worth $19K, registers zero profit.

------------------------------------
## Dashboard
![image](https://github.com/user-attachments/assets/2eac4387-e2ff-4085-9880-670347e360ce)


