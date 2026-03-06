[connery-electrical (3).html](https://github.com/user-attachments/files/25782097/connery-electrical.3.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0"/>
<meta name="description" content="Connery Electrical – Sydney Northern Beaches trusted electrician for residential, commercial & EV charger installations."/>
<title>Connery Electrical</title>
<link href="https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@700;900&family=Barlow:wght@400;500;600&display=swap" rel="stylesheet"/>
<style>
*{margin:0;padding:0;box-sizing:border-box;-webkit-tap-highlight-color:transparent;}
:root{--o:#E8960A;--o2:#F5A623;--dk:#0E0E0E;--dk2:#161616;--dk3:#1E1E1E;--dk4:#272727;--wh:#FFFFFF;}
html{scroll-behavior:smooth;}
body{font-family:'Barlow',sans-serif;background:var(--dk);color:var(--wh);overflow-x:hidden;-webkit-font-smoothing:antialiased;}
a{text-decoration:none;color:inherit;}

/* ── MAX WIDTH WRAPPER ── */
.page-wrap{width:100%;max-width:480px;margin:0 auto;}

/* ── NAV ── */
nav{
  position:fixed;top:0;left:0;right:0;z-index:200;
  background:rgba(8,8,8,0.97);
  border-bottom:2px solid var(--o);
  display:flex;align-items:center;justify-content:space-between;
  padding:0 16px;height:60px;
}
.nav-inner{
  width:100%;max-width:480px;margin:0 auto;
  display:flex;align-items:center;justify-content:space-between;
}
.nav-logo img{height:34px;width:auto;display:block;}
.nav-call{
  display:flex;align-items:center;gap:6px;
  background:var(--o);color:#000;font-weight:700;font-size:13px;
  padding:9px 16px;border-radius:4px;letter-spacing:.5px;white-space:nowrap;
  flex-shrink:0;
}
.nav-call svg{width:13px;height:13px;flex-shrink:0;}

/* ── HERO ── */
#hero{
  min-height:100svh;
  display:flex;flex-direction:column;justify-content:center;
  padding:80px 20px 50px;
  position:relative;overflow:hidden;
  background:linear-gradient(155deg,#0a0a0a 0%,#131108 100%);
}
#hero::before{
  content:'';position:absolute;top:-10%;right:-20%;
  width:70vw;height:70vw;max-width:380px;max-height:380px;
  background:radial-gradient(circle,rgba(232,150,10,.12) 0%,transparent 65%);
  pointer-events:none;border-radius:50%;
}
.hero-deco{
  position:absolute;right:-60px;bottom:-40px;
  opacity:.04;pointer-events:none;width:260px;
}
.hero-inner{max-width:480px;margin:0 auto;position:relative;z-index:1;width:100%;}
.hero-badge{
  display:inline-flex;align-items:center;gap:6px;
  background:rgba(232,150,10,.12);border:1px solid rgba(232,150,10,.35);
  color:var(--o2);padding:5px 13px;border-radius:20px;
  font-size:10px;font-weight:700;letter-spacing:2px;
  text-transform:uppercase;margin-bottom:18px;width:fit-content;
  animation:fadeUp .5s ease both;
}
h1{
  font-family:'Barlow Condensed',sans-serif;
  font-size:clamp(50px,13vw,80px);
  font-weight:900;line-height:.88;
  text-transform:uppercase;letter-spacing:-1px;
  margin-bottom:16px;
  animation:fadeUp .55s .08s ease both;
}
h1 .o{color:var(--o2);}
.hero-sub{
  font-size:15px;line-height:1.75;color:#888;
  max-width:400px;margin-bottom:26px;
  animation:fadeUp .55s .16s ease both;
}
.hero-btns{
  display:flex;flex-direction:column;gap:10px;
  animation:fadeUp .55s .22s ease both;
}
@media(min-width:420px){.hero-btns{flex-direction:row;}}
.btn-main{
  background:var(--o);color:#000;font-weight:700;
  padding:14px 22px;border-radius:4px;font-size:14px;
  text-transform:uppercase;letter-spacing:1px;
  border:none;cursor:pointer;font-family:'Barlow',sans-serif;
  text-align:center;display:flex;align-items:center;justify-content:center;gap:8px;
  transition:opacity .2s;
}
.btn-main:active{opacity:.8;}
.btn-sec{
  background:transparent;color:var(--wh);font-weight:600;
  padding:13px 22px;border-radius:4px;font-size:14px;
  text-transform:uppercase;letter-spacing:1px;
  border:1.5px solid rgba(255,255,255,.18);
  cursor:pointer;font-family:'Barlow',sans-serif;text-align:center;
}
.hero-stats{
  display:flex;margin-top:28px;
  border-top:1px solid rgba(255,255,255,.08);padding-top:22px;
  animation:fadeUp .55s .3s ease both;
}
.stat{flex:1;text-align:center;padding:0 4px;}
.stat:not(:last-child){border-right:1px solid rgba(255,255,255,.08);}
.stat-n{font-family:'Barlow Condensed',sans-serif;font-size:28px;font-weight:900;color:var(--o2);line-height:1;}
.stat-l{font-size:10px;color:#555;text-transform:uppercase;letter-spacing:.7px;margin-top:4px;line-height:1.3;}

/* ── SECTIONS ── */
.sec{padding:56px 20px;}
.stag{display:inline-flex;align-items:center;gap:8px;color:var(--o2);font-size:10px;font-weight:700;text-transform:uppercase;letter-spacing:2.5px;margin-bottom:8px;}
.stag::before{content:'';display:block;width:20px;height:2px;background:var(--o2);}
.stitle{font-family:'Barlow Condensed',sans-serif;font-size:clamp(28px,8vw,42px);font-weight:900;text-transform:uppercase;line-height:.92;margin-bottom:10px;}
.ssub{color:#666;font-size:14px;line-height:1.7;}

/* ── SERVICES ── */
#services{background:var(--dk2);}
.svc-tabs{display:flex;gap:2px;margin:20px 0 0;background:var(--dk3);border-radius:4px;padding:3px;}
.svc-tab{flex:1;padding:9px 4px;text-align:center;font-size:11px;font-weight:700;text-transform:uppercase;letter-spacing:.5px;border-radius:3px;cursor:pointer;transition:background .2s,color .2s;color:#555;}
.svc-tab.active{background:var(--o);color:#000;}
.svc-panel{display:none;margin-top:12px;}
.svc-panel.active{display:block;}
.svc-list{list-style:none;}
.svc-list li{
  display:flex;align-items:center;gap:12px;
  padding:13px 14px;background:var(--dk3);margin-bottom:2px;
  border-radius:3px;font-size:14px;color:#ccc;
  border-left:3px solid transparent;
}
.svc-list li:active{border-left-color:var(--o);}
.svc-list li::before{content:'⚡';color:var(--o2);font-size:10px;flex-shrink:0;}

/* ── ABOUT ── */
#about{background:var(--dk);}
.about-logo{display:flex;justify-content:center;margin:26px 0 20px;}
.about-logo img{width:140px;height:auto;display:block;}
.about-body p{color:#777;font-size:14px;line-height:1.85;margin-bottom:12px;}
.checks{list-style:none;margin-top:16px;}
.checks li{
  display:flex;align-items:center;gap:11px;
  padding:12px 14px;background:var(--dk3);border-radius:3px;
  font-size:14px;color:#ccc;margin-bottom:2px;
}
.checks li::before{content:'✓';color:var(--o2);font-weight:700;font-size:13px;flex-shrink:0;}

/* ── EV ── */
#ev{background:var(--o);padding:50px 20px;}
#ev .stag{color:#000;}#ev .stag::before{background:#000;}
#ev .stitle{color:#000;}
#ev .ssub{color:rgba(0,0,0,.6);}
.ev-cards{display:flex;flex-direction:column;gap:2px;margin-top:20px;}
.ev-card{background:rgba(0,0,0,.1);padding:20px 18px;border-radius:3px;}
.ev-card-t{font-family:'Barlow Condensed',sans-serif;font-size:19px;font-weight:900;text-transform:uppercase;color:#000;margin-bottom:6px;}
.ev-card-d{font-size:13px;color:rgba(0,0,0,.65);line-height:1.65;}

/* ── CONTACT ── */
#contact{background:var(--dk2);}
.cinfo{display:flex;flex-direction:column;gap:2px;margin-bottom:22px;}
.citem{display:flex;align-items:center;gap:14px;background:var(--dk3);padding:13px 14px;border-radius:3px;}
.cicon{width:38px;height:38px;background:rgba(232,150,10,.1);border:1px solid rgba(232,150,10,.2);border-radius:3px;display:flex;align-items:center;justify-content:center;font-size:15px;flex-shrink:0;}
.clabel{font-size:10px;color:#555;text-transform:uppercase;letter-spacing:1px;}
.cval{font-size:14px;color:#ddd;margin-top:1px;}
.social-row{display:flex;gap:8px;margin-bottom:20px;}
.social-btn{flex:1;display:flex;align-items:center;justify-content:center;gap:7px;background:var(--dk3);border:1px solid #333;padding:13px 8px;border-radius:3px;font-size:12px;font-weight:700;color:#bbb;letter-spacing:.5px;text-transform:uppercase;}
.social-btn:active{border-color:var(--o);color:var(--o);}
.cform{display:flex;flex-direction:column;gap:10px;}
.cform input,.cform textarea,.cform select{
  background:var(--dk3);border:1px solid #2e2e2e;color:#fff;
  padding:14px;border-radius:3px;font-size:15px;
  font-family:'Barlow',sans-serif;width:100%;
  -webkit-appearance:none;appearance:none;
}
.cform input:focus,.cform textarea:focus,.cform select:focus{outline:none;border-color:var(--o);}
.cform textarea{min-height:100px;resize:vertical;}
.cform select option{background:#222;}

/* ── FOOTER ── */
footer{
  background:#080808;border-top:2px solid var(--o);
  padding:24px 20px;
}
.footer-inner{
  max-width:480px;margin:0 auto;
  display:flex;flex-direction:column;align-items:center;gap:14px;text-align:center;
}
.footer-logo img{height:30px;width:auto;display:block;}
footer p{font-size:11px;color:#3a3a3a;line-height:1.6;}
.foot-links{display:flex;gap:20px;}
.foot-links a{font-size:12px;color:#444;}

/* ── SHARE SHEET ── */
#share-overlay{display:none;position:fixed;inset:0;z-index:500;background:rgba(0,0,0,.75);backdrop-filter:blur(4px);align-items:flex-end;justify-content:center;}
#share-overlay.open{display:flex;}
#share-sheet{background:var(--dk2);border-radius:16px 16px 0 0;padding:24px 20px 36px;width:100%;max-width:480px;border-top:2px solid var(--o);animation:slideUp .25s ease;}
#share-sheet h3{font-family:'Barlow Condensed',sans-serif;font-size:22px;font-weight:900;text-transform:uppercase;margin-bottom:4px;}
#share-sheet p{font-size:13px;color:#666;margin-bottom:18px;}
.share-url-row{display:flex;gap:8px;margin-bottom:18px;}
.share-url-row input{flex:1;background:var(--dk3);border:1px solid #333;color:#aaa;padding:12px;border-radius:4px;font-size:13px;font-family:'Barlow',sans-serif;}
.share-url-row button{background:var(--o);color:#000;font-weight:700;padding:12px 18px;border:none;border-radius:4px;cursor:pointer;font-size:13px;white-space:nowrap;}
.share-options{display:flex;gap:10px;}
.share-opt{flex:1;display:flex;flex-direction:column;align-items:center;gap:7px;background:var(--dk3);border:1px solid #2a2a2a;padding:16px 8px;border-radius:6px;cursor:pointer;font-size:11px;color:#999;font-weight:600;letter-spacing:.5px;text-transform:uppercase;}
.share-opt:active{border-color:var(--o);color:var(--o);}
.share-opt svg{width:24px;height:24px;}
#share-close{display:block;width:100%;margin-top:14px;background:none;border:1px solid #333;color:#666;padding:13px;border-radius:4px;font-size:14px;cursor:pointer;font-family:'Barlow',sans-serif;}

/* ── EDIT PANEL ── */
#edit-panel{display:none;position:fixed;bottom:0;left:0;right:0;z-index:300;background:var(--dk2);border-top:2px solid var(--o);padding:18px 20px 36px;border-radius:16px 16px 0 0;}
#edit-panel h4{font-family:'Barlow Condensed',sans-serif;font-size:18px;color:var(--o2);margin-bottom:10px;}
#edit-panel label{font-size:10px;text-transform:uppercase;letter-spacing:1px;color:#555;display:block;margin-bottom:5px;}
#edit-panel input,#edit-panel textarea{width:100%;background:var(--dk3);border:1px solid #333;color:#fff;padding:11px 12px;border-radius:4px;font-size:15px;font-family:'Barlow',sans-serif;-webkit-appearance:none;}
#edit-panel textarea{resize:vertical;min-height:80px;}
.ep-btns{display:flex;gap:8px;margin-top:12px;}
.ep-btns button{flex:1;padding:13px;border:none;border-radius:4px;cursor:pointer;font-weight:700;font-size:14px;font-family:'Barlow',sans-serif;}
#ep-apply{background:var(--o);color:#000;}
#ep-cancel{background:#2a2a2a;color:#aaa;}
#ep-close-x{position:absolute;top:14px;right:18px;background:none;border:none;color:#555;font-size:22px;cursor:pointer;}

/* ── FAB ── */
#fab{position:fixed;bottom:22px;right:16px;z-index:150;display:flex;flex-direction:column;align-items:flex-end;gap:10px;}
.fab-btn{display:flex;align-items:center;gap:7px;color:#000;font-weight:700;font-size:12px;padding:10px 15px;border-radius:30px;border:none;cursor:pointer;letter-spacing:.5px;text-transform:uppercase;font-family:'Barlow',sans-serif;background:var(--o);box-shadow:0 4px 18px rgba(232,150,10,.35);}
.fab-btn.secondary{background:var(--dk3);color:#ccc;box-shadow:0 4px 14px rgba(0,0,0,.4);border:1px solid #333;}
.fab-btn svg{width:14px;height:14px;flex-shrink:0;}

/* ── EDITABLE ── */
[data-editable]{cursor:pointer;}
[data-editable].editing{outline:2px dashed var(--o);outline-offset:2px;border-radius:2px;}

/* ── ANIMATIONS ── */
@keyframes fadeUp{from{opacity:0;transform:translateY(14px);}to{opacity:1;transform:none;}}
@keyframes slideUp{from{transform:translateY(100%);}to{transform:none;}}
.reveal{opacity:0;transform:translateY(18px);transition:opacity .5s ease,transform .5s ease;}
.reveal.shown{opacity:1;transform:none;}

/* ── DESKTOP ── */
@media(min-width:600px){
  .ev-cards{flex-direction:row;}
  .ev-card{flex:1;}
  #share-sheet{border-radius:16px;margin:20px;max-width:440px;}
  #edit-panel{left:50%;transform:translateX(-50%);bottom:20px;width:460px;border-radius:12px;}
}
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <div class="nav-inner">
    <div class="nav-logo">
      <img src="data:image/png;base64,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" alt="Connery Electrical"/>
    </div>
    <a href="tel:0421755198" class="nav-call">
      <svg viewBox="0 0 24 24" fill="currentColor"><path d="M6.6 10.8c1.4 2.8 3.8 5.1 6.6 6.6l2.2-2.2c.3-.3.7-.4 1-.2 1.1.4 2.3.6 3.6.6.6 0 1 .4 1 1V20c0 .6-.4 1-1 1-9.4 0-17-7.6-17-17 0-.6.4-1 1-1h3.5c.6 0 1 .4 1 1 0 1.3.2 2.5.6 3.6.1.3 0 .7-.2 1L6.6 10.8z"/></svg>
      Call Now
    </a>
  </div>
</nav>

<!-- HERO -->
<section id="hero">
  <div class="hero-deco">
    <img src="data:image/png;base64,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x+pVXRAF6E6Pap6eW7s52Wy3DLrZT3CKxGCSnfJs9r+Bw4SNuq89kQHfsF3uNhvlHerVUvpq6jmbNBKzq1wO4V/7frNpFqro4LZnd9ttsqLjS91X0c7iHQzDlxs5HoRxNPu9V54ogN1ssFsxTWm1xi9Ulda7de6d4uERPdPhbM13eeY9nmVa3tkaradZdopUWbG8tt1zuBrqeRsEJcXcLSdzzAVHUQGZwrJrzh2UUOR2CrdS3CikD43jofNrh4tI3BHkVe7TXtTabZlY2UGb91Y657A2oiqo+8ppDtzLXbHlv4EcvNefCID0op887OGLPddqC5YpS1Hzg+mhDpCevLYciqydrXtA2zU+lgxrHLSG2mln775dVRjv5XDl7A+g3n7zsq5IgL06Das6Q6W6FUVrjyekqb0ykfW1dOyN/FNVOaXd3vw7bjkwH0CpRkF7uV8vldeLhVSyVVdUPqJnF55ue4uP2lY1EBtek+ZVuDai2TKqeSQ/IKpr5WB37pEfZkb8WlwVpe1vqZpHqZpU+mtWRxTX23ztqqBvcuBcfmvj326Fp+toVL0QFt+xTq/genmnd4tWV3j5DVT3Z1REzunO4mGKNu/L1afqUz1HaH0BmnfPNXUksrzu57rdu5x8ySOa84UQHobe+0JoJLaayCCamMslO9jOG2D5xaQPBeebzxOLtttzuvxEAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREB//2Q==" alt="" aria-hidden="true"/>
  </div>
  <div class="hero-inner">
    <div class="hero-badge">⚡ Licensed &amp; Insured</div>
    <h1><span class="o">Powering</span><br>Your Home<br>&amp; Business</h1>
    <p class="hero-sub" data-editable data-field="text" id="hero-sub">Sydney Northern Beaches trusted electrician for residential &amp; commercial service, maintenance, and EV charger installations.</p>
    <div class="hero-btns">
      <a href="#contact" class="btn-main">
        <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>
        Free Quote
      </a>
      <a href="#services" class="btn-sec">Our Services</a>
    </div>
    <div class="hero-stats">
      <div class="stat">
        <div class="stat-n" data-editable data-field="text" id="sn1">Local</div>
        <div class="stat-l" data-editable data-field="text" id="sl1">Northern<br>Beaches</div>
      </div>
      <div class="stat">
        <div class="stat-n" data-editable data-field="text" id="sn2">24/7</div>
        <div class="stat-l" data-editable data-field="text" id="sl2">Emergency<br>Service</div>
      </div>
      <div class="stat">
        <div class="stat-n" data-editable data-field="text" id="sn3">100%</div>
        <div class="stat-l" data-editable data-field="text" id="sl3">Licensed<br>&amp; Insured</div>
      </div>
    </div>
  </div>
</section>

<!-- SERVICES -->
<section id="services" class="sec">
  <div class="page-wrap reveal">
    <div class="stag">What We Do</div>
    <h2 class="stitle">Our Services</h2>
    <p class="ssub">Residential, commercial &amp; EV — across the Northern Beaches.</p>
    <div class="svc-tabs">
      <div class="svc-tab active" data-tab="res">Residential</div>
      <div class="svc-tab" data-tab="com">Commercial</div>
      <div class="svc-tab" data-tab="ev">EV Chargers</div>
    </div>
    <div class="svc-panel active" id="tab-res">
      <ul class="svc-list">
        <li data-editable data-field="text">LED Installations &amp; Upgrades</li>
        <li data-editable data-field="text">Fan Installs</li>
        <li data-editable data-field="text">Fault Finding</li>
        <li data-editable data-field="text">Power Installs</li>
        <li data-editable data-field="text">Appliance Installs</li>
        <li data-editable data-field="text">Safety Checks</li>
        <li data-editable data-field="text">Switchboard Upgrades</li>
      </ul>
    </div>
    <div class="svc-panel" id="tab-com">
      <ul class="svc-list">
        <li data-editable data-field="text">LED Installations &amp; Upgrades</li>
        <li data-editable data-field="text">Fan Installs</li>
        <li data-editable data-field="text">Fault Finding</li>
        <li data-editable data-field="text">Power Installs</li>
        <li data-editable data-field="text">Appliance Installs</li>
        <li data-editable data-field="text">Safety Checks</li>
        <li data-editable data-field="text">Switchboard Upgrades</li>
        <li data-editable data-field="text">General Electrical Works</li>
        <li data-editable data-field="text">Mechanical Electrical Work</li>
      </ul>
    </div>
    <div class="svc-panel" id="tab-ev">
      <ul class="svc-list">
        <li data-editable data-field="text">Home EV Charger Installation</li>
        <li data-editable data-field="text">Commercial Charging Stations</li>
        <li data-editable data-field="text">Level 1 &amp; Level 2 Charging</li>
        <li data-editable data-field="text">Switchboard Upgrades for EV</li>
        <li data-editable data-field="text">Safety Inspections</li>
        <li data-editable data-field="text">All Major Brands Supported</li>
      </ul>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section id="about" class="sec">
  <div class="page-wrap reveal">
    <div class="stag">Who We Are</div>
    <div class="about-logo">
      <img src="data:image/png;base64,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x+pVXRAF6E6Pap6eW7s52Wy3DLrZT3CKxGCSnfJs9r+Bw4SNuq89kQHfsF3uNhvlHerVUvpq6jmbNBKzq1wO4V/7frNpFqro4LZnd9ttsqLjS91X0c7iHQzDlxs5HoRxNPu9V54ogN1ssFsxTWm1xi9Ulda7de6d4uERPdPhbM13eeY9nmVa3tkaradZdopUWbG8tt1zuBrqeRsEJcXcLSdzzAVHUQGZwrJrzh2UUOR2CrdS3CikD43jofNrh4tI3BHkVe7TXtTabZlY2UGb91Y657A2oiqo+8ppDtzLXbHlv4EcvNefCID0op887OGLPddqC5YpS1Hzg+mhDpCevLYciqydrXtA2zU+lgxrHLSG2mln775dVRjv5XDl7A+g3n7zsq5IgL06Das6Q6W6FUVrjyekqb0ykfW1dOyN/FNVOaXd3vw7bjkwH0CpRkF7uV8vldeLhVSyVVdUPqJnF55ue4uP2lY1EBtek+ZVuDai2TKqeSQ/IKpr5WB37pEfZkb8WlwVpe1vqZpHqZpU+mtWRxTX23ztqqBvcuBcfmvj326Fp+toVL0QFt+xTq/genmnd4tWV3j5DVT3Z1REzunO4mGKNu/L1afqUz1HaH0BmnfPNXUksrzu57rdu5x8ySOa84UQHobe+0JoJLaayCCamMslO9jOG2D5xaQPBeebzxOLtttzuvxEAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREAREQBERAEREB//2Q==" alt="Connery Electrical"/>
    </div>
    <h2 class="stitle" data-editable data-field="text" id="about-title">About Connery Electrical</h2>
    <div class="about-body">
      <p data-editable data-field="text" id="ab-p1">Connery Electrical is a Sydney Northern Beaches electrical service and maintenance business operating across residential and commercial properties.</p>
      <p data-editable data-field="text" id="ab-p2">From LED upgrades and fan installs to full switchboard replacements and commercial mechanical electrical work — we bring skill, speed, and honesty to every job.</p>
    </div>
    <ul class="checks">
      <li data-editable data-field="text">Fully Licensed &amp; Insured Electrician</li>
      <li data-editable data-field="text">Residential &amp; Commercial Specialist</li>
      <li data-editable data-field="text">Fast Response &amp; Reliable Service</li>
      <li data-editable data-field="text">Upfront, Transparent Pricing</li>
      <li data-editable data-field="text">Sydney Northern Beaches &amp; Surrounds</li>
    </ul>
  </div>
</section>

<!-- EV -->
<section id="ev" class="reveal">
  <div class="page-wrap">
    <div class="stag">Going Electric</div>
    <h2 class="stitle" data-editable data-field="text">EV Charger Installation</h2>
    <p class="ssub" data-editable data-field="text">Professional EV charger installs for Northern Beaches homes and businesses.</p>
    <div class="ev-cards">
      <div class="ev-card">
        <div class="ev-card-t" data-editable data-field="text">Home Charging</div>
        <div class="ev-card-d" data-editable data-field="text">Overnight charging from your garage. We assess your switchboard, run the wiring, and install the right charger for your vehicle and home.</div>
      </div>
      <div class="ev-card">
        <div class="ev-card-t" data-editable data-field="text">Commercial Charging</div>
        <div class="ev-card-d" data-editable data-field="text">Dedicated EV bays for staff, fleet, or customers. We handle everything from design to commissioning.</div>
      </div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact" class="sec">
  <div class="page-wrap reveal">
    <div class="stag">Get In Touch</div>
    <h2 class="stitle">Request a Quote</h2>
    <div class="cinfo">
      <a href="tel:0421755198" class="citem" style="text-decoration:none;">
        <div class="cicon">📞</div>
        <div>
          <div class="clabel">Mobile</div>
          <div class="cval" data-editable data-field="text" id="ct-phone">0421 755 198</div>
        </div>
      </a>
      <a href="mailto:oscar@conneryelectrical.com.au" class="citem" style="text-decoration:none;">
        <div class="cicon">✉️</div>
        <div>
          <div class="clabel">Email</div>
          <div class="cval" data-editable data-field="text" id="ct-email">oscar@conneryelectrical.com.au</div>
        </div>
      </a>
      <div class="citem">
        <div class="cicon">📍</div>
        <div>
          <div class="clabel">Service Area</div>
          <div class="cval" data-editable data-field="text" id="ct-area">Sydney Northern Beaches &amp; Surrounds</div>
        </div>
      </div>
    </div>
    <div class="social-row">
      <a href="https://www.instagram.com/connery.electrical/" target="_blank" class="social-btn">
        <svg viewBox="0 0 24 24" width="16" height="16" fill="currentColor"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zM12 0C8.741 0 8.333.014 7.053.072 2.695.272.273 2.69.073 7.052.014 8.333 0 8.741 0 12c0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98C8.333 23.986 8.741 24 12 24c3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98C15.668.014 15.259 0 12 0zm0 5.838a6.162 6.162 0 100 12.324 6.162 6.162 0 000-12.324zM12 16a4 4 0 110-8 4 4 0 010 8zm6.406-11.845a1.44 1.44 0 100 2.881 1.44 1.44 0 000-2.881z"/></svg>
        Instagram
      </a>
      <a href="https://www.facebook.com/61580903685433/" target="_blank" class="social-btn">
        <svg viewBox="0 0 24 24" width="16" height="16" fill="currentColor"><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/></svg>
        Facebook
      </a>
    </div>
    <div class="cform">
      <input type="text" placeholder="Your Name"/>
      <input type="email" placeholder="Email Address"/>
      <input type="tel" placeholder="Phone Number"/>
      <select>
        <option value="">Select Service Type</option>
        <option>Residential</option>
        <option>Commercial</option>
        <option>EV Charger</option>
        <option>Emergency</option>
        <option>Other</option>
      </select>
      <textarea placeholder="Tell us about your job…"></textarea>
      <button class="btn-main" style="justify-content:center;width:100%;">Send Message</button>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-inner">
    <div class="footer-logo">
      <img src="data:image/png;base64,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" alt="Connery Electrical"/>
    </div>
    <p data-editable data-field="text" id="foot-txt">© 2025 Connery Electrical. All rights reserved.<br>Licensed Electrical Contractor — Sydney Northern Beaches, NSW.</p>
    <div class="foot-links">
      <a href="https://www.instagram.com/connery.electrical/" target="_blank">Instagram</a>
      <a href="https://www.facebook.com/61580903685433/" target="_blank">Facebook</a>
      <a href="tel:0421755198">0421 755 198</a>
    </div>
  </div>
</footer>

<!-- FABs -->
<div id="fab">
  <button class="fab-btn secondary" id="fab-edit" onclick="toggleEditMode()">
    <svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 17.25V21h3.75L17.81 9.94l-3.75-3.75L3 17.25zM20.71 7.04c.39-.39.39-1.02 0-1.41l-2.34-2.34c-.39-.39-1.02-.39-1.41 0l-1.83 1.83 3.75 3.75 1.83-1.83z"/></svg>
    Edit
  </button>
  <button class="fab-btn" onclick="openShare()">
    <svg viewBox="0 0 24 24" fill="currentColor"><path d="M18 16.08c-.76 0-1.44.3-1.96.77L8.91 12.7c.05-.23.09-.46.09-.7s-.04-.47-.09-.7l7.05-4.11c.54.5 1.25.81 2.04.81 1.66 0 3-1.34 3-3s-1.34-3-3-3-3 1.34-3 3c0 .24.04.47.09.7L8.04 9.81C7.5 9.31 6.79 9 6 9c-1.66 0-3 1.34-3 3s1.34 3 3 3c.79 0 1.5-.31 2.04-.81l7.12 4.16c-.05.21-.08.43-.08.65 0 1.61 1.31 2.92 2.92 2.92s2.92-1.31 2.92-2.92-1.31-2.92-2.92-2.92z"/></svg>
    Share
  </button>
</div>

<!-- SHARE OVERLAY -->
<div id="share-overlay" onclick="closeShare(event)">
  <div id="share-sheet">
    <h3>Share This Page</h3>
    <p>Send to your mate or anyone needing an electrician.</p>
    <div class="share-url-row">
      <input type="text" id="share-url-input" readonly value=""/>
      <button onclick="copyLink()">Copy</button>
    </div>
    <div class="share-options">
      <div class="share-opt" onclick="shareVia('sms')">
        <svg viewBox="0 0 24 24" fill="currentColor"><path d="M20 2H4c-1.1 0-2 .9-2 2v18l4-4h14c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2zm0 14H5.17L4 17.17V4h16v12z"/></svg>SMS
      </div>
      <div class="share-opt" onclick="shareVia('whatsapp')">
        <svg viewBox="0 0 24 24" fill="currentColor"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>WhatsApp
      </div>
      <div class="share-opt" onclick="shareVia('email')">
        <svg viewBox="0 0 24 24" fill="currentColor"><path d="M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>Email
      </div>
      <div class="share-opt" onclick="shareVia('native')">
        <svg viewBox="0 0 24 24" fill="currentColor"><path d="M18 16.08c-.76 0-1.44.3-1.96.77L8.91 12.7c.05-.23.09-.46.09-.7s-.04-.47-.09-.7l7.05-4.11c.54.5 1.25.81 2.04.81 1.66 0 3-1.34 3-3s-1.34-3-3-3-3 1.34-3 3c0 .24.04.47.09.7L8.04 9.81C7.5 9.31 6.79 9 6 9c-1.66 0-3 1.34-3 3s1.34 3 3 3c.79 0 1.5-.31 2.04-.81l7.12 4.16c-.05.21-.08.43-.08.65 0 1.61 1.31 2.92 2.92 2.92s2.92-1.31 2.92-2.92-1.31-2.92-2.92-2.92z"/></svg>More
      </div>
    </div>
    <button id="share-close" onclick="closeShare()">Cancel</button>
  </div>
</div>

<!-- EDIT PANEL -->
<div id="edit-panel">
  <button id="ep-close-x" onclick="closeEdit()">✕</button>
  <h4>✏ Edit Content</h4>
  <div id="ep-fields"></div>
  <div class="ep-btns">
    <button id="ep-apply">Apply</button>
    <button id="ep-cancel" onclick="closeEdit()">Cancel</button>
  </div>
</div>

<script>
// TABS
document.querySelectorAll('.svc-tab').forEach(tab=>{
  tab.addEventListener('click',()=>{
    document.querySelectorAll('.svc-tab').forEach(t=>t.classList.remove('active'));
    document.querySelectorAll('.svc-panel').forEach(p=>p.classList.remove('active'));
    tab.classList.add('active');
    document.getElementById('tab-'+tab.dataset.tab).classList.add('active');
  });
});

// SCROLL REVEAL
const obs=new IntersectionObserver(entries=>{
  entries.forEach(e=>{if(e.isIntersecting)e.target.classList.add('shown');});
},{threshold:.1});
document.querySelectorAll('.reveal').forEach(el=>obs.observe(el));

// SHARE
function openShare(){
  document.getElementById('share-url-input').value=window.location.href;
  document.getElementById('share-overlay').classList.add('open');
}
function closeShare(e){
  if(!e||e.target===document.getElementById('share-overlay')){
    document.getElementById('share-overlay').classList.remove('open');
  }
}
function copyLink(){
  const inp=document.getElementById('share-url-input');
  navigator.clipboard.writeText(inp.value).catch(()=>{inp.select();document.execCommand('copy');});
  const btn=inp.nextElementSibling;
  btn.textContent='Copied!';setTimeout(()=>{btn.textContent='Copy';},2000);
}
function shareVia(method){
  const url=encodeURIComponent(window.location.href);
  const msg=encodeURIComponent('Check out Connery Electrical — Northern Beaches electrician: ');
  if(method==='sms')window.open('sms:?body='+msg+decodeURIComponent(url));
  else if(method==='whatsapp')window.open('https://wa.me/?text='+msg+url);
  else if(method==='email')window.open('mailto:?subject=Connery Electrical&body='+msg+decodeURIComponent(url));
  else if(method==='native'&&navigator.share)navigator.share({title:'Connery Electrical',text:'Sydney Northern Beaches electrician.',url:window.location.href});
  else copyLink();
}

// EDIT MODE
let editMode=false,curEl=null;
function toggleEditMode(){
  editMode=!editMode;
  const btn=document.getElementById('fab-edit');
  if(editMode){
    btn.style.background='#E8960A';btn.style.color='#000';
    btn.innerHTML='<svg viewBox="0 0 24 24" fill="currentColor" width="14" height="14"><path d="M3 17.25V21h3.75L17.81 9.94l-3.75-3.75L3 17.25zM20.71 7.04c.39-.39.39-1.02 0-1.41l-2.34-2.34c-.39-.39-1.02-.39-1.41 0l-1.83 1.83 3.75 3.75 1.83-1.83z"/></svg> Editing';
  } else {
    btn.style.background='';btn.style.color='';
    btn.innerHTML='<svg viewBox="0 0 24 24" fill="currentColor" width="14" height="14"><path d="M3 17.25V21h3.75L17.81 9.94l-3.75-3.75L3 17.25zM20.71 7.04c.39-.39.39-1.02 0-1.41l-2.34-2.34c-.39-.39-1.02-.39-1.41 0l-1.83 1.83 3.75 3.75 1.83-1.83z"/></svg> Edit';
    closeEdit();
  }
}
document.querySelectorAll('[data-editable]').forEach(el=>{
  el.addEventListener('click',e=>{
    if(!editMode)return;
    e.stopPropagation();
    if(curEl)curEl.classList.remove('editing');
    curEl=el;el.classList.add('editing');
    const ep=document.getElementById('ep-fields');ep.innerHTML='';
    const lbl=document.createElement('label');lbl.textContent='Content';ep.appendChild(lbl);
    const isTA=el.tagName==='P'||el.classList.contains('ev-card-d')||el.classList.contains('ssub')||el.id==='hero-sub';
    const inp=isTA?document.createElement('textarea'):document.createElement('input');
    inp.id='epval';inp.value=el.innerText;ep.appendChild(inp);
    document.getElementById('edit-panel').style.display='block';
    setTimeout(()=>inp.focus(),100);
  });
});
document.getElementById('ep-apply').addEventListener('click',()=>{
  if(!curEl)return;
  curEl.innerText=document.getElementById('epval').value;
  closeEdit();
});
function closeEdit(){
  document.getElementById('edit-panel').style.display='none';
  if(curEl){curEl.classList.remove('editing');curEl=null;}
}
document.addEventListener('click',e=>{
  if(!e.target.closest('[data-editable]')&&!e.target.closest('#edit-panel'))closeEdit();
});
</script>
</body>
</html>
