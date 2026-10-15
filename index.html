<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#f2e8d8">
<title>O segredo do neném</title>
<style>
:root{--cream:#f5eee3;--beige:#e8d9c5;--brown:#765c46;--brown2:#9b8066;--line:#d3bea4;--blue:#b9def2;--blueInk:#28658c;--pink:#f4cbd7;--pinkInk:#a94f6b}
*{box-sizing:border-box}
body{margin:0;min-height:100vh;background:radial-gradient(ellipse at top,#fffaf2 0%,var(--cream) 58%,#e9dbc8 100%);color:var(--brown);font-family:"Trebuchet MS",Arial,sans-serif;overflow-x:hidden}
.decor{position:fixed;inset:0;pointer-events:none;overflow:hidden;opacity:.42}
.cloud{position:absolute;font-size:3rem;color:#c8b49c}.cloud.one{top:8%;left:4%}.cloud.two{top:23%;right:3%;font-size:2.3rem}.cloud.three{bottom:8%;left:6%;font-size:2.5rem}.cloud.four{bottom:15%;right:5%;font-size:3rem}
main{position:relative;width:min(92%,480px);margin:auto;padding:25px 0 32px;text-align:center}
.pill{display:inline-block;border:1px solid #d8c6af;background:#fff9f0b8;border-radius:999px;padding:8px 14px;font-size:.75rem;letter-spacing:.11em;text-transform:uppercase;color:#8c7259}
h1{font-family:Georgia,serif;font-weight:500;font-size:clamp(2rem,8vw,3rem);line-height:1.08;margin:17px 0 10px;color:#765c46}
.subtitle{max-width:360px;margin:0 auto;line-height:1.55;font-size:.98rem;color:#8a715a}
.bear{font-size:3.3rem;margin:10px 0 4px;filter:drop-shadow(0 5px 4px #8d72531c);animation:float 3s ease-in-out infinite}
@keyframes float{50%{transform:translateY(-5px) rotate(2deg)}}
.panel{margin-top:10px;background:#fffaf2d9;border:1px solid #e4d5c2;border-radius:26px;padding:18px 16px 17px;box-shadow:0 16px 42px #8b6c4817}
.label{font-weight:700;margin:0 0 7px;font-size:1rem}.hint{font-size:.85rem;color:#9b8066;margin:0 0 14px;line-height:1.45}
.board{width:min(100%,360px);margin:0 auto;display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:7px;touch-action:pan-y}
.cell{position:relative;aspect-ratio:1;border:1px solid #d9c5aa;border-radius:13px;overflow:hidden;background:#f5e9d8;box-shadow:inset 0 0 0 2px #fff8ed}
.under{position:absolute;inset:0;display:grid;place-items:center;font-size:clamp(2.4rem,13vw,4.2rem);font-family:Georgia,serif;font-weight:bold;user-select:none}
.under.blue{background:linear-gradient(145deg,#d7effb,var(--blue));color:var(--blueInk)}
.under.pink{background:linear-gradient(145deg,#fbe3e9,var(--pink));color:var(--pinkInk)}
.cover{position:absolute;inset:0;width:100%;height:100%;touch-action:none;cursor:crosshair}
.cell.done{border-color:#c2a98b;box-shadow:0 0 0 2px #fff7ec,0 3px 8px #9b806622}
.progress-wrap{height:6px;background:#eadfce;border-radius:99px;overflow:hidden;margin:15px auto 0;max-width:360px}
.progress{height:100%;width:0;background:#b69a78;transition:width .25s}
.status{min-height:24px;margin:10px 0 0;font-size:.87rem;color:#94795f}
.result{display:none;margin-top:17px;padding:17px 12px;background:#f4e7d5;border:1px solid #ddc8ad;border-radius:18px;animation:appear .65s ease both}
.result.show{display:block}.result .emoji{font-size:2.4rem}.result h2{font: bold 1.8rem Georgia,serif;color:#765c46;margin:5px 0 8px}.result p{margin:0;line-height:1.55;color:#8a7058;font-size:.94rem}
.buttons{display:flex;justify-content:center;gap:9px;flex-wrap:wrap;margin-top:14px}
button{border:0;border-radius:999px;padding:11px 16px;font-size:.9rem;font-weight:700;cursor:pointer}
.primary{background:#8a7058;color:#fffaf2}.secondary{background:#eee0ce;color:#765c46}
.foot{margin-top:18px;font-size:.77rem;color:#9b8066}
@keyframes appear{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:translateY(0)}}
.confetti{position:fixed;top:-20px;z-index:10;pointer-events:none;animation:fall linear forwards}
@keyframes fall{to{transform:translateY(110vh) rotate(700deg);opacity:.1}}
@media(max-width:360px){main{width:94%;padding-top:18px}.panel{padding:14px 10px}.board{gap:5px}.cell{border-radius:10px}}
@media(prefers-reduced-motion:reduce){*,*::before,*::after{animation-duration:.01ms!important;transition-duration:.01ms!important}}
</style>
</head>
<body>
<div class="decor" aria-hidden="true"><div class="cloud one">☁</div><div class="cloud two">☁</div><div class="cloud three">✦</div><div class="cloud four">☁</div></div>
<main>
  <div class="pill">Um momento cheio de amor</div>
  <h1>O grande segredo<br>do neném</h1>
  <p class="subtitle">A família está convidada para descobrir uma surpresa muito especial. Raspe os quadradinhos e encontre três símbolos iguais em uma linha!</p>
  <div class="bear" aria-hidden="true">🧸</div>
  <section class="panel">
    <p class="label">✨ Raspadinha jogo da velha ✨</p>
    <p class="hint">Raspe cada casa com o dedo ou com o mouse.<br>Será que você encontra a combinação vencedora?</p>
    <div class="board" id="board" aria-label="Tabuleiro de jogo da velha com nove raspadinhas"></div>
    <div class="progress-wrap" aria-hidden="true"><div class="progress" id="progress"></div></div>
    <p class="status" id="status" aria-live="polite">0 de 9 casas reveladas</p>
    <div class="result" id="result">
      <div class="emoji">🧸 ☁️ ✨</div>
      <h2>É MENINO!</h2>
      <p>Nosso amado neném está chegando! Que sua vida seja repleta de amor, saúde e momentos inesquecíveis. Obrigado por fazer parte dessa alegria!</p>
      <div class="buttons"><button class="primary" id="share">Compartilhar alegria</button><button class="secondary" id="again">Jogar novamente</button></div>
    </div>
  </section>
  <div class="foot">Feito com muito carinho para celebrar a chegada do neném 🤎</div>
</main>
<script>
(() => {
 const board=document.getElementById('board'), status=document.getElementById('status'), progress=document.getElementById('progress'), result=document.getElementById('result');
 // A coluna central contém a combinação vencedora vertical. As cores aparecem somente dentro do tabuleiro.
 const layout=[
  {symbol:'O',tone:'pink'}, {symbol:'X',tone:'blue'}, {symbol:'O',tone:'pink'},
  {symbol:'O',tone:'pink'}, {symbol:'X',tone:'blue'}, {symbol:'X',tone:'blue'},
  {symbol:'X',tone:'blue'}, {symbol:'X',tone:'blue'}, {symbol:'O',tone:'pink'}
 ];
 let cells=[], revealedCount=0, finished=false;
 function build(){
   board.innerHTML=''; cells=[]; revealedCount=0; finished=false; result.classList.remove('show');
   layout.forEach((item,i)=>{
     const cell=document.createElement('div'); cell.className='cell';
     const under=document.createElement('div'); under.className='under '+item.tone; under.textContent=item.symbol; under.setAttribute('aria-hidden','true');
     const canvas=document.createElement('canvas'); canvas.className='cover'; canvas.setAttribute('aria-label',`Raspar casa ${i+1}`);
     cell.append(under,canvas); board.append(cell);
     const ctx=canvas.getContext('2d',{willReadFrequently:true});
     const state={cell,canvas,ctx,item,done:false,drawing:false,lastCheck:0}; cells.push(state);
     paint(state);
     canvas.addEventListener('pointerdown',e=>{if(state.done||finished)return;state.drawing=true;try{canvas.setPointerCapture(e.pointerId)}catch(_){};scratch(state,e)});
     canvas.addEventListener('pointermove',e=>scratch(state,e));
     ['pointerup','pointercancel','lostpointercapture'].forEach(ev=>canvas.addEventListener(ev,()=>state.drawing=false));
   });
   updateStatus();
 }
 function paint(s){
   const rect=s.cell.getBoundingClientRect(), dpr=Math.max(1,window.devicePixelRatio||1);
   s.canvas.width=Math.round(rect.width*dpr);s.canvas.height=Math.round(rect.height*dpr);
   s.canvas.style.width=rect.width+'px';s.canvas.style.height=rect.height+'px';
   s.ctx.setTransform(dpr,0,0,dpr,0,0);
   const w=rect.width,h=rect.height, g=s.ctx.createLinearGradient(0,0,w,h);
   g.addColorStop(0,'#f8efe2');g.addColorStop(.55,'#ead9c2');g.addColorStop(1,'#f3e6d4');
   s.ctx.globalCompositeOperation='source-over';s.ctx.fillStyle=g;s.ctx.fillRect(0,0,w,h);
   s.ctx.fillStyle='rgba(151,120,86,.15)';
   for(let n=0;n<9;n++){const x=(n*31+13)%w,y=(n*23+17)%h;s.ctx.beginPath();s.ctx.arc(x,y,2+(n%3),0,Math.PI*2);s.ctx.fill()}
   s.ctx.fillStyle='#8b7056';s.ctx.textAlign='center';s.ctx.font='bold 12px Trebuchet MS, sans-serif';s.ctx.fillText('RASPE',w/2,h/2+4);
   s.ctx.globalCompositeOperation='destination-out';
 }
 function scratch(s,e){
   if(!s.drawing||s.done||finished)return;
   const r=s.canvas.getBoundingClientRect(),x=e.clientX-r.left,y=e.clientY-r.top;
   s.ctx.globalCompositeOperation='destination-out';s.ctx.beginPath();s.ctx.arc(x,y,17,0,Math.PI*2);s.ctx.fill();
   if(Date.now()-s.lastCheck>140){s.lastCheck=Date.now();check(s)}
 }
 function check(s){
   if(s.done)return;
   const data=s.ctx.getImageData(0,0,s.canvas.width,s.canvas.height).data;
   let clear=0,total=0;
   for(let i=3;i<data.length;i+=4*16){total++;if(data[i]<40)clear++}
   if(total&&clear/total>.43)revealCell(s);
 }
 function revealCell(s){
   if(s.done)return;s.done=true;s.cell.classList.add('done');s.canvas.style.display='none';revealedCount++;updateStatus();
   // A vitória é uma coluna vertical de três X azuis (casas 2, 5 e 8).
   if([1,4,7].every(i=>cells[i]&&cells[i].done&&cells[i].item.symbol==='X'))finish();
 }
 function updateStatus(){status.textContent=finished?'Combinação encontrada! 🎉':`${revealedCount} de 9 casas reveladas`;progress.style.width=(revealedCount/9*100)+'%'}
 function finish(){
   finished=true;status.textContent='Você encontrou a combinação vencedora!';result.classList.add('show');confetti();
 }
 function confetti(){
   const bits=['🤎','☁️','✨','🧸','🎉'];
   for(let i=0;i<34;i++){const el=document.createElement('div');el.className='confetti';el.textContent=bits[Math.floor(Math.random()*bits.length)];el.style.left=Math.random()*100+'vw';el.style.fontSize=(14+Math.random()*15)+'px';el.style.animationDuration=(2.5+Math.random()*2.3)+'s';el.style.animationDelay=(Math.random()*.5)+'s';document.body.appendChild(el);setTimeout(()=>el.remove(),5700)}
 }
 document.getElementById('again').addEventListener('click',build);
 document.getElementById('share').addEventListener('click',async()=>{
   const message='É MENINO! Nosso amado neném está chegando! 🤎';
   if(navigator.share){try{await navigator.share({title:'A revelação do neném',text:message,url:location.href})}catch(e){}}
   else if(navigator.clipboard&&window.isSecureContext){try{await navigator.clipboard.writeText(message+' '+location.href);alert('Mensagem copiada! Agora é só colar no WhatsApp.')}catch(e){prompt('Copie a mensagem:',message+' '+location.href)}}
   else prompt('Copie a mensagem:',message+' '+location.href);
 });
 build();
 window.addEventListener('resize',()=>{if(!finished)build()});
})();
</script>
</body>
</html>
