[index.html](https://github.com/user-attachments/files/33344054/index.html)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#e8f3fb">
<title>Uma surpresa para você 💙 | Davi</title>
<style>
  :root { --sky:#e8f3fb; --blue:#8dbfe2; --deep:#497fa8; --cream:#fffaf1; --ink:#496477; }
  * { box-sizing:border-box; }
  body {
    margin:0; min-height:100vh; color:var(--ink); overflow-x:hidden;
    font-family: "Trebuchet MS", "Segoe UI", system-ui, sans-serif;
    background: linear-gradient(180deg,#dceefa 0%,#f6f8fb 52%,#fff7ed 100%);
  }
  .sky { position:fixed; inset:0; pointer-events:none; overflow:hidden; z-index:0; }
  .cloud { position:absolute; width:150px; height:46px; border-radius:50px; background:rgba(255,255,255,.78); filter:drop-shadow(0 8px 12px #8dbfe222); }
  .cloud:before,.cloud:after { content:""; position:absolute; background:inherit; border-radius:50%; }
  .cloud:before { width:65px;height:65px;left:20px;top:-28px; }
  .cloud:after { width:80px;height:80px;left:62px;top:-39px; }
  .c1 { top:9%;left:-45px; transform:scale(.8); }
  .c2 { top:20%;right:-35px; transform:scale(1.05); }
  .c3 { bottom:13%;left:3%;transform:scale(.65); }
  .c4 { bottom:8%;right:2%;transform:scale(.75); }
  main { position:relative; z-index:1; width:min(92%,540px); margin:0 auto; padding:28px 0 36px; text-align:center; }
  .eyebrow { display:inline-block; padding:8px 14px; border:1px solid #ffffffb8; border-radius:999px; background:#ffffffa6; font-size:.78rem; letter-spacing:.09em; text-transform:uppercase; }
  h1 { font-family: Georgia,serif; font-weight:500; font-size:clamp(2rem,7vw,3.1rem); line-height:1.08; margin:17px 0 10px; color:#4d789a; }
  .subtitle { max-width:390px; margin:0 auto; line-height:1.6; font-size:1rem; }
  .bear-wrap { margin:22px auto 10px; width:118px; height:112px; display:grid; place-items:center; }
  .bear { font-size:5.2rem; filter:drop-shadow(0 8px 5px #557a9b1c); animation:float 3s ease-in-out infinite; }
  @keyframes float { 0%,100%{transform:translateY(0) rotate(-2deg)} 50%{transform:translateY(-7px) rotate(2deg)} }
  .card { background:#ffffffd9; border:1px solid #fff; border-radius:28px; padding:20px; box-shadow:0 18px 55px #527b9820; backdrop-filter:blur(8px); }
  .scratch-label { font-weight:700; margin:0 0 12px; }
  .scratch-box { position:relative; width:100%; height:245px; border-radius:22px; overflow:hidden; background:linear-gradient(145deg,#e3f1fb,#f9fcff); border:2px solid #d6e8f5; touch-action:none; }
  .reveal { position:absolute; inset:0; display:flex; flex-direction:column; align-items:center; justify-content:center; padding:20px; background:radial-gradient(circle at 50% 35%,#fff 0,#e6f4ff 60%,#d4e9f8 100%); }
  .reveal .small { font-size:.92rem; letter-spacing:.12em; text-transform:uppercase; }
  .reveal .big { margin:8px 0; font-family:Georgia,serif; font-size:clamp(2.5rem,10vw,3.8rem); line-height:1; color:#3979aa; font-weight:bold; }
  .reveal .baby { font-size:3rem; margin-bottom:4px; }
  #scratch { position:absolute; inset:0; width:100%; height:100%; cursor:crosshair; touch-action:none; }
  .instruction { margin:14px 0 0; font-size:.91rem; color:#668094; }
  .progress { height:6px; margin:14px 0 0; background:#e8eff4; border-radius:99px; overflow:hidden; }
  .progress > div { width:0%; height:100%; background:#7eb4dc; transition:width .2s; }
  .after { display:none; margin-top:18px; animation:appear .7s ease both; }
  .after.show { display:block; }
  .after h2 { color:#3e7da9; font: bold 1.8rem Georgia,serif; margin:0 0 8px; }
  .after p { line-height:1.6; margin:0; }
  .actions { display:flex; flex-wrap:wrap; justify-content:center; gap:10px; margin-top:18px; }
  button { border:0; border-radius:999px; padding:12px 17px; font-weight:700; font-size:.95rem; cursor:pointer; }
  .primary { background:#5f9dca; color:white; box-shadow:0 6px 16px #5f9dca40; }
  .secondary { background:#edf5fa; color:#4b7898; }
  .foot { margin-top:22px; font-size:.78rem; opacity:.75; }
  .confetti { position:fixed; top:-15px; z-index:5; pointer-events:none; animation:fall linear forwards; }
  @keyframes fall { to { transform:translateY(110vh) rotate(720deg); opacity:.2; } }
  @keyframes appear { from {opacity:0; transform:translateY(12px)} to {opacity:1;transform:translateY(0)} }
  @media (max-width:380px) { main{width:94%;padding-top:20px}.card{padding:14px}.scratch-box{height:220px} }
  @media (prefers-reduced-motion:reduce) { *,*::before,*::after { animation-duration:.01ms!important; transition-duration:.01ms!important; } }
</style>
</head>
<body>
<div class="sky" aria-hidden="true">
  <div class="cloud c1"></div><div class="cloud c2"></div><div class="cloud c3"></div><div class="cloud c4"></div>
</div>
<main>
  <div class="eyebrow">Um momento cheio de amor</div>
  <h1>Uma surpresa<br>está esperando por você</h1>
  <p class="subtitle">Preparamos um jeitinho especial de compartilhar uma notícia muito importante. Raspe o cartão e descubra!</p>
  <div class="bear-wrap" aria-hidden="true"><div class="bear">🧸</div></div>
  <section class="card">
    <p class="scratch-label">✨ Raspe aqui para revelar ✨</p>
    <div class="scratch-box" id="scratchBox" aria-label="Raspadinha virtual. Raspe com o dedo ou mouse para revelar a mensagem.">
      <div class="reveal">
        <div class="baby">👶🏻 💙</div>
        <div class="small">A família vai ganhar</div>
        <div class="big">UM MENINO!</div>
        <div>Nosso amado Davi está chegando!</div>
      </div>
      <canvas id="scratch"></canvas>
    </div>
    <p class="instruction" id="instruction">Use o dedo ou o mouse para raspar a camada azul.</p>
    <div class="progress" aria-hidden="true"><div id="progressBar"></div></div>
    <div class="after" id="after">
      <h2>É MENINO! 💙</h2>
      <p>O Davi está a caminho! Que a vida dele seja repleta de amor, saúde e momentos inesquecíveis. Obrigado por fazer parte dessa alegria! ☁️🧸</p>
      <div class="actions">
        <button class="primary" id="shareBtn">Compartilhar alegria</button>
        <button class="secondary" id="againBtn">Ver de novo</button>
      </div>
    </div>
  </section>
  <div class="foot">Feito com carinho para celebrar a chegada do Davi 💙</div>
</main>
<script>
(() => {
  const canvas = document.getElementById('scratch');
  const ctx = canvas.getContext('2d', { willReadFrequently: true });
  const box = document.getElementById('scratchBox');
  const progressBar = document.getElementById('progressBar');
  const after = document.getElementById('after');
  const instruction = document.getElementById('instruction');
  let drawing = false, revealed = false, lastCheck = 0;
  const brush = 27;

  function paintCover() {
    const rect = box.getBoundingClientRect();
    const dpr = Math.max(1, window.devicePixelRatio || 1);
    canvas.width = Math.round(rect.width * dpr);
    canvas.height = Math.round(rect.height * dpr);
    canvas.style.width = rect.width + 'px';
    canvas.style.height = rect.height + 'px';
    ctx.setTransform(dpr,0,0,dpr,0,0);
    const w = rect.width, h = rect.height;
    const grad = ctx.createLinearGradient(0,0,w,h);
    grad.addColorStop(0,'#b7d9f0');
    grad.addColorStop(.5,'#8dbfe2');
    grad.addColorStop(1,'#c8e3f5');
    ctx.globalCompositeOperation = 'source-over';
    ctx.fillStyle = grad;
    ctx.fillRect(0,0,w,h);
    // soft cloud-like shapes and decorative stars
    for (let i=0;i<11;i++) {
      const x = (i*73+24)%w, y = (i*47+22)%h;
      ctx.fillStyle = 'rgba(255,255,255,.22)';
      ctx.beginPath(); ctx.arc(x,y,10+(i%3)*4,0,Math.PI*2); ctx.fill();
    }
    ctx.fillStyle = 'rgba(255,255,255,.92)';
    ctx.textAlign = 'center';
    ctx.font = '26px Georgia, serif';
    ctx.fillText('✦     ✧     ✦',w/2,h/2-10);
    ctx.font = 'bold 18px Trebuchet MS, sans-serif';
    ctx.fillText('RASPE PARA DESCOBRIR',w/2,h/2+25);
    ctx.font = '13px Trebuchet MS, sans-serif';
    ctx.fillText('uma surpresa cheia de amor',w/2,h/2+48);
    ctx.globalCompositeOperation = 'destination-out';
    progressBar.style.width = '0%';
    after.classList.remove('show');
    instruction.textContent = 'Use o dedo ou o mouse para raspar a camada azul.';
    revealed = false;
  }
  function coords(e) {
    const r = canvas.getBoundingClientRect();
    return { x:e.clientX-r.left, y:e.clientY-r.top };
  }
  function scratch(e) {
    if (!drawing || revealed) return;
    const p = coords(e);
    ctx.globalCompositeOperation = 'destination-out';
    ctx.beginPath();
    ctx.arc(p.x,p.y,brush,0,Math.PI*2);
    ctx.fill();
    const now = Date.now();
    if (now-lastCheck > 180) { lastCheck=now; checkProgress(); }
  }
  function checkProgress() {
    if (revealed) return;
    const w = canvas.width, h = canvas.height;
    const data = ctx.getImageData(0,0,w,h).data;
    let clear = 0, sample = 0;
    // Sample alpha values to estimate how much has been scratched.
    const step = 32;
    for (let i=3;i<data.length;i+=4*step) { sample++; if (data[i] < 40) clear++; }
    const pct = sample ? Math.round(clear/sample*100) : 0;
    progressBar.style.width = Math.min(100,pct)+'%';
    if (pct > 42) revealAll();
  }
  function revealAll() {
    if (revealed) return;
    revealed = true;
    ctx.clearRect(0,0,canvas.width,canvas.height);
    canvas.style.transition = 'opacity .45s ease';
    canvas.style.opacity = '0';
    setTimeout(() => { canvas.style.display='none'; }, 480);
    progressBar.style.width='100%';
    instruction.textContent='Surpresa revelada! 💙';
    after.classList.add('show');
    confetti();
  }
  canvas.addEventListener('pointerdown', e => {
    if (revealed) return;
    drawing=true;
    try { canvas.setPointerCapture(e.pointerId); } catch (_) {}
    scratch(e);
  });
  canvas.addEventListener('pointermove', scratch);
  ['pointerup','pointercancel','lostpointercapture'].forEach(ev => canvas.addEventListener(ev,()=>drawing=false));
  document.getElementById('againBtn').addEventListener('click',()=>{
    canvas.style.display='block'; canvas.style.opacity='1'; canvas.style.transition='';
    paintCover();
  });
  document.getElementById('shareBtn').addEventListener('click', async()=>{
    const text='É MENINO! 💙 O Davi está a caminho! Que venha cheio de saúde e amor!';
    if (navigator.share) {
      try { await navigator.share({title:'A revelação do Davi',text,url:location.href}); } catch(e) {}
    } else if (navigator.clipboard && window.isSecureContext) {
      try { await navigator.clipboard.writeText(text+' '+location.href); alert('Mensagem copiada! Agora é só colar no WhatsApp.'); }
      catch(e) { prompt('Copie a mensagem abaixo:',text+' '+location.href); }
    } else { prompt('Copie a mensagem abaixo:',text+' '+location.href); }
  });
  function confetti() {
    const symbols=['💙','☁️','✨','🩵','🤍'];
    for(let i=0;i<34;i++){
      const el=document.createElement('div');
      el.className='confetti';
      el.textContent=symbols[Math.floor(Math.random()*symbols.length)];
      el.style.left=Math.random()*100+'vw';
      el.style.fontSize=(14+Math.random()*16)+'px';
      el.style.animationDuration=(2.4+Math.random()*2.6)+'s';
      el.style.animationDelay=(Math.random()*.6)+'s';
      document.body.appendChild(el);
      setTimeout(()=>el.remove(),6000);
    }
  }
  paintCover();
  window.addEventListener('resize',()=>{ if(!revealed) paintCover(); });
})();
</script>
</body>
</html>
