# user-registration
<!DOCTYPE html>
<html>
<head>
<title>Event Registration</title>
</head>
<body>

<h2>Event Registration Form</h2>

<form>
<label>Full Name:</label><br>
<input type="text" name="name" required>
<br><br>

<label>Email:</label><br>
<input type="email" name="email" required>
<br><br>

<label>Phone Number:</label><br>
<input type="tel" name="phone" required>
<br><br>

<label>Select Event:</label><br>
<select name="event" required>
<option value="">Choose an event</option>
<option value="Workshop">Workshop</option>
<option value="Hackathon">Hackathon</option>
<option value="Seminar">Seminar</option>
<option value="Cultural Fest">Cultural Fest</option>
</select>
<br><br>

<label>Registration Date:</label><br>
<input type="date" name="date" required>
<br><br>

<button type="submit">Register</button>
<button type="reset">Clear</button>
</form>

</body>
</html> 
