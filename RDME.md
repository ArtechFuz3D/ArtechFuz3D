<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!-- ARTECH FUZ3D — GITHUB PROFILE README                                   -->
<!-- THEME: SCI-FI / AEROSPACE / MECHANICAL / TERMINAL DASHBOARD            -->
<!-- Drop this file into your ArtechFuz3D/ArtechFuz3D repo as README.md    -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

<div align="center">

<!-- ════════════════════════════════════════════════════════════ -->
<!--           ANIMATED MECH HEADER BANNER                       -->
<!-- ════════════════════════════════════════════════════════════ -->

<svg width="100%" viewBox="0 0 860 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#030C14"/>
      <stop offset="50%" style="stop-color:#071420"/>
      <stop offset="100%" style="stop-color:#030C14"/>
    </linearGradient>
    <linearGradient id="cyanGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:transparent"/>
      <stop offset="50%" style="stop-color:#00FFFF"/>
      <stop offset="100%" style="stop-color:transparent"/>
    </linearGradient>
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#00FFFF"/>
      <stop offset="60%" style="stop-color:#00CCCC"/>
      <stop offset="100%" style="stop-color:#008888"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="2" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect width="860" height="200" fill="url(#bgGrad)"/>
  <!-- Grid lines -->
  <g opacity="0.12">
    <line x1="0" y1="40" x2="860" y2="40" stroke="#00FFFF" stroke-width="0.5"/>
    <line x1="0" y1="80" x2="860" y2="80" stroke="#00FFFF" stroke-width="0.3"/>
    <line x1="0" y1="120" x2="860" y2="120" stroke="#00FFFF" stroke-width="0.3"/>
    <line x1="0" y1="160" x2="860" y2="160" stroke="#00FFFF" stroke-width="0.5"/>
    <line x1="43" y1="0" x2="43" y2="200" stroke="#00FFFF" stroke-width="0.3"/>
    <line x1="817" y1="0" x2="817" y2="200" stroke="#00FFFF" stroke-width="0.3"/>
  </g>
  <!-- Scan line animation -->
  <rect x="0" y="0" width="860" height="2" fill="url(#cyanGrad)" opacity="0.7">
    <animateTransform attributeName="transform" type="translate" values="0,0;0,198;0,0" dur="4s" repeatCount="indefinite"/>
  </rect>
  <!-- Corner brackets -->
  <polyline points="30,10 10,10 10,30" fill="none" stroke="#00FFFF" stroke-width="2" filter="url(#glow)"/>
  <polyline points="830,10 850,10 850,30" fill="none" stroke="#00FFFF" stroke-width="2" filter="url(#glow)"/>
  <polyline points="30,190 10,190 10,170" fill="none" stroke="#00FFFF" stroke-width="2" filter="url(#glow)"/>
  <polyline points="830,190 850,190 850,170" fill="none" stroke="#00FFFF" stroke-width="2" filter="url(#glow)"/>
  <!-- Left mech deco -->
  <g opacity="0.45">
    <polyline points="10,90 80,90 90,80 130,80" fill="none" stroke="#00FFFF" stroke-width="0.7"/>
    <circle cx="133" cy="80" r="3.5" fill="none" stroke="#00FFFF" stroke-width="1">
      <animate attributeName="r" values="3.5;5.5;3.5" dur="2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="1;0.3;1" dur="2s" repeatCount="indefinite"/>
    </circle>
    <polyline points="10,110 60,110 72,122" fill="none" stroke="#00FFFF" stroke-width="0.7"/>
    <rect x="70" y="120" width="7" height="7" fill="none" stroke="#FF4500" stroke-width="1">
      <animate attributeName="opacity" values="1;0.15;1" dur="1.5s" repeatCount="indefinite"/>
    </rect>
  </g>
  <!-- Right mech deco -->
  <g opacity="0.45">
    <polyline points="850,90 780,90 770,80 730,80" fill="none" stroke="#00FFFF" stroke-width="0.7"/>
    <circle cx="727" cy="80" r="3.5" fill="none" stroke="#00FFFF" stroke-width="1">
      <animate attributeName="r" values="3.5;5.5;3.5" dur="2.3s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="1;0.3;1" dur="2.3s" repeatCount="indefinite"/>
    </circle>
    <polyline points="850,110 800,110 788,122" fill="none" stroke="#00FFFF" stroke-width="0.7"/>
    <rect x="783" y="120" width="7" height="7" fill="none" stroke="#FF4500" stroke-width="1">
      <animate attributeName="opacity" values="1;0.15;1" dur="1.8s" repeatCount="indefinite"/>
    </rect>
  </g>
  <!-- Ghost glitch layer -->
  <text x="432" y="95" text-anchor="middle" font-family="'Courier New', monospace" font-size="52" font-weight="900" fill="#FF4500" opacity="0.10" letter-spacing="8">ARTECH FUZ3D</text>
  <!-- Main title -->
  <text x="430" y="95" text-anchor="middle" font-family="'Courier New', monospace" font-size="52" font-weight="900" fill="url(#textGrad)" letter-spacing="8" filter="url(#glow)">ARTECH FUZ3D</text>
  <!-- Designation -->
  <text x="430" y="125" text-anchor="middle" font-family="'Courier New', monospace" font-size="11" fill="#00AAAA" letter-spacing="4">◈  AEROSPACE  ·  MECHANICAL  ·  3D  ·  DESIGN SYSTEMS  ◈</text>
  <!-- Status row -->
  <circle cx="190" cy="155" r="4" fill="#00FF41">
    <animate attributeName="opacity" values="1;0.2;1" dur="1.4s" repeatCount="indefinite"/>
  </circle>
  <text x="198" y="159" font-family="'Courier New', monospace" font-size="9" fill="#00FF41" letter-spacing="2">ONLINE</text>
  <text x="252" y="159" font-family="'Courier New', monospace" font-size="9" fill="#0A3040">│</text>
  <text x="262" y="159" font-family="'Courier New', monospace" font-size="9" fill="#00FFFF" letter-spacing="2">CLEARANCE: LVL-9</text>
  <text x="386" y="159" font-family="'Courier New', monospace" font-size="9" fill="#0A3040">│</text>
  <circle cx="398" cy="155" r="3" fill="#FF4500">
    <animate attributeName="r" values="3;4.5;3" dur="2s" repeatCount="indefinite"/>
  </circle>
  <text x="405" y="159" font-family="'Courier New', monospace" font-size="9" fill="#FF4500" letter-spacing="2">DESIGN OPS: ACTIVE</text>
  <text x="540" y="159" font-family="'Courier New', monospace" font-size="9" fill="#0A3040">│</text>
  <text x="550" y="159" font-family="'Courier New', monospace" font-size="9" fill="#6ABCCC" letter-spacing="2">BASE: PRETORIA, ZA</text>
  <!-- Bottom line -->
  <rect x="0" y="196" width="860" height="1" fill="url(#cyanGrad)" opacity="0.5"/>
  <text x="848" y="195" text-anchor="end" font-family="'Courier New', monospace" font-size="8" fill="#0D2A38" letter-spacing="1">AF3D-HUD v4.2.1</text>
