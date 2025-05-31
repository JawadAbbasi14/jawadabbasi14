<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jawad Abbasi - Portfolio</title>
  <style>
    body {
      font-family: 'Segoe UI', Arial, sans-serif;
      background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
      color: #333;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }

    .container {
      max-width: 1200px;
      margin: auto;
      padding: 20px;
    }

    /* Header Animation */
    .animated-heading {
      font-size: 35px;
      font-weight: bold;
      text-align: center;
      color: #333;
      margin: 40px 0;
      overflow: hidden;
    }

    .animated-heading span {
      display: inline-block;
      opacity: 0;
      transform: translateY(20px);
      animation: fadeInUp 0.6s ease forwards;
    }

    .animated-heading span:nth-child(1) { animation-delay: 0.1s; }
    .animated-heading span:nth-child(2) { animation-delay: 0.2s; }
    .animated-heading span:nth-child(3) { animation-delay: 0.3s; }
    .animated-heading span:nth-child(4) { animation-delay: 0.4s; }
    .animated-heading span:nth-child(5) { animation-delay: 0.5s; }

    @keyframes fadeInUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    /* Section Styling */
    h2 {
      font-size: 28px;
      font-weight: bold;
      text-transform: uppercase;
      text-align: center;
      margin: 40px 0 20px;
      position: relative;
      padding-bottom: 10px;
    }

    h2::after {
      content: '';
      width: 60px;
      height: 4px;
      background: #4CAF50;
      display: block;
      margin: 10px auto;
      border-radius: 2px;
    }

    h2.about { color: #4CAF50; }
    h2.skills { color: #FF5722; }
    h2.goals { color: #2196F3; }
    h2.stats { color: #9C27B0; }

    p, ul {
      font-size: 16px;
      color: #333;
      max-width: 80%;
      margin: auto;
      text-align: center;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    ul li {
      margin: 10px 0;
    }

    a {
      color: #4CAF50;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    a:hover {
      color: #FF5722;
      text-decoration: underline;
    }

    /* Table Styling */
    table {
      width: 90%;
      margin: 20px auto;
      border-collapse: collapse;
      background: #fff;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
      border-radius: 10px;
      overflow: hidden;
    }

    th, td {
      padding: 15px;
      text-align: left;
    }

    th {
      background: #FF5722;
      color: #fff;
      font-weight: bold;
    }

    tr:nth-child(even) {
      background: #f9f9f9;
    }

    tr:hover {
      background: #e0f7fa;
      transition: background 0.3s ease;
    }

    /* Stats Section */
    .stats-container {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
      margin: 20px auto;
    }

    .stats-container img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
    }

    /* Responsive Design */
    @media (max-width: 768px) {
      .animated-heading {
        font-size: 24px;
      }

      h2 {
        font-size: 24px;
      }

      p, ul, table {
        font-size: 14px;
      }

      .stats-container {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1 class="animated-heading">
      <span>Hi 👋, I am Jawad!</span><br>
      <span>Welcome to my GitHub!</span><br>
      <span>Python Developer & Programmer 💻!</span>
    </h1>

    <h2 class="about">✨ About Me ✨</h2>
    <p>
      Hi, I am <strong>Jawad Abbasi</strong>! 🚀<br>
      A learning <em>Full Stack Developer</em>, <em>AI Enthusiast</em>, and <em>Cybersecurity Learner</em> 💻.<br>
      Passionate about coding, AI, security, and building impactful solutions. 🌟
    </p>
    <ul>
      <li><strong>Email:</strong> <a href="mailto:jawadabbasi1107@gmail.com">jawadabbasi1107@gmail.com</a></li>
      <li><strong>Portfolio:</strong> <a href="https://jawadabbasi14.github.io/my-portfolio-website/">My Portfolio Website 🌐</a></li>
    </ul>

    <h2 class="skills">🌟 Skills & Tools 🌟</h2>
    <table>
      <thead>
        <tr>
          <th>Category</th>
          <th>Details</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Languages</td>
          <td>Python 🐍, Bash 🖥️</td>
        </tr>
        <tr>
          <td>AI & Machine Learning</td>
          <td>TensorFlow 🔬, PyTorch 🔥, Scikit-Learn 📊</td>
        </tr>
        <tr>
          <td>Cybersecurity</td>
          <td>Kali Linux 🛡️, Metasploit, Wireshark</td>
        </tr>
        <tr>
          <td>Backend & Databases</td>
          <td>Django 🍃, FastAPI ⚡, PostgreSQL 🗄️, MongoDB 🍃</td>
        </tr>
        <tr>
          <td>DevOps & Cloud</td>
          <td>Docker 🐳, Kubernetes ☸️, AWS ☁️, GitHub Actions</td>
        </tr>
        <tr>
          <td>Tools</td>
          <td>Git 🛠️, VS Code ✏️, Jupyter Notebook 📒</td>
        </tr>
      </tbody>
    </table>

    <h2 class="goals">🚀 Goals 🚀</h2>
    <ul>
      <li>Become a <strong>Full Stack Developer</strong> 🌐</li>
      <li>Master <strong>AI & Machine Learning</strong> 🤖</li>
      <li>Develop and deploy scalable software solutions 🏗️</li>
      <li>Contribute to impactful open-source projects 🌟</li>
      <li>Build and optimize real-world AI systems ⚡</li>
      <li>Master <strong>Cybersecurity & Ethical Hacking</strong> 🔐</li>
      <li>Create innovative AI-powered applications 🚀</li>
    </ul>

    <h2 class="stats">💻 GitHub Stats 💻</h2>
    <div class="stats-container">
      <img src="https://github-readme-stats.vercel.app/api?username=JawadAbbasi14&show_icons=true&theme=radical" alt="Jawad Abbasi's GitHub contribution stats" />
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=JawadAbbasi14&theme=radical" alt="Jawad Abbasi's GitHub contribution streak" />
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JawadAbbasi14&layout=compact&theme=radical" alt="Jawad Abbasi's most used programming languages" />
    </div>
  </div>
</body>
</html>
