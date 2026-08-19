<div align="center">

# Hi 👋, I'm Sai Harshitha Kollipara

### 💻 B.Tech Student | 🤖 AI & Data Science | 🚀 Building Things With Code

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=6C63FF&center=true&vCenter=true&width=600&lines=AI+%26+Data+Science+Student;Exploring+LLMs+%26+Cloud;Learning+DSA+Every+Day;Building+AI+%26+Full-Stack+Projects;Turning+Ideas+Into+Code+%F0%9F%9A%80" alt="Typing SVG">

</div>

---

## 🐾 Meet Mochi — My Virtual Puppy

<div align="center">

### 🐶 Mochi says Hi! 👋
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mochi — Your Virtual Puppy</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Baloo+2:wght@500;700;800&family=Nunito:wght@500;700;800&display=swap" rel="stylesheet">
<style>
:root{
  --deep-blue:#1b1464;
  --purple:#6c3ce9;
  --cyan:#33d6d6;
  --pink:#ff8fc7;
  --hot-pink:#ff5fa2;
  --yellow:#ffd23f;
  --panel:#ffffffcc;
  --ink:#241b4e;
  --sky-day-1:#8fd8ff;
  --sky-day-2:#c9f0ff;
  --sky-eve-1:#ff9a76;
  --sky-eve-2:#ffd97a;
  --sky-night-1:#0b0a2e;
  --sky-night-2:#2a1e6b;
}
*{box-sizing:border-box;}
html,body{margin:0;padding:0;height:100%;font-family:'Nunito',sans-serif;overflow:hidden;background:#0b0a2e;}
#app{position:relative;width:100vw;height:100vh;min-height:520px;overflow:hidden;user-select:none;}

/* ===== SKY ===== */
#sky{position:absolute;inset:0;transition:background 3s ease;z-index:0;}
.sky-day{background:linear-gradient(180deg,var(--sky-day-1) 0%,var(--sky-day-2) 55%,#ffe9b3 100%);}
.sky-evening{background:linear-gradient(180deg,#5b3a8e 0%,var(--sky-eve-1) 55%,var(--sky-eve-2) 100%);}
.sky-night{background:linear-gradient(180deg,var(--sky-night-1) 0%,var(--sky-night-2) 65%,#3a2b7a 100%);}

.celestial{position:absolute;border-radius:50%;transition:opacity 2s ease, top 2s ease, left 2s ease;}
#sun{width:70px;height:70px;background:radial-gradient(circle,#fff6c8,#ffd23f 70%);box-shadow:0 0 60px 18px #ffd23f88;}
#moon{width:54px;height:54px;background:radial-gradient(circle at 35% 35%,#fffef2,#e7e6ff 75%);box-shadow:0 0 40px 12px #ffffff55;}

.star{position:absolute;width:3px;height:3px;background:#fff;border-radius:50%;animation:twinkle 3s ease-in-out infinite;}
@keyframes twinkle{0%,100%{opacity:.2;}50%{opacity:1;}}

.cloud{position:absolute;opacity:.9;filter:drop-shadow(0 4px 6px rgba(0,0,0,.06));}
.cloud div{position:absolute;background:#fff;border-radius:50%;}

.firefly{position:absolute;width:5px;height:5px;border-radius:50%;background:#ffe98a;box-shadow:0 0 8px 3px #ffe98a;animation:flyabout 9s ease-in-out infinite;}
@keyframes flyabout{
  0%{transform:translate(0,0);opacity:.2;}
  20%{opacity:1;}
  50%{transform:translate(30px,-24px);}
  80%{opacity:.5;}
  100%{transform:translate(-10px,10px);opacity:.2;}
}

.bird{position:absolute;font-size:16px;animation:birdfly 14s linear infinite;opacity:.85;}
@keyframes birdfly{ from{ left:-5%; } to{ left:105%; } }

/* ===== GROUND / WORLD ===== */
#world{position:absolute;inset:0;z-index:1;}

#room{position:absolute;left:0;top:0;width:38%;height:100%;background:linear-gradient(180deg, rgba(255,255,255,0.12) 0%, rgba(255,255,255,0.05) 100%);border-right:4px dashed rgba(255,255,255,0.25);}
#window{position:absolute;left:8%;top:10%;width:130px;height:150px;border-radius:18px;background:linear-gradient(180deg,#bfe9ff,#eaf8ff);border:10px solid #fff3;box-shadow:0 10px 30px rgba(0,0,0,.15) inset, 0 8px 24px rgba(0,0,0,.2);overflow:hidden;}
#window .pane{position:absolute;inset:0;}
#window .cross-v{position:absolute;left:50%;top:0;bottom:0;width:6px;background:#fff6;transform:translateX(-50%);}
#window .cross-h{position:absolute;top:50%;left:0;right:0;height:6px;background:#fff6;transform:translateY(-50%);}

#den{position:absolute;left:6%;bottom:8%;width:150px;height:110px;z-index:5;}
#den .roof{position:absolute;top:-26px;left:-6px;width:162px;height:0;border-left:81px solid transparent;border-right:81px solid transparent;border-bottom:46px solid var(--hot-pink);filter:drop-shadow(0 4px 4px rgba(0,0,0,.15));}
#den .hut{position:absolute;top:14px;width:100%;height:96px;background:linear-gradient(180deg,#ffd6ea,#ffc2e0);border-radius:16px 16px 10px 10px;box-shadow:0 8px 18px rgba(0,0,0,.15);}
#den .door{position:absolute;left:50%;bottom:0;width:64px;height:70px;transform:translateX(-50%);background:radial-gradient(ellipse at top, #4a3070 60%, #2c1c4d 100%);border-radius:32px 32px 6px 6px;}
#den .bed{position:absolute;left:50%;bottom:6px;width:78px;height:26px;transform:translateX(-50%);background:#8f6fe8;border-radius:16px;box-shadow:inset 0 3px 6px rgba(0,0,0,.2);}
#den .heart{position:absolute;top:24px;left:50%;transform:translateX(-50%);font-size:14px;}
#den.cozy .hut{filter:brightness(.55) saturate(1.2);}
#den.cozy::after{content:'';position:absolute;inset:-20px;border-radius:24px;box-shadow:0 0 40px 16px rgba(120,90,255,.35);pointer-events:none;}

#foodBowl,#waterBowl{position:absolute;bottom:9%;width:60px;height:34px;z-index:4;}
#foodBowl{left:34%;}
#waterBowl{left:44%;}
.bowl-body{width:100%;height:22px;margin-top:12px;border-radius:0 0 30px 30px;background:linear-gradient(180deg,#ff8fc7,#ff5fa2);box-shadow:0 6px 10px rgba(0,0,0,.2);}
.bowl-rim{width:106%;margin-left:-3%;height:10px;border-radius:50%;background:#ffd23f;box-shadow:0 2px 4px rgba(0,0,0,.15);}
.bowl-content{position:absolute;top:14px;left:14%;width:72%;height:10px;border-radius:50%;background:#c9a06a;opacity:0;transition:opacity .4s;}
#waterBowl .bowl-content{background:#66d9ff;}
.bowl-content.show{opacity:1;}

#garden{position:absolute;right:0;top:0;width:62%;height:100%;}
.tree{position:absolute;bottom:6%;font-size:70px;filter:drop-shadow(0 6px 4px rgba(0,0,0,.15));}
.flower{position:absolute;bottom:6%;font-size:22px;animation:sway 4s ease-in-out infinite;}
@keyframes sway{0%,100%{transform:rotate(-6deg);}50%{transform:rotate(6deg);}}
.grasstuft{position:absolute;bottom:5%;font-size:20px;}

#ground{position:absolute;left:0;right:0;bottom:0;height:14%;background:linear-gradient(180deg,#7fd68a,#4fae62);z-index:2;}
#roomFloor{position:absolute;left:0;width:38%;bottom:0;height:14%;background:linear-gradient(180deg,#caa6f0,#a884d9);z-index:2;}

.ball{position:absolute;bottom:16%;width:26px;height:26px;border-radius:50%;background:radial-gradient(circle at 35% 30%,#ffe37a,#ffb100);box-shadow:0 4px 6px rgba(0,0,0,.25);z-index:6;display:none;}

/* ===== SPEECH / PARTICLES ===== */
.bubble{position:absolute;bottom:100%;left:50%;transform:translate(-50%,10px);background:#fff;color:var(--ink);padding:6px 12px;border-radius:14px;font-weight:800;font-size:13px;white-space:nowrap;box-shadow:0 4px 10px rgba(0,0,0,.2);opacity:0;transition:all .3s;pointer-events:none;}
.bubble::after{content:'';position:absolute;top:100%;left:50%;transform:translateX(-50%);border:6px solid transparent;border-top-color:#fff;}
.bubble.show{opacity:1;transform:translate(-50%,-4px);}

.particle{position:absolute;pointer-events:none;font-size:16px;animation:floatUp 1.4s ease-out forwards;z-index:20;}
@keyframes floatUp{0%{opacity:1;transform:translate(0,0) scale(.7);}100%{opacity:0;transform:translate(var(--dx,10px),-60px) scale(1.2);}}

/* ===== MOCHI ===== */
#mochi-wrap{position:absolute;bottom:11%;left:400px;width:170px;height:150px;z-index:10;transform-origin:bottom center;transition:left .05s linear;cursor:pointer;}
#mochi-shadow{position:absolute;bottom:-4px;left:50%;transform:translateX(-50%);width:110px;height:18px;background:radial-gradient(ellipse,rgba(0,0,0,.28),transparent 70%);border-radius:50%;}
#mochi-flip{width:100%;height:100%;transition:transform .35s ease;}
#mochi-body-group{width:100%;height:100%;}

.breathe{animation:breathe 3.2s ease-in-out infinite;}
@keyframes breathe{0%,100%{transform:scaleY(1);}50%{transform:scaleY(1.02);}}

.legfl,.legfr,.legbl,.legbr{transform-origin:top center;}
.walking .legfl{animation:legfwd .55s ease-in-out infinite;}
.walking .legbr{animation:legfwd .55s ease-in-out infinite;}
.walking .legfr{animation:legback .55s ease-in-out infinite;}
.walking .legbl{animation:legback .55s ease-in-out infinite;}
.running .legfl,.running .legbr{animation:legfwd .3s ease-in-out infinite;}
.running .legfr,.running .legbl{animation:legback .3s ease-in-out infinite;}
@keyframes legfwd{0%,100%{transform:rotate(0deg);}50%{transform:rotate(24deg);}}
@keyframes legback{0%,100%{transform:rotate(0deg);}50%{transform:rotate(-24deg);}}

.tailgroup{transform-origin:80% 60%;}
.wag-slow .tailgroup{animation:wag 1.1s ease-in-out infinite;}
.wag-fast .tailgroup{animation:wag .35s ease-in-out infinite;}
.wag-happy .tailgroup{animation:wag .22s ease-in-out infinite;}
@keyframes wag{0%,100%{transform:rotate(-14deg);}50%{transform:rotate(20deg);}}

.eargroup{transform-origin:top center;transition:transform .3s ease;}
.ear-perk{transform:rotate(-14deg) scale(1.05);}
.ear-droop{transform:rotate(20deg);}

#headgroup{transform-origin:50% 90%;transition:transform .12s ease-out;}

.eyelidL,.eyelidR{transition:transform .12s;}
.blink .eyelidL,.blink .eyelidR{transform:scaleY(1);}
.eyes-closed .eyelidL,.eyes-closed .eyelidR{transform:scaleY(1) !important;}

.pupilL,.pupilR{transition:transform .1s linear;}

.mouth-path{transition:d .2s;}

.jump{animation:jumpUp .55s ease-in-out;}
@keyframes jumpUp{0%,100%{transform:translateY(0);}40%{transform:translateY(-26px);}}

.spin-sit{transition:transform .3s;}

.zzz{position:absolute;top:-10px;right:0;font-weight:800;color:#fff;font-size:18px;opacity:0;pointer-events:none;text-shadow:0 2px 4px rgba(0,0,0,.3);}
.zzz.show{animation:zzzfloat 2.4s ease-in-out infinite;}
@keyframes zzzfloat{0%{opacity:0;transform:translate(0,0) scale(.6);}20%{opacity:1;}100%{opacity:0;transform:translate(24px,-48px) scale(1.3);}}

/* ===== UI ===== */
#topbar{position:absolute;top:14px;left:50%;transform:translateX(-50%);z-index:40;display:flex;gap:10px;align-items:center;background:var(--panel);backdrop-filter:blur(6px);padding:10px 18px;border-radius:22px;box-shadow:0 8px 24px rgba(20,10,60,.25);}
#topbar .name{font-family:'Baloo 2',sans-serif;font-weight:800;color:var(--ink);font-size:18px;display:flex;align-items:center;gap:6px;margin-right:6px;}
.stat{display:flex;align-items:center;gap:6px;font-weight:800;color:var(--ink);font-size:13px;}
.stat .bar{width:70px;height:10px;border-radius:6px;background:#eee2ff;overflow:hidden;box-shadow:inset 0 1px 3px rgba(0,0,0,.15);}
.stat .fill{height:100%;border-radius:6px;transition:width .5s ease;}
.fill.happy{background:linear-gradient(90deg,#ff8fc7,#ff5fa2);}
.fill.hunger{background:linear-gradient(90deg,#ffd23f,#ff9d3f);}
.fill.energy{background:linear-gradient(90deg,#33d6d6,#3fa0ff);}

#muteBtn{margin-left:4px;background:none;border:none;font-size:18px;cursor:pointer;}

#bottombar{position:absolute;bottom:16px;left:50%;transform:translateX(-50%);z-index:40;display:flex;gap:12px;flex-wrap:wrap;justify-content:center;max-width:96vw;}
.actionBtn{font-family:'Baloo 2',sans-serif;font-weight:700;font-size:14px;color:#fff;border:none;padding:12px 20px;border-radius:20px;cursor:pointer;box-shadow:0 6px 0 rgba(0,0,0,.18), 0 10px 18px rgba(0,0,0,.2);transition:transform .12s, box-shadow .12s;display:flex;align-items:center;gap:6px;}
.actionBtn:active{transform:translateY(4px);box-shadow:0 2px 0 rgba(0,0,0,.18), 0 4px 10px rgba(0,0,0,.2);}
.actionBtn.eat{background:linear-gradient(180deg,#ffd23f,#ff9d3f);}
.actionBtn.sleep{background:linear-gradient(180deg,#8f6fe8,#6c3ce9);}
.actionBtn.play{background:linear-gradient(180deg,#33d6d6,#1fb3c9);}
.actionBtn.pet{background:linear-gradient(180deg,#ff8fc7,#ff5fa2);}
.actionBtn.drink{background:linear-gradient(180deg,#6bc8ff,#3fa0ff);}

#cmdWrap{position:absolute;bottom:76px;left:50%;transform:translateX(-50%);z-index:40;display:flex;gap:8px;}
#cmdInput{font-family:'Nunito',sans-serif;font-weight:700;padding:10px 14px;border-radius:16px;border:none;width:220px;box-shadow:0 4px 12px rgba(0,0,0,.2);outline:none;color:var(--ink);}
#cmdSend{font-family:'Baloo 2',sans-serif;font-weight:700;border:none;background:var(--deep-blue);color:#fff;border-radius:16px;padding:0 16px;cursor:pointer;}

#hint{position:absolute;top:14px;right:14px;z-index:40;background:var(--panel);padding:8px 12px;border-radius:14px;font-size:12px;color:var(--ink);font-weight:700;max-width:180px;box-shadow:0 6px 14px rgba(0,0,0,.2);}

@media (max-width:640px){
  #topbar{flex-wrap:wrap;padding:8px 12px;gap:6px;}
  .stat .bar{width:44px;}
  .actionBtn{padding:10px 14px;font-size:12px;}
  #cmdInput{width:150px;}
  #hint{display:none;}
  #mochi-wrap{width:120px;height:110px;}
}
</style>
</head>
<body>
<div id="app">
  <div id="sky" class="sky-day">
    <div id="sun" class="celestial"></div>
    <div id="moon" class="celestial" style="opacity:0;"></div>
    <div id="starsLayer"></div>
    <div id="cloudsLayer"></div>
    <div id="firefliesLayer"></div>
    <div class="bird" style="top:12%;">🐦</div>
    <div class="bird" style="top:18%;animation-delay:-6s;">🐦</div>
  </div>

  <div id="world">
    <div id="room">
      <div id="window">
        <div class="pane"></div>
        <div class="cross-v"></div>
        <div class="cross-h"></div>
      </div>
    </div>
    <div id="garden">
      <div class="tree" style="right:6%;">🌳</div>
      <div class="tree" style="right:20%;font-size:52px;bottom:5%;">🌳</div>
      <div class="flower" style="right:12%;">🌸</div>
      <div class="flower" style="right:30%;animation-delay:-1s;">🌷</div>
      <div class="flower" style="right:45%;animation-delay:-2s;">🌼</div>
      <div class="flower" style="right:8%;bottom:9%;animation-delay:-1.5s;">🌺</div>
      <div class="grasstuft" style="right:38%;">🌿</div>
      <div class="grasstuft" style="right:16%;">🌿</div>
      <div class="grasstuft" style="right:50%;">🌿</div>
    </div>

    <div id="roomFloor"></div>
    <div id="ground"></div>

    <div id="den">
      <div class="roof"></div>
      <div class="hut">
        <div class="door"></div>
      </div>
      <div class="bed"></div>
      <div class="heart">💗</div>
    </div>

    <div id="foodBowl">
      <div class="bowl-content" id="foodContent">🍗</div>
      <div class="bowl-rim"></div>
      <div class="bowl-body"></div>
    </div>
    <div id="waterBowl">
      <div class="bowl-content"></div>
      <div class="bowl-rim"></div>
      <div class="bowl-body"></div>
    </div>

    <div class="ball" id="ball"></div>

    <!-- MOCHI -->
    <div id="mochi-wrap">
      <div class="bubble" id="bubble"></div>
      <div class="zzz" id="zzz">💤</div>
      <div id="mochi-shadow"></div>
      <div id="mochi-flip">
        <svg id="mochiSvg" viewBox="0 0 220 200" width="100%" height="100%" xmlns="http://www.w3.org/2000/svg">
          <g id="mochi-body-group">
            <!-- back legs -->
            <g class="legbl" transform="translate(70,150)"><ellipse cx="0" cy="18" rx="12" ry="20" fill="#f4f0ff"/></g>
            <g class="legbr" transform="translate(150,150)"><ellipse cx="0" cy="18" rx="12" ry="20" fill="#eee7ff"/></g>

            <!-- tail -->
            <g class="tailgroup" transform="translate(178,120)">
              <path d="M0,0 C 26,-10 30,-40 12,-52 C 22,-38 14,-14 -6,-4 Z" fill="#ffffff" stroke="#e9e2ff" stroke-width="2"/>
            </g>

            <!-- body -->
            <g id="bodyPuff">
              <ellipse cx="110" cy="128" rx="72" ry="52" fill="#ffffff"/>
              <circle cx="55" cy="110" r="26" fill="#ffffff"/>
              <circle cx="165" cy="112" r="24" fill="#ffffff"/>
              <circle cx="90" cy="82" r="22" fill="#ffffff"/>
              <circle cx="135" cy="80" r="22" fill="#ffffff"/>
              <circle cx="60" cy="160" r="20" fill="#ffffff"/>
              <circle cx="160" cy="162" r="20" fill="#ffffff"/>
              <ellipse cx="110" cy="150" rx="60" ry="30" fill="#fbf7ff"/>
            </g>

            <!-- front legs -->
            <g class="legfl" transform="translate(82,156)"><ellipse cx="0" cy="18" rx="13" ry="22" fill="#ffffff"/><ellipse cx="0" cy="36" rx="13" ry="7" fill="#fff"/></g>
            <g class="legfr" transform="translate(140,156)"><ellipse cx="0" cy="18" rx="13" ry="22" fill="#f7f3ff"/><ellipse cx="0" cy="36" rx="13" ry="7" fill="#fff"/></g>

            <!-- head -->
            <g id="headgroup" transform="translate(110,78)">
              <g class="eargroup" id="earL" transform="translate(-48,-30)">
                <path d="M0,0 C-22,4 -30,34 -10,52 C-16,26 -6,8 6,-2 Z" fill="#ffe3f1"/>
              </g>
              <g class="eargroup" id="earR" transform="translate(48,-30)">
                <path d="M0,0 C22,4 30,34 10,52 C16,26 6,8 -6,-2 Z" fill="#ffe3f1"/>
              </g>

              <circle cx="0" cy="0" r="56" fill="#ffffff"/>
              <circle cx="-44" cy="6" r="20" fill="#ffffff"/>
              <circle cx="44" cy="6" r="20" fill="#ffffff"/>
              <circle cx="-30" cy="-36" r="18" fill="#ffffff"/>
              <circle cx="30" cy="-36" r="18" fill="#ffffff"/>
              <circle cx="0" cy="-46" r="18" fill="#ffffff"/>
              <circle cx="0" cy="40" r="26" fill="#ffffff"/>

              <!-- bow -->
              <g transform="translate(0,-52)">
                <path d="M0,0 L-22,-14 L-22,14 Z" fill="#ff5fa2"/>
                <path d="M0,0 L22,-14 L22,14 Z" fill="#ff8fc7"/>
                <circle cx="0" cy="0" r="7" fill="#ff2d84"/>
              </g>

              <!-- blush -->
              <ellipse cx="-32" cy="18" rx="10" ry="6" fill="#ffc2da" opacity=".8"/>
              <ellipse cx="32" cy="18" rx="10" ry="6" fill="#ffc2da" opacity=".8"/>

              <!-- eyes -->
              <g id="eyeGroupL" transform="translate(-20,-2)">
                <ellipse cx="0" cy="0" rx="13" ry="15" fill="#3a2a55"/>
                <circle class="pupilL" cx="-3" cy="-3" r="4" fill="#fff"/>
                <ellipse class="eyelidL" cx="0" cy="-15" rx="15" ry="15" fill="#ffffff" transform="scaleY(0)"/>
              </g>
              <g id="eyeGroupR" transform="translate(20,-2)">
                <ellipse cx="0" cy="0" rx="13" ry="15" fill="#3a2a55"/>
                <circle class="pupilR" cx="3" cy="-3" r="4" fill="#fff"/>
                <ellipse class="eyelidR" cx="0" cy="-15" rx="15" ry="15" fill="#ffffff" transform="scaleY(0)"/>
              </g>

              <!-- brows -->
              <path id="browL" d="M-32,-24 Q-20,-30 -10,-24" stroke="#3a2a55" stroke-width="3" fill="none" stroke-linecap="round" opacity=".0"/>
              <path id="browR" d="M10,-24 Q20,-30 32,-24" stroke="#3a2a55" stroke-width="3" fill="none" stroke-linecap="round" opacity=".0"/>

              <!-- nose + mouth -->
              <ellipse cx="0" cy="26" rx="7" ry="5" fill="#3a2a55"/>
              <path class="mouth-path" id="mouth" d="M0,31 Q0,40 -10,38" stroke="#3a2a55" stroke-width="3" fill="none" stroke-linecap="round"/>
              <path class="mouth-path" id="mouth2" d="M0,31 Q0,40 10,38" stroke="#3a2a55" stroke-width="3" fill="none" stroke-linecap="round"/>
            </g>
          </g>
        </svg>
      </div>
    </div>
  </div>

  <div id="topbar">
    <div class="name">🐾 Mochi</div>
    <div class="stat">❤️<div class="bar"><div class="fill happy" id="happyFill" style="width:87%;"></div></div></div>
    <div class="stat">🍖<div class="bar"><div class="fill hunger" id="hungerFill" style="width:70%;"></div></div></div>
    <div class="stat">⚡<div class="bar"><div class="fill energy" id="energyFill" style="width:80%;"></div></div></div>
    <button id="muteBtn" title="Mute sound">🔊</button>
  </div>

  <div id="hint">Move your mouse — Mochi will notice you 👀. Try typing a command below!</div>

  <div id="cmdWrap">
    <input id="cmdInput" type="text" placeholder="Type: sleep, play, come here..." />
    <button id="cmdSend">Say</button>
  </div>

  <div id="bottombar">
    <button class="actionBtn eat" id="btnEat">🍖 Eat</button>
    <button class="actionBtn sleep" id="btnSleep">💤 Sleep</button>
    <button class="actionBtn play" id="btnPlay">🎾 Play</button>
    <button class="actionBtn pet" id="btnPet">❤️ Pet</button>
    <button class="actionBtn drink" id="btnDrink">💧 Drink</button>
  </div>
</div>

<script>
(function(){
"use strict";

/* ============ SETUP ============ */
const app=document.getElementById('app');
const world=document.getElementById('world');
const wrap=document.getElementById('mochi-wrap');
const flip=document.getElementById('mochi-flip');
const headgroup=document.getElementById('headgroup');
const bodyGroup=document.getElementById('mochi-body-group');
const svgRoot=document.getElementById('mochiSvg');
const pupilL=document.querySelector('.pupilL');
const pupilR=document.querySelector('.pupilR');
const eyelidL=document.querySelector('.eyelidL');
const eyelidR=document.querySelector('.eyelidR');
const earL=document.getElementById('earL');
const earR=document.getElementById('earR');
const browL=document.getElementById('browL');
const browR=document.getElementById('browR');
const mouth=document.getElementById('mouth');
const mouth2=document.getElementById('mouth2');
const bubble=document.getElementById('bubble');
const zzzEl=document.getElementById('zzz');
const denEl=document.getElementById('den');
const ball=document.getElementById('ball');
const foodContent=document.getElementById('foodContent');
const happyFill=document.getElementById('happyFill');
const hungerFill=document.getElementById('hungerFill');
const energyFill=document.getElementById('energyFill');

/* ============ STATE ============ */
let stats={happiness:87,hunger:70,energy:80};
let lastInteraction=Date.now();
let muted=false;

let mochi={
  x:400,           // px position within world
  facing:1,        // 1 right, -1 left
  state:'idle',
  busy:false,      // true while running a scripted sequence (eat/sleep/play)
  followMode:false,
  targetX:null,
  speed:2.2,
  sitting:false
};

const WORLD_MIN_X=60;
function worldMaxX(){ return world.clientWidth-60; }

const DEN_X=140;
const FOOD_X=world? 0:0; // set after layout
let FOOD_X_PX=0, WATER_X_PX=0, YARD_X_PX=0, BALL_SPOT_X=0;

function layoutSpots(){
  const w=world.clientWidth;
  FOOD_X_PX = w*0.36;
  WATER_X_PX = w*0.46;
  YARD_X_PX = w*0.58;
  BALL_SPOT_X = w*0.8;
}
window.addEventListener('resize',layoutSpots);

/* ============ TIME OF DAY (accelerated) ============ */
// full day/night cycle every 6 minutes real time, for a lively but not-annoying pace
const CYCLE_MS=6*60*1000;
let cycleStart=Date.now();
let timeOfDay='day'; // day, evening, night

function updateSky(){
  const t=((Date.now()-cycleStart)%CYCLE_MS)/CYCLE_MS; // 0..1
  const sky=document.getElementById('sky');
  const sun=document.getElementById('sun');
  const moon=document.getElementById('moon');
  let phase;
  if(t<0.45){phase='day';}
  else if(t<0.6){phase='evening';}
  else {phase='night';}
  if(phase!==timeOfDay){
    timeOfDay=phase;
    onTimeChange(phase);
  }
  sky.className=phase==='day'?'sky-day':phase==='evening'?'sky-evening':'sky-night';

  // sun/moon arc
  const dayT=Math.min(t/0.45,1);
  const nightT=t>0.6? (t-0.6)/0.4 : 0;
  if(phase==='day'||phase==='evening'){
    sun.style.opacity= phase==='day'?1:0.6;
    moon.style.opacity=0;
    const arc=phase==='day'?dayT:1;
    sun.style.left=(10+arc*70)+'%';
    sun.style.top=(60-Math.sin(arc*Math.PI)*45)+'%';
  } else {
    sun.style.opacity=0;
    moon.style.opacity=1;
    moon.style.left=(10+nightT*70)+'%';
    moon.style.top=(60-Math.sin(nightT*Math.PI)*45)+'%';
  }
}

function onTimeChange(phase){
  if(phase==='night'){
    spawnFireflies();
    document.querySelectorAll('.bird').forEach(b=>b.style.display='none');
  } else if(phase==='day'){
    document.getElementById('firefliesLayer').innerHTML='';
    document.querySelectorAll('.bird').forEach(b=>b.style.display='');
  }
}

function spawnStars(){
  const layer=document.getElementById('starsLayer');
  let html='';
  for(let i=0;i<60;i++){
    html+=`<div class="star" style="left:${Math.random()*100}%;top:${Math.random()*55}%;animation-delay:${Math.random()*3}s;"></div>`;
  }
  layer.innerHTML=html;
}
spawnStars();

function spawnFireflies(){
  const layer=document.getElementById('firefliesLayer');
  let html='';
  for(let i=0;i<14;i++){
    html+=`<div class="firefly" style="left:${20+Math.random()*60}%;top:${55+Math.random()*35}%;animation-delay:${Math.random()*4}s;"></div>`;
  }
  layer.innerHTML=html;
}

function spawnClouds(){
  const layer=document.getElementById('cloudsLayer');
  const positions=[[8,10,70],[30,6,50],[62,14,80],[80,8,55]];
  let html='';
  positions.forEach(([left,top,size],i)=>{
    html+=`<div class="cloud" style="left:${left}%;top:${top}%;width:${size}px;height:${size*0.5}px;animation:driftCloud ${40+i*8}s linear infinite;">
      <div style="width:60%;height:100%;border-radius:50%;left:0;top:20%;"></div>
      <div style="width:70%;height:120%;border-radius:50%;left:25%;top:0;"></div>
      <div style="width:50%;height:90%;border-radius:50%;left:55%;top:15%;"></div>
    </div>`;
  });
  layer.innerHTML=html;
  if(!document.getElementById('cloudKeyframe')){
    const style=document.createElement('style');
    style.id='cloudKeyframe';
    style.textContent=`@keyframes driftCloud{from{transform:translateX(-40px);}to{transform:translateX(40px);}}`;
    document.head.appendChild(style);
  }
}
spawnClouds();

/* ============ SOUND (WebAudio, synthesized, no external files) ============ */
let actx=null;
function getCtx(){ if(!actx){ try{ actx=new (window.AudioContext||window.webkitAudioContext)(); }catch(e){} } return actx; }
function beep(freq,dur,type,vol,glideTo){
  if(muted) return;
  const ctx=getCtx(); if(!ctx) return;
  const t0=ctx.currentTime;
  const osc=ctx.createOscillator();
  const gain=ctx.createGain();
  osc.type=type||'sine';
  osc.frequency.setValueAtTime(freq,t0);
  if(glideTo) osc.frequency.exponentialRampToValueAtTime(glideTo,t0+dur);
  gain.gain.setValueAtTime(0.0001,t0);
  gain.gain.exponentialRampToValueAtTime(vol||0.15,t0+0.02);
  gain.gain.exponentialRampToValueAtTime(0.0001,t0+dur);
  osc.connect(gain).connect(ctx.destination);
  osc.start(t0); osc.stop(t0+dur+0.02);
}
const sfx={
  bark:()=>{ beep(520,.12,'square',.12,300); setTimeout(()=>beep(420,.1,'square',.1,260),90); },
  eat:()=>{ for(let i=0;i<3;i++) setTimeout(()=>beep(180+Math.random()*60,.08,'square',.08),i*140); },
  bounce:()=>beep(300,.09,'triangle',.12,500),
  sleep:()=>beep(220,.5,'sine',.08,140),
  happy:()=>{ beep(660,.1,'sine',.12,880); setTimeout(()=>beep(880,.12,'sine',.12,1100),90); },
  step:()=>beep(120,.04,'square',.03)
};
document.getElementById('muteBtn').addEventListener('click',()=>{
  muted=!muted;
  document.getElementById('muteBtn').textContent=muted?'🔇':'🔊';
});

/* ============ PARTICLES / BUBBLE ============ */
function showBubble(text,ms){
  bubble.textContent=text;
  bubble.classList.add('show');
  clearTimeout(showBubble._t);
  showBubble._t=setTimeout(()=>bubble.classList.remove('show'),ms||2200);
}
function spawnParticle(emoji,x,y,dx){
  const p=document.createElement('div');
  p.className='particle';
  p.textContent=emoji;
  p.style.left=x+'px';
  p.style.top=y+'px';
  p.style.setProperty('--dx',(dx||0)+'px');
  world.appendChild(p);
  setTimeout(()=>p.remove(),1500);
}
function heartsBurst(){
  const r=wrap.getBoundingClientRect();
  const wr=world.getBoundingClientRect();
  for(let i=0;i<4;i++){
    setTimeout(()=>spawnParticle('💗', r.left-wr.left+40+Math.random()*40, r.top-wr.top+10, (Math.random()-0.5)*60),i*120);
  }
}
function foodParticles(){
  const r=wrap.getBoundingClientRect();
  const wr=world.getBoundingClientRect();
  for(let i=0;i<3;i++){
    setTimeout(()=>spawnParticle('✨', r.left-wr.left+50+Math.random()*30, r.top-wr.top+60,(Math.random()-0.5)*30),i*180);
  }
}

/* ============ STATE MACHINE HELPERS ============ */
const STATES=['idle','walking','running','looking','happy','excited','hungry','eating','sleepy',
  'walking_to_den','sleeping','waking_up','playing','chasing_ball','returning_ball','being_petted','sad','surprised'];

function setState(s){
  mochi.state=s;
  wrap.classList.remove('walking','running','wag-slow','wag-fast','wag-happy','jump');
  earL.classList.remove('ear-perk','ear-droop');
  earR.classList.remove('ear-perk','ear-droop');
  bodyGroup.classList.remove('breathe');
  browL.style.opacity=0; browR.style.opacity=0;
  setMouth('smile');

  switch(s){
    case 'idle':
      bodyGroup.classList.add('breathe');
      wrap.classList.add('wag-slow');
      break;
    case 'walking':
      wrap.classList.add('walking','wag-slow'); break;
    case 'running':
    case 'chasing_ball':
      wrap.classList.add('running','wag-fast');
      earL.classList.add('ear-perk'); earR.classList.add('ear-perk');
      break;
    case 'returning_ball':
      wrap.classList.add('walking','wag-happy');
      earL.classList.add('ear-perk'); earR.classList.add('ear-perk');
      break;
    case 'looking':
      earL.classList.add('ear-perk'); earR.classList.add('ear-perk');
      break;
    case 'happy':
    case 'excited':
    case 'being_petted':
      wrap.classList.add('wag-happy');
      earL.classList.add('ear-perk'); earR.classList.add('ear-perk');
      setMouth('smile-big');
      break;
    case 'hungry':
      setMouth('sad'); browL.style.opacity=1; browR.style.opacity=1;
      earL.classList.add('ear-droop'); earR.classList.add('ear-droop');
      break;
    case 'eating':
      wrap.classList.add('wag-fast');
      break;
    case 'sleepy':
    case 'walking_to_den':
      earL.classList.add('ear-droop'); earR.classList.add('ear-droop');
      setMouth('sad');
      break;
    case 'sleeping':
      earL.classList.add('ear-droop'); earR.classList.add('ear-droop');
      break;
    case 'waking_up':
      break;
    case 'playing':
      wrap.classList.add('wag-happy');
      break;
    case 'sad':
      setMouth('sad'); browL.style.opacity=1; browR.style.opacity=1;
      earL.classList.add('ear-droop'); earR.classList.add('ear-droop');
      break;
    case 'surprised':
      setMouth('o'); browL.style.opacity=1; browR.style.opacity=1;
      earL.classList.add('ear-perk'); earR.classList.add('ear-perk');
      break;
  }
}

function setMouth(kind){
  if(kind==='smile'){ mouth.setAttribute('d','M0,31 Q0,40 -10,38'); mouth2.setAttribute('d','M0,31 Q0,40 10,38'); }
  else if(kind==='smile-big'){ mouth.setAttribute('d','M0,32 Q0,46 -16,40'); mouth2.setAttribute('d','M0,32 Q0,46 16,40'); }
  else if(kind==='sad'){ mouth.setAttribute('d','M0,36 Q0,30 -10,34'); mouth2.setAttribute('d','M0,36 Q0,30 10,34'); }
  else if(kind==='o'){ mouth.setAttribute('d','M-6,32 a6,6 0 1,0 12,0 a6,6 0 1,0 -12,0'); mouth2.setAttribute('d','M0,31 Q0,31 0,31'); }
}

let eyesClosedFlag=false;
function setEyesClosed(closed){
  eyesClosedFlag=closed;
  eyelidL.style.transform='scaleY('+(closed?1:0)+')';
  eyelidR.style.transform='scaleY('+(closed?1:0)+')';
}

/* ============ MOVEMENT ============ */
function faceDir(dir){
  if(dir===mochi.facing) return;
  mochi.facing=dir;
  flip.style.transform = dir<0 ? 'scaleX(-1)' : 'scaleX(1)';
}

function walkTo(x,cb,runFlag){
  mochi.targetX=Math.max(WORLD_MIN_X,Math.min(worldMaxX(),x));
  mochi.onArrive=cb||null;
  if(Math.abs(mochi.targetX-mochi.x)>2){
    setState(runFlag?'running':'walking');
    faceDir(mochi.targetX>mochi.x?1:-1);
  } else if(cb){ cb(); }
}

let lastStep=0;
function tickMovement(dt){
  if(mochi.targetX!=null){
    const dx=mochi.targetX-mochi.x;
    const dist=Math.abs(dx);
    const spd=(mochi.state==='running'||mochi.state==='chasing_ball')?4.6:2.3;
    if(dist<3){
      mochi.x=mochi.targetX;
      mochi.targetX=null;
      const cb=mochi.onArrive; mochi.onArrive=null;
      if(cb) cb();
    } else {
      mochi.x += Math.sign(dx)*Math.min(spd,dist);
      const now=Date.now();
      if(now-lastStep>220){ lastStep=now; sfx.step(); }
    }
    wrap.style.left=mochi.x+'px';
  }
}

/* ============ MOUSE TRACKING ============ */
let mouse={x:null,y:null};
let lastMouseWalk=0;
world.addEventListener('mousemove',(e)=>{
  const r=world.getBoundingClientRect();
  mouse.x=e.clientX-r.left;
  mouse.y=e.clientY-r.top;
});
world.addEventListener('mouseleave',()=>{ mouse.x=null; mouse.y=null; });

function tickMouseAwareness(){
  if(mouse.x==null) return;
  const wr=wrap.getBoundingClientRect();
  const wrld=world.getBoundingClientRect();
  const headX=wr.left-wrld.left+wr.width/2;
  const headY=wr.top-wrld.top+wr.height*0.28;

  // eye / head look-toward
  const dxh=mouse.x-headX, dyh=mouse.y-headY;
  const angle=Math.max(-14,Math.min(14, (dxh/ (wrld.width/2)) * 18 ));
  headgroup.style.transform=`rotate(${angle*0.5}deg) translate(${Math.max(-6,Math.min(6,dxh*0.02))}px, ${Math.max(-4,Math.min(4,dyh*0.02))}px)`;
  const pupilShiftX=Math.max(-4,Math.min(4,dxh*0.02));
  const pupilShiftY=Math.max(-4,Math.min(4,dyh*0.02));
  pupilL.style.transform=`translate(${-3+pupilShiftX}px,${-3+pupilShiftY}px)`;
  pupilR.style.transform=`translate(${3+pupilShiftX}px,${3+pupilShiftY}px)`;

  if(mochi.busy || mochi.state==='sleeping'||mochi.state==='waking_up') return;

  const dist=Math.abs(mouse.x-mochi.x);
  const now=Date.now();
  if(dist>150 && now-lastMouseWalk>900){
    lastMouseWalk=now;
    if(mochi.state!=='walking' || mochi.targetX==null || Math.abs(mochi.targetX-mouse.x)>60){
      if(mochi.state==='idle'||mochi.state==='walking'||mochi.state==='looking'){
        walkTo(mouse.x);
        lastInteraction=Date.now();
      }
    }
  } else if(dist<=150 && mochi.state==='walking' && mochi.targetX!=null){
    // close enough, stop and look
  } else if(dist<80 && (mochi.state==='idle')){
    setState('looking');
    setTimeout(()=>{ if(mochi.state==='looking') setState('idle'); },1400);
  }
}

/* ============ PETTING ============ */
let petHold=null;
wrap.addEventListener('mousedown',(e)=>{
  e.stopPropagation();
  doPet();
});
function doPet(){
  if(mochi.busy && !['idle','walking','looking','happy'].includes(mochi.state)) {
    // allow petting almost anytime except mid-sleep/eat sequences core moment
  }
  interruptToFree();
  setState('being_petted');
  setEyesClosed(true);
  heartsBurst();
  sfx.happy();
  showBubble('😊 *happy puppy noises*',1600);
  adjustStats({happiness:+10});
  lastInteraction=Date.now();
  clearTimeout(doPet._t);
  doPet._t=setTimeout(()=>{
    setEyesClosed(false);
    if(mochi.state==='being_petted') setState('happy');
    setTimeout(()=>{ if(mochi.state==='happy') setState('idle'); },900);
  },1300);
}
document.getElementById('btnPet').addEventListener('click',doPet);

/* ============ SEQUENCES: EAT / SLEEP / PLAY / DRINK ============ */
function interruptToFree(){
  mochi.busy=false;
  mochi.targetX=null;
  mochi.onArrive=null;
  denEl.classList.remove('cozy');
  zzzEl.classList.remove('show');
  ball.style.display='none';
}

function doEat(){
  interruptToFree();
  mochi.busy=true;
  setState('hungry');
  foodContent.classList.add('show');
  showBubble('🍗 Ooh, food!',1600);
  walkTo(FOOD_X_PX,()=>{
    setState('eating');
    setMouth('smile');
    let count=0;
    const chew=setInterval(()=>{
      foodParticles();
      sfx.eat();
      count++;
      if(count>=4){
        clearInterval(chew);
        foodContent.classList.remove('show');
        adjustStats({hunger:+35,happiness:+8});
        setState('happy');
        setTimeout(()=>{ mochi.busy=false; setState('idle'); },900);
      }
    },500);
  });
}
document.getElementById('btnEat').addEventListener('click',()=>{ doEat(); lastInteraction=Date.now(); });

function doDrink(){
  interruptToFree();
  mochi.busy=true;
  showBubble('💧 slurp slurp',1400);
  walkTo(WATER_X_PX,()=>{
    setState('eating');
    let count=0;
    const drink=setInterval(()=>{
      count++;
      if(count>=3){
        clearInterval(drink);
        adjustStats({energy:+6,happiness:+3});
        setState('happy');
        setTimeout(()=>{ mochi.busy=false; setState('idle'); },700);
      }
    },400);
  });
}
document.getElementById('btnDrink').addEventListener('click',()=>{ doDrink(); lastInteraction=Date.now(); });

function doSleep(){
  interruptToFree();
  mochi.busy=true;
  setState('sleepy');
  showBubble('😴 *yawn*',1600);
  setTimeout(()=>{
    setState('walking_to_den');
    walkTo(DEN_X,()=>{
      denEl.classList.add('cozy');
      setState('sleeping');
      setEyesClosed(true);
      zzzEl.classList.add('show');
      sfx.sleep();
      wrap.style.transform='translateY(6px) scale(0.94)';
      sleepUntilWoken();
    });
  },900);
}
document.getElementById('btnSleep').addEventListener('click',()=>{
  lastInteraction=Date.now();
  if(mochi.state==='sleeping'){ doWake(); }
  else if(mochi.state!=='walking_to_den' && mochi.state!=='sleepy' && mochi.state!=='waking_up'){ doSleep(); }
});

let sleepTimer=null;
function sleepUntilWoken(){
  clearTimeout(sleepTimer);
  sleepTimer=setTimeout(()=>{
    if(mochi.state==='sleeping') doWake();
  }, 12000); // auto-wake fallback after 12s
}
function doWake(){
  clearTimeout(sleepTimer);
  setState('waking_up');
  zzzEl.classList.remove('show');
  setEyesClosed(false);
  wrap.style.transform='';
  denEl.classList.remove('cozy');
  showBubble('🥱 stretch...',1400);
  setTimeout(()=>{
    walkTo(YARD_X_PX,()=>{
      mochi.busy=false;
      setState('idle');
      adjustStats({energy:+4});
    });
  },900);
}
function doPlay(){
  interruptToFree();
  mochi.busy=true;
  setState('excited');
  sfx.bark();
  showBubble('🎾 Let\u2019s play!',1400);
  let rounds=0;
  const maxRounds=3;
  function throwBall(){
    const spot=BALL_SPOT_X + (Math.random()-0.5)*80;
    ball.style.left=Math.max(WORLD_MIN_X,Math.min(worldMaxX(),spot))+'px';
    ball.style.display='block';
    sfx.bounce();
    setState('chasing_ball');
    walkTo(spot,()=>{
      wrap.classList.add('jump');
      sfx.bounce();
      setTimeout(()=>{
        wrap.classList.remove('jump');
        ball.style.display='none';
        setState('returning_ball');
        walkTo(YARD_X_PX,()=>{
          rounds++;
          adjustStats({happiness:+6,energy:-6});
          if(rounds<maxRounds && stats.energy>15){
            setTimeout(throwBall,500);
          } else {
            setState('happy');
            setTimeout(()=>{ mochi.busy=false; setState('idle'); },800);
          }
        },true);
      },350);
    },true);
  }
  throwBall();
}
document.getElementById('btnPlay').addEventListener('click',()=>{ doPlay(); lastInteraction=Date.now(); });

/* ============ COMMAND PARSER ============ */
function runCommand(raw){
  const c=raw.trim().toLowerCase();
  if(!c) return;
  lastInteraction=Date.now();
  if(c.includes('sleep')){
    if(c.includes('wake')){ if(mochi.state==='sleeping') doWake(); else showBubble("I'm already awake!",1400); }
    else doSleep();
  } else if(c.includes('wake')){
    if(mochi.state==='sleeping') doWake(); else showBubble("I'm already awake!",1400);
  } else if(c.includes('eat') || c.includes('food') || c.includes('hungry')){
    doEat();
  } else if(c.includes('play') || c.includes('ball') || c.includes('fetch')){
    doPlay();
  } else if(c.includes('drink') || c.includes('water')){
    doDrink();
  } else if(c.includes('pet') || c.includes('love') || c.includes('good boy') || c.includes('good girl')){
    doPet();
  } else if(c.includes('come') || c.includes('here')){
    interruptToFree();
    walkTo(mochi.facing>=0? YARD_X_PX-40 : YARD_X_PX);
    showBubble('🐾 Coming!',1200);
  } else if(c.includes('sit')){
    interruptToFree();
    mochi.targetX=null;
    setState('looking');
    showBubble('🐶 *sits*',1200);
  } else if(c.includes('follow')){
    mochi.followMode=!mochi.followMode;
    showBubble(mochi.followMode? '👀 Following you!':'Okay, staying put.',1400);
  } else {
    setState('surprised');
    showBubble("Woof? 🐾",1400);
    setTimeout(()=>{ if(mochi.state==='surprised') setState('idle'); },1200);
  }
}
document.getElementById('cmdSend').addEventListener('click',()=>{
  const input=document.getElementById('cmdInput');
  runCommand(input.value);
  input.value='';
});
document.getElementById('cmdInput').addEventListener('keydown',(e)=>{
  if(e.key==='Enter'){ document.getElementById('cmdSend').click(); }
});

/* ============ STATS ============ */
function adjustStats(delta){
  Object.keys(delta).forEach(k=>{
    stats[k]=Math.max(0,Math.min(100,stats[k]+delta[k]));
  });
  renderStats();
  saveState();
}
function renderStats(){
  happyFill.style.width=stats.happiness+'%';
  hungerFill.style.width=stats.hunger+'%';
  energyFill.style.width=stats.energy+'%';
}

let lastStatTick=Date.now();
function tickStats(){
  const now=Date.now();
  const dt=(now-lastStatTick)/1000;
  lastStatTick=now;
  let hungerDrop=0.15*dt;
  let energyDelta=0;
  if(mochi.state==='running'||mochi.state==='chasing_ball'||mochi.state==='playing') energyDelta=-0.5*dt;
  else if(mochi.state==='sleeping') energyDelta=2.2*dt;
  else energyDelta=-0.06*dt;

  let happinessDelta=0;
  const idleSecs=(now-lastInteraction)/1000;
  if(idleSecs>40) happinessDelta=-0.08*dt;

  stats.hunger=Math.max(0,Math.min(100,stats.hunger-hungerDrop));
  stats.energy=Math.max(0,Math.min(100,stats.energy+energyDelta));
  stats.happiness=Math.max(0,Math.min(100,stats.happiness+happinessDelta));
  renderStats();
}

/* ============ AUTONOMOUS BEHAVIOR ============ */
let nextAutoAt=Date.now()+5000;
function maybeAutonomous(){
  const now=Date.now();

  // urgent: very tired -> auto sleep
  if(stats.energy<15 && !mochi.busy && mochi.state!=='sleeping' && mochi.state!=='walking_to_den'){
    doSleep();
    return;
  }
  // urgent: very hungry -> hint
  if(stats.hunger<20 && !mochi.busy && mochi.state==='idle'){
    setState('hungry');
    showBubble("I'm hungry 🥺",2200);
    walkTo(FOOD_X_PX,()=>{ if(mochi.state==='hungry') setState('idle'); });
    return;
  }
  // night + idle -> wander toward den
  if(timeOfDay==='night' && !mochi.busy && mochi.state==='idle' && Math.random()<0.4){
    doSleep();
    return;
  }

  if(now<nextAutoAt) return;
  nextAutoAt=now+4000+Math.random()*5000;
  if(mochi.busy) return;
  if(mochi.state!=='idle' && mochi.state!=='walking') return;

  const options=['wander','sit','look','yawn','wag','chase_butterfly','look_outside','drink_bit'];
  const pick=options[Math.floor(Math.random()*options.length)];
  switch(pick){
    case 'wander':
      walkTo(YARD_X_PX + (Math.random()-0.5)* (worldMaxX()-YARD_X_PX));
      break;
    case 'sit':
      setState('looking');
      setTimeout(()=>{ if(mochi.state==='looking') setState('idle'); },1600);
      break;
    case 'look':
      setState('surprised');
      setTimeout(()=>{ if(mochi.state==='surprised') setState('idle'); },900);
      break;
    case 'yawn':
      if(stats.energy<60){
        showBubble('🥱',1200);
      }
      break;
    case 'wag':
      setState('happy');
      setTimeout(()=>{ if(mochi.state==='happy') setState('idle'); },1000);
      break;
    case 'chase_butterfly':
      showBubble('🦋 !',1400);
      walkTo(mochi.x + (Math.random()>0.5?90:-90),null,true);
      break;
    case 'look_outside':
      setState('looking');
      setTimeout(()=>{ if(mochi.state==='looking') setState('idle'); },1800);
      break;
    case 'drink_bit':
      if(Math.random()<0.4 && !mochi.busy) doDrink();
      break;
  }
}

/* ============ MAIN LOOP ============ */
let blinkAt=Date.now()+2000;
function tickBlink(){
  if(mochi.state==='sleeping') return;
  const now=Date.now();
  if(now>blinkAt){
    blinkAt=now+2500+Math.random()*2500;
    if(!eyesClosedFlag){
      setEyesClosed(true);
      setTimeout(()=>{ if(!eyesClosedFlag) return; if(mochi.state!=='sleeping') setEyesClosed(false); },140);
    }
  }
}

function mainLoop(){
  updateSky();
  tickMovement();
  tickMouseAwareness();
  tickStats();
  tickBlink();
  maybeAutonomous();
  if(mochi.followMode && mouse.x!=null && !mochi.busy && (mochi.state==='idle'||mochi.state==='walking')){
    if(Math.abs(mouse.x-mochi.x)>40) walkTo(mouse.x);
  }
  requestAnimationFrame(mainLoop);
}

/* ============ SAVE / LOAD STATE ============ */
let saveTimer=null;
function saveState(){
  clearTimeout(saveTimer);
  saveTimer=setTimeout(async ()=>{
    try{
      if(window.storage){
        await window.storage.set('mochi-stats', JSON.stringify({stats, savedAt:Date.now()}), false);
      }
    }catch(e){ /* storage unavailable, ignore */ }
  },600);
}
async function loadState(){
  try{
    if(window.storage){
      const res=await window.storage.get('mochi-stats', false);
      if(res && res.value){
        const parsed=JSON.parse(res.value);
        if(parsed && parsed.stats){
          stats=Object.assign(stats,parsed.stats);
          renderStats();
        }
      }
    }
  }catch(e){ /* no saved state yet */ }
}

/* ============ INIT ============ */
function init(){
  layoutSpots();
  mochi.x=YARD_X_PX || 400;
  wrap.style.left=mochi.x+'px';
  setState('idle');
  renderStats();
  loadState().then(()=>{ requestAnimationFrame(mainLoop); });
}
window.addEventListener('load',init);
if(document.readyState==='complete') init();

})();
</script>
</body>
</html>
**Welcome to Mochi's little world! 🐾**

<br>

🍖 **Feed**&nbsp;&nbsp;&nbsp;🎾 **Play**&nbsp;&nbsp;&nbsp;💤 **Sleep**&nbsp;&nbsp;&nbsp;❤️ **Pet**

<br>

<img src="https://img.shields.io/badge/❤️%20Happiness-87%25-ff69b4?style=for-the-badge">
<img src="https://img.shields.io/badge/🍖%20Hunger-54%25-ffb000?style=for-the-badge">
<img src="https://img.shields.io/badge/⚡%20Energy-76%25-6c63ff?style=for-the-badge">

<br><br>

Mochi is an interactive virtual puppy I'm building as a separate web project — GitHub READMEs can't run JavaScript, so the "feed / play / pet" buttons above are just a preview of what the real site will do.

**🚧 Mochi's interactive world is coming soon!**

</div>

---

## 👩‍💻 About Me

* 🎓 B.Tech Student in **AI & Data Science**
* 🤖 Interested in **Artificial Intelligence, Machine Learning & LLMs**
* 🧠 Currently improving my **DSA & problem-solving skills**
* ☁️ Exploring **Cloud Computing**
* 💻 Building **AI & Full-Stack applications**
* 🚀 Turning ideas into real projects
* 📚 Always learning something new

---

## 💻 Coding Profiles

<div align="center">

<a href="https://linkedin.com/in/jahnavi-kollipara-672420334">
<img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" width="40" height="40" alt="LinkedIn">
</a>
&nbsp;&nbsp;&nbsp;
<a href="https://www.codechef.com/users/jahnavi_2026">
<img src="https://cdn.jsdelivr.net/npm/simple-icons@3.1.0/icons/codechef.svg" width="40" height="40" alt="CodeChef">
</a>
&nbsp;&nbsp;&nbsp;
<a href="https://www.hackerrank.com/jahnavikollipar3">
<img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hackerrank.svg" width="40" height="40" alt="HackerRank">
</a>
&nbsp;&nbsp;&nbsp;
<a href="https://codeforces.com/profile/jahnavikollipara055">
<img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/codeforces.svg" width="40" height="40" alt="Codeforces">
</a>
&nbsp;&nbsp;&nbsp;
<a href="https://leetcode.com/jahnavi_kollipara">
<img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" width="40" height="40" alt="LeetCode">
</a>

</div>

---

## 🛠️ Languages & Tools

<div align="center">

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" width="45" height="45" alt="C">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="45" height="45" alt="Java">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="45" height="45" alt="Python">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="45" height="45" alt="JavaScript">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" width="45" height="45" alt="HTML">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" width="45" height="45" alt="CSS">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" width="45" height="45" alt="React">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" width="45" height="45" alt="Node.js">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" width="45" height="45" alt="MySQL">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" width="45" height="45" alt="Docker">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/firebase/firebase-original.svg" width="45" height="45" alt="Firebase">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="45" height="45" alt="Git">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/figma/figma-original.svg" width="45" height="45" alt="Figma">

</div>

---

## 🚀 My Projects

<table>
<tr>
<td width="50%" valign="top">

### 🏠 Cloud Kitchen Management System
Full-stack food delivery application connecting customers, home chefs and delivery drivers.

**React • Firebase • Cloudinary**

</td>
<td width="50%" valign="top">

### 🤖 SmartDoc AI Assistant
An Agentic RAG-based PDF question-answering system.

**n8n • Docker • RAG • LLMs**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏡 House Price Prediction
A machine-learning based house price prediction and recommendation system.

**Python • Machine Learning**

</td>
<td width="50%" valign="top">

### 🎬 Movie Review Sentiment Analysis
An NLP project for classifying movie reviews using sentiment analysis.

**Python • NLP • Machine Learning**

</td>
</tr>
</table>

---

## 🧠 Currently Learning

<div align="center">

<img src="https://img.shields.io/badge/DSA-6C63FF?style=for-the-badge">
<img src="https://img.shields.io/badge/Machine%20Learning-FF69B4?style=for-the-badge">
<img src="https://img.shields.io/badge/LLMs-00BFFF?style=for-the-badge">
<img src="https://img.shields.io/badge/RAG-8A2BE2?style=for-the-badge">
<img src="https://img.shields.io/badge/Agentic%20AI-FFB000?style=for-the-badge">
<img src="https://img.shields.io/badge/Cloud-4285F4?style=for-the-badge">

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=saiharshithakollipara&show_icons=true&theme=default&hide_border=true&border_radius=15&bg_color=ffffff" height="170">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=saiharshithakollipara&theme=default&hide_border=true&border_radius=15&background=ffffff" height="170">

<br><br>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=saiharshithakollipara&layout=compact&theme=default&hide_border=true&border_radius=15&bg_color=ffffff">

</div>

---

## 🌱 My Coding Journey

<div align="center">

### 💡 Think → 🧠 Learn → 💻 Build → 🐛 Break → 🔧 Fix → 🚀 Ship

**"Always learning. Always building. Always curious."**

</div>

---

## 🐶 Mochi's Rules

<div align="center">

🍖 **Never forget to eat**

🎾 **Always make time to play**

💤 **Sleep when you're tired**

❤️ **Be curious**

🚀 **Keep building**

</div>

---

<div align="center">

### ✨ Thanks for visiting my profile! ✨

<img src="https://komarev.com/ghpvc/?username=saiharshithakollipara&label=Profile%20Views&color=6C63FF&style=for-the-badge">

<br><br>

🐾 **Mochi says: See you again!** 🐶

</div>
