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
   SECTION TITLE (ABOUT / SKILLS / PROJECTS 공통)
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

/* 사진 + 정보 같은 행 */
.about-panel{
  display:grid;
  grid-template-columns:260px 1fr;
  gap:60px;
  align-items:start;
}

@media (max-width:920px){
  .about-panel{
    grid-template-columns:1fr;
    gap:24px;
    justify-items:center;
  }
}

/* 프로필 사진 */
.about-photo{
  display:flex;
  justify-content:flex-start;
}

@media (max-width:920px){
  .about-photo{ justify-content:center; }
}

.about-photo img{
  width:220px;
  height:280px;
  object-fit:cover;
  border-radius:16px;
  border:1px solid #e5e7eb;
  box-shadow:0 10px 24px rgba(0,0,0,.14);
}

/* 정보 그리드 */
.about-grid{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:26px 70px;
  align-content:start;
}

@media (max-width:820px){
  .about-grid{
    grid-template-columns:1fr;
    gap:18px;
  }
}

.about-item{
  display:flex;
  gap:16px;
  align-items:flex-start;
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
  flex:0 0 auto;
}

.about-label{
  font-weight:900;
  margin-bottom:6px;
}

.about-value{
  color:#4b5563;
  font-size:15px;
  line-height:1.5;
  word-break:break-word;
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
  max-width:1000px;
  margin:20px auto 80px;
  padding:0 20px;
}

.projects-grid{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:26px;
}

@media (max-width:920px){
  .projects-grid{ grid-template-columns:1fr; }
}

