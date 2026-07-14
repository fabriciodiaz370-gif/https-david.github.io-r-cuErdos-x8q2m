<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Un año nuestro</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;1,500&family=Marcellus&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
/* ============================================================================
   🔧 PERSONALIZÁ TODO EL CONTENIDO EN EL BLOQUE "CONFIG" DENTRO DEL <script>
   (contraseña, fecha de inicio, recuerdos, fotos, frases y música)
   ============================================================================ */

/* ===================== 1. VARIABLES Y BASE ===================== */
:root{
  --deep:       #030308;
  --gold:       #e7b768;
  --gold-soft:  #f0d4a0;
  --rose:       #ff8fab;
  --ink:        #f4eefc;
  --ink-dim:    #cbb9e8;
  --glass:      rgba(255,255,255,0.06);
  --accent-a:   #d98fa3;
  --accent-b:   #9077c9;
}
*{ margin:0; padding:0; box-sizing:border-box; -webkit-tap-highlight-color:transparent; }
html,body{ height:100%; width:100%; overflow:hidden; background:#000; font-family:'Poppins',sans-serif; color:var(--ink); }
.serif{ font-family:'Cormorant Garamond', serif; }
#app{ position:relative; width:100vw; height:100vh; overflow:hidden; }
::-webkit-scrollbar{ width:0; }
button{ font-family:'Poppins',sans-serif; }

/* ===================== 2. FONDO: NEBULOSA + ESTRELLAS + POLVO (canvas único) ===================== */
#bg-canvas{ position:fixed; inset:0; z-index:0; pointer-events:none; background:#000; }

/* destello de flash para transiciones cinematográficas */
#flash{
  position:fixed; inset:0; z-index:60; pointer-events:none;
  background:radial-gradient(circle at 50% 55%, rgba(255,241,214,.95), rgba(231,183,104,.4) 40%, transparent 70%);
  opacity:0;
}
#flash.fire{ animation:flash-anim 900ms ease-out forwards; }
@keyframes flash-anim{
  0%{ opacity:0; }
  12%{ opacity:1; }
  100%{ opacity:0; }
}

/* ===================== 3. PANTALLA DE BIENVENIDA ===================== */
#welcome{
  position:absolute; inset:0; z-index:20;
  display:flex; flex-direction:column; align-items:center; justify-content:center;
  text-align:center; padding:32px;
  transition: transform 1.1s cubic-bezier(.76,0,.24,1), opacity 1s ease, filter 1s ease;
}
#welcome.opening{ transform:scale(9); opacity:0; filter:blur(6px); }
#welcome.reentering{ transform:scale(9); opacity:0; filter:blur(6px); transition:none; }

.eyebrow{
  letter-spacing:.4em; text-transform:uppercase; font-size:11px; color:var(--gold-soft);
  opacity:.85; margin-bottom:18px; font-weight:400;
}

/* --- corazón de cristal con halo y partículas orbitando --- */
.locket-wrap{ position:relative; width:100px; height:100px; margin-bottom:24px; }
.locket{
  position:absolute; inset:7px; border-radius:50%;
  border:1px solid rgba(231,183,104,.55);
  display:flex; align-items:center; justify-content:center;
  background:linear-gradient(160deg, rgba(255,255,255,.10), rgba(255,255,255,.01));
  backdrop-filter:blur(2px);
  box-shadow: 0 0 40px rgba(231,183,104,.25), inset 0 0 20px rgba(231,183,104,.15);
  animation: breathe 4.5s ease-in-out infinite;
  overflow:hidden;
}
.locket::before{
  content:''; position:absolute; width:200%; height:200%; top:-50%; left:-90%;
  background:linear-gradient(75deg, transparent 40%, rgba(255,255,255,.35) 48%, transparent 56%);
  animation:shine-sweep 4.5s ease-in-out infinite;
}
@keyframes shine-sweep{ 0%,60%{ transform:translateX(0); } 100%{ transform:translateX(60%); } }
@keyframes breathe{
  0%,100%{ transform:scale(1); box-shadow:0 0 40px rgba(231,183,104,.25), inset 0 0 20px rgba(231,183,104,.15);}
  50%{ transform:scale(1.06); box-shadow:0 0 60px rgba(231,183,104,.4), inset 0 0 26px rgba(231,183,104,.25);}
}
.locket svg{ width:30px; height:30px; position:relative; z-index:1; }
.orbit{ position:absolute; inset:0; border-radius:50%; animation:spin linear infinite; }
.orbit .dot{ position:absolute; top:-1px; left:50%; width:4px; height:4px; margin-left:-2px; border-radius:50%; box-shadow:0 0 6px currentColor; }
.orbit.o1{ animation-duration:7s; color:var(--gold-soft); }
.orbit.o2{ animation-duration:11s; animation-direction:reverse; color:var(--accent-a); }
@keyframes spin{ to{ transform:rotate(360deg); } }

/* --- título letra por letra con brillo --- */
h1.title{
  font-size:clamp(34px,7vw,58px); font-weight:600; line-height:1.15; margin-bottom:10px;
  position:relative; overflow:hidden; display:inline-block;
}
h1.title .line{ display:block; }
h1.title .ch{
  display:inline-block; opacity:0; transform:translateY(16px);
  background:linear-gradient(120deg,var(--gold-soft),var(--rose) 55%, var(--gold-soft));
  -webkit-background-clip:text; background-clip:text; color:transparent;
  animation:letter-in .7s cubic-bezier(.2,.9,.3,1) forwards;
}
h1.title .ch.space{ width:.35em; }
@keyframes letter-in{ to{ opacity:1; transform:translateY(0); } }
h1.title .sheen{
  position:absolute; inset:0; pointer-events:none;
  background:linear-gradient(100deg, transparent 40%, rgba(255,255,255,.55) 50%, transparent 60%);
  transform:translateX(-120%);
  animation:sheen-move 3.4s ease-in-out 2.2s infinite;
  mix-blend-mode:overlay;
}
@keyframes sheen-move{ 0%,25%{ transform:translateX(-120%);} 55%{ transform:translateX(120%);} 100%{ transform:translateX(120%);} }

.subtitle{ font-size:15px; color:var(--ink-dim); font-weight:300; letter-spacing:.02em; max-width:380px; margin-bottom:38px; line-height:1.6; opacity:0; animation:fade-up .9s ease forwards; animation-delay:1.5s; }
@keyframes fade-up{ from{opacity:0; transform:translateY(10px);} to{opacity:1; transform:translateY(0);} }