</svg>

<br/>

<!-- ════════════════════════════════════════════════════════════ -->
<!--                OPERATOR TERMINAL                            -->
<!-- ════════════════════════════════════════════════════════════ -->

<svg width="100%" viewBox="0 0 860 178" xmlns="http://www.w3.org/2000/svg">
  <rect width="860" height="178" rx="2" fill="#050F1A" stroke="#0D4050" stroke-width="1"/>
  <!-- Title bar -->
  <rect width="860" height="26" rx="2" fill="#071420"/>
  <rect y="26" width="860" height="1" fill="#0D4050"/>
  <circle cx="16" cy="13" r="5" fill="#FF4500"/>
  <circle cx="32" cy="13" r="5" fill="#FFD700"/>
  <circle cx="48" cy="13" r="5" fill="#00FF41"/>
  <text x="430" y="17" text-anchor="middle" font-family="'Courier New', monospace" font-size="9" fill="#3A7080" letter-spacing="3">◈  OPERATOR CONFIG  /  PILOT.YAML  ◈</text>
  <!-- Content -->
  <text x="20" y="50" font-family="'Courier New', monospace" font-size="11" fill="#3A7080">root@artech-hud:~$</text>
  <text x="160" y="50" font-family="'Courier New', monospace" font-size="11" fill="#00FFFF">cat operator.yaml</text>
  <text x="20" y="70" font-family="'Courier New', monospace" font-size="11" fill="#6ABCCC">CALLSIGN</text>
  <text x="115" y="70" font-family="'Courier New', monospace" font-size="11" fill="#3A7080">:</text>
  <text x="130" y="70" font-family="'Courier New', monospace" font-size="11" fill="#00FF41">ArtechFuz3D</text>
  <text x="350" y="70" font-family="'Courier New', monospace" font-size="11" fill="#3A7080">│</text>
  <text x="368" y="70" font-family="'Courier New', monospace" font-size="11" fill="#6ABCCC">LOCATION</text>
  <text x="450" y="70" font-family="'Courier New', monospace" font-size="11" fill="#3A7080">:</text>
  <text x="465" y="70" font-family="'Courier New', monospace" font-size="11" fill="#00FF41">Pretoria, South Africa</text>
  <text x="20" y="90" font-family="'Courier New', monospace" font-size="11" fill="#6ABCCC">SPECIALITY</text>
  <text x="125" y="90" font-family="'Courier New', monospace" font-size="11" fill="#3A7080">:</text>
  <text x="140" y="90" font-family="'Courier New', monospace" font-size="11" fill="#A0E8FF">Aerospace · Mechanical · Hard-Surface 3D · Design Systems</text>
  <text x="20" y="110" font-family="'Courier New', monospace" font-size="11" fill="#6ABCCC">TOOLCHAIN</text>
  <text x="115" y="110" font-family="'Courier New', monospace" font-size="11" fill="#3A7080">:</text>
  <text x="130" y="110" font-family="'Courier New', monospace" font-size="11" fill="#A0E8FF">Blender  ·  Fusion 360  ·  Unreal Engine  ·  Python  ·  FreeCAD</text>
  <text x="20" y="130" font-family="'Courier New', monospace" font-size="11" fill="#6ABCCC">FABRICATION</text>
  <text x="135" y="130" font-family="'Courier New', monospace" font-size="11" fill="#3A7080">:</text>
  <text x="150" y="130" font-family="'Courier New', monospace" font-size="11" fill="#A0E8FF">FDM · Resin 3D Printing · CNC · Laser Cutting · Composites</text>
  <text x="20" y="150" font-family="'Courier New', monospace" font-size="11" fill="#6ABCCC">PHILOSOPHY</text>
  <text x="120" y="150" font-family="'Courier New', monospace" font-size="11" fill="#3A7080">:</text>
  <text x="135" y="150" font-family="'Courier New', monospace" font-size="11" fill="#FF4500">"Design is engineering with soul."</text>
  <text x="20" y="168" font-family="'Courier New', monospace" font-size="11" fill="#3A7080">root@artech-hud:~$</text>
  <rect x="160" y="157" width="8" height="13" fill="#00FFFF">
    <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
  </rect>
