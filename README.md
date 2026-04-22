<div align="center">

<!-- ████████████████████  WEB HEADER  ████████████████████ -->

<svg width="900" height="80" viewBox="0 0 900 80" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Creepster&amp;display=swap');
    </style>
  </defs>
  <!-- top web lines -->
  <line x1="0" y1="0" x2="450" y2="80" stroke="#8B0000" stroke-width="0.6" opacity="0.5"/>
  <line x1="100" y1="0" x2="450" y2="80" stroke="#8B0000" stroke-width="0.6" opacity="0.5"/>
  <line x1="200" y1="0" x2="450" y2="80" stroke="#8B0000" stroke-width="0.6" opacity="0.5"/>
  <line x1="300" y1="0" x2="450" y2="80" stroke="#8B0000" stroke-width="0.6" opacity="0.5"/>
  <line x1="400" y1="0" x2="450" y2="80" stroke="#8B0000" stroke-width="0.6" opacity="0.5"/>
  <line x1="500" y1="0" x2="450" y2="80" stroke="#8B0000" stroke-width="0.6" opacity="0.5"/>
  <line x1="600" y1="0" x2="450" y2="80" stroke="#8B0000" stroke-width="0.6" opacity="0.5"/>
  <line x1="700" y1="0" x2="450" y2="80" stroke="#8B0000" stroke-width="0.6" opacity="0.5"/>
  <line x1="800" y1="0" x2="450" y2="80" stroke="#8B0000" stroke-width="0.6" opacity="0.5"/>
  <line x1="900" y1="0" x2="450" y2="80" stroke="#8B0000" stroke-width="0.6" opacity="0.5"/>
  <!-- arcs -->
  <path d="M0,0 Q450,40 900,0" fill="none" stroke="#8B0000" stroke-width="0.5" opacity="0.4"/>
  <path d="M0,0 Q450,20 900,0" fill="none" stroke="#8B0000" stroke-width="0.5" opacity="0.3"/>
</svg>

<!-- ████████████████████  ANIMATED NAME  ████████████████████ -->

<svg width="900" height="160" viewBox="0 0 900 160" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#FF0000;stop-opacity:1">
        <animate attributeName="stop-color" values="#FF0000;#8B0000;#CC0000;#FF0000" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" style="stop-color:#ffffff;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#8B0000;stop-opacity:1">
        <animate attributeName="stop-color" values="#8B0000;#FF0000;#8B0000" dur="4s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="shadow">
      <feDropShadow dx="3" dy="3" stdDeviation="4" flood-color="#8B0000" flood-opacity="0.9"/>
    </filter>
  </defs>
  <!-- web lines behind name -->
  <line x1="0" y1="80" x2="900" y2="80" stroke="#8B0000" stroke-width="0.4" opacity="0.3"/>
  <line x1="0" y1="100" x2="900" y2="100" stroke="#8B0000" stroke-width="0.4" opacity="0.2"/>

  <!-- A -->
  <text x="50" y="120" font-family="Georgia, serif" font-size="90" font-weight="900" font-style="italic"
        fill="url(#nameGrad)" filter="url(#glow)" opacity="0">
    A
    <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.0s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,-30;0,0" dur="0.3s" begin="0.0s" fill="freeze"/>
  </text>
  <!-- F -->
  <text x="115" y="120" font-family="Georgia, serif" font-size="90" font-weight="900" font-style="italic"
        fill="url(#nameGrad)" filter="url(#glow)" opacity="0">
    F
    <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.15s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,-30;0,0" dur="0.3s" begin="0.15s" fill="freeze"/>
  </text>
  <!-- R -->
  <text x="170" y="120" font-family="Georgia, serif" font-size="90" font-weight="900" font-style="italic"
        fill="url(#nameGrad)" filter="url(#glow)" opacity="0">
    R
    <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.3s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,-30;0,0" dur="0.3s" begin="0.3s" fill="freeze"/>
  </text>
  <!-- E -->
  <text x="238" y="120" font-family="Georgia, serif" font-size="90" font-weight="900" font-style="italic"
        fill="url(#nameGrad)" filter="url(#glow)" opacity="0">
    E
    <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.45s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,-30;0,0" dur="0.3s" begin="0.45s" fill="freeze"/>
  </text>
  <!-- E -->
  <text x="300" y="120" font-family="Georgia, serif" font-size="90" font-weight="900" font-style="italic"
        fill="url(#nameGrad)" filter="url(#glow)" opacity="0">
    E
    <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.6s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,-30;0,0" dur="0.3s" begin="0.6s" fill="freeze"/>
  </text>
  <!-- N -->
  <text x="362" y="120" font-family="Georgia, serif" font-size="90" font-weight="900" font-style="italic"
        fill="url(#nameGrad)" filter="url(#glow)" opacity="0">
    N
    <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.75s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,-30;0,0" dur="0.3s" begin="0.75s" fill="freeze"/>
  </text>
  <!-- space + T -->
  <text x="468" y="120" font-family="Georgia, serif" font-size="90" font-weight="900" font-style="italic"
        fill="#ffffff" filter="url(#shadow)" opacity="0">
    T
    <animate attributeName="opacity" values="0;1" dur="0.2s" begin="0.9s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,-30;0,0" dur="0.3s" begin="0.9s" fill="freeze"/>
  </text>
  <!-- A -->
  <text x="528" y="120" font-family="Georgia, serif" font-size="90" font-weight="900" font-style="italic"
        fill="#ffffff" filter="url(#shadow)" opacity="0">
    A
    <animate attributeName="opacity" values="0;1" dur="0.2s" begin="1.05s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,-30;0,0" dur="0.3s" begin="1.05s" fill="freeze"/>
  </text>
  <!-- H -->
  <text x="600" y="120" font-family="Georgia, serif" font-size="90" font-weight="900" font-style="italic"
        fill="#ffffff" filter="url(#shadow)" opacity="0">
    H
    <animate attributeName="opacity" values="0;1" dur="0.2s" begin="1.2s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,-30;0,0" dur="0.3s" begin="1.2s" fill="freeze"/>
  </text>
  <!-- I -->
  <text x="679" y="120" font-family="Georgia, serif" font-size="90" font-weight="900" font-style="italic"
        fill="#ffffff" filter="url(#shadow)" opacity="0">
    I
    <animate attributeName="opacity" values="0;1" dur="0.2s" begin="1.35s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,-30;0,0" dur="0.3s" begin="1.35s" fill="freeze"/>
  </text>
  <!-- R -->
  <text x="710" y="120" font-family="Georgia, serif" font-size="90" font-weight="900" font-style="italic"
        fill="#ffffff" filter="url(#shadow)" opacity="0">
    R
    <animate attributeName="opacity" values="0;1" dur="0.2s" begin="1.5s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate" values="0,-30;0,0" dur="0.3s" begin="1.5s" fill="freeze"/>
  </text>
  <!-- underline sweep -->
  <rect x="50" y="130" width="0" height="4" fill="#8B0000" rx="2">
    <animate attributeName="width" from="0" to="760" dur="0.8s" begin="1.6s" fill="freeze"/>
  </rect>
