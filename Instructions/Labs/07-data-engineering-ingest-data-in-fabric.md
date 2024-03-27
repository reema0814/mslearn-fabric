# Data Engineering Ingest Data in Fabric


•	I'm using the KiZAN Fabric Tenant - where we have Copilot enabled
•	Select the workspace fabric-2024001 (this is the workspace that mimics the lab environment)
•	Data Factory Persona
o	In the labs you'll create a simple data pipeline to bring in customer sales data, 
o	I want to demonstrate doing the same thing, but by using a new Data Flow Gen2
o	And leveraging the native integration of Copilot to use natural language to ingest and transform my data
 
#	Create New - Dataflow Gen2

1.	Get Data - Start by creating a connection to our data file
1.	Text/CSV
https://raw.githubusercontent.com/MicrosoftLearning/dp-data/main/sales.csv

     >**Note:** This is the same file and link you'll use in the labs.

1. Create new connection OR Edit Existing Connection
1.	Basic authentication
1.	NEXT
 
1.	You see a preview of Simple Customer/Order data
1.	CREATE
1.	Click Copilot button on Ribbon
1.	To better illustrate all that Copilot is doing for you, let me expand the UI a little to see what's going on behind the scenes.
1. 	Expand Query Settings (these are the steps in the query that bring in the data
1.	View menu
1.	Diagram View
1.	Script View - to see the M-Code that Copilot generates
1.	Looking at the data… Notice the Item Column
1.	this is really three different fields -- It contains a short description of the item, a color and a size 
o	The fields are not consistently delimited (' ' and then ' ,')
1.	Lets use Copilot to clean this up:
   -	Add a step to the query
1.  Type the following into Copilot:
 
 - In the Item column, replace the ', ' with ' '
 
The Item column now consistently has a delimiter of ' ' 
 
o	Show the m-code and new query step that copilot generated
 
•	Add a step to the query
Type the following into Copilot:
 
Split the Item column on the ' ', creating three new fields called Description, Color and Size
 
Three new fields are now created to replace the Item Column
 
o	Show the m-code and new query step that copilot generated
 
Copilot can do more than transform the table, we can actually change data as well
Scenario: think Red bikes are going to be a big seller, so increase the quantity in Inventory
Call out that the quantities for all items are 1
 
•	Add a step to the query
Type the following into Copilot:
 
Multiply the column Quantity by 10 where Color is 'Red'
 
Show that the quantity field for Red bikes is now 10 instead of 1
 
o	Discuss the effects in the Visual Query and M-Query/M-Code script
 
