# Ex03 Time Table
## Date:18-3-24

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
        <title>My Time Table </title>
    </head>
    <body>
        <img src="C:\Users\admin\slot\Jishnu\Jishnu\static\logo.png" heigth="150" width="800">
        <table border="2" cellspacing="5" cellspacing="5" width="800" height="300">
            <caption>
                SLOT TIME TABLE -S.JISHNUPRIYAN(21222324001)
            </caption>
            <tr>
                <th bgcolor="#CCCCFF"> DAY/TIME</th>
                <th bgcolor="#CCCCFF">Monday</th>
                <th bgcolor="#CCCCFF">Tuesday</th>
                <th bgcolor="#CCCCFF"> Wednesday</th>
                <th bgcolor="#CCCCFF"> Thursday</th>
                <th bgcolor="#CCCCFF"> Friday</th>
                <th bgcolor="#CCCCFF"> Saturday</th>
            </tr>
            <tr>
                <td bgcolor="#CCCCFF">8-10</td>
                <td bgcolor="#DAF7A6">Free Slot</td>
                <td bgcolor="#DAF7A6">Free Slot</td>
                <td bgcolor="#DAF7A6">Free Slot</td>
                <td bgcolor="#DAF7A6">Free Slot</td>
                <td bgcolor="#DAF7A6">Web Development</td>
                <td bgcolor="#DAF7A6">Free Slot</td>
            </tr>
            <tr>
                <td bgcolor="#CCCCFF">10-12</td>
                <td bgcolor="#DAF7A6">Communcative English</td>
                <td bgcolor="#DAF7A6">C Programing</td>
                <td bgcolor="#DAF7A6">Quantum Computing</td>
                <td bgcolor="#DAF7A6">C Programing</td>
                <td bgcolor="#DAF7A6">Free Slot</td>
                <td bgcolor="#DAF7A6">Operting System</td>
            </tr>
            <tr>
                <td bgcolor="#CCCCFF">12-1</td>
                <td bgcolor="#DAF7A6">Lunch TIME</td>
                <td bgcolor="#DAF7A6">Lunch TIME</td>
                <td bgcolor="#DAF7A6">Lunch TIME</td>
                <td bgcolor="#DAF7A6">Mentor Meet</td>
                <td bgcolor="#DAF7A6">Lunch TIME</td>
                <td bgcolor="#DAF7A6">Lunch TIME</td>
            </tr>


            <tr>
                <td bgcolor="#CCCCFF">1-3</td>
                <td bgcolor="#DAF7A6">Introduction To Data Science</td>
                <td bgcolor="#DAF7A6">web Development</td>
                <td bgcolor="#DAF7A6">Communcative english</td>
                <td bgcolor="#DAF7A6">web Development</td>
                <td bgcolor="#DAF7A6">Free Slot </td>
                <td bgcolor="#DAF7A6">Free Slot </td>
             </tr>
             <tr>
                <td bgcolor="#CCCCFF">3-5</td>
                <td bgcolor="#DAF7A6">Operting System</td>
                <td bgcolor="#DAF7A6">Quantum Computing</td>
                <td bgcolor="#DAF7A6">Free Slot</td>
                <td bgcolor="#DAF7A6">Free Slot</td>
                <td bgcolor="#DAF7A6">Free Slot</td>
                <td bgcolor="#DAF7A6">Introduction To Data Science</td>
             </tr>   
            </table>

            <table border="2" cellspacing="5" cellpadding="5" width="600" height="50">
                <br>
                <br>
            
                <tr>
                    <th>S.NO</th>
                    <th>Subject Code</th>
                    <th><center>Subject Name</center></th>
                </tr>
                <tr>
                    <th><center>1.</center></th>
                    <th>19AI304</th>
                    <th><center>Fundamentals of C Programming</center></th>
                </tr>
                <tr>
                    <th><center>2.</center></th>
                    <th>19AI403</th>
                    <th><center>Introduction To Data Science</center></th>
                </tr>
                <tr>
                    <th><center>3.</center></th>
                    <th>19AI414</th>
                    <th><center>Fundamentals of Web Application Development</center></th>
                </tr>
                <tr>
                    <th><center>4.</center></th>
                    <th>19CS405</th>
                    <th><center>Operating System</center></th>
                </tr>
                <tr>
                    <th><center>5.</center></th>
                    <th>19EN101</th>
                    <th><center>Communicative English</center></th>
                </tr>
                <tr>
                    <th><center>6.</center></th>
                    <th>19MC802</th>
                    <th><center>Environmental Science</center></th>
                </tr>
                <tr>
                    <th><center>7.</center></th>
                    <th>19PH214</th>
                    <th><center>Physics For Quantum Computing</center></th>
                </tr>
                <tr>
                    <th><center>8.</center></th>
                    <th>22HS102</th>
                    <th><center>Tamil and technology</center></th>
                </tr>
                <tr>
                    <th><center>9.</center></th>
                    <th>ECA-M</th>
                    <th><center>Mentor Meet</center></th>
                </tr>
            </table>
            
    </body>
</html>
```
## OUTPUT
![Screenshot (4)](https://github.com/jishnusankaran/slot/assets/144979369/f9f4e9e0-724a-460b-99f0-d088646e0a6d)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