</svg>

<!-- ████████████████████  SPIDER GIF (pure SVG animated)  ████████████████████ -->

<svg width="120" height="160" viewBox="0 0 120 160" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="bodyGrad" cx="50%" cy="40%" r="50%">
      <stop offset="0%" stop-color="#CC0000"/>
      <stop offset="100%" stop-color="#4A0000"/>
    </radialGradient>
    <radialGradient id="abdomenGrad" cx="50%" cy="60%" r="50%">
      <stop offset="0%" stop-color="#1a1a1a"/>
      <stop offset="100%" stop-color="#000000"/>
    </radialGradient>
  </defs>

  <!-- web thread from top -->
  <line x1="60" y1="0" x2="60" y2="35" stroke="#cccccc" stroke-width="1.5" opacity="0.8">
    <animate attributeName="y2" values="35;45;35" dur="2s" repeatCount="indefinite"/>
  </line>

  <!-- spider body group - bouncing -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,8;0,0" dur="2s" repeatCount="indefinite"/>

    <!-- legs left -->
    <line x1="46" y1="55" x2="20" y2="40" stroke="#1a1a1a" stroke-width="2.5" stroke-linecap="round">
      <animate attributeName="x2" values="20;14;20" dur="0.5s" repeatCount="indefinite"/>
      <animate attributeName="y2" values="40;36;40" dur="0.5s" repeatCount="indefinite"/>
    </line>
    <line x1="44" y1="60" x2="16" y2="58" stroke="#1a1a1a" stroke-width="2.5" stroke-linecap="round">
      <animate attributeName="x2" values="16;10;16" dur="0.5s" begin="0.1s" repeatCount="indefinite"/>
      <animate attributeName="y2" values="58;54;58" dur="0.5s" begin="0.1s" repeatCount="indefinite"/>
    </line>
    <line x1="44" y1="66" x2="18" y2="74" stroke="#1a1a1a" stroke-width="2.5" stroke-linecap="round">
      <animate attributeName="x2" values="18;12;18" dur="0.5s" begin="0.2s" repeatCount="indefinite"/>
    </line>
    <line x1="46" y1="72" x2="22" y2="85" stroke="#1a1a1a" stroke-width="2.5" stroke-linecap="round">
      <animate attributeName="x2" values="22;16;22" dur="0.5s" begin="0.15s" repeatCount="indefinite"/>
    </line>

    <!-- legs right -->
    <line x1="74" y1="55" x2="100" y2="40" stroke="#1a1a1a" stroke-width="2.5" stroke-linecap="round">
      <animate attributeName="x2" values="100;106;100" dur="0.5s" repeatCount="indefinite"/>
      <animate attributeName="y2" values="40;36;40" dur="0.5s" repeatCount="indefinite"/>
    </line>
    <line x1="76" y1="60" x2="104" y2="58" stroke="#1a1a1a" stroke-width="2.5" stroke-linecap="round">
      <animate attributeName="x2" values="104;110;104" dur="0.5s" begin="0.1s" repeatCount="indefinite"/>
      <animate attributeName="y2" values="58;54;58" dur="0.5s" begin="0.1s" repeatCount="indefinite"/>
    </line>
    <line x1="76" y1="66" x2="102" y2="74" stroke="#1a1a1a" stroke-width="2.5" stroke-linecap="round">
      <animate attributeName="x2" values="102;108;102" dur="0.5s" begin="0.2s" repeatCount="indefinite"/>
    </line>
    <line x1="74" y1="72" x2="98" y2="85" stroke="#1a1a1a" stroke-width="2.5" stroke-linecap="round">
      <animate attributeName="x2" values="98;104;98" dur="0.5s" begin="0.15s" repeatCount="indefinite"/>
    </line>

    <!-- cephalothorax (head+chest) -->
    <ellipse cx="60" cy="60" rx="18" ry="16" fill="url(#bodyGrad)"/>
    <!-- web pattern on body -->
    <line x1="42" y1="60" x2="78" y2="60" stroke="#8B0000" stroke-width="0.8" opacity="0.6"/>
    <line x1="60" y1="44" x2="60" y2="76" stroke="#8B0000" stroke-width="0.8" opacity="0.6"/>
    <ellipse cx="60" cy="60" rx="18" ry="16" fill="none" stroke="#8B0000" stroke-width="1" opacity="0.4"/>

    <!-- eyes -->
    <ellipse cx="53" cy="54" rx="5" ry="4" fill="white"/>
    <ellipse cx="67" cy="54" rx="5" ry="4" fill="white"/>
    <circle cx="54" cy="54" r="2.5" fill="#000000"/>
    <circle cx="68" cy="54" r="2.5" fill="#000000"/>
    <circle cx="55" cy="53" r="1" fill="white"/>
    <circle cx="69" cy="53" r="1" fill="white"/>

    <!-- abdomen -->
    <ellipse cx="60" cy="92" rx="20" ry="24" fill="url(#abdomenGrad)"/>
    <!-- red hourglass marking -->
    <path d="M52,82 L68,82 L62,92 L68,102 L52,102 L58,92 Z" fill="#8B0000" opacity="0.8"/>
    <!-- web pattern on abdomen -->
    <ellipse cx="60" cy="92" rx="20" ry="24" fill="none" stroke="#333" stroke-width="0.8" opacity="0.5"/>
    <line x1="40" y1="92" x2="80" y2="92" stroke="#333" stroke-width="0.6" opacity="0.4"/>

    <!-- spinnerets -->
    <ellipse cx="60" cy="116" rx="5" ry="3" fill="#1a1a1a"/>
    <!-- silk thread from bottom -->
    <line x1="60" y1="119" x2="60" y2="130" stroke="#cccccc" stroke-width="1" opacity="0.6">
      <animate attributeName="y2" values="119;135;119" dur="2s" repeatCount="indefinite"/>
    </line>
  </g>
