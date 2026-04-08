<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Circuitos RC, RL y RLC — Electric Dark</title>
<link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&family=Orbitron:wght@400;700;900&family=Rajdhani:wght@300;400;600;700&display=swap" rel="stylesheet">
<script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/3.2.2/es5/tex-mml-chtml.min.js"></script>
<style>
  :root {
    --bg-deep: #020408;
    --bg-mid: #080d14;
    --bg-card: #0b1220;
    --bg-card2: #0d1626;
    --neon-blue: #00d4ff;
    --neon-orange: #ff6b00;
    --neon-green: #00ff88;
    --neon-purple: #b000ff;
    --neon-yellow: #ffe000;
    --text-main: #d0e8f7;
    --text-dim: #6a8fa8;
    --text-bright: #f0faff;
    --glow-blue: 0 0 8px #00d4ff88, 0 0 24px #00d4ff44;
    --glow-orange: 0 0 8px #ff6b0088, 0 0 24px #ff6b0044;
    --glow-green: 0 0 8px #00ff8888, 0 0 24px #00ff8844;
    --border-blue: 1px solid #00d4ff33;
    --border-orange: 1px solid #ff6b0033;
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg-deep);
    color: var(--text-main);
    font-family: 'Rajdhani', sans-serif;
    font-size: 17px;
    line-height: 1.7;
    overflow-x: hidden;
  }

  /* === GRID BG === */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background-image:
      linear-gradient(rgba(0,212,255,0.04) 1px, transparent 1px),
      linear-gradient(90deg, rgba(0,212,255,0.04) 1px, transparent 1px);
    background-size: 48px 48px;
    pointer-events: none;
    z-index: 0;
  }

  /* === HERO === */
  .hero {
    position: relative;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 4rem 2rem;
    z-index: 1;
  }

  .hero-glow {
    position: absolute;
    inset: 0;
    background: radial-gradient(ellipse 60% 40% at 50% 60%, #00d4ff12 0%, transparent 70%),
                radial-gradient(ellipse 40% 30% at 80% 20%, #ff6b0008 0%, transparent 60%);
    pointer-events: none;
  }

  .hero-badge {
    display: inline-block;
    border: 1px solid var(--neon-blue);
    color: var(--neon-blue);
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.72rem;
    letter-spacing: 0.25em;
    padding: 0.35em 1.1em;
    border-radius: 2px;
    box-shadow: var(--glow-blue);
    margin-bottom: 2rem;
    animation: pulse-badge 3s ease-in-out infinite;
  }

  @keyframes pulse-badge {
    0%, 100% { opacity: 1; }
    50% { opacity: 0.6; }
  }

  .hero h1 {
    font-family: 'Orbitron', monospace;
    font-size: clamp(2.4rem, 7vw, 5.5rem);
    font-weight: 900;
    line-height: 1.05;
    letter-spacing: -0.01em;
    margin-bottom: 0.5rem;
  }

  .hero h1 .word-rc { color: var(--neon-blue); text-shadow: var(--glow-blue); }
  .hero h1 .word-rl { color: var(--neon-orange); text-shadow: var(--glow-orange); }
  .hero h1 .word-rlc { color: var(--neon-green); text-shadow: var(--glow-green); }

  .hero-sub {
    font-size: 1.15rem;
    color: var(--text-dim);
    max-width: 600px;
    margin: 1.2rem auto 2.5rem;
    font-weight: 300;
    letter-spacing: 0.04em;
  }

  .hero-sub em { color: var(--neon-blue); font-style: normal; }

  .nav-pills {
    display: flex;
    gap: 0.75rem;
    flex-wrap: wrap;
    justify-content: center;
    margin-bottom: 3.5rem;
  }

  .nav-pill {
    padding: 0.45em 1.4em;
    border-radius: 2px;
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.8rem;
    letter-spacing: 0.12em;
    text-decoration: none;
    cursor: pointer;
    transition: all 0.25s;
  }

  .pill-blue { border: 1px solid var(--neon-blue); color: var(--neon-blue); }
  .pill-blue:hover { background: var(--neon-blue); color: var(--bg-deep); box-shadow: var(--glow-blue); }
  .pill-orange { border: 1px solid var(--neon-orange); color: var(--neon-orange); }
  .pill-orange:hover { background: var(--neon-orange); color: var(--bg-deep); box-shadow: var(--glow-orange); }
  .pill-green { border: 1px solid var(--neon-green); color: var(--neon-green); }
  .pill-green:hover { background: var(--neon-green); color: var(--bg-deep); box-shadow: var(--glow-green); }

  .scroll-hint {
    color: var(--text-dim);
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.72rem;
    letter-spacing: 0.2em;
    animation: bounce 2s ease-in-out infinite;
  }

  @keyframes bounce { 0%,100%{transform:translateY(0)}50%{transform:translateY(6px)} }

  /* === SECTIONS === */
  section { position: relative; z-index: 1; padding: 5rem 1.5rem; }

  .container { max-width: 1080px; margin: 0 auto; }

  .section-label {
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.7rem;
    letter-spacing: 0.3em;
    margin-bottom: 0.6rem;
  }

  .section-title {
    font-family: 'Orbitron', monospace;
    font-size: clamp(1.6rem, 4vw, 2.6rem);
    font-weight: 700;
    line-height: 1.1;
    margin-bottom: 0.5rem;
  }

  .section-divider {
    height: 2px;
    width: 80px;
    border-radius: 2px;
    margin-bottom: 3rem;
  }

  /* === CIRCUIT CARDS === */
  .circuit-grid { display: grid; gap: 2rem; }

  .circuit-card {
    background: var(--bg-card);
    border-radius: 4px;
    padding: 2.2rem 2.5rem;
    position: relative;
    overflow: hidden;
    transition: transform 0.3s;
  }

  .circuit-card::before {
    content: '';
    position: absolute;
    inset: 0;
    border-radius: 4px;
    pointer-events: none;
  }

  .circuit-card:hover { transform: translateY(-3px); }

  .card-blue { border: 1px solid #00d4ff33; }
  .card-blue::before { box-shadow: inset 0 0 40px #00d4ff08; }
  .card-blue .card-accent { color: var(--neon-blue); text-shadow: var(--glow-blue); border-color: var(--neon-blue); }

  .card-orange { border: 1px solid #ff6b0033; }
  .card-orange::before { box-shadow: inset 0 0 40px #ff6b0008; }
  .card-orange .card-accent { color: var(--neon-orange); text-shadow: var(--glow-orange); border-color: var(--neon-orange); }

  .card-green { border: 1px solid #00ff8833; }
  .card-green::before { box-shadow: inset 0 0 40px #00ff8808; }
  .card-green .card-accent { color: var(--neon-green); text-shadow: var(--glow-green); border-color: var(--neon-green); }

  .card-tag {
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.68rem;
    letter-spacing: 0.25em;
    border: 1px solid;
    padding: 0.2em 0.8em;
    border-radius: 2px;
    display: inline-block;
    margin-bottom: 1rem;
  }

  .card-title {
    font-family: 'Orbitron', monospace;
    font-size: 1.45rem;
    font-weight: 700;
    margin-bottom: 0.8rem;
  }

  .card-body { color: var(--text-dim); font-size: 1rem; margin-bottom: 1.5rem; font-weight: 300; }
  .card-body strong { color: var(--text-main); font-weight: 600; }

  /* Analogy box */
  .analogy-box {
    background: rgba(255,255,255,0.03);
    border-left: 3px solid;
    padding: 0.9rem 1.2rem;
    border-radius: 0 3px 3px 0;
    font-size: 0.95rem;
    color: var(--text-dim);
    margin: 1.2rem 0;
    font-style: italic;
  }

  .analogy-box strong { font-style: normal; }

  /* Equation box */
  .eq-box {
    background: #050b14;
    border: 1px solid #1a2a3a;
    border-radius: 4px;
    padding: 1.2rem 1.5rem;
    margin: 1rem 0;
    overflow-x: auto;
    text-align: center;
    font-size: 1.05rem;
  }

  /* Variables grid */
  .vars-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 0.75rem;
    margin-top: 1rem;
  }

  .var-item {
    background: rgba(255,255,255,0.025);
    border: 1px solid #1a2a3a;
    border-radius: 3px;
    padding: 0.6rem 0.9rem;
    font-size: 0.88rem;
  }

  .var-sym {
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.95rem;
    margin-bottom: 0.15rem;
  }

  .var-desc { color: var(--text-dim); font-size: 0.82rem; }

  /* Formulas row */
  .formulas-row {
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;
    margin-top: 1rem;
  }

  .formula-chip {
    background: #050b14;
    border: 1px solid #1e3040;
    border-radius: 3px;
    padding: 0.5rem 1rem;
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.85rem;
    color: var(--text-bright);
  }

  /* === RLC STATES === */
  .states-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 1.5rem;
    margin-top: 2.5rem;
  }

  .state-card {
    background: var(--bg-card);
    border-radius: 4px;
    padding: 1.8rem;
    position: relative;
    overflow: hidden;
  }

  .state-card .state-icon {
    font-size: 2.2rem;
    margin-bottom: 0.7rem;
    display: block;
  }

  .state-card h3 {
    font-family: 'Orbitron', monospace;
    font-size: 1rem;
    font-weight: 700;
    margin-bottom: 0.5rem;
  }

  .state-card p { font-size: 0.92rem; color: var(--text-dim); margin-bottom: 0.9rem; }

  .state-red { border: 1px solid #ff003333; }
  .state-red h3 { color: #ff4466; }
  .state-red .state-condition { color: #ff4466; }

  .state-yellow { border: 1px solid #ffe00033; }
  .state-yellow h3 { color: var(--neon-yellow); }
  .state-yellow .state-condition { color: var(--neon-yellow); }

  .state-cyan { border: 1px solid #00d4ff33; }
  .state-cyan h3 { color: var(--neon-blue); }
  .state-cyan .state-condition { color: var(--neon-blue); }

  .state-condition {
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.8rem;
    letter-spacing: 0.1em;
    margin-bottom: 0.7rem;
    display: block;
  }

  /* Oscillation visualizer */
  .osc-visual {
    height: 48px;
    margin: 0.8rem 0;
    position: relative;
    overflow: hidden;
  }

  .osc-visual canvas { width: 100%; height: 100%; }

  /* === APPLICATIONS === */
  .apps-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 1.5rem;
    margin-top: 2.5rem;
  }

  .app-card {
    background: var(--bg-card);
    border-radius: 4px;
    padding: 2rem;
    border: 1px solid #1a2a3a;
    position: relative;
    overflow: hidden;
    transition: border-color 0.3s, transform 0.3s;
  }

  .app-card:hover { transform: translateY(-4px); }
  .app-card.app-rc:hover { border-color: var(--neon-blue); }
  .app-card.app-rl:hover { border-color: var(--neon-orange); }
  .app-card.app-rlc:hover { border-color: var(--neon-green); }

  .app-icon {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    display: block;
    filter: grayscale(0.3);
  }

  .app-type {
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.65rem;
    letter-spacing: 0.3em;
    margin-bottom: 0.5rem;
  }

  .app-type-rc { color: var(--neon-blue); }
  .app-type-rl { color: var(--neon-orange); }
  .app-type-rlc { color: var(--neon-green); }

  .app-card h3 {
    font-family: 'Orbitron', monospace;
    font-size: 1rem;
    margin-bottom: 0.7rem;
    color: var(--text-bright);
  }

  .app-card p { color: var(--text-dim); font-size: 0.92rem; }

  /* === TABLE === */
  .table-wrapper {
    overflow-x: auto;
    border-radius: 4px;
    border: 1px solid #1a2a3a;
    margin-top: 2.5rem;
  }

  table {
    width: 100%;
    border-collapse: collapse;
    font-size: 0.95rem;
  }

  thead {
    background: #0b1828;
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.78rem;
    letter-spacing: 0.12em;
  }

  thead th { padding: 1rem 1.2rem; text-align: left; color: var(--text-dim); border-bottom: 1px solid #1a2a3a; }

  tbody tr { border-bottom: 1px solid #0f1e2e; transition: background 0.2s; }
  tbody tr:hover { background: rgba(0,212,255,0.04); }
  tbody td { padding: 1rem 1.2rem; }

  .td-feature { color: var(--text-dim); font-size: 0.9rem; }
  .td-rc { color: var(--neon-blue); font-family: 'Share Tech Mono', monospace; font-size: 0.88rem; }
  .td-rl { color: var(--neon-orange); font-family: 'Share Tech Mono', monospace; font-size: 0.88rem; }
  .td-rlc { color: var(--neon-green); font-family: 'Share Tech Mono', monospace; font-size: 0.88rem; }

  .badge {
    display: inline-block;
    padding: 0.18em 0.7em;
    border-radius: 2px;
    font-size: 0.75rem;
    font-family: 'Share Tech Mono', monospace;
  }

  .badge-yes { background: #00ff8820; color: var(--neon-green); border: 1px solid #00ff8840; }
  .badge-no { background: #ff444420; color: #ff6688; border: 1px solid #ff444440; }

  /* === QUIZ === */
  #quiz-section { background: #06101a; }

  .quiz-wrapper {
    max-width: 760px;
    margin: 0 auto;
  }

  .quiz-terminal {
    background: #030a10;
    border: 1px solid #00d4ff44;
    border-radius: 6px;
    overflow: hidden;
    box-shadow: var(--glow-blue);
  }

  .quiz-topbar {
    background: #0a1a26;
    padding: 0.7rem 1.2rem;
    display: flex;
    align-items: center;
    gap: 0.5rem;
    border-bottom: 1px solid #00d4ff22;
  }

  .dot { width: 10px; height: 10px; border-radius: 50%; }
  .dot-red { background: #ff5555; }
  .dot-yellow { background: #ffcc00; }
  .dot-green { background: #55ff88; }

  .quiz-topbar-title {
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.72rem;
    color: var(--text-dim);
    letter-spacing: 0.15em;
    margin-left: 0.5rem;
  }

  .quiz-body { padding: 2rem 2.5rem; }

  .quiz-progress-bar {
    height: 3px;
    background: #0d1e2e;
    border-radius: 2px;
    margin-bottom: 1.8rem;
    overflow: hidden;
  }

  .quiz-progress-fill {
    height: 100%;
    background: linear-gradient(90deg, var(--neon-blue), var(--neon-green));
    border-radius: 2px;
    transition: width 0.5s;
  }

  .quiz-q-num {
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.7rem;
    color: var(--neon-blue);
    letter-spacing: 0.2em;
    margin-bottom: 0.5rem;
  }

  .quiz-question {
    font-family: 'Rajdhani', sans-serif;
    font-size: 1.2rem;
    font-weight: 600;
    color: var(--text-bright);
    margin-bottom: 1.8rem;
    line-height: 1.5;
  }

  .quiz-options { display: grid; gap: 0.75rem; }

  .quiz-option {
    background: #0a1620;
    border: 1px solid #1a2e42;
    border-radius: 4px;
    padding: 0.9rem 1.3rem;
    cursor: pointer;
    transition: all 0.2s;
    display: flex;
    align-items: center;
    gap: 1rem;
    font-size: 0.98rem;
    color: var(--text-main);
  }

  .quiz-option:hover { border-color: var(--neon-blue); background: rgba(0,212,255,0.06); }
  .quiz-option.correct { border-color: var(--neon-green); background: rgba(0,255,136,0.08); color: var(--neon-green); }
  .quiz-option.wrong { border-color: #ff4466; background: rgba(255,68,102,0.08); color: #ff6688; }

  .opt-key {
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.8rem;
    color: var(--text-dim);
    min-width: 20px;
  }

  .quiz-feedback {
    margin-top: 1.2rem;
    padding: 1rem 1.3rem;
    border-radius: 4px;
    font-size: 0.95rem;
    display: none;
  }

  .feedback-correct { background: rgba(0,255,136,0.08); border: 1px solid #00ff8840; color: var(--neon-green); }
  .feedback-wrong { background: rgba(255,68,102,0.08); border: 1px solid #ff446640; color: #ff8899; }

  .quiz-btn {
    margin-top: 1.5rem;
    padding: 0.75em 2em;
    background: transparent;
    border: 1px solid var(--neon-blue);
    color: var(--neon-blue);
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.85rem;
    letter-spacing: 0.15em;
    cursor: pointer;
    border-radius: 3px;
    transition: all 0.25s;
    display: none;
  }

  .quiz-btn:hover { background: var(--neon-blue); color: var(--bg-deep); box-shadow: var(--glow-blue); }

  .quiz-score {
    text-align: center;
    display: none;
    padding: 2rem;
  }

  .score-num {
    font-family: 'Orbitron', monospace;
    font-size: 4rem;
    font-weight: 900;
    color: var(--neon-green);
    text-shadow: var(--glow-green);
  }

  .score-label { color: var(--text-dim); font-size: 1rem; margin-bottom: 1.5rem; }
  .score-msg { font-size: 1.1rem; color: var(--text-main); margin-bottom: 1.5rem; }

  .quiz-restart {
    background: var(--neon-blue);
    color: var(--bg-deep);
    border: none;
    padding: 0.75em 2em;
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.85rem;
    letter-spacing: 0.15em;
    cursor: pointer;
    border-radius: 3px;
    transition: box-shadow 0.25s;
  }

  .quiz-restart:hover { box-shadow: var(--glow-blue); }

  /* === AI SECTION === */
  #ai-section {
    background: linear-gradient(180deg, var(--bg-deep), #030c18);
  }

  .ai-card {
    background: var(--bg-card);
    border: 1px solid #b000ff33;
    border-radius: 4px;
    padding: 2.5rem;
    position: relative;
    overflow: hidden;
  }

  .ai-card::before {
    content: '';
    position: absolute;
    inset: 0;
    box-shadow: inset 0 0 60px #b000ff08;
    pointer-events: none;
  }

  .ai-card h3 {
    font-family: 'Orbitron', monospace;
    font-size: 1.1rem;
    color: var(--neon-purple);
    text-shadow: 0 0 12px #b000ff66;
    margin-bottom: 1rem;
  }

  .ai-card p { color: var(--text-dim); margin-bottom: 1rem; font-size: 0.98rem; }
  .ai-card strong { color: var(--text-main); }

  .ai-uses {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
    gap: 1rem;
    margin-top: 1.5rem;
  }

  .ai-use-item {
    background: rgba(176,0,255,0.06);
    border: 1px solid #b000ff22;
    border-radius: 3px;
    padding: 0.9rem 1rem;
  }

  .ai-use-item .ai-use-title {
    color: #c855ff;
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.78rem;
    letter-spacing: 0.1em;
    margin-bottom: 0.4rem;
  }

  .ai-use-item p { color: var(--text-dim); font-size: 0.85rem; margin: 0; }

  /* === FOOTER === */
  footer {
    position: relative;
    z-index: 1;
    text-align: center;
    padding: 2rem;
    border-top: 1px solid #0d1e2e;
    color: var(--text-dim);
    font-family: 'Share Tech Mono', monospace;
    font-size: 0.72rem;
    letter-spacing: 0.15em;
  }

  /* === RESPONSIVE === */
  @media (max-width: 640px) {
    .circuit-card { padding: 1.5rem; }
    .quiz-body { padding: 1.5rem; }
    .formulas-row { flex-direction: column; }
  }

  /* === SCAN LINES === */
  body::after {
    content: '';
    position: fixed;
    inset: 0;
    background: repeating-linear-gradient(
      0deg,
      transparent,
      transparent 3px,
      rgba(0,0,0,0.03) 3px,
      rgba(0,0,0,0.03) 4px
    );
    pointer-events: none;
    z-index: 9999;
  }

  /* Animations */
  @keyframes fadeInUp {
    from { opacity: 0; transform: translateY(24px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .fade-in { animation: fadeInUp 0.7s ease both; }
  .fade-in-2 { animation: fadeInUp 0.7s 0.15s ease both; }
  .fade-in-3 { animation: fadeInUp 0.7s 0.3s ease both; }
  .fade-in-4 { animation: fadeInUp 0.7s 0.45s ease both; }
</style>
</head>
<body>

<!-- ===== HERO ===== -->
<section class="hero">
  <div class="hero-glow"></div>
  <div class="hero-badge">PROYECTO UNIVERSITARIO — CIRCUITOS ELÉCTRICOS</div>
  <h1 class="fade-in">
    <span class="word-rc">RC</span> ·
    <span class="word-rl">RL</span> ·
    <span class="word-rlc">RLC</span>
  </h1>
  <p class="hero-sub fade-in-2">
    La física del tiempo, la inercia y la resonancia.<br>
    Desde el corazón hasta las estrellas de radio.
  </p>
  <div class="nav-pills fade-in-3">
    <a class="nav-pill pill-blue" href="#rc-section">Circuito RC</a>
    <a class="nav-pill pill-orange" href="#rl-section">Circuito RL</a>
    <a class="nav-pill pill-green" href="#rlc-section">Circuito RLC</a>
    <a class="nav-pill pill-blue" href="#tabla-section">Tabla Comparativa</a>
    <a class="nav-pill pill-orange" href="#quiz-section">Simulador Quiz</a>
  </div>
  <div class="scroll-hint fade-in-4">▼ SCROLL PARA EXPLORAR ▼</div>
</section>

<!-- ===== RC ===== -->
<section id="rc-section">
  <div class="container">
    <div class="section-label" style="color:var(--neon-blue)">// CIRCUITO 01</div>
    <h2 class="section-title" style="color:var(--text-bright)">Resistencia — <span style="color:var(--neon-blue)">Capacitor</span></h2>
    <div class="section-divider" style="background:linear-gradient(90deg,var(--neon-blue),transparent)"></div>

    <div class="circuit-grid">
      <div class="circuit-card card-blue fade-in">
        <span class="card-tag card-accent">FENÓMENO FÍSICO</span>
        <h3 class="card-title card-accent">El Depósito de Carga</h3>
        <p class="card-body">
          Un circuito RC modela el proceso de <strong>almacenamiento y liberación de energía</strong>
          en forma de campo eléctrico. El capacitor actúa como un depósito de carga, mientras
          que la resistencia limita la velocidad a la que esta carga fluye (corriente).
        </p>
        <div class="analogy-box" style="border-color:var(--neon-blue)">
          <strong>⚡ Analogía:</strong> Imagina el capacitor como un globo de agua. La resistencia
          es el ancho de la manguera. A mayor resistencia, más lento se llena (o vacía) el globo.
          El <em>tiempo</em> que tarda en llenarse al 63.2% es la constante τ.
        </div>
        <p class="card-body">
          Aplicando la <strong>Ley de Voltajes de Kirchhoff (LVK)</strong> a un circuito RC en serie:
        </p>
        <div class="eq-box">
          \( V_s = RC\dfrac{dV_C(t)}{dt} + V_C(t) \)
        </div>
        <p class="card-body" style="margin-top:1rem">
          <strong>Solución — Carga</strong> \((V_C(0)=0)\):
        </p>
        <div class="eq-box">\( V_C(t) = V_s\left(1 - e^{-t/\tau}\right) \)</div>
        <p class="card-body" style="margin-top:1rem"><strong>Solución — Descarga</strong> \((V_0)\):</p>
        <div class="eq-box">\( V_C(t) = V_0\,e^{-t/\tau} \)</div>

        <div class="formulas-row">
          <div class="formula-chip">τ = R · C</div>
          <div class="formula-chip">i(t) = (Vs/R) · e^(−t/τ)</div>
        </div>

        <div class="vars-grid" style="margin-top:1.5rem">
          <div class="var-item"><div class="var-sym" style="color:var(--neon-blue)">V<sub>s</sub></div><div class="var-desc">Voltaje fuente (V)</div></div>
          <div class="var-item"><div class="var-sym" style="color:var(--neon-blue)">V<sub>C</sub>(t)</div><div class="var-desc">Voltaje en capacitor (V)</div></div>
          <div class="var-item"><div class="var-sym" style="color:var(--neon-blue)">R</div><div class="var-desc">Resistencia (Ω)</div></div>
          <div class="var-item"><div class="var-sym" style="color:var(--neon-blue)">C</div><div class="var-desc">Capacitancia (F)</div></div>
          <div class="var-item"><div class="var-sym" style="color:var(--neon-blue)">τ = RC</div><div class="var-desc">Constante de tiempo (s)</div></div>
        </div>

        <div class="analogy-box" style="border-color:var(--neon-blue);margin-top:1.5rem">
          <strong>🫀 Comportamiento:</strong> En los primeros 5τ el voltaje cambia rápidamente
          (estado transitorio). Para t &gt; 5τ el capacitor se comporta como circuito abierto:
          corriente → 0, voltaje → máximo.
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ===== RL ===== -->
<section id="rl-section" style="background:#05090f">
  <div class="container">
    <div class="section-label" style="color:var(--neon-orange)">// CIRCUITO 02</div>
    <h2 class="section-title" style="color:var(--text-bright)">Resistencia — <span style="color:var(--neon-orange)">Inductor</span></h2>
    <div class="section-divider" style="background:linear-gradient(90deg,var(--neon-orange),transparent)"></div>

    <div class="circuit-grid">
      <div class="circuit-card card-orange">
        <span class="card-tag card-accent">FENÓMENO FÍSICO</span>
        <h3 class="card-title card-accent">La Inercia de la Corriente</h3>
        <p class="card-body">
          Un circuito RL modela el <strong>almacenamiento de energía en forma de campo magnético</strong>.
          El inductor se opone a los cambios bruscos de corriente. Cuando se aplica un voltaje,
          la corriente no salta a su valor máximo de inmediato.
        </p>
        <div class="analogy-box" style="border-color:var(--neon-orange)">
          <strong>🚂 Analogía (Inercia):</strong> El inductor es como un tren en movimiento.
          No puede detenerse ni acelerarse de golpe. La inductancia L determina cuánta
          "inercia magnética" tiene el sistema. A mayor L, más tarda en establecerse la corriente.
        </div>
        <p class="card-body">
          Aplicando LVK a un circuito RL en serie:
        </p>
        <div class="eq-box">
          \( V_s = R\cdot i(t) + L\dfrac{di(t)}{dt} \)
        </div>
        <p class="card-body" style="margin-top:1rem"><strong>Establecimiento de la corriente</strong> \((i(0)=0)\):</p>
        <div class="eq-box">\( i(t) = \dfrac{V_s}{R}\left(1 - e^{-t/\tau}\right) \)</div>
        <p class="card-body" style="margin-top:1rem"><strong>Caída de la corriente</strong> \((I_0)\):</p>
        <div class="eq-box">\( i(t) = I_0\,e^{-t/\tau} \)</div>

        <div class="formulas-row">
          <div class="formula-chip">τ = L / R</div>
          <div class="formula-chip">V_L(t) = Vs · e^(−t/τ)</div>
        </div>

        <div class="vars-grid" style="margin-top:1.5rem">
          <div class="var-item"><div class="var-sym" style="color:var(--neon-orange)">i(t)</div><div class="var-desc">Corriente del circuito (A)</div></div>
          <div class="var-item"><div class="var-sym" style="color:var(--neon-orange)">L</div><div class="var-desc">Inductancia (H)</div></div>
          <div class="var-item"><div class="var-sym" style="color:var(--neon-orange)">R</div><div class="var-desc">Resistencia (Ω)</div></div>
          <div class="var-item"><div class="var-sym" style="color:var(--neon-orange)">τ = L/R</div><div class="var-desc">Constante de tiempo (s)</div></div>
          <div class="var-item"><div class="var-sym" style="color:var(--neon-orange)">V<sub>L</sub>(t)</div><div class="var-desc">Voltaje en inductor (V)</div></div>
        </div>

        <div class="analogy-box" style="border-color:var(--neon-orange);margin-top:1.5rem">
          <strong>⚡ Estado estacionario:</strong> En corriente continua pura, el inductor se comporta
          como un cortocircuito ideal (V<sub>L</sub> = 0). Si se interrumpe la corriente bruscamente,
          genera picos de <strong>alto voltaje</strong> — principio de las bobinas de encendido.
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ===== RLC ===== -->
<section id="rlc-section">
  <div class="container">
    <div class="section-label" style="color:var(--neon-green)">// CIRCUITO 03</div>
    <h2 class="section-title" style="color:var(--text-bright)">Resistencia — Inductor — <span style="color:var(--neon-green)">Capacitor</span></h2>
    <div class="section-divider" style="background:linear-gradient(90deg,var(--neon-green),transparent)"></div>

    <div class="circuit-card card-green">
      <span class="card-tag card-accent">FENÓMENO FÍSICO — SEGUNDO ORDEN</span>
      <h3 class="card-title card-accent">El Sistema Resonante</h3>
      <p class="card-body">
        El circuito RLC es un <strong>sistema de segundo orden</strong> capaz de almacenar energía en
        dos elementos diferentes: campo eléctrico (capacitor) y campo magnético (inductor).
        La energía <em>oscila</em> entre ambos componentes. La resistencia disipa estas oscilaciones.
      </p>
      <div class="analogy-box" style="border-color:var(--neon-green)">
        <strong>🎵 Analogía (Péndulo):</strong> El inductor y el capacitor son como los extremos
        de un péndulo intercambiando energía potencial y cinética. La resistencia es el rozamiento
        que amortigua el movimiento. Sin R, el péndulo oscilaría para siempre.
      </div>

      <p class="card-body" style="margin-top:1rem">Ecuación diferencial (LVK, derivada respecto al tiempo):</p>
      <div class="eq-box">
        \( \dfrac{d^2i(t)}{dt^2} + \dfrac{R}{L}\dfrac{di(t)}{dt} + \dfrac{1}{LC}\,i(t) = 0 \)
      </div>

      <div class="formulas-row" style="margin-top:1rem">
        <div class="formula-chip">ω₀ = 1/√(LC)</div>
        <div class="formula-chip">α = R / 2L</div>
        <div class="formula-chip">s₁,₂ = −α ± √(α² − ω₀²)</div>
      </div>

      <div class="vars-grid" style="margin-top:1.5rem">
        <div class="var-item"><div class="var-sym" style="color:var(--neon-green)">ω₀</div><div class="var-desc">Frecuencia natural no amortiguada (rad/s)</div></div>
        <div class="var-item"><div class="var-sym" style="color:var(--neon-green)">α</div><div class="var-desc">Factor de amortiguamiento (Np/s)</div></div>
        <div class="var-item"><div class="var-sym" style="color:var(--neon-green)">s₁,₂</div><div class="var-desc">Raíces — determinan el tipo de respuesta</div></div>
        <div class="var-item"><div class="var-sym" style="color:var(--neon-green)">ω<sub>d</sub></div><div class="var-desc">Frecuencia amortiguada = √(ω₀²−α²)</div></div>
      </div>
    </div>

    <!-- THREE STATES -->
    <h3 style="font-family:'Orbitron',monospace;font-size:1.2rem;color:var(--text-bright);margin-top:3rem;margin-bottom:0.5rem">
      Los Tres Regímenes de Amortiguamiento
    </h3>
    <p style="color:var(--text-dim);margin-bottom:0.5rem">La relación entre α y ω₀ determina el destino del sistema.</p>

    <div class="states-grid">
      <div class="state-card state-red">
        <span class="state-icon">📉</span>
        <span class="state-condition">α &gt; ω₀ → Raíces reales y distintas</span>
        <h3>Sobreamortiguado</h3>
        <p>El sistema disipa energía tan rápido que <strong>nunca oscila</strong>. Regresa al equilibrio lentamente siguiendo una suma de exponenciales decrecientes.</p>
        <div class="eq-box" style="font-size:0.85rem">\( i(t) = A_1 e^{s_1 t} + A_2 e^{s_2 t} \)</div>
        <div class="osc-visual"><canvas id="canvas-over"></canvas></div>
      </div>

      <div class="state-card state-yellow">
        <span class="state-icon">⚖️</span>
        <span class="state-condition">α = ω₀ → Raíces reales e iguales</span>
        <h3>Críticamente Amortiguado</h3>
        <p>El estado <strong>óptimo</strong>: alcanza el equilibrio en el menor tiempo posible sin oscilar. Es el diseño ideal para amortiguadores de automóviles.</p>
        <div class="eq-box" style="font-size:0.85rem">\( i(t) = (A_1 + A_2 t)\,e^{-\alpha t} \)</div>
        <div class="osc-visual"><canvas id="canvas-crit"></canvas></div>
      </div>

      <div class="state-card state-cyan">
        <span class="state-icon">〰️</span>
        <span class="state-condition">α &lt; ω₀ → Raíces complejas conjugadas</span>
        <h3>Subamortiguado</h3>
        <p>El sistema <strong>oscila</strong> mientras la amplitud decae exponencialmente. La energía rebota entre L y C antes de disiparse en R.</p>
        <div class="eq-box" style="font-size:0.85rem">\( i(t) = e^{-\alpha t}(B_1\cos\omega_d t + B_2\sin\omega_d t) \)</div>
        <div class="osc-visual"><canvas id="canvas-under"></canvas></div>
      </div>
    </div>
  </div>
</section>

<!-- ===== APPLICATIONS ===== -->
<section id="apps-section" style="background:#05090f">
  <div class="container">
    <div class="section-label" style="color:var(--neon-purple)">// CASOS REALES</div>
    <h2 class="section-title" style="color:var(--text-bright)">Aplicaciones en el <span style="color:var(--neon-purple);text-shadow:0 0 12px #b000ff66">Mundo Real</span></h2>
    <div class="section-divider" style="background:linear-gradient(90deg,var(--neon-purple),transparent)"></div>

    <div class="apps-grid">
      <div class="app-card app-rc">
        <span class="app-icon">🫀</span>
        <div class="app-type app-type-rc">CIRCUITO RC</div>
        <h3>Marcapasos Cardíacos</h3>
        <p>El capacitor se carga a través de una resistencia hasta un umbral de voltaje específico.
          Al alcanzarlo, descarga un pulso eléctrico que estimula el corazón. El valor de RC determina
          exactamente la frecuencia cardíaca artificial, con precisión de milisegundos.</p>
      </div>

      <div class="app-card app-rl">
        <span class="app-icon">🚗</span>
        <div class="app-type app-type-rl">CIRCUITO RL</div>
        <h3>Bobinas de Encendido</h3>
        <p>La bobina de encendido de un motor almacena energía magnética. Al interrumpir la corriente
          bruscamente (di/dt enorme), el inductor genera miles de voltios — suficientes para crear
          la chispa en la bujía que ignita el combustible.</p>
      </div>

      <div class="app-card app-rlc">
        <span class="app-icon">📻</span>
        <div class="app-type app-type-rlc">CIRCUITO RLC</div>
        <h3>Sintonizadores de Radio</h3>
        <p>Al variar la capacitancia con un capacitor ajustable, se modifica la frecuencia de
          resonancia ω₀ del circuito para que coincida exactamente con la frecuencia de la emisora
          deseada, amplificando esa señal y filtrando el resto del espectro.</p>
      </div>
    </div>
  </div>
</section>

<!-- ===== TABLA ===== -->
<section id="tabla-section">
  <div class="container">
    <div class="section-label" style="color:var(--neon-blue)">// COMPARATIVA</div>
    <h2 class="section-title" style="color:var(--text-bright)">Tabla <span style="color:var(--neon-blue)">Interactiva</span></h2>
    <div class="section-divider" style="background:linear-gradient(90deg,var(--neon-blue),transparent)"></div>

    <div class="table-wrapper">
      <table>
        <thead>
          <tr>
            <th>CARACTERÍSTICA</th>
            <th style="color:var(--neon-blue)">CIRCUITO RC</th>
            <th style="color:var(--neon-orange)">CIRCUITO RL</th>
            <th style="color:var(--neon-green)">CIRCUITO RLC</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="td-feature">Orden del sistema</td>
            <td class="td-rc">1er orden</td>
            <td class="td-rl">1er orden</td>
            <td class="td-rlc">2do orden</td>
          </tr>
          <tr>
            <td class="td-feature">Almacenamiento de energía</td>
            <td class="td-rc">Campo eléctrico (voltaje)</td>
            <td class="td-rl">Campo magnético (corriente)</td>
            <td class="td-rlc">Ambos (intercambio)</td>
          </tr>
          <tr>
            <td class="td-feature">Constante de tiempo (τ)</td>
            <td class="td-rc">R · C</td>
            <td class="td-rl">L / R</td>
            <td class="td-rlc">α = R / 2L</td>
          </tr>
          <tr>
            <td class="td-feature">Oscilación posible</td>
            <td><span class="badge badge-no">NO</span></td>
            <td><span class="badge badge-no">NO</span></td>
            <td><span class="badge badge-yes">SÍ (subamortiguado)</span></td>
          </tr>
          <tr>
            <td class="td-feature">Oposición principal</td>
            <td class="td-rc">Cambios de voltaje (dv/dt)</td>
            <td class="td-rl">Cambios de corriente (di/dt)</td>
            <td class="td-rlc">Cambios simultáneos + resonancia</td>
          </tr>
          <tr>
            <td class="td-feature">Ecuación diferencial</td>
            <td class="td-rc">1er orden lineal</td>
            <td class="td-rl">1er orden lineal</td>
            <td class="td-rlc">2do orden homogénea</td>
          </tr>
          <tr>
            <td class="td-feature">Frecuencia de resonancia</td>
            <td><span class="badge badge-no">N/A</span></td>
            <td><span class="badge badge-no">N/A</span></td>
            <td class="td-rlc">ω₀ = 1/√(LC)</td>
          </tr>
          <tr>
            <td class="td-feature">Uso principal</td>
            <td class="td-rc">Filtros, temporización, marcapasos</td>
            <td class="td-rl">Motores, solenoides, protección</td>
            <td class="td-rlc">Sintonizadores, filtros de banda</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</section>

<!-- ===== QUIZ ===== -->
<section id="quiz-section">
  <div class="container">
    <div class="section-label" style="color:var(--neon-orange)">// GAMIFICACIÓN</div>
    <h2 class="section-title" style="color:var(--text-bright)">Simulador de <span style="color:var(--neon-orange)">Decisiones</span></h2>
    <div class="section-divider" style="background:linear-gradient(90deg,var(--neon-orange),transparent)"></div>

    <div class="quiz-wrapper">
      <div class="quiz-terminal">
        <div class="quiz-topbar">
          <div class="dot dot-red"></div>
          <div class="dot dot-yellow"></div>
          <div class="dot dot-green"></div>
          <div class="quiz-topbar-title">CIRCUIT_DECISION_SIMULATOR_v2.1 — MODO EXPERTO</div>
        </div>

        <div class="quiz-body">
          <div class="quiz-progress-bar">
            <div class="quiz-progress-fill" id="quiz-progress" style="width:0%"></div>
          </div>

          <div id="quiz-active">
            <div class="quiz-q-num" id="q-num">PREGUNTA 01 / 07</div>
            <div class="quiz-question" id="q-text">Cargando...</div>
            <div class="quiz-options" id="q-options"></div>
            <div class="quiz-feedback" id="q-feedback"></div>
            <button class="quiz-btn" id="quiz-next">SIGUIENTE →</button>
          </div>

          <div class="quiz-score" id="quiz-score">
            <div class="score-num" id="score-num">0/7</div>
            <div class="score-label">PUNTUACIÓN FINAL</div>
            <div class="score-msg" id="score-msg"></div>
            <button class="quiz-restart" onclick="initQuiz()">⟳ REINICIAR SIMULADOR</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ===== AI SECTION ===== -->
<section id="ai-section">
  <div class="container">
    <div class="section-label" style="color:var(--neon-purple)">// REFLEXIÓN ACADÉMICA</div>
    <h2 class="section-title" style="color:var(--text-bright)">Uso de <span style="color:var(--neon-purple);text-shadow:0 0 12px #b000ff66">Inteligencia Artificial</span></h2>
    <div class="section-divider" style="background:linear-gradient(90deg,var(--neon-purple),transparent)"></div>

    <div class="ai-card">
      <h3>⚙️ Justificación del Uso de IA en Este Proyecto</h3>
      <p>
        El desarrollo de este componente HTML incorporó <strong>herramientas de IA generativa</strong>
        (Claude de Anthropic) como co-piloto técnico y creativo. Esta colaboración fue
        documentada y orientada con criterio académico, siguiendo las siguientes áreas de uso:
      </p>

      <div class="ai-uses">
        <div class="ai-use-item">
          <div class="ai-use-title">// ARQUITECTURA DEL CÓDIGO</div>
          <p>La IA ayudó a estructurar el HTML semántico, el sistema de variables CSS y la
          lógica de gamificación del quiz, que fue revisada y adaptada por el estudiante.</p>
        </div>
        <div class="ai-use-item">
          <div class="ai-use-title">// ANALOGÍAS PEDAGÓGICAS</div>
          <p>Se utilizó IA para generar y refinar las analogías (tren-inercia, globo-condensador,
          péndulo-RLC) que potencian el storytelling del contenido físico.</p>
        </div>
        <div class="ai-use-item">
          <div class="ai-use-title">// DISEÑO VISUAL</div>
          <p>El tema "Electric Dark" con tipografías técnicas (Orbitron, Share Tech Mono) y el
          sistema de resplandor neón fue co-diseñado con asistencia de IA y ajustado manualmente.</p>
        </div>
        <div class="ai-use-item">
          <div class="ai-use-title">// CONTENIDO CIENTÍFICO</div>
          <p>Todo el contenido físico-matemático fue extraído directamente del documento
          <em>circuitos.pdf</em> del curso. La IA no generó fórmulas; las estructuró visualmente.</p>
        </div>
        <div class="ai-use-item">
          <div class="ai-use-title">// VERIFICACIÓN CRÍTICA</div>
          <p>El estudiante verificó cada ecuación, ejemplo de aplicación real y explicación
          de variables contra la fuente académica original antes de publicar.</p>
        </div>
        <div class="ai-use-item">
          <div class="ai-use-title">// LIMITACIONES RECONOCIDAS</div>
          <p>La IA puede generar errores sutiles en expresiones matemáticas complejas.
          El pensamiento crítico humano es irreemplazable para la validación final.</p>
        </div>
      </div>

      <p style="margin-top:2rem;font-size:0.9rem;color:var(--text-dim)">
        <strong style="color:var(--neon-purple)">Conclusión:</strong> La IA fue una herramienta de amplificación creativa y técnica,
        no un sustituto del aprendizaje. Comprender los circuitos RC, RL y RLC fue el requisito
        previo para poder dirigir, corregir y validar cada aspecto del código generado.
      </p>
    </div>
  </div>
</section>

<footer>
  <p>CIRCUITOS RC · RL · RLC &nbsp;|&nbsp; PROYECTO UNIVERSITARIO &nbsp;|&nbsp; ELECTRIC DARK v1.0</p>
  <p style="margin-top:0.5rem;font-size:0.65rem;opacity:0.5">Contenido basado en circuitos.pdf del curso · Diseño: Electric Dark Theme</p>
</footer>

<script>
// =====================
// OSCILLATION CANVASES
// =====================
function drawOscillation(canvasId, type) {
  const canvas = document.getElementById(canvasId);
  if (!canvas) return;
  const ctx = canvas.getContext('2d');
  const W = canvas.offsetWidth || 280;
  const H = canvas.offsetHeight || 48;
  canvas.width = W;
  canvas.height = H;

  const pts = 300;
  ctx.clearRect(0, 0, W, H);

  let colors = { over: '#ff4466', crit: '#ffe000', under: '#00d4ff' };
  let color = type === 'over' ? colors.over : type === 'crit' ? colors.crit : colors.under;

  ctx.beginPath();
  ctx.strokeStyle = color;
  ctx.lineWidth = 1.5;
  ctx.shadowColor = color;
  ctx.shadowBlur = 6;

  for (let i = 0; i < pts; i++) {
    const x = (i / pts) * W;
    const t = (i / pts) * 6;
    let y;
    if (type === 'over') {
      y = H/2 - (H/2.4) * (0.6*Math.exp(-1.5*t) + 0.4*Math.exp(-4*t));
    } else if (type === 'crit') {
      y = H/2 - (H/2.4) * (1 + 2*t) * Math.exp(-2*t);
    } else {
      y = H/2 - (H/2.4) * Math.exp(-0.3*t) * Math.cos(2.5*t);
    }
    i === 0 ? ctx.moveTo(x, y) : ctx.lineTo(x, y);
  }
  ctx.stroke();

  // zero line
  ctx.beginPath();
  ctx.strokeStyle = '#1a2a3a';
  ctx.lineWidth = 1;
  ctx.shadowBlur = 0;
  ctx.setLineDash([4, 4]);
  ctx.moveTo(0, H/2);
  ctx.lineTo(W, H/2);
  ctx.stroke();
  ctx.setLineDash([]);
}

window.addEventListener('load', () => {
  drawOscillation('canvas-over', 'over');
  drawOscillation('canvas-crit', 'crit');
  drawOscillation('canvas-under', 'under');
});

// =====================
// QUIZ ENGINE
// =====================
const quizData = [
  {
    q: "Tienes un circuito RC y necesitas que reaccione MÁS RÁPIDO a los cambios de voltaje. ¿Qué parámetro debes cambiar?",
    opts: [
      "Aumentar R para que haya más oposición",
      "Disminuir R o C para reducir τ",
      "Aumentar C para almacenar más carga",
      "Aumentar la fuente de voltaje Vs"
    ],
    correct: 1,
    feedback: "✅ Correcto. τ = RC. Al disminuir R o C, τ se reduce, y el circuito responde más rápido a los cambios. Es la misma razón por la que los circuitos de alta velocidad usan capacitores pequeños."
  },
  {
    q: "En un circuito RL, el inductor se comporta como un CORTOCIRCUITO IDEAL en estado estacionario de corriente continua. ¿Por qué?",
    opts: [
      "Porque L = 0 en DC",
      "Porque V_L = L·(di/dt) = 0 cuando la corriente es constante",
      "Porque R domina el circuito siempre",
      "Porque la corriente máxima es Vs/L"
    ],
    correct: 1,
    feedback: "✅ Exacto. En estado estacionario DC, di/dt = 0, entonces V_L = L·(0) = 0. El inductor no presenta oposición a la corriente constante, actuando como un cable ideal."
  },
  {
    q: "Un circuito RLC oscila indefinidamente. ¿Qué modificación eliminaría las oscilaciones llevando el sistema al estado CRÍTICAMENTE AMORTIGUADO?",
    opts: [
      "Aumentar L para dar más inercia al sistema",
      "Disminuir C para bajar ω₀",
      "Ajustar R hasta que α = ω₀ = R/(2L)",
      "Quitar la resistencia del circuito"
    ],
    correct: 2,
    feedback: "✅ Perfecto. El amortiguamiento crítico ocurre cuando α = ω₀, es decir R = 2√(L/C). Este es el diseño óptimo: no oscila y llega al equilibrio en el menor tiempo posible."
  },
  {
    q: "Un marcapasos usa circuito RC. Para aumentar la frecuencia cardíaca artificial (más pulsos por segundo), el ingeniero debe:",
    opts: [
      "Aumentar R·C para que el capacitor tarde más en cargarse",
      "Disminuir R·C para que el capacitor alcance el umbral más rápido",
      "Aumentar el voltaje umbral de disparo",
      "Cambiar el capacitor por un inductor"
    ],
    correct: 1,
    feedback: "✅ Correcto. El tiempo entre pulsos depende de cuánto tarda el capacitor en cargarse hasta el umbral. Al reducir τ=RC, el capacitor llega al umbral más rápido → más pulsos por segundo → mayor frecuencia cardíaca."
  },
  {
    q: "¿Cuál de los siguientes circuitos puede exhibir RESONANCIA y por qué?",
    opts: [
      "Circuito RC, porque el capacitor almacena energía",
      "Circuito RL, porque el inductor opone cambios de corriente",
      "Circuito RLC, porque la energía puede oscilar entre L y C",
      "Todos pueden resonar si se aplica la frecuencia correcta"
    ],
    correct: 2,
    feedback: "✅ Solo el RLC puede resonar. La resonancia requiere que la energía intercambie entre dos elementos almacenadores: el campo eléctrico del capacitor y el magnético del inductor. RC y RL solo tienen un elemento almacenador cada uno."
  },
  {
    q: "La bobina de encendido de un auto interrumpe bruscamente la corriente. ¿Qué fenómeno RL explica el alto voltaje generado?",
    opts: [
      "El capacitor libera su carga almacenada",
      "V_L = L·(di/dt) → di/dt enorme produce voltaje enorme",
      "La resistencia bloquea la corriente y genera calor",
      "El inductor actúa como batería en estado estacionario"
    ],
    correct: 1,
    feedback: "✅ Exactamente. V_L = L·(di/dt). Al interrumpir la corriente bruscamente, di/dt es enorme (negativo), generando miles de voltios. Esta tensión cruza hacia la bujía y crea la chispa de ignición."
  },
  {
    q: "Para sintonizar una radio analógica a 100 MHz usando un circuito RLC, ¿qué parámetro ajustas y cómo?",
    opts: [
      "Aumentar R para disipar más energía en esa frecuencia",
      "Ajustar L o C para que ω₀ = 2π×100MHz = 1/√(LC)",
      "Reducir α para que el sistema oscile más rápido",
      "Aumentar la fuente de voltaje para más amplitud"
    ],
    correct: 1,
    feedback: "✅ Perfecto. La resonancia ocurre en ω₀ = 1/√(LC). Para 100 MHz, ajustas el capacitor variable (girando el dial) hasta que ω₀ coincida con 2π×10⁸ rad/s. El circuito amplifica esa frecuencia y filtra el resto."
  }
];

let currentQ = 0;
let score = 0;
let answered = false;

function initQuiz() {
  currentQ = 0;
  score = 0;
  answered = false;
  document.getElementById('quiz-active').style.display = 'block';
  document.getElementById('quiz-score').style.display = 'none';
  renderQuestion();
}

function renderQuestion() {
  answered = false;
  const q = quizData[currentQ];
  const total = quizData.length;

  document.getElementById('q-num').textContent = `PREGUNTA ${String(currentQ+1).padStart(2,'0')} / ${String(total).padStart(2,'0')}`;
  document.getElementById('q-text').textContent = q.q;
  document.getElementById('quiz-progress').style.width = `${(currentQ/total)*100}%`;

  const feedback = document.getElementById('q-feedback');
  feedback.style.display = 'none';
  feedback.className = 'quiz-feedback';

  const nextBtn = document.getElementById('quiz-next');
  nextBtn.style.display = 'none';

  const optContainer = document.getElementById('q-options');
  optContainer.innerHTML = '';
  const keys = ['A', 'B', 'C', 'D'];

  q.opts.forEach((opt, i) => {
    const btn = document.createElement('button');
    btn.className = 'quiz-option';
    btn.innerHTML = `<span class="opt-key">${keys[i]}</span> ${opt}`;
    btn.onclick = () => selectAnswer(i);
    optContainer.appendChild(btn);
  });
}

function selectAnswer(idx) {
  if (answered) return;
  answered = true;

  const q = quizData[currentQ];
  const opts = document.querySelectorAll('.quiz-option');
  const feedback = document.getElementById('q-feedback');
  const nextBtn = document.getElementById('quiz-next');

  opts[idx].classList.add(idx === q.correct ? 'correct' : 'wrong');
  if (idx !== q.correct) opts[q.correct].classList.add('correct');

  if (idx === q.correct) {
    score++;
    feedback.className = 'quiz-feedback feedback-correct';
  } else {
    feedback.className = 'quiz-feedback feedback-wrong';
  }
  feedback.textContent = q.feedback;
  feedback.style.display = 'block';

  nextBtn.textContent = currentQ < quizData.length - 1 ? 'SIGUIENTE →' : 'VER RESULTADOS →';
  nextBtn.style.display = 'inline-block';
}

document.getElementById('quiz-next').onclick = () => {
  currentQ++;
  if (currentQ >= quizData.length) {
    showScore();
  } else {
    renderQuestion();
  }
};

function showScore() {
  document.getElementById('quiz-active').style.display = 'none';
  document.getElementById('quiz-score').style.display = 'block';
  document.getElementById('quiz-progress').style.width = '100%';
  document.getElementById('score-num').textContent = `${score}/${quizData.length}`;

  const pct = score / quizData.length;
  let msg;
  if (pct === 1) msg = "🏆 ¡Perfecto! Dominas los circuitos RC, RL y RLC. Estás listo para el mundo real.";
  else if (pct >= 0.7) msg = "⚡ Muy bien. Tienes sólida comprensión. Repasa los casos que fallaste.";
  else if (pct >= 0.5) msg = "🔧 En progreso. Vuelve a revisar las secciones de τ y amortiguamiento.";
  else msg = "📚 Continúa estudiando. Lee cada sección con calma y vuelve a intentarlo.";

  document.getElementById('score-msg').textContent = msg;
}

// Init
initQuiz();

// MathJax render after load
window.addEventListener('load', () => {
  if (window.MathJax) MathJax.typesetPromise();
});
</script>
</body>
</html>