</svg>

<br/>

<!-- ════════════════════════════════════════════════════════════ -->
<!--          STAT DASHBOARD — CUSTOM ENGINE                     -->
<!-- ════════════════════════════════════════════════════════════ -->

<svg width="100%" viewBox="0 0 860 108" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="cB" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" style="stop-color:#004444"/><stop offset="100%" style="stop-color:#00FFFF"/></linearGradient>
    <linearGradient id="oB" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" style="stop-color:#440000"/><stop offset="100%" style="stop-color:#FF4500"/></linearGradient>
    <linearGradient id="gB" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" style="stop-color:#004400"/><stop offset="100%" style="stop-color:#00FF41"/></linearGradient>
  </defs>
  <!-- Panel 1 -->
  <rect x="0" y="0" width="272" height="105" rx="2" fill="#050F1A" stroke="#0D4050" stroke-width="1"/>
  <rect x="0" y="0" width="272" height="3" rx="1" fill="#00FFFF" opacity="0.7"/>
  <text x="14" y="22" font-family="'Courier New', monospace" font-size="8" fill="#3A7080" letter-spacing="2">SYS-01  ◈  REPOSITORIES</text>
  <text x="14" y="62" font-family="'Courier New', monospace" font-size="36" font-weight="bold" fill="#00FFFF"><!--REPOS-->—<!--/REPOS--></text>
  <text x="14" y="80" font-family="'Courier New', monospace" font-size="9" fill="#6ABCCC">▲ PUBLIC REPOS · AUTO-UPDATES DAILY</text>
  <rect x="14" y="92" width="244" height="3" rx="1" fill="#071420"/>
  <rect x="14" y="92" width="180" height="3" rx="1" fill="url(#cB)">
    <animate attributeName="width" values="0;180" dur="1.2s" fill="freeze"/>
  </rect>
  <!-- Panel 2 -->
  <rect x="294" y="0" width="272" height="105" rx="2" fill="#050F1A" stroke="#0D4050" stroke-width="1"/>
  <rect x="294" y="0" width="272" height="3" rx="1" fill="#FF4500" opacity="0.7"/>
  <text x="308" y="22" font-family="'Courier New', monospace" font-size="8" fill="#3A7080" letter-spacing="2">SYS-02  ◈  FOLLOWERS</text>
  <text x="308" y="62" font-family="'Courier New', monospace" font-size="36" font-weight="bold" fill="#FF4500"><!--FOLLOWERS-->—<!--/FOLLOWERS--></text>
  <text x="308" y="80" font-family="'Courier New', monospace" font-size="9" fill="#6ABCCC">▲ GITHUB FOLLOWERS · LIVE COUNT</text>
  <rect x="308" y="92" width="244" height="3" rx="1" fill="#071420"/>
  <rect x="308" y="92" width="120" height="3" rx="1" fill="url(#oB)">
    <animate attributeName="width" values="0;120" dur="1.4s" fill="freeze"/>
  </rect>
  <!-- Panel 3 -->
  <rect x="588" y="0" width="272" height="105" rx="2" fill="#050F1A" stroke="#0D4050" stroke-width="1"/>
  <rect x="588" y="0" width="272" height="3" rx="1" fill="#00FF41" opacity="0.7"/>
  <text x="602" y="22" font-family="'Courier New', monospace" font-size="8" fill="#3A7080" letter-spacing="2">SYS-03  ◈  TOTAL STARS</text>
  <text x="602" y="62" font-family="'Courier New', monospace" font-size="36" font-weight="bold" fill="#00FF41"><!--STARS-->★<!--/STARS--></text>
  <text x="602" y="80" font-family="'Courier New', monospace" font-size="9" fill="#6ABCCC">▲ STARS ACROSS ALL REPOS</text>
  <rect x="602" y="92" width="244" height="3" rx="1" fill="#071420"/>
  <rect x="602" y="92" width="80" height="3" rx="1" fill="url(#gB)">
    <animate attributeName="width" values="0;80" dur="1.6s" fill="freeze"/>
  </rect>
