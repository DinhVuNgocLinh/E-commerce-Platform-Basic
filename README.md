# PDM_Project: E-commerce platform
- This project is to build an e-commerce platform basic including building a database and user interface
- Inspired by major e-commerce platforms like shopee, lazada,...
- The project is designed based on Principles of Database Management course

# Members:
- Dinh Thi Thanh Hang - ITDSIU21083
- Dinh Vu Ngoc Linh - ITDSIU21095
- Le Thi Tuyet My - ITDSIU21005
- Trinh Le Bich Hang - ITDSIU21084
- Nguyen Mai Phuong - ITDSIU20105
- Nguyen Huu Thuy	-	ITCSIU22141

# I. Introduction
This project is for a company that has an e-commerce site as a place to buy and sell online for buyers and sellers.
### 1.	Analyst requirement of topic 
#### 1.1.	User (Customers) can: 
-	Sign up/ Sign in on the application.
-	Search for desired products and proceed to the payment page.
-	Manage the shopping cart by viewing, adding, or removing items.
-	Upon successful payment, the estimated product delivery time should be communicated to the user on the order page.
#### 1.2.	User (Sellers) can: 
-	Sign up/ Sign in on the application.
-	Search for desired products and proceed to the payment page.
-	Manage the shopping cart by viewing, adding, or removing items.
-	Add/ Remove products to sell.
-	Process orders.
#### 1.3.	Admin can:
-	Sign up/ Sign in on the application.
-	Manage Users including Customers and Sellers.
-	Manage orders such as approve orders.

### 2.  Goals
- New Account Register
- Auto Generated User ID
- Pays through banking
- Purchase one or many 
- Invoices displayed
# II. Techniques
- IDE for form programming: VSCode, NetBeans, SQL Sever
- Draft the ERD : ERDplus
- Programming languages: Java, SQL
# III. ERD
### Entity & Attributes
![image](https://github.com/DinhVuNgocLinh/PDM-Project/assets/125757646/f4fd1e4e-7a68-4bde-824e-f291c99f2df8)
- Customer has Customer's ID(CID), User's ID(UID), Bank's name(Bname), Bank account(Baccount), Phone number(Phone), Customer account password(CPassword), address of customer(Address)
- Admin has Admin's ID(AID), Admin's name(Aname), admin's email(Email), Admin's Password(Password)
- Seller has Seller's name(Sname), Seller ID(SID), Seller's password(SPassword)
- Product has product's ID, product's name, product's price(Price), product's quantity(Quantity)
- Order has order's ID, the transaction date of  the order(TransactionDate),shipping fee(DeliveryFee), total price including shipping fee and product price(Total)
- OrderItems has the total price of product that not including shipping fee(Subtotal), quantity of product(Quantity), number of different products(ItemNo)
### The complete ERD
![image](https://github.com/DinhVuNgocLinh/PDM-Project/assets/125757646/d1543988-e63b-4279-85d5-4b7df6a41ef7)
# IV. Normalization
The DataBase Diagram is verified on three level:
- 1NF: A relational database that has all attributes in a tuple must have a single value from the domain of that attribute, and the domain of an attribute only include atomic values. Therefore, database is already in the first normal form.
- 2NF: A relational database is in first normal form and every non-key characteristic is completely functionally dependent on the primary key. Therefore, database is already in the second normal form.
- 3NF: A relational database is in 2NF and non-transitive functional dependency of non-prime attributes on any super key. Therefore, database is already in the third normal form.
