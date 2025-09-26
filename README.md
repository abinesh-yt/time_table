# Ex03 Time Table
# Date: 26-09-2025
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
    <title>TimeTable</title>

</head>
<style>
    div{
        color: red;
        font-size: 40px;
    }
   
    th{
        color: cyan;
    }

    tr{
        color:white;
    }
    .time-col{
        color:lightgreen;
    }

    .fow{
        color: gold;
    }
    .py{
        color:yellowgreen;
    }
    .ml{
        color: blue;
        

    }
    .fp{
        color:crimson;
    }

</style>


<body bgcolor="wheat">
  
    <center>
    <img src="image.jpg">
    <div>
        Time Table 25017255 👉Abinesh👈
    </div>
    <table border="6" cellpadding="5" cellspacing="7" style="background-color: black; border-color:cyan;" >
        <thead>
            <tr>
                <th>TIME</th>
                <th>monday</th>
                <th>tuesday</th>
                <th>wednesday</th>
                <th>thursday</th>
                <th>friday</th>
                <th>saturday</th>
            </tr>
        </thead>
         <tbody>
          <tr>
            <td class="time-col">08:00 - 09:00</td>
            <td rowspan="2"><span class="fp">Free period</span></td>
            <td rowspan="2"><span class="fow">web development</span></td>
            <td rowspan="2"><span class="ml">ml</span></td>
            <td rowspan="2"><span class="ml">ml</span></td>
            <td rowspan="2"><span class="py">python</span></td>
            <td rowspan="2"><span class="fow">web development</span></td>
          </tr>

          <tr>
            <td class="time-col">09:00 - 10:00</td>
           
            
          </tr>

          <tr>
            <td class="time-col">10:00 - 11:00</td>
            <td rowspan="2"><span class="fow">web development</span></td>
            <td rowspan="2"><span class="ml">ml</span></td>
            <td rowspan="2"><span class="py">python</span></td>
            <td rowspan="2"><span class="py">python</span></td>
            <td rowspan="2"><span class="fp">free period</span></td>
            <td rowspan="2"><span class="ml">ml</span></td>




            
          </tr>

          <tr>
            <td class="time-col">11:00 - 12:00</td>
           
           
       
          </tr>

          

          <tr>
            <td class="time-col">12:00 - 13:00</td>
            <td colspan="7" align="center"><div class="subject break">Lunch Break</div></td>
          </tr>

          <tr>
            <td class="time-col">13:00 - 14:00</td>
            <td rowspan="2"><span class="fp">Free period</span></td>
            <td rowspan="2"><span class="fow">web development</span></td>
            <td rowspan="2"><span class="subject english">mentor meet</span></td>
            <td rowspan="2"><span class="fp">free period</span></td>
            <td rowspan="2"><span class="fow">web development</span></td>
             <td rowspan="2"><span class="fp">free period</span></td>
  
          </tr>

          <tr>
            <td class="time-col">14:00 - 15:00</td>
         
         
          </tr>
          <tr>
            <td class="time-col">15:00 - 17:00</td>
            <td><span class="py">Python</span></td>
            <td><span class="fp">free period</span></td>
            <td><span class="ml">ml</span></td>
            <td><span class="fp">free period</span></td>
            <td><span class="fp">free period</span></td>
             <td rowspan="2"><span class="py">python</span></td>
        
          </tr>
        </tbody>
    </table>
    <br>
   

    <table border="5" style="background-color: black; border-color: aqua;" >
            <tr>
                <th>Sno:</th>
                <th>subject code</th>
                <th>subject name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>Fundamentals of web development </td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI410</td>
                <td>Machine learning</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19AI303</td>
                <td>python programming </td>
            </tr>
    </table>
    </center>

    
</body>
</html>
```
# OUTPUT
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8fcefead-00da-403a-9eee-77dae61c1a31" />

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