</svg>

</div>

<br/>

<!-- ════════════════════════════════════════════════════════════ -->
<!--          SKILL MATRIX — ANIMATED BARS + RADAR              -->
<!-- ════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="100%" viewBox="0 0 860 238" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="cBar" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" style="stop-color:#004444"/><stop offset="100%" style="stop-color:#00FFFF"/></linearGradient>
    <linearGradient id="oBar" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" style="stop-color:#440000"/><stop offset="100%" style="stop-color:#FF4500"/></linearGradient>
    <linearGradient id="gBar" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" style="stop-color:#004400"/><stop offset="100%" style="stop-color:#00FF41"/></linearGradient>
  </defs>
  <rect width="860" height="238" rx="2" fill="#050F1A" stroke="#0D4050" stroke-width="1"/>
  <rect width="860" height="3" fill="#00FFFF" opacity="0.35"/>
  <text x="430" y="26" text-anchor="middle" font-family="'Courier New', monospace" font-size="9" fill="#3A7080" letter-spacing="4">◈  CAPABILITY MATRIX  /  SKILL TELEMETRY  ◈</text>
  <line x1="20" y1="36" x2="840" y2="36" stroke="#0A3040" stroke-width="0.5"/>
  <!-- Skill bars left -->
  <g font-family="'Courier New', monospace" font-size="10">
    <text x="24" y="60" fill="#6ABCCC" letter-spacing="1">BLENDER / 3D MODELLING</text>
    <text x="395" y="60" text-anchor="end" fill="#00FFFF">95%</text>
    <rect x="24" y="65" width="371" height="5" rx="2" fill="#071420"/>
    <rect x="24" y="65" width="0" height="5" rx="2" fill="url(#cBar)">
      <animate attributeName="width" values="0;352" dur="0.8s" begin="0.1s" fill="freeze"/>
    </rect>
    <text x="24" y="92" fill="#6ABCCC" letter-spacing="1">FUSION 360 / CAD</text>
    <text x="395" y="92" text-anchor="end" fill="#00FFFF">88%</text>
    <rect x="24" y="97" width="371" height="5" rx="2" fill="#071420"/>
    <rect x="24" y="97" width="0" height="5" rx="2" fill="url(#cBar)">
      <animate attributeName="width" values="0;326" dur="0.8s" begin="0.2s" fill="freeze"/>
    </rect>
    <text x="24" y="124" fill="#6ABCCC" letter-spacing="1">3D PRINTING / FDM / RESIN</text>
    <text x="395" y="124" text-anchor="end" fill="#FF4500">92%</text>
    <rect x="24" y="129" width="371" height="5" rx="2" fill="#071420"/>
    <rect x="24" y="129" width="0" height="5" rx="2" fill="url(#oBar)">
      <animate attributeName="width" values="0;341" dur="0.8s" begin="0.3s" fill="freeze"/>
    </rect>
    <text x="24" y="156" fill="#6ABCCC" letter-spacing="1">UNREAL ENGINE / REAL-TIME VIZ</text>
    <text x="395" y="156" text-anchor="end" fill="#00FFFF">78%</text>
    <rect x="24" y="161" width="371" height="5" rx="2" fill="#071420"/>
    <rect x="24" y="161" width="0" height="5" rx="2" fill="url(#cBar)">
      <animate attributeName="width" values="0;289" dur="0.8s" begin="0.4s" fill="freeze"/>
    </rect>
    <text x="24" y="188" fill="#6ABCCC" letter-spacing="1">PYTHON / SCRIPTING</text>
    <text x="395" y="188" text-anchor="end" fill="#00FF41">74%</text>
    <rect x="24" y="193" width="371" height="5" rx="2" fill="#071420"/>
    <rect x="24" y="193" width="0" height="5" rx="2" fill="url(#gBar)">
      <animate attributeName="width" values="0;274" dur="0.8s" begin="0.5s" fill="freeze"/>
    </rect>
    <text x="24" y="220" fill="#6ABCCC" letter-spacing="1">COMPOSITES / FABRICATION</text>
    <text x="395" y="220" text-anchor="end" fill="#FF4500">82%</text>
    <rect x="24" y="225" width="371" height="5" rx="2" fill="#071420"/>
    <rect x="24" y="225" width="0" height="5" rx="2" fill="url(#oBar)">
      <animate attributeName="width" values="0;304" dur="0.8s" begin="0.6s" fill="freeze"/>
    </rect>
  </g>
  <!-- Vertical divider -->
  <line x1="420" y1="40" x2="420" y2="230" stroke="#0A3040" stroke-width="0.5"/>
  <!-- Radar chart right side -->
  <g transform="translate(640, 135)">
    <polygon points="0,-75 65,-37.5 65,37.5 0,75 -65,37.5 -65,-37.5" fill="none" stroke="#0A3040" stroke-width="0.5"/>
    <polygon points="0,-56 49,-28 49,28 0,56 -49,28 -49,-28" fill="none" stroke="#0A3040" stroke-width="0.5"/>
    <polygon points="0,-37 32,-18.5 32,18.5 0,37 -32,18.5 -32,-18.5" fill="none" stroke="#0A3040" stroke-width="0.5"/>
    <polygon points="0,-19 16,-9.5 16,9.5 0,19 -16,9.5 -16,-9.5" fill="none" stroke="#0A3040" stroke-width="0.5"/>
    <line x1="0" y1="-75" x2="0" y2="75" stroke="#071420" stroke-width="0.5"/>
    <line x1="-65" y1="-37.5" x2="65" y2="37.5" stroke="#071420" stroke-width="0.5"/>
    <line x1="-65" y1="37.5" x2="65" y2="-37.5" stroke="#071420" stroke-width="0.5"/>
    <!-- Data -->
    <polygon points="0,-71 57,-28 52,35 0,63 -55,34 -47,-33" fill="#00FFFF" fill-opacity="0.06" stroke="#00CCCC" stroke-width="1.5">
      <animateTransform attributeName="transform" type="scale" values="0;1" dur="0.9s" fill="freeze"/>
    </polygon>
    <!-- Labels -->
    <text x="0" y="-82" text-anchor="middle" font-family="'Courier New', monospace" font-size="9" fill="#00FFFF">3D</text>
    <text x="76" y="-33" font-family="'Courier New', monospace" font-size="9" fill="#6ABCCC">CAD</text>
    <text x="72" y="44" font-family="'Courier New', monospace" font-size="9" fill="#6ABCCC">FAB</text>
    <text x="0" y="90" text-anchor="middle" font-family="'Courier New', monospace" font-size="9" fill="#6ABCCC">CODE</text>
    <text x="-85" y="44" font-family="'Courier New', monospace" font-size="9" fill="#6ABCCC">ART</text>
    <text x="-85" y="-33" font-family="'Courier New', monospace" font-size="9" fill="#6ABCCC">VIZ</text>
    <circle cx="0" cy="0" r="4" fill="#00FFFF">
      <animate attributeName="r" values="4;6;4" dur="2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="1;0.5;1" dur="2s" repeatCount="indefinite"/>
    </circle>
  </g>
