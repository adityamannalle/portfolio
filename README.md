<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aditya Mannalle | Full Stack Developer & Prompt Engineer</title>
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #e3f2fd, #fce4ec);
      color: #222;
      transition: background 1s ease-in-out;
    }
    header {
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      color: white;
      text-align: center;
      padding: 4rem 1rem 2rem;
      animation: fadeIn 1.5s ease-out;
    }
    header h1 {
      margin: 0;
      font-size: 3rem;
      animation: slideIn 1s ease-out;
    }
    header p {
      font-size: 1.25rem;
      margin-top: 0.5rem;
      animation: fadeIn 2s ease-in;
    }
    section {
      padding: 2rem;
      max-width: 900px;
      margin: 2rem auto;
      background: rgba(255, 255, 255, 0.9);
      border-radius: 15px;
      box-shadow: 0 8px 24px rgba(0,0,0,0.1);
      animation: fadeUp 1s ease-out;
    }
    h2 {
      color: #2c3e50;
      border-bottom: 2px solid #ddd;
      padding-bottom: 0.5rem;
    }
    ul {
      padding-left: 1.5rem;
    }
    ul li {
      margin-bottom: 0.5rem;
      line-height: 1.6;
    }
    a {
      color: #0066cc;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    footer {
      text-align: center;
      padding: 1.5rem;
      background: #1f1f1f;
      color: white;
    }
    .timeline li::before {
      content: "\2022";
      color: #3498db;
      font-weight: bold;
      display: inline-block;
      width: 1em;
      margin-left: -1em;
    }
    .resume-button {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.6rem 1.2rem;
      background-color: #0066cc;
      color: white;
      border-radius: 8px;
      text-decoration: none;
      font-weight: 500;
      transition: background-color 0.3s;
      animation: fadeIn 2s ease-in-out;
    }
    .resume-button:hover {
      background-color: #004b99;
    }
    @keyframes fadeIn {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }
    @keyframes slideIn {
      0% { transform: translateY(-50px); opacity: 0; }
      100% { transform: translateY(0); opacity: 1; }
    }
    @keyframes fadeUp {
      from { transform: translateY(30px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
  </style>
</head>
<body>
  <!-- File Name: aditya.portfolio.html -->
  <header>
    <h1>Hi, I'm Aditya 👨‍💻</h1>
    <p>Full Stack Developer & Prompt Engineer | Passionate about Building Intelligent Web Apps</p>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I am a BCA student currently in my 4th semester, focused on becoming a professional Full Stack Developer and Prompt Engineer. I enjoy building smart and user-friendly web apps, and I’m dedicated to mastering both frontend and backend technologies along with prompt crafting techniques that improve development efficiency.</p>
    <a href="#" class="resume-button">Download Resume (Coming Soon)</a>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li><strong>Frontend:</strong> HTML, CSS, JavaScript (Learning)</li>
      <li><strong>Backend:</strong> Node.js, MongoDB (Upcoming)</li>
      <li><strong>Tools:</strong> Git, GitHub, VS Code</li>
      <li><strong>Frameworks:</strong> React.js, Tailwind CSS (Learning Soon)</li>
      <li><strong>Prompt Engineering:</strong> Writing precise and efficient prompts to enhance AI-assisted coding and problem-solving</li>
    </ul>
  </section>

  <section id="timeline">
    <h2>Learning Timeline</h2>
    <ul class="timeline">
      <li>June 2025 – Learned HTML & CSS</li>
      <li>July 2025 – Practicing JavaScript & GitHub</li>
      <li>August 2025 – Start React & build dynamic apps</li>
      <li>September 2025 – Learn Node.js, MongoDB & Tailwind CSS</li>
      <li>December 2025 – Launch 3 Full Stack Projects</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <p>I am currently learning and haven't completed any projects yet. My first project will be a personal blog app built using React and Node.js, followed by a portfolio site and a full-stack to-do app. Stay tuned!</p>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:adityamannalle.dev@gmail.com">adityamannalle.dev@gmail.com</a></p>
    <p>GitHub: <em>Coming soon</em></p>
    <p>LinkedIn: <em>Coming soon</em></p>
  </section>

  <footer>
    <p>&copy; 2025 Aditya Mannalle. All rights reserved.</p>
  </footer>
</body>
</html>
