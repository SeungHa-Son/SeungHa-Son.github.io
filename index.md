<style>
  /* =====================
     SKILLS (Clean Chip UI)
  ===================== */

  :root{
    /* 배경 톤(따뜻한 노랑 계열 유지) */
    --skills-outer: #f6e27d;
    --skills-inner: #fff3c4;

    /* 텍스트/테두리/그림자 */
    --text: #1f2937;
    --muted: #6b7280;
    --border: rgba(17, 24, 39, .10);
    --shadow: 0 12px 26px rgba(0,0,0,.12);

    /* 칩 컬러: '한 팔레트'로 통일 (Blue/Indigo/Slate) */
    --chip-bg: #eef2ff;        /* 아주 연한 인디고 */
    --chip-text: #1f2937;
    --chip-border: rgba(79,70,229,.18);

    /* 강조 칩(핵심 기술만) */
    --chip-accent-bg: #4f46e5; /* 인디고 */
    --chip-accent-text: #ffffff;

    /* 아이콘 배경 */
    --icon-bg: #fff1b8;
  }

  .skill-box{
    max-width: 900px;
    margin: 20px auto;
    padding: 20px;
    border-radius: 18px;
    background: var(--skills-outer);
    box-shadow: var(--shadow);
  }

  .skill-card{
    border-radius: 16px;
    background: var(--skills-inner);
    padding: 18px;
    border: 1px solid var(--border);
  }

  /* ✅த 핵심: grid로 고정 배치해서 Embedded가 아래로 안 내려가게 */
  .skill-row{
    display: grid;
    grid-template-columns: 170px 1fr; /* 왼쪽 라벨 고정, 오른쪽 태그 유연 */
    gap: 14px;
    padding: 14px 0;
    align-items: start;
  }

  @media (max-width: 720px){
    .skill-row{
      grid-template-columns: 1fr; /* 모바일에서는 자연스럽게 세로 */
    }
  }

  .skill-label{
    display:flex;
    gap: 10px;
    align-items:center;
    font-weight: 800;
    font-size: 18px;
    color: var(--text);
    white-space: nowrap;
  }

  .skill-icon{
    width: 34px;
    height: 34px;
    border-radius: 10px;
    display:inline-flex;
    align-items:center;
    justify-content:center;
    background: var(--icon-bg);
    border: 1px solid var(--border);
  }

  .skill-tags{
    display:flex;
    flex-wrap: wrap;
    gap: 10px;
    align-items: center;
    min-width: 0; /* 중요: 긴 텍스트에서도 레이아웃 안정 */
  }

  .chip{
    display:inline-block;
    padding: 8px 14px;
    border-radius: 999px;
    font-weight: 700;
    font-size: 14px;
    line-height: 1;
    color: var(--chip-text);
    background: var(--chip-bg);
    border: 1px solid var(--chip-border);
    white-space: nowrap;
  }

  /* 핵심 기술만 강조 */
  .chip.accent{
    background: var(--chip-accent-bg);
    color: var(--chip-accent-text);
    border-color: rgba(255,255,255,.25);
  }
</style>

<h2>🔗 SKILLS</h2>

<div class="skill-box">
  <div class="skill-card">

    <div class="skill-row">
      <div class="skill-label">
        <span class="skill-icon">🤖</span> AI
      </div>
      <div class="skill-tags">
        <span class="chip accent">YOLO</span>
        <span class="chip">TensorFlow</span>
        <span class="chip">OpenCV</span>
        <span class="chip">Hailo-8</span>
      </div>
    </div>

    <div class="skill-row">
      <div class="skill-label">
        <span class="skill-icon">💻</span> Language
      </div>
      <div class="skill-tags">
        <span class="chip accent">Python</span>
        <span class="chip">C</span>
        <span class="chip">C++</span>
        <span class="chip">Java</span>
        <span class="chip">SQL</span>
      </div>
    </div>

    <div class="skill-row">
      <div class="skill-label">
        <span class="skill-icon">⚙️</span> Embedded
      </div>
      <div class="skill-tags">
        <span class="chip">Arduino</span>
        <span class="chip">Raspberry Pi</span>
        <span class="chip accent">Linux</span>
        <span class="chip">Embedded System</span>
        <span class="chip">Firmware</span>
      </div>
    </div>

    <div class="skill-row">
      <div class="skill-label">
        <span class="skill-icon">🌐</span> System / IoT
      </div>
      <div class="skill-tags">
        <span class="chip">IoT</span>
        <span class="chip">Network Programming</span>
        <span class="chip">Database</span>
        <span class="chip">Cloud Computing</span>
      </div>
    </div>

  </div>
</div>
