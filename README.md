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
