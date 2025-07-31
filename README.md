<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Imtiaj Ahmed - Portfolio</title>
  <style>
    :root {
      --primary: #007BFF;
      --dark: #222;
      --light: #f4f4f4;
      --text: #333;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: var(--light);
      color: var(--text);
    }

    header {
      background: linear-gradient(135deg, #007BFF, #0056b3);
      color: white;
      text-align: center;
      padding: 60px 20px;
    }

    header h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.3em;
      font-weight: 300;
    }

    nav {
      background-color: var(--dark);
      display: flex;
      justify-content: center;
      padding: 15px 0;
      flex-wrap: wrap;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 10px 20px;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: var(--primary);
    }

    main {
      max-width: 1000px;
      margin: 40px auto;
      padding: 0 20px;
    }

    .profile-pic {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid var(--primary);
      margin: 0 auto 20px;
      display: block;
    }

    section {
      margin-bottom: 50px;
      background: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    }

    h2 {
      color: var(--primary);
      margin-bottom: 20px;
      font-size: 1.8em;
    }

    ul {
      padding-left: 20px;
    }

    ul li {
      margin-bottom: 10px;
    }

    a {
      color: var(--primary);
    }

    footer {
      background-color: var(--dark);
      color: white;
      text-align: center;
      padding: 25px 10px;
      font-size: 0.9em;
    }

    /* Responsive */
    @media (max-width: 600px) {
      header h1 {
        font-size: 2em;
      }

      nav {
        flex-direction: column;
      }

      nav a {
        margin: 10px 0;
      }

      .profile-pic {
        width: 130px;
        height: 130px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Imtiaj Ahmed</h1>
    <p>Web Developer | C Programmer | Creative Designer</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <main>
    <section id="about">
      <img src="IMG_8154.jpg" alt="Imtiaj Ahmed" class="profile-pic" />
      <h2>About Me</h2>
      <p>Hi, I'm <strong>Imtiaj Ahmed</strong>, a passionate web developer and student from Bangladesh. I love coding in C and creating clean, responsive websites using HTML, CSS, and JavaScript. I’m always eager to learn and work on new and exciting projects.</p>
    </section>

    <section id="projects">
      <h2>My Projects</h2>
      <ul>
        <li><strong>Online Exam System</strong> – A C console app to take exams with file operations</li>
        <li><strong>Student Management System</strong> – File-based database system in C</li>
        <li><strong>Personal Portfolio Website</strong> – This portfolio made with HTML & CSS</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <p>Email: <a href="mailto:imtiaj@email.com">imtiaj@email.com</a></p>
      <p>Facebook: <a href="https://facebook.com/imtiaj.ahmed" target="_blank">facebook.com/imtiaj.ahmed</a></p>
      <p>GitHub: <a href="https://github.com/imtiajahmed" target="_blank">github.com/imtiajahmed</a></p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Imtiaj Ahmed. All rights reserved.</p>
  </footer>
</body>
</html>
