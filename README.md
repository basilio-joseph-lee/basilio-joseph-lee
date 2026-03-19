<svg width="900" height="280" viewBox="0 0 900 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="50%" style="stop-color:#0d1f35"/>
      <stop offset="100%" style="stop-color:#0d1117"/>
    </linearGradient>
    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ffffff"/>
      <stop offset="55%" style="stop-color:#ffffff"/>
      <stop offset="100%" style="stop-color:#58a6ff"/>
    </linearGradient>
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#58a6ff;stop-opacity:0"/>
      <stop offset="30%" style="stop-color:#58a6ff;stop-opacity:1"/>
      <stop offset="70%" style="stop-color:#58a6ff;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#58a6ff;stop-opacity:0"/>
    </linearGradient>
    <linearGradient id="glowLeft" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#1f6feb;stop-opacity:0.25"/>
      <stop offset="100%" style="stop-color:#1f6feb;stop-opacity:0"/>
    </linearGradient>
    <linearGradient id="glowRight" x1="100%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#388bfd;stop-opacity:0.18"/>
      <stop offset="100%" style="stop-color:#388bfd;stop-opacity:0"/>
    </linearGradient>
    <linearGradient id="avatarRing" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#58a6ff"/>
      <stop offset="50%" style="stop-color:#1f6feb"/>
      <stop offset="100%" style="stop-color:#58a6ff"/>
    </linearGradient>
    <linearGradient id="dotLine" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#58a6ff;stop-opacity:0.6"/>
      <stop offset="100%" style="stop-color:#58a6ff;stop-opacity:0"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="softglow">
      <feGaussianBlur stdDeviation="8" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <clipPath id="avatarClip">
      <circle cx="130" cy="140" r="58"/>
    </clipPath>
  </defs>

  <!-- Background -->
  <rect width="900" height="280" fill="url(#bg)" rx="16"/>

  <!-- Ambient glow blobs -->
  <ellipse cx="130" cy="140" rx="160" ry="130" fill="url(#glowLeft)"/>
  <ellipse cx="780" cy="90" rx="180" ry="140" fill="url(#glowRight)"/>

  <!-- Grid dots pattern -->
  <g opacity="0.18" fill="#58a6ff">
    <circle cx="40" cy="30" r="1"/><circle cx="80" cy="30" r="1"/><circle cx="120" cy="30" r="1"/><circle cx="160" cy="30" r="1"/><circle cx="200" cy="30" r="1"/><circle cx="240" cy="30" r="1"/>
    <circle cx="40" cy="60" r="1"/><circle cx="80" cy="60" r="1"/><circle cx="120" cy="60" r="1"/><circle cx="160" cy="60" r="1"/><circle cx="200" cy="60" r="1"/><circle cx="240" cy="60" r="1"/>
    <circle cx="40" cy="90" r="1"/><circle cx="80" cy="90" r="1"/><circle cx="120" cy="90" r="1"/>
    <circle cx="660" cy="200" r="1"/><circle cx="700" cy="200" r="1"/><circle cx="740" cy="200" r="1"/><circle cx="780" cy="200" r="1"/><circle cx="820" cy="200" r="1"/><circle cx="860" cy="200" r="1"/>
    <circle cx="660" cy="230" r="1"/><circle cx="700" cy="230" r="1"/><circle cx="740" cy="230" r="1"/><circle cx="780" cy="230" r="1"/><circle cx="820" cy="230" r="1"/><circle cx="860" cy="230" r="1"/>
    <circle cx="660" cy="260" r="1"/><circle cx="700" cy="260" r="1"/><circle cx="740" cy="260" r="1"/><circle cx="780" cy="260" r="1"/><circle cx="820" cy="260" r="1"/>
  </g>

  <!-- Corner accents -->
  <path d="M20 50 L20 20 L50 20" stroke="#58a6ff" stroke-width="2" fill="none" opacity="0.5"/>
  <path d="M880 50 L880 20 L850 20" stroke="#58a6ff" stroke-width="2" fill="none" opacity="0.5"/>
  <path d="M20 230 L20 260 L50 260" stroke="#58a6ff" stroke-width="2" fill="none" opacity="0.5"/>
  <path d="M880 230 L880 260 L850 260" stroke="#58a6ff" stroke-width="2" fill="none" opacity="0.5"/>

  <!-- Avatar outer glow ring -->
  <circle cx="130" cy="140" r="66" fill="none" stroke="#58a6ff" stroke-width="1" opacity="0.15"/>
  <circle cx="130" cy="140" r="72" fill="none" stroke="#58a6ff" stroke-width="0.5" opacity="0.08"/>

  <!-- Avatar ring gradient -->
  <circle cx="130" cy="140" r="63" fill="none" stroke="url(#avatarRing)" stroke-width="2.5" opacity="0.9"/>

  <!-- Avatar background -->
  <circle cx="130" cy="140" r="58" fill="#161b22"/>

  <!-- Avatar face SVG (clipped) -->
  <g clip-path="url(#avatarClip)">
    <rect x="72" y="82" width="116" height="116" fill="#161b22"/>
    <!-- Body/shirt -->
    <ellipse cx="130" cy="210" rx="46" ry="28" fill="#21262d"/>
    <ellipse cx="130" cy="205" rx="38" ry="22" fill="#2d333b"/>
    <!-- Neck -->
    <rect x="120" y="172" width="20" height="18" rx="6" fill="#f0c080"/>
    <!-- Head -->
    <ellipse cx="130" cy="148" rx="30" ry="34" fill="#f0c080"/>
    <!-- Hair -->
    <ellipse cx="130" cy="120" rx="30" ry="16" fill="#1a0a00"/>
    <ellipse cx="103" cy="138" rx="8" ry="14" fill="#1a0a00"/>
    <ellipse cx="157" cy="138" rx="8" ry="14" fill="#1a0a00"/>
    <!-- Ears -->
    <ellipse cx="101" cy="150" rx="5" ry="7" fill="#e8b070"/>
    <ellipse cx="159" cy="150" rx="5" ry="7" fill="#e8b070"/>
    <!-- Eyes -->
    <ellipse cx="119" cy="148" rx="6" ry="7" fill="white"/>
    <ellipse cx="141" cy="148" rx="6" ry="7" fill="white"/>
    <circle cx="120" cy="149" r="3.5" fill="#1a0a00"/>
    <circle cx="142" cy="149" r="3.5" fill="#1a0a00"/>
    <circle cx="121" cy="147" r="1.2" fill="white"/>
    <circle cx="143" cy="147" r="1.2" fill="white"/>
    <!-- Eyebrows -->
    <path d="M113 140 Q119 137 125 140" stroke="#1a0a00" stroke-width="2" fill="none" stroke-linecap="round"/>
    <path d="M135 140 Q141 137 147 140" stroke="#1a0a00" stroke-width="2" fill="none" stroke-linecap="round"/>
    <!-- Smile -->
    <path d="M120 162 Q130 170 140 162" stroke="#c47a30" stroke-width="2" fill="none" stroke-linecap="round"/>
    <!-- Nose -->
    <ellipse cx="130" cy="157" rx="3" ry="2" fill="#d4995a" opacity="0.6"/>
  </g>

  <!-- Hi badge -->
  <rect x="172" y="82" width="76" height="26" rx="13" fill="#58a6ff"/>
  <text x="210" y="99" font-family="'Segoe UI',Arial,sans-serif" font-size="12" font-weight="700" fill="#0d1117" text-anchor="middle">Hi there 👋</text>

  <!-- Status dot -->
  <circle cx="176" cy="190" r="7" fill="#3fb950"/>
  <circle cx="176" cy="190" r="5" fill="#3fb950"/>
  <circle cx="176" cy="190" r="10" fill="none" stroke="#3fb950" stroke-width="1.5" opacity="0.4"/>

  <!-- Divider line left of text -->
  <line x1="210" y1="140" x2="220" y2="140" stroke="#58a6ff" stroke-width="1.5" opacity="0.5"/>

  <!-- RIGHT SIDE TEXT BLOCK -->
  <!-- Tag chip -->
  <rect x="230" y="68" width="120" height="22" rx="11" fill="#21262d" stroke="#58a6ff" stroke-width="0.8" opacity="0.9"/>
  <text x="290" y="83" font-family="'Courier New',monospace" font-size="11" fill="#58a6ff" text-anchor="middle" opacity="0.9">&lt;developer /&gt;</text>

  <!-- Name -->
  <text x="230" y="128" font-family="'Segoe UI',Arial,sans-serif" font-size="38" font-weight="700" fill="url(#nameGrad)" filter="url(#softglow)" opacity="0.15">Basilio Joseph Lee</text>
  <text x="230" y="128" font-family="'Segoe UI',Arial,sans-serif" font-size="38" font-weight="700" fill="url(#nameGrad)">Basilio Joseph Lee</text>

  <!-- Accent underline -->
  <rect x="230" y="136" width="340" height="2" rx="1" fill="url(#lineGrad)"/>

  <!-- Role subtitle -->
  <text x="230" y="162" font-family="'Courier New',monospace" font-size="13" fill="#8b949e">Web Developer  ·  Mobile App Developer</text>

  <!-- Bio line -->
  <text x="230" y="188" font-family="'Segoe UI',Arial,sans-serif" font-size="12" fill="#6e7681">Always exploring new tech &amp; integrating AI into real products.</text>

  <!-- Location + status -->
  <text x="230" y="210" font-family="'Courier New',monospace" font-size="11" fill="#58a6ff" opacity="0.7">📍 Philippines  ·  🟢 Open to opportunities</text>

  <!-- Divider -->
  <line x1="230" y1="224" x2="640" y2="224" stroke="#21262d" stroke-width="1"/>

  <!-- Social link pills -->
  <!-- Gmail -->
  <rect x="230" y="234" width="80" height="26" rx="6" fill="#21262d" stroke="#30363d" stroke-width="1"/>
  <text x="270" y="251" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#8b949e" text-anchor="middle">✉ Gmail</text>

  <!-- LinkedIn -->
  <rect x="318" y="234" width="88" height="26" rx="6" fill="#21262d" stroke="#30363d" stroke-width="1"/>
  <text x="362" y="251" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#8b949e" text-anchor="middle">in LinkedIn</text>

  <!-- Upwork -->
  <rect x="414" y="234" width="84" height="26" rx="6" fill="#21262d" stroke="#30363d" stroke-width="1"/>
  <text x="456" y="251" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#8b949e" text-anchor="middle">⬆ Upwork</text>

  <!-- GitHub -->
  <rect x="506" y="234" width="84" height="26" rx="6" fill="#21262d" stroke="#30363d" stroke-width="1"/>
  <text x="548" y="251" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#8b949e" text-anchor="middle">⌥ GitHub</text>

  <!-- Floating code snippets decoration -->
  <text x="700" y="110" font-family="'Courier New',monospace" font-size="11" fill="#58a6ff" opacity="0.12" transform="rotate(-15,700,110)">const dev = {</text>
  <text x="715" y="128" font-family="'Courier New',monospace" font-size="11" fill="#58a6ff" opacity="0.12" transform="rotate(-15,715,128)">  stack: 'full',</text>
  <text x="710" y="146" font-family="'Courier New',monospace" font-size="11" fill="#3fb950" opacity="0.12" transform="rotate(-15,710,146)">  passion: true</text>
  <text x="700" y="164" font-family="'Courier New',monospace" font-size="11" fill="#58a6ff" opacity="0.12" transform="rotate(-15,700,164)">}</text>

  <!-- Subtle particle dots scattered right side -->
  <circle cx="690" cy="60" r="1.5" fill="#58a6ff" opacity="0.3"/>
  <circle cx="730" cy="45" r="1" fill="#58a6ff" opacity="0.2"/>
  <circle cx="810" cy="75" r="2" fill="#58a6ff" opacity="0.25"/>
  <circle cx="860" cy="50" r="1" fill="#58a6ff" opacity="0.2"/>
  <circle cx="850" cy="160" r="1.5" fill="#58a6ff" opacity="0.2"/>
  <circle cx="875" cy="130" r="1" fill="#1f6feb" opacity="0.3"/>
  <circle cx="670" cy="170" r="1" fill="#388bfd" opacity="0.2"/>

  <!-- Connecting lines between particles -->
  <line x1="690" y1="60" x2="730" y2="45" stroke="#58a6ff" stroke-width="0.5" opacity="0.12"/>
  <line x1="730" y1="45" x2="810" y2="75" stroke="#58a6ff" stroke-width="0.5" opacity="0.1"/>
  <line x1="810" y1="75" x2="860" y2="50" stroke="#58a6ff" stroke-width="0.5" opacity="0.1"/>
  <line x1="850" y1="160" x2="875" y2="130" stroke="#58a6ff" stroke-width="0.5" opacity="0.12"/>
</svg>