.pw-wrap{ position:relative; width:min(300px,80vw); margin-bottom:16px; opacity:0; animation:fade-up .9s ease forwards; animation-delay:1.75s; }
#pw-input{
  width:100%; padding:15px 20px; border-radius:30px; border:1px solid rgba(244,238,252,.25);
  background:var(--glass); color:var(--ink); font-family:'Poppins',sans-serif; font-size:15px;
  letter-spacing:.15em; text-align:center; outline:none; backdrop-filter:blur(6px);
  transition:border-color .3s ease, box-shadow .3s ease;
}
#pw-input::placeholder{ color:var(--ink-dim); letter-spacing:.05em; }
#pw-input:focus{ border-color:var(--gold); box-shadow:0 0 0 4px rgba(231,183,104,.12); }
.pw-wrap.shake{ animation:shake .45s; }
@keyframes shake{ 0%,100%{transform:translateX(0);} 20%{transform:translateX(-10px);} 40%{transform:translateX(9px);} 60%{transform:translateX(-6px);} 80%{transform:translateX(4px);} }
#pw-error{ height:18px; font-size:12.5px; color:var(--rose); margin-bottom:14px; opacity:0; transition:opacity .25s ease; }
#pw-error.show{ opacity:1; }

#start-btn{
  position:relative; overflow:hidden; padding:15px 46px; border-radius:30px; border:none; cursor:pointer;
  background:linear-gradient(120deg,var(--accent-a),var(--accent-b),var(--accent-a));
  background-size:220% 220%; color:#221334; font-weight:600; font-size:14.5px; letter-spacing:.08em;
  text-transform:uppercase; box-shadow:0 8px 30px rgba(144,119,201,.35), 0 2px 0 rgba(255,255,255,.25) inset;
  animation: gradient-shift 4s ease-in-out infinite, pulse-glow 2.6s ease-in-out infinite, fade-up .9s ease forwards;
  animation-delay:0s,0s,2s;
  opacity:0;
  transition:transform .2s cubic-bezier(.34,1.56,.64,1);
}
@keyframes gradient-shift{ 0%,100%{background-position:0% 50%;} 50%{background-position:100% 50%;} }
@keyframes pulse-glow{ 0%,100%{box-shadow:0 8px 30px rgba(144,119,201,.35), 0 2px 0 rgba(255,255,255,.25) inset;} 50%{box-shadow:0 8px 46px rgba(217,143,163,.55), 0 2px 0 rgba(255,255,255,.25) inset;} }
#start-btn:hover{ transform:translateY(-3px) scale(1.04); }
#start-btn:active{ transform:translateY(1px) scale(.93); }
.ripple{ position:absolute; border-radius:50%; background:rgba(255,255,255,.55); transform:scale(0); animation:ripple-anim .6s ease-out forwards; pointer-events:none; }
@keyframes ripple-anim{ to{ transform:scale(3.2); opacity:0; } }

/* ===================== 4. GALAXIA DE RECUERDOS ===================== */
#galaxy{ position:absolute; inset:0; z-index:10; opacity:0; pointer-events:none; transition:opacity 1.1s ease; }
#galaxy.visible{ opacity:1; pointer-events:auto; }

#galaxy-header{ position:absolute; top:0; left:0; right:0; z-index:12; text-align:center; padding:26px 60px 10px; pointer-events:none; }
#galaxy-header h2{ font-family:'Cormorant Garamond',serif; font-style:italic; font-weight:500; font-size:clamp(20px,4vw,28px); color:var(--gold-soft); text-shadow:0 0 20px rgba(231,183,104,.35); }
#galaxy-header p{ font-size:11px; color:var(--ink-dim); letter-spacing:.13em; text-transform:uppercase; margin-top:6px; }

#back-btn{
  position:fixed; top:18px; left:18px; z-index:50; width:42px; height:42px; border-radius:50%;
  border:1px solid rgba(244,238,252,.2); background:rgba(0,0,0,.5); backdrop-filter:blur(8px);
  color:var(--gold-soft); display:flex; align-items:center; justify-content:center; cursor:pointer;
  opacity:0; pointer-events:none; transition:opacity .5s ease, background .25s ease;
}
#back-btn.show{ opacity:1; pointer-events:auto; }
#back-btn:hover{ background:rgba(144,119,201,.25); }
#back-btn svg{ width:18px; height:18px; }

#bubble-field{ position:absolute; inset:0; }

.bubble{
  position:absolute; border-radius:50%; cursor:pointer; overflow:hidden;
  border:1.5px solid rgba(244,238,252,.35);
  box-shadow:0 0 0 rgba(144,119,201,0), 0 6px 24px rgba(0,0,0,.35);
  transition: box-shadow .35s ease, filter .35s ease, opacity .5s ease, transform .5s ease;
  will-change: transform; width:var(--size); height:var(--size);
  background:radial-gradient(circle at 35% 30%, rgba(144,119,201,.35), rgba(10,6,20,.9));
}
.bubble .halo{ position:absolute; inset:-30%; border-radius:50%; background:radial-gradient(circle, rgba(231,183,104,.16), transparent 70%); opacity:0; transition:opacity .3s ease; }
.bubble.big .halo{ opacity:1; }
.bubble .bg{ position:absolute; inset:-14%; background-size:cover; background-position:center; filter:blur(7px) saturate(1.15) brightness(.8); transform:scale(1.1); }
.bubble .tint{ position:absolute; inset:0; background:linear-gradient(160deg, rgba(217,143,163,.28), rgba(29,15,48,.55)); mix-blend-mode:soft-light; }
.bubble .glass{ position:absolute; inset:0; border-radius:50%; background:linear-gradient(135deg, rgba(255,255,255,.30) 0%, rgba(255,255,255,0) 30%, rgba(255,255,255,0) 70%, rgba(255,255,255,.10) 100%); }
.bubble::after{ content:''; position:absolute; inset:0; border-radius:50%; z-index:2; background:radial-gradient(circle at 32% 28%, rgba(255,255,255,.30), rgba(255,255,255,0) 55%); }
.bubble:hover{ box-shadow:0 0 30px rgba(144,119,201,.6), 0 10px 30px rgba(0,0,0,.4); filter:brightness(1.12); transform:scale(1.12) !important; }
.bubble.opened{ opacity:0; transform:scale(2.6); pointer-events:none; }
.bubble.entering{ opacity:0; transform:scale(.25); }
.bubble.entering.show{ opacity:1; transform:scale(1); }
.bubble .label{
  position:absolute; z-index:5; top:calc(100% + 8px); left:50%; transform:translateX(-50%) translateY(2px);
  font-size:10.5px; letter-spacing:.06em; white-space:nowrap; color:var(--ink);
  background:rgba(10,6,20,.6); padding:4px 10px; border-radius:12px; border:1px solid rgba(244,238,252,.15);
  opacity:0; pointer-events:none; transition:opacity .25s ease, transform .25s ease;
}
.bubble:hover .label{ opacity:1; transform:translateX(-50%) translateY(0); }

/* corazones chiquitos que suben al abrir un recuerdo */
.mini-heart{ position:fixed; z-index:45; font-size:16px; pointer-events:none; color:var(--rose); animation:heart-rise 1.1s ease-out forwards; }
@keyframes heart-rise{ 0%{ opacity:0; transform:translate(0,0) scale(.5);} 15%{opacity:1;} 100%{ opacity:0; transform:translate(var(--hx),-90px) scale(1.1); } }

