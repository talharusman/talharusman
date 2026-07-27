## Hi there 👋
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1180 610" width="1180" height="610">
  <defs>

    <!-- GRADIENTS -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#030712"/>
      <stop offset="100%" stop-color="#0a0f1e"/>
    </linearGradient>

    <linearGradient id="accentGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#7C3AED"/>
      <stop offset="50%" stop-color="#22D3EE"/>
      <stop offset="100%" stop-color="#10B981"/>
    </linearGradient>

    <linearGradient id="accentGradAnim" x1="0%" y1="0%" x2="100%" y2="100%" gradientUnits="userSpaceOnUse">
      <stop offset="0%" stop-color="#7C3AED">
        <animate attributeName="stop-color" values="#7C3AED;#22D3EE;#10B981;#7C3AED" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" stop-color="#22D3EE">
        <animate attributeName="stop-color" values="#22D3EE;#10B981;#7C3AED;#22D3EE" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#10B981">
        <animate attributeName="stop-color" values="#10B981;#7C3AED;#22D3EE;#10B981" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <linearGradient id="asciiGrad" x1="0%" y1="0%" x2="100%" y2="100%" gradientUnits="userSpaceOnUse">
      <stop offset="0%" stop-color="#22D3EE">
        <animate attributeName="stop-color" values="#22D3EE;#7C3AED;#10B981;#22D3EE" dur="5s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#7C3AED">
        <animate attributeName="stop-color" values="#7C3AED;#10B981;#22D3EE;#7C3AED" dur="5s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <linearGradient id="borderShimmer" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="rgba(124,58,237,0)"/>
      <stop offset="40%" stop-color="rgba(34,211,238,0.8)"/>
      <stop offset="60%" stop-color="rgba(16,185,129,0.8)"/>
      <stop offset="100%" stop-color="rgba(124,58,237,0)"/>
      <animateTransform attributeName="gradientTransform" type="translate" values="-1 0;1 0;-1 0" dur="3s" repeatCount="indefinite"/>
    </linearGradient>

    <linearGradient id="panelGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#0F172A" stop-opacity="0.97"/>
      <stop offset="100%" stop-color="#0a0f20" stop-opacity="0.97"/>
    </linearGradient>

    <linearGradient id="titleGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#F8FAFC"/>
      <stop offset="60%" stop-color="#22D3EE"/>
      <stop offset="100%" stop-color="#7C3AED"/>
    </linearGradient>

    <linearGradient id="scanlineGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="rgba(34,211,238,0)" />
      <stop offset="45%" stop-color="rgba(34,211,238,0)" />
      <stop offset="50%" stop-color="rgba(34,211,238,0.06)" />
      <stop offset="55%" stop-color="rgba(34,211,238,0)" />
      <stop offset="100%" stop-color="rgba(34,211,238,0)" />
    </linearGradient>

    <linearGradient id="glassReflect" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="rgba(255,255,255,0.07)"/>
      <stop offset="40%" stop-color="rgba(255,255,255,0.02)"/>
      <stop offset="100%" stop-color="rgba(255,255,255,0)"/>
    </linearGradient>

    <!-- RADIAL GLOWS -->
    <radialGradient id="glowBlue" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#2563EB" stop-opacity="0.18"/>
      <stop offset="100%" stop-color="#2563EB" stop-opacity="0"/>
    </radialGradient>

    <radialGradient id="glowPurple" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#7C3AED" stop-opacity="0.16"/>
      <stop offset="100%" stop-color="#7C3AED" stop-opacity="0"/>
    </radialGradient>

    <radialGradient id="glowEmerald" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#10B981" stop-opacity="0.12"/>
      <stop offset="100%" stop-color="#10B981" stop-opacity="0"/>
    </radialGradient>

    <radialGradient id="glowCyan" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#22D3EE" stop-opacity="0.15"/>
      <stop offset="100%" stop-color="#22D3EE" stop-opacity="0"/>
    </radialGradient>

    <!-- FILTERS -->
    <filter id="glowFilter" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feComposite in="SourceGraphic" in2="blur" operator="over"/>
    </filter>

    <filter id="softGlow" x="-30%" y="-30%" width="160%" height="160%">
      <feGaussianBlur stdDeviation="8" result="blur"/>
      <feComposite in="SourceGraphic" in2="blur" operator="over"/>
    </filter>

    <filter id="pillGlow" x="-20%" y="-50%" width="140%" height="200%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feComposite in="SourceGraphic" in2="blur" operator="over"/>
    </filter>

    <filter id="panelShadow" x="-5%" y="-5%" width="110%" height="120%">
      <feDropShadow dx="0" dy="8" stdDeviation="24" flood-color="#7C3AED" flood-opacity="0.12"/>
    </filter>

    <filter id="noiseFilter">
      <feTurbulence type="fractalNoise" baseFrequency="0.65" numOctaves="3" stitchTiles="stitch" result="noise"/>
      <feColorMatrix type="saturate" values="0" in="noise" result="grayNoise"/>
      <feBlend in="SourceGraphic" in2="grayNoise" mode="overlay" result="blended"/>
      <feComposite in="blended" in2="SourceGraphic" operator="in"/>
    </filter>

    <filter id="asciiGlow" x="-10%" y="-10%" width="120%" height="120%">
      <feGaussianBlur stdDeviation="2.5" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- CLIP PATHS -->
    <clipPath id="mainClip">
      <rect width="1180" height="610" rx="20" ry="20"/>
    </clipPath>

    <clipPath id="leftClip">
      <rect x="0" y="0" width="448" height="610"/>
    </clipPath>

    <clipPath id="rightClip">
      <rect x="460" y="0" width="720" height="610"/>
    </clipPath>

    <!-- PILL gradients -->
    <linearGradient id="pillGrad1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="rgba(124,58,237,0.25)"/>
      <stop offset="100%" stop-color="rgba(34,211,238,0.15)"/>
    </linearGradient>
    <linearGradient id="pillGrad2" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="rgba(34,211,238,0.2)"/>
      <stop offset="100%" stop-color="rgba(16,185,129,0.15)"/>
    </linearGradient>
    <linearGradient id="pillGrad3" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="rgba(16,185,129,0.2)"/>
      <stop offset="100%" stop-color="rgba(124,58,237,0.15)"/>
    </linearGradient>

    <!-- MASKS -->
    <mask id="fadeMaskLeft">
      <linearGradient id="fadeLeftGrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="70%" stop-color="white"/>
        <stop offset="100%" stop-color="black"/>
      </linearGradient>
      <rect width="448" height="610" fill="url(#fadeLeftGrad)"/>
    </mask>

    <!-- SCANLINE animate gradient -->
    <linearGradient id="scanAnim" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="rgba(34,211,238,0.0)"/>
      <stop offset="45%" stop-color="rgba(34,211,238,0.0)"/>
      <stop offset="50%" stop-color="rgba(34,211,238,0.07)"/>
      <stop offset="55%" stop-color="rgba(34,211,238,0.0)"/>
      <stop offset="100%" stop-color="rgba(34,211,238,0.0)">
      </stop>
    </linearGradient>

  </defs>

  <g clip-path="url(#mainClip)">

    <!-- ═══════════════════════════════════════════ -->
    <!-- BACKGROUND -->
    <!-- ═══════════════════════════════════════════ -->
    <rect width="1180" height="610" fill="url(#bgGrad)"/>

    <!-- Floating background glows -->
    <ellipse cx="200" cy="150" rx="280" ry="200" fill="url(#glowBlue)">
      <animate attributeName="cx" values="200;240;200" dur="8s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="150;180;150" dur="10s" repeatCount="indefinite"/>
    </ellipse>
    <ellipse cx="900" cy="400" rx="320" ry="240" fill="url(#glowPurple)">
      <animate attributeName="cx" values="900;860;900" dur="9s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="400;360;400" dur="7s" repeatCount="indefinite"/>
    </ellipse>
    <ellipse cx="600" cy="550" rx="260" ry="180" fill="url(#glowEmerald)">
      <animate attributeName="cx" values="600;640;600" dur="11s" repeatCount="indefinite"/>
    </ellipse>
    <ellipse cx="1050" cy="100" rx="200" ry="150" fill="url(#glowCyan)">
      <animate attributeName="cy" values="100;130;100" dur="6s" repeatCount="indefinite"/>
    </ellipse>

    <!-- Noise overlay -->
    <rect width="1180" height="610" fill="rgba(255,255,255,0.018)" filter="url(#noiseFilter)" opacity="0.4"/>

    <!-- Animated particles -->
    <circle cx="80" cy="80" r="1.5" fill="#22D3EE" opacity="0.6">
      <animate attributeName="cy" values="80;50;80" dur="4s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.6;0.2;0.6" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="320" cy="520" r="1" fill="#7C3AED" opacity="0.5">
      <animate attributeName="cy" values="520;490;520" dur="5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;0.1;0.5" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="700" cy="60" r="1.5" fill="#10B981" opacity="0.5">
      <animate attributeName="cy" values="60;35;60" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;0.15;0.5" dur="6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1100" cy="300" r="1" fill="#22D3EE" opacity="0.4">
      <animate attributeName="cx" values="1100;1080;1100" dur="7s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.4;0.1;0.4" dur="7s" repeatCount="indefinite"/>
    </circle>
    <circle cx="550" cy="560" r="1.5" fill="#7C3AED" opacity="0.5">
      <animate attributeName="cy" values="560;535;560" dur="5.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="950" cy="480" r="1" fill="#10B981" opacity="0.45">
      <animate attributeName="cx" values="950;970;950" dur="8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="160" cy="400" r="1.5" fill="#22D3EE" opacity="0.35">
      <animate attributeName="cy" values="400;375;400" dur="9s" repeatCount="indefinite"/>
    </circle>
    <circle cx="840" cy="140" r="1" fill="#7C3AED" opacity="0.5">
      <animate attributeName="cy" values="140;115;140" dur="4.5s" repeatCount="indefinite"/>
    </circle>

    <!-- ═══════════════════════════════════════════ -->
    <!-- LEFT PANEL — ASCII Terminal -->
    <!-- ═══════════════════════════════════════════ -->
    <g clip-path="url(#leftClip)">

      <!-- Panel bg -->
      <rect x="16" y="16" width="418" height="578" rx="16" ry="16" fill="url(#panelGrad)" filter="url(#panelShadow)"/>
      <!-- Glass reflection -->
      <rect x="16" y="16" width="418" height="200" rx="16" ry="16" fill="url(#glassReflect)"/>
      <!-- Border -->
      <rect x="16" y="16" width="418" height="578" rx="16" ry="16" fill="none" stroke="url(#accentGradAnim)" stroke-width="1.5" opacity="0.6"/>
      <!-- Border shimmer -->
      <rect x="16" y="16" width="418" height="578" rx="16" ry="16" fill="none" stroke="url(#borderShimmer)" stroke-width="1.5"/>

      <!-- Terminal title bar -->
      <rect x="16" y="16" width="418" height="40" rx="16" ry="16" fill="rgba(15,23,42,0.9)"/>
      <rect x="16" y="40" width="418" height="16" fill="rgba(15,23,42,0.9)"/>

      <!-- Traffic lights -->
      <circle cx="44" cy="36" r="6" fill="#FF5F57"/>
      <circle cx="64" cy="36" r="6" fill="#FEBC2E"/>
      <circle cx="84" cy="36" r="6" fill="#28C840"/>

      <!-- Terminal label -->
      <text x="224" y="41" text-anchor="middle" font-family="'SF Mono','Fira Code',monospace" font-size="11" fill="#94A3B8" letter-spacing="2">ASCII.PORTRAIT</text>

      <!-- Scanline sweep over left panel -->
      <rect x="16" y="56" width="418" height="538" rx="0" fill="none"/>
      <rect x="16" y="56" width="418" height="538" fill="rgba(34,211,238,0.03)" opacity="1">
        <animate attributeName="y" values="56;594;56" dur="4s" repeatCount="indefinite"/>
        <animate attributeName="height" values="4;4;4" dur="4s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;1;0" dur="4s" repeatCount="indefinite"/>
      </rect>

      <!-- ── ASCII ART PORTRAIT ── -->
      <g font-family="'SF Mono','Fira Code','Courier New',monospace" font-size="7.2" fill="url(#asciiGrad)" filter="url(#asciiGlow)">
        <g transform="translate(30, 76)">
          <!-- Float animation on whole ASCII block -->
          <g>
            <animateTransform attributeName="transform" type="translate" values="0,0;0,-5;0,0" dur="4s" repeatCount="indefinite" additive="sum"/>

            <!-- Line 1 -->
            <text y="12" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.03;0.06;1" dur="14s" repeatCount="indefinite"/>
              ·····████████████████████████·····
            </text>
            <!-- Line 2 -->
            <text y="22" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.05;0.08;1" dur="14s" repeatCount="indefinite"/>
              ···██░░░░░░░░░░░░░░░░░░░░░░░██···
            </text>
            <!-- Line 3 -->
            <text y="32" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.07;0.10;1" dur="14s" repeatCount="indefinite"/>
              ··█░░░░░░░░░░░░░░░░░░░░░░░░░░░█··
            </text>
            <!-- Line 4 -->
            <text y="42" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.09;0.12;1" dur="14s" repeatCount="indefinite"/>
              ·█░░░░░░░░░░░░░░░░░░░░░░░░░░░░░█·
            </text>
            <!-- Line 5 -->
            <text y="52" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.11;0.14;1" dur="14s" repeatCount="indefinite"/>
              █░░░░░░░░▒▒▒▒▒░░░░░░▒▒▒▒▒░░░░░░█
            </text>
            <!-- Line 6 -->
            <text y="62" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.13;0.16;1" dur="14s" repeatCount="indefinite"/>
              █░░░░░░▒▒████▒▒░░░░▒▒████▒▒░░░░█
            </text>
            <!-- Line 7 -->
            <text y="72" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.15;0.18;1" dur="14s" repeatCount="indefinite"/>
              █░░░░░▒▒██████▒░░░░▒██████▒▒░░░░█
            </text>
            <!-- Line 8 -->
            <text y="82" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.17;0.20;1" dur="14s" repeatCount="indefinite"/>
              █░░░░░▒▒██░░██▒░░░░▒██░░██▒▒░░░░█
            </text>
            <!-- Line 9 -->
            <text y="92" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.19;0.22;1" dur="14s" repeatCount="indefinite"/>
              █░░░░░▒▒██████▒░░░░▒██████▒▒░░░░█
            </text>
            <!-- Line 10 -->
            <text y="102" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.21;0.24;1" dur="14s" repeatCount="indefinite"/>
              █░░░░░░▒▒████▒▒░░░░▒▒████▒▒░░░░░█
            </text>
            <!-- Line 11 -->
            <text y="112" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.23;0.26;1" dur="14s" repeatCount="indefinite"/>
              █░░░░░░░░▒▒░░░░░░░░░░░▒▒░░░░░░░░█
            </text>
            <!-- Line 12 -->
            <text y="122" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.25;0.28;1" dur="14s" repeatCount="indefinite"/>
              █░░░░░░░░░░░░░▒▒▒▒▒░░░░░░░░░░░░░█
            </text>
            <!-- Line 13 -->
            <text y="132" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.27;0.30;1" dur="14s" repeatCount="indefinite"/>
              █░░░░░░░░░░░░▒▒███▒▒░░░░░░░░░░░░█
            </text>
            <!-- Line 14 -->
            <text y="142" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.29;0.32;1" dur="14s" repeatCount="indefinite"/>
              █░░░░░░░░░░░░░▒▒▒▒▒░░░░░░░░░░░░░█
            </text>
            <!-- Line 15 -->
            <text y="152" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.31;0.34;1" dur="14s" repeatCount="indefinite"/>
              █░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░█
            </text>
            <!-- Line 16 -->
            <text y="162" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.33;0.36;1" dur="14s" repeatCount="indefinite"/>
              █░░░▒▒▒▒░░░░░░░░░░░░░░░░▒▒▒▒░░░░█
            </text>
            <!-- Line 17 -->
            <text y="172" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.35;0.38;1" dur="14s" repeatCount="indefinite"/>
              █░░░░░░░▒▒░░░░░░░░░░░░▒▒░░░░░░░░█
            </text>
            <!-- Line 18 -->
            <text y="182" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.37;0.40;1" dur="14s" repeatCount="indefinite"/>
              █░░░░░░░░░▒▒▒▒▒▒▒▒▒▒▒▒░░░░░░░░░░█
            </text>
            <!-- Line 19 -->
            <text y="192" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.39;0.42;1" dur="14s" repeatCount="indefinite"/>
              ·█░░░░░░░░░░░░░░░░░░░░░░░░░░░░░█·
            </text>
            <!-- Line 20 -->
            <text y="202" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.41;0.44;1" dur="14s" repeatCount="indefinite"/>
              ··█░░░░░░░░░░░░░░░░░░░░░░░░░░░█··
            </text>
            <!-- Line 21 -->
            <text y="212" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.43;0.46;1" dur="14s" repeatCount="indefinite"/>
              ···██░░░███████████████░░░░░██···
            </text>
            <!-- Line 22 -->
            <text y="222" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.45;0.48;1" dur="14s" repeatCount="indefinite"/>
              ·····█░░░░░░░░░░░░░░░░░░░░░█·····
            </text>
            <!-- Line 23 -->
            <text y="232" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.47;0.50;1" dur="14s" repeatCount="indefinite"/>
              ·····█░░░▒░░░░░░░░░░░░▒░░░█·····
            </text>
            <!-- Line 24 -->
            <text y="242" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.49;0.52;1" dur="14s" repeatCount="indefinite"/>
              ·····██░░░░░░░░░░░░░░░░░░██·····
            </text>
            <!-- Line 25 -->
            <text y="252" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.51;0.54;1" dur="14s" repeatCount="indefinite"/>
              ·········████░░░░░░████·········
            </text>
            <!-- Line 26 -->
            <text y="262" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.53;0.56;1" dur="14s" repeatCount="indefinite"/>
              ············████████············
            </text>
            <!-- Line 27 -->
            <text y="285" opacity="0">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.55;0.58;1" dur="14s" repeatCount="indefinite"/>
              ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
            </text>
            <!-- Line 28 -->
            <text y="295" opacity="0" font-size="7" fill="#22D3EE">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.58;0.61;1" dur="14s" repeatCount="indefinite"/>
              [ talha@dev ~ ] $ whoami
            </text>
            <!-- Line 29 -->
            <text y="308" opacity="0" font-size="7" fill="#10B981">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.61;0.64;1" dur="14s" repeatCount="indefinite"/>
              → Talha Rusman · Frontend &amp; AI Engineer
            </text>
            <!-- Line 30 -->
            <text y="321" opacity="0" font-size="7" fill="#94A3B8">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.64;0.67;1" dur="14s" repeatCount="indefinite"/>
              → Based in Karachi, Pakistan 🇵🇰
            </text>
            <!-- Line 31 -->
            <text y="334" opacity="0" font-size="7" fill="#22D3EE">
              <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.67;0.70;1" dur="14s" repeatCount="indefinite"/>
              → Building the future, one commit at a time
            </text>
            <!-- Cursor -->
            <rect x="0" y="338" width="7" height="10" fill="#22D3EE" opacity="0">
              <animate attributeName="opacity" values="0;0;0;1;0;1;0;1;0" keyTimes="0;0.70;0.71;0.73;0.75;0.77;0.79;0.81;1" dur="14s" repeatCount="indefinite"/>
            </rect>
          </g>
        </g>
      </g>

      <!-- Bottom glow bar -->
      <rect x="16" y="570" width="418" height="24" rx="0" ry="0" fill="url(#accentGradAnim)" opacity="0.08"/>
      <rect x="16" y="570" width="418" height="24" rx="0" ry="16" fill="none"/>

    </g>

    <!-- ═══════════════════════════════════════════ -->
    <!-- DIVIDER LINE -->
    <!-- ═══════════════════════════════════════════ -->
    <line x1="450" y1="40" x2="450" y2="570" stroke="url(#accentGradAnim)" stroke-width="1" opacity="0.3"/>

    <!-- ═══════════════════════════════════════════ -->
    <!-- RIGHT PANEL — Terminal Info -->
    <!-- ═══════════════════════════════════════════ -->
    <g clip-path="url(#rightClip)">

      <!-- Panel bg -->
      <rect x="462" y="16" width="702" height="578" rx="16" ry="16" fill="url(#panelGrad)" filter="url(#panelShadow)"/>
      <!-- Glass reflection -->
      <rect x="462" y="16" width="702" height="180" rx="16" ry="16" fill="url(#glassReflect)"/>
      <!-- Border -->
      <rect x="462" y="16" width="702" height="578" rx="16" ry="16" fill="none" stroke="url(#accentGradAnim)" stroke-width="1.5" opacity="0.5"/>
      <rect x="462" y="16" width="702" height="578" rx="16" ry="16" fill="none" stroke="url(#borderShimmer)" stroke-width="1.5"/>

      <!-- Terminal title bar -->
      <rect x="462" y="16" width="702" height="40" rx="16" ry="16" fill="rgba(15,23,42,0.95)"/>
      <rect x="462" y="40" width="702" height="16" fill="rgba(15,23,42,0.95)"/>

      <!-- Traffic lights -->
      <circle cx="490" cy="36" r="6" fill="#FF5F57"/>
      <circle cx="510" cy="36" r="6" fill="#FEBC2E"/>
      <circle cx="530" cy="36" r="6" fill="#28C840"/>

      <!-- Terminal label -->
      <text x="813" y="41" text-anchor="middle" font-family="'SF Mono','Fira Code',monospace" font-size="11" fill="#94A3B8" letter-spacing="2">PROFILE.README.MD</text>

      <!-- ── GREETING ── -->
      <text x="492" y="90" font-family="'SF Mono','Fira Code',monospace" font-size="13" fill="#94A3B8" opacity="0">
        <animate attributeName="opacity" values="0;1" begin="0.4s" dur="0.5s" fill="freeze"/>
        Hi there 👋
      </text>

      <!-- ── NAME ── -->
      <text x="492" y="128" font-family="system-ui,sans-serif" font-size="34" font-weight="700" fill="url(#titleGrad)" opacity="0">
        <animate attributeName="opacity" values="0;1" begin="0.8s" dur="0.6s" fill="freeze"/>
        I'm Talha Rusman
      </text>

      <!-- Underline accent -->
      <rect x="492" y="136" width="0" height="2" rx="1" fill="url(#accentGradAnim)" opacity="0.8">
        <animate attributeName="width" values="0;340" begin="1.2s" dur="0.8s" fill="freeze"/>
      </rect>

      <!-- ── ANIMATED TYPING ROLE ── -->
      <g font-family="'SF Mono','Fira Code',monospace" font-size="16" fill="#22D3EE">
        <text x="492" y="170">
          <!-- Cycle through roles via visibility -->
          <tspan opacity="1">
            <animate attributeName="opacity" values="1;1;0;0;0;0;0;0;0;0;1;1" keyTimes="0;0.18;0.21;0.25;0.26;0.44;0.47;0.68;0.71;0.90;0.93;1" dur="12s" repeatCount="indefinite"/>
            Frontend Engineer
          </tspan>
        </text>
        <text x="492" y="170" opacity="0">
          <animate attributeName="opacity" values="0;0;1;1;0;0;0;0;0;0;0;0" keyTimes="0;0.20;0.22;0.42;0.44;0.46;0.48;0.68;0.70;0.90;0.92;1" dur="12s" repeatCount="indefinite"/>
          AI Engineer
        </text>
        <text x="492" y="170" opacity="0">
          <animate attributeName="opacity" values="0;0;0;0;0;1;1;0;0;0;0;0" keyTimes="0;0.20;0.22;0.44;0.46;0.48;0.65;0.67;0.68;0.90;0.92;1" dur="12s" repeatCount="indefinite"/>
          Full Stack Developer
        </text>
        <text x="492" y="170" opacity="0">
          <animate attributeName="opacity" values="0;0;0;0;0;0;0;1;1;0;0;0" keyTimes="0;0.20;0.22;0.44;0.46;0.68;0.70;0.72;0.88;0.90;0.92;1" dur="12s" repeatCount="indefinite"/>
          UI Engineer
        </text>

        <!-- Blinking cursor after role -->
        <rect x="780" y="154" width="2" height="18" fill="#22D3EE">
          <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
        </rect>
      </g>

      <!-- ── SEPARATOR ── -->
      <line x1="492" y1="188" x2="1148" y2="188" stroke="rgba(255,255,255,0.06)" stroke-width="1"/>

      <!-- ── INFO ROWS ── -->
      <g font-family="'SF Mono','Fira Code',monospace" font-size="12.5">

        <!-- Location -->
        <g opacity="0">
          <animate attributeName="opacity" values="0;1" begin="1.5s" dur="0.4s" fill="freeze"/>
          <text x="492" y="218" fill="#94A3B8">📍</text>
          <text x="520" y="218" fill="#94A3B8">Location</text>
          <text x="640" y="218" fill="#475569">·············</text>
          <text x="760" y="218" fill="#F8FAFC">Karachi, Pakistan</text>
        </g>

        <!-- Education -->
        <g opacity="0">
          <animate attributeName="opacity" values="0;1" begin="1.9s" dur="0.4s" fill="freeze"/>
          <text x="492" y="244" fill="#94A3B8">🎓</text>
          <text x="520" y="244" fill="#94A3B8">Education</text>
          <text x="640" y="244" fill="#475569">············</text>
          <text x="760" y="244" fill="#F8FAFC">Computer Science</text>
        </g>

        <!-- Focus -->
        <g opacity="0">
          <animate attributeName="opacity" values="0;1" begin="2.3s" dur="0.4s" fill="freeze"/>
          <text x="492" y="270" fill="#94A3B8">🚀</text>
          <text x="520" y="270" fill="#94A3B8">Current Focus</text>
          <text x="640" y="270" fill="#475569">·······</text>
          <text x="760" y="270" fill="#F8FAFC">AI &amp; Web Engineering</text>
        </g>

        <!-- Portfolio -->
        <g opacity="0">
          <animate attributeName="opacity" values="0;1" begin="2.7s" dur="0.4s" fill="freeze"/>
          <text x="492" y="296" fill="#94A3B8">🌐</text>
          <text x="520" y="296" fill="#94A3B8">Portfolio</text>
          <text x="640" y="296" fill="#475569">·············</text>
          <text x="760" y="296" fill="#22D3EE">talharusman.dev</text>
        </g>

        <!-- Email -->
        <g opacity="0">
          <animate attributeName="opacity" values="0;1" begin="3.1s" dur="0.4s" fill="freeze"/>
          <text x="492" y="322" fill="#94A3B8">✉</text>
          <text x="520" y="322" fill="#94A3B8">Email</text>
          <text x="640" y="322" fill="#475569">················</text>
          <text x="760" y="322" fill="#10B981" font-size="11.5">talharusman2004@gmail.com</text>
        </g>

      </g>

      <!-- ── SEPARATOR ── -->
      <line x1="492" y1="340" x2="1148" y2="340" stroke="rgba(255,255,255,0.06)" stroke-width="1"/>

      <!-- ── SKILLS HEADER ── -->
      <text x="492" y="367" font-family="'SF Mono','Fira Code',monospace" font-size="11" fill="#94A3B8" letter-spacing="3" opacity="0">
        <animate attributeName="opacity" values="0;1" begin="3.5s" dur="0.4s" fill="freeze"/>
        SKILLS &amp; TECHNOLOGIES
      </text>

      <!-- ── SKILL PILLS ROW 1 ── -->
      <g opacity="0">
        <animate attributeName="opacity" values="0;1" begin="3.8s" dur="0.5s" fill="freeze"/>

        <!-- React -->
        <rect x="492" y="380" width="72" height="26" rx="13" fill="url(#pillGrad1)" stroke="#22D3EE" stroke-width="1" stroke-opacity="0.5" filter="url(#pillGlow)"/>
        <text x="528" y="397" text-anchor="middle" font-family="system-ui,sans-serif" font-size="11" font-weight="500" fill="#22D3EE">React</text>

        <!-- Next.js -->
        <rect x="574" y="380" width="72" height="26" rx="13" fill="url(#pillGrad2)" stroke="#7C3AED" stroke-width="1" stroke-opacity="0.5" filter="url(#pillGlow)"/>
        <text x="610" y="397" text-anchor="middle" font-family="system-ui,sans-serif" font-size="11" font-weight="500" fill="#A78BFA">Next.js</text>

        <!-- Node.js -->
        <rect x="656" y="380" width="72" height="26" rx="13" fill="url(#pillGrad3)" stroke="#10B981" stroke-width="1" stroke-opacity="0.5" filter="url(#pillGlow)"/>
        <text x="692" y="397" text-anchor="middle" font-family="system-ui,sans-serif" font-size="11" font-weight="500" fill="#10B981">Node.js</text>

        <!-- TypeScript -->
        <rect x="738" y="380" width="88" height="26" rx="13" fill="url(#pillGrad1)" stroke="#22D3EE" stroke-width="1" stroke-opacity="0.5" filter="url(#pillGlow)"/>
        <text x="782" y="397" text-anchor="middle" font-family="system-ui,sans-serif" font-size="11" font-weight="500" fill="#22D3EE">TypeScript</text>

        <!-- Tailwind -->
        <rect x="836" y="380" width="76" height="26" rx="13" fill="url(#pillGrad2)" stroke="#7C3AED" stroke-width="1" stroke-opacity="0.5" filter="url(#pillGlow)"/>
        <text x="874" y="397" text-anchor="middle" font-family="system-ui,sans-serif" font-size="11" font-weight="500" fill="#A78BFA">Tailwind</text>

      </g>

      <!-- ── SKILL PILLS ROW 2 ── -->
      <g opacity="0">
        <animate attributeName="opacity" values="0;1" begin="4.1s" dur="0.5s" fill="freeze"/>

        <!-- Python -->
        <rect x="492" y="416" width="72" height="26" rx="13" fill="url(#pillGrad3)" stroke="#10B981" stroke-width="1" stroke-opacity="0.5" filter="url(#pillGlow)"/>
        <text x="528" y="433" text-anchor="middle" font-family="system-ui,sans-serif" font-size="11" font-weight="500" fill="#10B981">Python</text>

        <!-- AWS -->
        <rect x="574" y="416" width="60" height="26" rx="13" fill="url(#pillGrad1)" stroke="#22D3EE" stroke-width="1" stroke-opacity="0.5" filter="url(#pillGlow)"/>
        <text x="604" y="433" text-anchor="middle" font-family="system-ui,sans-serif" font-size="11" font-weight="500" fill="#22D3EE">AWS</text>

        <!-- Git -->
        <rect x="644" y="416" width="56" height="26" rx="13" fill="url(#pillGrad2)" stroke="#7C3AED" stroke-width="1" stroke-opacity="0.5" filter="url(#pillGlow)"/>
        <text x="672" y="433" text-anchor="middle" font-family="system-ui,sans-serif" font-size="11" font-weight="500" fill="#A78BFA">Git</text>

        <!-- Docker -->
        <rect x="710" y="416" width="68" height="26" rx="13" fill="url(#pillGrad3)" stroke="#10B981" stroke-width="1" stroke-opacity="0.5" filter="url(#pillGlow)"/>
        <text x="744" y="433" text-anchor="middle" font-family="system-ui,sans-serif" font-size="11" font-weight="500" fill="#10B981">Docker</text>

        <!-- PostgreSQL -->
        <rect x="788" y="416" width="92" height="26" rx="13" fill="url(#pillGrad1)" stroke="#22D3EE" stroke-width="1" stroke-opacity="0.5" filter="url(#pillGlow)"/>
        <text x="834" y="433" text-anchor="middle" font-family="system-ui,sans-serif" font-size="11" font-weight="500" fill="#22D3EE">PostgreSQL</text>

      </g>

      <!-- ── SEPARATOR ── -->
      <line x1="492" y1="456" x2="1148" y2="456" stroke="rgba(255,255,255,0.06)" stroke-width="1"/>

      <!-- ── SOCIAL HEADER ── -->
      <text x="492" y="482" font-family="'SF Mono','Fira Code',monospace" font-size="11" fill="#94A3B8" letter-spacing="3" opacity="0">
        <animate attributeName="opacity" values="0;1" begin="4.4s" dur="0.4s" fill="freeze"/>
        CONNECT
      </text>

      <!-- ── SOCIAL ICONS ── -->
      <g opacity="0">
        <animate attributeName="opacity" values="0;1" begin="4.7s" dur="0.5s" fill="freeze"/>

        <!-- GitHub icon card -->
        <rect x="492" y="495" width="110" height="42" rx="10" fill="rgba(15,23,42,0.8)" stroke="rgba(255,255,255,0.08)" stroke-width="1" filter="url(#pillGlow)"/>
        <!-- GitHub mark (simplified) -->
        <text x="520" y="521" text-anchor="middle" font-size="18" fill="#F8FAFC">⌥</text>
        <text x="556" y="521" font-family="system-ui,sans-serif" font-size="12" fill="#F8FAFC" font-weight="500">GitHub</text>

        <!-- LinkedIn icon card -->
        <rect x="614" y="495" width="118" height="42" rx="10" fill="rgba(15,23,42,0.8)" stroke="rgba(34,211,238,0.15)" stroke-width="1" filter="url(#pillGlow)"/>
        <text x="642" y="521" text-anchor="middle" font-size="18" fill="#22D3EE">◈</text>
        <text x="678" y="521" font-family="system-ui,sans-serif" font-size="12" fill="#22D3EE" font-weight="500">LinkedIn</text>

        <!-- Portfolio icon card -->
        <rect x="744" y="495" width="118" height="42" rx="10" fill="rgba(15,23,42,0.8)" stroke="rgba(16,185,129,0.15)" stroke-width="1" filter="url(#pillGlow)"/>
        <text x="772" y="521" text-anchor="middle" font-size="18" fill="#10B981">⊛</text>
        <text x="806" y="521" font-family="system-ui,sans-serif" font-size="12" fill="#10B981" font-weight="500">Portfolio</text>

        <!-- Glow pulse on cards -->
        <rect x="492" y="495" width="110" height="42" rx="10" fill="url(#glowPurple)" opacity="0.4">
          <animate attributeName="opacity" values="0.4;0.8;0.4" dur="3s" repeatCount="indefinite"/>
        </rect>
        <rect x="614" y="495" width="118" height="42" rx="10" fill="url(#glowCyan)" opacity="0.4">
          <animate attributeName="opacity" values="0.4;0.8;0.4" dur="3.5s" repeatCount="indefinite"/>
        </rect>
        <rect x="744" y="495" width="118" height="42" rx="10" fill="url(#glowEmerald)" opacity="0.4">
          <animate attributeName="opacity" values="0.4;0.8;0.4" dur="4s" repeatCount="indefinite"/>
        </rect>

      </g>

      <!-- Scanline sweep right panel -->
      <rect x="462" y="56" width="702" height="4" fill="rgba(34,211,238,0.05)" opacity="0">
        <animate attributeName="y" values="56;594;56" dur="5s" repeatCount="indefinite" begin="2s"/>
        <animate attributeName="opacity" values="0;1;0" dur="5s" repeatCount="indefinite" begin="2s"/>
      </rect>

    </g>

    <!-- ═══════════════════════════════════════════ -->
    <!-- OUTER BORDER SHIMMER -->
    <!-- ═══════════════════════════════════════════ -->
    <rect width="1180" height="610" rx="20" ry="20" fill="none" stroke="url(#accentGradAnim)" stroke-width="2" opacity="0.4"/>
    <rect width="1180" height="610" rx="20" ry="20" fill="none" stroke="url(#borderShimmer)" stroke-width="2"/>

  </g>
</svg>
<!--
**talharusman/talharusman** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# 💫 About Me:
🔭 I’m currently working on AI-powered systems, data structures projects in C/C++, and full-stack web apps using Next.js & TypeScript<br>🌱 I’m currently learning Machine Learning, MERN stack, system programming, and advanced problem solving<br>👯 I’m looking to collaborate on AI projects, open-source tools, web applications, and data science projects<br>🤔 I’m looking for help with scaling AI projects, system design, and competitive programming optimization<br>💬 Ask me about C/C++, Python, Data Structures, AI concepts, Pandas, FastAPI, Next.js, and project architecture<br>📫 How to reach me: GitHub Issues / Discussions or professional platforms<br>😄 Pronouns: He/Him<br>⚡ Fun fact: I enjoy turning complex AI & system concepts into clean, working projects 🚀


## 🌐 Socials:
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/talharusman06) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/talharusman) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:talharusman2004@gmail.com) 

# 💻 Tech Stack:
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![React Query](https://img.shields.io/badge/-React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=talharusman&theme=tokyonight&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=talharusman&theme=tokyonight&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=talharusman&theme=tokyonight&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

---
[![](https://visitcount.itsvg.in/api?id=talharusman&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
