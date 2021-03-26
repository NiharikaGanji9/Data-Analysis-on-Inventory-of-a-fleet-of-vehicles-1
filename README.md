# Data-Analysis-on-Inventory-of-a-fleet-of-vehicles-1

The dataset used comes from the following source: https://data.world/montgomery-county-of-maryland/1f06ef22-f2db-433c-b589-59afcab814ce under a Public Domain license. This data originates from the US Open Data Portal at https://data.world/datagov-us.

Intial Workbook: Montgomery_Fleet_Equipment_Inventory_FA_PART_1_START.CSV

##Several tasks perfomed in cleaning and preparing the data include:

1.Changing the format of the file: Saving the CSV file as an XLSX file.

2..Column widths: Sorting out the widths of all columns.

3.Empty rows: Using the Filter feature to look for blanks and removing all empty rows from the data.

4.Duplicate records: Using Remove Duplicates feature to look for and remove any duplicated records from the data.

5.Spelling:Checking for spelling mistakes in the data and fixing them.

6.Whitespace:Using the Find and Replace feature to remove all the double-spaces from the data.

7.Department names:Using Flash Fill to reduce the department names to just one column as shown below, and then removing any unnecessary columns.

Department	

Board of Elections

Economic Development

Circuit Court	

Environmental Protection

Community Engagement Cluster	

Finance

Community Use of Public Facilities

Fire and Rescue

Consumer Protection	

General Services

Correction and Rehabilitation	

Health and Human Services

County Executives Office	

####Several tasks perfomed in analysing,mining and visualizing the data include:

1.Formatting the data as a table

2.AutoSum: Use AutoSum to find the following values for column 'C' and record each of the values:

SUM
AVERAGE
MIN
MAX
COUNT
Create a Pivot Table: Use the PivotTable feature to create a pivot table that displays the Department field in the Rows section, and the Equipment Count in the Values section, so that the pivot table displays the sum of equipment count by department.

Sort the pivot table data: Use the Sort By Value setting on the pivot table to sort it in descending order by the sum of equipment count.

Make two more pivot tables exactly the same as task 3: Follow the same steps you performed in Tasks 3 and 4 to create two more identical pivot tables so that you end up with 3 worksheets that contain identical pivot tables.

Analyze data in the pivot table: Use the PivotTable Fields pane to manipulate and analyze data in the two copied pivot table as follows:

In pivot table 2 add the Equipment Class field below the Department field so that the different vehicle types appear under each department with their respective counts.
Collapse all fields except the top one - Transportation
In pivot table 3 add the Equipment Class field above the Department field so that the different vehicle types appear first, with the different departments listed underneath each vehicle type with their respective counts.
Collapse all fields except the top one - CUV

