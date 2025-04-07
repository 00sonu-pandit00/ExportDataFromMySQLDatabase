# ExportDataFromMySQLDatabase

 Method 1: Using MySQL Workbench (GUI tool)
step1 ----->  Open MySQL Workbench.

step2 ----->  click on database->connect to database
then ,Enter MySQL Password 
Run the SQL query to get the data you want.
step3 ----->
              show database;
              use db_name;  //Name of Database from that database you want to export data into csv file
              SELECT * FROM student;
step5 ------>
Click on the query->Export Result button.

Choose "Export Results" > "Export to Excel" or CSV (you can convert CSV to Excel).
Save the file.