.project-card{
  background:#ffffff;
  border:1px solid rgba(17,24,39,.12);
  border-radius:18px;
  padding:24px;
  box-shadow:0 12px 26px rgba(0,0,0,.12);
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

.project-date{
  margin-top:10px;
  color:#6b7280;
  font-size:13px;
  font-weight:700;
}

.project-title{
  margin:10px 0 12px;
  font-size:18px;
  font-weight:900;
  line-height:1.35;
}

.project-hr{
  border:0;
  height:1px;
  background:#e5e7eb;
  margin:0 0 14px;
}

.project-list{
  margin:0;
  padding-left:18px;
  color:#111827;
  font-size:14px;
  line-height:1.7;
}

.project-link{
  margin-top:12px;
  display:inline-block;
  color:#2563eb;
  text-decoration:none;
  font-weight:800;
}

.project-link:hover{ text-decoration:underline; }

.project-tags{
  margin-top:14px;
  display:flex;
  flex-wrap:wrap;
  gap:10px;
}

.project-chip{
  padding:8px 14px;
  border-radius:999px;
  font-weight:800;
  font-size:13px;
  background:#fff7ed;
  color:#92400e;
  border:1px solid #f59e0b;
  white-space:nowrap;
}

.project-footer{
  margin-top:14px;
  display:flex;
  flex-wrap:wrap;
  gap:10px;
}

.project-btn{
  display:inline-flex;
  align-items:center;
  justify-content:center;
  padding:10px 14px;
  border-radius:12px;
  border:1px solid #d1d5db;
  background:#ffffff;
  font-weight:900;
  font-size:14px;
  text-decoration:none;
  color:#111111;
}

.project-btn:hover{
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

  <div class="about-panel">
    <div class="about-photo">
      <img
        src="/assets/img/son-face-220.jpg?v=2"
        srcset="/assets/img/son-face-220.jpg?v=2 1x, /assets/img/son-face-440.jpg?v=2 2x"
        alt="손승하 프로필 사진">
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

<!-- =====================
     PROJECTS
===================== -->
<div class="section-title">PROJECTS</div>
<div class="section-hr"></div>

<section class="projects-wrap">
  <div class="projects-grid">

    <!-- 1) 시각장애인 보행 보조 장치 -->
    <article class="project-card">
      <span class="project-badge">Capstone Design</span>
      <div class="project-date">시각장애인 보행 보조 장치</div>
      <div class="project-title">실시간 객체 인식 기반 음성 안내 보행 보조 시스템</div>
      <hr class="project-hr" />
      <ul class="project-list">
        <li>YOLO 기반으로 횡단보도/점자블록/차량/보행자/신호등을 실시간 인식</li>
        <li>TTS로 주변 상황을 안내하고, 쿨타임 로직으로 중복 음성 출력 방지</li>
        <li>Raspberry Pi 5 + USB 카메라/스피커 기반의 저비용·웨어러블 형태 구현</li>
      </ul>
      <a class="project-link" href="https://github.com/SeungHa-Son/Visual-impairment-mobility-aid" target="_blank" rel="noopener">GitHub Repo</a>
      <div class="project-tags">
        <span class="project-chip">Python</span>
        <span class="project-chip">YOLOv5/YOLOv8</span>
        <span class="project-chip">OpenCV</span>
        <span class="project-chip">TTS</span>
        <span class="project-chip">Raspberry Pi 5</span>
      </div>
      <div class="project-footer">
        <a class="project-btn" href="https://github.com/SeungHa-Son/Visual-impairment-mobility-aid#readme" target="_blank" rel="noopener">README</a>
        <a class="project-btn" href="https://github.com/SeungHa-Son/Visual-impairment-mobility-aid/blob/main/%EC%8B%9C%EA%B0%81%EC%9E%A5%EC%95%A0%EC%9D%B8%20%EB%B3%B4%ED%96%89%20%EB%B3%B4%EC%A1%B0%20%EC%9E%A5%EC%B9%98%20%EB%B0%9C%ED%91%9C%EC%9E%90%EB%A3%8C.pdf" target="_blank" rel="noopener">발표자료</a>
      </div>
    </article>

    <!-- 2) AI 음성 변환 프로젝트 -->
    <article class="project-card">
      <span class="project-badge">AI / Audio</span>
      <div class="project-date">AI 음성 변환 프로젝트 (2024년 2학기 · 테크페어)</div>
      <div class="project-title">AI Voice Cover: 내 목소리를 아티스트 목소리로 변환해 커버곡 생성</div>
      <hr class="project-hr" />
      <ul class="project-list">
        <li>Gradio 웹 UI에서 “사용자 음성 파일 + 변환할 노래 파일” 입력으로 커버곡 생성</li>
        <li>UVR로 MR/보컬 분리 후, SoftVC+VITS 기반으로 음성 변환·합성 파이프라인 구성</li>
        <li>Colab 환경에서 구현(실험 단계) 및 시연 중심의 프로토타입 운영</li>
      </ul>
      <a class="project-link" href="https://github.com/hoo1suu/AI_cover" target="_blank" rel="noopener">GitHub Repo</a>
      <div class="project-tags">
        <span class="project-chip">Python</span>
        <span class="project-chip">Google Colab</span>
        <span class="project-chip">SoftVC + VITS</span>
        <span class="project-chip">Gradio</span>
        <span class="project-chip">UVR</span>
        <span class="project-chip">ffmpeg / librosa</span>
      </div>
      <div class="project-footer">
        <a class="project-btn" href="https://github.com/hoo1suu/AI_cover#readme" target="_blank" rel="noopener">README</a>
        <a class="project-btn" href="https://colab.research.google.com/github/hoo1suu/AI_cover/blob/main/aicover.ipynb" target="_blank" rel="noopener">Colab</a>
      </div>
    </article>

    <!-- 3) 데이터베이스 수강신청 GUI -->
    <article class="project-card">
      <span class="project-badge">DB / Desktop</span>
      <div class="project-date">데이터베이스 수강신청 GUI</div>
      <div class="project-title">Python + PyQt5 기반 역할별 수강신청 관리 시스템</div>
      <hr class="project-hr" />
      <ul class="project-list">
        <li>학생/교수/교무처 직원 역할을 분리해 기능 접근 권한을 명확하게 설계</li>
        <li>수강신청·취소·시간표 조회 / 과목별 수강학생 조회 / 교과목 CRUD 등 기능 구현</li>
        <li>ERD 설계 후(MySQL), GUI 화면 전환 및 테이블(QTableWidget) 출력으로 사용성 강화</li>
      </ul>
      <a class="project-link" href="https://github.com/SeungHa-Son/Database-GUI-Course-Registration" target="_blank" rel="noopener">GitHub Repo</a>
      <div class="project-tags">
        <span class="project-chip">Python</span>
        <span class="project-chip">PyQt5</span>
        <span class="project-chip">MySQL</span>
        <span class="project-chip">PyMySQL</span>
      </div>
      <div class="project-footer">
        <a class="project-btn" href="https://github.com/SeungHa-Son/Database-GUI-Course-Registration#readme" target="_blank" rel="noopener">README</a>
        <a class="project-btn" href="https://github.com/SeungHa-Son/Database-GUI-Course-Registration/blob/main/%EC%88%98%EA%B0%95%EC%8B%A0%EC%B2%AD%20GUI%20%EB%B0%9C%ED%91%9C%EC%9E%90%EB%A3%8C.pdf" target="_blank" rel="noopener">발표자료</a>
      </div>
    </article>

    <!-- 4) SW 교육기부 활동 -->
    <article class="project-card">
      <span class="project-badge">Volunteering</span>
      <div class="project-date">초·중학생 대상으로 한 SW 교육기부 활동 (2024 상반기)</div>
      <div class="project-title">파이썬 기초를 실습 중심으로 설계한 주차별 교육 자료 제작</div>
      <hr class="project-hr" />
      <ul class="project-list">
        <li>Code Club Korea “찾아가는 SW 교육기부단” 활동으로 초·중학생 대상 교육 진행</li>
        <li>주차별 PDF 자료(1–2주차~7–8주차)로 개념→실습→미니프로그램 흐름 구성</li>
        <li>비전공자 눈높이 설명/커리큘럼 구성 경험을 통해 커뮤니케이션 역량 강화</li>
      </ul>
      <a class="project-link" href="https://github.com/SeungHa-Son/Software-Education-Volunteering" target="_blank" rel="noopener">GitHub Repo</a>
      <div class="project-tags">
        <span class="project-chip">Python</span>
        <span class="project-chip">Curriculum</span>
        <span class="project-chip">Teaching</span>
        <span class="project-chip">PDF Materials</span>
      </div>
      <div class="project-footer">
        <a class="project-btn" href="https://github.com/SeungHa-Son/Software-Education-Volunteering#readme" target="_blank" rel="noopener">README</a>
        <a class="project-btn" href="https://github.com/SeungHa-Son/Software-Education-Volunteering/blob/main/SW%EA%B5%90%EC%9C%A1%EA%B8%B0%EB%B6%80%EB%8B%A8-%EC%88%98%EB%A3%8C%EC%A6%9D.pdf" target="_blank" rel="noopener">수료증</a>
      </div>
    </article>

  </div>
</section>