</svg>

<!-- ████████████████████  SUBTITLE  ████████████████████ -->

<svg width="700" height="50" viewBox="0 0 700 50" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="subGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#8B0000"/>
      <stop offset="50%" stop-color="#CC0000"/>
      <stop offset="100%" stop-color="#8B0000"/>
    </linearGradient>
  </defs>
  <!-- decorative left web -->
  <path d="M10,25 L80,25 M10,25 L45,5 M10,25 L45,45 M45,5 L80,25 M45,45 L80,25 M45,5 L45,45" 
        fill="none" stroke="#8B0000" stroke-width="0.8" opacity="0.6"/>
  <!-- decorative right web -->
  <path d="M690,25 L620,25 M690,25 L655,5 M690,25 L655,45 M655,5 L620,25 M655,45 L620,25 M655,5 L655,45" 
        fill="none" stroke="#8B0000" stroke-width="0.8" opacity="0.6"/>
  <text x="350" y="32" text-anchor="middle" font-family="Georgia, serif" font-size="18" 
        letter-spacing="6" fill="url(#subGrad)" font-style="italic">
    BS BDA · Business Development · Marketing
  </text>
</svg>

<!-- ████████████████████  WEB DIVIDER  ████████████████████ -->

<svg width="800" height="30" viewBox="0 0 800 30" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="15" x2="800" y2="15" stroke="#8B0000" stroke-width="0.6" opacity="0.4"/>
  <!-- small webs along line -->
  <circle cx="100" cy="15" r="3" fill="#8B0000" opacity="0.6"/>
  <circle cx="200" cy="15" r="3" fill="#8B0000" opacity="0.6"/>
  <circle cx="300" cy="15" r="3" fill="#8B0000" opacity="0.6"/>
  <circle cx="400" cy="15" r="5" fill="#8B0000" opacity="0.8"/>
  <circle cx="500" cy="15" r="3" fill="#8B0000" opacity="0.6"/>
  <circle cx="600" cy="15" r="3" fill="#8B0000" opacity="0.6"/>
  <circle cx="700" cy="15" r="3" fill="#8B0000" opacity="0.6"/>
  <!-- mini webs at nodes -->
  <path d="M95,10 L105,10 M95,20 L105,20 M100,5 L100,25 M96,11 L104,19 M104,11 L96,19" 
        stroke="#8B0000" stroke-width="0.5" opacity="0.5"/>
  <path d="M395,8 L405,8 M395,22 L405,22 M400,3 L400,27 M396,9 L404,21 M404,9 L396,21" 
        stroke="#8B0000" stroke-width="0.5" opacity="0.5"/>
