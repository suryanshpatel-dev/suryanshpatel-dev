
<!-- github-metrics-card.html — dark neon "maker metrics" card -->
<div class="metrics-card">
  <header class="mc-header">
    <div class="mc-avatar">S</div>
    <div>
      <h1 class="mc-name">Suryansh</h1>
      <p class="mc-sub">B.Tech CSE, VBSPU &nbsp;·&nbsp; Lab Assistant &nbsp;·&nbsp; Varanasi, UP</p>
    </div>
  </header>

  <div class="mc-rule"></div>

  <section class="mc-stats">
    <div class="mc-stat">
      <div class="mc-ring" style="--pct:70"><span>7</span></div>
      <p>Active Projects</p>
    </div>
    <div class="mc-stat">
      <div class="mc-ring" style="--pct:50"><span>2</span></div>
      <p>Domains: HW + SW</p>
    </div>
    <div class="mc-stat">
      <div class="mc-ring" style="--pct:85"><span>Maker</span></div>
      <p>Builds from salvage</p>
    </div>
    <div class="mc-stat">
      <div class="mc-ring" style="--pct:90"><span>10+</span></div>
      <p>Tools &amp; Stacks</p>
    </div>
  </section>

  <div class="mc-rule"></div>

  <section class="mc-projects">
    <h2>Featured Projects</h2>
    <div class="mc-project-grid">
      <div class="mc-card">
        <h3>NestCloud</h3>
        <p>Home server built from salvaged parts</p>
      </div>
      <div class="mc-card">
        <h3>NetSentinel</h3>
        <p>WiFi intrusion detection on ESP32</p>
      </div>
      <div class="mc-card">
        <h3>Saathi AI</h3>
        <p>Voice companion assistant</p>
      </div>
      <div class="mc-card">
        <h3>Royal Kitchen POS</h3>
        <p>Electron/React billing desktop app</p>
      </div>
      <div class="mc-card">
        <h3>RC Trainer Aircraft v2</h3>
        <p>Custom-built radio-controlled aircraft</p>
      </div>
      <div class="mc-card">
        <h3>WhatsApp Automation Bots</h3>
        <p>GPT-integrated chatbot automation</p>
      </div>
    </div>
  </section>

  <section class="mc-stack">
    <h2>Tech Stack</h2>
    <div class="mc-chips">
      <span class="chip c1">Python</span>
      <span class="chip c2">C</span>
      <span class="chip c3">Node.js</span>
      <span class="chip c4">React</span>
      <span class="chip c1">SQL</span>
      <span class="chip c2">Arduino</span>
      <span class="chip c3">ESP32</span>
      <span class="chip c4">ESP8266</span>
      <span class="chip c1">Raspberry Pi</span>
    </div>
  </section>
</div>

<style>
  * { box-sizing: border-box; }

  .metrics-card {
    --bg1: #0f0c29;
    --bg2: #1b1836;
    --bg3: #24243e;
    --accent1: #00ff9c;
    --accent2: #00d4ff;
    --line: #2c2856;
    --sub: #9aa4b2;
    --body: #d7dbe0;

    max-width: 900px;
    margin: 0 auto;
    padding: 32px;
    border-radius: 16px;
    background: linear-gradient(135deg, var(--bg1) 0%, var(--bg2) 55%, var(--bg3) 100%);
    border: 1px solid rgba(0,255,156,0.25);
    font-family: 'Courier New', Consolas, monospace;
    color: var(--body);
  }

  .mc-header { display: flex; align-items: center; gap: 18px; }

  .mc-avatar {
    width: 60px; height: 60px; border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    font-size: 22px; font-weight: bold; color: #fff;
    background: var(--bg1);
    border: 2.5px solid transparent;
    background-image: linear-gradient(var(--bg1), var(--bg1)), linear-gradient(135deg, var(--accent1), var(--accent2));
    background-origin: border-box;
    background-clip: padding-box, border-box;
    flex-shrink: 0;
  }

  .mc-name { margin: 0 0 4px 0; font-size: 22px; color: #fff; }
  .mc-sub { margin: 0; font-size: 13px; color: var(--sub); }

  .mc-rule { height: 1px; background: var(--line); margin: 24px 0; }

  .mc-stats {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 16px;
    text-align: center;
  }

  .mc-stat p { margin: 12px 0 0 0; font-size: 12.5px; color: var(--sub); }

  .mc-ring {
    width: 80px; height: 80px;
    margin: 0 auto;
    border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    background:
      radial-gradient(closest-side, var(--bg2) 79%, transparent 80% 100%),
      conic-gradient(var(--accent1) calc(var(--pct) * 1%), var(--line) 0);
    font-size: 15px; font-weight: bold; color: #fff;
  }

  .mc-projects h2, .mc-stack h2 {
    font-size: 15px; color: var(--accent1); margin: 0 0 14px 0;
  }

  .mc-project-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
  }

  .mc-card {
    background: #171433;
    border: 1px solid var(--line);
    border-radius: 8px;
    padding: 10px 14px;
    transition: border-color 0.2s ease, transform 0.2s ease;
  }
  .mc-card:hover {
    border-color: var(--accent1);
    transform: translateY(-2px);
  }
  .mc-card h3 { margin: 0 0 4px 0; font-size: 13px; color: var(--body); }
  .mc-card p { margin: 0; font-size: 11px; color: var(--sub); }

  .mc-stack { margin-top: 24px; }

  .mc-chips { display: flex; flex-wrap: wrap; gap: 8px; }

  .chip {
    padding: 5px 14px;
    border-radius: 999px;
    font-size: 12px;
    font-weight: bold;
    color: var(--bg1);
  }
  .chip.c1 { background: var(--accent1); }
  .chip.c2 { background: var(--accent2); }
  .chip.c3 { background: #ff6ec7; }
  .chip.c4 { background: #ffd166; }

  @media (max-width: 640px) {
    .mc-stats { grid-template-columns: repeat(2, 1fr); }
    .mc-project-grid { grid-template-columns: 1fr; }
  }
</style>
