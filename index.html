<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Younes Taibi — Data Engineer</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@300;400;600;700&family=Syne:wght@400;700;800&display=swap" rel="stylesheet">
<style>
:root {
  --bg: #080c10;
  --bg2: #0d1117;
  --bg3: #111820;
  --green: #00ff88;
  --green2: #00cc6a;
  --blue: #00aaff;
  --orange: #ff8c00;
  --red: #ff4466;
  --text: #c9d1d9;
  --muted: #4a5568;
  --border: #1e2d3d;
}

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

html { scroll-behavior: smooth; }

body {
  background: var(--bg);
  color: var(--text);
  font-family: 'JetBrains Mono', monospace;
  overflow-x: hidden;
  cursor: none;
}

/* ── Custom cursor ── */
#cursor {
  position: fixed; width: 12px; height: 12px;
  background: var(--green); border-radius: 50%;
  pointer-events: none; z-index: 9999;
  transform: translate(-50%, -50%);
  transition: transform 0.1s, background 0.2s;
  box-shadow: 0 0 12px var(--green);
}
#cursor-ring {
  position: fixed; width: 36px; height: 36px;
  border: 1px solid var(--green); border-radius: 50%;
  pointer-events: none; z-index: 9998;
  transform: translate(-50%, -50%);
  transition: all 0.15s ease;
  opacity: 0.5;
}

/* ── Canvas bg ── */
#canvas-bg {
  position: fixed; top: 0; left: 0;
  width: 100%; height: 100%;
  z-index: 0; opacity: 0.25;
}

/* ── Navbar ── */
nav {
  position: fixed; top: 0; width: 100%;
  z-index: 100; padding: 16px 48px;
  display: flex; justify-content: space-between; align-items: center;
  background: rgba(8,12,16,0.85);
  backdrop-filter: blur(12px);
  border-bottom: 1px solid var(--border);
}
.nav-logo {
  font-family: 'Syne', sans-serif;
  font-size: 1.1rem; font-weight: 800;
  color: var(--green);
  letter-spacing: 2px;
}
.nav-logo span { color: var(--text); }
.nav-links { display: flex; gap: 32px; }
.nav-links a {
  color: var(--muted); text-decoration: none;
  font-size: 0.75rem; letter-spacing: 1px;
  text-transform: uppercase;
  transition: color 0.2s;
  position: relative;
}
.nav-links a::after {
  content: ''; position: absolute;
  bottom: -4px; left: 0; width: 0; height: 1px;
  background: var(--green); transition: width 0.3s;
}
.nav-links a:hover { color: var(--green); }
.nav-links a:hover::after { width: 100%; }

/* ── Hero ── */
#hero {
  position: relative; z-index: 1;
  min-height: 100vh;
  display: flex; align-items: center;
  padding: 0 10%;
}
.hero-inner { max-width: 900px; }
.hero-tag {
  display: inline-block;
  font-size: 0.7rem; letter-spacing: 3px;
  color: var(--green); text-transform: uppercase;
  border: 1px solid var(--green);
  padding: 4px 12px; border-radius: 2px;
  margin-bottom: 24px;
  animation: fadeUp 0.6s ease both;
}
.hero-name {
  font-family: 'Syne', sans-serif;
  font-size: clamp(3.5rem, 8vw, 7rem);
  font-weight: 800;
  line-height: 0.95;
  color: #fff;
  animation: fadeUp 0.7s 0.1s ease both;
}
.hero-name .accent { color: var(--green); }
.hero-title {
  font-size: clamp(1rem, 2.5vw, 1.4rem);
  color: var(--muted);
  margin-top: 20px;
  animation: fadeUp 0.7s 0.2s ease both;
}
.hero-title .typed-text { color: var(--blue); }
.hero-desc {
  max-width: 540px;
  font-size: 0.85rem; line-height: 1.8;
  color: #6b7d8f; margin-top: 24px;
  animation: fadeUp 0.7s 0.3s ease both;
}
.hero-ctas {
  display: flex; gap: 16px; margin-top: 40px;
  animation: fadeUp 0.7s 0.4s ease both;
  flex-wrap: wrap;
}
.btn-primary {
  background: var(--green); color: #000;
  padding: 12px 28px; border: none; border-radius: 4px;
  font-family: 'JetBrains Mono', monospace;
  font-size: 0.78rem; font-weight: 700;
  letter-spacing: 1px; cursor: none;
  text-decoration: none; display: inline-block;
  transition: transform 0.2s, box-shadow 0.2s;
}
.btn-primary:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 24px rgba(0,255,136,0.3);
}
.btn-outline {
  border: 1px solid var(--border); color: var(--text);
  padding: 12px 28px; border-radius: 4px;
  font-family: 'JetBrains Mono', monospace;
  font-size: 0.78rem; letter-spacing: 1px;
  text-decoration: none; display: inline-block;
  transition: border-color 0.2s, color 0.2s;
  cursor: none;
}
.btn-outline:hover { border-color: var(--green); color: var(--green); }