/* ===================== 5. TARJETA DE RECUERDO (glassmorphism + marco dorado) ===================== */
#card-overlay{
  position:fixed; inset:0; z-index:40; display:flex; align-items:center; justify-content:center; padding:26px;
  background:rgba(0,0,0,.6); backdrop-filter:blur(10px);
  opacity:0; pointer-events:none; transition:opacity .5s ease;
}
#card-overlay.visible{ opacity:1; pointer-events:auto; }

#card-wrap{ position:relative; width:min(400px,92vw); border-radius:28px; }

#memory-card{
  position:relative; max-height:86vh; overflow-y:auto; border-radius:26px;
  background:linear-gradient(160deg, rgba(30,20,50,.94), rgba(5,5,10,.97));
  box-shadow:0 30px 80px rgba(0,0,0,.55), 0 0 60px rgba(231,183,104,.12);
  padding:22px 22px 26px; text-align:center;
  transform:scale(.72) translateY(70px); opacity:0;
  transition:transform .6s cubic-bezier(.2,.9,.25,1.05), opacity .45s ease;
}
#card-overlay.visible #memory-card{ transform:scale(1) translateY(0); opacity:1; }

.chapter-label{ font-size:10.5px; letter-spacing:.28em; text-transform:uppercase; color:var(--accent-a); margin-bottom:14px; }

#memory-card .frame{ position:relative; width:100%; aspect-ratio:1/1; border-radius:18px; overflow:hidden; border:1px solid rgba(244,238,252,.2); margin-bottom:18px; box-shadow:0 10px 30px rgba(0,0,0,.4); }
#memory-card img{ width:100%; height:100%; object-fit:cover; display:block; filter:sepia(.16) contrast(1.06) saturate(1.06) brightness(.97); transform:scale(1.12); opacity:0; transition:transform .9s cubic-bezier(.2,.8,.2,1), opacity .5s ease; }
#card-overlay.visible #memory-card img{ transform:scale(1); opacity:1; }
#memory-card .frame::after{ content:''; position:absolute; inset:0; box-shadow:inset 0 0 50px rgba(0,0,0,.55); pointer-events:none; }

#memory-card .date{ font-size:11px; letter-spacing:.2em; text-transform:uppercase; color:var(--gold-soft); margin-bottom:10px; opacity:.9; }
#memory-card .phrase{ font-family:'Cormorant Garamond',serif; font-style:italic; font-size:clamp(19px,4.4vw,23px); line-height:1.5; color:var(--ink); }

.nav-row{ display:flex; align-items:center; justify-content:center; margin-top:22px; }
.nav-btn{ background:none; border:none; color:var(--ink-dim); font-size:12.5px; letter-spacing:.05em; cursor:pointer; padding:8px; display:flex; align-items:center; gap:6px; transition:color .2s ease; }
.nav-btn:hover{ color:var(--gold-soft); }
.nav-btn svg{ width:14px; height:14px; }
.counter{ font-size:11px; letter-spacing:.1em; color:var(--ink-dim); }

.card-actions{ display:flex; justify-content:center; margin-top:18px; }
.pill-btn{ padding:11px 24px; border-radius:24px; border:1px solid rgba(244,238,252,.3); background:var(--glass); color:var(--ink); font-size:12.5px; letter-spacing:.08em; cursor:pointer; text-transform:uppercase; transition:all .25s ease; }
.pill-btn:hover{ background:rgba(144,119,201,.18); border-color:var(--accent-b); }

/* ===================== 6. REPRODUCTOR DE MÚSICA FLOTANTE ===================== */
#music-ctrl{
  position:fixed; bottom:22px; right:22px; z-index:50; display:flex; align-items:center; gap:10px;
  opacity:0; pointer-events:none; transition:opacity .6s ease;
}
#music-ctrl.show{ opacity:1; pointer-events:auto; }
#vol-pop{
  background:rgba(10,6,20,.7); border:1px solid rgba(244,238,252,.18); border-radius:20px; padding:8px 14px;
  backdrop-filter:blur(8px); display:flex; align-items:center; opacity:0; transform:translateX(8px) scale(.9);
  pointer-events:none; transition:opacity .25s ease, transform .25s ease;
}
#music-ctrl:hover #vol-pop, #music-ctrl.expanded #vol-pop{ opacity:1; transform:translateX(0) scale(1); pointer-events:auto; }
#vol-slider{ -webkit-appearance:none; width:80px; height:3px; border-radius:3px; background:rgba(244,238,252,.3); outline:none; }
#vol-slider::-webkit-slider-thumb{ -webkit-appearance:none; width:12px; height:12px; border-radius:50%; background:var(--gold-soft); cursor:pointer; }
#vol-slider::-moz-range-thumb{ width:12px; height:12px; border-radius:50%; background:var(--gold-soft); border:none; cursor:pointer; }

#mute-btn{
  position:relative; width:52px; height:52px; border-radius:50%; border:1px solid rgba(231,183,104,.4); cursor:pointer;
  background:radial-gradient(circle at 35% 30%, rgba(255,255,255,.15), rgba(20,12,35,.75));
  backdrop-filter:blur(8px); box-shadow:0 8px 26px rgba(0,0,0,.45), 0 0 0 rgba(231,183,104,0);
  display:flex; align-items:center; justify-content:center; color:var(--gold-soft);
  transition:box-shadow .3s ease;
}
#mute-btn.playing{ box-shadow:0 8px 26px rgba(0,0,0,.45), 0 0 22px rgba(231,183,104,.35); }
#mute-btn svg{ width:19px; height:19px; z-index:2; position:relative; }
.bars{ position:absolute; bottom:11px; left:50%; transform:translateX(-50%); display:flex; gap:2.5px; align-items:flex-end; height:10px; }
.bars span{ width:2.5px; background:var(--gold-soft); border-radius:2px; height:3px; opacity:.55; }
#mute-btn.playing .bars span{ animation:bar-bounce 900ms ease-in-out infinite; opacity:.9; }
.bars span:nth-child(1){ animation-delay:0ms; } .bars span:nth-child(2){ animation-delay:150ms; }
.bars span:nth-child(3){ animation-delay:300ms; } .bars span:nth-child(4){ animation-delay:450ms; }
@keyframes bar-bounce{ 0%,100%{ height:3px; } 50%{ height:11px; } }

