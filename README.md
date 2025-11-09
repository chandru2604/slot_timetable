# Ex03 Time Table
## 

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```

<html>
    <body>
        <center>
            <img src="logo.png" width="800" height="100">
        </center><br>
        
        <table border="5" align="center" cellpadding="20" bgcolor="cyan" style="text-align: center;">
            <caption>
                <h4>SLOT TIME-TABLE PANDEESWARAN N (24901111)</h4>
            </caption>
            <tr bgcolor="yellow"><th>Day/Time</th><th>Monday</th><th>Tuesday</th><th>Wednesday</th><th>Thursday</th><th>Friday</th><th>Saturday</th></tr>
            <tr><th bgcolor="yellow">8-10</th><td>-</td><td>-</td><td>-</td><td>-</td><td>EVS</td><td>FWAD</td></tr>
            <tr><th bgcolor="yellow">10-12</th><td>GAME DEVELOPMENT</td><td>-</td><td>FUND OF C</td><td>DBMS</td><td>CN</td><td>-</td></tr>
            <tr><th bgcolor="yellow">12-1</th><td colspan="6" align="center">Lunch</td></tr>
            <tr><th bgcolor="yellow">1-3</th><td>FUND OF C</td><td>-</td><td>MM</td><td>TOC(1-HOUR(1-2))</td><td>FWAD</td><td>CN</td></tr>
            <tr><th bgcolor="yellow">3-5</th><td>-</td><td>HVAPE</td><td>DBMS</td><td>-</td><td>GAME DEVELOPMENT</td><td>TOC</td></tr>
        </table>
        <br><br>
        <table border="5" align="center" cellpadding="10" style="text-align: center;">
            <tr><th>S.No.</th><th>Subject Code</th><th>Subject Name</th></tr>
            <tr><td>1</td><td>19AI304</td><td>FUNDAMENTALS OF C PROGRAMMING</td></tr>
            <tr><td>2</td><td>19AI414</td><td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td></tr>
            <tr><td>3</td><td>19CS404</td><td>DATABASE MANAGEMENT SYSTEM AND ITS APPLICATION</td></tr>
            <tr><td>4</td><td>19CS406</td><td>COMPUTER NETWORKS</td></tr>
            <tr><td>5</td><td>19CS407</td><td>THEORY OF COMPUTATION</td></tr>
            <tr><td>6</td><td>19CY801</td><td>ENVIRONMENTAL SCIENCE AND SUSTAINABILITY</td></tr>
            <tr><td>7</td><td>19HS801</td><td>HUMAN VALUES AND PROFESSIONAL ETHICS</td></tr>
            <tr><td>8</td><td>19IT402</td><td>GAME DEVELOPMENT TECHNOLOGIES</td></tr>

        </table>


    </body>
</html>
```

## OUTPUT

<img width="1032" height="617" alt="Screenshot 2025-11-10 000349" src="https://github.com/user-attachments/assets/39c1827b-ed1c-4e76-9959-ce945bbe00fe" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
