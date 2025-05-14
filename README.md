# Ex09 Event Registration Web Application
## Date:14/5/25
## Nmae : Sharon Steffani F

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Spring Fest Registration</title>
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      scroll-behavior: smooth;
    }

    section {
      min-height: 100vh;
      padding: 40px 20px;
      text-align: center;
      background-size: cover;
      background-position: center;
      position: relative;
      color: #fff;
    }

    section::before {
      content: "";
      position: absolute;
      top: 0; left: 0;
      height: 100%; width: 100%;
      background: rgba(0, 0, 0, 0.4);
      z-index: 0;
    }

    section > * {
      position: relative;
      z-index: 1;
    }

    h1 {
      font-size: 40px;
      margin-bottom: 10px;
      color: #ffeb3b;
      text-shadow: 2px 2px #4caf50;
    }

    h2, p {
      font-size: 22px;
      color: #fff9c4;
      margin-bottom: 20px;
      text-shadow: 1px 1px #388e3c;
    }

    .button {
      display: inline-block;
      margin: 10px;
      padding: 12px 28px;
      background-color: #66bb6a;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-size: 18px;
      font-weight: bold;
      box-shadow: 3px 3px 8px #333;
    }

    .button:hover {
      background-color: #388e3c;
    }

    .form input, .form select {
      display: block;
      margin: 10px auto;
      padding: 12px;
      width: 90%;
      max-width: 400px;
      border: 2px solid #aed581;
      border-radius: 5px;
      font-size: 16px;
    }

    .form button {
      padding: 10px 25px;
      background-color: #43a047;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 18px;
      cursor: pointer;
      margin-top: 10px;
    }

    .form button:hover {
      background-color: #2e7d32;
    }

    ul {
      list-style-type: none;
      padding: 0;
      font-size: 22px;
      color: #c8e6c9;
    }

    li::before {
      content: "🌼 ";
    }

    /* Section backgrounds */
    #home {
      background-image: url('https://images.unsplash.com/photo-1559589689-577aabd1ae72?auto=format&fit=crop&w=1400&q=80');
    }

    #events {
      background-image: url('https://images.unsplash.com/photo-1491951931722-5a446214b4e2?auto=format&fit=crop&w=1400&q=80');
    }

    #register {
      background-image: url('https://images.unsplash.com/photo-1526401281623-73c5c4d106cd?auto=format&fit=crop&w=1400&q=80');
    }

    #contact {
      background-image: url('https://images.unsplash.com/photo-1527969906781-52d2d3b4e6d1?auto=format&fit=crop&w=1400&q=80');
    }

    .contact-info {
      background: rgba(255, 255, 255, 0.8);
      display: inline-block;
      padding: 20px;
      border-radius: 10px;
      color: #2e7d32;
      font-weight: bold;
    }
  </style>
</head>
<body>

<!-- HOME PAGE -->
<section id="home">
  <h1>🌸 SPRING FEST 2025</h1>
  <img src="https://cdn-icons-png.flaticon.com/512/616/616408.png" alt="Spring Icon" width="100">
  <h2>Celebrate Joy, Color & Nature!</h2>
  <a href="#events" class="button">View Events</a>
  <a href="#register" class="button">Register Now</a>
</section>

<!-- EVENTS PAGE -->
<section id="events">
  <h1>🌷 Spring Fest Highlights</h1>
  <ul>
    <li>Flower Arrangement Contest</li>
    <li>Eco Fashion Show</li>
    <li>Open Mic Poetry</li>
    <li>Nature Photography</li>
    <li>Art & Craft Fair</li>
    <li>Organic Food Stalls</li>
  </ul>
  <a href="#home" class="button">Back to Home</a>
</section>

<!-- REGISTRATION PAGE -->
<section id="register">
  <h1>Register to Join 🌱</h1>
  <form class="form">
    <input type="text" placeholder="Full Name" required>
    <select required>
      <option disabled selected>Gender</option>
      <option>Male</option>
      <option>Female</option>
      <option>Other</option>
    </select>
    <input type="number" placeholder="Age" required>
    <input type="text" placeholder="Department" required>
    <input type="tel" placeholder="Mobile Number" required>
    <input type="email" placeholder="Email ID" required>
    <select required>
      <option disabled selected>Choose Event</option>
      <option>Flower Arrangement</option>
      <option>Poetry</option>
      <option>Photography</option>
    </select>
    <button type="submit">🌿 Submit</button>
  </form>
</section>

<!-- CONTACT PAGE -->
<section id="contact">
  <h1>🌞 Thank You!</h1>
  <h2>We can’t wait to celebrate Spring with you!</h2>
  <div class="contact-info">
    <p><strong>Contact Us</strong></p>
    <p>Email: springfest@yourcollege.edu</p>
    <p>Phone: +91 9876543210</p>
    <p>Saveetha Engineering College</p>
  </div>
  <br>
  <a href="#home" class="button">Back to Home</a>
</section>

</body>
</html>




```


## OUTPUT:
![image](https://github.com/user-attachments/assets/6962b978-0218-4bfd-b596-71b4ad1d77a4)
![image](https://github.com/user-attachments/assets/f52372e6-ad4a-454a-a683-2ccfaf2aef56)
![image](https://github.com/user-attachments/assets/76bcec6a-a664-4cea-8ea9-b6eef73fc044)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
