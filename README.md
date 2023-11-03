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
<!DOCTYPE html>
<html lang="en">
<head>
<title>Project Exhibition Schedule</title>
</head>
<body>

<br>
<center>
<img src = "C:\Users\SEC\Desktop\timetable\web.png" >
</center>

<table align="center" width="540" cellspacing="2" cellpadding="4" bgcolor="cyan">2
<caption><b>SLOT TIME TABLE - LAVANYA M (22009026) </b></caption>

</table>
</br>  
<br>
<table bgcolor="black" align="center" cellspacing="2" cellpadding="4" border="2">


<tr align="center">
<th bgcolor="brown"> DAY/TIME</th>
<th bgcolor="yellow">MONDAY</th>  
<th bgcolor="yellow">TUESDAY</th>    
<th bgcolor="yellow">WEDNESDAY</th>
<th bgcolor="yellow">THURSDAY</th>
<th bgcolor="yellow">FRIDAY</th>
<th bgcolor="yellow">SATURDAY</th>
</tr>
<tr>
<td  bgcolor="orange" align="center">8-10</td>
<td colspan="2" bgcolor="blue" align="center" >FREE SLOT</td>
<td bgcolor="violet" align="center">CN</td>
<td bgcolor="pink" align="center">FWAD</td>
<td bgcolor="olive" align="center">FREE SLOT</td>
<td bgcolor="green" align="center">FWAD</td>

</tr>
<tr>
<td  bgcolor="orange" align="center">10-12</td>
<td bgcolor="lavender" align="center">FREE SLOT</td>
<td colspan="2" bgcolor="red" align="center">PQM</td>
<td bgcolor="gold" align="center">IOT</td>
<td bgcolor="crimson red" align="center">FREE SLOT</td>
<td bgcolor="silver" align="center">CN</td>

</tr>

<tr>
<td  bgcolor="orange" align="center">12-1</td>
<td bgcolor="cyan" colspan="6" align="center">LUNCH</td>

</tr>
<tr>
<td  bgcolor="orange" align="center">1-3</td>
<td bgcolor="grey" align="center">SNLT</td>
<td bgcolor="pink" align="center">EMPD</td>
<td bgcolor="brown" align="center">PMC</td>
<td bgcolor="purple" align="center">EMPD</td>
<td bgcolor="red" colspan="2" align="center">FREE SLOT</td>


</tr>
<tr>
<td  bgcolor="orange" align="center">3-5</td>
<td bgcolor="lavender" align="center">FREE SLOT</td>
<td bgcolor="silver" align="center">FWAD</td>
<td colspan="2" bgcolor="green" align="center">FREE SLOT</td>
<td bgcolor="blue" align="center">PMC</td>
<td bgcolor="orange" align="center">IOT</td>

</tr>
<tr>
    <td  bgcolor="orange" align="center">5-7</td>
    <td bgcolor="brown" align="center">BEEE</td>
    <td bgcolor="violet" align="center">FREE SLOT</td>
    <td bgcolor="silver" align="center">BEEE</td>
    <td bgcolor="gold" colspan="3" align="center">FREE SLOT</td>
</tr>
</table>
<br>
<table align="center" bgcolor="cyan" cellspacing="2" cellpadding="2" border="2">
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19CS406</td>
<td>Computer Networks (CN)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AM508</td>
<td>Introduction to IOT (IOT)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19EE309</td>
<td>Programming microcontrollers (PCM)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EE305</td>
<td> Basic Electrical,Electronics and Measurement Engineering (BEEE)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19AI303</td>
<td>Engineering Mechanics and Product Development (EMPD)</td>
</tr>

<tr>
<td align="center">7.</td>
<td align="center">19EY703</td>
<td>System of Numerical and Logical Terminologies (SNLT)</td>
</tr>

<tr>
<td align="center">8.</td>
<td align="center">19MA222</td>
<td>Probablity and Queuing Methods (PQM)</td>
</tr>
</table>
</body>
</html>
```

## OUTPUT
![output](<web 3 new.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.