/* ── Terminal block ── */
.terminal {
  background: var(--bg2);
  border: 1px solid var(--border);
  border-radius: 8px; overflow: hidden;
  margin-top: 60px;
  animation: fadeUp 0.7s 0.5s ease both;
  max-width: 580px;
}
.terminal-bar {
  background: var(--bg3);
  padding: 10px 16px;
  display: flex; align-items: center; gap: 8px;
  border-bottom: 1px solid var(--border);
}
.dot { width: 10px; height: 10px; border-radius: 50%; }
.dot-r { background: #ff5f56; }
.dot-y { background: #ffbd2e; }
.dot-g { background: #27c93f; }
.terminal-title {
  font-size: 0.65rem; color: var(--muted);
  margin-left: auto; letter-spacing: 1px;
}
.terminal-body { padding: 20px 24px; font-size: 0.78rem; line-height: 2; }
.t-prompt { color: var(--green); }
.t-cmd { color: var(--text); }
.t-out { color: var(--muted); }
.t-val { color: var(--blue); }
.t-str { color: var(--orange); }
.blink { animation: blink 1s infinite; color: var(--green); }

/* ── Section layout ── */
section {
  position: relative; z-index: 1;
  padding: 100px 10%;
}
.section-header {
  display: flex; align-items: center; gap: 16px;
  margin-bottom: 60px;
}
.section-num {
  font-size: 0.7rem; color: var(--green);
  letter-spacing: 2px;
}
.section-title {
  font-family: 'Syne', sans-serif;
  font-size: clamp(1.8rem, 3vw, 2.5rem);
  font-weight: 800; color: #fff;
}
.section-line {
  flex: 1; height: 1px;
  background: linear-gradient(to right, var(--border), transparent);
}

/* ── Skills ── */
#skills { background: var(--bg2); }
.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 20px;
}
.skill-card {
  background: var(--bg);
  border: 1px solid var(--border);
  border-radius: 8px; padding: 24px;
  transition: border-color 0.3s, transform 0.3s;
  position: relative; overflow: hidden;
}
.skill-card::before {
  content: ''; position: absolute;
  top: 0; left: 0; right: 0; height: 2px;
  background: linear-gradient(to right, var(--green), var(--blue));
  transform: scaleX(0); transform-origin: left;
  transition: transform 0.4s;
}
.skill-card:hover { border-color: var(--green)44; transform: translateY(-4px); }
.skill-card:hover::before { transform: scaleX(1); }
.skill-cat {
  font-size: 0.65rem; letter-spacing: 2px;
  text-transform: uppercase; color: var(--green);
  margin-bottom: 16px;
}
.skill-items { display: flex; flex-wrap: wrap; gap: 8px; }
.skill-tag {
  background: var(--bg3);
  border: 1px solid var(--border);
  padding: 4px 10px; border-radius: 3px;
  font-size: 0.7rem; color: var(--text);
  transition: border-color 0.2s, color 0.2s;
}
.skill-tag:hover { border-color: var(--green); color: var(--green); }

/* ── Experience ── */
.timeline { position: relative; padding-left: 32px; }
.timeline::before {
  content: ''; position: absolute;
  left: 0; top: 8px; bottom: 0; width: 1px;
  background: linear-gradient(to bottom, var(--green), transparent);
}
.timeline-item { position: relative; margin-bottom: 48px; }
.timeline-dot {
  position: absolute; left: -37px; top: 6px;
  width: 10px; height: 10px; border-radius: 50%;
  background: var(--green);
  box-shadow: 0 0 10px var(--green);
}
.tl-date {
  font-size: 0.68rem; color: var(--green);
  letter-spacing: 1px; margin-bottom: 8px;
}
.tl-role {
  font-family: 'Syne', sans-serif;
  font-size: 1.1rem; font-weight: 700; color: #fff;
}
.tl-company {
  font-size: 0.78rem; color: var(--blue);
  margin-top: 2px; margin-bottom: 14px;
}
.tl-points { list-style: none; }
.tl-points li {
  font-size: 0.78rem; color: var(--muted);
  line-height: 1.8; padding-left: 16px;
  position: relative;
}
.tl-points li::before {
  content: '▸'; position: absolute; left: 0;
  color: var(--green);
}
.tl-stack { display: flex; flex-wrap: wrap; gap: 6px; margin-top: 12px; }
.tl-tag {
  background: rgba(0,255,136,0.07);
  border: 1px solid rgba(0,255,136,0.2);
  color: var(--green); font-size: 0.65rem;
  padding: 2px 8px; border-radius: 2px;
}

/* ── Projects ── */
#projects { background: var(--bg2); }
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 24px;
}
.project-card {
  background: var(--bg);
  border: 1px solid var(--border);
  border-radius: 10px; padding: 28px;
  transition: all 0.3s; position: relative;
  overflow: hidden;
}
.project-card::after {
  content: ''; position: absolute;
  inset: 0;
  background: linear-gradient(135deg, rgba(0,255,136,0.03), transparent);
  opacity: 0; transition: opacity 0.3s;
}
.project-card:hover {
  border-color: rgba(0,255,136,0.3);
  transform: translateY(-6px);
  box-shadow: 0 20px 40px rgba(0,0,0,0.4);
}
.project-card:hover::after { opacity: 1; }
.project-top {
  display: flex; justify-content: space-between;
  align-items: flex-start; margin-bottom: 16px;
}
.project-icon { font-size: 1.8rem; }
.project-links { display: flex; gap: 12px; }
.project-links a {
  color: var(--muted); text-decoration: none;
  font-size: 0.7rem; letter-spacing: 1px;
  transition: color 0.2s;
}
.project-links a:hover { color: var(--green); }
.project-name {
  font-family: 'Syne', sans-serif;
  font-size: 1rem; font-weight: 700; color: #fff;
  margin-bottom: 10px;
}
.project-desc {
  font-size: 0.75rem; color: var(--muted);
  line-height: 1.8; margin-bottom: 16px;
}
.project-stack { display: flex; flex-wrap: wrap; gap: 6px; }
.project-tech {
  font-size: 0.65rem; color: var(--blue);
  background: rgba(0,170,255,0.08);
  border: 1px solid rgba(0,170,255,0.2);
  padding: 2px 8px; border-radius: 2px;
}

/* ── Stats bar ── */
.stats-row {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
  gap: 20px; margin-top: 60px;
}
.stat-box {
  border: 1px solid var(--border);
  border-radius: 8px; padding: 24px;
  text-align: center;
  background: var(--bg);
  transition: border-color 0.3s;
}
.stat-box:hover { border-color: var(--green)44; }
.stat-num {
  font-family: 'Syne', sans-serif;
  font-size: 2.2rem; font-weight: 800;
  color: var(--green);
}
.stat-lbl {
  font-size: 0.65rem; color: var(--muted);
  letter-spacing: 1px; text-transform: uppercase;
  margin-top: 4px;
}

/* ── Education ── */
.edu-card {
  background: var(--bg2);
  border: 1px solid var(--border);
  border-radius: 8px; padding: 28px 32px;
  display: flex; gap: 24px;
  align-items: flex-start;
  transition: border-color 0.3s;
}
.edu-card:hover { border-color: rgba(0,255,136,0.3); }
.edu-icon {
  font-size: 2rem; flex-shrink: 0;
  margin-top: 4px;
}
.edu-degree {
  font-family: 'Syne', sans-serif;
  font-size: 1.1rem; font-weight: 700; color: #fff;
}
.edu-school { font-size: 0.78rem; color: var(--blue); margin-top: 4px; }
.edu-date { font-size: 0.68rem; color: var(--green); margin-top: 4px; }
.edu-topics { display: flex; flex-wrap: wrap; gap: 6px; margin-top: 14px; }
.edu-topic {
  font-size: 0.65rem; color: var(--muted);
  background: var(--bg3); border: 1px solid var(--border);
  padding: 3px 10px; border-radius: 2px;
}

/* ── Contact ── */
#contact {
  background: var(--bg2);
  text-align: center;
}
.contact-inner { max-width: 560px; margin: 0 auto; }
.contact-sub {
  font-size: 0.8rem; color: var(--muted);
  line-height: 1.8; margin-bottom: 40px;
}
.contact-links { display: flex; justify-content: center; flex-wrap: wrap; gap: 16px; }
.contact-link {
  border: 1px solid var(--border);
  color: var(--text); text-decoration: none;
  padding: 12px 24px; border-radius: 4px;
  font-size: 0.75rem; letter-spacing: 1px;
  display: flex; align-items: center; gap: 8px;
  transition: all 0.2s;
}
.contact-link:hover {
  border-color: var(--green);
  color: var(--green);
  background: rgba(0,255,136,0.05);
}
.contact-status {
  display: inline-flex; align-items: center; gap: 8px;
  font-size: 0.72rem; color: var(--green);
  background: rgba(0,255,136,0.08);
  border: 1px solid rgba(0,255,136,0.2);
  padding: 8px 16px; border-radius: 24px;
  margin-bottom: 32px;
}
.status-dot {
  width: 7px; height: 7px; border-radius: 50%;
  background: var(--green);
  animation: pulse 2s infinite;
}

