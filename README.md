This is an SQL Database I made for a Stardance website I created. This Database uses Microsoft Azure, which makes it more difficult to display. So I inserted the code here. 


**ALL INFORMATION IN THIS DATABASE BELONGS TO https://worldofoutlaws.com/sprintcars/historical-stats-sprint-cars/all-time-wins/ AND OTHER RESPECTIVE HOLDERS**

How I made the Database

First, I created a Microsoft Azure SQL database and server. I used the credentials to connect to VS Code. This allowed me to create the SQL Database without leaving my VS Code workspace, allowing me to track my coding time with Wakatime.
Secondly, I used the SQL commands: 
```
CREATE TABLE sprintcars3 (
  pos INT PRIMARY KEY,
  driver VARCHAR(255) NOT NULL,
  locatiom VARCHAR(255) NOT NULL,
  wins INT NOT NULL
  );
  ```
  This creates the table, then the code inside of DB.sql inserts the data into said table.
