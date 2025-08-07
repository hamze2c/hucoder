<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>HUcoder</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
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
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    input, textarea, button {
      margin: 10px 0;
      padding: 10px;
      font-size: 1em;
    }
    button {
      background-color: #0a174e;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background-color: #003566;
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
  </style>
</head>
<body>  <header>
    <h1>HUcoder</h1>
    <p>Welcome to my personal website</p>
  </header>  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
    <a href="#signup">Sign Up</a>
  </nav>  <main>
    <section id="home">
      <h2>Home</h2>
      <p>Hello! I’m a passionate coder from Haramaya. This is my personal website where you can learn more about me and my work.</p>
    </section><section id="about">
  <h2>About</h2>
  <p>I am currently studying Computer Science. I enjoy building websites, learning new technologies, and solving problems through code.</p>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>Email: <a href="mailto:please2wait@gmail.com">please2wait@gmail.com</a></p>
</section>

<section id="signup">
  <h2>Sign Up</h2>
  <form onsubmit="return handleSubmit()">
    <input type="text" placeholder="Full Name" required />
    <input type="email" placeholder="Email Address" required />
    <input type="password" placeholder="Password" required />
    <input type="password" placeholder="Confirm Password" required />
    <button type="submit">Register</button>
  </form>
  <p id="success-message">Your sign-up has been submitted!</p>
</section>

  </main>  <footer>
    &copy; 2025 HUcoder | All rights reserved.
  </footer>  <script>
    function handleSubmit() {
      document.getElementById("success-message").style.display = "block";
      return false; // Prevent actual submission
    }
  </script></body>
</html>