/* ===================== 7. MENSAJE SECRETO OCULTO ===================== */
#secret-trigger{
  position:fixed; bottom:20px; left:20px; z-index:50; width:14px; height:14px; border-radius:50%;
  background:rgba(255,143,171,.35); cursor:pointer; opacity:0; pointer-events:none;
  transition:opacity 1s ease, background .3s ease; animation:secret-pulse 3s ease-in-out infinite;
}
#secret-trigger.show{ opacity:.55; pointer-events:auto; }
#secret-trigger:hover{ background:rgba(255,143,171,.8); }
@keyframes secret-pulse{ 0%,100%{ box-shadow:0 0 0 rgba(255,143,171,.5);} 50%{ box-shadow:0 0 14px rgba(255,143,171,.7);} }
#secret-modal{
  position:fixed; inset:0; z-index:65; display:flex; align-items:center; justify-content:center; padding:30px;
  background:rgba(0,0,0,.7); backdrop-filter:blur(10px); opacity:0; pointer-events:none; transition:opacity .4s ease;
}
#secret-modal.visible{ opacity:1; pointer-events:auto; }
#secret-modal .box{ max-width:340px; text-align:center; padding:30px 26px; border-radius:22px; border:1px solid rgba(255,143,171,.35); background:linear-gradient(160deg, rgba(40,20,45,.9), rgba(8,5,14,.95)); }
#secret-modal p{ font-family:'Cormorant Garamond',serif; font-style:italic; font-size:19px; line-height:1.6; margin-bottom:18px; }

/* ===================== 8. ESCENA FINAL SECRETA ===================== */
#finale{
  position:fixed; inset:0; z-index:70; display:flex; align-items:center; justify-content:center; flex-direction:column;
  text-align:center; padding:32px; background:#000; opacity:0; pointer-events:none; transition:opacity 1.2s ease;
}
#finale.visible{ opacity:1; pointer-events:auto; }
#finale .eyebrow{ margin-bottom:16px; }
#finale h2{ font-family:'Cormorant Garamond',serif; font-style:italic; font-weight:500; font-size:clamp(22px,5vw,32px); color:var(--ink); max-width:600px; line-height:1.5; margin-bottom:14px; opacity:0; }
#finale h2.appear{ animation:fade-up 1.2s ease forwards; }
#finale .big-line{ font-family:'Cormorant Garamond',serif; font-weight:600; font-size:clamp(30px,7vw,50px); background:linear-gradient(120deg,var(--gold-soft),var(--rose)); -webkit-background-clip:text; background-clip:text; color:transparent; margin:14px 0 30px; opacity:0; }
#finale .big-line.appear{ animation:fade-up 1.2s ease forwards; }
.falling-heart{ position:fixed; top:-30px; z-index:69; font-size:18px; color:var(--rose); pointer-events:none; animation:heart-fall linear forwards; }
@keyframes heart-fall{ to{ transform:translateY(110vh) rotate(40deg); opacity:0; } }

@media (prefers-reduced-motion: reduce){
  .locket, #start-btn, .orbit{ animation:none !important; }
}
@media (max-width:520px){
  #galaxy-header{ padding:22px 70px 8px; }
  #music-ctrl{ bottom:16px; right:16px; }
  #secret-trigger{ bottom:16px; left:16px; }
}
</style>
</head>
<body>
<div id="app">
  <canvas id="bg-canvas"></canvas>
  <div id="flash"></div>

  <!-- ============ PANTALLA DE BIENVENIDA ============ -->
  <div id="welcome">
    <div class="eyebrow">un recuerdo para vos</div>
    <div class="locket-wrap">
      <div class="orbit o1"><span class="dot"></span></div>
      <div class="orbit o2"><span class="dot"></span></div>
      <div class="locket">
        <svg viewBox="0 0 24 24" fill="none" stroke="#f0d4a0" stroke-width="1.4">
          <path d="M12 21s-7.5-4.6-10-9.2C.4 8.1 2.3 4.5 6 4.1c2.1-.2 3.8 1 6 3.4 2.2-2.4 3.9-3.6 6-3.4 3.7.4 5.6 4 4 7.7C19.5 16.4 12 21 12 21z"/>
        </svg>
      </div>
    </div>
    <h1 class="title" id="title-target">
      <span class="sheen"></span>
    </h1>
    <p class="subtitle">Un año guardando momentos. Antes de entrar, necesito saber que sos vos.</p>

    <div class="pw-wrap" id="pw-wrap">
      <input id="pw-input" type="password" placeholder="contraseña" autocomplete="off">
    </div>
    <div id="pw-error">esa no es&hellip; probá de nuevo</div>
    <button id="start-btn">Comenzar</button>
  </div>

  <!-- ============ GALAXIA DE RECUERDOS ============ -->
  <div id="galaxy">
    <div id="galaxy-header">
      <h2>Tocá un recuerdo</h2>
      <p id="days-counter">un año, tantos momentos</p>
    </div>
    <div id="bubble-field"></div>
  </div>

  <button id="back-btn" title="Volver al inicio">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M19 12H5"/><path d="M11 18l-6-6 6-6"/></svg>
  </button>

  <!-- ============ TARJETA DE RECUERDO ============ -->
  <div id="card-overlay">
    <div id="card-wrap">
      <div id="memory-card">
        <div class="chapter-label" id="card-chapter">CAPÍTULO 01</div>
        <div class="frame"><img id="card-img" src="" alt=""></div>
        <div class="date" id="card-date"></div>
        <div class="phrase" id="card-phrase"></div>
        <div class="nav-row">
          <span class="counter" id="card-counter">1 de 8</span>
        </div>
        <div class="card-actions"><button class="pill-btn" id="close-btn">Volver</button></div>
      </div>
    </div>
  </div>

  <!-- ============ MÚSICA ============ -->
  <div id="music-ctrl">
    <div id="vol-pop"><input id="vol-slider" type="range" min="0" max="100" value="55"></div>
    <button id="mute-btn">
      <div class="bars"><span></span><span></span><span></span><span></span></div>
      <svg id="icon-on" viewBox="0 0 24 24" fill="currentColor"><path d="M4 9v6h4l5 5V4L8 9H4z"/></svg>
      <svg id="icon-off" viewBox="0 0 24 24" fill="currentColor" style="display:none"><path d="M4 9v6h4l5 5V4L8 9H4z"/><path d="M19 8l-4 4m0-4l4 4" stroke="currentColor" stroke-width="1.6" fill="none" stroke-linecap="round"/></svg>
    </button>
  </div>
  <audio id="bg-audio" loop preload="none"></audio>

  <!-- ============ MENSAJE SECRETO ============ -->
  <div id="secret-trigger" title="???"></div>
  <div id="secret-modal">
    <div class="box">
      <p id="secret-text"></p>
      <button class="pill-btn" id="secret-close">Cerrar</button>
    </div>
  </div>

  <!-- ============ ESCENA FINAL ============ -->
  <div id="finale">
    <div class="eyebrow">recorriste cada recuerdo</div>
    <h2 id="finale-l1">Y después de todos estos momentos&hellip;</h2>
    <div class="big-line" id="finale-l2">Vos y yo ❤</div>
    <h2 id="finale-l3" style="font-size:15px; max-width:420px; color:var(--ink-dim);">El recuerdo más importante todavía sigue escribiéndose.</h2>
    <button class="pill-btn" id="finale-btn" style="margin-top:26px;">Volver a ver nuestra historia</button>
  </div>
</div>

