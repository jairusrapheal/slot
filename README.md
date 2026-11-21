# Ex04 Time Table
## Date:21/11/2026

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
    <title>DOCUMENT</title>
</head>
<body>
    <center>
        <img src="logo.png" alt="SAVEETHA LOGO"
             width="600" height="150">
        <h1 style="color: crimson">
            SOLT TABLE - JAIRUS RAPHEAL(26011256)
        </h1>
        <table border="2" style="background-color: aquamarine;">
            <tr style="background-color: rgb(217, 0, 255);">
                <th>DAY / TIME</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturdy</th>
            </tr>
            <tr>
                <th >08:00-09:00</th>
                <td>Maths</td>
                <td>English</td>
                <td>EDM</td>
                <td>DE</td>
                <td>CA</td>
                <td>FREE</td>
            </tr>
            <tr>
                <th>09:00-10:00</th>
                <td>FREE</td>
                <td>German</td>
                <td>English</td>
                <td>Maths</td>
                <td>FWAD</td>
                <td>Python</td>
            </tr>
            <tr>
                <th>10:00-11:00</th>
                <td>FREE</td>
                <td>B.EEE</td>
                <td>DATA</td>
                <td>FREE</td>
                <td>FREE</td>
                <td>DE</td>
            </tr>
            <tr>
                <th>11:00-12:00</th>
                <td>English</td>
                <td>python</td>
                <td>DATA</td>
                <td>FWAD</td>
                <td>B.EEE</td>
                <td>DE</td>
            </tr>
            <tr>
                <th>12:00-01:00</th>
                <td>German</td>
                <td>FREE</td>
                <td>Maths</td>
                <td>Japenese</td>
                <td>CA</td>
                <td>German</td>
            </tr>
            <tr>
                <th>11:00-12:00</th>
                <td>English</td>
                <td>python</td>
                <td>DATA</td>
                <td>FWAD</td>
                <td>B.EEE</td>
                <td>DE</td>
            </tr>
            <tr>
                <th>02:00-03:00</th>
                <td>Python</td>
                <td>FWAD</td>
                <td>Maths</td>
                <td>CA</td>
                <td>German</td>
                <td>EDM</td>
            </tr>
            <tr>
                <th>03:00-04:00</th>
                <td>CA</td>
                <td>DATA</td>
                <td>German</td>
                <td>B.EEE</td>
                <td>FWAD</td>
                <td>DE</td>
            </tr>
        </table>
        <br><br>
        <table border="2" style="background-color: brown;">

            <tr style="background-color: rgb(86, 143, 187);">
                <th>S.NO</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
            <tr>
                <th>1</th>
                <td>19AI245</td>
                <td>maths</td>
            </tr>
            <tr>
                <th>2</th>
                <td>19AI251</td>
                <td>german</td>
            </tr>
            <tr>
                <th>3</th>
                <td>19AI211</td>
                <td>English</td>
            </tr>
            <tr>
                <th>4</th>
                <td>19AI273</td>
                <td>B.EEE</td>
            </tr>
            <tr>
                <th>5</th>
                <td>19AI209</td>
                <td>EDM</td>
            </tr>
            <tr>
                <th>6</th>
                <td>19AI298</td>
                <td>FWAD</td>
            </tr>
            <tr>
                <th>7</th>
                <td>19AI267</td>
                <td>DE</td>
            </tr>
            <tr>
                <th>8</th>
                <td>19AI298</td>
                <td>DATA</td>
            </tr>
        </table>
    </center>
</body>
</html>
```
## OUTPUT
![alt text](<Screenshot (17).png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
