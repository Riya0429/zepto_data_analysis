#Zepto's dataset is used to extract key insight for Data analysis

Dataset used from Kaggle platform

##why used zepto?
Zepto is India’s fastest-growing quick-commerce platform.      
As e-commerce platforms became the emerging and trending way of dealing with purchases.
The objective is to understand how these platforms manage, operates and function to meet the consumer demands.

###The project answers the following major business questions arise during data analysis 

Q1. Find the top 10 best-value products based on the discount percentage
Q2. What are the Products with High MRP but Out of Stock
Q3. Calculate Estimated Revenue for each category
Q4. Find all products where MRP is greater than ₹500 and discount is less than 10%.
Q5. Identify the top 5 categories offering the highest average discount percentage.
Q6. Find the price per gram for products above 100g and sort by best value.
Q7. Group the products into categories like Low, Medium, Bulk.
Q8. What is the Total Inventory Weight Per Category  

####Example-
Extracted the distinct categories of products exist in zepto. 

![image alt](https://github.com/Riya0429/zepto_data_analysis/blob/94bc3cb4268fe714e836c9738f4035f42196d5be/Category%20wise%20Dataset.png) 

Used the following syntax- 
select distinct category, mrp, availableQuantity, discountedSellingPrice,
weightInGms, outOfStock, quantity from zepto
order by mrp desc;

Here "Distinct" operator is used to retrieve only unique values.
And "Order BY" operator to organize data in the descending format based on the column 'MRP' of products within categories.

