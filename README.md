# Ex03 Time Table
## DATE : 14-11-2025

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
<<html>
<head>
<title>slot Timetable</title>    
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="10" border="7" bgcolor="white">
<caption><b>SLOT TIME TABLE - CHANDRU S(212224230042)</b></caption>
<tr bgcolor="yellow" align="center">
<th>Day/Time</th>
<th>Monday</th>
<th>Tuesday</th>
<th>Wednesday</th>
<th>Thursday</th>
<th>Friday</th>
<th>Saturday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td>FWAD</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>LEAVE </td>
<td>FWAD</td>
<td>FREE SLOT</td>

</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>LEAVE</td>
<td> C PROGRAM </td>
<td>COMPUTER</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="6" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>UI AND UX</td>
<td>UI AND UX</td>
<td>MENTOR</td>
<td>LEAVE</td>
<td>RESONING </td>
<td>C PROGRAM</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>OS</td>
<td>COMPUTER</td>
<td>OS</td>
<td>LEAVE</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>


</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="5" border="2">
<tr align="center">
<th>S.No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Appilication Development(FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19CS405</td>
<td>OPERATING SYSTEM</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI304</td>
<td>FUNDAMENTALS OF C Programming(C)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS305</td>
<td>COMPUTER ARCHITECTURE</th>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19CS549</td>
<td>UI AND UX</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EY709</td>
<td>REASONING ABILITY</td>
</tr>
</table>
</body>
</html>
```


## OUTPUT

<img width="1783" height="1079" alt="Screenshot 2025-11-14 093256" src="https://github.com/user-attachments/assets/0f1fd8f4-6ec5-4ede-ba27-1ceacd875352" />



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
