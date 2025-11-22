<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Calculator + Ads (Demo)</title>
<style>
  :root{
    --bg:#f4f6f8;
    --card:#ffffff;
    --accent:#0b72ff;
    --muted:#6b7280;
  }
  body{
    margin:0;
    font-family:Inter, system-ui, Arial;
    background:var(--bg);
    color:#111827;
    display:flex;
    justify-content:center;
    padding:20px;
    min-height:100vh;
    box-sizing:border-box;
  }

  .container{
    width:100%;
    max-width:420px;
    display:flex;
    flex-direction:column;
    gap:14px;
  }

  /* Card for calculator */
  .calc-card{
    background:var(--card);
    border-radius:12px;
    padding:18px;
    box-shadow:0 6px 18px rgba(15,23,42,0.06);
  }

  #screen{
    width:100%;
    height:56px;
    font-size:26px;
    border-radius:8px;
    border:1px solid #e6e9ee;
    padding:10px;
    text-align:right;
    box-sizing:border-box;
    margin-bottom:14px;
    background:#fbfdff;
  }

  .keys{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:10px;
  }
  button.key{
    height:52px;
    border-radius:10px;
    border:0;
    font-size:18px;
    cursor:pointer;
    background:#f3f6fb;
    box-shadow:inset 0 -2px 0 rgba(0,0,0,0.03);
  }
  button.op{
    background:var(--accent);
    color:white;
  }
  .wide{
    grid-column:span 2;
  }

  /* Banner ad placeholder */
  .ad-banner{
    background:#fff;
    border-radius:10px;
    padding:10px;
    box-shadow:0 6px 18px rgba(15,23,42,0.04);
    text-align:center;
    min-height:90px;
    display:flex;
    align-items:center;
    justify-content:center;
  }

  .ad-banner small{ color:var(--muted); }

  /* Sticky footer ad */
  .sticky-ad{
    position:fixed;
    left:0;
    right:0;
    bottom:12px;
    display:flex;
    justify-content:center;
    pointer-events:none; /* makes clicks fall through to actual content unless ad iframe handles clicks */
  }
  .sticky-ad .ad-wrap{
    pointer-events:auto;
    width:100%;
    max-width:420px;
    background:#fff;
    border-radius:12px;
    padding:8px;
    box-shadow:0 10px 30px rgba(2,6,23,0.12);
    text-align:center;
  }

  /* small note */
  .note{
    font-size:13px;
    color:var(--muted);
    text-align:center;
  }

  @media (max-width:420px){
    .container{ padding-bottom:90px } /* leave space for sticky ad */
  }
</style>
</head>
<body>

<div class="container">

  <!-- Calculator Card (on top) -->
  <div class="calc-card" id="calcCard">
    <input id="screen" disabled value="0">
    <div class="keys" id="keys">
      <button class="key" onclick="press('7')">7</button>
      <button class="key" onclick="press('8')">8</button>
      <button class="key" onclick="press('9')">9</button>
      <button class="key op" onclick="press('/')">÷</button>

      <button class="key" onclick="press('4')">4</button>
      <button class="key" onclick="press('5')">5</button>
      <button class="key" onclick="press('6')">6</button>
      <button class="key op" onclick="press('*')">×</button>

      <button class="key" onclick="press('1')">1</button>
      <button class="key" onclick="press('2')">2</button>
      <button class="key" onclick="press('3')">3</button>
      <button class="key op" onclick="press('-')">−</button>

      <button class="key" onclick="press('0')">0</button>
      <button class="key" onclick="press('.')">.</button>
      <button class="key" onclick="clearScreen()">C</button>
      <button class="key op" onclick="press('+')">+</button>

      <button class="key wide op" onclick="calculate()">=</button>
    </div>
  </div>

  <!-- Banner Ad (allowed location) -->
  <div class="ad-banner" id="bannerAd">
    <!-- Place AdSense code or any banner ad code here -->
    <!-- EXAMPLE: paste your AdSense <ins ...> block here (replace client/slot) -->
    <div>
      <small>Ad banner placeholder — replace with AdSense / AdMob Web ad unit</small>
    </div>
  </div>

  <div class="note">Calculator upar — ads niche. AdSense use kar rahe ho to code yahin paste karein.</div>

</div>

<!-- Sticky Footer Ad (optional) -->
<div class="sticky-ad" id="stickyAd">
  <div class="ad-wrap">
    <!-- Put a small responsive ad here (AdSense responsive or partners). -->
    <small>Sticky Ad Placeholder — replace with real ad code</small>
  </div>
</div>

<script>
  let expr = "";
  const screen = document.getElementById('screen');

  function press(ch){
    if(screen.value === "0") screen.value = "";
    expr += ch;
    screen.value = expr;
  }

  function clearScreen(){
    expr = "";
    screen.value = "0";
  }

  function calculate(){
    try{
      // safe eval: allow only digits . and +-*/()
      if(!/^[0-9+\-*/().\s]+$/.test(expr)) throw 'Invalid';
      const val = Function('"use strict";return ('+expr+')')();
      screen.value = String(val);
      expr = "";
      // Optional: after calculation, you can highlight ad (policy-safe)
      const ad = document.getElementById('bannerAd');
      if(ad) {
        ad.style.boxShadow = "0 0 0 3px rgba(11,114,255,0.12)";
        setTimeout(()=>ad.style.boxShadow = "", 900);
      }
    } catch(e){
      screen.value = "Error";
      expr = "";
    }
  }
</script>

</body>
</html>
