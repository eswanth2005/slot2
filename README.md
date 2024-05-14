# Ex03 Time Table
## Date:
04.03.2024
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
       <title> TIME TABLE </title>
   </head>
 <body align="center">
 <table border="6" cellspacing="6" cellpadding="8" align="center" bgcolor="CYAN">
<img src="logo.png" align="center" height="70" width="800">
<caption><b>SLOT TIMETABLE- K ESWANTH KUMAR(212223040046)</b></caption>

   <tr>
        <th bgcolor="yellow">Day/Time</th>
        <th bgcolor="yellow">Monday</th>
        <th bgcolor="yellow">Tuesday</th>
        <th bgcolor="yellow">Wednesday</th>
        <th bgcolor="yellow">Thursday</th>
        <th bgcolor="yellow">Friday</th>
  </tr>
  <tr>
        <th bgcolor="yellow">8-10</th>
        <td>CS</td>
        <td>FWAD</td>
        <td>CA</t>
        <td>DE</td>
        <td>EDM</td>
 </tr>
 <tr>
        <th bgcolor="yellow">10-12</th>
        <td>FREE</td>
        <td>CA</td>
        <td>Free Slot</t>
        <td>Free</td>
        <td>CN</td>
 </tr>
 <tr> 
        <th bgcolor="yellow">12-1</th>
        <TD colspan="5" Align="center"><B>L U N C H </B></TD> </tr>
 <tr>
        <th bgcolor="yellow">1-3</th>
        <td>CN</td>
        <td>ADVC</td>
        <td>FWDA</t>
        <td>ADVC</td>
        <td>FREE</td>
 </tr>
 <tr>
        <th bgcolor="yellow">3-5</th>
        <td>Free Slot</td>
        <td>Free Slot</td>
        <td>EDM</t>
        <td>Free Slot</td>
        <td>FWDA</td>
</tr>
</body>
</html>
<table cellspacing="8" cellpadding="0" align="center">
<html>
<head>
    <title> Subject code </title>
</head>
 <body>
 <table border="6" cellspacing="7" cellpadding="8" align="center">

<tr> 
        <th>S.NO</th>
        <th>Subject Code</th>
        <th>Subject</th>
</tr>        
<tr>
     <td>1</td>
     <td>19AI414</td>
     <td>Fundamentals of Web Application Development(FWAD)</td>
</tr>    
<tr>
     <td>2</td>
     <td>19EY702</td>
     <td>Creative skills(CS)</td>
</tr> 
<tr>
     <td>3</td>
     <td>19CS405</td>
     <td>Computer Architecture(CA)</td>
</tr>     
<tr>
     <td>4</td>
     <td>10AI302</td>
     <td>Engineering design and modelling(EDM)</td>
</tr>   
<tr>
     <td>5</td>
     <td>19AI305</td>
     <td>Advanced C programming(ADVC)</td>
</tr> 
<tr>
    <td>6</td>
    <td>19CS406</td>
    <td>Computer networks(CN)</td>
</tr>  
<tr>
    <td>7</td>
    <td>19EE404</td>
    <td>Digital Electronics(DE)</td>
</tr>   
   
</body>
</html>
```
## OUTPUT
![alt text](<Screenshot (4).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
