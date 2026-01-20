---
layout: page
permalink: /
---

<style>
  /* =====================
     HERO
  ===================== */
  .simple-hero{
    max-width: 1000px;
    margin: 30px auto 50px;
    padding: 80px 20px;
    text-align: center;
    color: #ffffff;

    background-image:
      linear-gradient(rgba(0,0,0,.55), rgba(0,0,0,.55)),
      url('/assets/img/hero.jpg');
    background-size: cover;
    background-position: center;
    border-radius: 18px;
    box-shadow: 0 18px 40px rgba(0,0,0,.18);
  }

  .simple-hero h1{
    font-size: 44px;
    font-weight: 900;
    margin-bottom: 10px;
  }

  .simple-hero h2{
    font-size: 26px;
    font-weight: 800;
    margin-bottom: 18px;
    opacity: .95;
  }

  .simple-hero p{
    font-size: 16px;
    line-height: 1.7;
    opacity: .92;
  }

  .hero-hr{
    width: 44px;
    height: 3px;
    background: #ff6a3d;
    margin: 16px auto 18px;
    border-radius: 999px;
  }

  @media (max-width: 720px){
    .simple-hero h1{ font-size: 32px; }
    .simple-hero h2{ font-size: 20px; }
  }

  /* =====================
     SKILLS
  ===================== */
  :root{
    --outer:#f6e27d;
    --inner:#fff3c4;
    --border:rgba(17,24,39,.12);
    --shadow:0 12px 26px rgba(0,0,0,.12);

    --chip-bg:#ffffff;
    --chip-text:#111111;
    --chip-border:#d1d5db;

    --icon-bg:#fff1b8;
    --text:#1f2937;
  }

  .skill-box{
    max-width:900px;
    margin:20px auto;
    padding:20px;
    border-radius:18px;
    background:var(--outer);
    box-shadow:var(--shadow);
  }

  .skill-card{
    border-radius:16px;
    background:var(--inner);
    padding:18px;
    border:1px solid var(--border);
  }

  .skill-row{
    display:grid;
    grid-template-columns:170px 1fr;
    gap:16px;
    padding:14px 0;
    align-items:start;
  }

  @media (max-width:720px){
    .skill-row{
      grid-template-columns:1fr;
    }
  }

  .skill-label{
    display:flex;
    gap:10px;
    align-items:center;
    font-weight:800;
    font-size:18px;
    color:var(--text);
    white-space:nowrap;
  }

  .skill-icon{
    width:34px;
    height:34px;
    border-radius:10px;
    display:inline-flex;
    align-items:center;
    justify-content:center;
    background:var(--icon-bg);
    border:1px solid var(--border);
  }

  .skill-tags{
    display:flex;
    flex-wrap:wrap;
    gap:10px;
    align-items:center;
  }

  .chip{
    padding:8px 14px;
    border-radius:999px;
    font-weight:700;
    font-size:14px;
    background:var(--chip-bg);
    color:var(--chip-text);
    border:1px solid var(--chip-border);
    white-space:nowrap;
  }

  .chip:hover{
    background:#f9fafb;
    border-color:#9ca3af;
  }
</style>

<!-- =====================
     HERO
===================== -->
<section class="simple-hero">
  <h1>- 손승하 -</h1>
  <h2>AI시스템 전공 포트폴리오</h2>
  <div class="hero-hr"></div>
  <p>
    안녕하세요.<br>
    기술을 이해하는 마케터 손승하입니다.
  </p>
</section>

<!-- =====================
     SKILLS
===================== -->
<h2>🔗 SKILLS</h2>

<div class="skill-box">
  <div class="skill-card">

    <div class="skill-row">
      <div class="skill-label"><span class="skill-icon">🤖</span> AI</div>
      <div class="skill-tags">
        <span class="chip">YOLO</span>
        <span class="chip">TensorFlow</span>
        <span class="chip">OpenCV</span>
        <span class="chip">Hailo-8</span>
      </div>
    </div>

    <div class="skill-row">
      <div class="skill-label"><span class="skill-icon">💻</span> Language</div>
      <div class="skill-tags">
        <span class="chip">Python</span>
        <span class="chip">C</span>
        <span class="chip">C++</span>
        <span class="chip">Java</span>
        <span class="chip">SQL</span>
      </div>
    </div>

    <div class="skill-row">
      <div class="skill-label"><span class="skill-icon">⚙️</span> Embedded</div>
      <div class="skill-tags">
        <span class="chip">Arduino</span>
        <span class="chip">Raspberry Pi</span>
        <span class="chip">Linux</span>
        <span class="chip">Embedded System</span>
        <span class="chip">Firmware</span>
      </div>
    </div>

    <div class="skill-row">
      <div class="skill-label"><span class="skill-icon">🌐</span> System / IoT</div>
      <div class="skill-tags">
        <span class="chip">IoT</span>
        <span class="chip">Network Programming</span>
        <span class="chip">Database</span>
        <span class="chip">Cloud Computing</span>
      </div>
    </div>

  </div>
</div>
