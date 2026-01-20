---
layout: page
title: 손승하
permalink: /
---

<style>
  /* =====================
     HERO (Top Section)
  ===================== */
  .simple-hero{
    max-width: 1000px;
    margin: 20px auto 40px;
    padding: 80px 20px;
    text-align: center;
    color: #ffffff;

    /* ✅ 배경 이미지: /assets/img/hero.jpg 를 넣거나 파일명 바꾸기 */
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
    margin: 0 0 10px;
    letter-spacing: -0.5px;
  }

  .simple-hero h2{
    font-size: 26px;
    font-weight: 800;
    margin: 0 0 18px;
    opacity: .95;
  }

  .simple-hero p{
    font-size: 16px;
    line-height: 1.7;
    margin: 0;
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
    .simple-hero{ padding: 64px 16px; }
    .simple-hero h1{ font-size: 32px; }
    .simple-hero h2{ font-size: 20px; }
  }

  /* =====================
     Resume Card
  ===================== */
  .resume-card{
    max-width:900px;
    margin:0 auto 32px;
    overflow-x:auto;
  }
  .resume-table{
    width:100%;
    border-collapse:collapse;
    table-layout:fixed;
  }
  .resume-table th,
  .resume-table td{
    border:1px solid #333;
    padding:10px;
    vertical-align:middle;
    font-size:15px;
  }
  .resume-table th{
    background:#f5f5f5;
    width:120px;
    text-align:left;
  }
  .resume-photo{
    width:170px;
    text-align:center;
    background:#fff;
  }
  .resume-photo img{
    width:140px;
    height:auto;
    border:1px solid #999;
  }

  /* =====================
     SKILLS (White Chips)
  ===================== */
  :root{
    --outer:#f6e27d;          /* 큰 노란 배경 */
    --inner:#fff3c4;          /* 안쪽 카드 */
    --border:rgba(17,24,39,.12);
    --shadow:0 12px 26px rgba(0,0,0,.12);

    /* 칩: 흰 배경 + 검정 글씨 */
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

  /* grid 고정 → Embedded 내려가는 문제 해결 */
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

  /* 가로 나열 */
  .skill-tags{
    display:flex;
    flex-wrap:wrap;
    gap:10px;
    align-items:center;
    min-width:0;
  }

  .chip{
    padding:8px 14px;
    border-radius:999px;
    font-weight:700;
    font-size:14px;
    line-height:1;
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
     Resume
===================== -->
<div class="resume-card">
  <table class="resume-table">
    <tr>
      <td class="resume-photo" rowspan="4">
        <img src="/assets/img/son-face.jpg" alt="손승하 프로필 사진">
      </td>
      <th>이름</th>
      <td>손승하</td>
      <th>영문명</th>
      <td>Son Seung Ha</td>
    </tr>
    <tr>
      <th>지원분야</th>
      <td>마케터</td>
      <th>생년월일</th>
      <td>2002년</td>
    </tr>
    <tr>
      <th>휴대폰</th>
      <td>010-5535-1932</td>
      <th>성별</th>
      <td>남</td>
    </tr>
    <tr>
      <th>E-mail</th>
      <td colspan="3">ssha0730@naver.com</td>
    </tr>
  </table>
</div>

---

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
