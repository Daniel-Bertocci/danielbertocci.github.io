# danielbertocci.github.io<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Your Name</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Archivo:wdth,wght@62..125,100..900&display=swap" rel="stylesheet">
<style>
:root{--bg:#070a12;--fg:#eceef7;--dim:#8791ad;--line:rgba(150,165,220,.16);--lamp:#ff9a3c;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);color-scheme:dark}
html{scroll-behavior:smooth;scroll-padding-top:70px}
*,*::before,*::after{box-sizing:inherit}
body{margin:0;background:var(--bg);color:var(--fg);font-family:'Archivo',system-ui,sans-serif;line-height:1.55;overflow-x:hidden}
a{color:inherit;text-decoration:none}
:focus-visible{outline:2px solid var(--lamp);outline-offset:3px}
nav{position:fixed;top:env(safe-area-inset-top,0px);left:0;right:0;z-index:10;display:flex;justify-content:space-between;align-items:center;padding:18px clamp(20px,5vw,64px);
background:linear-gradient(var(--bg),transparent)}
nav .logo{font-weight:700;font-stretch:90%}
nav div{display:flex;gap:1.6rem}
nav a{color:var(--dim);transition:color .25s}
nav a:hover{color:var(--lamp)}
.hero{position:relative;height:100svh;min-height:560px;overflow:hidden;cursor:crosshair}
#c{position:absolute;inset:0;width:100%;height:100%}
.hero .txt{position:absolute;left:clamp(20px,5vw,64px);top:20vh;pointer-events:none;z-index:2}
.hero h1{margin:0;font-size:clamp(2.8rem,9vw,7.5rem);line-height:.95;font-weight:800;font-stretch:75%;letter-spacing:-.02em;transition:font-stretch .8s cubic-bezier(.2,.8,.2,1);background:linear-gradient(100deg,#ffe29a,#ff8a3d 55%,#ff5f6d);-webkit-background-clip:text;background-clip:text;color:transparent;padding-bottom:.08em}
.hero.rev h1{font-stretch:118%}
.hero p{margin:1rem 0 1.6rem;color:var(--dim);font-size:clamp(1rem,2vw,1.3rem)}
.hero .cta{pointer-events:auto;display:inline-block;border-bottom:1px solid var(--lamp);color:var(--lamp);padding-bottom:2px;transition:letter-spacing .3s}
.hero .cta:hover{letter-spacing:.06em}
.hint{position:absolute;right:clamp(20px,5vw,64px);bottom:22px;color:var(--dim);font-size:.85rem;z-index:2;pointer-events:none}
.wrap{max-width:900px;margin:0 auto;padding:0 clamp(20px,5vw,40px)}
h2{font-size:1.1rem;font-weight:600;color:var(--dim);margin:0 0 1.2rem}
#work{padding:12vh 0 6vh}
.filters{display:flex;gap:1.2rem;margin-bottom:1.4rem}
.filters button{background:none;border:0;padding:0 0 3px;font:inherit;color:var(--dim);cursor:pointer;border-bottom:1px solid transparent;transition:color .25s,border-color .25s}
.filters button:hover{color:var(--fg)}
.filters button[aria-pressed=true]{color:var(--c);border-color:var(--c)}
.proj{border-top:1px solid var(--line);transition:opacity .4s}
.proj:last-child{border-bottom:1px solid var(--line)}
.proj.hide{display:none}
.proj button{all:unset;box-sizing:border-box;width:100%;display:flex;align-items:baseline;gap:1rem;padding:1.1rem 0;cursor:pointer}
.proj .pl{font-size:1.3rem;color:var(--c,var(--lamp));width:1.2rem;transition:transform .4s cubic-bezier(.2,.8,.2,1)}
.proj .nm{font-size:clamp(1.2rem,3vw,1.7rem);font-weight:700;font-stretch:80%;transition:transform .35s cubic-bezier(.2,.8,.2,1),font-stretch .5s}
.proj .ds{color:var(--dim);margin-left:auto;text-align:right}
.proj button:hover .nm,.proj button:focus-visible .nm{transform:translateX(10px);font-stretch:105%;color:var(--c,var(--lamp))}
.proj.open .pl{transform:rotate(45deg)}
.more{display:grid;grid-template-rows:0fr;transition:grid-template-rows .5s cubic-bezier(.2,.8,.2,1)}
.proj.open .more{grid-template-rows:1fr}
.more>div{overflow:hidden}
.more p{margin:0 0 1.2rem 2.2rem;color:var(--dim);max-width:56ch}
#about{padding:6vh 0}
.abt{border-top:1px solid var(--line);border-bottom:1px solid var(--line)}
.abt button{all:unset;box-sizing:border-box;width:100%;display:flex;gap:1rem;padding:1.1rem 0;cursor:pointer;font-size:1.3rem;font-weight:700;font-stretch:80%}
.abt .pl{color:var(--lamp);transition:transform .4s}
.abt.open .pl{transform:rotate(45deg)}
.abt .more p{margin-left:2.2rem;color:var(--fg);font-size:1.05rem}
.ext{padding:6vh 0}
.ext a{display:flex;justify-content:space-between;gap:1rem;padding:.9rem 0;border-top:1px solid var(--line);transition:padding .3s,color .3s}
.ext a:last-child{border-bottom:1px solid var(--line)}
.ext a span{color:var(--dim)}
.ext a:hover{color:var(--lamp);padding-left:12px}
footer{padding:6vh 0 10vh;color:var(--dim);font-size:.9rem;display:flex;justify-content:space-between}
footer a:hover{color:var(--lamp)}
@media(max-width:600px){.proj .ds{display:none}nav div{gap:1rem}.hero .txt{top:16vh}}
@media(prefers-reduced-motion:reduce){*{transition-duration:.01ms!important;scroll-behavior:auto!important}}
</style>
</head>
<body>
<nav id="top"><a class="logo" href="#top">Your Name</a>
<div><a href="#work">projects</a><a href="#about">about</a><a href="#contact">contact</a></div></nav>

<header class="hero" id="hero">
  <canvas id="c" aria-label="Animated ASCII campsite with a tent and campfire under the stars"></canvas>
  <div class="txt">
    <h1>Your Name</h1>
    <p>Cars, computers and the outdoors.</p>
    <a class="cta" href="#work">View projects ↓</a>
  </div>
  <div class="hint">click to stoke the fire</div>
</header>

<section id="work"><div class="wrap">
  <h2>Projects</h2>
  <div class="filters" role="group" aria-label="Filter projects">
    <button aria-pressed="true" data-f="all">all</button><button aria-pressed="false" data-f="cars">cars</button><button aria-pressed="false" data-f="code">code</button><button aria-pressed="false" data-f="outdoors">outdoors</button>
  </div>
  <div id="list">
    <div class="proj" data-t="cars code"><button aria-expanded="false"><span class="pl">+</span><span class="nm">Garage Log</span><span class="ds">car maintenance tracker</span></button><div class="more"><div><p>Replace with a short description: what it does, who it's for, and what you built it with.</p></div></div></div>
    <div class="proj" data-t="code"><button aria-expanded="false"><span class="pl">+</span><span class="nm">Personal Website</span><span class="ds">this site · ascii campsite</span></button><div class="more"><div><p>A hand-built page with a live ASCII scene. Click it to stoke the campfire.</p></div></div></div>
    <div class="proj" data-t="code"><button aria-expanded="false"><span class="pl">+</span><span class="nm">Home Server</span><span class="ds">self-hosted lab</span></button><div class="more"><div><p>Describe your setup: hardware, what it runs, what you learned.</p></div></div></div>
    <div class="proj" data-t="cars code"><button aria-expanded="false"><span class="pl">+</span><span class="nm">Track Day Timer</span><span class="ds">lap data viewer</span></button><div class="more"><div><p>Describe how you capture laps and what the charts show.</p></div></div></div>
    <div class="proj" data-t="outdoors code"><button aria-expanded="false"><span class="pl">+</span><span class="nm">Trail Planner</span><span class="ds">routes &amp; gear lists</span></button><div class="more"><div><p>A tool for planning trips: distance, elevation, and what to pack.</p></div></div></div>
    <div class="proj" data-t="cars"><button aria-expanded="false"><span class="pl">+</span><span class="nm">Weekend Builds</span><span class="ds">repairs &amp; upgrades</span></button><div class="more"><div><p>Add the jobs you've done on your car, with a photo or two.</p></div></div></div>
    <div class="proj" data-t="outdoors"><button aria-expanded="false"><span class="pl">+</span><span class="nm">Summit Log</span><span class="ds">hikes &amp; camps</span></button><div class="more"><div><p>Your favorite trails, where they are, and why they stuck with you.</p></div></div></div>
  </div>
</div></section>

<section id="about"><div class="wrap">
  <div class="abt"><button aria-expanded="false"><span class="pl">+</span>About me</button>
  <div class="more"><div><p>Replace this with a few sentences: where you're based, what you study or do for work, and what you love. I love cars, computers, and getting outside, and I like working out how things fit together.</p></div></div></div>
</div></section>

<section class="ext" id="contact"><div class="wrap">
  <h2>Elsewhere</h2>
  <a href="#"><b>Resume</b><span>one-page PDF</span></a>
  <a href="#"><b>GitHub</b><span>username</span></a>
  <a href="#"><b>Instagram</b><span>@handle</span></a>
  <a href="mailto:you@example.com"><b>Email</b><span>you@example.com</span></a>
  <footer><span>© 2026 Your Name · City, ST</span><a href="#top">back to top ↑</a></footer>
</div></section>

<script>
(function(){
const reduce=matchMedia('(prefers-reduced-motion: reduce)').matches;
const hero=document.getElementById('hero'),cv=document.getElementById('c'),ctx=cv.getContext('2d');
let W,H,cols,rows,cw=10,ch=16,dpr=1,mx=-999,my=-999,px=0,speed=1,boost=0,t=0;
function size(){
  dpr=Math.min(devicePixelRatio||1,2);W=hero.clientWidth;H=hero.clientHeight;
  cv.width=W*dpr;cv.height=H*dpr;ctx.setTransform(dpr,0,0,dpr,0,0);
  cw=W<600?8:10;ch=Math.round(cw*1.6);cols=Math.ceil(W/cw);rows=Math.ceil(H/ch);
  ctx.font=cw*1.6*.82+'px ui-monospace,Menlo,Consolas,monospace';ctx.textBaseline='top';
}
size();addEventListener('resize',()=>{size();frame(0)});
const layers=[{ch:'.',h:.56,amp:.11,sp:.3,f:.018,s:1,c:'#5566aa'},{ch:':',h:.64,amp:.10,sp:.8,f:.03,s:4,c:'#40508a'},{ch:'#',h:.72,amp:.06,sp:1.6,f:.05,s:9,c:'#2c3a66'}];
const stars=[];for(let i=0;i<90;i++)stars.push([Math.random(),Math.random()*.38,Math.random()*6]);
const sparks=[];
function ridge(L,x){const u=(x+px*L.sp)*L.f;
  return Math.round(rows*(L.h-L.amp*(Math.sin(u+L.s)*.55+Math.sin(u*2.3+L.s*2)*.3+Math.sin(u*5.1+L.s)*.15)));}
function frame(dt){
  t+=dt;boost*=.97;
  px+=((mx>=0?(mx/W-.5)*60:0)-px)*.05;
  ctx.clearRect(0,0,W,H);
  const g=[],k=[];for(let r=0;r<rows;r++){g.push(new Array(cols).fill(' '));k.push(new Array(cols).fill(''))}
  const put=(r,c,ch,col)=>{if(r>=0&&r<rows&&c>=0&&c<cols){g[r][c]=ch;k[r][c]=col}};
  stars.forEach(s=>{const tw=Math.sin(t*.003+s[2])>.1;put(Math.floor(s[1]*rows),Math.floor(s[0]*cols),tw?'*':'.',tw?'#d4e6ff':'#6f7fb0')});
  const mc=Math.floor(cols*.8),mr=Math.floor(rows*.1);
  [' _.._ ','/ .  \\','\\_  _/'].forEach((ln,i)=>[...ln].forEach((x,j)=>{if(x!==' ')put(mr+i,mc+j,x,'#f6edc8')}));
  const gr=Math.floor(rows*.86);
  layers.forEach(L=>{for(let c=0;c<cols;c++){const top=ridge(L,c);for(let r=Math.max(top,0);r<gr;r++)put(r,c,r===top?(c%2?'/':'\\'):L.ch,L.c)}});
  for(let r=gr;r<rows;r++)for(let c=0;c<cols;c++)put(r,c,r===gr?'_':((r+c)%3?',':'.'),r===gr?'#4a9a70':'#2f5a45');
  [[.05,5],[.1,4],[.16,6],[.76,4],[.86,6],[.92,4],[.97,5]].forEach(([f,h])=>{
    const c0=Math.floor(cols*f-px*1.2);
    for(let i=0;i<h;i++)for(let j=-i;j<=i;j++)put(gr-1-h+i,c0+j,'^',i%2?'#3f9a6c':'#58c08c');
    put(gr-1,c0,'|','#8a5a3c');});
  const tc=Math.floor(cols*.42),fc=tc+15,fr=gr-1;
  ["   /\\   ","  /  \\  "," /_/\\_\\ "].forEach((ln,i)=>[...ln].forEach((x,j)=>{if(x!==' ')put(gr-3+i,tc+j,x,(i===2&&(j===3||j===4))?'#ffd27a':'#ff7a59')}));
  [..."/==\\"].forEach((x,j)=>put(fr,fc-1+j,x,'#9a6a45'));
  const fh=2+Math.min(3,Math.floor(boost*.5));
  for(let i=0;i<fh;i++){const w=Math.max(0,Math.floor((fh-i)/1.3));
    for(let j=-w;j<=w;j++){const q=Math.floor((Math.sin(t*.02+i*3+j*5)+1)*2.4)%5;
      put(fr-1-i,fc+j,['(',')','^','*',"'"][q],i===0?'#ff3d2e':i===1?'#ff8a2a':'#ffd23d')}}
  if(sparks.length<80&&Math.random()<.18+boost*.12)sparks.push({x:fc+(Math.random()*3-1),y:fr-fh-1,vy:.004+Math.random()*.01,vx:(Math.random()-.5)*.006,l:1});
  for(let i=sparks.length-1;i>=0;i--){const p=sparks[i];p.y-=p.vy*dt;p.x+=p.vx*dt;p.l-=dt*.0005;
    if(p.l<=0){sparks.splice(i,1);continue}
    put(Math.round(p.y),Math.round(p.x),p.l>.5?'*':'.',p.l>.5?'#ffd23d':'#ff7a3a')}
  const R=110,fx=fc*cw,fy=(fr-1)*ch,FR=150+boost*16;
  for(let r=0;r<rows;r++){for(let c=0;c<cols;c++){const ch2=g[r][c];if(ch2===' ')continue;
    const x=c*cw,y=r*ch,dm=Math.hypot(x-mx,y-my),df=Math.hypot(x-fx,y-fy);
    if(dm<R)ctx.fillStyle='rgba(255,214,130,'+(1-dm/R*.5).toFixed(2)+')';
    else if(df<FR&&r>gr-8)ctx.fillStyle='rgba(255,150,60,'+(1-df/FR*.6).toFixed(2)+')';
    else ctx.fillStyle=k[r][c];
    ctx.fillText(ch2,x,y);}}
}
let last=performance.now();
function loop(n){const dt=Math.min(50,n-last);last=n;frame(dt);if(!reduce)requestAnimationFrame(loop)}
frame(16);if(!reduce)requestAnimationFrame(loop);
hero.addEventListener('pointermove',e=>{const r=hero.getBoundingClientRect();mx=e.clientX-r.left;my=e.clientY-r.top});
hero.addEventListener('pointerleave',()=>{mx=my=-999});
hero.addEventListener('click',e=>{if(e.target.closest('a'))return;boost=Math.min(boost+7,12);hero.classList.add('rev');setTimeout(()=>hero.classList.remove('rev'),900)});

const CC={all:'#ff9a3c',cars:'#ff6b5b',code:'#6cb6ff',outdoors:'#6fd08c'};
document.querySelectorAll('.proj').forEach(p=>p.style.setProperty('--c',CC[p.dataset.t.split(' ')[0]]));
document.querySelectorAll('.filters button').forEach(b=>b.style.setProperty('--c',CC[b.dataset.f]));
/* accordions */
document.querySelectorAll('.proj>button,.abt>button').forEach(b=>b.addEventListener('click',()=>{
  const p=b.parentElement,o=p.classList.toggle('open');b.setAttribute('aria-expanded',o)}));
/* filters */
document.querySelectorAll('.filters button').forEach(b=>b.addEventListener('click',()=>{
  document.querySelectorAll('.filters button').forEach(x=>x.setAttribute('aria-pressed',x===b));
  const f=b.dataset.f;
  document.querySelectorAll('.proj').forEach(p=>p.classList.toggle('hide',f!=='all'&&!p.dataset.t.split(' ').includes(f)));
}));
/* scroll speeds up the road a bit */
let ls=scrollY;addEventListener('scroll',()=>{boost=Math.min(boost+Math.abs(scrollY-ls)*.01,6);ls=scrollY},{passive:true});
})();
</script>
</body>
</html>
