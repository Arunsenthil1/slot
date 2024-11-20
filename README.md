# Ex03 Time Table
## Date:20/11/2024

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
'''
<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TIME TABLE</title>
    <center>
    <img src="C:\Users\Arun\Downloads\images.png"
    </center>
    <title>TIME TABLE</title>
    <center>
    <h3> SLOT TIME TABLE - ARUN(24900219)</h3>    
    </center>
    </head>    
    <style>
        body{
            font-family:
    Arial,sans-serif;
          margin:0
          padding:0
            background-colour: antiquewhite;
            border;2px solid 
        }
        table{
            border-collapse: collapse;
            margin: 20px  auto;
            background-color: #d6cbda;
                 solid
            box-shadow: 0;
        }
        td{
            border: 20px
        solid
            padding:10px;
            text-align:
        }
    </style>
<table border="1" width="50%" height="25%">
    <tr  style="background-color: #9ba8ab;">
    <th>Day/Time</th>
    <th> 8-10 </th>
    <th> 10-12 </th>
    <th> 12-1 </th>
    <th> 1-3 </th>
    <th> 3-5 </th>
    </tr>
    <tr> 
        <th style="background-color: #f5f4d3;">Monday</th>
        <td style="background-color: #d6cbda;"></td> 
        <td style="background-color: #d6cbda;"> WEB Development </td>
        <td rowspan="6" style="background-color: #9ba8ab;"> Lunch </td>
        <td style="background-color: #d6cbda;"> </td>  
    </tr>
    <tr>
        <th style="background-color: #f5f4d3;"></thstyle>Tuesday</th>
        <td style="background-color: #d6cbda;"> FREE</td>
        <td style="background-color: #d6cbda;"> python</td>
        <td style="background-color: #d6cbda;"></td>
    <tr>
        <th style="background-color: #f5f4d3;"></thstyle>Wesdnesday</th>
        <td style="background-color: #d6cbda;"> Python</td>
        <td style="background-color: #d6cbda;"></td>
        <td style="background-color: #d6cbda;">Mentor Meet</td>
    </tr>  
    <tr>
        <th style="background-color: #f5f4d3;"></thstyle>Thrusady</th>
        <td style="background-color: #d6cbda;"> Physics </td>
        <td style="background-color: #d6cbda;"> Python </td>
        <td style="background-color: #d6cbda;"> Web development </td>
        <td style="background-color: #d6cbda;"></td>
    </tr>
    <tr>
        <th style="background-color: #f5f4d3;"></thstyle>Friday</th>
        <td style="background-color: #d6cbda;"> English </td>
        <td style="background-color: #d6cbda;"> Career development</td>
        <td style="background-color: #d6cbda;"> Physics</td>
        <td style="background-color: #d6cbda;"> </td>
    </tr>
    <tr>
    <th style="background-color: #f5f4d3;">Saturday</th>
    <td style="background-color: #d6cbda;"></td>
    <td style="background-color: #d6cbda;">Python</td>
    <td style="background-color: #d6cbda;"></td>
    <td style="background-color: #d6cbda;"> Web development</td>
</tr>    
</table>
</head>
<body>
<table border="4px" width="300" height="400">
        <tr>
            <th style="background-color: #9ba8ab;"> S.NO </th>
            <th style="background-color: #9ba8ab;">  Subject Name </th>
            <th style="background-color: #9ba8ab;"> Subject Code </th>
        </tr>
        <tr>
            <th> 1. </th>
            <td> Fundamentals of web applications </td>
            <td> 19AI414 </td>
        </tr>
        <tr>
            <th> 2. </th>
            <td> Maths for AI/python/linear algebra </td>
            <td> 19AI301 </td>
        </tr>
        <tr>
            <th> 3. </th>
            <td>Communicative English </td>
            <td> 19EN101 </td>
        </tr>
        <tr>
            <th> 4. </th>
            <td> Career Development skill </td>
            <td> 19EY708 </td>
        </tr>
        <tr>
            <th> 5. </th>
            <td> Career Development Skills</td>
            <td> 19EY708 </td>
         </tr>
         <tr>
            <th> 6. </th>
            <td> Physics For Quantum Computing </td>
            <td> SH3214 </td>
         </tr>   
</table>
</body>
</html>
'''
## OUTPUT

![Screenshot (1)](https://github.com/user-attachments/assets/d3aaf157-5651-4ea7-b25f-4641f446e788)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