/* ── Footer ── */
footer {
  text-align: center; padding: 24px;
  font-size: 0.65rem; color: var(--muted);
  border-top: 1px solid var(--border);
  position: relative; z-index: 1;
}

/* ── Animations ── */
@keyframes fadeUp {
  from { opacity: 0; transform: translateY(24px); }
  to   { opacity: 1; transform: translateY(0); }
}
@keyframes blink {
  0%, 100% { opacity: 1; } 50% { opacity: 0; }
}
@keyframes pulse {
  0%, 100% { box-shadow: 0 0 0 0 rgba(0,255,136,0.4); }
  50% { box-shadow: 0 0 0 6px rgba(0,255,136,0); }
}
@keyframes float {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-8px); }
}
.reveal {
  opacity: 0; transform: translateY(30px);
  transition: opacity 0.7s ease, transform 0.7s ease;
}
.reveal.visible { opacity: 1; transform: translateY(0); }

/* ── Scrollbar ── */
::-webkit-scrollbar { width: 4px; }
::-webkit-scrollbar-track { background: var(--bg); }
::-webkit-scrollbar-thumb { background: var(--border); border-radius: 2px; }
::-webkit-scrollbar-thumb:hover { background: var(--green); }

@media (max-width: 768px) {
  nav { padding: 16px 24px; }
  .nav-links { display: none; }
  section { padding: 80px 6%; }
  #hero { padding: 0 6%; }
}
</style>
</head>
<body>

