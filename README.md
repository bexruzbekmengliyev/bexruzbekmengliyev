<!DOCTYPE html>
<html lang="uz">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GitHub Profilim | Portfolio</title>
  <style>
    :root {
      --bg: #0d1117;
      --card-bg: #161b22;
      --border: #30363d;
      --text: #c9d1d9;
      --text-muted: #8b949e;
      --accent: #58a6ff;
      --accent-hover: #79c0ff;
      --radius: 12px;
    }
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif; }
    body { background: var(--bg); color: var(--text); line-height: 1.6; padding: 20px; }
    .container { max-width: 950px; margin: 0 auto; }
    
    /* Header */
    header { text-align: center; padding: 40px 0 20px; }
    header h1 { 
      font-size: 2.5rem; 
      background: linear-gradient(90deg, var(--accent), #a371f7, #f778ba); 
      -webkit-background-clip: text; 
      color: transparent; 
      margin-bottom: 10px; 
    }
    header p { color: var(--text-muted); font-size: 1.1rem; }
    .avatar { 
      width: 120px; height: 120px; border-radius: 50%; 
      border: 3px solid var(--accent); margin: 0 auto 20px; display: block; 
      object-fit: cover; box-shadow: 0 0 15px rgba(88,166,255,0.3); 
    }

    /* Sections */
    .section { margin: 40px 0; }
    .section h2 { 
      font-size: 1.8rem; margin-bottom: 20px; color: var(--text); 
      border-left: 4px solid var(--accent); padding-left: 12px; 
    }

    /* Skills */
    .skills { display: flex; flex-wrap: wrap; gap: 10px; }
    .skill { 
      background: var(--card-bg); border: 1px solid var(--border); 
      padding: 6px 14px; border-radius: 20px; font-size: 0.9rem; 
      color: var(--text-muted); transition: 0.3s; cursor: default; 
    }
    .skill:hover { border-color: var(--accent); color: var(--accent); transform: translateY(-2px); }

    /* Projects */
    .projects { display: grid; grid-template-columns: repeat(auto-fill, minmax(280px, 1fr)); gap: 20px; }
    .project { 
      background: var(--card-bg); border: 1px solid var(--border); 
      border-radius: var(--radius); padding: 20px; transition: 0.3s; 
    }
    .project:hover { transform: translateY(-5px); box-shadow: 0 8px 25px rgba(0,0,0,0.5); border-color: var(--accent); }
    .project h3 { color: var(--accent); margin-bottom: 8px; font-size: 1.2rem; }
    .project p { color: var(--text-muted); font-size: 0.95rem; margin-bottom: 15px; min-height: 40px; }
    .project a { color: var(--accent); text-decoration: none; font-weight: 500; display: inline-flex; align-items: center; gap: 5px; }
    .project a:hover { color: var(--accent-hover); text-decoration: underline; }

    /* Stats */
    .stats { display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; }
    .stats img { background: var(--card-bg); border: 1px solid var(--border); border-radius: var(--radius); padding: 10px; max-width: 100%; }

    /* Footer */
    footer { text-align: center; padding: 30px 0; color: var(--text-muted); font-size: 0.9rem; border-top: 1px solid var(--border); margin-top: 40px; }

    @media (max-width: 600px) {
      header h1 { font-size: 2rem; }
      .projects { grid-template-columns: 1fr; }
      .stats { flex-direction: column; align-items: center; }
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <img src="https://github.com/USERNAME.png" alt="Avatar" class="avatar" id="avatar">
      <h1>Salom, Men [Ismingiz]man 👋</h1>
      <p>Frontend Developer | UI/UX dizayner | Open Source ishqibozi</p>
    </header>

    <section class="section">
      <h2>🛠 Ko'nikmalarim</h2>
      <div class="skills">
        <span class="skill">HTML5 / CSS3</span>
        <span class="skill">JavaScript (ES6+)</span>
        <span class="skill">React.js</span>
        <span class="skill">Tailwind CSS</span>
        <span class="skill">Python</span>
        <span class="skill">Node.js</span>
        <span class="skill">Git & GitHub</span>
        <span class="skill">Figma</span>
      </div>
    </section>

    <section class="section">
      <h2>📂 Loyihalarim</h2>
      <div class="projects">
        <div class="project">
          <h3>🛒 E-Commerce Platform</h3>
          <p>React va Firebase yordamida yaratilgan zamonaviy online do'kon. Savatcha, to'lov va admin panel mavjud.</p>
          <a href="https://github.com/USERNAME/proekt1" target="_blank">GitHub →</a>
        </div>
        <div class="project">
          <h3>📊 Ma'lumotlar Tahlili Dashboard</h3>
          <p>Python va Chart.js bilan ishlangan real-time vizualizatsiya paneli. API integratsiyasi qilingan.</p>
          <a href="https://github.com/USERNAME/proekt2" target="_blank">GitHub →</a>
        </div>
        <div class="project">
          <h3>🎮 Brauzer O'yini</h3>
          <p>Vanilla JS va Canvas API yordamida yaratilgan mini-o'yin. Responsive va yengil.</p>
          <a href="https://github.com/USERNAME/proekt3" target="_blank">GitHub →</a>
        </div>
      </div>
    </section>

    <section class="section">
      <h2>📈 GitHub Faolligim</h2>
      <p style="color: var(--text-muted); margin-bottom: 15px;">Quyida mening GitHub statistikasi va yozishlar ketma-ketligi ko'rsatilgan:</p>
      <div class="stats">
        <img src="https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="GitHub Stats">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=USERNAME&theme=dark&hide_border=true&background=161b22" alt="GitHub Streak">
      </div>
    </section>

    footer>
      <p>© 2026 [Ismingiz] | GitHub Pages da joylashtirilgan 💙</p>
    </footer>
  </div>

  <script>
    // Avatar va statistikalarni o'zingizning GitHub username'ingiz bilan almashtirish
    const GITHUB_USERNAME = 'USERNAME'; // 🔴 BU YERGA O'Z GITHUB USERNAME'INGIZNI YOZING
    document.getElementById('avatar').src = `https://github.com/${GITHUB_USERNAME}.png`;
    
    const statsImg = document.querySelector('.stats img');
    const streakImg = document.querySelectorAll('.stats img')[1];
    statsImg.src = `https://github-readme-stats.vercel.app/api?username=${GITHUB_USERNAME}&show_icons=true&theme=dark&hide_border=true&count_private=true`;
    streakImg.src = `https://github-readme-streak-stats.herokuapp.com/?user=${GITHUB_USERNAME}&theme=dark&hide_border=true&background=161b22`;
  </script>
</body>
</html>
