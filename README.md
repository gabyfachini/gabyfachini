<div align="center">

<svg width="600" height="200" viewBox="0 0 600 200" xmlns="http://www.w3.org/2000/svg">

  <style>
    .star {
      animation: blink 1.5s infinite alternate;
    }

    .star2 {
      animation: blink 2s infinite alternate;
    }

    .star3 {
      animation: blink 1s infinite alternate;
    }

    @keyframes blink {
      from { opacity: 0.2; }
      to { opacity: 1; }
    }

    .text {
      font-family: monospace;
      font-size: 32px;
      fill: black;
    }

    .box {
      fill: white;
      stroke: black;
      stroke-width: 4;
    }
  </style>

  <!-- Estrelas -->
  <text x="80" y="40" class="star">+</text>
  <text x="140" y="20" class="star2">×</text>
  <text x="480" y="50" class="star3">+</text>
  <text x="520" y="90" class="star">×</text>
  <text x="100" y="150" class="star3">+</text>
  <text x="300" y="170" class="star2">×</text>
  <text x="450" y="160" class="star">+</text>

  <!-- Caixa -->
  <rect x="130" y="70" rx="8" ry="8" width="340" height="60" class="box"/>

  <!-- Texto -->
  <text x="170" y="110" class="text">HELLO WORLD</text>

</svg>

</div>
