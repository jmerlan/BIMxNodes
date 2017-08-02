#BIMxNodes: BIMxHTML
This node uses Dynamo inputs to create a web page. It outputs a string of HTML code in which you can view in any web browser.

##Sample Files

###Sample Graph.dyn
A Dynamo graph that takes data from a SQLite database and writes the query results to table rows. This graph uses Twitter Bootstrap as a frontend framework.

###Mechanical.db
SQLite database of mechanical equipment. Used as data source for Test.html

###Mechanical.rvt
Mechanical Revit model - source of data in sample database. Refer to https://github.com/jmerlan/RvtSql to generate a database like this.

###Sheets.db
Alternate SQLite database of electrical drawings.

###Test.html
Sample HTML file (web page) in which Sample Graph.dyn writes to. Open this file in any modern browser.