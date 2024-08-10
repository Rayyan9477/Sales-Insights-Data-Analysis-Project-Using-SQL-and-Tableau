### Sales Insights Data Analysis Project Using SQL and Tableau

#### Summary
This project involves analyzing sales data to derive meaningful insights using SQL and visualizing the results with Tableau. The data is stored in a MySQL database, and various SQL queries are used to extract and analyze the information. The project aims to provide a comprehensive understanding of customer transactions, market-specific sales, and product performance.

#### Techniques Used
- **MySQL Database Setup**: Instructions to set up MySQL on your local machine and import the provided database dump.
- **SQL Queries**: Various SQL queries to analyze customer records, transaction details, market-specific data, and currency-specific transactions.
- **Tableau Visualizations**: Creating interactive dashboards and visualizations to present the analyzed data effectively.

#### Instructions to Setup MySQL on Your Local Computer
1. Follow the steps in [this video](https://www.youtube.com/watch?v=WuBcTJnIuzo) to install MySQL on your local computer.
2. Download the [`db_dump.sql`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fr%3A%2Fproject%2Fpower%20bi%2F2_SalesInsightsTableau%2Fdb_dump.sql%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "r:\project\power bi\2_SalesInsightsTableau\db_dump.sql") file and import it as per the instructions given in the tutorial video.

#### Data Analysis Using SQL
1. **Show all customer records**
    ```sql
    SELECT * FROM customers;
    ```

2. **Show total number of customers**
    ```sql
    SELECT count(*) FROM customers;
    ```

3. **Show transactions for Chennai market (market code for Chennai is Mark001)**
    ```sql
    SELECT * FROM transactions WHERE market_code='Mark001';
    ```

4. **Show distinct product codes that were sold in Chennai**
    ```sql
    SELECT DISTINCT product_code FROM transactions WHERE market_code='Mark001';
    ```

5. **Show transactions where currency is US dollars**
    ```sql
    SELECT * FROM transactions WHERE currency='USD';
    ```

#### Tableau Visualizations
- Import the analyzed data into Tableau.
- Create interactive dashboards to visualize customer transactions, market-specific sales, and product performance.

#### Contact Information
- **LinkedIn**: [Rayyan Ahmed](https://www.linkedin.com/in/rayyan-ahmed9477/)
- **Email**: rayyanahmed265@yahoo.com