<script>
/* ============================================================================
   🔧 CONFIG — PERSONALIZÁ TODO ACÁ
   ============================================================================ */
const CONFIG = {
  password: "1año",
  musicUrl: "",                 // URL de un mp3. Vacío = sin música.
  startDate: "2025-07-13",      // fecha en que empezaron (para el contador de días)
  titleLine1: "Una mente",
  titleLine2: "llena de nosotros",
  secretMessage: "Este es un mensaje secreto para vos: pase lo que pase, elijo seguir sumando recuerdos a esta mente. Te amo.",
  passwordHint: "pista: nuestro primer mes 💛",   // aparece después de varios intentos fallidos
  memories: [
    { date: "7 de julio", photo: "fotos/IMG-20250707-WA0015.jpg", phrase: "El principio de algo que no sabíamos que iba a ser tan grande.", big:true },
    { date: "18 de julio", photo: "fotos/IMG-20250718-WA0009.jpg", phrase: "Ni con la cara verde dejás de ser mi persona favorita." },
    { date: "26 de julio", photo: "fotos/IMG-20250726-WA0027.jpg", phrase: "Un beso robado frente al espejo, de esos que quiero mil veces más." },
    { date: "29 de julio", photo: "fotos/IMG-20250729-WA0014.jpg", phrase: "Caminando de noche sin apuro, como si el tiempo fuera solo nuestro." },
    { date: "6 de agosto", photo: "fotos/IMG-20250806-WA0101.jpg", phrase: "Nuestro lado más pavote, el que solo se muestra en confianza." },
    { date: "9 de agosto", photo: "fotos/IMG-20250809-WA0026.jpg", phrase: "Las fotos que salen mal son las que más me hacen reír después.", big:true },
    { date: "4 de septiembre", photo: "fotos/IMG-20250904-WA0035.jpg", phrase: "Un día cualquiera caminando juntos, de esos que sin querer se vuelven recuerdo." },
    { date: "4 de septiembre", photo: "fotos/IMG-20250904-WA0029.jpg", phrase: "El mismo día, otro beso más para la colección." },
    { date: "15 de septiembre", photo: "fotos/IMG-20250915-WA0015.jpg", phrase: "Así de simple es el cariño cuando es de verdad." },
    { date: "15 de octubre", photo: "fotos/IMG-20251015-WA0037.jpg", phrase: "Haciendo caras raras porque con vos hasta lo tonto se disfruta." },
    { date: "25 de octubre", photo: "fotos/IMG-20251025-WA0018.jpg", phrase: "Entre perros y atardeceres, otra tarde perfecta con vos.", big:true },
    { date: "31 de octubre", photo: "fotos/IMG-20251031-WA0007.jpg", phrase: "Hasta patas para arriba, el mundo se ve mejor con vos al lado." },
    { date: "8 de noviembre", photo: "fotos/IMG-20251108-WA0016_1_.jpg", phrase: "Robándonos sonrisas en cualquier esquina." },
    { date: "22 de noviembre", photo: "fotos/IMG-20251122-WA0001.jpg", phrase: "Abrazados mirando el cielo, sintiendo que el tiempo se detiene.", big:true },
    { date: "26 de diciembre", photo: "fotos/IMG-20251226-WA0021.jpg", phrase: "Cerrando el año haciendo morisquetas, como siempre." },
    { date: "1 de enero", photo: "fotos/IMG-20260101-WA0012.jpg", phrase: "El primer atardecer del año, y ya empezó siendo nuestro." },
    { date: "17 de febrero", photo: "fotos/IMG-20260217-WA0018.jpg", phrase: "Sol, arena y vos: la combinación perfecta de verano." },
    { date: "1 de junio", photo: "fotos/IMG-20260601-WA0020.jpg", phrase: "Un trámite cualquiera se hace especial cuando lo hacemos juntos.", big:true }
  ]
};
/* ============================================================================ */

/* ===================== AUDIO SINTETIZADO (sin archivos externos) ===================== */
let actx = null;
function ensureAudioCtx(){ if(!actx){ try{ actx = new (window.AudioContext||window.webkitAudioContext)(); }catch(e){} } return actx; }
function playWhoosh(){
  const ctx = ensureAudioCtx(); if(!ctx) return;
  const o = ctx.createOscillator(), g = ctx.createGain();
  o.type='sine'; o.frequency.setValueAtTime(180, ctx.currentTime); o.frequency.exponentialRampToValueAtTime(640, ctx.currentTime+0.7);
  g.gain.setValueAtTime(0.0001, ctx.currentTime); g.gain.exponentialRampToValueAtTime(0.16, ctx.currentTime+0.08); g.gain.exponentialRampToValueAtTime(0.0001, ctx.currentTime+0.8);
  o.connect(g); g.connect(ctx.destination); o.start(); o.stop(ctx.currentTime+0.85);
}
function playBell(){
  const ctx = ensureAudioCtx(); if(!ctx) return;
  [880,1320].forEach((freq,i)=>{
    const o = ctx.createOscillator(), g = ctx.createGain();
    o.type='sine'; o.frequency.value = freq;
    g.gain.setValueAtTime(0.0001, ctx.currentTime);
    g.gain.exponentialRampToValueAtTime(0.14/(i+1), ctx.currentTime+0.02);
    g.gain.exponentialRampToValueAtTime(0.0001, ctx.currentTime+1.1);
    o.connect(g); g.connect(ctx.destination); o.start(); o.stop(ctx.currentTime+1.15);
  });
}

/* ===================== FONDO: canvas único (nebulosa + estrellas + polvo + fugaces + destellos) ===================== */
const bgCanvas = document.getElementById('bg-canvas');
const bctx = bgCanvas.getContext('2d');
let bw, bh, stars=[], dust=[], nebulas=[], shootingStars=[], bursts=[];
const isMobile = window.innerWidth < 600;

function resizeBg(){ bw = bgCanvas.width = window.innerWidth; bh = bgCanvas.height = window.innerHeight; }

function initField(){
  resizeBg();
  const nStars = isMobile ? 120 : 210;
  stars = Array.from({length:nStars}, () => {
    const depth = Math.random();
    return { x:Math.random()*bw, y:Math.random()*bh, r:0.4+depth*1.6,
      vx:(Math.random()-0.5)*(0.06+depth*0.16), vy:(Math.random()-0.5)*(0.06+depth*0.16),
      baseAlpha:0.25+depth*0.65, tp:Math.random()*Math.PI*2, ts:0.4+Math.random()*0.8 };
  });
  const nDust = isMobile ? 16 : 34;
  dust = Array.from({length:nDust}, () => ({
    x:Math.random()*bw, y:Math.random()*bh, r:0.8+Math.random()*1.6,
    vy:-(0.008+Math.random()*0.02), vx:(Math.random()-0.5)*0.012,
    alpha:0.15+Math.random()*0.35, phase:Math.random()*Math.PI*2
  }));
  nebulas = [
    { hue:'147,119,201', baseX:0.25, baseY:0.3, r:Math.max(bw,bh)*0.42, sp:0.00006, ph:0 },
    { hue:'217,143,163', baseX:0.75, baseY:0.65, r:Math.max(bw,bh)*0.38, sp:0.00008, ph:2 },
    { hue:'90,110,190',  baseX:0.5,  baseY:0.85, r:Math.max(bw,bh)*0.4,  sp:0.00005, ph:4 }
  ];
}

