# Ex02 Time Table
## Date:26-11-2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <head>
    </head>
    <title>SLOT TIME TABLE</title>7
    <body>
        <center> <img src="logo.png" height="150" width="900"></center>
        <table align="center" cellspacing="1" cellpadding="3" border="3" width="600">
            <caption> SLOT TIME TABLE - MUKHILARASU K(25010728)</caption>
            <tr bgcolor="yellow" align="center">
                <td>Day/Time</td>
                <td>Monday</td>
                <td>Tuesday</td>
                <td>Wednesday</td>
                <td>Thursday</td>
                <td>Friday</td>
                <td>Saturday</td>    
            </tr>
            <tr align="center">
                <td bgcolor="yellow">8-10</td>
                <td>ITDS</td>
                <td>CP</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
                <td>FREE SLOT</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow">10-12</td>
                <td>CP</td>
                <td>ITDS</td>
                <td>FREE SLOT</td>
                <td>ITDS</td>
                <td>FWAD</td>
                <td>FWAD</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow">12-1</td>
                <td bgcolor="cyan"colspan="6" align="center">LUNCH</td>      
            </tr>
            <tr align="center">
                <td bgcolor="yellow">1-3</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>Mentor Meet</td>
                <td>ITDS</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow">3-5</td>
                <td>FREE SLOT</td>
                <td>CP</td>
                <td>CP</td>
                <td>CP</td>
                <td>ITDS</td>
                <td>FREE SLOT</td>
            </tr>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" border="5">
            <tr bgcolor="yellow">
                <td>S.NO</td>
                <td>SUBJECT NAME</td>
                <td>SUBJECT CODE</td>
            </tr>
            <tr>
                <td>1</td>
                <td>INTRODUCTION TO DATA SCIENCE (ITDS)</td>
                <td>19AI403</td>
            </tr>
            <tr>
                <td>2</td>
                <td>FUNDAMENTALS OF C PROGRAMMING (CP)</td>
                <td>19AI304</td>
            </tr>
            <tr>
                <td>3</td>
                <td>FUNDAMENTALS OF WEB APPLICATION (FWAD)</td>
                <td>19AI414</td>
            </tr>
        </table>
        </br>
    </body>
</html>
```

## OUTPUT
![Slot Image](static/image.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
