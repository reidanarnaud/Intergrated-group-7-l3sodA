# Intergrated-group-7-l3sodA
GROUP WORK <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Student Registration Form</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <h2>Student Registration Form</h2>
    <form action="submit.php" method="POST">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
      
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      
      <label for="phone">Phone:</label>
      <input type="tel" id="phone" name="phone" required>
      
      <label for="dob">Date of Birth:</label>
      <input type="date" id="dob" name="dob" required>
      
      <button type="submit">Register</button>
    </form>
  </div>
</body>
</html>