let nextShootAt = performance.now() + 2500 + Math.random()*3500;
function spawnShootingStar(){
  const fromLeft = Math.random() < 0.5;
  const startX = fromLeft ? -20 : bw + 20;
  const startY = Math.random() * bh * 0.55;
  const angle = fromLeft ? (0.25+Math.random()*0.35) : (Math.PI-0.25-Math.random()*0.35);
  const speed = 0.9+Math.random()*0.7;
  shootingStars.push({ x:startX, y:startY, vx:Math.cos(angle)*speed, vy:Math.sin(angle)*speed, life:0, maxLife:700+Math.random()*400, len:70+Math.random()*70 });
}
function spawnBurst(x, y, count, colors){
  for(let i=0;i<count;i++){
    const ang = Math.random()*Math.PI*2, spd = 0.4+Math.random()*1.6;
    bursts.push({ x, y, vx:Math.cos(ang)*spd, vy:Math.sin(ang)*spd, life:0, maxLife:500+Math.random()*400,
      r:1+Math.random()*2, color: colors[Math.floor(Math.random()*colors.length)] });
  }
}
window.spawnBurst = spawnBurst; // usado por otras funciones (apertura de recuerdos, transición inicial)

let lastT = performance.now();
function tick(t){
  const dt = Math.min(50, t - lastT); lastT = t;
  bctx.clearRect(0,0,bw,bh);
  bctx.fillStyle = '#000'; bctx.fillRect(0,0,bw,bh);

  // nebulosa
  bctx.globalCompositeOperation = 'lighter';
  for(const n of nebulas){
    n.ph += n.sp*dt;
    const cx = bw*n.baseX + Math.sin(n.ph)*bw*0.08;
    const cy = bh*n.baseY + Math.cos(n.ph*0.8)*bh*0.06;
    const grad = bctx.createRadialGradient(cx,cy,0,cx,cy,n.r);
    grad.addColorStop(0, `rgba(${n.hue},0.10)`);
    grad.addColorStop(1, `rgba(${n.hue},0)`);
    bctx.fillStyle = grad;
    bctx.beginPath(); bctx.arc(cx,cy,n.r,0,Math.PI*2); bctx.fill();
  }
  bctx.globalCompositeOperation = 'source-over';

  // polvo dorado
  for(const d of dust){
    d.y += d.vy*dt; d.x += d.vx*dt + Math.sin(d.phase)*0.02;
    d.phase += 0.0012*dt;
    if(d.y < -10) d.y = bh+10;
    if(d.x < -10) d.x = bw+10; if(d.x > bw+10) d.x = -10;
    bctx.beginPath(); bctx.fillStyle = `rgba(231,183,104,${d.alpha})`;
    bctx.arc(d.x, d.y, d.r, 0, Math.PI*2); bctx.fill();
  }

  // estrellas
  for(const s of stars){
    s.x += s.vx*dt*0.09; s.y += s.vy*dt*0.09;
    if(s.x<-5) s.x=bw+5; if(s.x>bw+5) s.x=-5; if(s.y<-5) s.y=bh+5; if(s.y>bh+5) s.y=-5;
    s.tp += s.ts*dt*0.001;
    const a = s.baseAlpha*(0.6+0.4*Math.sin(s.tp));
    bctx.beginPath(); bctx.fillStyle = `rgba(255,255,255,${a})`; bctx.arc(s.x,s.y,s.r,0,Math.PI*2); bctx.fill();
  }

  // estrellas fugaces
  if(t > nextShootAt){ spawnShootingStar(); nextShootAt = t + 3000 + Math.random()*5000; }
  shootingStars = shootingStars.filter(s => s.life < s.maxLife);
  for(const s of shootingStars){
    s.x += s.vx*dt; s.y += s.vy*dt; s.life += dt;
    const fade = 1-(s.life/s.maxLife);
    const ang = Math.atan2(s.vy, s.vx);
    const tx = s.x - Math.cos(ang)*s.len, ty = s.y - Math.sin(ang)*s.len;
    const grad = bctx.createLinearGradient(s.x,s.y,tx,ty);
    grad.addColorStop(0, `rgba(255,255,255,${0.9*fade})`); grad.addColorStop(1, 'rgba(255,255,255,0)');
    bctx.strokeStyle = grad; bctx.lineWidth = 1.6;
    bctx.beginPath(); bctx.moveTo(s.x,s.y); bctx.lineTo(tx,ty); bctx.stroke();
  }

  // partículas de estallido (transición inicial / apertura de recuerdos)
  bursts = bursts.filter(b => b.life < b.maxLife);
  for(const b of bursts){
    b.x += b.vx*dt; b.y += b.vy*dt; b.life += dt; b.vx *= 0.985; b.vy *= 0.985;
    const fade = 1-(b.life/b.maxLife);
    bctx.beginPath(); bctx.fillStyle = b.color.replace('ALPHA', (fade*0.9).toFixed(2));
    bctx.arc(b.x,b.y,b.r,0,Math.PI*2); bctx.fill();
  }

  requestAnimationFrame(tick);
}
initField();
requestAnimationFrame(tick);
window.addEventListener('resize', () => { resizeBg(); });

/* ===================== TÍTULO LETRA POR LETRA ===================== */
(function buildTitle(){
  const target = document.getElementById('title-target');
  const sheen = target.querySelector('.sheen');
  let delay = 0;
  [CONFIG.titleLine1, CONFIG.titleLine2].forEach((line, li) => {
    const lineEl = document.createElement('span');
    lineEl.className = 'line';
    line.split('').forEach(ch => {
      const span = document.createElement('span');
      span.className = 'ch' + (ch === ' ' ? ' space' : '');
      span.textContent = ch === ' ' ? '\u00A0' : ch;
      span.style.animationDelay = delay + 'ms';
      delay += 38;
      lineEl.appendChild(span);
    });
    target.insertBefore(lineEl, sheen);
    delay += 120;
  });
})();

/* ===================== CONTADOR DE TIEMPO JUNTOS (en vivo) ===================== */
(function liveCounter(){
  const el = document.getElementById('days-counter');
  const start = new Date(CONFIG.startDate);
  if(isNaN(start.getTime())) return;
  function render(){
    const diff = Math.max(0, Date.now() - start.getTime());
    const days = Math.floor(diff / 86400000);
    const hours = Math.floor((diff % 86400000) / 3600000);
    const minutes = Math.floor((diff % 3600000) / 60000);
    el.textContent = `${days} días, ${hours} horas y ${minutes} minutos juntos`;
  }
  render();
  setInterval(render, 1000 * 30); // se actualiza solo, cada 30 segundos alcanza para que se sienta "en vivo"
})();

