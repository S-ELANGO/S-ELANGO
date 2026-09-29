<svg
  xmlns="http://www.w3.org/2000/svg"
  width="1180"
  height="610"
  viewBox="0 0 1180 610"
  role="img"
  aria-label="Elango AI Engineer GitHub profile"
>

  <!-- =========================
       DEFINITIONS
       ========================= -->

  <defs>

    <!-- Background gradient -->
    <linearGradient id="background" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#020617"/>
      <stop offset="50%" stop-color="#07111F"/>
      <stop offset="100%" stop-color="#0B1220"/>
    </linearGradient>

    <!-- Cyan → violet → green -->
    <linearGradient id="neon" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#22D3EE"/>
      <stop offset="50%" stop-color="#7C3AED"/>
      <stop offset="100%" stop-color="#10B981"/>
    </linearGradient>

    <!-- Glow -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="5" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Background grid -->
    <pattern
      id="grid"
      width="24"
      height="24"
      patternUnits="userSpaceOnUse"
    >
      <path
        d="M24 0H0V24"
        fill="none"
        stroke="#22D3EE"
        stroke-opacity=".08"
      />
    </pattern>

  </defs>


  <!-- =========================
       BACKGROUND
       ========================= -->

  <rect
    width="1180"
    height="610"
    rx="24"
    fill="url(#background)"
  />

  <rect
    x="10"
    y="10"
    width="1160"
    height="590"
    rx="22"
    fill="url(#grid)"
  />


  <!-- =========================
       TERMINAL HEADER
       ========================= -->

  <rect
    x="25"
    y="25"
    width="1130"
    height="45"
    rx="12"
    fill="#020617"
    stroke="#164E63"
  />

  <!-- Terminal buttons -->

  <circle cx="50" cy="47" r="7" fill="#EF4444"/>
  <circle cx="72" cy="47" r="7" fill="#FBBF24"/>
  <circle cx="94" cy="47" r="7" fill="#22C55E"/>

  <text
    x="125"
    y="52"
    fill="#22D3EE"
    font-family="monospace"
    font-size="15"
    font-weight="bold"
  >
    elango@developer:~ / README.md
  </text>


  <!-- Navigation -->

  <text
    x="850"
    y="52"
    fill="#22D3EE"
    font-family="monospace"
    font-size="13"
  >
    &lt;&gt; Code
  </text>

  <text
    x="930"
    y="52"
    fill="#22D3EE"
    font-family="monospace"
    font-size="13"
  >
    ⊞ Projects
  </text>

  <text
    x="1030"
    y="52"
    fill="#22D3EE"
    font-family="monospace"
    font-size="13"
  >
    ◯ Contact
  </text>


  <!-- =========================
       LEFT PANEL
       ========================= -->

  <rect
    x="40"
    y="90"
    width="500"
    height="470"
    rx="18"
    fill="#020617"
    fill-opacity=".85"
    stroke="url(#neon)"
    stroke-width="2"
    filter="url(#glow)"
  />

  <text
    x="62"
    y="112"
    fill="#22D3EE"
    font-family="monospace"
    font-size="13"
    font-weight="bold"
    letter-spacing="2"
  >
    VISUAL.MAP
  </text>


  <!-- =========================
       CODE-GENERATED AI VISUAL
       ========================= -->

  <!-- Central circle -->

  <circle
    cx="290"
    cy="300"
    r="125"
    fill="none"
    stroke="#22D3EE"
    stroke-opacity=".25"
    stroke-width="2"
  />

  <circle
    cx="290"
    cy="300"
    r="90"
    fill="none"
    stroke="#7C3AED"
    stroke-opacity=".35"
    stroke-width="2"
  />

  <!-- Orbit -->

  <ellipse
    cx="290"
    cy="300"
    rx="180"
    ry="70"
    fill="none"
    stroke="#22D3EE"
    stroke-opacity=".3"
  >
    <animateTransform
      attributeName="transform"
      type="rotate"
      from="0 290 300"
      to="360 290 300"
      dur="12s"
      repeatCount="indefinite"
    />
  </ellipse>


  <!-- AI nodes -->

  <circle cx="290" cy="300" r="12" fill="#22D3EE" filter="url(#glow)">
    <animate
      attributeName="r"
      values="10;14;10"
      dur="2s"
      repeatCount="indefinite"
    />
  </circle>

  <circle cx="170" cy="220" r="6" fill="#7C3AED"/>
  <circle cx="410" cy="220" r="6" fill="#10B981"/>
  <circle cx="180" cy="400" r="6" fill="#22D3EE"/>
  <circle cx="400" cy="400" r="6" fill="#7C3AED"/>


  <!-- Connections -->

  <line
    x1="170"
    y1="220"
    x2="290"
    y2="300"
    stroke="#22D3EE"
    stroke-opacity=".5"
  />

  <line
    x1="410"
    y1="220"
    x2="290"
    y2="300"
    stroke="#22D3EE"
    stroke-opacity=".5"
  />

  <line
    x1="180"
    y1="400"
    x2="290"
    y2="300"
    stroke="#22D3EE"
    stroke-opacity=".5"
  />

  <line
    x1="400"
    y1="400"
    x2="290"
    y2="300"
    stroke="#22D3EE"
    stroke-opacity=".5"
  />


  <!-- Floating code -->

  <text
    x="100"
    y="175"
    fill="#67E8F9"
    font-family="monospace"
    font-size="11"
  >
    &lt;AI_AGENT /&gt;
  </text>

  <text
    x="340"
    y="175"
    fill="#A78BFA"
    font-family="monospace"
    font-size="11"
  >
    RAG.pipeline()
  </text>

  <text
    x="105"
    y="470"
    fill="#10B981"
    font-family="monospace"
    font-size="11"
  >
    Python → FastAPI
  </text>

  <text
    x="335"
    y="470"
    fill="#22D3EE"
    font-family="monospace"
    font-size="11"
  >
    LangGraph → LLM
  </text>


  <!-- Scan line -->

  <rect
    x="55"
    y="140"
    width="470"
    height="1"
    fill="#22D3EE"
    opacity=".6"
  >
    <animate
      attributeName="y"
      values="140;530;140"
      dur="7s"
      repeatCount="indefinite"
    />
  </rect>


  <text
    x="70"
    y="530"
    fill="#94A3B8"
    font-family="monospace"
    font-size="11"
  >
    ~/profile $ build --ship
  </text>


  <!-- =========================
       RIGHT SYSTEM.INFO
       ========================= -->

  <rect
    x="560"
    y="90"
    width="580"
    height="470"
    rx="18"
    fill="#020617"
    fill-opacity=".88"
    stroke="url(#neon)"
    stroke-width="2"
    filter="url(#glow)"
  />

  <text
    x="585"
    y="112"
    fill="#22D3EE"
    font-family="monospace"
    font-size="13"
    font-weight="bold"
    letter-spacing="2"
  >
    SYSTEM.INFO
  </text>


  <!-- Online -->

  <circle cx="1080" cy="108" r="5" fill="#10B981">
    <animate
      attributeName="opacity"
      values="1;.3;1"
      dur="2s"
      repeatCount="indefinite"
    />
  </circle>

  <text
    x="1092"
    y="112"
    fill="#10B981"
    font-family="monospace"
    font-size="11"
  >
    online
  </text>


  <!-- Terminal command -->

  <text
    x="585"
    y="145"
    fill="#60A5FA"
    font-family="monospace"
    font-size="13"
    font-weight="bold"
  >
    elango@developer:~$ ./profile.sh
  </text>


  <!-- Profile information -->

  <text x="585" y="180"
        fill="#22D3EE"
        font-family="monospace"
        font-size="12">
    &gt; NAME
  </text>

  <text x="720" y="180"
        fill="#F8FAFC"
        font-family="monospace"
        font-size="12">
    Elango S
  </text>


  <text x="585" y="210"
        fill="#22D3EE"
        font-family="monospace"
        font-size="12">
    &gt; ROLE
  </text>

  <text x="720" y="210"
        fill="#F8FAFC"
        font-family="monospace"
        font-size="12">
    AI/ML Engineer
  </text>


  <text x="585" y="240"
        fill="#22D3EE"
        font-family="monospace"
        font-size="12">
    &gt; FOCUS
  </text>

  <text x="720" y="240"
        fill="#F8FAFC"
        font-family="monospace"
        font-size="12">
    AI Agents · RAG
  </text>


  <text x="585" y="270"
        fill="#22D3EE"
        font-family="monospace"
        font-size="12">
    &gt; STACK
  </text>

  <text x="720" y="270"
        fill="#F8FAFC"
        font-family="monospace"
        font-size="12">
    Python · FastAPI · LangGraph
  </text>


  <text x="720" y="292"
        fill="#94A3B8"
        font-family="monospace"
        font-size="12">
    Neo4j · Qdrant · MySQL
  </text>


  <!-- Projects -->

  <text x="585" y="330"
        fill="#22D3EE"
        font-family="monospace"
        font-size="12">
    &gt; PROJECTS
  </text>

  <text x="605" y="360"
        fill="#67E8F9"
        font-family="monospace"
        font-size="12">
    • MUBIS
  </text>

  <text x="720" y="360"
        fill="#CBD5E1"
        font-family="monospace"
        font-size="12">
    Behavior Intelligence
  </text>


  <text x="605" y="385"
        fill="#67E8F9"
        font-family="monospace"
        font-size="12">
    • Graph RAG
  </text>

  <text x="720" y="385"
        fill="#CBD5E1"
        font-family="monospace"
        font-size="12">
    Neo4j Retrieval
  </text>


  <text x="605" y="410"
        fill="#67E8F9"
        font-family="monospace"
        font-size="12">
    • Vectorless RAG
  </text>

  <text x="720" y="410"
        fill="#CBD5E1"
        font-family="monospace"
        font-size="12">
    Tree-based Retrieval
  </text>


  <text x="605" y="435"
        fill="#67E8F9"
        font-family="monospace"
        font-size="12">
    • Feedback Agent
  </text>


  <!-- Links -->

  <text x="585" y="475"
        fill="#22D3EE"
        font-family="monospace"
        font-size="12">
    &gt; LINKS
  </text>

  <text x="605" y="505"
        fill="#67E8F9"
        font-family="monospace"
        font-size="12">
    GitHub
  </text>

  <text x="720" y="505"
        fill="#CBD5E1"
        font-family="monospace"
        font-size="12">
    github.com/S-ELANGO
  </text>


  <text x="605" y="530"
        fill="#67E8F9"
        font-family="monospace"
        font-size="12">
    LinkedIn
  </text>

  <text x="720" y="530"
        fill="#CBD5E1"
        font-family="monospace"
        font-size="12">
    linkedin.com/in/elango-s-elango/
  </text>


  <!-- Cursor -->

  <rect
    x="585"
    y="545"
    width="8"
    height="15"
    fill="#F8FAFC"
  >
    <animate
      attributeName="opacity"
      values="1;0;1"
      dur="1s"
      repeatCount="indefinite"
    />
  </rect>

</svg>
