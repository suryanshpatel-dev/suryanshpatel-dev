<svg width="900" height="480" viewBox="0 0 900 480" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg2" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0f0c29"/>
      <stop offset="55%" stop-color="#1b1836"/>
      <stop offset="100%" stop-color="#24243e"/>
    </linearGradient>
    <linearGradient id="ring1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#00ff9c"/>
      <stop offset="100%" stop-color="#00d4ff"/>
    </linearGradient>
    <style>
      .mono { font-family: 'Courier New', Consolas, monospace; }
      .h1 { fill: #ffffff; font-weight: bold; }
      .h2 { fill: #00ff9c; font-weight: bold; }
      .sub { fill: #9aa4b2; }
      .body { fill: #d7dbe0; }
      .card { fill: #171433; stroke: #2c2856; stroke-width: 1; }
      .chip { fill: #ffffff10; stroke: #00ff9c55; stroke-width: 1; }
    </style>
  </defs>

  <rect width="900" height="480" rx="16" fill="url(#bg2)"/>
  <rect x="1" y="1" width="898" height="478" rx="16" fill="none" stroke="#00ff9c" stroke-opacity="0.25"/>

  <!-- header -->
  <g class="mono">
    <circle cx="60" cy="55" r="30" fill="#0f0c29" stroke="url(#ring1)" stroke-width="2.5"/>
    <text x="60" y="63" text-anchor="middle" font-size="22" class="h1">S</text>

    <text x="105" y="48" font-size="22" class="h1">Suryansh</text>
    <text x="105" y="70" font-size="13" class="sub">B.Tech CSE, VBSPU  ·  Lab Assistant  ·  Varanasi, UP</text>
  </g>

  <line x1="30" y1="95" x2="870" y2="95" stroke="#2c2856" stroke-width="1"/>

  <!-- stat rings -->
  <g class="mono" text-anchor="middle">
    <!-- ring template repeated -->
    <g transform="translate(110,175)">
      <circle r="40" fill="none" stroke="#2c2856" stroke-width="8"/>
      <circle r="40" fill="none" stroke="url(#ring1)" stroke-width="8" stroke-dasharray="251" stroke-dashoffset="20" stroke-linecap="round" transform="rotate(-90)"/>
      <text y="6" font-size="20" class="h1">7</text>
      <text y="65" font-size="13" class="sub">Active Projects</text>
    </g>
    <g transform="translate(280,175)">
      <circle r="40" fill="none" stroke="#2c2856" stroke-width="8"/>
      <circle r="40" fill="none" stroke="url(#ring1)" stroke-width="8" stroke-dasharray="251" stroke-dashoffset="10" stroke-linecap="round" transform="rotate(-90)"/>
      <text y="6" font-size="20" class="h1">2</text>
      <text y="65" font-size="13" class="sub">Domains: HW+SW</text>
    </g>
    <g transform="translate(450,175)">
      <circle r="40" fill="none" stroke="#2c2856" stroke-width="8"/>
      <circle r="40" fill="none" stroke="url(#ring1)" stroke-width="8" stroke-dasharray="251" stroke-dashoffset="40" stroke-linecap="round" transform="rotate(-90)"/>
      <text y="0" font-size="15" class="h1">Maker</text>
      <text y="18" font-size="15" class="h1">Mindset</text>
      <text y="65" font-size="13" class="sub">Builds from salvage</text>
    </g>
    <g transform="translate(620,175)">
      <circle r="40" fill="none" stroke="#2c2856" stroke-width="8"/>
      <circle r="40" fill="none" stroke="url(#ring1)" stroke-width="8" stroke-dasharray="251" stroke-dashoffset="60" stroke-linecap="round" transform="rotate(-90)"/>
      <text y="6" font-size="20" class="h1">10+</text>
      <text y="65" font-size="13" class="sub">Tools &amp; Stacks</text>
    </g>
  </g>

  <line x1="30" y1="235" x2="870" y2="235" stroke="#2c2856" stroke-width="1"/>

  <!-- featured projects -->
  <g class="mono">
    <text x="40" y="262" font-size="15" class="h2">Featured Projects</text>

    <rect x="40" y="278" width="390" height="46" rx="8" class="card"/>
    <text x="54" y="298" font-size="13" class="body">NestCloud</text>
    <text x="54" y="315" font-size="11" class="sub">Home server built from salvaged parts</text>

    <rect x="440" y="278" width="420" height="46" rx="8" class="card"/>
    <text x="454" y="298" font-size="13" class="body">NetSentinel</text>
    <text x="454" y="315" font-size="11" class="sub">WiFi intrusion detection on ESP32</text>

    <rect x="40" y="332" width="390" height="46" rx="8" class="card"/>
    <text x="54" y="352" font-size="13" class="body">Saathi AI</text>
    <text x="54" y="369" font-size="11" class="sub">Voice companion assistant</text>

    <rect x="440" y="332" width="420" height="46" rx="8" class="card"/>
    <text x="454" y="352" font-size="13" class="body">Royal Kitchen POS</text>
    <text x="454" y="369" font-size="11" class="sub">Electron/React billing desktop app</text>

    <rect x="40" y="386" width="390" height="46" rx="8" class="card"/>
    <text x="54" y="406" font-size="13" class="body">RC Trainer Aircraft v2</text>
    <text x="54" y="423" font-size="11" class="sub">Custom-built radio-controlled aircraft</text>

    <rect x="440" y="386" width="420" height="46" rx="8" class="card"/>
    <text x="454" y="406" font-size="13" class="body">WhatsApp Automation Bots</text>
    <text x="454" y="423" font-size="11" class="sub">GPT-integrated chatbot automation</text>
  </g>

  <!-- tech stack chips -->
  <g class="mono" font-size="12">
    <text x="40" y="455" font-size="15" class="h2">Tech Stack</text>
  </g>
  <g class="mono" font-size="12" fill="#0f0c29">
    <rect x="145" y="440" width="60" height="24" rx="12" fill="#00ff9c"/><text x="157" y="456">Python</text>
    <rect x="213" y="440" width="46" height="24" rx="12" fill="#00d4ff"/><text x="222" y="456">C</text>
    <rect x="267" y="440" width="70" height="24" rx="12" fill="#ff6ec7"/><text x="277" y="456">Node.js</text>
    <rect x="345" y="440" width="60" height="24" rx="12" fill="#ffd166"/><text x="357" y="456">React</text>
    <rect x="413" y="440" width="60" height="24" rx="12" fill="#00ff9c"/><text x="424" y="456">SQL</text>
    <rect x="481" y="440" width="72" height="24" rx="12" fill="#00d4ff"/><text x="491" y="456">Arduino</text>
    <rect x="561" y="440" width="66" height="24" rx="12" fill="#ff6ec7"/><text x="571" y="456">ESP32</text>
    <rect x="635" y="440" width="80" height="24" rx="12" fill="#ffd166"/><text x="645" y="456">ESP8266</text>
    <rect x="723" y="440" width="106" height="24" rx="12" fill="#00ff9c"/><text x="733" y="456">Raspberry Pi</text>
  </g>
</svg>
