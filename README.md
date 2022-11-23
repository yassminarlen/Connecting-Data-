# Connecting-Data-
# Connecting-Data
1. Download **County Health Rankings & Roadmaps** data excel sheet to desktop/laptop.

>Use link to download [County 2022 Data] (https://docs.google.com/spreadsheets/d/1RzU5DgjJf1hqWez1d29ZHZ-TkJkHYcdt/edit#gid=217844784)
2. Launch Tableau on your laptop/desktop.

**Pay special attention to the left column.** 
![Tableau Connect](https://github.com/yassminarlen/Connecting-Data/blob/main/Connecting%20Data.png?raw=true.png)

>Under the highlighted *Connect* left side of the Tableau screen, click the underlined *Microsoft Excel* option. 

3. Take notice of the pop-up screen, click on the underlined option, then click *Open* which is highlighted on the bottom right of the pop-up screen.
![Connect Excel Sheet](https://github.com/yassminarlen/Connecting-Data/blob/main/Connecting%20Excel%20Sheet.png?raw=true.png)

**Be aware that the *executing query* pop-up screen means Tableau is working on performing the tasks you have assigned it to-do, some tasks or queries( a request for data results from your database or for action on the data, or both) may take longer than others. Do not fear!**

>![Executing Query](https://github.com/yassminarlen/Connecting-Data/blob/main/executing%20query.png?raw=true.png)

4. Before you start working on any tables make sure to check the box **Clean with Data Interperter** located on the top left column of Tableau.

![Clean Data](https://github.com/yassminarlen/Connecting-Data/blob/main/Clean%20with%20Data%20Int.png?raw=true.png)

5. Right click on your mouse and hold it down to drag and drop the **Ranked Measure Data** table to the right side of the screen. 

![Drag and Drop](https://github.com/yassminarlen/Connecting-Data/blob/main/drag%20and%20drop.png?raw=true.png)

6. Drag and drop **Additional Measure Data** table right next to **Ranked Measure Data** to create a connection between tables.

 -**Be aware that the connection will be unsuccessful at first**, *it will look like this.*
 
![First Attempt at Connection](https://github.com/yassminarlen/Connecting-Data/blob/main/First%20attempt%20at%20connection.png?raw=true.png)

>Pay close attention to the highlighted and underlined areas in the image, particularly to the bottom left corner. 

7. **Select matching fields to create this relationship.** Click the drop down menu and type in *FIPS* repeat step for both of the highlighted drop down menus. 
>This will create a successful connection, changing the red line to an orange one.

>![Successful Connection](https://github.com/yassminarlen/Connecting-Data/blob/main/Successful%20Connection.png?raw=true.png)

![Matching Fields](https://github.com/yassminarlen/Connecting-Data/blob/main/Matching%20Fields.png?raw=true.png)

8. Repeat the process for *Outcomes & Factor Rankings* and *Outcomes & Factor Subrankings.*

![Repeat for Outcomes-Subrankings](https://github.com/yassminarlen/Connecting-Data/blob/main/Repeating%20for%20Outcomes.png?raw=true.png)

**You have created a web of tables to explore and create with!** 

All info obtained from Summer Workshops Data Literacy 
