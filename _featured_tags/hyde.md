---
layout: page
title: Portfolio
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
    linear-gradient(rgba(0,0,0,0.35), rgba(0,0,0,0.35)),
    url('/assets/img/computer.jpg');
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
   SECTION TITLE (ABOUT / SKILLS 공통)
===================== */
.section-title{
  display:flex;
  justify-content:center;
  align-items:center;
  gap:12px;
  font-size:28px;
  font-weight:900;
  margin:60px 0 10px;
}

.section-hr{
  width:90px;
  height:3px;
  background:#111;
  margin:0 auto 30px;
  border-radius:999px;
}

/* =====================
   ABOUT ME
===================== */
.about-wrap{
  max-width:1000px;
  margin:60px auto 20px;
  padding:0 20px;
}

/* ✅ 사진(왼쪽) + 정보(오른쪽) 같은 줄 */
.about-top{
  display:grid;
  grid-template-columns: 260px 1fr;
  gap: 30px 60px;
  align-items:start;
}

/* 사진 영역 */
.about-photo{
  display:flex;
  justify-content:flex-start;
  margin-bottom:0;
}

/* ✅ 흐림 방지용: shadow/radius를 img가 아니라 frame에 적용 */
.photo-frame{
  width:220px;
  height:280px;
  border-radius:14px;
  overflow:hidden;
  border:1px solid #e5e7eb;
  box-shadow:0 8px 20px rgba(0,0,0,.15);
  background:#fff;
}

.photo-frame img{
  width:100%;
  height:100%;
  object-fit:cover;
  display:block; /* ✅ 미세한 흐림/여백 방지 */
}

/* 오른쪽 정보 그리드 */
.about-grid{
  display:grid;
  grid-template-columns: repeat(2, minmax(220px, 1fr));
  gap:22px 50px;
}

/* 모바일 */
@media (max-width:820px){
  .about-top{
    grid-template-columns: 1fr;
    gap: 24px;
  }
  .about-photo{
    justify-content:center;
  }
  .about-grid{
    grid-template-columns:1fr;
  }
}

/* 모바일 사진 크기 */
@media (max-width:480px){
  .photo-frame{
    width:170px;
    height:220px;
  }
}

.about-item{
  display:flex;
  gap:16px;
  align-items:center;
}

.about-icon{
  width:44px;
  height:44px;
  border-radius:12px;
  background:#f3f4f6;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:22px;
  border:1px solid #e5e7eb;
}

.about-label{
  font-weight:900;
  margin-bottom:6px;
}

.about-value{
  color:#4b5563;
  font-size:15px;
  line-height:1.5;
}

/* =====================
   SKILLS
===================== */
:root{
  --outer:#f3f4f6;
  --inner:#ffffff;
  --border:rgba(17,24,39,.12);
  --shadow:0 12px 26px rgba(0,0,0,.12);

  --chip-bg:#ffffff;
  --chip-text:#111111;
  --chip-border:#d1d5db;

  --icon-bg:#e5e7eb;
  --text:#1f2937;
}

.skill-box{
  max-width:900px;
  margin:20px auto 60px;
  padding:20px;
  border-radius:18px;
  background:var(--outer);
  box-shadow:var(--shadow);
  border:1px solid var(--border);
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
}

@media (max-width:720px){
  .skill-row{ grid-template-columns:1fr; }
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
  background:var(--icon-bg);
  display:flex;
  align-items:center;
  justify-content:center;
  border:1px solid var(--border);
}

.skill-tags{
  display:flex;
  flex-wrap:wrap;
  gap:10px;
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
    배운 것을 직접 적용하며 성장해온<br>
    손승하입니다.
  </p>
</section>

<!-- =====================
     ABOUT ME
===================== -->
<section class="about-wrap">
  <div class="section-title">ABOUT ME</div>
  <div class="section-hr"></div>

  <div class="about-top">
    <div class="about-photo">
      <div class="photo-frame">
        <img src="/assets/img/son-face.jpg" alt="손승하 프로필 사진">
      </div>
    </div>

    <div class="about-grid">
      <div class="about-item">
        <div class="about-icon">👤</div>
        <div>
          <div class="about-label">이름</div>
          <div class="about-value">손승하</div>
        </div>
      </div>

      <div class="about-item">
        <div class="about-icon">📅</div>
        <div>
          <div class="about-label">생년</div>
          <div class="about-value">2002년</div>
        </div>
      </div>

      <div class="about-item">
        <div class="about-icon">📍</div>
        <div>
          <div class="about-label">위치</div>
          <div class="about-value">경기도 수원시</div>
        </div>
      </div>

      <div class="about-item">
        <div class="about-icon">📞</div>
        <div>
          <div class="about-label">연락처</div>
          <div class="about-value">010-5535-1932</div>
        </div>
      </div>

      <div class="about-item">
        <div class="about-icon">✉️</div>
        <div>
          <div class="about-label">이메일</div>
          <div class="about-value">ssha0730@naver.com</div>
        </div>
      </div>

      <div class="about-item">
        <div class="about-icon">🎓</div>
        <div>
          <div class="about-label">학력</div>
          <div class="about-value">대림대학교 AI시스템학과</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- =====================
     SKILLS
===================== -->
<div class="section-title">SKILLS</div>
<div class="section-hr"></div>

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
