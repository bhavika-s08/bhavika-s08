<svg width="1000" height="240" viewBox="0 0 1000 240" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="sky" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0b1026"/>
      <stop offset="60%" stop-color="#1b1f4b"/>
      <stop offset="100%" stop-color="#3b2a6b"/>
    </linearGradient>
    <radialGradient id="glow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#fff6d6" stop-opacity="0.55"/>
      <stop offset="100%" stop-color="#fff6d6" stop-opacity="0"/>
    </radialGradient>
    <mask id="crescent">
      <rect width="1000" height="240" fill="black"/>
      <circle cx="830" cy="120" r="60" fill="white"/>
      <circle cx="858" cy="105" r="54" fill="black"/>
    </mask>
    <style>
      .star { fill: #ffffff; animation: twinkle 3s ease-in-out infinite; }
      .s2 { animation-delay: 0.8s; }
      .s3 { animation-delay: 1.6s; }
      .s4 { animation-delay: 2.2s; }
      @keyframes twinkle { 0%,100% { opacity: 0.2; } 50% { opacity: 1; } }
    </style>
  </defs>

  <rect width="1000" height="240" fill="url(#sky)"/>

  <circle cx="830" cy="120" r="130" fill="url(#glow)"/>
  <circle cx="830" cy="120" r="60" fill="#fff3c4" mask="url(#crescent)"/>

  <circle class="star" cx="120" cy="50" r="2"/>
  <circle class="star s2" cx="260" cy="190" r="1.5"/>
  <circle class="star s3" cx="400" cy="40" r="2"/>
  <circle class="star s4" cx="560" cy="200" r="1.5"/>
  <circle class="star" cx="640" cy="70" r="2"/>
  <circle class="star s2" cx="720" cy="190" r="1.5"/>
  <circle class="star s3" cx="940" cy="40" r="2"/>
  <circle class="star s4" cx="60" cy="150" r="1.5"/>
  <circle class="star" cx="330" cy="120" r="1.5"/>
  <circle class="star s2" cx="950" cy="200" r="2"/>

  <text x="70" y="115" font-family="Segoe UI, Helvetica, Arial, sans-serif" font-size="46" font-weight="700" fill="#ffffff">Bhavika Suryawanshi</text>
  <text x="72" y="155" font-family="Segoe UI, Helvetica, Arial, sans-serif" font-size="20" fill="#c9c6f5">CS @ UVA  |  software + medtech</text>
</svg>
