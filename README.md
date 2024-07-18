## Instructions
1. Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.

2. Import the necessary PySpark SQL functions for this assignment.

3. Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

4. Create a temporary table called home_sales.

5. Answer the following questions using SparkSQL:

   * What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
  
     ![image](https://github.com/user-attachments/assets/82821e65-1e11-4709-b02a-ba22a5cedec7)


   * What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
  
     ![image](https://github.com/user-attachments/assets/9054f479-c10f-4c4d-979f-c69b7e640238)


   * What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
  
     ![image](https://github.com/user-attachments/assets/e315929e-a2e1-4b5b-b86a-6947c6e7e58c)


   * What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
  
     ![image](https://github.com/user-attachments/assets/e53aa91a-d2d8-4d90-8083-22e4030945ef)


6. Cache your temporary table home_sales.

7. Check if your temporary table is cached.

8. Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

   ![image](https://github.com/user-attachments/assets/72eb5aff-956b-4db3-b3ca-7ab19571e7b7)


10. Partition by the "date_built" field on the formatted parquet home sales data.

11. Create a temporary table for the parquet data.

12. Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

    ![image](https://github.com/user-attachments/assets/de03b18d-c376-4c87-8142-4d82a88950ca)


14. Uncache the home_sales temporary table.

15. Verify that the home_sales temporary table is uncached using PySpark.

16. Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.
