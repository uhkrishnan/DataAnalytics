SQL -
* Data was loaded into mySQL using SQL workbench.
* All tables were analysed using SQL queries
	+ transactions table had currencies in INR and USD
	+ transactions table had sales_amount 0 and -1
	+ duplicate rows were identified for both INR and USD records
	+ duplicate INR and INR\r values were identified
	+ duplicate USD and USD\r values were identified

Power BI -
* Data was imported into Power BI using mySQL database connection
* Data was cleaned and transformed using Power Query in Power BI
	+ Filtered out rows with 0 and -1
	+ Filtered out duplicate rows (records with INR and USD)
	+ Added new column (norm_sales_amount) in transactions table to convert USD records to INR
	+ New column was converted into decimal format
	+ Star schema was used for modelling 
	+ Base Measures table was created using 'Enter data' to create measures such as Revenue and Sales quantity
	+ Visualisations created:
		- Cards for total revenue and total sales quantity
		- Slicers for year and month
		- Line chart for revenue trend
		- Bar charts for revenue by markets, sales quantity by markets, top 5 customers and top 5 products
	+ Power BI report created and published - both with desktop and mobile layout