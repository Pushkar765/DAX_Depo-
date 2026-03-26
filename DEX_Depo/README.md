#DAX_Depo 

1.  Data Loading: Loaded dataset into Power BI using Excel file.
    Verified tables like Sales_Fact, Customer_Dim, and Returns_Fact.

2.  Data Modeling: Created relationships between tables:

-   Sales_Fact with Customer_Dim using CustomerID
-   Sales_Fact with Returns_Fact using OrderID
-   Created Date table and linked with Sales_Fact

3.  Calculated Columns:

-   Profit = SalesAmount - Cost
-   ReturnFlag using Returns_Fact (1 = Returned, 0 = Not Returned)
-   Customer Full Name using FirstName and LastName
-   Used RELATED() to fetch customer details

4.  Measures:

-   Total Sales
-   Total Cost
-   Total Profit
-   Return Rate (using ReturnFlag)
-   Average Sales

5.  Measure Table: Created a separate table (_Measures) to store all
    measures for better organization.

6.  Time Intelligence:

-   YTD Sales
-   Last Year Sales
-   Running Total
-   Previous Month Sales and Difference

7.  Filter Context:

-   Used ALL() to remove filters
-   Used FILTER() for conditional calculations

8.  DAX Functions:

-   COUNTX for transactions
-   DISTINCTCOUNT for unique customers
-   SUM for returned orders

9.  Final Visualization: Created Matrix Visual:

-   Rows: Region, Product Category
-   Columns: Month
-   Values: Total Sales, Profit, Return Rate, Avg Sales

10. Conclusion: Built a complete Power BI model with proper data
    modeling, DAX calculations, and interactive reporting. The project
    demonstrates strong understanding of Power BI concepts.
