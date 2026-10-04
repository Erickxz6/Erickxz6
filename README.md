<!-- Degradado para el texto superior (Cara brillante) -->
<linearGradient id="text-top-grad" x1="0%" y1="0%" x2="100%" y2="0%">
  <stop offset="0%" stop-color="#00f2fe">
    <animate attributeName="stop-color" values="#00f2fe;#4facfe;#00f2fe" dur="4s" repeatCount="indefinite" />
  </stop>
  <stop offset="100%" stop-color="#4facfe">
    <animate attributeName="stop-color" values="#4facfe;#00f2fe;#4facfe" dur="4s" repeatCount="indefinite" />
  </stop>
</linearGradient>

<!-- Degradado para la extrusión 3D (Cara lateral) -->
<linearGradient id="text-side-grad" x1="0%" y1="0%" x2="0%" y2="100%">
  <stop offset="0%" stop-color="#1e3a8a" />
  <stop offset="100%" stop-color="#0f172a" />
</linearGradient>

<!-- Efecto de brillo -->
<filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
  <feGaussianBlur stdDeviation="8" result="blur" />
  <feMerge>
    <feMergeNode in="blur" />
    <feMergeNode in="SourceGraphic" />
  </feMerge>
</filter>


<!-- Cara principal brillante -->
<text x="50%" y="45%" class="title" fill="url(#text-top-grad)" filter="url(#glow)">Erickxz6</text>
