HR Analytics dashboard - Attendance Insights

AIM:
To create a dashboard that will answer the below questions:
	- Percentage of employees that are present on a particular day
		+ Historical data as well
		+ Understand staff availability on a monthly basis to plan implementations
	- Percentage of employess working from home
		+ When do employees mostly work from home
		+ Preferred day
	- Percentage of employees that are on sick leave
		+ Identify trends if any
		+ Understand staff availability on a monthly basis

METHOD:
- Data was imported from the excel sheet maintained by HR department
- Data was transformed using power query
	+ General template and formula were created so that all transformations work on future sheets
	+ New columns were added using DAX 
	+ All columns were transposed using unpivot columns to rows
- Dashboard was created
	+ New measures added using DAX