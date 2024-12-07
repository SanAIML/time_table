# Ex03 Time Table
# Date: 25.11.2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using <table> tag in html.

## STEP 4
Add header row using <th> tag.

## STEP 5
Add your timetable using <td> tag.

## STEP 6
Execute the program using runserver command.



# PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Timetable</title>
</head>
 
<style>
    table,th,td{border: 2px solid black; text-align: center;}
    
    th{ background-color: yellow;}
    
</style>    
<body style="background-color: white;">
    <img src="\static\Saveetha eng.jpg" width="700px">
    <h1></h1>
    <table width = "700px" style="background-color: white; border: 0cap;">
        <tr align="center">
            <th style="background-color:white;border: 0cap;  ">SLOT TIME TABLE - SANCHITA S (24900172)</th>
        </tr>  
    </table> 
    <table style="border: 2px solid black; text-align: center;background-color: aqua; width: 700px;">
        <tr>
        <th width="100"> Day/time </th>
        <th width="100"> Monday </th>
        <th width="100"> Tuesday </th>
        <th width="100"> Wednesday</th>
        <th width="100"> Thursday</th>
        <th width="100"> Friday</th>
        <th width="100"> Saturday</th>
        </tr>
        <tr>
            <th> 8-10 </th>
            <td> Free slot</td>
            <td> Chemistry </td>
            <td rowspan="2"> Free slot</td>
            <td colspan="2"> Machine learning </td>
            <td> Statistics </td>
        </tr>
        <tr>
            <th> 10-12 </th>
            <td> Career Development </td>
            <td> Statistics </td>
            <td> C programming </td>
            <td colspan="2"> Web application</td>
        </tr> 
        <tr>  
            <th> 12-1 </th>
            <td colspan="6"> Lunch </td>
        </tr>    
        <tr>
            <th> 1-3 </th>
            <td> Web application</td>
            <td>C programming</td>
            <td>Mentor meet</td>
            <td> Chemistry</td>
            <td>Human values</td>
            <td> Free slot</td>
        </tr>   
    </table> 
        <h1></h1>




        <table style="border: 2px solid black; text-align: center;" style="background-color: white;" width="700px">
              
            <tr>
                <th style="background-color: white;"> S.No.</th>
                <th style="background-color: white;"> Subject code</th>
                <th style="background-color: white;"> Subject Name </th>
            </tr>
            <tr>
                <td style="background-color: white;" > 1 </td>
                <td style="background-color: white;">19EY708</td>
                <td style="background-color: white;"> Career Development</td>
            </tr>  
            <tr>
                <td style="background-color: white;"> 2 </td>
                <td style="background-color: white;">19AI404</td>
                <td style="background-color: white;"> Web application</td>
            </tr> 
            <tr>
                <td style="background-color: white;"> 3 </td>
                <td style="background-color: white;">19CY205</td>
                <td style="background-color: white;"> Chemistry</td>
            </tr> 
            <tr>
                <td style="background-color: white;"> 4 </td>
                <td style="background-color: white;">19MA211</td>
                <td style="background-color: white;"> Statistics</td>
            </tr> 
            <tr>
                <td style="background-color: white;"> 5 </td>
                <td style="background-color: white;">19AI304</td>
                <td style="background-color: white;"> C programming</td>
            </tr>   
            <tr>
                <td style="background-color: white;"> 6</td>
                <td style="background-color: white;">19AI410</td>
                <td style="background-color: white;"> Machine learning</td>
            </tr>   
            <tr>
                <td style="background-color: white;"> 7 </td>
                <td style="background-color: white;">SH7801</td>
                <td style="background-color: white;">Human values</td>
            </tr> 
            
        </table>    
      
      
        
        
        
       


    
        </body>
</html>
```
# OUTPUT

![alt text](<timetable screenshot.png>)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