/* ===================== BIENVENIDA / CONTRASEÑA ===================== */
const pwInput = document.getElementById('pw-input');
const pwWrap = document.getElementById('pw-wrap');
const pwError = document.getElementById('pw-error');
const startBtn = document.getElementById('start-btn');
const welcome = document.getElementById('welcome');
const galaxy = document.getElementById('galaxy');
const musicCtrl = document.getElementById('music-ctrl');
const backBtn = document.getElementById('back-btn');
const secretTrigger = document.getElementById('secret-trigger');
const audio = document.getElementById('bg-audio');

let failedAttempts = 0;
function tryStart(){
  const val = pwInput.value.trim().toLowerCase();
  if(val === CONFIG.password.trim().toLowerCase()){
    pwError.classList.remove('show');
    ensureAudioCtx();
    playWhoosh();
    const rect = startBtn.getBoundingClientRect();
    spawnBurst(rect.left+rect.width/2, rect.top+rect.height/2, isMobile?24:42,
      ['rgba(231,183,104,ALPHA)','rgba(217,143,163,ALPHA)','rgba(244,238,252,ALPHA)']);
    document.getElementById('flash').classList.remove('fire'); void document.getElementById('flash').offsetWidth;
    document.getElementById('flash').classList.add('fire');
    welcome.classList.add('opening');
    buildBubbles();
    setTimeout(()=>{
      galaxy.classList.add('visible');
      musicCtrl.classList.add('show');
      backBtn.classList.add('show');
      secretTrigger.classList.add('show');
      welcome.style.display = 'none';
      startMusic();
    }, 950);
  } else {
    failedAttempts++;
    pwError.textContent = failedAttempts >= 3 ? CONFIG.passwordHint : 'esa no es… probá de nuevo';
    pwError.classList.add('show');
    pwWrap.classList.remove('shake'); void pwWrap.offsetWidth; pwWrap.classList.add('shake');
  }
}
startBtn.addEventListener('click', (e) => {
  const rect = startBtn.getBoundingClientRect();
  const ripple = document.createElement('span');
  ripple.className = 'ripple';
  const size = Math.max(rect.width, rect.height);
  ripple.style.width = ripple.style.height = size+'px';
  ripple.style.left = (e.clientX - rect.left - size/2)+'px';
  ripple.style.top = (e.clientY - rect.top - size/2)+'px';
  startBtn.appendChild(ripple);
  setTimeout(()=>ripple.remove(), 650);
  tryStart();
});
pwInput.addEventListener('keydown', e => { if(e.key === 'Enter') tryStart(); });

backBtn.addEventListener('click', () => {
  galaxy.classList.remove('visible');
  musicCtrl.classList.remove('show');
  backBtn.classList.remove('show');
  secretTrigger.classList.remove('show');
  audio.pause();
  pwInput.value = '';
  welcome.style.display = 'flex';
  welcome.classList.add('reentering');
  void welcome.offsetWidth;
  requestAnimationFrame(()=>{
    welcome.classList.remove('reentering');
    welcome.classList.remove('opening');
  });
});

/* ===================== BURBUJAS DE RECUERDOS ===================== */
let bubbleObjs = [];
let bubbleRAF = null;
let lastBubbleT = performance.now();
let openedSet = new Set();
let currentIndex = 0;
let financeShown = false;

function buildBubbles(){
  const fieldEl = document.getElementById('bubble-field');
  fieldEl.innerHTML = '';
  bubbleObjs = [];
  const w = window.innerWidth, h = window.innerHeight;
  const baseSize = isMobile ? 46 : 66;

  CONFIG.memories.forEach((mem, i) => {
    const el = document.createElement('div');
    const size = mem.big ? Math.round(baseSize*1.35) : baseSize;
    el.className = 'bubble' + (mem.big ? ' big' : '');
    el.style.setProperty('--size', size+'px');

    const halo = document.createElement('div'); halo.className = 'halo'; el.appendChild(halo);
    const bg = document.createElement('div'); bg.className = 'bg'; bg.style.backgroundImage = `url(${mem.photo})`; el.appendChild(bg);
    const tint = document.createElement('div'); tint.className = 'tint'; el.appendChild(tint);
    const glass = document.createElement('div'); glass.className = 'glass'; el.appendChild(glass);
    const label = document.createElement('div'); label.className = 'label'; label.textContent = mem.date; el.appendChild(label);

    const cols = isMobile ? 3 : 5;
    const rows = Math.ceil(CONFIG.memories.length / cols);
    const col = i % cols, row = Math.floor(i / cols);
    const cellW = w / cols, cellH = (h*0.72) / rows;
    const x = Math.max(10, Math.min(w-size-10, col*cellW + cellW/2 - size/2 + (Math.random()-0.5)*cellW*0.4));
    const y = Math.max(90, Math.min(h-size-20, h*0.20 + row*cellH + cellH/2 - size/2 + (Math.random()-0.5)*cellH*0.4));

    const speed = 0.0035 + Math.random()*0.0055;
    const obj = { el, x, y, size, speed, vx:0, vy:0, t:Math.random()*10000,
      phase:Math.random()*Math.PI*2, p1:Math.random()*Math.PI*2, p2:Math.random()*Math.PI*2, opened:false };

    el.addEventListener('click', () => openMemory(i));
    el.addEventListener('touchstart', () => { if(navigator.vibrate) navigator.vibrate(12); }, {passive:true});

    el.classList.add('entering');
    fieldEl.appendChild(el);
    bubbleObjs.push(obj);
    setTimeout(() => {
      el.classList.add('show');
      setTimeout(() => el.classList.remove('entering','show'), 700);
    }, 200 + i*110);
  });

  if(bubbleRAF) cancelAnimationFrame(bubbleRAF);
  lastBubbleT = performance.now();
  bubbleRAF = requestAnimationFrame(animateBubbles);
}

