<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>[Purity Benjamin] - Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>[Purity Benjamin]</h1>
    <nav>
      <ul>
        <li><a href="#about">About Me</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hi, I'm [Purity Benjamin], a [Web developer and Technical writer] specializing in building awesome web experiences.</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>JavaScript</li>
      <li>HTML & CSS</li>
      <li>React</li>
      <li>Node.js</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <p>Here are some of the projects I've worked on:</p>
    <!-- https://medium.com/@mallitypurrie/a-freshmans-guide-to-navigating-tech-in-university-0b6f0934966f  -->
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form id="contact-form">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>

      <label for="message">Message:</label>
      <textarea id="message" name="message" required></textarea>

      <button type="submit">Send</button>
    </form>
  </section>

  <script src="script.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
  margin: 0;
  padding: 0;
}

header {
  background-color: #333;
  color: white;
  padding: 1rem;
  text-align: center;
}

nav ul {
  list-style: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin: 0 10px;
}

nav ul li a {
  color: white;
  text-decoration: none;
}

section {
  margin: 20px auto;
  padding: 20px;
  width: 80%;
  background-color: white;
  border-radius: 5px;
}

h2 {
  color: #333;
}

ul {
  list-style-type: none;
}

form input, form textarea {
  width: 100%;
  padding: 10px;
  margin: 10px 0;
  border: 1px solid #ccc;
  border-radius: 5px;
}

form button {
  background-color: #333;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

form button:hover {
  background-color: #555;
}
document.getElementById('contact-form').addEventListener('submit', function(event) {
  event.preventDefault();
  
  const name = document.getElementById('name').value;
  const email = document.getElementById('email').value;
  const message = document.getElementById('message').value;
  
  if (name && email && message) {
    alert(`Thank you ${name}, your message has been sent!`);
  } else {
    alert('Please fill out all fields.');
  }
});
document.getElementById('contact-form').addEventListener('submit', function(event) {
  event.preventDefault();
  
  const name = document.getElementById('name').value;
  const email = document.getElementById('email').value;
  const message = document.getElementById('message').value;
  
  if (name && email && message) {
    alert(`Thank you ${name}, your message has been sent!`);
  } else {
    alert('Please fill out all fields.');
  }
});