<div id="cursor"></div>
<div id="cursor-ring"></div>
<canvas id="canvas-bg"></canvas>

<!-- NAV -->
<nav>
  <div class="nav-logo">YT<span>.</span></div>
  <div class="nav-links">
    <a href="#skills">Skills</a>
    <a href="#experience">Expérience</a>
    <a href="#projects">Projets</a>
    <a href="#education">Formation</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<!-- HERO -->
<section id="hero">
  <div class="hero-inner">
    <div class="hero-tag">// Data Engineer · Paris, France</div>
    <h1 class="hero-name">Younes<br><span class="accent">Taibi</span></h1>
    <p class="hero-title">
      <span class="typed-text" id="typed"></span><span class="blink">█</span>
    </p>
    <p class="hero-desc">
      Passionné par les architectures Big Data, les pipelines ML et l'industrialisation de solutions data.
      Je conçois des systèmes de données fiables, performants et scalables.
    </p>
    <div class="hero-ctas">
      <a href="#contact" class="btn-primary">// Me contacter</a>
      <a href="#projects" class="btn-outline">// Voir mes projets</a>
    </div>

    <div class="terminal">
      <div class="terminal-bar">
        <div class="dot dot-r"></div>
        <div class="dot dot-y"></div>
        <div class="dot dot-g"></div>
        <span class="terminal-title">younes@data-eng ~ $</span>
      </div>
      <div class="terminal-body">
        <div><span class="t-prompt">❯ </span><span class="t-cmd">whoami</span></div>
        <div class="t-out">  Younes Taibi — Data Engineer</div>
        <br>
        <div><span class="t-prompt">❯ </span><span class="t-cmd">cat skills.json</span></div>
        <div><span class="t-out">  {</span></div>
        <div><span class="t-out">  &nbsp;&nbsp;"stack": </span><span class="t-str">"Python · Spark · GCP · SQL"</span><span class="t-out">,</span></div>
        <div><span class="t-out">  &nbsp;&nbsp;"ml": </span><span class="t-str">"Scikit-learn · TensorFlow · PyTorch"</span><span class="t-out">,</span></div>
        <div><span class="t-out">  &nbsp;&nbsp;"status": </span><span class="t-val">"open_to_work"</span><span class="t-out">,</span></div>
        <div><span class="t-out">  &nbsp;&nbsp;"contract": </span><span class="t-str">"CDI"</span></div>
        <div><span class="t-out">  }</span></div>
        <br>
        <div><span class="t-prompt">❯ </span><span class="blink">█</span></div>
      </div>
    </div>
  </div>
