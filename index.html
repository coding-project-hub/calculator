<!doctype html>
<html ⚡ lang="hi">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,minimum-scale=1,initial-scale=1">
  <title>Calculator + AMP Ads</title>

  <script async src="https://cdn.ampproject.org/v0.js"></script>
  <script async custom-element="amp-bind" src="https://cdn.ampproject.org/v0/amp-bind-0.1.js"></script>
  <script async custom-element="amp-ad" src="https://cdn.ampproject.org/v0/amp-ad-0.1.js"></script>

  <style amp-custom>
    :root {
      --bg: #f4f6f8;
      --card: #ffffff;
      --accent: #0b72ff;
      --muted: #6b7280;
    }
    body {
      margin: 0;
      font-family: Inter, system-ui, Arial;
      background: var(--bg);
      color: #111827;
      display: flex;
      justify-content: center;
      padding: 20px;
      min-height: 100vh;
      box-sizing: border-box;
    }
    .container {
      width: 100%;
      max-width: 420px;
      display: flex;
      flex-direction: column;
      gap: 14px;
    }
    .calc-card {
      background: var(--card);
      border-radius: 12px;
      padding: 18px;
      box-shadow: 0 6px 18px rgba(15,23,42,0.06);
    }
    #screen {
      width: 100%;
      height: 56px;
      font-size: 26px;
      border-radius: 8px;
      border: 1px solid #e6e9ee;
      padding: 10px;
      text-align: right;
      box-sizing: border-box;
      margin-bottom: 14px;
      background: #fbfdff;
    }
    .keys {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 10px;
    }
    button.key {
      height: 52px;
      border-radius: 10px;
      border: 0;
      font-size: 18px;
      cursor: pointer;
      background: #f3f6fb;
      box-shadow: inset 0 -2px 0 rgba(0,0,0,0.03);
    }
    button.op {
      background: var(--accent);
      color: white;
    }
    .wide {
      grid-column: span 2;
    }
    .ad-banner {
      text-align: center;
      margin: 14px 0;
    }
    .note {
      font-size: 13px;
      color: var(--muted);
      text-align: center;
    }
    @media (max-width:420px){
      .container { padding-bottom: 90px; }
      #screen { font-size: 22px; }
      button.key { height: 48px; font-size: 16px; }
    }
  </style>
</head>
<body>

<div class="container">
  <amp-state id="calculator">
    <script type="application/json">
      {
        "expr": "",
        "screen": "0"
      }
    </script>
  </amp-state>

  <div class="calc-card">
    <input id="screen" disabled [value]="calculator.screen">

    <!-- Safe AMP calculation macro -->
    <amp-bind-macro id="calcExpr" arguments="expr" expression="
      expr == '' ? '0' :
      Math.round((expr.replace('×','*').replace('÷','/').split('').reduce((a,b)=>a+b,''))*1000000)/1000000
    "></amp-bind-macro>

    <div class="keys">
      <!-- Numbers -->
      <button class="key" on="tap:AMP.setState({calculator:{expr: calculator.expr+'7', screen: calculator.expr+'7'}})">7</button>
      <button class="key" on="tap:AMP.setState({calculator:{expr: calculator.expr+'8', screen: calculator.expr+'8'}})">8</button>
      <button class="key" on="tap:AMP.setState({calculator:{expr: calculator.expr+'9', screen: calculator.expr+'9'}})">9</button>
      <button class="key op" on="tap:AMP.setState({calculator:{expr: calculator.expr+'÷', screen: calculator.expr+'÷'}})">÷</button>

      <button class="key" on="tap:AMP.setState({calculator:{expr: calculator.expr+'4', screen: calculator.expr+'4'}})">4</button>
      <button class="key" on="tap:AMP.setState({calculator:{expr: calculator.expr+'5', screen: calculator.expr+'5'}})">5</button>
      <button class="key" on="tap:AMP.setState({calculator:{expr: calculator.expr+'6', screen: calculator.expr+'6'}})">6</button>
      <button class="key op" on="tap:AMP.setState({calculator:{expr: calculator.expr+'×', screen: calculator.expr+'×'}})">×</button>

      <button class="key" on="tap:AMP.setState({calculator:{expr: calculator.expr+'1', screen: calculator.expr+'1'}})">1</button>
      <button class="key" on="tap:AMP.setState({calculator:{expr: calculator.expr+'2', screen: calculator.expr+'2'}})">2</button>
      <button class="key" on="tap:AMP.setState({calculator:{expr: calculator.expr+'3', screen: calculator.expr+'3'}})">3</button>
      <button class="key op" on="tap:AMP.setState({calculator:{expr: calculator.expr+'-', screen: calculator.expr+'-'}})">−</button>

      <button class="key" on="tap:AMP.setState({calculator:{expr: calculator.expr+'0', screen: calculator.expr+'0'}})">0</button>
      <button class="key" on="tap:AMP.setState({calculator:{expr: calculator.expr+'.', screen: calculator.expr+'.'}})">.</button>
      <button class="key" on="tap:AMP.setState({calculator:{expr:'', screen:'0'}})">C</button>
      <button class="key op" on="tap:AMP.setState({calculator:{expr: calculator.expr+'+', screen: calculator.expr+'+'}})">+</button>

      <!-- Calculate Button -->
      <button class="key wide op" 
        on="tap:AMP.setState({calculator:{screen: eval(calculator.expr.replace('×','*').replace('÷','/')), expr: eval(calculator.expr.replace('×','*').replace('÷','/'))}})">=</button>
    </div>
  </div>

  <div class="ad-banner">
    <amp-ad width="300" height="250"
      type="adsense"
      layout="responsive"
      data-ad-client="ca-pub-1749863107862688"
      data-ad-slot="2721705134">
      <div overflow></div>
    </amp-ad>
  </div>

  <div class="note">AMP Adsense banner integrated. Replace client + slot IDs with your own.</div>
</div>

</body>
</html>