</svg>

</div>

<br/>

<!-- ════════════════════════════════════════════════════════════ -->
<!--           MISSION DOSSIER — PROJECT CARDS                   -->
<!-- ════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="100%" viewBox="0 0 860 28" xmlns="http://www.w3.org/2000/svg">
  <rect y="14" width="860" height="1" fill="#0D4050"/>
  <text x="430" y="20" text-anchor="middle" font-family="'Courier New', monospace" font-size="9" fill="#3A7080" letter-spacing="4">◈  ACTIVE MISSION DOSSIER  /  CLASSIFIED PROJECTS  ◈</text>
</svg>

</div>

<table width="100%"><tr>
<td width="50%" valign="top">

```
╔══════════════════════════════════════╗
║  ◈ MISSION-001                       ║
║  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━  ║
║  AEROSPACE-PRINT-LAB                 ║
║  STATUS  : ● ACTIVE                  ║
║  TECH    : Blender · Python          ║
║  TYPE    : Fabrication Framework     ║
╚══════════════════════════════════════╝
```

**Parametric aerospace-grade 3D print library.** Structural brackets, airfoil profiles, duct systems — fully parametric and field-ready.

`#parametric` `#aerospace` `#blender` `#3dprint`

</td>
<td width="50%" valign="top">

```
╔══════════════════════════════════════╗
║  ◈ MISSION-002                       ║
║  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━  ║
║  MECH-VIZ-ENGINE                     ║
║  STATUS  : ◎ IN DEVELOPMENT          ║
║  TECH    : Unreal Engine · Python    ║
║  TYPE    : Visualization Pipeline    ║
╚══════════════════════════════════════╝
```