</section>

<!-- SKILLS -->
<section id="skills">
  <div class="section-header reveal">
    <span class="section-num">01.</span>
    <h2 class="section-title">Compétences</h2>
    <div class="section-line"></div>
  </div>
  <div class="skills-grid">
    <div class="skill-card reveal">
      <div class="skill-cat">🐍 Langages & Data</div>
      <div class="skill-items">
        <span class="skill-tag">Python</span>
        <span class="skill-tag">SQL</span>
        <span class="skill-tag">PL/SQL</span>
        <span class="skill-tag">Java</span>
        <span class="skill-tag">C++</span>
        <span class="skill-tag">Pandas</span>
        <span class="skill-tag">NumPy</span>
      </div>
    </div>
    <div class="skill-card reveal">
      <div class="skill-cat">🤖 Machine Learning</div>
      <div class="skill-items">
        <span class="skill-tag">Scikit-learn</span>
        <span class="skill-tag">TensorFlow</span>
        <span class="skill-tag">PyTorch</span>
        <span class="skill-tag">Random Forest</span>
        <span class="skill-tag">AutoEncoder</span>
        <span class="skill-tag">KNN</span>
      </div>
    </div>
    <div class="skill-card reveal">
      <div class="skill-cat">☁️ Cloud & Big Data</div>
      <div class="skill-items">
        <span class="skill-tag">Apache Spark</span>
        <span class="skill-tag">GCP</span>
        <span class="skill-tag">Docker</span>
        <span class="skill-tag">ETL (ODI)</span>
        <span class="skill-tag">CI/CD</span>
        <span class="skill-tag">Serverless</span>
      </div>
    </div>
    <div class="skill-card reveal">
      <div class="skill-cat">📊 Visualisation & BI</div>
      <div class="skill-items">
        <span class="skill-tag">Power BI</span>
        <span class="skill-tag">Plotly</span>
        <span class="skill-tag">Seaborn</span>
        <span class="skill-tag">Geopandas</span>
        <span class="skill-tag">Matplotlib</span>
      </div>
    </div>
    <div class="skill-card reveal">
      <div class="skill-cat">⚡ Automatisation & IA</div>
      <div class="skill-items">
        <span class="skill-tag">n8n</span>
        <span class="skill-tag">UiPath</span>
        <span class="skill-tag">Power Automate</span>
        <span class="skill-tag">ChatGPT API</span>
        <span class="skill-tag">Gemini</span>
        <span class="skill-tag">Copilot</span>
      </div>
    </div>
    <div class="skill-card reveal">
      <div class="skill-cat">🌐 Langues</div>
      <div class="skill-items">
        <span class="skill-tag">🇫🇷 Français (Bilingue)</span>
        <span class="skill-tag">🇬🇧 Anglais (B1/B2)</span>
        <span class="skill-tag">🇩🇪 Allemand (A2)</span>
      </div>
    </div>
  </div>

  <div class="stats-row reveal">
    <div class="stat-box">
      <div class="stat-num" data-target="2">0</div>
      <div class="stat-lbl">Ans d'expérience</div>
    </div>
    <div class="stat-box">
      <div class="stat-num" data-target="6">0</div>
      <div class="stat-lbl">Projets GitHub</div>
    </div>
    <div class="stat-box">
      <div class="stat-num" data-target="10">0</div>
      <div class="stat-lbl">Technologies</div>
    </div>
    <div class="stat-box">
      <div class="stat-num" data-target="1">0</div>
      <div class="stat-lbl">Master obtenu</div>
    </div>
  </div>
</section>

