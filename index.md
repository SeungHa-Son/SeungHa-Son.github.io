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
   SECTION TITLE
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

.about-top{
  display:grid;
  grid-template-columns: 260px 1fr;
  gap: 30px 60px;
  align-items:start;
}

.about-photo{
  display:flex;
  justify-content:flex-start;
  margin-bottom:0;
}

/* frame에만 radius/shadow */
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
  display:block;
}

.about-grid{
  display:grid;
  grid-template-columns: repeat(2, minmax(220px, 1fr));
  gap:22px 50px;
}

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

/* =====================
   PROJECTS
===================== */
.projects-wrap{
  max-width:1100px;
  margin:20px auto 80px;
  padding:0 20px;
}

/* ✅ 1열로 넓게 */
.projects-grid{
  display:grid;
  grid-template-columns:1fr;
  gap:26px;
}

.project-card{
  background:#ffffff;
  border:1px solid rgba(17,24,39,.12);
  border-radius:18px;
  padding:22px;
  box-shadow:0 12px 26px rgba(0,0,0,.12);
}

/* ✅ 배지 + GitHub 버튼 같은 줄 */
.project-head{
  display:flex;
  align-items:center;
  justify-content:space-between;
  gap:12px;
}

.project-badge{
  display:inline-block;
  padding:7px 12px;
  border-radius:10px;
  font-weight:900;
  font-size:13px;
  background:#ef4444;
  color:#ffffff;
}

.project-title{
  margin:12px 0 10px;
  font-size:18px;
  font-weight:900;
  line-height:1.35;
  color:#111827;
}

.project-desc{
  color:#374151;
  font-size:14px;
  line-height:1.7;
  margin:0 0 12px;
}

.project-list{
  margin:0;
  padding-left:18px;
  color:#111827;
  font-size:14px;
  line-height:1.7;
}

.project-tags{
  margin-top:14px;
  display:flex;
  flex-wrap:wrap;
  gap:10px;
}

/* ✅ project-chip 색상을 skills chip과 통일 */
.project-chip{
  padding:8px 14px;
  border-radius:999px;
  font-weight:700;
  font-size:14px;
  background:var(--chip-bg);
  color:var(--chip-text);
  border:1px solid var(--chip-border);
  white-space:nowrap;
}

.project-chip:hover{
  background:#f9fafb;
  border-color:#9ca3af;
}

/* ✅ GitHub 버튼: 배지 색으로 채우고 글자 흰색 */
.project-btn{
  display:inline-flex;
  align-items:center;
  justify-content:center;
  padding:8px 12px;
  border-radius:10px;
  border:1px solid #ef4444;
  background:#ef4444;
  font-weight:900;
  font-size:13px;
  text-decoration:none;
  color:#ffffff;
  line-height:1;
}

.project-btn:hover{
  filter:brightness(0.95);
}
</style>

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

<section class="about-wrap">
  <div class="section-title">ABOUT ME</div>
  <div class="section-hr"></div>

  <div class="about-top">
    <div class="about-photo">
      <div class="photo-frame">
        <img
          src="/assets/img/son-face-220x280-q95.jpg"
          srcset="
            /assets/img/son-face-170x220-q95.jpg 170w,
            /assets/img/son-face-220x280-q95.jpg 220w,
            /assets/img/son-face-340x440-q95.jpg 340w,
            /assets/img/son-face-440x560-q95.jpg 440w
          "
          sizes="(max-width: 480px) 170px, 220px"
          width="220"
          height="280"
          alt="손승하 프로필 사진"
        >
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

<!-- =====================
     PROJECTS
===================== -->
<div class="section-title">PROJECTS</div>
<div class="section-hr"></div>

