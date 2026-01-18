---
layout: page
title: 손승하
permalink: /
---

<style>
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
     SKILLS (Grouped Colors)
  ===================== */
  :root{
    --outer:#f6e27d;
    --inner:#fff3c4;
    --border:rgba(17,24,39,.12);
    --shadow:0 12px 26px rgba(0,0,0,.12);
    --text:#1f2937;

    /* 색상 그룹 */
    --chip-tech-bg:#e0e7ff;      /* AI + Embedded */
    --chip-tech-text:#1e3a8a;

    --chip-lang-bg:#dcfce7;      /* Language + System */
    --chip-lang-text:#065f46;

    --icon-bg:#fff1b8;
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
    padding:16px 0;
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
    flex-direction:column;   /* ⭐ 한 개당 한 줄 */
    gap:8px;
  }

  .chip{
    padding:8px 14px;
    border-radius:999px;
    font-weight:700;
    font-size:14px;
    line-height:1.2;
    width:fit-content;
    border:1px solid var(--border);
  }

  /* 그룹별 색상 */
  .chip.tech{
    background:var(--chip-tech-bg);
    color:var(--chip-tech-text);
  }
  .chip.lang{
    background:var(--chip-lang-bg);
    color:var(--chip-lang-text);
  }
</style>

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

<!-- =====================
     SKILLS
===================== -->
<h2>🔗 SKILLS</h2>

<div class="skill-box">
  <div class="skill-card">

    <div class="skill-row">
      <div class="skill-label"><span class="skill-icon">🤖</span> AI</div>
      <div class="skill-tags">
        <span class="chip tech">YOLO</span>
        <span class="chip tech">TensorFlow</span>
        <span class="chip tech">OpenCV</span>
        <span class="chip tech">Hailo-8</span>
      </div>
    </div>

    <div class="skill-row">
      <div class="skill-label"><span class="skill-icon">💻</span> Language</div>
      <div class="skill-tags">
        <span class="chip lang">Python</span>
        <span class="chip lang">C</span>
        <span class="chip lang">C++</span>
        <span class="chip lang">Java</span>
        <span class="chip lang">SQL</span>
      </div>
    </div>

    <div class="skill-row">
      <div class="skill-label"><span class="skill-icon">⚙️</span> Embedded</div>
      <div class="skill-tags">
        <span class="chip tech">Arduino</span>
        <span class="chip tech">Raspberry Pi</span>
        <span class="chip tech">Linux</span>
        <span class="chip tech">Embedded System</span>
        <span class="chip tech">Firmware</span>
      </div>
    </div>

    <div class="skill-row">
      <div class="skill-label"><span class="skill-icon">🌐</span> System / IoT</div>
      <div class="skill-tags">
        <span class="chip lang">IoT</span>
        <span class="chip lang">Network Programming</span>
        <span class="chip lang">Database</span>
        <span class="chip lang">Cloud Computing</span>
      </div>
    </div>

  </div>
</div>
