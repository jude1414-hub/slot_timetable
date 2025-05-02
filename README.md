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
~~~
<html>
    <head>
        <title> Course Schedule </title>
    </head>
    <body>
        <br>
            <table align="center" width="540" cellspacing="2" cellpadding="4" border="5">
                <caption><b>SLOT TIME TABLE - JUDE CLEMENT JOSE 212224230109</b></caption>
                    <tr align="center">
                        <th bgcolor="blue">Day/Time</th>
                        <th bgcolor="blue">8-10</th>
                        <th bgcolor="blue">10-12</th>
                        <th bgcolor="blue">11-12</th>
                        <th bgcolor="blue">LUNCH</th>
                        <th bgcolor="blue">1-3</th>
                        <th bgcolor="blue">3-5</th>
                    </tr>
                    <tr align="center">
                        <th bgcolor="blue">Monday</th>
                        <td>FREE SLOT</td>
                        <td>BLOCKCHAIN FOR BUSINESS</td>
                        <td>LUNCH</td>
                        <td>DIGITAL</td> 
                        <td>FREE SLOT</td>
                    </tr>
                    <tr align="center">
                        <th bgcolor="blue">Tuesday</th>
                        <td>FREE SLOT</td>
                        <td>FREE SLOT</td>
                        <td>LUNCH</td>
                        <td>FREE SLOT</td>
                        <td>INTRODUCTION TO DATA SCIENCE</td>
                    </tr>
                    <tr>
                        <th bgcolor="blue">Wednesday</th>
                        <td>FREE SLOT</td>
                        <td>DIGITAL ELECTRONACIS</td>
                        <td>LUNCH</td>
                        <td>MENTOR MEET</td>
                        <td>INTRODUCTION TO DATA SCIENCE</td>
                    </tr>
                    <tr align="center">
                        <th bgcolor="blue">Thursday</th>
                        <td>FUNDAMENTALS OF C PROGRAM</td>
                        <td>FREE SLOT</td>
                        <td>LUNCH</td>
                        <td>COMPUTER NETWORK</td>
                        <td>FUNDAMENTAL OF WEB DEVELOPMENT</td>
                    </tr>
                    <tr align="center">
                        <th bgcolor="blue">Friday</th>
                        <td>FUNDAMENTALS OF C PROGRAM</td>
                        <td>FUNDAMENTAL OF WEB DEVELOPMENT</td>
                        <td>LUNCH</td>
                        <td>FREE SLOT</td>
                        <td>FREE SLOT</td>
                    </tr>
                    <tr align="center">
                        <th bgcolor="blue">Saturday</th>
                        <td>BLOCKCHAIN FOR BUSINESS</td>
                        <td>COMPUTER STRUCTURE</td>
                        <td>LUNCH</td>
                        <td>FREE SLOT</td>
                        <td>FREE SLOT</td>
            </table>
            <br>
                <table align="center" cellspacing="2" cellpadding="4" border="2">
                    <tr align="center">
                        <th>S. No.</th>
                        <th>Subject Code</th>
                        <th>Subject Name</th>
                    </tr>
                    <tr>
                        <td align="center">1.</td>
                        <td align="center">19AI403</td>
                        <td>INTRODUCTION TO DATA SCIENCE</td>
                    </tr>
                    <tr>
                        <td align="center">2.</td>
                        <td align="center">19AI414</td>
                        <td>FUNDAMENTALS OF WEB DEVELOPEMENT</td>
                    </tr>
                    <tr>
                        <td align="center">3.</td>
                        <td align="center">19AI547</td>
                        <td>BLOCKCHAIN FOR BUSINESS</td>
                    </tr>
                    <tr>
                        <td align="center">4.</td>
                        <td align="center">19CS406</td>
                        <td>COMPUTER NETWORKS</td>
                    </tr>
                    <tr>
                        <td align="center">5.</td>
                        <td align="center">19AI301</td>
                        <td>FUNDAMENTALS OF C PROGRAM</td>
                    </tr>
                    <tr>
                        <td align="center">6.</td>
                        <td align="center">19EE404</td>
                        <td>DIGITAL ELECTRONACIS</td>
                    </tr>
            </table>
        </body>
</html>
~~~


## OUTPUT
![alt text](<Screenshot 2025-05-01 212923.png>)
![alt text](<Screenshot 2025-05-01 212852.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
