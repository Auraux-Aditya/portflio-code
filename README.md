# portflio-code
this code of my index page

<!DOCTYPE html>
<html>
<head>
    <title>Aditya Portfolio</title>
</head>
<body>

<nav class="navbar">
    <div class="nav-logo">
        <a href="index.html"><span>&lt;/&gt;</span>Aditya Portfolio</a>
    </div>

    <div class="nav-links">

    <a href="index.html">Home</a>
    <a href="about.html">About Me</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
    </div>
</nav>

   <div class="search-box">
    <input type="text" id="searchInput" placeholder="Search...">
    <button onclick="searchPage()">Search</button>
</div>

<script>
function searchPage() {
    let search = document.getElementById("searchInput").value.toLowerCase();

    if (search === "home") {
        window.location.href = "index.html";
    }
    else if (search === "about") {
        window.location.href = "about.html";
    }
    else if (search === "projects") {
        window.location.href = "projects.html";
    }
    else if (search === "contact") {
        window.location.href = "contact.html";
    }
    else {
        alert("Page not found!");
    }
}
</script>


    
<link rel="stylesheet" href="style.css">


</body>
</html>
</nav>



<link rel="stylesheet" href="style.css">

<main>
    <h1>Welcome To Aditya Portfolio</h1>
    
    <p>Hi, my name is Aditya. I am a student and web developer.</p>
    
    
<div class="button-group">
    <a href="contact.html">
        <button class="btn-primary">Contact Me</button>
    </a>

    <a href="projects.html">
        <button class="btn-secondary">Explore Projects</button>
    </a>
</div>
<h2>Learn <span id="changing-text"></span><span class="cursor">|</span></h2>
<script src="script.js"></script>

<div class="video-container">
    

    <section class="courses-section">
    <h2 class="section-title">Code Smarter with Real-World Practice</h2>
    
    <div class="courses-grid">
        <div class="project-card course-item">
            <div class="card-image">
                <img src="https://images.unsplash.com/photo-1547082299-de196ea013d6?q=80&w=600&auto=format&fit=crop" alt="Web Development">
            </div>
            <div class="card-content">
                <h3>Web Development</h3>
                
            </div>
        </div>

        <div class="project-card course-item">
            <div class="card-image">
                <img src="https://images.unsplash.com/photo-1515879218367-8466d910aaa4?q=80&w=600&auto=format&fit=crop" alt="Data Science">
            </div>
            <div class="card-content">
                <h3>Data Science & AI</h3>
                
            </div>
        </div>

        <div class="project-card course-item">
            <div class="card-image">
                <img src="https://images.unsplash.com/photo-1607799279861-4dd421887fb3?q=80&w=600&auto=format&fit=crop" alt="DSA">
            </div>
            <div class="card-content">
                <h3>Data Structures & Algorithms</h3>
                
            </div>
        </div>
    </div>
</section>

<video src="video4.mp4" height="1%" controls loop width="30%"></video>


<img src="image6.jpeg" height="1%" width="25%">

</div>
<section class="hero-section">
  <div class="hero-content">
   <section class="stats-section">
  </section>

<section class="hero-section">
  
  

<div class="companies-section">
    
    <div class="companies-grid">
        <div class="company-card">Amazon</div>
        <div class="company-card">Google</div>
        <div class="company-card">Microsoft</div>
        <div class="company-card">Goldman Sachs</div>
        <div class="company-card">PayPal</div>
        <div class="company-card">Samsung</div>

        <div class="company-card">EY</div>
        <div class="company-card">Hitachi</div>
        <div class="company-card">JPMorgan</div>
        <div class="company-card">IBM</div>
        <div class="company-card">Dell</div>
        <div class="company-card">Deloitte</div>
    </div>

    <p>
        <h1>
        building a personal portfolio website for web development, here are a few
        that company section to keep your visitors engaged:
        </h1>
    </p>
    <p>
        <h3>
            Hello! My name is Aditya, and I am a student and aspiring web developer. I have a strong interest in technology, programming, and creating websites. I enjoy learning new skills and challenging myself with different web development projects.

