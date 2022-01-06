
# Hi, I'm Sukumar Sarma! 👋

 
## 🚀 About Me
I'm having an experience of Database Administrator and i love in the field of Data science, Machine learning and Data Analyst and i had done 3 month of internship in Machine Learning and Data Analysis field. I used to have a creative thinking with the real world problem and try to analize it and try to implement it.

  
# Sales Insights Analysis by using MySQL and Tableau BI tool.

Downloaded a real world data in the form of SQL database dump format file where i imported into mysql workbench then perform some Analysis and finds Insights from the data and finally through tableau i connected mysql and loaded the data into tableau and created an interactive dashboard for Revenue analysis and another dashboard for profit analysis.


  
## Authors

- [@SukumarSarma](https://www.github.com/SukumarSarma)

  
## Screenshots
1. Profit Analysis
![Screenshot (248)](https://user-images.githubusercontent.com/86522739/148404772-ce7c04f4-f4bc-4b3d-8c7a-ccd1c995f6a5.png)

2. Revenue Analysis
![Screenshot (250)](https://user-images.githubusercontent.com/86522739/148404798-e9a0e2c0-661a-4669-88da-6aebf5bafd71.png)


  

  

  




  


  
## 🛠 Skills
Python(EDA), Sklearn, Tensorflow, NLP, mySQL, Tableau, Advanced-Excel.
## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sukumar-sarma-271184197/)

  
## Mysql Analysis 

1. Show all customer records

    SELECT * FROM customers;

2. Show total number of customers

    SELECT count(*) FROM customers;

3. Show transactions for Chennai market (market code for chennai is Mark001

    SELECT * FROM transactions where market_code='Mark001';

4. Show distrinct product codes that were sold in chennai

    SELECT distinct product_code FROM transactions where market_code='Mark001';

5. Show transactions where currency is US dollars

    SELECT * from transactions where currency="USD"

6. Show transactions in 2020 join by date table

    SELECT transactions.*, date.* FROM transactions INNER JOIN date ON transactions.order_date=date.date where date.year=2020;

7. Show total revenue in year 2020,

    SELECT SUM(transactions.sales_amount) FROM transactions INNER JOIN date ON transactions.order_date=date.date where date.year=2020 and transactions.currency="INR\r" or transactions.currency="USD\r";

8. Show total revenue in year 2020, January Month,

    SELECT SUM(transactions.sales_amount) FROM transactions INNER JOIN date ON transactions.order_date=date.date where date.year=2020 and and date.month_name="January" and (transactions.currency="INR\r" or transactions.currency="USD\r");

9. Show total revenue in year 2020 in Chennai

    SELECT SUM(transactions.sales_amount) FROM transactions INNER JOIN date ON transactions.order_date=date.date where date.year=2020 and transactions.market_code="Mark001";
