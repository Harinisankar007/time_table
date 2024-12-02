# Ex03 Time Table
# Date:02.12.2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using ```<table>``` tag in html.

## STEP 4
Add header row using ```<th> ```tag.

## STEP 5
Add your timetable using ```<td>``` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<html>
    <head>
        <center>
        <img src="saveetha.png">
        <title>SLOT TIMETABLE (HARINI)</title>
        <caption><h3>SLOT TIMETABLE- HARINI S (24901178)</h3></caption>
        </center>
    </head>
    <body>
        <center>
           <table border="1">
            <tr bgcolor="beige">
                <td><h3>Day/Time</h3></td>
                <td><h3><center>Monday</center></h3></td>
                <td><h3><center>Tuesday</center></h3></td>
                <td><h3><center>Wednesday</center></h3></td>
                <td><h3><center>Thursday</center></h3></td>
                <td><h3><center>Friday</center></h3></td>
                <td><h3><center>Saturday</center></h3></td>
            </tr>
            <tr bgcolor="pink">
                <td bgcolor="blue"><center><h3>8-10</h3></center></td>
                <td></td>
                <td>Communicative english</td>
                <td>Python Programming</td>
                <td></td>
                <td>Communicative english</td>
                <td></td>
            </tr>
            <tr bgcolor="pink">
                <td bgcolor="blue"><center><h3>10-12</h3></center></td>
                <td>Web Development</td>
                <td>Physics</td>
                <td></td>
                <td>Python Programming</td>
                <td></td>
                <td>Python Programming</td>
            </tr>
            <tr bgcolor="pink">
                <td bgcolor="blue"><center><h3>12-1</h3></center></td>
                <td colspan="6"><center><h3>L U N C H</h3></center></td>
            </tr>
            <tr bgcolor="pink">
                <td bgcolor="blue"><center><h3>1-3</h3></center></td>
                <td></td>
                <td>Python Programming</td>
                <td>Mentor Meet</td>
                <td>Web Development</td>
                <td>carrer Development skills</td>
                <td>Physics</td>
            </tr>
                <tr bgcolor="pink">
                    <td bgcolor="blue"><center><h3>3-5</h3></center></td>
                    <td></td>
                    <td></td>
                    <td>BEEE</td>
                    <td></td>
                    <td></td>
                    <td>Web Development</td>
                </tr>
            

        </table><br>

        <table border="1">
            <tr>
                <td><h3>s.no</S></h3></td>
                <td><h3>Subject code</h3></td>
                <td><h3><center>subject name</center></h3></td>
            </tr>
            <tr>
                <td>1.</td>
                <td><center>19AI414</center></td>
                <td>Fundamental WebDevelopment</td>
            </tr>
            <tr>
                <td>2.</td>
                <td><center>19AI301C</center></td>
                <td>Python Programming</td>
            </tr>
            <tr>
                <td>3.</td>
                <td><center>SH3214</center></td>
                <td> Physics</td>
            </tr>
            <tr>
                <td>4.</td>
                <td><center>19EY708</center></td>
                <td>Carrer Development Skills</td>
            </tr>
            <tr>
                <td>5.</td>
                <td><center>19EN101</center></td>
                <td>Communicative english</td>
            </tr>
            <tr>
                <td>6.</td>
                <td><center>19EE305</center></td>
                <td>BEEE</td>
            </tr>
        </table>
        </center>
    </body>
</html>
```
# OUTPUT
![alt text](<Screenshot 2024-12-02 134527.png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
