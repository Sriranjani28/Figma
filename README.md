# Ex09 Event Registration Web Application
## Date:15.05.2025

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
page1
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SEC Arena 2025</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="flyer">
    <header class="top-bar">
      <img src="https://upload.wikimedia.org/wikipedia/en/thumb/f/f9/Saveetha_Engineering_College_Logo.png/220px-Saveetha_Engineering_College_Logo.png" alt="SEC Logo">
      <div class="college-info">
        <h2>Saveetha Engineering College</h2>
        <p>Affiliated to Anna University</p>
      </div>
      <div class="code-box">
        <p>TNEA CODE</p>
        <h3>1216</h3>
      </div>
    </header>

    <main>
      <h1>SEC ARENA</h1>
      <h2>2025</h2>
      <a href="#" class="register-btn">REGISTER</a>
    </main>

    <footer class="footer">
      <img src="https://img.freepik.com/free-vector/cheering-crowd-silhouettes-concert_23-2148444482.jpg" alt="Crowd" />
    </footer>
  </div>
</body>
</html>

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #fdf6fb;
}

.flyer {
  width: 380px;
  margin: 20px auto;
  background: white;
  box-shadow: 0 0 15px rgba(0,0,0,0.1);
  border-radius: 10px;
  overflow: hidden;
  text-align: center;
}

.top-bar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background: #f9f3fc;
  padding: 10px 15px;
}

.top-bar img {
  height: 50px;
}

.college-info {
  flex-grow: 1;
  margin-left: 10px;
  text-align: left;
}

.college-info h2 {
  margin: 0;
  font-size: 14px;
  color: #014a88;
  text-transform: uppercase;
}

.college-info p {
  margin: 2px 0 0;
  font-size: 12px;
  color: #c69c06;
  font-weight: bold;
}

.code-box {
  text-align: center;
  background: #eef;
  padding: 5px;
  border-radius: 5px;
}

.code-box p {
  margin: 0;
  font-size: 10px;
  font-weight: bold;
}

.code-box h3 {
  margin: 2px 0 0;
  color: #2b3990;
}

main h1 {
  margin-top: 30px;
  font-size: 28px;
  font-weight: bold;
}

main h2 {
  margin: 10px 0;
  font-size: 24px;
  color: #222;
}

.register-btn {
  display: inline-block;
  margin: 20px 0;
  padding: 10px 30px;
  background: #00aaff;
  color: white;
  text-decoration: none;
  font-weight: bold;
  border-radius: 50px;
}

.footer img {
  width: 100%;
  height: auto;
  margin-top: 20px;
}

page2
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Best of Luck</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="card">
    <img src="https://img.freepik.com/premium-vector/trophy-held-hand-best-design_9845-71.jpg" alt="Trophy" class="trophy-img">
    <h1>BEST OF LUCK</h1>
  </div>
</body>
</html>

body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  background: #f7f7f7;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.card {
  width: 400px;
  text-align: center;
  background: white;
  border: 2px solid #ddd;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.trophy-img {
  width: 100%;
  height: auto;
  display: block;
}

h1 {
  margin: 20px 0;
  font-size: 24px;
  color: #000;
  font-weight: bold;
}

page3
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Football Event</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="poster">
    <div class="event-details">
      <p>VENUE: MAJESTORIUM HALL</p>
      <p>TIMING: 9AM</p>
      <p>DATE: 25.05.2025</p>
    </div>
    <img src="https://img.freepik.com/free-vector/soccer-football-players-watercolor-silhouette_1048-12922.jpg" alt="Football Players">
  </div>
</body>
</html>

body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  background: linear-gradient(to bottom, #ff3300, #ffff33);
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.poster {
  width: 400px;
  text-align: center;
  color: white;
  font-weight: bold;
}

.event-details {
  margin: 30px 0;
  font-size: 18px;
}

img {
  width: 100%;
  height: auto;
  border-radius: 10px;
}

page4
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Sports Events</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="poster">
    <ul class="events">
      <li>🏅 BADMINTON</li>
      <li>🏅 TRACK & FIELD EVENT</li>
      <li>🏅 FOOTBALL</li>
      <li>🏅 BASKET-BALL</li>
    </ul>
    <img src="https://img.freepik.com/free-vector/hand-drawn-flat-design-athletics-background_23-2149491193.jpg" alt="Running Athlete">
  </div>
</body>
</html>

body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  background: #e8f6ff;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.poster {
  width: 400px;
  text-align: left;
  background: white;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

.events {
  list-style: none;
  padding: 30px 40px 10px;
  margin: 0;
  font-size: 18px;
  font-weight: bold;
}

.events li {
  margin-bottom: 15px;
  color: #000;
}

img {
  width: 100%;
  height: auto;
  display: block;
}

```

## OUTPUT:
![alt text](<WEB 06.png>)
![alt text](<web ss1.png>)
![alt text](<web ss2.png>)
![alt text](<web ss3.png>)
![alt text](<web ss4.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
