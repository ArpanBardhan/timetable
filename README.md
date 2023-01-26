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
```
<!DOCTYPE html>
<html lang="en">
    <head>
    <title>Slot Timetable</title>
    </head>

    <center>
    <img src="/static/images/logo.png" height="150" width="1825">
    </center>
    <table border = "4" cellspacing="14" bordercolor="cyan"
    bgcolor="white">
    <tr>
    <th colspan="12">TIME TABLE</th>
    </tr>
    <th colspan=3>Reference Number:</th>
    <th colspan=2>22008018</th>
    <th colspan=2>Name:</th>
    <th colspan=4>Arpan Bardhan</th>
    </tr>
    <tr>
    <th>DAYS</th>
    <th>1</th>
    <th>2</th>
    <th>3</th>
    <th>4</th>
    <th rowspan="8">Lunch Break</th>
    <th>5</th>
    <th>6</th>
    <th>7</th>
    <th>8</th>
    </tr>
    <tr>
    <td>MONDAY</td>
    <td>Programming in C P1</td>
    <td>Programming in C P1</td>
    <td>Fundamentals of Web Application Development</td>
    <td>Fundamentals of Web Application Development</td>
    <td>Problem solving and Python Programming P1</td>
    <td>Problem solving and Python Programming P1</td>
    <td>Soft Skills</td>
    <td>Soft Skills</td>
    </tr>
    <tr>
    <td>TUESDAY</td>
    <td>Japanese Basic</td>
    <td>Japanese Basic</td>
    <td>Coding Practice T03</td>
    <td>Coding Practice T03</td>
    <td>Fundamentals of Web Application Development</td>
    <td>Fundamentals of Web Application Development</td>
    <td>Programming in C P1</td>
    <td>Programming in C P1</td>
    </tr>
    <tr>
    <td>WEDNESDAY</td>
    <td>Computational Physics</td>
    <td>Computational Physics</td>
    <td>Principles of Chemistry in Engineering</td>
    <td>Principles of Chemistry in Engineering</td>
    <td>Fundamentals of Web Application Development</td>
    <td>Fundamentals of Web Application Development</td>
    <td>Digital Principles and System Design</td>
    <td>Digital Principles and System Design</td>
    </tr>
    <tr>
    <td>THURSDAY</td>
    <td>Digital Principles and System Design</td>
    <td>Digital Principles and System Design</td>
    <td>Coding Practice TH03</td>
    <td>Coding Practice TH03</td>
    <td>Principles of Chemistry in Engineering</td>
    <td>Principles of Chemistry in Engineering</td>
    <td>Computational Physics</td>
    <td>Computational Physics</td>
    </tr>
    <tr>
    <td>FRIDAY</td>
    <td>Problem solving and Python Programming P1</td>
    <td>Problem solving and Python Programming P1</td>
    <td>Break</td>
    <td>Break</td>
    <td>Break</td>
    <td>Digital Principles and System Design</td>
    <td>Japanese Basic</td>
    <td>Japanese Basic</td>
    </tr>
    </table>
    
</html>
```
# OUPUT

![OUTPUT](myproj/static/images/timetable.png)

![OUTPUT](myproj/static/images/validi.png)