**Real-time mechanical visualization pipeline.** Exploded views, assembly animations, and cinematic CAD rendering.

`#unrealengine` `#cad` `#animation` `#realtime`

</td>
</tr><tr>
<td width="50%" valign="top">

```
╔══════════════════════════════════════╗
║  ◈ MISSION-003                       ║
║  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━  ║
║  COMPOSITE-TOOLKIT                   ║
║  STATUS  : ● ACTIVE                  ║
║  TECH    : Python · FreeCAD          ║
║  TYPE    : Engineering Toolkit       ║
╚══════════════════════════════════════╝
```

**Carbon fibre & composite layup design toolkit.** Ply calculators, layup generators, mold geometry scripts.

`#composites` `#carbonfibre` `#engineering` `#python`

</td>
<td width="50%" valign="top">

```
╔══════════════════════════════════════╗
║  ◈ MISSION-004                       ║
║  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━  ║
║  SCIFI-PROP-VAULT                    ║
║  STATUS  : ◈ CLASSIFIED              ║
║  TECH    : Blender · Substance       ║
║  TYPE    : Open Asset Library        ║
╚══════════════════════════════════════╝
```

**Free open-source sci-fi hard-surface asset vault.** Greeble panels, mechanical props — PBR game-ready.

`#scifi` `#blender` `#hardsurface` `#pbr`

</td>
</tr></table>

<div align="center">
<sub>🔧 Replace project names and repo slugs with your actual repositories — see setup guide below 🔧</sub>
</div>

<br/>

<!-- ════════════════════════════════════════════════════════════ -->
<!--          CONTRIBUTION SNAKE — ACTIVATE VIA ACTIONS          -->
<!-- ════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="100%" viewBox="0 0 860 24" xmlns="http://www.w3.org/2000/svg">
  <text x="430" y="16" text-anchor="middle" font-family="'Courier New', monospace" font-size="9" fill="#3A7080" letter-spacing="4">◈  COMMIT TELEMETRY  /  CONTRIBUTION GRID  ◈</text>
</svg>

<!-- SNAKE: Once you run the GitHub Action, replace this comment block with: -->
<!--
<picture>
  <source media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/ArtechFuz3D/ArtechFuz3D/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/ArtechFuz3D/ArtechFuz3D/output/github-contribution-grid-snake.svg">
  <img src="https://raw.githubusercontent.com/ArtechFuz3D/ArtechFuz3D/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</picture>
-->

