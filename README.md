# SQL_Project
The idea of this project is to perform a data analysis using a database provided by Microsoft for learning purposes: [AdventureWorks_DB](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms).  
We will use **SQL** for querying the data and **Power BI** for visualization and analysis.




## Steps
### 1. Creación del entorno
- Nos conectamos a SQL SERVER desde SSMS
- Creamos la base de datos y agregamos las tablas (archivos csv) en este caso, obtenidas desde Microsoft Learn

### 2. Business Request
- Leemos el Business Request para orientar nuestro análisis a objetivos dados por el cliente

### 3. SQL QUERYS
- Selección de columnas importantes
- Joins 
- Filtrado por fechas de análisis solicitadas
- Guardado de resultados (Querys y Archivos csv)

### 4. PowerBi Dasboard y Creación de métricas con DAX
- Importación de resultados a través de SQL Server con Querys guardadas anteriormente
- Modificaciones importantes como tipos de datos
- Creación de métricas claves para exponer resultados como: 
  - Budget Amount = SUM(Fact_Budget[Budget])
  - Sales - Budget = [Sales] - [Budget Amount]
  - Sales / Budget Amount = Divide ( [Sales], [Budget Amount])
- Creación de panel interactivo

