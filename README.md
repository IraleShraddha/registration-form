# registration-form
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
    <title>form</title> 
    <link rel="stylesheet" href="survey.css">
</head>
<body>
    <form>
        <fieldset>
        <label for="fname">First name:</label>
        <input type="text" id="fname" name="fname" ><br><br>
        <label for="lname">Last name:</label>
        <input type="text" id="lname" name="lname" ><br><br>

        <label for="birthday">Date of Birth:</label>
<input type="date" id="birthday" name="birthday"><br><br>

        <label for="Email">Email:</label>
        <input type="email" id="email" name="email" ><br><br>
        <label for="pwd">Password:</label>
        <input type="password" id="pwd" name="pwd"><br><br>
        <label for="Gender">Gender:</label>
        <input type="checkbox" id="gender" name="gender" value="Bike">
  <label for="Gender"> Male</label>
  <input type="checkbox" id="vehicle2" name="gender" value="Car">
  <label for="gender"> Female</label>

        <p>Language you prefer to learn?</p>
        <input type="radio" id="html"   name="lang" value="HTML">
  <label for="html">HTML</label><br>
  <input type="radio" id="css" name="lang" value="CSS">
  <label for="css">CSS</label><br>
  <input type="radio" id="javascript"  name="lang" value="JavaScript">
  <label for="javascript">JavaScript</label><br><br>
  <p> Any Suggestions </p><br>


  <textarea name="comment" form="user" ></textarea><br>


        
        <input type="submit" value="Submit">
        </fieldset>
      </form>
</body>
</html>

