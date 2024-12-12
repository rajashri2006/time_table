# Ex03 Time Table
# Date:21-10-2024
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
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
time.html


!Doctype html>
<html>
    <head>
        <title>TIMETABLE</title>
        <style>
            *{
                margin: 0%;
                padding: 0%;
            }
           
        table,tr,th,td{
            border: 4px solid rgb(146, 143, 141);
        } 
        th{
            background-color: rgb(246, 242, 9);
        }
        tr{
            background-color: rgb(51, 209, 227);
        }
        table{
            border-collapse: collapse;
            -moz-box-align: center;
            
        }
        .head{
            text-align: center;
            font-size: 50px;
        }
        img {
            width: 100%;
            height: 22vh;
            padding: 0;
            
        }
        .text{
             font-size: 20px;
        }
        body{
            font-size: larger;
        }
   

        </style>
    </head>
        <body>
            
            <div class="logo">
            <img src="WEB_LOGO-01.png">
            </div>
            <div class="head">
                <b>TIME TABLE</b>
            </div>

            <BR>
            <div class="text">
                <b>RAJA SHRI I<br>REG.NO:24900207</b>
            </div>

            <br>
            <table style="border: 5px;">
                <tr>
                    <th>TIME</th>
                    <th>08.00-10.00</th>
                    <th>10.00-12.00</th>
                    <td rowspan="7">LUNCH</td>
                    <th>01.00-03.00</th>
                    <th>03.00-05.00</th>
                </tr>
                <tr>
                    <th>MONDAY</th>
                    <td>free</td>
                    <td>communicative english</td>
                    <td>web application</td>
                    <td>free</td>
                    </tr>
                    <tr>
                        <th>TUESDAY</th>
                    <td>EDM</td>
                    <td>digial electronics</td>
                    <td>communicative english</td>
                    <td>free</td>
                    </tr>
                    <tr>
                    <th>WEDNESDAY</th>
                    <td>EDM</td>
                    <td>calculus and matrix</td>
                    <td>mentor meeting</td>
                    <td>chemistry</td>
                    </tr>
                    <tr>
                    <th>THURSDAY</th>
                    <td>free</td>
                    <td>digital electronics</td>
                    <td>career development</td>
                    <td>free</td>
                    </tr>
                    <tr>
                    <th>FRIDAY</th>
                    <td>free</td>
                    <td>web application</td>
                    <td>calculus and matrix</td>
                    <td>free</td>
                    </tr>
                    <tr>
                    <th>SATURDAY
                    <td>free</td>
                    <td>web application</td>
                    <td>calculus and matrix</td>
                    <td>free</td>
                    </tr>
            </table>
            



            <br>
            <table border="5px">
                <tr>
                  <th><h4>S.NO</h4></th>    
                  <th><h4>SUBJECT CODE </h4></th>
                  <th><h4>SUBJECT NAME </h4></th>
                </tr>
                <tr>
                   <th>1</th>
                   <td>19AI302</td>
                   <td>EDM</td>
                </tr>
                <tr>
                    <th>2</th>
                    <td>19AI414</td>
                    <td>fundamentals of web application</td>
                 </tr> 
                 <tr>
                    <th>3</th>
                    <td>19CY205</td>
                    <td>principles of chemistry in engineering</td>
                 </tr> 
                 <tr>
                    <th>4</th>
                    <td>19EE404</td>
                    <td>Digital Electronics</td>
                 </tr>
                  <tr>
                    <th>5</th>
                    <td>19EN101</td>
                    <td>Communicative English</td>
                 </tr>
        
                 <tr>
                  <th>6</th>
                 <td>19EY708</td>
                 <td>Career development skills </td>
                 </TR>
        
                 <TR>
                    <TH>7</TH>
                    <TD>19MA201</TD>
                    <TD>Calculus and matrix algebra</TD>
                 </TR>
             </table>
                
        </body>
</html>
```
         


# OUTPUT
![timetable](https://github.com/user-attachments/assets/5105c4fa-0e1a-44cb-ac7c-8be0b9645a2c)


![time table output](https://github.com/user-attachments/assets/da3c9c7b-0ae3-4661-84d3-3c3881d9fe4b)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
