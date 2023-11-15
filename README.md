# Ex03 Time Table
## Date:

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
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="grey">
<caption><b>SLOT TIME TABLE - RAGAVI K (23012384)</b></caption>
<tr align="center">
<th bgcolor="white">Day/Time</th>
<th bgcolor="white">Monday</th>
<th bgcolor="white">Tuesday</th>
<th bgcolor="white">Wednesday</th>
<th bgcolor="white">Thursday</th>
<th bgcolor="white">Friday</th>
</tr>
<tr align="center">
<th bgcolor="white">8-10</th>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>PHYSICS FOR QUANTUM COMPUTING</td>
<td>STATISTICS AND NUMERICAL METHODS</td>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
</tr>
<tr align="center">
<th bgcolor="white">10-12</th>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
<td>FREE SLOT</td>
<td>STATISTICS AND NUMERICAL METHODS</td>
</tr>
<tr>
<th bgcolor="white">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="white">1-3</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>SOFT SKILLS</td>
</tr>
<tr align="center">
<th bgcolor="white">3-5</th>
<td>STATISTICS AND NUMERICAL METHODS</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>PHYSICS FOR QUANTUM COMPUTIN</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S.No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>
<td>FUNDAMENTALS OF C PROGRAMMING(C PROGRAME)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>
<td>FUNDAMENTALS OF C PROGRAMMING(C PROGRAM)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI414</td>
<td>FUNDAENTALS OF WEB APPLICATION DEVELOPMENT(FWAD)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT(FWAD)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CY205</td>
<td>Principles of Chemistry in Engineering (CHE)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EY701</td>
<td>Soft Skills(SS)</td>
</tr>
</table>
</body>
</html>


```

## OUTPUT
![Screenshot (7)](https://github.com/Ragavikrishnan/slot/assets/144870428/268a3565-f1ed-4c63-9c7d-b8caf52de60a)
![Screenshot (8)](https://github.com/Ragavikrishnan/slot/assets/144870428/b93377f7-3711-46e9-bc6d-35a35939667a)





## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
