# Ex09 Event Registration Web Application
## Date:18/10/2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
1st page html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Saveetha Engineering College</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <header>
      <img src="https://www.saveetha.ac.in/images/sec_logo.png" alt="Saveetha Engineering College Logo" class="college-logo">
      <h2 class="college-name">SAVEETHA ENGINEERING COLLEGE</h2>
      <p class="affiliation">AUTONOMOUS • AFFILIATED TO ANNA UNIVERSITY</p>
    </header>

    <main>
      <img src="https://upload.wikimedia.org/wikipedia/en/3/38/Saveetha_Engineering_College_logo.png" alt="SEC Logo" class="sec-logo">
      <div class="buttons">
        <button class="btn">LOGIN</button>
        <button class="btn">REGISTER</button>
      </div>
    </main>

    <footer>
      <img src="https://img.freepik.com/free-vector/people-playing-badminton-illustration_1308-126924.jpg" alt="Sports Illustration" class="footer-img">
    </footer>
  </div>
</body>
</html>
1st page css
body {
  margin: 0;
  font-family: "Poppins", sans-serif;
  background-color: #ffffff;
  text-align: center;
}

.container {
  max-width: 400px;
  margin: auto;
  border: 2px solid #fff;
  box-shadow: 0 0 10px rgba(0,0,0,0.2);
  border-radius: 8px;
  overflow: hidden;
}

header {
  background: linear-gradient(to right, #0052cc, #0084ff);
  color: white;
  padding: 15px;
}

.college-logo {
  width: 60px;
}

.college-name {
  margin: 5px 0;
  font-size: 18px;
  font-weight: bold;
}

.affiliation {
  font-size: 12px;
  color: #ffeb3b;
}

.sec-logo {
  margin: 25px 0;
  width: 120px;
  border-radius: 8px;
}

.buttons {
  display: flex;
  flex-direction: column;
  gap: 15px;
  align-items: center;
}

.btn {
  width: 150px;
  padding: 10px;
  background-color: red;
  border: none;
  color: white;
  font-weight: bold;
  border-radius: 4px;
  cursor: pointer;
  transition: 0.3s;
}

.btn:hover {
  background-color: darkred;
}

.footer-img {
  width: 100%;
  height: auto;
  margin-top: 20px;
}
2nd page html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sports Day Events</title>
  <link rel="stylesheet" href="sports.css">
</head>
<body>
  <div class="container">
    <h2>SPORTS DAY EVENTS</h2>
    <ul>
      <li>*CRICKET</li>
      <li>*KABADDI</li>
      <li>*KHO-KHO</li>
      <li>*VOLLEYBALL</li>
      <li>*FOOTBALL</li>
    </ul>
  </div>
</body>
</html>
2nd page css
body {
  margin: 0;
  padding: 0;
  font-family: "Poppins", sans-serif;
  color: black;
  text-align: left;
  background: url('https://img.freepik.com/free-vector/basketball-player-silhouette-city-background_1048-11874.jpg') no-repeat center center/cover;
  height: 100vh;
}

.container {
  padding: 20px;
  width: 250px;
  margin-left: 20px;
  margin-top: 50px;
  background-color: rgba(255, 255, 255, 0.0); /* transparent */
}

h2 {
  font-size: 18px;
  font-weight: bold;
  color: black;
  margin-bottom: 15px;
}

ul {
  list-style: none;
  padding: 0;
}

li {
  font-size: 16px;
  margin: 10px 0;
  color: #6a00ff;
  font-weight: 600;
}
3rd page html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Event Registration Form</title>
  <link rel="stylesheet" href="register.css">
</head>
<body>
  <div class="container">
    <h2>EVENT REGISTRATION FORM</h2>

    <form>
      <label>FULL NAME:</label>
      <input type="text" placeholder="Enter your full name" required>

      <label>AGE:</label>
      <input type="number" placeholder="Enter your age" required>

      <label>GENDER:</label>
      <input type="text" placeholder="Enter your gender" required>

      <label>REGISTRATION NO:</label>
      <input type="text" placeholder="Enter registration number" required>

      <label>DEPT:</label>
      <input type="text" placeholder="Enter your department" required>

      <button type="submit">REGISTER</button>
    </form>
  </div>
</body>
</html>
3rd page css
body {
  margin: 0;
  font-family: "Poppins", sans-serif;
  background: linear-gradient(to bottom, #00c6ff, #0072ff, #8e2de2, #4a00e0);
  background-size: cover;
  background-repeat: no-repeat;
  text-align: center;
  height: 100vh;
  color: black;
}

.container {
  width: 300px;
  margin: 20px auto;
  background-color: rgba(255, 255, 255, 0.3);
  border-radius: 10px;
  padding: 15px 20px;
  box-shadow: 0 0 8px rgba(0,0,0,0.2);
}

h2 {
  color: red;
  font-size: 18px;
  font-weight: bold;
  margin-bottom: 15px;
}

form {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

label {
  font-size: 14px;
  font-weight: 600;
  margin-top: 10px;
}

input {
  width: 100%;
  padding: 8px;
  margin-top: 5px;
  border: none;
  border-radius: 5px;
  background: rgba(255,255,255,0.8);
}

button {
  width: 100%;
  margin-top: 20px;
  padding: 10px;
  background-color: limegreen;
  color: white;
  font-weight: bold;
  border: none;
  border-radius: 6px;
  cursor: pointer;
  transition: 0.3s;
}

button:hover {
  background-color: #009900;
}
4th page html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Saveetha Sports Event</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <div class="poster">
    <h1>SAVEETHA ENGINEERING COLLEGE</h1>
    <h2>AUTONOMOUS</h2>
    <h3>Affiliated to Anna University</h3>
    <div class="thank-you">THANK YOU</div>
    <p class="message">
      We are all eagerly waiting for your participation in the sports events
    </p>
    <div class="contact">
      <p> Email: <a href="mailto:ABC@gmail.com">ABC@gmail.com</a></p>
      <p> Mobile: <a href="tel:+918069664567">8069664567</a></p>
    </div>
    <div class="silhouettes">
      <img src="https://upload.wikimedia.org/wikipedia/commons/7/7e/Sport_silhouettes.png" alt="Sports silhouettes" />
    </div>
  </div>
</body>
</html>
4th page css
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: linear-gradient(to right, #ff6a00, #ee0979);
  color: white;
  text-align: center;
}

.poster {
  padding: 40px 20px;
  max-width: 800px;
  margin: auto;
  background: rgba(0, 0, 0, 0.4);
  border-radius: 20px;
  box-shadow: 0 0 20px rgba(0,0,0,0.5);
}

h1 {
  font-size: 2.5em;
  margin-bottom: 0.2em;
}

h2 {
  font-size: 1.5em;
  margin: 0.2em 0;
  font-weight: bold;
}

h3 {
  font-size: 1.2em;
  margin-bottom: 1em;
  font-style: italic;
}

.thank-you {
  font-size: 2em;
  margin: 1em 0;
  font-weight: bold;
  color: #ffff00;
}

.message {
  font-size: 1.2em;
  margin-bottom: 2em;
}

.contact p {
  font-size: 1em;
  margin: 0.5em 0;
}

.contact a {
  color: #fff;
  text-decoration: underline;
}

.silhouettes img {
  width: 100%;
  max-width: 600px;
  margin-top: 30px;
  opacity: 0.9;
}


```

## OUTPUT:
<img width="1920" height="1080" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/2273fbfa-78b8-47ed-b24a-b49ef101e6ff" />


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
