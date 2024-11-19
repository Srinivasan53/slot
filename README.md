# Ex03 Time Table
## Date:17/11/24

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
<img src="logo.png"width="500">
<table border="3"cellspacing="3"cellpadding="5">
    <caption>SLOT TIME TABLE-SRINIVASAN S 24005090</caption>
<tr bgcolor="navyblue">
    <th>Date/Time</th>
    <th>8-10</th>
    <th>10-12</th>
    <th>12-1</th>
    <th>1-3</th>
    <th>3-5</th>
</tr>
<tr>
    <th>Monday</th>
    <td>Free slot</td>
    <td>CHEM</td>
    <td>LUNCH</td>
    <td>EDM</td>
    <td>Free slot</td>
</tr>
<tr>
    <th>Tuesday</th>
    <td>WEB</td>
    <td>MATHS</td>
    <td>LUNCH</td>
    <td>CE</td>
    <td>Free slot</td>
</tr>
<tr>
    <th>Wednesday</th>
    <td>EDM</td>
    <td>C Program</td>
    <td>LUNCH</td>
    <td>mentor meeting</td>
    <td>Free slot</td>
</tr> 
<tr>
    <th>Thursday</th>
    <td>Free slot</td>
    <td>CHEM</td>
    <td>LUNCH</td>
    <td>C Program</td>
    <td>Free slot</td>
</tr>
<tr>
    <th>Friday</th>
    <td>Free slot</td>
    <td>CHEM</td>
    <td>LUNCH</td>
    <td>WEB</td>
    <td>Career development</td>
</tr>
<tr>
    <th>saturday</th>
    <td>Free slot</td>
    <td>MATHS</td>
    <td>LUNCH</td>
    <td>WEB</td>
    <td>Free slot</td>
</tr>
</table>
<br>
<table border="3" cellspacing="3" cellpadding="5">
    <tr bgcolor="cyan">
        <th>S.NO</th>
        <th>Course Code</th>
        <th>Course</th>
    </tr>
    <tr>
        <th>1</th>
        <td>19AI414</td>
        <td>Fundamental of web application development(WEB)</td>
    </tr>
    <tr>
        <th>2</th>
        <td>19AI302</td>
        <td>Engineering design and model(EDM)</td>
    </tr>
    <tr>
         <th>3</th>
         <td>19AI304</td>
         <td>Fundamental of c programming(C Program)</td>
    </tr>
    <tr>
        <th>4</th>
        <td>19CY205</td>
        <td>Priniciple of chemistry in engineering(CHEM)</td>
    </tr>
    <tr>
        <th>5</th>
        <td>19EN101</td>
        <td>Communicative english(CE)</td>
    </tr>
    <tr>
        <th>6</th>
        <td>19MA201</td>
        <td>Calculas and matrix algebra(MATHS)</td>
    </tr>
</table>
</body>
</html>
```
## OUTPUT
![alt text](<Screenshot (679).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
