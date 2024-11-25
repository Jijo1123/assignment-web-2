<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Multimedia Webpage and Registration Form</title>
</head>
<body>
  <h1>Welcome to Our Multimedia Page</h1>

  <!-- Part 1: Multimedia Webpage -->
  <section>
    <h2>Enjoy Multimedia Content</h2>

    <!-- Audio Section -->
    <h3>Listen to Music</h3>
    <audio controls>
      <source src="audio-file.mp3" type="audio/mpeg">
      <source src="audio-file.ogg" type="audio/ogg">
      Your browser does not support the audio element.
    </audio>

    <!-- Video Section -->
    <h3>Watch a Video</h3>
    <video controls poster="poster-image.jpg" width="640" height="360">
      <source src="video-file.mp4" type="video/mp4">
      <source src="video-file.webm" type="video/webm">
      Your browser does not support the video element.
    </video>
  </section>

  <hr>

  <!-- Part 2: Registration Form -->
  <section>
    <h2>Register to Join</h2>
    <form action="#" method="post">
      <!-- Full Name -->
      <label for="fullname">Full Name:</label>
      <input type="text" id="fullname" name="fullname" required maxlength="50"><br><br>

      <!-- Email Address -->
      <label for="email">Email Address:</label>
      <input type="email" id="email" name="email" required><br><br>

      <!-- Password -->
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" required minlength="8"><br><br>

      <!-- Age -->
      <label for="age">Age:</label>
      <input type="number" id="age" name="age" min="18" required><br><br>

      <!-- Gender -->
      <label>Gender:</label>
      <input type="radio" id="male" name="gender" value="male" required>
      <label for="male">Male</label>
      <input type="radio" id="female" name="gender" value="female" required>
      <label for="female">Female</label>
      <input type="radio" id="other" name="gender" value="other" required>
      <label for="other">Other</label><br><br>

      <!-- Terms and Conditions -->
      <input type="checkbox" id="terms" name="terms" required>
      <label for="terms">I agree to the terms and conditions</label><br><br>

      <!-- Submit Button -->
      <button type="submit">Register</button>
    </form>
  </section>
</body>
</html>
