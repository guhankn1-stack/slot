# Ex03 Time Table
## Date:27.09.2025

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
        <title>TimeTable</title>
    </head>
    <body>
        <img src="logo.png" width="400" height="100">
        <h2 >TIME TABLE - Guhan.K (25014479)</h2>
        <table border="3" cellspacing="3">
            <tr bgcolor="Blue">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr>
                <th bgcolor="Blue">8-10</th>
                <td colspan="2" align="center">FREE SLOT</td>
                
                <td>FWAD</td>
                <td colspan="2" align="center">FREE SLOT</td>
                <td>FWAD</td>
            </tr>
            <tr>
                <th bgcolor="Blue">10-12</th>
                <td>Python</td>
                <td>English</td>
                <td>FWAD</td>
                <td>English</td>
                <td colspan="2" align="center">FREE SLOT</td>
            </tr>
            <tr>
                <th bgcolor="Blue">12-1</th>
                <td colspan="6" align="center">LUNCH BREAK</td>
            </tr>
            <tr>
                <th bgcolor="Blue">1-3</th>
                <td colspan="2" align="center">Python</td>
                <td>Mentor meet</td>
                <td>Python</td>
                <td colspan="2" align="center">FWAD</td>
            </tr>
            <tr>
                <th bgcolor="Blue">3-5</th>
                <td colspan="3" align="center">English</td>
                <td>Python</td>
                <td>FREE SLOT</td>
                <td>Engish</td>
            </tr>
        </table><br><br>
        <table border="3">
            <tr bgcolor="yellow">
                <th align="center">S.NO></th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td bgcolor="yellow" align="center">1</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development (FWAD)</td>
            </tr>
            <tr>
                <td bgcolor="yellow" align="center">2</td>
                <td>19AI301</td>
                <td>Python</td>
            </tr>
            <tr>
                <td bgcolor="yellow" align="center">3</td>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
        </table>
    </body>
</html>
```
![alt text](<Screenshot 2025-09-27 230915.png>)
## OUTPUT


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