<!-- Placeholder activity grid until snake is live -->
<svg width="100%" viewBox="0 0 860 100" xmlns="http://www.w3.org/2000/svg">
  <rect width="860" height="100" rx="2" fill="#050F1A" stroke="#0D4050" stroke-width="1"/>
  <text x="14" y="20" font-family="'Courier New', monospace" font-size="8" fill="#3A7080" letter-spacing="2">JAN    FEB    MAR    APR    MAY    JUN    JUL    AUG    SEP    OCT    NOV    DEC</text>
  <!-- Simulated grid rows -->
  <g opacity="0.6">
    <rect x="14" y="28" width="833" height="10" rx="2" fill="#004444"/>
    <rect x="14" y="42" width="600" height="10" rx="2" fill="#007777"/>
    <rect x="14" y="56" width="750" height="10" rx="2" fill="#004444"/>
    <rect x="14" y="70" width="400" height="10" rx="2" fill="#00AAAA"/>
    <rect x="14" y="84" width="700" height="10" rx="2" fill="#007777"/>
  </g>
  <!-- Active streak highlight -->
  <rect x="700" y="26" width="147" height="70" rx="2" fill="#00FFFF" fill-opacity="0.04" stroke="#00FFFF" stroke-width="0.5"/>
  <text x="773" y="106" text-anchor="middle" font-family="'Courier New', monospace" font-size="8" fill="#00AAAA">ACTIVE</text>
  <!-- Legend -->
  <rect x="660" y="88" width="9" height="9" rx="2" fill="#0A1A22"/>
  <rect x="672" y="88" width="9" height="9" rx="2" fill="#004444"/>
  <rect x="684" y="88" width="9" height="9" rx="2" fill="#007777"/>
  <rect x="696" y="88" width="9" height="9" rx="2" fill="#00AAAA"/>
  <rect x="708" y="88" width="9" height="9" rx="2" fill="#00FFFF"/>
  <text x="720" y="96" font-family="'Courier New', monospace" font-size="7" fill="#3A7080">MORE</text>
  <text x="645" y="96" text-anchor="end" font-family="'Courier New', monospace" font-size="7" fill="#3A7080">LESS</text>
</svg>

</div>

<br/>

<!-- ════════════════════════════════════════════════════════════ -->
<!--                COMMS CHANNELS / SOCIALS                     -->
<!-- ════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="100%" viewBox="0 0 860 24" xmlns="http://www.w3.org/2000/svg">
  <text x="430" y="16" text-anchor="middle" font-family="'Courier New', monospace" font-size="9" fill="#3A7080" letter-spacing="4">◈  OPEN COMMS CHANNELS  ◈</text>
</svg>

