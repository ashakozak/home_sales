# Home Sales Data Analysis Challenge

Repository for the Monash University Bootcamp Module 22.

## File Structure

- `Home_Sales.ipynb`: The Jupyter Notebook developed to analyze home sales data using SparkSQL.
- `README.md`: The document you're currently reading, which provides a detailed report of the project.

## Project Overview

This project is centered around analyzing a dataset of home sales to extract insights using SparkSQL. 
The challenge involves implementing various SparkSQL operations such as creating views, caching tables, and partitioning data to optimize query performance.

### Methodology

- SparkSQL functions were used to read the `home_sales_revised.csv` data into a Spark DataFrame.
- A temporary table named `home_sales` was created to facilitate SQL queries on the dataset.
- Queries were constructed to derive insights such as average prices of homes based on the number of bedrooms, bathrooms, floors, square footage, and year built.
- The `home_sales` table was cached to improve the performance of queries.
- The dataset was partitioned by the `date_built` field to further optimize performance for specific queries.
- The runtimes of queries were measured to assess the impact of caching and partitioning on performance.
- All operations and findings were documented in the `Home_Sales.ipynb` notebook.

### Results and Conclusion

The project concludes with a comprehensive understanding of how to utilize SparkSQL for data analysis. 
The performance improvements through caching and partitioning were noted and compared.


## Contact

- For any additional questions or comments, please contact the repository owner.

---
