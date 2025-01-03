# Ex03 Time Table
## Date:13.11.2024

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
        <img src="/static/logo.png">
        <table border="1" cellspacing="10" cellpadding="2">
            <caption>TimeTable-Sandhiya M (24011750)</caption>
            <tr bgcolor="cyan">
                <th>Date/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr bgcolor="yellow">
                <td>8-10</td>
                <td>FREE SLOT</td>
                <td>EDM</td>
                <td>EDM</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
                <td>FREE SLOT</td>
            </tr>
            <tr bgcolor="yellow">
                <td>10-12</td>
                <td>DS</td>
                <td>MATH</td>
                <td>FCP</td>
                <td>BEEE</td>
                <td>FCP</td>
                <td>CDS</td>
            </tr>
            <tr bgcolor="yellow">
                <td>12-1</td>
                <td colspan="6">LUNCH</td>
            </tr>
            <tr bgcolor="yellow">
                <td>1-3</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>MM</td>
                <td>DS</td>
                <td>BEEE</td>
                <td>MATH</td>
            </tr>
        </table>
        <br>
        <table border="1" cellspacing="10" cellpadding="2">
            <tr>
                <th>S.No</th>
                <th>Course Code</th>
                <th>Course Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI302</td>
                <td>Design and Modelling(EDM)</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI304</td>
                <td>Fundamentals of c programming(FCP)</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19AI403</td>
                <td>Introduction to Data science(DS)</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19AI414</td>
                <td>Fundamentals of web Application Development(FWAD)</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19EE305</td>
                <td>Basic Electronics and measurement Engineering(BEEE)</td>
            </tr>
            <tr>
                <td>6</td>
                <td>19EY708</td>
                <td>Career Development Skills</td>
            </tr>
            <tr>
                <td>7</td>
                <td>19MA201</td>
                <td>Calculus and Matrix Algebra(MATH)</td>
            </tr>
            <tr>
                <td>8</td>
                <td>ECA-M-SCOFT</td>
                <td>Mentor meet(MM)</td>
            </tr>
        
        </table>
    </body>
</html> 
```


## OUTPUT
![alt text](<Screenshot 2024-11-19 084220.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
