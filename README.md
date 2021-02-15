# registration-form
<!DOCTYPE html>

 
<html>

 
<head>

 
<title>Html Form</title>

 
</head>

 
<body>

 
 

 
<h1>Registration Form</h1>

 
 

 
<!-- HTML Form -->

 
<form action="/submit.php" target="_self" method="POST">

 
 

 
<!-- input text field -->

 
<label for="firstName">First Name</label>

 
<input type="text" name="fname" id="firstName">

 
 

 
<label for="lastName">Last Name</label>

 
<input type="text" name="lname" id="lastName">

 
 

 
<br>
 
<br>

 
 

 
<!-- Radio -->

 
<label>Gender</label>

 
<input type="radio" name="gender" id="male" value="male">

 
<label for="male">Male</label>

 
<input type="radio" name="gender" id="female" value="female">

 
<label for="female">Female</label>

 
 

 
<br>


 
 

 
<!-- Dropdown/Select -->


<br>
 
<label for="religion">Religion</label>

 
<select id="religion" name="Religion">

 
<option value="Hindu">Hindu</option>
<option value="Muslim">Muslim</option>
<option value="Christian">Christian</option>
<option value="Buddh">Buddh</option>

 
</select>
<br>

<br>

<label for="fatherName">Father's Name</label>

 
<input type="text" name="fthname" id="fatherName">
<br>

<br>

<label for="motherName">Mother's Name</label>

 
<input type="text" name="mtname" id="motherName">



 
 


 
<br>

<br>

<label for="presentAddress">Present Address</label>

 
<input type="text" name="preAddress" id="presentAddress">
<br>

<br>

<label for="permanentAddress">Permanent Address</label>

 
<input type="text" name="permAddress" id="permanentAddress">

<br>
<br>
<label for="phone">Phone</label>
 
<input type="text" name="phonenumber" id="phone">
 <br>

<br>
<label for="email">Email</label>

 
<input type="email" name="email" id="email">
 <br>

<br>

<label for="websiteLink">Personal Website Link</label>

 
<input type="text" name="website" id="websiteLink">
<br> 
<br>

 
 <br>
<label for="sscYear">SSC Year</label>

 
<input type="number" name="sscyear" id="sscYear">
 <br>
<br>
<label for="sscInstitution">SSC Institution</label>

 
<input type="text" name="sscinstitution" id="sscInstitution">
 <br> 
 <br>
<label for="hscYear">HSC Year</label>

 
<input type="number" name="hscyear" id="hscYear">
 <br>
<br>
<label for="hscInstitution">HSC Institution</label>

 
<input type="text" name="hscinstitution" id="hscInstitution">
 <br> 

 
<input type="submit" value="Register">

 
 

 
</form>

 

 
</body>

 
</html>