<!-- EXPERIENCE -->
<section id="experience">
  <div class="section-header reveal">
    <span class="section-num">02.</span>
    <h2 class="section-title">Expérience</h2>
    <div class="section-line"></div>
  </div>
  <div class="timeline">
    <div class="timeline-item reveal">
      <div class="timeline-dot"></div>
      <div class="tl-date">06/2025 — 10/2025</div>
      <div class="tl-role">Data Scientist MLOps</div>
      <div class="tl-company">Tech4fab · Paris</div>
      <ul class="tl-points">
        <li>Développement d'un modèle de classification pour la maintenance prédictive (iMotor-Diag)</li>
        <li>Détection automatique de défauts rotoriques par analyse de signaux vibratoires</li>
        <li>Industrialisation sur GCP avec pipeline serverless et mise en place CI/CD (MLOps)</li>
        <li>Containerisation avec Docker et monitoring des modèles en production</li>
      </ul>
      <div class="tl-stack">
        <span class="tl-tag">Python</span>
        <span class="tl-tag">TensorFlow</span>
        <span class="tl-tag">Scikit-learn</span>
        <span class="tl-tag">Docker</span>
        <span class="tl-tag">GCP</span>
        <span class="tl-tag">CI/CD</span>
      </div>
    </div>
    <div class="timeline-item reveal">
      <div class="timeline-dot"></div>
      <div class="tl-date">05/2024 — 08/2024</div>
      <div class="tl-role">Data Analyst (Stagiaire)</div>
      <div class="tl-company">Tech4fab · Paris</div>
      <ul class="tl-points">
        <li>Collecte, nettoyage et structuration de données opérationnelles</li>
        <li>Analyses exploratoires et détection d'anomalies — identification de dérives de consommation</li>
        <li>Développement de dashboards Power BI temps réel pour le suivi des KPIs</li>
        <li>Aide à la décision et reporting stratégique pour les équipes techniques</li>
      </ul>
      <div class="tl-stack">
        <span class="tl-tag">Power BI</span>
        <span class="tl-tag">Python</span>
        <span class="tl-tag">SQL</span>
        <span class="tl-tag">Power Automate</span>
        <span class="tl-tag">Excel VBA</span>
      </div>
    </div>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects">
  <div class="section-header reveal">
    <span class="section-num">03.</span>
    <h2 class="section-title">Projets</h2>
    <div class="section-line"></div>
  </div>
  <div class="projects-grid">
    <div class="project-card reveal">
      <div class="project-top">
        <div class="project-icon">⚽</div>
        <div class="project-links">
          <a href="https://github.com/taibi1995/Prediction-veleur-des-joueurs-de-football" target="_blank">GitHub ↗</a>
        </div>
      </div>
      <div class="project-name">Prédiction Valeur Joueurs Football</div>
      <div class="project-desc">
        Modèle Random Forest entraîné sur les datasets FIFA & Transfermarkt (2015–2024) pour prédire la valeur marchande des joueurs. Feature engineering poussé, validation croisée, ~85% de R².
      </div>
      <div class="project-stack">
        <span class="project-tech">Python</span>
        <span class="project-tech">Scikit-learn</span>
        <span class="project-tech">Pandas</span>
        <span class="project-tech">Random Forest</span>
        <span class="project-tech">Jupyter</span>
      </div>
    </div>

    <div class="project-card reveal">
      <div class="project-top">
        <div class="project-icon">🚕</div>
        <div class="project-links">
          <a href="https://github.com/taibi1995/Big-Data" target="_blank">GitHub ↗</a>
        </div>
      </div>
      <div class="project-name">Analyse Big Data — Taxis NYC</div>
      <div class="project-desc">
        Traitement de 80M+ de courses Yellow Cab & FHV avec Apache Spark. Visualisations géospatiales, analyse des tendances de l'industrie, heatmaps et évolution des parts de marché.
      </div>
      <div class="project-stack">
        <span class="project-tech">Apache Spark</span>
        <span class="project-tech">Plotly</span>
        <span class="project-tech">Geopandas</span>
        <span class="project-tech">Seaborn</span>
        <span class="project-tech">PySpark</span>
      </div>
    </div>

    <div class="project-card reveal">
      <div class="project-top">
        <div class="project-icon">🧠</div>
        <div class="project-links">
          <a href="https://github.com/taibi1995/TP-Deep-Learning" target="_blank">GitHub ↗</a>
        </div>
      </div>
      <div class="project-name">Deep Learning — Expérimentations</div>
      <div class="project-desc">
        Implémentation d'AutoEncoders pour la détection d'anomalies, classification multi-classes, réseaux convolutifs. Expérimentations avec PyTorch et TensorFlow.
      </div>
      <div class="project-stack">
        <span class="project-tech">PyTorch</span>
        <span class="project-tech">TensorFlow</span>
        <span class="project-tech">AutoEncoder</span>
        <span class="project-tech">CNN</span>
      </div>
    </div>

    <div class="project-card reveal">
      <div class="project-top">
        <div class="project-icon">⚡</div>
        <div class="project-links">
          <a href="https://github.com/taibi1995/Optimisation-C-" target="_blank">GitHub ↗</a>
        </div>
      </div>
      <div class="project-name">Algorithmes d'Optimisation — C++</div>
      <div class="project-desc">
        Implémentation haute performance d'algorithmes classiques : BFS/DFS, Prim, Max Flow, Knapsack, Job Scheduling. Benchmark et analyse de complexité.
      </div>
      <div class="project-stack">
        <span class="project-tech">C++</span>
        <span class="project-tech">Algorithmes</span>
        <span class="project-tech">Optimisation</span>
        <span class="project-tech">Graphes</span>
      </div>
    </div>

    <div class="project-card reveal">
      <div class="project-top">
        <div class="project-icon">🗄️</div>
        <div class="project-links">
          <a href="https://github.com/taibi1995/TPs-Archi_BDD-JAVA" target="_blank">GitHub ↗</a>
        </div>
      </div>
      <div class="project-name">Architecture BDD — Java</div>
      <div class="project-desc">
        Optimisation de bases de données, gestion de blocs, algorithmes de jointure (hash join, merge join). Implémentation d'un moteur de requêtes simplifié.
      </div>
      <div class="project-stack">
        <span class="project-tech">Java</span>
        <span class="project-tech">SQL</span>
        <span class="project-tech">BDD</span>
        <span class="project-tech">Optimisation</span>
      </div>
    </div>

    <div class="project-card reveal" style="border-style: dashed; opacity: 0.6;">
      <div class="project-top">
        <div class="project-icon">🔧</div>
      </div>
      <div class="project-name">Maintenance Prédictive — iMotor</div>
      <div class="project-desc">
        Détection de défauts rotoriques par ML, déployé sur GCP. Version démo publique en cours de préparation.
      </div>
      <div class="project-stack">
        <span class="project-tech">GCP</span>
        <span class="project-tech">TensorFlow</span>
        <span class="project-tech">Docker</span>
        <span class="project-tech">MLOps</span>
        <span class="project-tech">Coming soon</span>
      </div>
    </div>
  </div>