[![GitHub](https://img.shields.io/badge/GITHUB-ArtechFuz3D-00FFFF?style=for-the-badge&logo=github&logoColor=black&labelColor=030C14)](https://github.com/ArtechFuz3D)
[![ArtStation](https://img.shields.io/badge/ARTSTATION-Portfolio-00FFFF?style=for-the-badge&logo=artstation&logoColor=black&labelColor=030C14)](https://artstation.com/)
[![YouTube](https://img.shields.io/badge/YOUTUBE-Channel-FF4500?style=for-the-badge&logo=youtube&logoColor=white&labelColor=030C14)](https://youtube.com/)
[![Instagram](https://img.shields.io/badge/INSTAGRAM-Feed-FF4500?style=for-the-badge&logo=instagram&logoColor=white&labelColor=030C14)](https://instagram.com/)
[![Printables](https://img.shields.io/badge/PRINTABLES-Models-00FF41?style=for-the-badge&logo=prusa&logoColor=black&labelColor=030C14)](https://printables.com/)
[![Discord](https://img.shields.io/badge/DISCORD-Server-00FF41?style=for-the-badge&logo=discord&logoColor=black&labelColor=030C14)](https://discord.com/)

<br/>

![Visitors](https://komarev.com/ghpvc/?username=ArtechFuz3D&style=for-the-badge&color=00FFFF&labelColor=030C14&label=PROFILE+VISITORS)
![Followers](https://img.shields.io/github/followers/ArtechFuz3D?style=for-the-badge&color=00FFFF&labelColor=030C14&logo=github&label=FOLLOWERS)

<br/>

<!-- ════════════════════════════════════════════════════════════ -->
<!--                   ANIMATED FOOTER                           -->
<!-- ════════════════════════════════════════════════════════════ -->

<svg width="100%" viewBox="0 0 860 56" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="fGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:transparent"/>
      <stop offset="50%" style="stop-color:#00FFFF"/>
      <stop offset="100%" style="stop-color:transparent"/>
    </linearGradient>
  </defs>
  <rect width="860" height="56" fill="#030C14"/>
  <rect y="0" width="860" height="1" fill="url(#fGrad)" opacity="0.5"/>
  <!-- Animated pulse line -->
  <rect x="-200" y="1" width="200" height="1" fill="#00FFFF" opacity="0.5">
    <animateTransform attributeName="transform" type="translate" values="0,0;1060,0" dur="3s" repeatCount="indefinite"/>
  </rect>
  <text x="430" y="26" text-anchor="middle" font-family="'Courier New', monospace" font-size="9" fill="#3A7080" letter-spacing="3">[ SYS: END OF TRANSMISSION ]  ━━━━━━━━━━━━━━━━  ARTECH FUZ3D  ◈</text>
  <text x="430" y="44" text-anchor="middle" font-family="'Courier New', monospace" font-size="9" fill="#1A3040" letter-spacing="2">Design is engineering with soul.</text>
</svg>

</div>

---

<details>
<summary><strong>⚙ SETUP GUIDE — Activate Every Feature (click to expand)</strong></summary>

<br/>

## 🛠 Full Activation Checklist

### 1. 🐍 Contribution Snake Animation

Create `.github/workflows/snake.yml` in your **profile repo**:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ArtechFuz3D
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

Then **uncomment** the `<picture>` block in the contribution section and delete the placeholder SVG above it.

---

### 2. 📊 Custom Stat Engine — Auto-Updating Numbers

Create `.github/workflows/update-stats.yml`:

```yaml
name: Update README Stats

on:
  schedule:
    - cron: "0 6 * * *"
  workflow_dispatch:

jobs:
  update:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Fetch and inject stats
        run: |
          python3 << 'EOF'
          import urllib.request, json, re

          user = "ArtechFuz3D"
          headers = {"User-Agent": "readme-bot"}

          # Fetch user stats
          req = urllib.request.Request(f"https://api.github.com/users/{user}", headers=headers)
          data = json.loads(urllib.request.urlopen(req).read())
          repos = str(data.get("public_repos", "—"))
          followers = str(data.get("followers", "—"))

          # Fetch all repos and sum stars
          req2 = urllib.request.Request(
              f"https://api.github.com/users/{user}/repos?per_page=100", headers=headers)
          repos_data = json.loads(urllib.request.urlopen(req2).read())
          stars = str(sum(r.get("stargazers_count", 0) for r in repos_data))

          with open("README.md", "r") as f:
              content = f.read()

          content = re.sub(r'<!--REPOS-->.*?<!--/REPOS-->', f'<!--REPOS-->{repos}<!--/REPOS-->', content)
          content = re.sub(r'<!--FOLLOWERS-->.*?<!--/FOLLOWERS-->', f'<!--FOLLOWERS-->{followers}<!--/FOLLOWERS-->', content)
          content = re.sub(r'<!--STARS-->.*?<!--/STARS-->', f'<!--STARS-->{stars}<!--/STARS-->', content)

          with open("README.md", "w") as f:
              f.write(content)

          print(f"Updated: repos={repos}, followers={followers}, stars={stars}")
          EOF
      - uses: actions/add-and-commit@v9
        with:
          message: "chore: auto-update README stats [skip ci]"
          default_author: github_actions
```

The `<!--REPOS-->`, `<!--FOLLOWERS-->`, `<!--STARS-->` comment markers in the README SVGs are the injection points — the script replaces them automatically.

---

### 3. 🃏 Update Project Cards with Your Real Repos

In the 4 mission card sections, update:
- Mission name and code title
- STATUS (ACTIVE / IN DEVELOPMENT / CLASSIFIED)
- Tech stack and description
- Tags to match your actual repo topics

---

### 4. 🔗 Update All Social Links

Replace the placeholder `https://artstation.com/`, `https://youtube.com/` etc. in the badge links with your actual profile URLs.

---

### 5. 🚀 Maximize This Profile Repo — Power User Strategies

| Strategy | What to Do |
|---|---|
| **Renders folder** | Add `/renders/` with your best `.png` renders, link them in each project card |
| **GitHub Pages** | Enable Pages on this repo → free instant portfolio site |
| **Pinned repos** | Pin your 6 best repos from profile settings so they show under this README |
| **Release packs** | Create GitHub Releases with `.blend`, `.stl`, `.step` attachments for each project |
| **Topics** | Add `3d-printing`, `aerospace`, `blender`, `cad` tags to each repo for discoverability |
| **FUNDING.yml** | Add `.github/FUNDING.yml` to enable the Sponsor button on your profile |
| **Discussions devlog** | Use GitHub Discussions as a public build log for WIP projects |
| **README per repo** | Give every repo its own themed terminal-style README — builds brand consistency |
| **Issue templates** | Add issue templates for bug reports and feature requests to look professional |
| **GitHub Actions showcase** | Build a small automation per repo and feature it in the README — recruiters love this |

</details>