</svg>

</div>

---

<!-- ████████████████████  ABOUT  ████████████████████ -->

<div align="center">

<svg width="600" height="40" viewBox="0 0 600 40" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="hGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#8B0000"/>
      <stop offset="50%" stop-color="#FF0000"/>
      <stop offset="100%" stop-color="#8B0000"/>
    </linearGradient>
  </defs>
  <!-- web corner left -->
  <path d="M20,35 L60,35 M20,35 L40,10 M40,10 L60,35" fill="none" stroke="#8B0000" stroke-width="1" opacity="0.7"/>
  <circle cx="20" cy="35" r="2" fill="#8B0000"/>
  <circle cx="60" cy="35" r="2" fill="#8B0000"/>
  <circle cx="40" cy="10" r="2" fill="#8B0000"/>
  <!-- web corner right -->
  <path d="M580,35 L540,35 M580,35 L560,10 M560,10 L540,35" fill="none" stroke="#8B0000" stroke-width="1" opacity="0.7"/>
  <circle cx="580" cy="35" r="2" fill="#8B0000"/>
  <circle cx="540" cy="35" r="2" fill="#8B0000"/>
  <circle cx="560" cy="10" r="2" fill="#8B0000"/>
  <text x="300" y="28" text-anchor="middle" font-family="Georgia, serif" font-size="22" 
        font-weight="bold" letter-spacing="4" fill="url(#hGrad)">◈  ABOUT ME  ◈</text>
</svg>

</div>

<br/>