function animateBubbles(t){
  const dt = Math.min(60, t - lastBubbleT); lastBubbleT = t;
  const w = window.innerWidth, h = window.innerHeight;
  const cx = w*0.5, cy = h*0.56;
  for(const b of bubbleObjs){
    if(b.opened) continue;
    b.t += dt;
    const bMinX = w*0.06, bMaxX = w*0.94 - b.size;
    const bMinY = h*0.17, bMaxY = h*0.90 - b.size;

    const heading = b.phase + Math.sin(b.t*0.00016+b.p1)*1.15 + Math.sin(b.t*0.00041+b.p2)*0.55;
    let dvx = Math.cos(heading)*b.speed, dvy = Math.sin(heading)*b.speed;

    const bcx = b.x+b.size/2, bcy = b.y+b.size/2;
    const toCx = cx-bcx, toCy = cy-bcy;
    const distC = Math.hypot(toCx,toCy) || 1;
    const pull = Math.min(distC,420)*0.0000075;
    dvx += (toCx/distC)*pull; dvy += (toCy/distC)*pull;

    for(const other of bubbleObjs){
      if(other===b || other.opened) continue;
      const dx=b.x-other.x, dy=b.y-other.y;
      const dist=Math.hypot(dx,dy)||1;
      const minDist=(b.size+other.size)/2+20;
      if(dist<minDist){
        const push=(minDist-dist)/minDist;
        dvx += (dx/dist)*push*b.speed*2.4; dvy += (dy/dist)*push*b.speed*2.4;
      }
    }

    const margin = 150;
    const rL = Math.max(0, margin-(b.x-bMinX))/margin, rR = Math.max(0, margin-(bMaxX-b.x))/margin;
    const rT = Math.max(0, margin-(b.y-bMinY))/margin, rB = Math.max(0, margin-(bMaxY-b.y))/margin;
    dvx += (rL-rR)*b.speed*1.8; dvy += (rT-rB)*b.speed*1.8;

    const dmag = Math.hypot(dvx,dvy)||1; dvx = dvx/dmag*b.speed; dvy = dvy/dmag*b.speed;
    const turn = Math.min(1, 0.0028*dt);
    b.vx += (dvx-b.vx)*turn; b.vy += (dvy-b.vy)*turn;

    b.x += b.vx*dt; b.y += b.vy*dt;
    b.x = Math.max(bMinX, Math.min(bMaxX, b.x));
    b.y = Math.max(bMinY, Math.min(bMaxY, b.y));
    b.el.style.left = b.x+'px'; b.el.style.top = b.y+'px';
  }
  bubbleRAF = requestAnimationFrame(animateBubbles);
}

/* ===================== TARJETA DE RECUERDO ===================== */
const overlay = document.getElementById('card-overlay');
const cardImg = document.getElementById('card-img');
const cardDate = document.getElementById('card-date');
const cardPhrase = document.getElementById('card-phrase');
const cardChapter = document.getElementById('card-chapter');
const cardCounter = document.getElementById('card-counter');
const closeBtn = document.getElementById('close-btn');

function openMemory(index){
  currentIndex = index;
  const mem = CONFIG.memories[index];
  const obj = bubbleObjs[index];

  if(obj){
    const rect = obj.el.getBoundingClientRect();
    const cx = rect.left+rect.width/2, cy = rect.top+rect.height/2;
    spawnBurst(cx, cy, isMobile?14:22, ['rgba(231,183,104,ALPHA)','rgba(217,143,163,ALPHA)']);
    for(let i=0;i<4;i++){
      const h = document.createElement('div');
      h.className = 'mini-heart'; h.textContent = '❤';
      h.style.left = cx+'px'; h.style.top = cy+'px';
      h.style.setProperty('--hx', ((Math.random()-0.5)*70)+'px');
      h.style.animationDelay = (i*90)+'ms';
      document.body.appendChild(h);
      setTimeout(()=>h.remove(), 1300+i*90);
    }
    obj.opened = true; obj.el.classList.add('opened');
  }

  playBell();
  cardChapter.textContent = 'CAPÍTULO ' + String(index+1).padStart(2,'0');
  cardImg.src = mem.photo;
  cardDate.textContent = mem.date;
  cardPhrase.textContent = mem.phrase;
  cardCounter.textContent = `${index+1} de ${CONFIG.memories.length}`;
  overlay.classList.add('visible');
  openedSet.add(index);
}

function closeMemory(){
  overlay.classList.remove('visible');
  const obj = bubbleObjs[currentIndex];
  if(obj){ obj.opened = false; obj.el.classList.remove('opened'); }

  if(!financeShown && openedSet.size === CONFIG.memories.length){
    financeShown = true;
    setTimeout(showFinale, 500);
  }
}
closeBtn.addEventListener('click', closeMemory);
overlay.addEventListener('click', (e) => { if(e.target === overlay) closeMemory(); });

/* ===================== ESCENA FINAL ===================== */
const finale = document.getElementById('finale');
function showFinale(){
  finale.classList.add('visible');
  ['finale-l1','finale-l2','finale-l3'].forEach((id, i) => {
    setTimeout(()=> document.getElementById(id).classList.add('appear'), 300 + i*700);
  });
  let count = 0;
  const rain = setInterval(() => {
    if(count++ > 34){ clearInterval(rain); return; }
    const h = document.createElement('div');
    h.className = 'falling-heart'; h.textContent = Math.random()>0.5 ? '❤' : '✦';
    h.style.left = (Math.random()*100)+'vw';
    h.style.animationDuration = (3.5+Math.random()*2.5)+'s';
    h.style.opacity = (0.5+Math.random()*0.5).toFixed(2);
    document.body.appendChild(h);
    setTimeout(()=>h.remove(), 7000);
  }, 180);
}
document.getElementById('finale-btn').addEventListener('click', () => {
  finale.classList.remove('visible');
  ['finale-l1','finale-l2','finale-l3'].forEach(id => document.getElementById(id).classList.remove('appear'));
  openedSet = new Set();
  financeShown = false;
});

/* ===================== MÚSICA ===================== */
const muteBtn = document.getElementById('mute-btn');
const iconOn = document.getElementById('icon-on');
const iconOff = document.getElementById('icon-off');
const volSlider = document.getElementById('vol-slider');
let muted = false;

function startMusic(){
  if(!CONFIG.musicUrl) return;
  audio.src = CONFIG.musicUrl;
  audio.volume = volSlider.value/100;
  audio.play().then(()=> muteBtn.classList.add('playing')).catch(()=>{});
}
muteBtn.addEventListener('click', () => {
  muted = !muted; audio.muted = muted;
  iconOn.style.display = muted ? 'none' : 'block';
  iconOff.style.display = muted ? 'block' : 'none';
  muteBtn.classList.toggle('playing', !muted && !audio.paused);
  document.getElementById('music-ctrl').classList.toggle('expanded');
});
volSlider.addEventListener('input', () => {
  audio.volume = volSlider.value/100;
  const zero = volSlider.value == 0;
  muted = zero; audio.muted = zero;
  iconOn.style.display = zero ? 'none' : 'block';
  iconOff.style.display = zero ? 'block' : 'none';
  muteBtn.classList.toggle('playing', !zero);
});

/* ===================== MENSAJE SECRETO ===================== */
const secretModal = document.getElementById('secret-modal');
document.getElementById('secret-text').textContent = CONFIG.secretMessage;
secretTrigger.addEventListener('click', () => secretModal.classList.add('visible'));
document.getElementById('secret-close').addEventListener('click', () => secretModal.classList.remove('visible'));
secretModal.addEventListener('click', (e) => { if(e.target === secretModal) secretModal.classList.remove('visible'); });

/* reposicionar burbujas y re-inicializar el fondo si cambia el tamaño de pantalla */
window.addEventListener('resize', () => { if(galaxy.classList.contains('visible')) buildBubbles(); });
</script>
</body>
</html>
