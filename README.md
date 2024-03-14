# Ex03 Time Table
## Date: 14-03-2024

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
        <title>Time Table</title>
   </head>   
   <body>
        <img src="logo.png"height="200"width="1200">
        <table border="4" cellspacing="5" cellpadding="5" width="40" height="50">
            <caption>SLOT TIME TABLE-ANU VARSHINI(212223240010)</caption>
            <tr bgcolor="violet">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
            </tr>
            <tr>
                <th bgcolor="violet">8-10</th>
                <td bgcolor="lightpink">BEEME</td>
                <td bgcolor="lightpink">MATHS</td>
                <td bgcolor="lightpink">FREE SLOT</td>
                <td bgcolor="lightpink">FREE SLOT</td>
                <td bgcolor="lightpink">FWAD</td>
            </tr>
            <tr>
                <th bgcolor="violet">10-12</th>
                <td bgcolor="lightpink">FREE SLOT</td>
                <td bgcolor="lightpink">DIP</td>
                <td bgcolor="lightpink">DIP</td>
                <td bgcolor="lightpink">MATHS</td>
                <td bgcolor="lightpink">C PROGRAM</td>
            </tr>
            <tr>
                <th bgcolor="violet">12-1</th>
                <td bgcolor="lightpink" colspan="5" align="center">LUNCH BREAK</td>
            </tr>
            <tr>
                <th bgcolor="violet">1-3</th>
                <td bgcolor="lightpink">ML</td>
                <td bgcolor="lightpink">FWAD</td>
                <td bgcolor="lightpink">HRM</td>
                <td bgcolor="lightpink">FWAD</td>
                <td bgcolor="lightpink">HRM</td>
            </tr>
            <tr>
                <th bgcolor="violet">3-5</th>
                <td bgcolor="lightpink">C PROGRAM</td>
                <td bgcolor="lightpink">FREE SLOT</td>
                <td bgcolor="lightpink">FREE SLOT</td>
                <td bgcolor="lightpink">SOFT SKILLS</td>
                <td bgcolor="lightpink">FREE SLOT</td>
            </tr>
        </table>
        <table border="4" cellspacing="5" cellpadding="5" width="20" height="20">
            <tr>
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development(FWAD)</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI406</td>
                <td>Digital Image Processing(DIP)</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19AI410</td>
                <td>Introduction to Machine Learning</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19AI304</td>
                <td>Fundamentals of C Programming</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19EE305</td>
                <td>Basic Electrical,Electronics and Measurement Engineering(BEEME)</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19EY701</td>
                <td>Soft Skills</td>
            </tr>
            <tr>
                <td>7.</td>
                <td>19MA219</td>
                <td>Transforms and its Applications(Maths)</td>
            </tr>
            <tr>
                <td>8.</td>
                <td>19MS156</td>
                <td>Human Resource Management and Team Building</td>
            </tr>
        </table>
   </body>
</html>
```


# OUTPUT
![alt text](exp3.png)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
