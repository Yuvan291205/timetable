# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
<!DOCTYPE html>
<html>
<head>
    <title> "timetable" </title>
</head>
<img src="logo.png">
<body>
    <table border="5" width="600">
        <tr>
            <th bgcolor="yellow" >day/time</th>
            <th bgcolor="yellow" >Monday</th>
            <th bgcolor="yellow" >Tuesday</th>
            <th bgcolor="yellow" >Wednesday</th>
            <th bgcolor="yellow">Thursday</th>
            <th bgcolor="yellow">Friday</th>
        </tr>
        <tr>
            <th align="center" bgcolor="yellow">8-10</th>
            <td align="center" bgcolor="cyan" colspan="3">FREE SLOT</td>
            <td align="center" bgcolor="cyan">PHY</td>
            <td align="center" bgcolor="cyan">CHE</td>
        </tr>
        <tr>
            <th align="center" bgcolor="yellow">10-12</th>
            <td align="center" bgcolor="cyan">GER</td>
            <td align="center" bgcolor="cyan">FREE SLOT</td>
            <td align="center" bgcolor="cyan">FWAD</td>
            <td align="center" bgcolor="cyan">FWAD</td>
            <td align="center" bgcolor="cyan">PHY</td>
        </tr>
        <tr>
            <td align="center" bgcolor="yellow">12-1</td>
            <td align="center" bgcolor="cyan" colspan="5">LUNCH</td>
        </tr>
        <tr>
            <th align="center" bgcolor="yellow">1-3</td>
            <td colspan="2" align="center" bgcolor="cyan">FREE SLOT</td>
            <td align="center" bgcolor="cyan">MAT</td>
            <td align="center" bgcolor="cyan">MAT</td>
            <td align="center" bgcolor="cyan">SS</td>
        </tr>
        <tr>
            <th align="center" bgcolor="yellow">3-5</th>
            <td colspan="2" align="center" bgcolor="cyan">FREE SLOT</td>
            <td align="center" bgcolor="cyan">GER</td>
            <td align="center" bgcolor="cyan">CHE</td>
            <td align="center" bgcolor="cyan">FWAD</td>
        </tr>

    </table>
    <br>

    <table border="5" width="600">
        <tr>
            <td>S.no</td>
            <td>Subject Code</td>    
            <td>Subject Name</td>    
        </tr>
        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>Fundamental of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19EN612</td>
            <td>Germna Basic (GER)</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19PH206</td>
            <td>Physical Information Technology(PHY)</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19CY205</td>
            <td>Principles of Chemistry in Engineering (CHE)</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19MA201</td>
            <td>Calculus and Matrix Algebra (MAT)</td>
        </tr>
        <tr>
            <td>6</td>
            <td>19EY701</td>
            <td>Soft Skills(SS)</td>
        </tr>
    </table>
</body>
</html>


# OUPUT
![output.png](output.png)
