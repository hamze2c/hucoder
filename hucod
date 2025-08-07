<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>HU Computers Coder</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #0a174e;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #003566;
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      padding: 40px;
    }
    section {
      margin-bottom: 40px;
    }
    form {
      max-width: 400px;
      margin: auto;
      display: flex;
      flex-direction: column;
    }
    input, textarea, button {
      margin: 10px 0;
      padding: 10px;
      font-size: 1em;
    }
    footer {
      background-color: #0a174e;
      color: white;
      text-align: center;
      padding: 20px;
    }
    #success-message {
      color: green;
      text-align: center;
      display: none;
      font-weight: bold;
    }
    #loginStatus {
      text-align: center;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <header>
    <h1>HU Computers Coder</h1>
    <p>Welcome to my personal website</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
    <a href="#signup">Sign Up</a>
    <a href="#login">Login</a>
  </nav>

  <main>

    <!-- Home -->
    <section id="home">
      <h2>Home</h2>
      <p>Hello! I’m a passionate coder from Haramaya University. This is my personal website where you can learn more about me and get in touch.</p>
    </section>

    <!-- About -->
    <section id="about">
      <h2>About</h2>
      <p>I am currently studying Computer Science at Haramaya University. I’m interested in web development, especially using HTML, CSS, JavaScript, and the MERN stack. I created this website to showcase my work and practice what I learn.</p>
    </section>

    <!-- Contact -->
    <section id="contact">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:please2wait@gmail.com">please2wait@gmail.com</a></p>
      <p>Phone: +251 96 957 0512</p>
    </section>

    <!-- Sign Up -->
    <section id="signup">
      <h2>Sign Up Form</h2>
      <form action="https://docs.google.com/forms/d/e/YOUR-FORM-ID/formResponse" method="POST" target="hidden_iframe" onsubmit="submitted=true;">
        <input name="entry.1111111111" type="text" placeholder="Full Name" required />
        <input name="entry.2222222222" type="email" placeholder="Email Address" required />
        <input name="entry.3333333333" type="tel" placeholder="Phone Number" required />
        <textarea name="entry.4444444444" placeholder="Your Message..." rows="4"></textarea>
        <button type="submit">Submit</button>
      </form>
      <iframe name="hidden_iframe" style="display:none;" onload="if(submitted) showSuccess();"></iframe>
      <p id="success-message">✔️ Your sign-up has been submitted!</p>
    </section>

    <!-- Login -->
    <section id="login">
      <h2>Login</h2>
      <form onsubmit="return loginUser()">
        <input type="email" id="loginEmail" placeholder="Email" required />
        <input type="password" id="loginPassword" placeholder="Password" required />
        <button type="submit">Login</button>
      </form>
      <p id="loginStatus"></p>
    </section>

  </main>

  <footer>
    &copy; 2025 HU Computers Coder | All rights reserved.
  </footer>

  <!-- JavaScript -->
  <script>
    let submitted = false;
    function showSuccess() {
      document.getElementById("success-message").style.display = "block";
    }

    function loginUser() {
      const email = document.getElementById("loginEmail").value;
      const password = document.getElementById("loginPassword").value;
      const status = document.getElementById("loginStatus");

      if (email === "admin@example.com" && password === "123456") {
        status.style.color = "green";
        status.innerText = "✅ Login successful!";
      } else {
        status.style.color = "red";
        status.innerText = "❌ Invalid email or password.";
      }
      return false; // Prevent form from reloading page
    }
  </script>

</body>
</html>
