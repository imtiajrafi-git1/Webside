<!DOCTYPE html>
<html lang="en" data-theme="light">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Imtiaj Ahmed - Portfolio</title>
  
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- AOS (Animate On Scroll) CSS -->
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

  <!-- Font Awesome for Social Icons -->
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>

  <style>
    body { padding-top: 64px; transition: background-color 0.3s, color 0.3s;}
    [data-theme="dark"] {
      background-color: #1a202c; /* Tailwind gray-900 */
      color: #a0aec0; /* Tailwind gray-400 */
    }
    [data-theme="dark"] a {
      color: #63b3ed; /* Tailwind blue-400 */
    }
    [data-theme="dark"] .bg-white { background-color: #2d3748; }
    [data-theme="dark"] .bg-gray-50 { background-color: #2d3748; }
    [data-theme="dark"] .bg-gray-100 { background-color: #4a5568; }
  </style>
</head>
<body class="bg-gray-100 text-gray-800 font-sans">

  <!-- Navbar -->
  <nav class="bg-white shadow fixed w-full top-0 left-0 z-50">
    <div class="max-w-6xl mx-auto px-4 py-4 flex justify-between items-center">
      <a href="#" class="text-blue-900 font-bold text-xl">Imtiaj</a>
      <div class="space-x-6 text-gray-700 flex items-center">
        <a href="#about" class="hover:text-blue-900">About</a>
        <a href="#education" class="hover:text-blue-900">Education</a>
        <a href="#achievements" class="hover:text-blue-900">Achievements</a>
        <a href="#projects" class="hover:text-blue-900">Projects</a>
        <a href="#testimonials" class="hover:text-blue-900">Testimonials</a>
        <a href="#blog" class="hover:text-blue-900">Blog</a>
        <a href="#contact" class="hover:text-blue-900">Contact</a>

        <!-- Language Toggle -->
        <button id="langToggle" class="ml-4 px-2 py-1 border rounded hover:bg-blue-100">বাংলা</button>

        <!-- Dark Mode Toggle -->
        <button id="themeToggle" class="ml-4 px-2 py-1 border rounded hover:bg-blue-100">
          🌙
        </button>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="bg-blue-900 text-white py-20 text-center" data-aos="fade-up">
    <h1 class="text-4xl font-bold mb-4" data-en="I'm Imtiaj Ahmed" data-bn="আমি ইমতিয়াজ আহমেদ">I'm Imtiaj Ahmed</h1>
    <p class="text-xl" data-en="Web Developer | Designer | Freelancer" data-bn="ওয়েব ডেভেলপার | ডিজাইনার | ফ্রিল্যান্সার">Web Developer | Designer | Freelancer</p>
    <div class="mt-6">
      <a href="#contact" class="bg-white text-blue-900 px-6 py-2 rounded-full font-semibold" data-en="Contact Me" data-bn="যোগাযোগ করুন">Contact Me</a>
    </div>
  </section>

  <!-- About Me -->
  <section id="about" class="py-16 px-6 max-w-4xl mx-auto" data-aos="fade-right">
    <h2 class="text-3xl font-bold mb-4 text-center" data-en="About Me" data-bn="আমার সম্পর্কে">About Me</h2>
    <p class="text-lg text-center" data-en="I am an enthusiastic web developer experienced in creating websites, web applications, and UI/UX designs. I am always ready to learn something new and take on new challenges." data-bn="আমি একজন উদ্যমী ওয়েব ডেভেলপার, যিনি ওয়েবসাইট, ওয়েব অ্যাপ এবং UI/UX ডিজাইন তৈরি করতে অভিজ্ঞ। আমি সবসময় নতুন কিছু শেখার এবং নতুন চ্যালেঞ্জ গ্রহণ করার জন্য প্রস্তুত।">
      I am an enthusiastic web developer experienced in creating websites, web applications, and UI/UX designs. I am always ready to learn something new and take on new challenges.
    </p>
  </section>

  <!-- Education -->
  <section id="education" class="py-16 px-6 bg-white" data-aos="fade-left">
    <h2 class="text-3xl font-bold text-center mb-10" data-en="Educational Qualifications" data-bn="শিক্ষাগত যোগ্যতা">Educational Qualifications</h2>
    <div class="max-w-4xl mx-auto space-y-6">
      
      <div class="bg-gray-100 p-6 rounded shadow">
        <h3 class="text-xl font-semibold" data-en="B.Sc. in Software Engineering" data-bn="সফটওয়্যার ইঞ্জিনিয়ারিংয়ে বি.এস.সি">B.Sc. in Software Engineering</h3>
        <p class="text-gray-700" data-en="Daffodil International University" data-bn="ড্যাফোডিল ইন্টারন্যাশনাল ইউনিভার্সিটি">Daffodil International University</p>
        <span class="text-sm text-gray-500" data-en="2024 - Ongoing" data-bn="২০২৪ - চলমান">2024 - Ongoing</span>
      </div>
      
      <div class="bg-gray-100 p-6 rounded shadow">
        <h3 class="text-xl font-semibold" data-en="Higher Secondary School Certificate (HSC)" data-bn="এইচ.এস.সি (উচ্চ মাধ্যমিক)">Higher Secondary School Certificate (HSC)</h3>
        <p class="text-gray-700" data-en="Milestone College" data-bn="মাইলস্টোন কলেজ">Milestone College</p>
        <span class="text-sm text-gray-500" data-en="2019" data-bn="২০১৯">2019</span>
      </div>
      
      <div class="bg-gray-100 p-6 rounded shadow">
        <h3 class="text-xl font-semibold" data-en="Secondary School Certificate (SSC)" data-bn="এস.এস.সি (মাধ্যমিক)">Secondary School Certificate (SSC)</h3>
        <p class="text-gray-700" data-en="Hirapur Ideal High School & College" data-bn="হিরাপুর আইডিয়াল হাই স্কুল এন্ড কলেজ">Hirapur Ideal High School & College</p>
        <span class="text-sm text-gray-500" data-en="2017" data-bn="২০১৭">2017</span>
      </div>

    </div>
  </section>

  <!-- Achievements -->
  <section id="achievements" class="py-16 px-6 bg-gray-50" data-aos="fade-up">
    <h2 class="text-3xl font-bold text-center mb-10" data-en="Achievements & Certifications" data-bn="অর্জন ও সনদপত্র">Achievements & Certifications</h2>
    <div class="max-w-4xl mx-auto space-y-4">
      <div class="bg-white p-6 rounded shadow">
        <h3 class="font-semibold text-lg" data-en="Certified Front-End Developer" data-bn="সার্টিফায়েড ফ্রন্ট-এন্ড ডেভেলপার">Certified Front-End Developer</h3>
        <p class="text-sm text-gray-600" data-en="Meta, 2024" data-bn="মেটা, ২০২৪">Meta, 2024</p>
      </div>
      <div class="bg-white p-6 rounded shadow">
        <h3 class="font-semibold text-lg" data-en="Complete Web Development" data-bn="কমপ্লিট ওয়েব ডেভেলপমেন্ট">Complete Web Development</h3>
        <p class="text-sm text-gray-600" data-en="Programming Hero, 2023" data-bn="প্রোগ্রামিং হিরো, ২০২৩">Programming Hero, 2023</p>
      </div>
    </div>
  </section>

  <!-- Skills with Progress Bars -->
  <section class="bg-white py-16 px-6" data-aos="fade-right">
    <h2 class="text-3xl font-bold text-center mb-8" data-en="Skills" data-bn="দক্ষতা">Skills</h2>
    <div class="max-w-4xl mx-auto space-y-6">

      <div>
        <label class="block mb-1" data-en="HTML" data-bn="এইচটিএমএল">HTML</label>
        <div class="w-full bg-gray-200 rounded-full h-4">
          <div class="bg-blue-900 h-4 rounded-full" style="width: 90%"></div>
        </div>
      </div>

      <div>
        <label class="block mb-1" data-en="CSS" data-bn="সিএসএস">CSS</label>
        <div class="w-full bg-gray-200 rounded-full h-4">
          <div class="bg-blue-900 h-4 rounded-full" style="width: 85%"></div>
        </div>
      </div>

      <div>
        <label class="block mb-1" data-en="JavaScript" data-bn="জাভাস্ক্রিপ্ট">JavaScript</label>
        <div class="w-full bg-gray-200 rounded-full h-4">
          <div class="bg-blue-900 h-4 rounded-full" style="width: 75%"></div>
        </div>
      </div>

      <div>
        <label class="block mb-1" data-en="Tailwind CSS" data-bn="টেইলউইন্ড সিএসএস">Tailwind CSS</label>
        <div class="w-full bg-gray-200 rounded-full h-4">
          <div class="bg-blue-900 h-4 rounded-full" style="width: 70%"></div>
        </div>
      </div>

    </div>
  </section>

  <!-- Projects with Filtering -->
  <section id="projects" class="py-16 px-6 bg-gray-50" data-aos="fade-left">
    <h2 class="text-3xl font-bold text-center mb-8" data-en="Projects" data-bn="প্রজেক্টস">Projects</h2>
    
    <!-- Filter Buttons -->
    <div class="flex justify-center gap-4 mb-10">
      <button class="filter-btn px-4 py-2 bg-blue-900 text-white rounded" data-filter="all">All</button>
      <button class="filter-btn px-4 py-2 border border-blue-900 text-blue-900 rounded" data-filter="web">Web</button>
      <button class="filter-btn px-4 py-2 border border-blue-900 text-blue-900 rounded" data-filter="mobile">Mobile</button>
      <button class="filter-btn px-4 py-2 border border-blue-900 text-blue-900 rounded" data-filter="design">Design</button>
    </div>

    <div class="max-w-5xl mx-auto grid md:grid-cols-2 gap-6">
      <div class="project-item bg-white p-6 rounded shadow" data-category="web">
        <h3 class="font-bold text-xl mb-2">Responsive Website</h3>
        <p>Built with HTML, CSS, and JavaScript.</p>
      </div>
      <div class="project-item bg-white p-6 rounded shadow" data-category="mobile">
        <h3 class="font-bold text-xl mb-2">Mobile App UI</h3>
        <p>Designed interactive mobile user interfaces.</p>
      </div>
      <div class="project-item bg-white p-6 rounded shadow" data-category="design">
        <h3 class="font-bold text-xl mb-2">Logo Design</h3>
        <p>Created branding logo for clients.</p>
      </div>
      <div class="project-item bg-white p-6 rounded shadow" data-category="web">
        <h3 class="font-bold text-xl mb-2">Portfolio Site</h3>
        <p>Interactive portfolio showcasing works.</p>
      </div>
    </div>
  </section>

  <!-- Testimonials -->
  <section id="testimonials" class="py-16 px-6 bg-white" data-aos="fade-up">
    <h2 class="text-3xl font-bold text-center mb-10" data-en="What People Say" data-bn="ক্লায়েন্টদের মতামত">What People Say</h2>
    <div class="max-w-3xl mx-auto space-y-6">
      <div class="bg-gray-100 p-6 rounded shadow italic">
        “Imtiaj did a great job on my website. Highly professional and punctual.” – <strong>Client A</strong>
      </div>
      <div class="bg-gray-100 p-6 rounded shadow italic">
        “Very skilled and communicates well. Will hire again.” – <strong>Client B</strong>
      </div>
    </div>
  </section>

  <!-- Blog -->
  <section id="blog" class="py-16 px-6 bg-gray-50" data-aos="fade-right">
    <h2 class="text-3xl font-bold text-center mb-10" data-en="Latest Articles" data-bn="সর্বশেষ নিবন্ধ">Latest Articles</h2>
    <div class="max-w-4xl mx-auto grid gap-6 md:grid-cols-2">
      <div class="bg-white p-6 rounded shadow">
        <h3 class="text-xl font-semibold mb-2">How I Built My Portfolio Website</h3>
        <p class="text-sm text-gray-600">July 2025</p>
      </div>
      <div class="bg-white p-6 rounded shadow">
        <h3 class="text-xl font-semibold mb-2">Top 5 Tools Every Developer Should Use</h3>
        <p class="text-sm text-gray-600">June 2025</p>
      </div>
    </div>
  </section>

  <!-- Download Resume -->
  <section class="text-center py-10 bg-white" data-aos="zoom-in">
    <a href="resume.pdf" download
       class="inline-block bg-blue-900 text-white px-8 py-3 rounded-full font-semibold hover:bg-blue-800 transition">
      Download My Resume
    </a>
  </section>

  <!-- Google Maps -->
  <section id="location" class="py-16 px-6 max-w-4xl mx-auto" data-aos="fade-up">
    <h2 class="text-3xl font-bold text-center mb-8" data-en="My Location" data-bn="আমার অবস্থান">My Location</h2>
    <div id="map" class="w-full h-64 rounded shadow"></div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-16 px-6 bg-blue-900 text-white" data-aos="fade-up">
    <h2 class="text-3xl font-bold text-center mb-8" data-en="Contact Me" data-bn="যোগাযোগ করুন">Contact Me</h2>
    <form action="contact-form-handler.php" method="POST" class="max-w-lg mx-auto grid gap-4">
      <input type="text" name="name" placeholder="Your Name" class="p-3 rounded text-black" required />
      <input type="email" name="email" placeholder="Your Email" class="p-3 rounded text-black" required />
      <textarea name="message" placeholder="Your Message" rows="5" class="p-3 rounded text-black" required></textarea>
      <button type="submit" class="bg-white text-blue-900 px-6 py-2 rounded font-semibold hover:bg-gray-200 transition">Send</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 text-white text-center py-4">
    &copy; 2025 Imtiaj Ahmed. All rights reserved.
    <div class="mt-2 space-x-4">
      <!-- Social Icons -->
      <a href="https://github.com/imtiaj" target="_blank" aria-label="GitHub" class="hover:text-gray-400">
        <i class="fab fa-github fa-lg"></i>
      </a>
      <a href="https://linkedin.com/in/imtiaj" target="_blank" aria-label="LinkedIn" class="hover:text-gray-400">
        <i class="fab fa-linkedin fa-lg"></i>
      </a>
      <a href="https://twitter.com/imtiaj" target="_blank" aria-label="Twitter" class="hover:text-gray-400">
        <i class="fab fa-twitter fa-lg"></i>
      </a>
    </div>
  </footer>

  <!-- Scripts -->

  <!-- AOS Animation -->
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init({
      duration: 800,
      easing: 'ease-in-out',
      once: true,
    });
  </script>

  <!-- Dark Mode Toggle Script -->
  <script>
    const themeToggle = document.getElementById('themeToggle');
    const htmlEl = document.documentElement;

    // Load saved theme
    if(localStorage.getItem('theme') === 'dark'){
      htmlEl.setAttribute('data-theme',
