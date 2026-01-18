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
    margin:0 auto 30px;
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
     SKILLS (Chip UI)
  ===================== */
  .skill-box{
    max-width:900px;
    margin:20px auto;
    padding:20px;
    border-radius:18px;
    background:#f7e27a;
    box-shadow:0 10px 22px rgba(0,0,0,.12);
  }
  .skill-card{
    border-radius:16px;
    background:#fff3c4;
    padding:18px;
  }
  .skill-row{
    display:flex;
    gap:14px;
    padding:12px 0;
    align-items:flex-start;
    flex-wrap:wrap;
  }
  .skill-label{
    min-width:140px;
    display:flex;
    gap:10px;
    align-items:center;
    font-weight:800;
    font-size:18px;
  }
  .skill-icon{
    width:34px;
    height:34px;
    border-radius:8px;
    display:inline-flex;
    align-items:center;
    justify-content:center;
    background:#ffe08a;
    border:2px solid rgba(0,0,0,.08);
  }
  .skill-tags{
    display:flex;
    flex-wrap:wrap;
    gap:10px;
  }
  .chip{
    display:inline-block;
    padding:7px 14px;
    border-radius:999px;
    font-weight:700;
    font-size:14px;
    line-height:1;
    color:#111;
    background:#e5e7eb;
  }
  .blue{background:#3b82f6;color:#fff;}
  .yellow{background:#f59e0b;color:#111;}
  .green{background:#22c55e;color:#fff;}
  .red{background:#ef4444;color:#fff;}
  .purple{background:#a855f7;color:#fff;}
  .gray{background:#111827;color:#fff;}
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
      <div class="skill-label">
        <span class="skill-icon">🤖</span> AI
      </div>
      <div class="skill-tags">
        <span class="chip blue">YOLO</span>
        <span class="chip yellow">TensorFlow</span>
        <span class="chip purple">OpenCV</span>
        <span class="chip gray">Hailo-8</span>
      </div>
    </div>

    <div class="skill-row">
      <div class="skill-label">
        <span class="skill-icon">💻</span> Language
      </div>
      <div class="skill-tags">
        <span class="chip blue">Python</span>
        <span class="chip gray">C</span>
        <span class="chip gray">C++</span>
        <span class="chip red">Java</span>
        <span class="chip green">SQL</span>
      </div>
    </div>

    <div class="skill-row">
      <div class="skill-label">
        <span class="skill-icon">⚙️</span> Embedded
      </div>
      <div class="skill-tags">
        <span class="chip yellow">Arduino</span>
        <span class="chip red">Raspberry Pi</span>
        <span class="chip gray">Linux</span>
        <span class="chip purple">Embedded System</span>
        <span class="chip green">Firmware</span>
      </div>
    </div>

    <div class="skill-row">
      <div class="skill-label">
        <span class="skill-icon">🌐</span> System / IoT
      </div>
      <div class="skill-tags">
        <span class="chip blue">IoT</span>
        <span class="chip purple">Network Programming</span>
        <span class="chip gray">Database</span>
        <span class="chip green">Cloud Computing</span>
      </div>
    </div>

  </div>
</div>
