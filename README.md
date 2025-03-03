# SQL_Project
The idea of this project is to perform a data analysis using a database provided by Microsoft for learning purposes: [AdventureWorks_DB](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms).  
We will use **SQL** for querying the data and **Power BI** for visualization and analysis.

## PowerBi Dashboard URL
[PowerBi](https://app.powerbi.com/view?r=eyJrIjoiMTdkNjgzZGYtM2ZmYS00ZDI3LTgwZDMtNzMwNjVkMjRkYmRmIiwidCI6IjhhZWJkZGI2LTM0MTgtNDNhMS1hMjU1LWI5NjQxODZlY2M2NCIsImMiOjl9)


## Steps
### 1. Environment Setup
- Connect to SQL SERVER using SSMS
- Create the database and add tables (CSV files), obtained from Microsoft Learn in this case

### 2. Business Request
- Read the Business Request to align our analysis with the client's objectives

### 3. SQL Queries
- Select important columns
- Use Joins
- Filter by requested analysis dates
- Save results (Queries and CSV files)

### 4. Power BI Dashboard and Metric Creation with DAX
- Import results through SQL Server using previously saved queries
- Perform important modifications, such as data type adjustments
- Create key metrics to present results, such as:
- Budget Amount = SUM(Fact_Budget[Budget])
  - Sales - Budget = [Sales] - [Budget Amount]
  - Sales / Budget Amount = DIVIDE([Sales], [Budget Amount])
- Build an interactive dashboard

