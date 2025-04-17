# EX01 Developing a Simple Webserver
## Date:16.04.25
## Name:Shagilan .U 
## AIM:
To develop a simple webserver to serve html pages and display the list of protocols in TCP/IP Protocol Suite.


## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>registration</title>
    <link href="sj.css"rel="stylesheet"/>
    <style>
    div{
        border: 1px solid black;
        margin-top: 50px;
        margin-bottom: 70px;
        margin-right: 150px;
        margin-left: 80px;
        background-color: blueviolet;
    }
</style>
</head>

<body>
    <div><b>The front font</b></div>
    <center><h1 style="color: rgb(41, 17, 220);"><b>Registration</b> </h1></center>
    <form>
        <center><h1><b>REGISTER HERE</b></h1></center>
       <center><table id="back==" border="6">
            <tr>
                <td>Name:</td>
                <td><input type="text" name="txtNme"/></td>
            </tr>
            <tr>
                <td>Password</td>
                <td><input type="password"/></td>
            </tr>
            <tr>
                <td>Confirm Password</td>
                <td><input type="password"/></td>
            </tr>
            <tr>
                <td>Email Id</td>
                <td><input type="email"/></td>
            </tr>
            <tr>
                <td>DOB</td>
                <td><input type="datetime-local"/></td>
            </tr>
            <tr>
                <td>Age</td>
                <td><input type="number"/></td>
            </tr>
            <tr>
                <td>Gender</td>
                <td><input type="radio"/>Male 
                    <input type="radio"/>Female
                </td>
            </tr>
            <tr>
                <td>Courses</td>
                <td><select>select the values
                    <option value="BE MECH">BE MECH</option>
                    <option value="BE CSE">BE CSE</option>
                    <option value="BE AIDS">BE AIDS</option>
                    <option value="BE AIML">BE AIML</option>
                </select></td>
            </tr>
            <tr>
                <td>Address</td>
                <td><textarea rows="2" cols="22"></textarea></td>
            </tr>
            <tr>
                <td><input type="submit"value="Register"><a href="about.html">Register</a>
                    <input type="reset" value="Reset"/>
                </td>
            </tr>
        </table></center> 
    </form>
</body>
</html>




```

## OUTPUT:
![Screenshot 2025-04-17 081036](https://github.com/user-attachments/assets/7d09af11-530e-4ba0-9f1f-703b5ee5d82e)



## RESULT:
The program for implementing simple webserver is executed successfully.
