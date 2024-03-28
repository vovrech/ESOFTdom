# ESOFTdom
Создать веб-страницу с визуализацией дома
<!DOCTYPE html>
<html>
  <head>
    <title>НЕ УМЕЮ РИСОВАТЬ ДОМА НО ОЧЕНЬ ХОЧУ НАУЧИТЬСЯ</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
      <h1 class="title">DOMIK </h1>
      <p id="currentTime"></p>
      <script src="script.js"></script>
  </body>
</html>
<svg width="230" height="140">
  <polygon points="5,135 115,5 225,135"
    fill="violet" stroke="purple" stroke-width="5"
  />
</svg>
<svg width="400" height="180">
   <rect x="50" y="20" rx="20" ry="20" width="150" height="150"
   style="fill:red;stroke:black;stroke-width:5;opacity:0.5" />
</svg>
<svg height="30" width="200">
   <text x="0" y="15" fill="red">не умею рисовать дома</text>
</svg>
<svg width="250" height="210" style="border: 1px solid">
  <g fill="#333">
    <ellipse rx="45" ry="37" cx="55" cy="60" transform="rotate(-45, 55, 55)"/>
    <ellipse rx="45" ry="37" cx="190" cy="60" transform="rotate(45, 190, 55)"/>
    <circle r="67" cx="122" cy="125"/>
  </g>
</svg>
<svg viewBox="0 0 600 200">
  <linearGradient id="grad--linear-1">
    <stop offset="0%" stop-color="crimson" 
          class="stop-1"/>   
    <stop offset="50%" stop-color="gold"
          class="stop-2"/>
    <stop offset="100%" stop-color="teal" 
          class="stop-3"/>
  </linearGradient>
    
  <rect fill="url(#grad--linear-1)"
        width="100%" height="100%"/>
</svg>
<svg height="60" width="200">
   <text x="0" y="15" fill="red" transform="rotate(30 20,40)">хочу научиться</text>
</svg> 
