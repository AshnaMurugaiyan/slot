# Ex03 Time Table
## Date:
10/12/2025

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
<!DOCTYPE html>
<html> 
<head>
    <title>Timetable</title>
</head>            
<title>Google <div class="Timetable"></div></title>
    <body> 
     <center> 
     <img src="/static/logo.png" height="150" width="800">
     </center>
      <h3 align="center">  SLOT TIME TABLE - STUDENT NAME ( ROLL NO.25018797 ) </h3>
        <table align="center" border="5" cellpadding="6" cellspacing="2" bgcolor="sky blue">
        <tr>
          <th bgcolor="Pink">Day</th>    
          <th bgcolor="Pink">8-10</th>
          <th bgcolor="Pink">10-12</th>
          <th bgcolor="Pink">12-1</th>
          <th bgcolor="Pink">1-3</th>
          <th bgcolor="Pink">3-5</th>
        </tr>
        <tr>
           <th bgcolor="cyan">MONDAY </th>
           <td>Python </td>
           <td>Python    </td>
           <td rowspan="6">L<br>U<br>N<br>C<br>H </td>
           <td>Web     </td>
           <td>English  </td>
        </tr>
        <tr>
            <th bgcolor="cyan">TUESDAY  </th>
            <td>Web </td>
            <td>Free slot</td>
            <td>Python   </td>
            <td>Web </td>
         </tr> 
         <tr>
            <th bgcolor="Cyan">WEDNESDAY </th>
            <td>Web </td>
            <td>Free slot </td>
            <td>Mentor Meeting  </td>
            <td>English </td>
         </tr> 
         <tr>
            <th bgcolor="Cyan">THURSDAY  </th>
            <td>Free slot  </td>
            <td>English</td>
            <td>Web   </td>
            <td>Free slot </td>
         </tr>
          <tr>
            <th bgcolor="Cyan">FRIDAY    </th>
            <td>Free slot   </td>
            <td>Python   </td>
            <td>Python  </td>
            <td>Free slot </td>
         </tr>
         <tr>
            <th bgcolor="Cyan">SATURDAY  </th>
            <td>Free slot</td>
            <td>Free slot  </td>
            <td>Free slot </td>
            <td>English  </td>
         </tr>
        </table>
        <br> 
        <table border="5" cellpadding="7" cellspacing="2" align="center">
         <tr>
           <th><h4>S.NO</h4></th>    
           <th><h4>SUBJECT CODE </h4></th>
           <th><h4>SUBJECT NAME </h4></th>
         </tr>
         <tr>
            <th>1.</th>
            <td>19AI414</td>
            <td>Fundamentals of web application</td>
         </tr>
         <tr>
             <th>2.</th>
             <td>19EN101</td>
             <td>Communicative English </td>
          </tr> 
          <tr>
             <th>3.</th>
             <td>19AI301</td>
             <td>Python Programming </td>
          </tr> 
          <tr>
             <th>4.</th>
             <td>ECA-M</td>
             <td>Mentor Meet  </td>
          </tr>
        
         </table>   
    </body>
</html>
```

## OUTPUT
<img width="1920" height="898" alt="Screenshot (68)" src="https://github.com/user-attachments/assets/cf1e0b07-0d3b-48c2-9ca5-e260be32510d" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
