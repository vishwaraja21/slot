# Ex04 Time Table
## Date:18/10/2024

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
time.html
```
<html>
<head>
<title> My Time Table </title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
<table border="2" cellspacing="5" cellpading="5">
<caption>SLOT TIMETABLE - Vishwaraja R (212221220060)</caption>
<tr>
<th bgcolor="pink">Day/Time</th>
<th bgcolor="pink">Monday</th>
<th bgcolor="pink">Tuesday</th>
<th bgcolor="pink">Wednesday</th>
<th bgcolor="pink">Thursday</th>
<th bgcolor="pink">Friday</th>
</tr>
<tr>
<td bgcolor="pink">8-10</td>
<td bgcolor="lightblue">Free Slot</td>
<td bgcolor="lightblue">Operating System</td>
<td bgcolor="lightblue">Fundamentals of c programing</td>
<td bgcolor="lightblue">Operating System</td>
<td bgcolor="lightblue">Fundamentals of Web Application Development</td>
<td bgcolor="lightblue">Free</td>
</tr>
<tr>
<td bgcolor="pink">10-12</td>
<td bgcolor="lightblue">Fundamentals of c programing</td>
<td bgcolor="lightblue">Principles of Chemistry in Engineering</td>
<td bgcolor="lightblue">Fundamentals of Web Application Development</td>
<td bgcolor="lightblue">Statics and Numerical Methods</td>
<td bgcolor="lightblue">Principles of Chemistry in Engineering</td>
<td bgcolor="lightblue">Statics and Numerical Methods</td>
</tr>
<tr>
<td bgcolor="pink">12-1</td>
<td colspan="5" bgcolor="lightblue">----------------LUNCH TIME----------------</td>
</tr>
<tr>
<td bgcolor="pink">1-3</td>
<td bgcolor="lightblue">Computer Networks</td>
<td bgcolor="lightblue">Free Slot</td>
<td bgcolor="lightblue">Mentor Meeting</td>
<td bgcolor="lightblue">Free Slot</td>
<td bgcolor="lightblue">Free Slot</td>
<td bgcolor="lightblue">Free Slot</td>
</tr>
<tr>
<td bgcolor="pink">3-5</td>
<td bgcolor="lightblue">Introduction to Data Science</td>
<td bgcolor="lightblue">Fundamentals of Web Application Development</td>
<td bgcolor="lightblue">Computer Networks</td>
<td bgcolor="lightblue">Free Slot</td>
<td bgcolor="lightblue">Free Slot</td>
</tr>
</table>
<table border="2" cellspacing="5" cellpading="5">
<tr>
<th>S.NO</th>
<th>SUBJECT CODE</th>
<th>SUBJECT NAME</th>
</tr>
<tr>
<td>1.</td>
<td>19AI414</td>
<td>Fundamentals of Web Application Developement(FWAD)</td>
</tr>
<tr>
<td>2.</td>
<td>19AI304</td>
<td>Fundamentals of C programming(C)</td>
</tr>
<tr>
<td>3.</td>
<td>19AI403</td>
<td>Introduction to Data Science</td>
</tr>
<tr>
<td>4.</td>
<td>19MA211</td>
<td>Statistics and Nuerical Methods</td>
<tr>
<td>5.</td>
<td>19CS405</td>
<td>Operating System</td>
</tr>
<tr>
<td>6.</td>
<td>19CS405</td>
<td>Computer Networks(CN)</td>
</tr>
<tr>
<td>7.</td>
<td>19CY205</td>
<td>Principles of Chemistry in Engineering </td>
</tr>
</table>
</center>
</body>
</html>
```


## OUTPUT


![Screenshot (534)](https://github.com/user-attachments/assets/b12ea71e-551a-4955-a5b5-8859717d6abe)

![Screenshot (535)](https://github.com/user-attachments/assets/f92ad2c6-f486-4594-8221-e548ff95757c)





## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
