# Ex03 Time Table
# Date:27/09/2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width,initial-scale=1.0">
        <title>Timetable</title>
    </head>
    <style>
        table,th,td{border:2px solid black;text-align:center;}
        th{background-color: turquoise;}
    </style>
    <body style="background-color:white;">
        <img src="C:\Users\admin\Documents\WhatsApp Image 2024-10-16 at 22.36.33_59082c33.jpg"/ width="100%";>
        <h1></h1>
        <table width="100%"; style="background-color:white;border: 0cap;">
            <tr align="center">
                <th style="background-color:white;border:0cap;">SLOT TIME TABLE-ALAGESHWARI V(24900791)</th>
            </tr>
        </table>
        <table style="border:2px solid black;text-align:center;background-color: peachpuff;"/ width="100%"/ height="400px">
            <tr>
                <th width="100">Day/Time</th>
                <th width="100">Monday</th>
                <th width="100">Tuesday</th>
                <th width="100">Wednesday</th>
                <th width="100">Thursday</th>
                <th width="100">Friday</th>
                <th width="100">Saturday</th>
            </tr>
            <tr>
                <th>8-10</th>
                <td>Digital electronics</td>
                <td>Chemistry</td>
                <td colspan="2">Free slot</td>
                <td>EMPD</td>
                <td>Communicative English</td>
            </tr>
            <tr>
                <th>10-12</th>
                <td>Career Development</td>
                <td>EDM</td>
                <td>Communicative English</td>
                <td>Free slot</td>
                <td colspan="2">Web application</td>
            </tr>
            <tr>
                <th>12-1</th>
                <td colspan="6">Lunch</td>
            </tr>
            <tr>
                <th>1-3</th>
                <td>Web application</td>
                <td>Digital Electronics</td>
                <td>Mentor meet</td>
                <td>Chemsitry</td>
                <td>EDM</td>
                <td>EMPD</td>
            </tr>
        </table>
        <h1></h1>
        <table style="border:2px solid black;text-align:center;"style="background-color:white;"width="100%"; height="400px">
            <tr>
                <th style="background-color:white;">S.No.</th>
                <th style="background-color:white;">Subject code</th>
                <th style="background-color:white;">Subject Name</th>
            </tr>
            <tr>
                <td style="background-color:white;">1</td>
                <td style="background-color:white;">19EN101</td>
                <td style="background-color:whitw;">Communicative English(ENG)</td>
            </tr>
            <tr>
                <td style="background-color:white;">2</td>
                <td style="background-color:white;">19CY205</td>
                <td style="background-color:white;">Principles of Chemistry in Engineering(CHE)</td>            
            </tr>
            <tr>
                <td style="background-color:white;">3</td>
                <td style="background-color:white;">19AI303</td>
                <td style="background-color:white;">Engineering Mechanics and Product Development(EMPD)</td>
            </tr>
            <tr>
                <td style="background-color:white;">4</td>
                <td style="background-color:white;">19AI414</td>
                <td style="background-color:white;">Fundamentals of Web Application Development(FWAD))</td>
            </tr>
                <td style="background-color:white;">5</td>
                <td style="background-color:white;">19AI302</td>
                <td style="background-color:white;">Engineering Design and Modelling(EDM)</td>
            </tr>
            <tr>
                <td style="background-color:white;">6</td>
                <td style="background-color:white;">19EE404</td>
                <td style="background-color:white;">Digital Electronics(DE)</td>
            </tr>
            </table>
    </body>
</html>
```
# OUTPUT

![Screenshot (30)](https://github.com/user-attachments/assets/3cc2bd8f-9d8e-40b0-8ffd-9b745715892a)
![Screenshot (31)](https://github.com/user-attachments/assets/c9ce7dbb-7a55-491f-ab24-e49470453fa3)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