```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║   Hey there! I'm Afreen — a Business Development &              ║
║   Marketing strategist who also codes. I bridge the gap         ║
║   between sharp business thinking and technical execution.       ║
║                                                                  ║
║   I spin webs of strategy, catch opportunities in my net,       ║
║   and build things that actually work — from pitch decks        ║
║   to Python pipelines. Every project gets my full venom. 🕷️    ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

---

<!-- ████████████████████  SKILLS  ████████████████████ -->

<div align="center">

<svg width="600" height="40" viewBox="0 0 600 40" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="hGrad2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#8B0000"/>
      <stop offset="50%" stop-color="#FF0000"/>
      <stop offset="100%" stop-color="#8B0000"/>
    </linearGradient>
  </defs>
  <path d="M20,35 L60,35 M20,35 L40,10 M40,10 L60,35" fill="none" stroke="#8B0000" stroke-width="1" opacity="0.7"/>
  <circle cx="20" cy="35" r="2" fill="#8B0000"/>
  <circle cx="40" cy="10" r="2" fill="#8B0000"/>
  <circle cx="60" cy="35" r="2" fill="#8B0000"/>
  <path d="M580,35 L540,35 M580,35 L560,10 M560,10 L540,35" fill="none" stroke="#8B0000" stroke-width="1" opacity="0.7"/>
  <circle cx="580" cy="35" r="2" fill="#8B0000"/>
  <circle cx="560" cy="10" r="2" fill="#8B0000"/>
  <circle cx="540" cy="35" r="2" fill="#8B0000"/>
  <text x="300" y="28" text-anchor="middle" font-family="Georgia, serif" font-size="22" 
        font-weight="bold" letter-spacing="4" fill="url(#hGrad2)">◈  WEB OF SKILLS  ◈</text>
</svg>

</div>

<br/>

<div align="center">

<!-- Skill web SVG -->
<svg width="700" height="320" viewBox="0 0 700 320" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="skillGrad" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#8B0000" stop-opacity="0.3"/>
      <stop offset="100%" stop-color="#000000" stop-opacity="0"/>
    </radialGradient>
    <filter id="skillGlow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- web rings -->
  <circle cx="350" cy="160" r="40" fill="none" stroke="#8B0000" stroke-width="0.6" opacity="0.3"/>
  <circle cx="350" cy="160" r="80" fill="none" stroke="#8B0000" stroke-width="0.6" opacity="0.3"/>
  <circle cx="350" cy="160" r="120" fill="none" stroke="#8B0000" stroke-width="0.6" opacity="0.25"/>
  <circle cx="350" cy="160" r="145" fill="none" stroke="#8B0000" stroke-width="0.5" opacity="0.2"/>

  <!-- web spokes -->
  <line x1="350" y1="15" x2="350" y2="305" stroke="#8B0000" stroke-width="0.5" opacity="0.25"/>
  <line x1="205" y1="76" x2="495" y2="244" stroke="#8B0000" stroke-width="0.5" opacity="0.25"/>
  <line x1="205" y1="244" x2="495" y2="76" stroke="#8B0000" stroke-width="0.5" opacity="0.25"/>
  <line x1="60" y1="160" x2="640" y2="160" stroke="#8B0000" stroke-width="0.5" opacity="0.25"/>
  <line x1="100" y1="56" x2="600" y2="264" stroke="#8B0000" stroke-width="0.5" opacity="0.2"/>
  <line x1="100" y1="264" x2="600" y2="56" stroke="#8B0000" stroke-width="0.5" opacity="0.2"/>

  <!-- center dot -->
  <circle cx="350" cy="160" r="8" fill="#8B0000" opacity="0.9" filter="url(#skillGlow)">
    <animate attributeName="r" values="8;12;8" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.9;0.5;0.9" dur="2s" repeatCount="indefinite"/>
  </circle>

  <!-- Skill nodes -->
  <!-- Business Dev - top -->
  <circle cx="350" cy="25" r="36" fill="#0d0000" stroke="#8B0000" stroke-width="1.5"/>
  <circle cx="350" cy="25" r="36" fill="none" stroke="#FF0000" stroke-width="0.5" opacity="0.4">
    <animate attributeName="r" values="36;40;36" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0.1;0.4" dur="3s" repeatCount="indefinite"/>
  </circle>
  <text x="350" y="19" text-anchor="middle" font-family="Georgia, serif" font-size="9" font-weight="bold" fill="#FF0000">BUSINESS</text>
  <text x="350" y="31" text-anchor="middle" font-family="Georgia, serif" font-size="9" font-weight="bold" fill="#FF0000">DEVELOPMENT</text>

  <!-- Marketing - top right -->
  <circle cx="520" cy="70" r="34" fill="#0d0000" stroke="#8B0000" stroke-width="1.5"/>
  <circle cx="520" cy="70" r="34" fill="none" stroke="#FF0000" stroke-width="0.5" opacity="0.4">
    <animate attributeName="r" values="34;38;34" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0.1;0.4" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <text x="520" y="64" text-anchor="middle" font-family="Georgia, serif" font-size="9" font-weight="bold" fill="#FF0000">MARKETING</text>
  <text x="520" y="76" text-anchor="middle" font-family="Georgia, serif" font-size="9" font-weight="bold" fill="#FF0000">STRATEGY</text>

  <!-- Python - right -->
  <circle cx="620" cy="160" r="34" fill="#0d0000" stroke="#8B0000" stroke-width="1.5"/>
  <circle cx="620" cy="160" r="34" fill="none" stroke="#FF0000" stroke-width="0.5" opacity="0.4">
    <animate attributeName="r" values="34;38;34" dur="2.8s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0.1;0.4" dur="2.8s" repeatCount="indefinite"/>
  </circle>
  <text x="620" y="154" text-anchor="middle" font-family="Georgia, serif" font-size="9" font-weight="bold" fill="#FF0000">PYTHON</text>
  <text x="620" y="166" text-anchor="middle" font-family="Georgia, serif" font-size="9" font-weight="bold" fill="#cccccc">🐍</text>

  <!-- C++ - bottom right -->
  <circle cx="520" cy="250" r="34" fill="#0d0000" stroke="#8B0000" stroke-width="1.5"/>
  <circle cx="520" cy="250" r="34" fill="none" stroke="#FF0000" stroke-width="0.5" opacity="0.4">
    <animate attributeName="r" values="34;38;34" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0.1;0.4" dur="4s" repeatCount="indefinite"/>
  </circle>
  <text x="520" y="244" text-anchor="middle" font-family="Georgia, serif" font-size="12" font-weight="bold" fill="#FF0000">C++</text>
  <text x="520" y="256" text-anchor="middle" font-family="Georgia, serif" font-size="9" fill="#cccccc">Systems</text>

  <!-- Comms/Negotiation - bottom -->
  <circle cx="350" cy="295" r="34" fill="#0d0000" stroke="#8B0000" stroke-width="1.5"/>
  <circle cx="350" cy="295" r="34" fill="none" stroke="#FF0000" stroke-width="0.5" opacity="0.4">
    <animate attributeName="r" values="34;38;34" dur="3.2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0.1;0.4" dur="3.2s" repeatCount="indefinite"/>
  </circle>
  <text x="350" y="289" text-anchor="middle" font-family="Georgia, serif" font-size="9" font-weight="bold" fill="#FF0000">COMM &amp;</text>
  <text x="350" y="301" text-anchor="middle" font-family="Georgia, serif" font-size="9" font-weight="bold" fill="#FF0000">NEGOTIATION</text>

  <!-- Analytics - bottom left -->
  <circle cx="180" cy="250" r="34" fill="#0d0000" stroke="#8B0000" stroke-width="1.5"/>
  <circle cx="180" cy="250" r="34" fill="none" stroke="#FF0000" stroke-width="0.5" opacity="0.4">
    <animate attributeName="r" values="34;38;34" dur="3.7s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0.1;0.4" dur="3.7s" repeatCount="indefinite"/>
  </circle>
  <text x="180" y="244" text-anchor="middle" font-family="Georgia, serif" font-size="9" font-weight="bold" fill="#FF0000">DATA</text>
  <text x="180" y="256" text-anchor="middle" font-family="Georgia, serif" font-size="9" font-weight="bold" fill="#FF0000">ANALYTICS</text>

  <!-- Research - left -->
  <circle cx="80" cy="160" r="34" fill="#0d0000" stroke="#8B0000" stroke-width="1.5"/>
  <circle cx="80" cy="160" r="34" fill="none" stroke="#FF0000" stroke-width="0.5" opacity="0.4">
    <animate attributeName="r" values="34;38;34" dur="2.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0.1;0.4" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <text x="80" y="154" text-anchor="middle" font-family="Georgia, serif" font-size="9" font-weight="bold" fill="#FF0000">MARKET</text>
  <text x="80" y="166" text-anchor="middle" font-family="Georgia, serif" font-size="9" font-weight="bold" fill="#FF0000">RESEARCH</text>

  <!-- Innovation - top left -->
  <circle cx="180" cy="70" r="34" fill="#0d0000" stroke="#8B0000" stroke-width="1.5"/>
  <circle cx="180" cy="70" r="34" fill="none" stroke="#FF0000" stroke-width="0.5" opacity="0.4">
    <animate attributeName="r" values="34;38;34" dur="4.2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0.1;0.4" dur="4.2s" repeatCount="indefinite"/>
  </circle>
  <text x="180" y="64" text-anchor="middle" font-family="Georgia, serif" font-size="9" font-weight="bold" fill="#FF0000">PROBLEM</text>
  <text x="180" y="76" text-anchor="middle" font-family="Georgia, serif" font-size="9" font-weight="bold" fill="#FF0000">SOLVING</text>
</svg>

</div>

---

<!-- ████████████████████  TECH STACK  ████████████████████ -->

<div align="center">

<svg width="600" height="40" viewBox="0 0 600 40" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="hGrad3" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#8B0000"/>
      <stop offset="50%" stop-color="#FF0000"/>
      <stop offset="100%" stop-color="#8B0000"/>
    </linearGradient>
  </defs>
  <path d="M20,35 L60,35 M20,35 L40,10 M40,10 L60,35" fill="none" stroke="#8B0000" stroke-width="1" opacity="0.7"/>
  <circle cx="20" cy="35" r="2" fill="#8B0000"/><circle cx="40" cy="10" r="2" fill="#8B0000"/><circle cx="60" cy="35" r="2" fill="#8B0000"/>
  <path d="M580,35 L540,35 M580,35 L560,10 M560,10 L540,35" fill="none" stroke="#8B0000" stroke-width="1" opacity="0.7"/>
  <circle cx="580" cy="35" r="2" fill="#8B0000"/><circle cx="560" cy="10" r="2" fill="#8B0000"/><circle cx="540" cy="35" r="2" fill="#8B0000"/>
  <text x="300" y="28" text-anchor="middle" font-family="Georgia, serif" font-size="22" 
        font-weight="bold" letter-spacing="4" fill="url(#hGrad3)">◈  TOOLS &amp; TECH  ◈</text>
</svg>

<br/><br/>

![Python](https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=CC0000)
![C++](https://img.shields.io/badge/C++-000000?style=for-the-badge&logo=cplusplus&logoColor=CC0000)
![VS Code](https://img.shields.io/badge/VS_Code-000000?style=for-the-badge&logo=visualstudiocode&logoColor=CC0000)
![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=CC0000)
![MS Office](https://img.shields.io/badge/MS_Office-000000?style=for-the-badge&logo=microsoftoffice&logoColor=CC0000)
![Canva](https://img.shields.io/badge/Canva-000000?style=for-the-badge&logo=canva&logoColor=CC0000)
![Google Analytics](https://img.shields.io/badge/Google_Analytics-000000?style=for-the-badge&logo=googleanalytics&logoColor=CC0000)

</div>

---

<!-- ████████████████████  STATS  ████████████████████ -->

<div align="center">

<svg width="600" height="40" viewBox="0 0 600 40" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="hGrad4" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#8B0000"/>
      <stop offset="50%" stop-color="#FF0000"/>
      <stop offset="100%" stop-color="#8B0000"/>
    </linearGradient>
  </defs>
  <path d="M20,35 L60,35 M20,35 L40,10 M40,10 L60,35" fill="none" stroke="#8B0000" stroke-width="1" opacity="0.7"/>
  <circle cx="20" cy="35" r="2" fill="#8B0000"/><circle cx="40" cy="10" r="2" fill="#8B0000"/><circle cx="60" cy="35" r="2" fill="#8B0000"/>
  <path d="M580,35 L540,35 M580,35 L560,10 M560,10 L540,35" fill="none" stroke="#8B0000" stroke-width="1" opacity="0.7"/>
  <circle cx="580" cy="35" r="2" fill="#8B0000"/><circle cx="560" cy="10" r="2" fill="#8B0000"/><circle cx="540" cy="35" r="2" fill="#8B0000"/>
  <text x="300" y="28" text-anchor="middle" font-family="Georgia, serif" font-size="22" 
        font-weight="bold" letter-spacing="4" fill="url(#hGrad4)">◈  GITHUB STATS  ◈</text>
</svg>

<br/>

![Afreen's GitHub Stats](https://github-readme-stats.vercel.app/api?username=afreentahir938&show_icons=true&theme=dark&title_color=CC0000&icon_color=8B0000&text_color=ffffff&bg_color=0d0000&border_color=8B0000&hide_border=false)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=afreentahir938&layout=compact&theme=dark&title_color=CC0000&text_color=ffffff&bg_color=0d0000&border_color=8B0000)

![GitHub Streak](https://streak-stats.demolab.com?user=afreentahir938&theme=dark&background=0d0000&border=8B0000&ring=CC0000&fire=FF0000&currStreakLabel=CC0000&sideLabels=CC0000&dates=888888)

</div>

---

<!-- ████████████████████  CONTACT BOX  ████████████████████ -->

<div align="center">

<svg width="600" height="40" viewBox="0 0 600 40" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="hGrad5" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#8B0000"/>
      <stop offset="50%" stop-color="#FF0000"/>
      <stop offset="100%" stop-color="#8B0000"/>
    </linearGradient>
  </defs>
  <path d="M20,35 L60,35 M20,35 L40,10 M40,10 L60,35" fill="none" stroke="#8B0000" stroke-width="1" opacity="0.7"/>
  <circle cx="20" cy="35" r="2" fill="#8B0000"/><circle cx="40" cy="10" r="2" fill="#8B0000"/><circle cx="60" cy="35" r="2" fill="#8B0000"/>
  <path d="M580,35 L540,35 M580,35 L560,10 M560,10 L540,35" fill="none" stroke="#8B0000" stroke-width="1" opacity="0.7"/>
  <circle cx="580" cy="35" r="2" fill="#8B0000"/><circle cx="560" cy="10" r="2" fill="#8B0000"/><circle cx="540" cy="35" r="2" fill="#8B0000"/>
  <text x="300" y="28" text-anchor="middle" font-family="Georgia, serif" font-size="22" 
        font-weight="bold" letter-spacing="4" fill="url(#hGrad5)">◈  CATCH ME  ◈</text>
</svg>

</div>

<br/>

<div align="center">

<!-- Animated contact box SVG -->
<svg width="640" height="160" viewBox="0 0 640 160" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="boxGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#1a0000"/>
      <stop offset="100%" stop-color="#0d0000"/>
    </linearGradient>
    <filter id="boxGlow">
      <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- box background -->
  <rect x="10" y="10" width="620" height="140" rx="8" fill="url(#boxGrad)"/>
  
  <!-- animated border -->
  <rect x="10" y="10" width="620" height="140" rx="8" fill="none" stroke="#8B0000" stroke-width="1.5">
    <animate attributeName="stroke" values="#8B0000;#FF0000;#8B0000" dur="3s" repeatCount="indefinite"/>
  </rect>

  <!-- corner web top-left -->
  <path d="M10,10 L50,10 M10,10 L10,50 M10,10 L50,50 M30,10 L10,30 M10,10 L50,10" 
        fill="none" stroke="#8B0000" stroke-width="0.8" opacity="0.7"/>
  <!-- corner web top-right -->
  <path d="M630,10 L590,10 M630,10 L630,50 M630,10 L590,50 M610,10 L630,30" 
        fill="none" stroke="#8B0000" stroke-width="0.8" opacity="0.7"/>
  <!-- corner web bottom-left -->
  <path d="M10,150 L50,150 M10,150 L10,110 M10,150 L50,110 M30,150 L10,130" 
        fill="none" stroke="#8B0000" stroke-width="0.8" opacity="0.7"/>
  <!-- corner web bottom-right -->
  <path d="M630,150 L590,150 M630,150 L630,110 M630,150 L590,110 M610,150 L630,130" 
        fill="none" stroke="#8B0000" stroke-width="0.8" opacity="0.7"/>

  <!-- Email icon + text -->
  <!-- mail icon -->
  <rect x="40" y="38" width="26" height="18" rx="2" fill="none" stroke="#CC0000" stroke-width="1.5"/>
  <path d="M40,38 L53,50 L66,38" fill="none" stroke="#CC0000" stroke-width="1.5"/>
  <text x="78" y="52" font-family="Georgia, serif" font-size="14" fill="#ffffff">afreentahir938@gmail.com</text>

  <!-- LinkedIn icon + text -->
  <!-- linkedin icon - simplified "in" box -->
  <rect x="40" y="68" width="26" height="26" rx="4" fill="#CC0000"/>
  <text x="46" y="86" font-family="Georgia, serif" font-size="14" font-weight="bold" fill="#ffffff">in</text>
  <a href="https://www.linkedin.com/in/afreen-tahir-989483404/">
    <text x="78" y="86" font-family="Georgia, serif" font-size="14" fill="#CC0000" text-decoration="underline">linkedin.com/in/afreen-tahir-989483404</text>
  </a>

  <!-- GitHub icon + text -->
  <!-- github octocat simplified circle -->
  <circle cx="53" cy="122" r="13" fill="none" stroke="#CC0000" stroke-width="1.5"/>
  <circle cx="53" cy="120" r="7" fill="none" stroke="#CC0000" stroke-width="1.2"/>
  <path d="M46,130 Q53,136 60,130" fill="none" stroke="#CC0000" stroke-width="1.2"/>
  <text x="78" y="126" font-family="Georgia, serif" font-size="14" fill="#ffffff">github.com/afreentahir938</text>
</svg>

</div>

---

<!-- ████████████████████  FOOTER WEB  ████████████████████ -->

<div align="center">

<svg width="900" height="80" viewBox="0 0 900 80" xmlns="http://www.w3.org/2000/svg">
  <!-- bottom web -->
  <line x1="0" y1="80" x2="450" y2="0" stroke="#8B0000" stroke-width="0.6" opacity="0.4"/>
  <line x1="100" y1="80" x2="450" y2="0" stroke="#8B0000" stroke-width="0.6" opacity="0.4"/>
  <line x1="200" y1="80" x2="450" y2="0" stroke="#8B0000" stroke-width="0.6" opacity="0.4"/>
  <line x1="300" y1="80" x2="450" y2="0" stroke="#8B0000" stroke-width="0.6" opacity="0.4"/>
  <line x1="400" y1="80" x2="450" y2="0" stroke="#8B0000" stroke-width="0.6" opacity="0.4"/>
  <line x1="500" y1="80" x2="450" y2="0" stroke="#8B0000" stroke-width="0.6" opacity="0.4"/>
  <line x1="600" y1="80" x2="450" y2="0" stroke="#8B0000" stroke-width="0.6" opacity="0.4"/>
  <line x1="700" y1="80" x2="450" y2="0" stroke="#8B0000" stroke-width="0.6" opacity="0.4"/>
  <line x1="800" y1="80" x2="450" y2="0" stroke="#8B0000" stroke-width="0.6" opacity="0.4"/>
  <line x1="900" y1="80" x2="450" y2="0" stroke="#8B0000" stroke-width="0.6" opacity="0.4"/>
  <path d="M0,80 Q450,40 900,80" fill="none" stroke="#8B0000" stroke-width="0.6" opacity="0.3"/>
  <path d="M0,80 Q450,60 900,80" fill="none" stroke="#8B0000" stroke-width="0.5" opacity="0.2"/>

  <text x="450" y="48" text-anchor="middle" font-family="Georgia, serif" font-size="13" 
        letter-spacing="3" fill="#8B0000" opacity="0.8">
    ✦  Every great network starts with a single thread  ✦
  </text>
</svg>

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=afreentahir938&color=8B0000&style=for-the-badge&label=WEB+HITS)

</div>
