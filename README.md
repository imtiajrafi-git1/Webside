<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet" />
  <!-- Font Awesome for icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" />
  <style>
    body {
      font-family: 'Inter', sans-serif;
    }
    .bg-pattern {
      background-image: linear-gradient(to right, #4a5568 1px, transparent 1px),
        linear-gradient(to bottom, #4a5568 1px, transparent 1px);
      background-size: 20px 20px;
    }
  </style>
</head>
<body class="bg-gray-900 text-gray-100">

  <!-- Header Section -->
  <header class="bg-gray-800 shadow-lg sticky top-0 z-50">
    <nav class="container mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
      <a href="#" class="text-2xl font-bold text-teal-400">My Name</a>
      <div class="hidden md:flex space-x-6">
        <a href="#home" class="text-gray-300 hover:text-teal-400 transition-colors duration-300">Home</a>
        <a href="#about" class="text-gray-300 hover:text-teal-400 transition-colors duration-300">About</a>
        <a href="#projects" class="text-gray-300 hover:text-teal-400 transition-colors duration-300">Projects</a>
        <a href="#contact" class="text-gray-300 hover:text-teal-400 transition-colors duration-300">Contact</a>
      </div>
      <button id="menu-button" class="md:hidden text-gray-300 hover:text-teal-400 focus:outline-none">
        <i class="fas fa-bars text-xl"></i>
      </button>
    </nav>
    <!-- Mobile Menu -->
    <div id="mobile-menu" class="hidden md:hidden bg-gray-800">
      <a href="#home" class="block py-2 px-4 text-gray-300 hover:bg-gray-700 hover:text-teal-400 transition-colors duration-300">Home</a>
      <a href="#about" class="block py-2 px-4 text-gray-300 hover:bg-gray-700 hover:text-teal-400 transition-colors duration-300">About</a>
      <a href="#projects" class="block py-2 px-4 text-gray-300 hover:bg-gray-700 hover:text-teal-400 transition-colors duration-300">Projects</a>
      <a href="#contact" class="block py-2 px-4 text-gray-300 hover:bg-gray-700 hover:text-teal-400 transition-colors duration-300">Contact</a>
    </div>
  </header>

  <!-- Main Content -->
  <main class="min-h-screen">

    <!-- Hero Section -->
    <section id="home" class="py-20 md:py-32 flex flex-col md:flex-row items-center justify-center bg-gray-900 text-center md:text-left px-4">
      <div class="md:w-1/2 flex justify-center md:justify-end mb-8 md:mb-0">
        <div class="relative w-48 h-48 md:w-64 md:h-64 rounded-full overflow-hidden border-4 border-teal-400 shadow-xl">
          <img src="https://placehold.co/256x256/2d3748/e2e8f0?text=Your+Photo" alt="Your Photo" class="w-full h-full object-cover" />
        </div>
      </div>
      <div class="md:w-1/2 md:pl-16">
        <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold text-white leading-tight mb-4">
          Hi, I’m <span class="text-teal-400">Your Name</span>
        </h1>
        <p class="text-lg md:text-xl text-gray-400 mb-6 max-w-xl">
          A passionate software developer focused on creating modern and functional web applications.
        </p>
        <div class="flex justify-center md:justify-start space-x-4">
          <a href="#projects" class="bg-teal-500 hover:bg-teal-600 text-white font-semibold py-3 px-6 rounded-full transition-colors duration-300 shadow-md">
            View My Work
          </a>
          <a href="#contact" class="bg-gray-700 hover:bg-gray-600 text-white font-semibold py-3 px-6 rounded-full transition-colors duration-300 shadow-md">
            Contact Me
          </a>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 md:py-24 bg-gray-800 px-4">
      <div class="container mx-auto">
        <h2 class="text-3xl sm:text-4xl font-bold text-center mb-12 text-white">About Me</h2>
        <div class="md:flex md:space-x-12">
          <div class="md:w-1/2 mb-8 md:mb-0">
            <p class="text-gray-400 text-lg mb-4">
              Hi, I'm [Your Name]. I’m a software engineering student and professional web developer. I love learning new technologies and solving real-life problems with them.
            </p>
            <p class="text-gray-400 text-lg">
              My technical skills include <strong>HTML, CSS, JavaScript</strong> and frameworks like <strong>React.js</strong>. I also work with back-end technologies like <strong>Node.js</strong> and <strong>MongoDB</strong>. I'm enthusiastic about contributing to open-source and always ready to learn something new.
            </p>
          </div>
          <div class="md:w-1/2">
            <div class="grid grid-cols-2 gap-4">
              <div class="p-6 bg-gray-900 rounded-lg shadow-lg transform transition-transform duration-300 hover:scale-105">
                <i class="fas fa-code text-teal-400 text-3xl mb-4"></i>
                <h3 class="text-xl font-semibold mb-2">Front-End</h3>
                <p class="text-gray-400">HTML, CSS, Tailwind CSS, JavaScript, React.js</p>
              </div>
              <div class="p-6 bg-gray-900 rounded-lg shadow-lg transform transition-transform duration-300 hover:scale-105">
                <i class="fas fa-server text-teal-400 text-3xl mb-4"></i>
                <h3 class="text-xl font-semibold mb-2">Back-End</h3>
                <p class="text-gray-400">Node.js, Express.js</p>
              </div>
              <div class="p-6 bg-gray-900 rounded-lg shadow-lg transform transition-transform duration-300 hover:scale-105">
                <i class="fas fa-database text-teal-400 text-3xl mb-4"></i>
                <h3 class="text-xl font-semibold mb-2">Database</h3>
                <p class="text-gray-400">MongoDB</p>
              </div>
              <div class="p-6 bg-gray-900 rounded-lg shadow-lg transform transition-transform duration-300 hover:scale-105">
                <i class="fas fa-tools text-teal-400 text-3xl mb-4"></i>
                <h3 class="text-xl font-semibold mb-2">Tools</h3>
                <p class="text-gray-400">Git, GitHub, VS Code</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-20 md:py-24 px-4 bg-gray-900">
      <div class="container mx-auto">
        <h2 class="text-3xl sm:text-4xl font-bold text-center mb-12 text-white">My Projects</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">

          <!-- Project Card -->
          <div class="bg-gray-800 rounded-xl shadow-lg overflow-hidden transform transition-transform duration-300 hover:scale-105">
            <img src="https://placehold.co/600x400/1f2937/d1d5db?text=Project+1" alt="Project 1" class="w-full h-48 object-cover" />
            <div class="p-6">
              <h3 class="text-2xl font-bold mb-2 text-white">Project Title</h3>
              <p class="text-gray-400 mb-4">This project was developed to solve [main objective]. It uses my [specific skill] to provide an effective solution.</p>
              <div class="flex space-x-4">
                <a href="#" class="text-teal-400 hover:text-teal-300 font-semibold">
                  <i class="fas fa-external-link-alt mr-2"></i>Live Demo
                </a>
                <a href="#" class="text-gray-400 hover:text-gray-300 font-semibold">
                  <i class="fab fa-github mr-2"></i>GitHub
                </a>
              </div>
            </div>
          </div>

          <!-- Repeat Project Cards for Project 2 & 3 -->
          <!-- ... -->

        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 md:py-24 bg-gray-800 px-4">
      <div class="container mx-auto">
        <h2 class="text-3xl sm:text-4xl font-bold text-center mb-12 text-white">Contact</h2>
        <div class="max-w-lg mx-auto">
          <p class="text-center text-gray-400 mb-8">
            If you have any questions or are interested in working with me, please fill out the form below or email me directly.
          </p>
          <form class="space-y-6">
            <div>
              <label for="name" class="block text-gray-300 mb-2">Your Name</label>
              <input type="text" id="name" name="name" placeholder="Your Name" class="w-full p-3 rounded-lg bg-gray-900 border border-gray-700 focus:outline-none focus:ring-2 focus:ring-teal-500 text-white" />
            </div>
            <div>
              <label for="email" class="block text-gray-300 mb-2">Your Email</label>
              <input type="email" id="email" name="email" placeholder="Your Email" class="w-full p-3 rounded-lg bg-gray-900 border border-gray-700 focus:outline-none focus:ring-2 focus:ring-teal-500 text-white" />
            </div>
            <div>
              <label for="message" class="block text-gray-300 mb-2">Your Message</label>
              <textarea id="message" name="message" rows="5" placeholder="Your Message" class="w-full p-3 rounded-lg bg-gray-900 border border-gray-700 focus:outline-none focus:ring-2 focus:ring-teal-500 text-white"></textarea>
            </div>
            <button type="submit" class="w-full bg-teal-500 hover:bg-teal-600 text-white font-semibold py-3 px-4 rounded-full transition-colors duration-300 shadow-md">
              Send Message
            </button>
          </form>
        </div>
      </div>
    </section>
  </main>

  <!-- Footer -->
  <footer class="bg-gray-900 py-8 border-t border-gray-700">
    <div class="container mx-auto text-center px-4">
      <p class="text-gray-400">&copy; 2024 My Name. All rights reserved.</p>
      <div class="mt-4 space-x-4">
        <a href="#" class="text-gray-400 hover:text-teal-400 transition-colors duration-300">
          <i class="fab fa-linkedin text-2xl"></i>
        </a>
        <a href="#" class="text-gray-400 hover:text-teal-400 transition-colors duration-300">
          <i class="fab fa-github text-2xl"></i>
        </a>
        <a href="#" class="text-gray-400 hover:text-teal-400 transition-colors duration-300">
          <i class="fab fa-twitter text-2xl"></i>
        </a>
      </div>
    </div>
  </footer>

  <!-- JavaScript for smooth scrolling and mobile menu -->
  <script>
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
          behavior: 'smooth'
        });
        const mobileMenu = document.getElementById('mobile-menu');
        if (!mobileMenu.classList.contains('hidden')) {
          mobileMenu.classList.add('hidden');
        }
      });
    });

    const menuButton = document.getElementById('menu-button');
    menuButton.addEventListener('click', () => {
      const menu = document.getElementById('mobile-menu');
      menu.classList.toggle('hidden');
    });
  </script>

</body>
</html>
