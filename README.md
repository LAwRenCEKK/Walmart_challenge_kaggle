# Retail Analysis with Walmart Data

**Procedures:**

-   Background Introduction
-   Dataset Description
-   Objectives of Analysis
-   Analysis Tasks to be performed

# Background Introduction
One of the leading retail stores in the world, Walmart, would like to predict the  **_sales_**  and  **_demands_**  accurately. The business is facing challenges due to unforeseen demands and runs out of stock some times, as the fact that there are certain events and holidays whihc impact sales to some extents. The current system fails to forecast the demand and sales appropriately. There is a need to develop an appropriate machine learning algorithm to predict demand accurately and ingest factors such as economic conditions including CPI, Unemployment Index, etc.

# Dataset Description
Historical sales date of Walmart 45 stores located in different regions are available for analysis and model building. The historical data covers sales from 2010-02-05 to 2012-11-01 and includes the attributes as follows:

-   Store - the store number
-   Date - the week of sales
-   Weekly_Sales - sales for the given store
-   Holiday_Flag - whether the week is a special holiday week 1 – Holiday week 0 – Non-holiday week
-   Temperature - Temperature on the day of sale
-   Fuel_Price - Cost of fuel in the region
-   CPI – Prevailing consumer price index
-   Unemployment - Prevailing unemployment rate

**Holiday Events:**

-   Super Bowl: 12-Feb-10, 11-Feb-11, 10-Feb-12, 8-Feb-13
-   Labour Day: 10-Sep-10, 9-Sep-11, 7-Sep-12, 6-Sep-13
-   Thanksgiving: 26-Nov-10, 25-Nov-11, 23-Nov-12, 29-Nov-13
-   Christmas: 31-Dec-10, 30-Dec-11, 28-Dec-12, 27-Dec-13

_Note: Walmart runs several promotional events throughout the year. These events precede prominent holidays, the four largest of all, which are the Super Bowl, Labour Day, Thanksgiving, and Christmas._

# Objectives of Analysis

-   Leveraging the available data to perform extensive analysis mine the insights and patterns.
-   Develop a machine learning algorithm to predict the future demand and sales.

# Analysis Tasks to be Performed
-   data wrangling
-   data exploration
-   data modeling

**Basic Statistics tasks**

1.  Which store has  **_maximum_**  sales
2.  Which store has  **_maximum standard deviation_**  i.e., the sales vary a lot. Also, find out the  **_coefficient of mean to standard deviation_**
3.  Which store/s has good quarterly growth rate in Q3’2012
4.  Some holidays have a negative impact on sales. Find out holidays which have higher sales than the mean sales in non-holiday season for all stores together
5.  Provide a monthly and semester view of sales in units and give insights

**Statistical Model**

1.  Build prediction models to forecast demand
    
2.  Linear Regression – Utilize variables like date and restructure dates as 1 for 5 Feb 2010 (starting from the earliest date in order). Hypothesize if CPI, unemployment, and fuel price have any impact on sales.
    
3.  Select the model which gives best accuracy.