</section>

<!-- EDUCATION -->
<section id="education">
  <div class="section-header reveal">
    <span class="section-num">04.</span>
    <h2 class="section-title">Formation</h2>
    <div class="section-line"></div>
  </div>
  <div class="edu-card reveal">
    <div class="edu-icon">🎓</div>
    <div>
      <div class="edu-degree">Master Data — Données, Algorithmes, Traitement et Analyse</div>
      <div class="edu-school">Université de Paris Cité</div>
      <div class="edu-date">2023 — 2025</div>
      <div class="edu-topics">
        <span class="edu-topic">Big Data</span>
        <span class="edu-topic">Machine Learning</span>
        <span class="edu-topic">Algorithmes avancés</span>
        <span class="edu-topic">Bases de données avancées</span>
        <span class="edu-topic">Fouille de données</span>
        <span class="edu-topic">Optimisation</span>
        <span class="edu-topic">Architectures BDD</span>
        <span class="edu-topic">Deep Learning</span>
      </div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="contact-inner">
    <div class="section-header reveal" style="justify-content:center;">
      <span class="section-num">05.</span>
      <h2 class="section-title">Contact</h2>
    </div>
    <div class="contact-status reveal">
      <div class="status-dot"></div>
      Disponible pour un CDI — Paris &amp; Remote
    </div>
    <p class="contact-sub reveal">
      Data Engineer à la recherche d'un CDI. Je suis toujours ouvert à discuter de nouveaux projets,
      d'opportunités ou simplement d'architecture data autour d'un café virtuel.
    </p>
    <div class="contact-links reveal">
      <a href="mailto:taibii.younesss@gmail.com" class="contact-link">
        📧 taibii.younesss@gmail.com
      </a>
      <a href="https://www.linkedin.com/in/younes-taibi-47690a23a/" target="_blank" class="contact-link">
        🔗 LinkedIn
      </a>
      <a href="https://github.com/taibi1995" target="_blank" class="contact-link">
        🐙 GitHub
      </a>
      <a href="tel:+33745708264" class="contact-link">
        📱 +33 7 45 70 82 64
      </a>
    </div>
  </div>
</section>

<footer>
  <p>Designed & built by Younes Taibi · 2026 · Paris, France</p>