<section class="projects-wrap">
  <div class="projects-grid">

    <!-- 1. 시각장애인 보행 보조 장치 -->
    <article class="project-card">
      <div class="project-head">
        <span class="project-badge">Capstone</span>
        <a class="project-btn" href="https://github.com/SeungHa-Son/Visual-impairment-mobility-aid" target="_blank" rel="noopener">GitHub</a>
      </div>

      <div class="project-title">시각장애인 보행 보조 장치</div>
      <p class="project-desc">
        실시간 객체 인식 기반으로 주변 상황을 음성으로 안내해 보행 안전을 돕는 시스템
      </p>
      <ul class="project-list">
        <li>카메라 입력 기반 객체 인식(보행자/장애물/환경 요소 등)</li>
        <li>TTS 음성 안내 및 중복 안내를 줄이기 위한 출력 로직 구성</li>
        <li>임베디드 환경에서 실시간 처리 흐름 설계</li>
      </ul>
      <div class="project-tags">
        <span class="project-chip">Python</span>
        <span class="project-chip">YOLO</span>
        <span class="project-chip">OpenCV</span>
        <span class="project-chip">Raspberry Pi</span>
      </div>
    </article>

    <!-- 2. AI 음성 변환 프로젝트 -->
    <article class="project-card">
      <div class="project-head">
        <span class="project-badge">AI</span>
        <a class="project-btn" href="https://github.com/hoo1suu/AI_cover" target="_blank" rel="noopener">GitHub</a>
      </div>

      <div class="project-title">AI 음성 변환 프로젝트</div>
      <p class="project-desc">
        보컬 분리 → 음성 변환 → 합성까지 이어지는 AI 커버 생성 파이프라인(프로토타입)
      </p>
      <ul class="project-list">
        <li>음원에서 보컬/반주 분리 후 음성 특징 분석</li>
        <li>음성 변환 모델 기반 변환/합성 흐름 구성</li>
        <li>Gradio 기반 간단 웹 UI로 시연</li>
      </ul>
      <div class="project-tags">
        <span class="project-chip">Python</span>
        <span class="project-chip">Gradio</span>
        <span class="project-chip">SVC/VITS</span>
      </div>
    </article>

    <!-- 3. 데이터베이스 수강신청 GUI -->
    <article class="project-card">
      <div class="project-head">
        <span class="project-badge">DB / GUI</span>
        <a class="project-btn" href="https://github.com/SeungHa-Son/Database-GUI-Course-Registration" target="_blank" rel="noopener">GitHub</a>
      </div>

      <div class="project-title">데이터베이스 수강신청 GUI</div>
      <p class="project-desc">
        DB 설계 기반으로 수강신청/조회/관리 기능을 GUI로 구현한 데스크톱 프로그램
      </p>
      <ul class="project-list">
        <li>테이블 설계 및 CRUD 기반 기능 구현</li>
        <li>GUI 화면 흐름(조회/신청/취소/관리) 구성</li>
        <li>입력 검증 및 데이터 무결성 고려</li>
      </ul>
      <div class="project-tags">
        <span class="project-chip">Python</span>
        <span class="project-chip">SQL</span>
        <span class="project-chip">DB Design</span>
        <span class="project-chip">GUI</span>
      </div>
    </article>

    <!-- 4. 초·중학생 대상으로 한 SW 교육기부 활동 -->
    <article class="project-card">
      <div class="project-head">
        <span class="project-badge">Volunteering</span>
        <a class="project-btn" href="https://github.com/SeungHa-Son/Software-Education-Volunteering" target="_blank" rel="noopener">GitHub</a>
      </div>

      <div class="project-title">초·중학생 대상 SW 교육기부 활동</div>
      <p class="project-desc">
        초·중학생 눈높이에 맞춘 Python 기초 교육 자료 제작 및 수업 진행 경험
      </p>
      <ul class="project-list">
        <li>주차별 교육 자료 제작(개념 → 실습 → 미니 과제)</li>
        <li>비전공자에게 이해되도록 설명 방식/예시 구성</li>
        <li>교육 운영을 통한 커뮤니케이션 역량 강화</li>
      </ul>
      <div class="project-tags">
        <span class="project-chip">Python</span>
      </div>
    </article>

  </div>
</section>
