# supershop

Introduction: A super shop is a large retailer who stocks and sells a wide variety of merchandise including groceries, clothing and general supplies, or a large store that sells a massive quantity of goods in one product line such as electronics or shoes. Super shops are very large supermarkets or shops selling household goods and equipment. Super shops are usually built outside city centers away from other shops. The best example of a superstore is Wal-Mart. A superstore is also referred to as a super center or megastore. Super Shop is a special market with different specialty. Super shop is located in special area for the class of people in Bangladesh. The products are categories in the super shop. The products are allocated with a highly qualified way. “Super Shop Management System” is a management system to provide service facility to the owner and also to the customers. Super Shop management system helps to create invoices, product category, purchase orders, receiving lists, payment receipts and can print bar labels. A Super shop management system configured to your warehouse, retail or product line will help to create revenue for a company. The Super shop Management System will control operating costs and provide better understanding.

Features:

Customer buys product, local store sells product, and therefore transaction happens.
Customer can be approved for membership.
Customer can search item for information and reliability.
Warehouse has product inventory.
Warehouse can distribute products to local store.
There is monthly, weekly and daily sales report.
Customer can search in different stores for product availability.
Customer can see top selling products of specific category
Database Link : We have established connections among the three laptops. One of them is considered as the server or host and the rest of the two are considered as sites. The tables of the project are run in the sites and then accessed via a site link connection. We are using one host and two sites for our project.

Database Tables (Global Schema):

Branch (branch_ID, Location, Phone)
Category (C_ID, C_Name)
Membership (M_ID, P_Range_From, P_Range_To, Discount_Rate, Type)
Product (P_ID, Selling_Price, P_Name, C_ID)
Customer (C_ID, C_Name, Email, M_ID)
Transaction (T_ID, Cust_ID, Branch_ID, Total_Price, T_Date)
goes_in (P_ID, T_ID, Quantity)
occurs_in (Branch_ID, T_ID)
proceed (T_ID,C_ID)
stores_in (P_ID, P_Quantity, Branch_ID)
warehouse (S_ID, S_Date, P_ID, P_Quantity, Buying_Price)
Sales (Serial_no, Month, Sales)
Fragmentation Schema:

Branch1 = PJbranch_ID,Location,PhoneSLLocation=’Dhanmondi’Branch
Branch2 = PJbranch_ID,Location,PhoneSLLocation=’Mohammadpur’Branch
Functions and Procedures: We have created two functions and three procedures for our project.The functionality of the functions and procedures are given below:

Functions:

Function1: Displays the names of the customers from the given site.
Function2: Displays the total number of customers from the both of the sites.
Procedures:

Procedure1: Checks and displays the membership of the customers with join operation.
Procedure2: Displays the sales report.
Procedure3: Distributes the warehouse.
Procedure4: prediction of a sales outcome for any month using machine learning.
Procedure5: Top selling information.
Procedure6: Search product.
Procedure7: Check membership with semi join.
Machine Learning Technique: In a procedure , we used a machine learning technique called linear regression to predict the sales outcome for any month. Our dataset includes 2 columns (Month = x, Sales = y). So for month, x = 1, 2…12 we inserted sales value y. Then we calculated values by using the regression formula for a and b. Then for any month, x = 1 = January we calculated y = a + bx and found the predicted score.

Conclusion: Distributing the Super Shop database can lead to a very good output in the Super Shop Management System. The owner can access different information from the sites via server or host and look over the whole database management system from one server.
