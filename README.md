<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sean T. Muponesi — Cybersecurity Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #0b556b;
      --secondary: #0fa3b1;
      --bg: #f1f5f9;
      --text: #1e293b;
      --light: #ffffff;
    }
    * {box-sizing: border-box; margin:0; padding:0;}
    body {font-family:'Inter',sans-serif;background:var(--bg);color:var(--text);line-height:1.6;}
    header {
      background:linear-gradient(135deg,var(--primary),var(--secondary));
      color:var(--light);
      padding:3rem 1rem;
      text-align:center;
    }
    header h1 {font-size:2.4rem;margin-bottom:.5rem;}
    header p {font-size:1.2rem;opacity:.95;}
    nav {
      background:var(--primary);
      text-align:center;
      padding:.8rem;
      position:sticky;
      top:0;
      z-index:10;
    }
    nav a {
      color:var(--light);
      margin:0 1rem;
      text-decoration:none;
      font-weight:600;
    }
    nav a:hover {text-decoration:underline;}
    section {
      max-width:1100px;
      margin:2rem auto;
      padding:0 1rem;
    }
    h2 {
      color:var(--primary);
      margin-bottom:.8rem;
      font-size:1.8rem;
      border-bottom:3px solid var(--secondary);
      display:inline-block;
      padding-bottom:.3rem;
    }
    .grid {
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
      gap:1.5rem;
    }
    .card {
      background:var(--light);
      border-radius:10px;
      padding:1rem;
      box-shadow:0 6px 14px rgba(0,0,0,0.08);
      transition:transform .2s, box-shadow .2s;
    }
    .card:hover {
      transform:translateY(-5px);
      box-shadow:0 8px 18px rgba(0,0,0,0.12);
    }
    footer {
      background:var(--primary);
      color:var(--light);
      text-align:center;
      padding:1rem;
      margin-top:3rem;
    }
    ul {margin-left:1rem;}
    a.btn {
      display:inline-block;
      background:var(--secondary);
      color:var(--light);
      padding:.6rem 1.2rem;
      border-radius:6px;
      text-decoration:none;
      font-weight:600;
      margin-top:.5rem;
    }
    a.btn:hover {background:#0c8691;}
  </style>
</head>
<body>

<header>
  <h1>Hello, I'm Sean Muponesi</h1>
  <p>Cybersecurity & Digital Forensics Student • Passionate Ethical Hacker • Based in Harare, Zimbabwe</p>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#projects">Projects</a>
  <a href="#skills">Skills</a>
  <a href="#goals">Future Goals</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about">
  <h2>About Me</h2>
  <p>I am a dedicated BSc Cybersecurity and Digital Forensics undergraduate at Arrupe Jesuit University. My academic journey includes an international exchange at Loyola University in Seville, Spain, where I collaborated on an AI innovation project that broadened my perspective on global cybersecurity challenges.</p>
  <p>My passion lies in securing networks, uncovering vulnerabilities, and building robust solutions. I’ve gained practical experience in system administration, secure coding, and malware analysis. Beyond academics, I value teamwork, knowledge sharing, and staying ahead of emerging threats in this ever-changing field.</p>
</section>

<section id="projects">
  <h2>Projects</h2>
  <div class="grid">
    <div class="card">
      <h3>System Administration</h3>
      <p>Designed and deployed a secure enterprise network infrastructure using Linux and Windows servers, firewalls, IDS/IPS, and automated audits for compliance.</p>
    </div>
    <div class="card">
      <h3>Secure Coding</h3>
      <p>Performed vulnerability scanning and implemented secure coding practices using OWASP ZAP and Bandit, preventing exploits like SQL injection and XSS.</p>
    </div>
    <div class="card">
      <h3>Innovation Project (Spain Exchange)</h3>
      <p>Built an AI-powered multimodal route advisor for tourists in Seville, integrating real-time transit data to improve travel efficiency.</p>
    </div>
    <div class="card">
      <h3>Operating System Scheduling</h3>
      <p>Implemented and analyzed five CPU scheduling algorithms in C on Kali Linux, comparing performance, fairness, and efficiency.</p>
    </div>
    <div class="card">
      <h3>Python Malware Detection</h3>
      <p>Developed a heuristic-based malware detection application using hashing analysis to identify malicious files and behaviors.</p>
    </div>
  </div>
</section>

<section id="skills">
  <h2>Technical Skills</h2>
  <ul>
    <li><strong>Programming & Scripting:</strong> Python (Malware Detection, Automation), Bash</li>
    <li><strong>Security Tools:</strong> Nmap, Metasploit, Burp Suite, Nessus</li>
    <li><strong>Forensic Tools:</strong> Autopsy, FTK Imager, Wireshark</li>
    <li><strong>OS & Platforms:</strong> Linux (Kali, Ubuntu), Windows, Android</li>
    <li><strong>Core Concepts:</strong> Network Defense, Cryptography, Threat Analysis, Digital Evidence Handling, GDPR Compliance, Ethical Hacking</li>
    <li><strong>Soft Skills:</strong> Analytical Thinking, Problem Solving, Teamwork, Communication</li>
  </ul>
</section>

<section id="goals">
  <h2>Future Goals</h2>
  <p>As I progress in my studies and projects, my aim is to grow into a versatile cybersecurity professional who can tackle advanced security challenges. My future goals include:</p>
  <ul>
    <li>Mastering advanced penetration testing, threat hunting, and digital forensics techniques.</li>
    <li>Contributing to open-source security tools and writing technical blogs to share knowledge with the community.</li>
    <li>Securing internships with forward-thinking organizations to apply my skills in real-world environments.</li>
    <li>Exploring AI and IoT security to help organizations defend against emerging cyber threats.</li>
    <li>Mentoring peers and leading workshops to inspire the next generation of cybersecurity enthusiasts.</li>
  </ul>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>I’m eager to collaborate on innovative projects or explore internship opportunities. Let’s connect!</p>
  <p>Email: <a href="mailto:seanmuponesi50@gmail.com">seanmuponesi50@gmail.com</a></p>
  <p>LinkedIn: <a href="https://linkedin.com/in/sean-muponesi-460590334" target="_blank">linkedin.com/in/sean-muponesi-460590334</a></p>
  <p>GitHub: <a href="https://github.com/SeanMUPO" target="_blank">github.com/SeanMUPO</a></p>
  <a class="btn" href="Sean_Muponesi_CV.pdf" download>Download My CV</a>
</section>

<footer>
  © 2025 Sean Tadiwanashe Muponesi — Passion for Cybersecurity and Innovation
</footer>

</body>
</html>