I build websites using HTML, CSS, and JavaScript, and I use Visual Studio Code as my main code editor. Through practice and self-learning, I have developed the ability to create responsive and user-friendly websites. I am constantly exploring new tools, techniques, and technologies to improve my coding skills and become a better developer.

My journey in web development started with simple web pages, and over time I learned how to design layouts, add navigation menus, create forms, embed videos, and build multi-page websites. Every project teaches me something new and helps me gain more experience.

Apart from coding, I enjoy solving problems, learning about computers, and working on creative ideas. My goal is to become a professional full-stack web developer and create websites and applications that are useful, modern, and accessible to everyone.

Thank you for visiting my portfolio website. Feel free to explore my projects and follow my journey as I continue learning, growing, and building exciting web development projects.
        </h3>
    </p>
</div>

</div>
<section class="courses-section">
    <h2 class="section-title">Code Starting</h2>
    
    <div class="courses-grid">
        <div class="project-card course-item">
            <div class="card-image">
                <video src="video3.mp4" autoplay loop muted playsinline></video>
            </div>
            <div class="card-content">
                <h3>Web Development</h3>
                
            </div>
        </div>

        <div class="project-card course-item">
            <div class="card-image">
                <video src="video2.mp4" autoplay loop muted playsinline></video>
            </div>
            <div class="card-content">
                <h3>Data Science & AI</h3>
                
            </div>
        </div>

        <div class="project-card course-item">
            <div class="card-image">
                <video src="Video1.mp4" autoplay loop muted playsinline></video>
            </div>
            <div class="card-content">
                <h3>Data Structures & Algorithms</h3>
                
            </div>
        </div>
    </div>
</section>
<section class="testimonials-section">
  <h2>Testimonials</h2>
  
  <div class="testimonials-container">
    
    <div class="testimonial-card">
      <span class="quote-mark">testimonials</span>
      <p>I am Aditya, a passionate web developer and student who enjoys creating modern and responsive websites. I am currently learning HTML, CSS, JavaScript, and Java. My goal is to improve my coding skills every day and build creative projects that help me become a professional developer in the future.</p>
      <h4>Aditya jha</h4>
      <span>Web Developer</span>
    </div>

    <div class="testimonial-card">
      <span class="quote-mark">testimonials</span>
      <p>Passionate about coding, web design, and continuous learning. I am dedicated to improving my skills and building projects that make a positive impact....</p>
      <h4>Aditya jha</h4>
      <span>Web Developer</span>
    </div>

  </div>
</section>
<footer>
    <div class="footer-container">

        <div>
            <h3>Main</h3>
            <a href="index.html">Home</a><br>
            <a href="contact.html">Contact</a><br>
            <a href="projects.html">Projects</a><br>
            <a href="about.html">About me</a>
        </div>

        <div>
            <h3> What I Learn</h3>
            <a href="https://www.java.com/en/download/">Java</a><br>
            <a href="https://en.wikipedia.org/wiki/HTML">HTML</a><br>
            <a href="https://www.w3schools.com/Css/">CSS</a>
        </div>

        <div>
            <h3>Legal</h3>
            <a href="Terms.html">Terms</a><br>
            <a href="privacy.html">Privacy</a><br>
            <a href="Refund.html">Refund</a>
        </div>

        <div>
            <h3>Social</h3>
            <a href="#">YouTube</a><br>
            <a href="https://github.com/Auraux-Aditya">GitHub</a><br>
            <a href="https://www.instagram.com/aurexil_aditya?igsh=YThveWNxbjZpcHB5">Instagram</a>
        </div>

    </div>

    <p class="footer-text">Made with ❤️ by Aditya</p>
</footer>

</body>
</html>      
    


