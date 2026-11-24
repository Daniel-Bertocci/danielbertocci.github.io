[index .html](https://github.com/user-attachments/files/35304376/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Daniel Bertocci | Portfolio</title>
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
.hero{position:relative;height:100svh;min-height:560px;overflow:hidden}
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
<nav id="top"><a class="logo" href="#top">Daniel Bertocci</a>
<div><a href="#work">projects</a><a href="#about">about</a><a href="#contact">contact</a></div></nav>

<header class="hero" id="hero">
  <canvas id="c" aria-label="Animated ASCII campsite with a tent and campfire under the stars"></canvas>
  <div class="txt">
    <h1>Daniel Bertocci</h1>
    <p>Cars, computers, and getting outside.</p>
    <a class="cta" href="#work">View projects ↓</a>
  </div>
</header>

<section id="work"><div class="wrap">
  <h2>Projects</h2>
  <div class="filters" role="group" aria-label="Filter projects">
    <button aria-pressed="true" data-f="all">all</button><button aria-pressed="false" data-f="cars">cars</button><button aria-pressed="false" data-f="code">code</button><button aria-pressed="false" data-f="outdoors">outdoors</button>
  </div>
  <div id="list">
    <div class="proj" data-t="cars code"><button aria-expanded="false"><span class="pl">+</span><span class="nm">Garage Log</span><span class="ds">car maintenance tracker</span></button><div class="more"><div><p>A simple place to track maintenance, repairs, upgrades, and the next project waiting in the garage.</p></div></div></div>
    <div class="proj" data-t="code"><button aria-expanded="false"><span class="pl">+</span><span class="nm">Personal Website</span><span class="ds">this site · ascii campsite</span></button><div class="more"><div><p>A hand-built portfolio with a lightweight animated ASCII campsite and a responsive layout.</p></div></div></div>
    <div class="proj" data-t="code"><button aria-expanded="false"><span class="pl">+</span><span class="nm">Home Server</span><span class="ds">self-hosted lab</span></button><div class="more"><div><p>A hands-on lab for learning hardware, networking, system administration, and how all the pieces fit together.</p></div></div></div>
    <div class="proj" data-t="cars code"><button aria-expanded="false"><span class="pl">+</span><span class="nm">Track Day Timer</span><span class="ds">lap data viewer</span></button><div class="more"><div><p>A concept for organizing lap times, comparing runs, and turning track-day data into something useful.</p></div></div></div>
    <div class="proj" data-t="outdoors code"><button aria-expanded="false"><span class="pl">+</span><span class="nm">Trail Planner</span><span class="ds">routes &amp; gear lists</span></button><div class="more"><div><p>A planning tool for outdoor trips, with room for routes, distance, elevation, gear, and the details that make a day outside better.</p></div></div></div>
    <div class="proj" data-t="cars"><button aria-expanded="false"><span class="pl">+</span><span class="nm">Weekend Builds</span><span class="ds">repairs &amp; upgrades</span></button><div class="more"><div><p>Add the jobs you've done on your car, with a photo or two.</p></div></div></div>
    <div class="proj" data-t="outdoors"><button aria-expanded="false"><span class="pl">+</span><span class="nm">Summit Log</span><span class="ds">hikes &amp; camps</span></button><div class="more"><div><p>Your favorite trails, where they are, and why they stuck with you.</p></div></div></div>
  </div>
</div></section>

<section id="about"><div class="wrap">
  <div class="abt"><button aria-expanded="false"><span class="pl">+</span>About me</button>
  <div class="more"><div><p>I'm Daniel Bertocci. I enjoy cars, computers, technology, and spending time outdoors. I like learning by building, troubleshooting, and figuring out how things fit together.</p></div></div></div>
</div></section>

<section class="ext" id="contact"><div class="wrap">
  <h2>Elsewhere</h2>
  <a href="resume.pdf"><b>Resume</b><span>one-page PDF</span></a>
  <a href="https://github.com/YOUR-GITHUB-USERNAME" target="_blank" rel="noopener"><b>GitHub</b><span>projects &amp; code</span></a>
  <a href="https://www.instagram.com/YOUR-INSTAGRAM-USERNAME" target="_blank" rel="noopener"><b>Instagram</b><span>photos &amp; outdoors</span></a>
  <a href="mailto:YOUR-EMAIL@example.com"><b>Email</b><span>YOUR-EMAIL@example.com</span></a>
  <footer><span>© 2026 Daniel Bertocci · California</span><a href="#top">back to top ↑</a></footer>
</div></section>

<script>
(function(){
const reduce=matchMedia('(prefers-reduced-motion: reduce)').matches;
const hero=document.getElementById('hero'),cv=document.getElementById('c'),ctx=cv.getContext('2d');
let W,H,cols,rows,cw=10,ch=16,dpr=1,px=0,t=0;
function size(){
  dpr=Math.min(devicePixelRatio||1,2);W=hero.clientWidth;H=hero.clientHeight;
  cv.width=W*dpr;cv.height=H*dpr;ctx.setTransform(dpr,0,0,dpr,0,0);
  cw=W<600?8:10;ch=Math.round(cw*1.6);cols=Math.ceil(W/cw);rows=Math.ceil(H/ch);
  ctx.font=cw*1.6*.82+'px ui-monospace,Menlo,Consolas,monospace';ctx.textBaseline='top';
}
size();addEventListener('resize',()=>{size();frame(0)});
const layers=[
  {ch:'.',base:.66,depth:.20,sp:.3,c:'#7c8490',peaks:[[.08,.13,.16],[.28,.18,.12],[.50,.15,.14],[.72,.20,.13],[.93,.14,.16]]},
  {ch:':',base:.75,depth:.24,sp:.8,c:'#59616d',peaks:[[.02,.18,.14],[.20,.24,.13],[.43,.19,.16],[.68,.27,.14],[.88,.21,.13]]},
  {ch:'#',base:.84,depth:.20,sp:1.6,c:'#39414d',peaks:[[.10,.15,.12],[.34,.22,.14],[.58,.17,.12],[.80,.23,.14],[1.00,.16,.12]]}
];
const stars=[];for(let i=0;i<90;i++)stars.push([Math.random(),Math.random()*.38,Math.random()*6]);
const sparks=[];
function ridge(L,x){
  const n=Math.max(0,Math.min(1,(x/Math.max(cols-1,1))+px*L.sp*.001));
  let height=L.base;
  L.peaks.forEach(([center,depth,width])=>{
    const distance=Math.abs(n-center);
    const peak=Math.max(0,1-distance/width);
    height-=peak*depth;
  });
  return Math.round(rows*height);}
function frame(dt){
  t+=dt;
  ctx.clearRect(0,0,W,H);
  const moonX=W*.82,moonY=H*.15,moonR=Math.min(W,H)*.12;
  const moonGlow=ctx.createRadialGradient(moonX,moonY,moonR*.18,moonX,moonY,moonR*2.8);
  moonGlow.addColorStop(0,'rgba(235,235,220,.22)');
  moonGlow.addColorStop(.35,'rgba(205,215,235,.10)');
  moonGlow.addColorStop(1,'rgba(120,150,220,0)');
  ctx.fillStyle=moonGlow;ctx.fillRect(0,0,W,H);
  ctx.beginPath();
  ctx.arc(moonX,moonY,moonR*.58,0,Math.PI*2);
  ctx.fillStyle='#d9d9d2';
  ctx.fill();
  const g=[],k=[];for(let r=0;r<rows;r++){g.push(new Array(cols).fill(' '));k.push(new Array(cols).fill(''))}
  const put=(r,c,ch,col)=>{if(r>=0&&r<rows&&c>=0&&c<cols){g[r][c]=ch;k[r][c]=col}};
  stars.forEach(s=>{const sx=s[0]*W,sy=s[1]*H;if(Math.hypot(sx-moonX,sy-moonY)>moonR*.6){const tw=Math.sin(t*.003+s[2])>.1;put(Math.floor(s[1]*rows),Math.floor(s[0]*cols),tw?'*':'.',tw?'#d4e6ff':'#6f7fb0')}});
  [[-.25,-.22],[.12,-.25],[-.30,.08],[.18,.12],[-.02,.28]].forEach(([ox,oy],i)=>{
    if(Math.sin(t*.008+i*1.8)>.05){
      put(Math.round((moonY+oy*moonR)/ch),Math.round((moonX+ox*moonR)/cw),'✦','#ffffff');
    }
  });
  const gr=Math.floor(rows*.86);
  layers.forEach(L=>{for(let c=0;c<cols;c++){const top=ridge(L,c);for(let r=Math.max(top,0);r<gr;r++)put(r,c,r===top?(c%2?'/':'\\'):L.ch,L.c)}});
  for(let r=gr;r<rows;r++)for(let c=0;c<cols;c++)put(r,c,r===gr?'_':((r+c)%3?',':'.'),r===gr?'#4a9a70':'#2f5a45');
  [[.05,5],[.1,4],[.16,6],[.76,4],[.86,6],[.92,4],[.97,5]].forEach(([f,h])=>{
    const c0=Math.floor(cols*f-px*1.2);
    for(let i=0;i<h;i++)for(let j=-i;j<=i;j++)put(gr-1-h+i,c0+j,'^',i%2?'#3f9a6c':'#58c08c');
    put(gr-1,c0,'|','#8a5a3c');});
  const tc=Math.floor(cols*.42),fc=tc+15,fr=gr-1;
  ["   /\\   ","  /  \\  "," /_/\\_\\ "].forEach((ln,i)=>[...ln].forEach((x,j)=>{
    if(x!==' ')put(gr-3+i,tc+j,x,(i===2&&(j===3||j===4))?'#ffffff':'#3d78c4');
  }));
  [..."/==\\"].forEach((x,j)=>put(fr,fc-1+j,x,'#9a6a45'));
  const fh=2+Math.min(3,Math.floor((Math.sin(t*.01)+1)*1.5));
  for(let i=0;i<fh;i++){const w=Math.max(0,Math.floor((fh-i)/1.3));
    for(let j=-w;j<=w;j++){const q=Math.floor((Math.sin(t*.02+i*3+j*5)+1)*2.4)%5;
      put(fr-1-i,fc+j,['(',')','^','*',"'"][q],i===0?'#ff3d2e':i===1?'#ff8a2a':'#ffd23d')}}
  if(sparks.length<35&&Math.random()<.12)sparks.push({x:fc+(Math.random()*3-1),y:fr-fh-1,vy:.004+Math.random()*.01,vx:(Math.random()-.5)*.006,l:1});
  for(let i=sparks.length-1;i>=0;i--){const p=sparks[i];p.y-=p.vy*dt;p.x+=p.vx*dt;p.l-=dt*.0007;
    if(p.l<=0){sparks.splice(i,1);continue}
    put(Math.round(p.y),Math.round(p.x),p.l>.5?'*':'.',p.l>.5?'#ffd23d':'#ff7a3a')}
  for(let r=0;r<rows;r++){for(let c=0;c<cols;c++){const ch2=g[r][c];if(ch2===' ')continue;
    const x=c*cw,y=r*ch;ctx.fillStyle=k[r][c];
    ctx.fillText(ch2,x,y);}}
}
let last=performance.now();
function loop(n){const dt=Math.min(50,n-last);last=n;frame(dt);if(!reduce)requestAnimationFrame(loop)}
frame(16);if(!reduce)requestAnimationFrame(loop);
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
})();
</script>
</body>
</html>
