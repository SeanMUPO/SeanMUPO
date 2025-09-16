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
    * {box-sizing:border-box;margin:0;padding:0;}
    body {font-family:'Inter',sans-serif;background:var(--bg);color:var(--text);line-height:1.6;}
    header {background:linear-gradient(135deg,var(--primary),var(--secondary));color:var(--light);padding:3rem 1rem;text-align:center;}
    header h1 {font-size:2.4rem;margin-bottom:.5rem;}
    header p {font-size:1.2rem;opacity:.95;}
    nav {background:var(--primary);text-align:center;padding:.8rem;position:sticky;top:0;z-index:10;}
    nav a {color:var(--light);margin:0 1rem;text-decoration:none;font-weight:600;}
    nav a:hover {text-decoration:underline;}
    section {max-width:1100px;margin:2rem auto;padding:0 1rem;}
    h2 {color:var(--primary);margin-bottom:.8rem;font-size:1.8rem;border-bottom:3px solid var(--secondary);display:inline-block;padding-bottom:.3rem;}
    .grid {display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:1.5rem;}
    .card {background:var(--light);border-radius:10px;padding:1rem;box-shadow:0 6px 14px rgba(0,0,0,0.08);transition:transform .2s,box-shadow .2s;}
    .card:hover {transform:translateY(-5px);box-shadow:0 8px 18px rgba(0,0,0,0.12);}
    footer {background:var(--primary);color:var(--light);text-align:center;padding:1rem;margin-top:3rem;}
    ul {margin-left:1rem;}
    a.btn {display:inline-block;background:var(--secondary);color:var(--light);padding:.6rem 1.2rem;border-radius:6px;text-decoration:none;font-weight:600;margin-top:.5rem;}
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
  <p>I am a BSc Cybersecurity and Digital Forensics undergraduate at Arrupe Jesuit University. I participated in an international exchange at Loyola University in Seville, Spain, collaborating on an AI innovation project that expanded my understanding of global cybersecurity challenges. I am passionate about ethical hacking, malware detection, and secure network design.</p>
</section>

<section id="projects">
  <h2>Projects</h2>
  <div class="grid">
    <div class="card">
      <h3>System Administration</h3>
      <p>Designed and deployed a secure enterprise network infrastructure with Linux and Windows servers, firewalls, IDS/IPS, and automated compliance audits.</p>
    </div>
    <div class="card">
      <h3>Secure Coding</h3>
      <p>Performed vulnerability scanning and implemented secure coding practices using OWASP ZAP and Bandit, mitigating risks like SQL injection and XSS.</p>
    </div>
    <div class="card">
      <h3>Innovation Project (Spain)</h3>
      <p>Built an AI-powered multimodal route advisor for tourists in Seville, integrating real-time transit data for improved travel efficiency.</p>
    </div>
    <div class="card">
      <h3>Operating System Scheduling</h3>
      <p>Implemented and compared five CPU scheduling algorithms in C on Kali Linux, analyzing performance and fairness.</p>
    </div>
  </div>
</section>

<section id="skills">
  <h2>Technical Skills</h2>
  <ul>
    <li>Python (Malware Detection, Automation), Bash scripting</li>
    <li>Nmap, Metasploit, Burp Suite, Nessus</li>
    <li>Autopsy, FTK Imager, Wireshark</li>
    <li>Linux (Kali, Ubuntu), Windows, Android</li>
    <li>Network Defense, Cryptography, Threat Analysis, Digital Evidence Handling</li>
  </ul>
</section>

<section id="goals">
  <h2>Future Goals</h2>
  <ul>
    <li>Secure internships with cutting-edge cybersecurity teams.</li>
    <li>Master advanced penetration testing, threat hunting, and digital forensics.</li>
    <li>Contribute to open-source security tools and publish technical blogs.</li>
    <li>Explore AI and IoT security to address emerging cyber threats.</li>
  </ul>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>Email: <a href="mailto:seanmuponesi50@gmail.com">seanmuponesi50@gmail.com</a></p>
  <p>LinkedIn: <a href="https://linkedin.com/in/sean-muponesi-460590334" target="_blank">linkedin.com/in/sean-muponesi-460590334</a></p>
  <p>GitHub: <a href="https://github.com/SeanMUPO" target="_blank">github.com/SeanMUPO</a></p>
</section>

<footer>
  © 2025 Sean Tadiwanashe Muponesi — Passion for Cybersecurity and Innovation
</footer>

</body>
</html>