</footer>

<script>
// ── Cursor ──
const cursor = document.getElementById('cursor');
const ring = document.getElementById('cursor-ring');
let mx = 0, my = 0, rx = 0, ry = 0;
document.addEventListener('mousemove', e => { mx = e.clientX; my = e.clientY; });
(function animCursor() {
  rx += (mx - rx) * 0.18;
  ry += (my - ry) * 0.18;
  cursor.style.left = mx + 'px'; cursor.style.top = my + 'px';
  ring.style.left = rx + 'px'; ring.style.top = ry + 'px';
  requestAnimationFrame(animCursor);
})();
document.querySelectorAll('a, button').forEach(el => {
  el.addEventListener('mouseenter', () => {
    cursor.style.transform = 'translate(-50%,-50%) scale(2.5)';
    ring.style.transform = 'translate(-50%,-50%) scale(0.5)';
    ring.style.opacity = '0.8';
  });
  el.addEventListener('mouseleave', () => {
    cursor.style.transform = 'translate(-50%,-50%) scale(1)';
    ring.style.transform = 'translate(-50%,-50%) scale(1)';
    ring.style.opacity = '0.5';
  });
});

// ── Canvas particles ──
const canvas = document.getElementById('canvas-bg');
const ctx = canvas.getContext('2d');
canvas.width = window.innerWidth; canvas.height = window.innerHeight;
window.addEventListener('resize', () => { canvas.width = window.innerWidth; canvas.height = window.innerHeight; });

const CHARS = '01アイウエオカキクケコデータパイプラインMLOPS';
const cols = Math.floor(window.innerWidth / 18);
const drops = Array.from({length: cols}, () => Math.random() * -canvas.height / 16);

function drawMatrix() {
  ctx.fillStyle = 'rgba(8,12,16,0.06)';
  ctx.fillRect(0, 0, canvas.width, canvas.height);
  ctx.font = '13px JetBrains Mono, monospace';
  for (let i = 0; i < cols; i++) {
    const ch = CHARS[Math.floor(Math.random() * CHARS.length)];
    const x = i * 18;
    const y = drops[i] * 16;
    const gradient = ctx.createLinearGradient(x, y - 80, x, y);
    gradient.addColorStop(0, 'rgba(0,255,136,0)');
    gradient.addColorStop(1, 'rgba(0,255,136,0.6)');
    ctx.fillStyle = gradient;
    ctx.fillText(ch, x, y);
    if (y > canvas.height && Math.random() > 0.975) drops[i] = 0;
    drops[i] += 0.4;
  }
}
setInterval(drawMatrix, 50);

// ── Typing animation ──
const phrases = [
  'Data Engineer',
  'ML Pipeline Builder',
  'Big Data Architect',
  'MLOps Practitioner',
];
let pi = 0, ci = 0, deleting = false;
const typed = document.getElementById('typed');
function typeLoop() {
  const cur = phrases[pi];
  typed.textContent = deleting ? cur.slice(0, ci--) : cur.slice(0, ci++);
  if (!deleting && ci > cur.length) { deleting = true; setTimeout(typeLoop, 1800); return; }
  if (deleting && ci < 0) { deleting = false; pi = (pi + 1) % phrases.length; ci = 0; }
  setTimeout(typeLoop, deleting ? 45 : 85);
}
typeLoop();

// ── Scroll reveal ──
const revealEls = document.querySelectorAll('.reveal');
const observer = new IntersectionObserver(entries => {
  entries.forEach((e, i) => {
    if (e.isIntersecting) {
      setTimeout(() => e.target.classList.add('visible'), i * 80);
    }
  });
}, { threshold: 0.1 });
revealEls.forEach(el => observer.observe(el));

// ── Counter animation ──
function animateCounters() {
  document.querySelectorAll('[data-target]').forEach(el => {
    const target = +el.dataset.target;
    const suffix = el.dataset.suffix || '';
    let count = 0;
    const step = Math.ceil(target / 40);
    const timer = setInterval(() => {
      count = Math.min(count + step, target);
      el.textContent = count + suffix;
      if (count >= target) clearInterval(timer);
    }, 40);
  });
}
const statsSection = document.getElementById('skills');
const statsObserver = new IntersectionObserver(entries => {
  if (entries[0].isIntersecting) { animateCounters(); statsObserver.disconnect(); }
}, { threshold: 0.4 });
statsObserver.observe(statsSection);
</script>
</body>
</html>
