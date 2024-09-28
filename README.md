<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SreeDathha Adda</title>
</head>
<body>
    <fieldset>
        <legend>
            <h1>Student Details </h1>
        </legend>
        <form action="success.html" method="POST">
            <label for="name">Name of the Student:</label>
            <input type="text" id="name" size="40" required/><br><br>

            <label for="pass-no">Hallticket Number:</label>
            <input type="number" id="pass-no" size="50" required/><br><br>

            <label for="aadhar-no">Aadhar Number:</label>
            <input type="number" id="aadhar-no" size="50" required/><br><br>

            <label for="vehicle-type">Student Father Name:</label>
            <input type="text" id="vehicle-type" size="50" required/><br><br>

            <label for="departure-date">Date of birth:</label>
            <input type="date" id="departure-date" size="40" required/><br><br>

            
            <label for="stay-duration-from">Duration of study:</label>
            <label for="stay-duration-from">From:</label>
            <input type="datetime-local" id="stay-duration-from" required/>&nbsp;
            <label for="stay-duration-to">To:</label>
            <input type="datetime-local" id="stay-duration-to" required/><br><br>

            <label for="td-place">Student Branch :</label>
            <input type="text" id="td-place" size="50" required/><br><br>

            
            <label for="authority">E-Mail:</label>
            <input type="text" id="authority" size="50" required/><br><br>

            <label for="contact-number">LinkedIn Id:</label>
            <input type="number" id="contact-number" size="50" required/><br><br>

            <label>Student Gender:</label>
            <input type="radio" name="advance" value="Male" required/> Male
            <input type="radio" name="advance" value="Female" required/> Female<br><br>

            <label for="project">Backlogs of the Student:</label>
            <input type="text" id="project" size="50" required/><br><br>

            <label for="hotel-tda">Percentage//CGPA of the Student:</label>
            <input type="text" id="hotel-tda" size="50" required/><br><br>

            <input type="submit" value="Submit"/>
        </form>
    </fieldset>
</body>
</html>

