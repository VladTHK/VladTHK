<svg width="600" height="150" viewBox="0 0 600 150" xmlns="http://www.w3.org/2000/svg" >
  <defs>
    <linearGradient id="holoGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#00f0ff" stop-opacity="0.8"/>
      <stop offset="50%" stop-color="#ff00f7" stop-opacity="0.6"/>
      <stop offset="100%" stop-color="#00ffaa" stop-opacity="0.8"/>
    </linearGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feDropShadow dx="0" dy="0" stdDeviation="3" flood-color="#00f0ff" flood-opacity="0.8"/>
      <feDropShadow dx="0" dy="0" stdDeviation="5" flood-color="#ff00f7" flood-opacity="0.6"/>
      <feDropShadow dx="0" dy="0" stdDeviation="8" flood-color="#00ffaa" flood-opacity="0.8"/>
    </filter>
  </defs>

  <rect width="600" height="150" fill="url(#holoGradient)" fill-opacity="0.3" rx="20" ry="20" />
  
  <text x="50%" y="45%" text-anchor="middle" fill="url(#holoGradient)" font-family="Segoe UI, Tahoma, Geneva, Verdana, sans-serif" font-weight="900" font-size="48" filter="url(#glow)" >
    ThinkerTHK
  </text>
  
  <text x="50%" y="80%" text-anchor="middle" fill="white" fill-opacity="0.7" font-family="Courier New, monospace" font-weight="600" font-size="24">
    Rust &nbsp; • &nbsp; Java &nbsp; • &nbsp; Python
  </text>
</svg>
