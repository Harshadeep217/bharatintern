#html
<!DOCTYPE html>
<html>
<head>
<title>Registration Form</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="container">
<h1>Registration Form</h1>

<form
 
action="/register"
 
method="POST">

<input
 
type="text"
 
name="name"
 
placeholder="Name"
 
required>

<input
 
type="email"
 
name="email"
 
placeholder="Email" required>

<input
 
type="password"
 
name="password"
 
placeholder="Password"
 
required>

<button
 
type="submit">Register</button>

</form>

</div>

</body>
</html>
