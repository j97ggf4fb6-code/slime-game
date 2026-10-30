<!DOCTYPE html>
<html lang="ja"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1,minimum-scale=1,viewport-fit=cover,user-scalable=no">
<title>巨人狩り 〜ウォール・マリア〜</title>
<style>
html,body{margin:0;height:100%;overflow:hidden;background:#9db4c8;touch-action:none;user-select:none;-webkit-user-select:none;font-family:-apple-system,"Hiragino Sans",sans-serif}
canvas{display:block}
#hud{position:fixed;top:env(safe-area-inset-top,0px);left:0;right:0;padding:10px 14px;color:#fff;text-shadow:0 1px 3px #000;font-size:15px;pointer-events:none;display:flex;justify-content:space-between;align-items:flex-start}
#ar{position:fixed;top:calc(52px + env(safe-area-inset-top,0px));left:50%;margin-left:-14px;width:28px;text-align:center;color:#ff6a50;font-size:24px;text-shadow:0 1px 3px #000;pointer-events:none}
.bar{width:140px;height:10px;background:#0008;border:1px solid #fff5;border-radius:5px;overflow:hidden;margin-top:5px}
.bar i{display:block;height:100%;background:linear-gradient(90deg,#3a9cff,#9ff);width:100%}
.btn{position:fixed;border-radius:50%;background:#000a;border:2px solid #fffb;color:#fff;display:flex;align-items:center;justify-content:center;font-weight:bold;font-size:15px;touch-action:none}
.btn.on{background:#c33a}
#hook{right:18px;bottom:calc(40px + env(safe-area-inset-bottom,0px));width:92px;height:92px}
#gas{right:122px;bottom:calc(24px + env(safe-area-inset-bottom,0px));width:72px;height:72px}
#sl{right:30px;bottom:calc(148px + env(safe-area-inset-bottom,0px));width:84px;height:84px;background:#8a1c1cc8}
#ar{top:50%;margin:-14px 0 0 -14px}
#rt{position:fixed;left:50%;top:50%;width:16px;height:16px;margin:-8px 0 0 -8px;border:2px solid #fff9;border-radius:50%;pointer-events:none}
#lm{position:fixed;width:34px;height:34px;margin:-17px 0 0 -17px;border:3px solid #ff3b2a;border-radius:50%;box-shadow:0 0 8px #f00;pointer-events:none;display:none}
#lk{right:122px;bottom:calc(112px + env(safe-area-inset-bottom,0px));width:60px;height:60px;font-size:13px}
#gn{right:190px;bottom:calc(105px + env(safe-area-inset-bottom,0px));width:60px;height:60px;font-size:14px;background:#2c4a8ac8}
#tf{left:14px;bottom:calc(150px + env(safe-area-inset-bottom,0px));width:70px;height:70px;font-size:14px;background:#a5530ec8}
.fb{margin:3px;padding:8px 12px;border:0;border-radius:14px;background:#444;color:#fff;font-size:14px}
#vg{position:fixed;inset:0;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.4) 100%)}
#vr{position:fixed;inset:0;pointer-events:none;background:radial-gradient(ellipse at center,transparent 40%,rgba(200,0,0,.6) 100%);opacity:0}
#sp{position:fixed;inset:0;pointer-events:none;background:repeating-conic-gradient(from 0deg,#fff0 0 5deg,#fff5 5deg 5.6deg);-webkit-mask-image:radial-gradient(circle,transparent 42%,#000 100%);mask-image:radial-gradient(circle,transparent 42%,#000 100%);opacity:0}
#mp{position:fixed;inset:0;display:none;width:100%;height:100%;z-index:5}
#hp{font-size:20px;color:#ff5a6a;letter-spacing:2px}
#wv{background:#0005;padding:6px 10px;border-radius:10px;line-height:1.5}
#stb{left:14px;top:calc(222px + env(safe-area-inset-top,0px));width:44px;height:44px;font-size:18px;z-index:6}
#mb{left:14px;top:calc(160px + env(safe-area-inset-top,0px));width:52px;height:52px;font-size:12px;z-index:6}
.tm{position:fixed;color:#ff5a4a;font-size:12px;font-weight:bold;text-shadow:0 1px 3px #000;pointer-events:none;transform:translate(-50%,-100%);display:none}
#jp{right:204px;bottom:calc(30px + env(safe-area-inset-bottom,0px));width:64px;height:64px;font-size:13px}
#rd{position:fixed;left:12px;top:calc(62px + env(safe-area-inset-top,0px));width:90px;height:90px;border-radius:50%;background:#0006;border:1px solid #fff5;pointer-events:none}
#tt{position:fixed;top:30%;left:0;right:0;text-align:center;color:#fff;font-size:22px;font-weight:bold;text-shadow:0 2px 6px #000;pointer-events:none;opacity:0;transition:opacity .3s}
#jb{position:fixed;width:120px;height:120px;margin:-60px 0 0 -60px;border-radius:50%;background:#fff3;border:2px solid #fff6;display:none;pointer-events:none}
#jk{position:absolute;left:35px;top:35px;width:50px;height:50px;border-radius:50%;background:#fffa}
#fl{position:fixed;inset:0;background:#fff;opacity:0;pointer-events:none;transition:opacity .2s}
#ov{position:fixed;inset:0;background:#000c;color:#fff;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:24px;line-height:1.7}
#ov h1{margin:0 0 8px;font-size:26px}
#ov p{margin:4px 0;font-size:14px;max-width:340px}
#go{margin-top:18px;padding:14px 40px;font-size:18px;font-weight:bold;border:0;border-radius:30px;background:#e8553a;color:#fff}
html{touch-action:manipulation}
body{-webkit-touch-callout:none;-webkit-tap-highlight-color:transparent}
#home{position:fixed;inset:0;z-index:20;display:none;flex-direction:column;align-items:center;justify-content:center;background:linear-gradient(#1c2a3a,#3b2a22);color:#fff;padding:20px;text-align:center}
#home h1{font-size:28px;margin:0 0 6px}
#home .s1{opacity:.75;font-size:13px;margin-bottom:18px}
#hm1,#hm2{display:flex;flex-direction:column;gap:12px;width:min(86vw,360px);align-items:stretch}
#home input{font-size:18px;padding:12px;border-radius:10px;border:0;text-align:center;-webkit-user-select:text;user-select:text}
#home label{font-size:14px;opacity:.85}
.hb{font-size:18px;font-weight:bold;padding:14px;border:0;border-radius:14px;background:#e8553a;color:#fff}
.hb.sub{background:#555}
#rc{font-size:54px;font-weight:bold;letter-spacing:8px;font-family:monospace;color:#ffd24a;margin:6px 0}
#nst{min-height:24px;font-size:15px}
</style></head><body>
<div id="hud"><div><div id="hp"></div><div class="bar"><i id="gb"></i></div><div class="bar"><i id="tb" style="background:#f93"></i></div></div><div id="wv" style="text-align:right"></div></div>
<div id="ar">▲</div>
<div id="jb"><div id="jk"></div></div>
<div class="btn" id="gas">ガス</div><div class="btn" id="hook">フック</div><div class="btn" id="sl">斬る</div><div class="btn" id="lk">ロック</div><div class="btn" id="jp">ジャンプ</div><div class="btn" id="tf">巨人化</div><canvas id="rd" width="90" height="90"></canvas><div id="rt"></div><canvas id="mp"></canvas><div class="btn" id="mb">マップ</div><div class="btn" id="stb">⚙</div><div id="lm"></div><div id="tt"></div>
<div id="vg"></div><div id="vr"></div><div id="sp"></div><div id="fl"></div>
<div id="home"><h1>巨人狩り 〜ウォール・マリア〜</h1><div class="s1">ホーム</div>
<div id="hm1"><label>ニックネーム</label><input id="nick" maxlength="12" placeholder="なまえ" autocomplete="off">
<button id="solo" class="hb">そのまま遊ぶ（ソロプレイ）</button><button id="onb" class="hb">オンライン対戦（P2P）</button></div>
<div id="hm2" style="display:none"><button id="mk" class="hb">ルームを作る</button><button id="jn" class="hb">部屋に入る</button>
<div id="rcw" style="display:none">パスワード<div id="rc"></div></div>
<div id="jw" style="display:none"><input id="jin" maxlength="6" placeholder="パスワード" autocomplete="off" autocapitalize="characters"><button id="jgo" class="hb" style="margin-top:10px;width:100%">接続</button></div>
<div id="nst"></div><button id="bk" class="hb sub">もどる</button></div></div>
<div id="ov" style="display:none"><h1>巨人狩り 〜ウォール・マリア〜</h1>
<p>城門が破られた。街に侵入する巨人を討て。</p>
<p>左ドラッグ：移動／右ドラッグ：視点</p>
<p><b>フック</b>：屋根・城壁・巨人のうなじに刺して飛ぶ（離すと解除）</p>
<p><b>ガス</b>：加速　<b>斬る</b>：ブレードで斬撃　連続撃破でコンボ</p>
<p>うなじ＝撃破／<b>目</b>＝視界を奪う／<b>足</b>＝動きを止める（巨人は再生する）。<b>ロック</b>で巨人を追尾。腕の叩きつけと踏みつけに注意！</p>
<p><b>巨人化</b>：ゲージ満タンで変身（時間制限なし。体力が尽きるか、もう一度押すと解除）。「斬る」＝巨人の攻撃。空中で高速のとき「斬る」＝<b>回転斬り</b></p><p>巨人化の型：</p><div id="fs"></div><button id="lq" class="fb">画質：標準</button><br><button id="go">出撃</button><br><button id="hmb" class="fb">ホームへ戻る</button></div>
<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/peerjs/1.4.7/peerjs.min.js"></script>
<script>
const T=THREE,$=id=>document.getElementById(id),rnd=Math.random;
const R=new T.WebGLRenderer({antialias:true});R.setPixelRatio(Math.min(devicePixelRatio,2));R.setSize(innerWidth,innerHeight);document.body.prepend(R.domElement);
const S=new T.Scene();S.fog=new T.Fog(0xc4ccd2,220,620);
const C=new T.PerspectiveCamera(68,innerWidth/innerHeight,0.1,900);
S.add(new T.HemisphereLight(0xdfe8f5,0x6a6050,.85));
const sun=new T.DirectionalLight(0xfff0d8,.9);sun.position.set(-80,120,60);S.add(sun);
function cv(w,h,f,rx=1,ry=1){const c=document.createElement('canvas');c.width=w;c.height=h;f(c.getContext('2d'),w,h);const t=new T.CanvasTexture(c);t.wrapS=t.wrapT=T.RepeatWrapping;t.repeat.set(rx,ry);t.anisotropy=4;return t}
const spk=(x,w,h,n,a)=>{for(let i=0;i<n;i++){x.fillStyle=`rgba(${rnd()<.5?'0,0,0':'255,255,255'},${rnd()*a})`;x.fillRect(rnd()*w,rnd()*h,1+rnd()*3,1+rnd()*3)}};
// 空
const sky=new T.Mesh(new T.SphereGeometry(600,16,12),new T.MeshBasicMaterial({map:cv(4,256,(x,w,h)=>{const g=x.createLinearGradient(0,0,0,h);g.addColorStop(0,'#5d86b8');g.addColorStop(.5,'#a9c2dc');g.addColorStop(.55,'#c4ccd2');g.addColorStop(1,'#c4ccd2');x.fillStyle=g;x.fillRect(0,0,w,h)}),side:T.BackSide,fog:false}));S.add(sky);
// 石畳
const gT=cv(256,256,(x,w,h)=>{x.fillStyle='#3d3a33';x.fillRect(0,0,w,h);for(let r=0;r<8;r++)for(let c=0;c<8;c++){x.fillStyle=`hsl(35,${6+rnd()*6}%,${36+rnd()*16}%)`;x.fillRect(c*32+(r%2)*16+2,r*32+2,28,28)}spk(x,w,h,300,.25)},110,110);
const gh=(x,z)=>{const r=Math.hypot(x,z),f=Math.min(1,Math.max(0,(262-r)/70));return f*(Math.sin(x*.018+1)*7+Math.cos(z*.021)*6+Math.sin((x+z)*.011)*9+Math.sin(x*.04)*Math.cos(z*.035)*4)};
const gG=new T.PlaneGeometry(700,700,150,150);gG.rotateX(-Math.PI/2);
{const ps=gG.attributes.position,cl=new Float32Array(ps.count*3);for(let i=0;i<ps.count;i++){const x=ps.getX(i),z=ps.getZ(i),h=gh(x,z);ps.setY(i,h);const g=Math.min(1,Math.max(0,(h-3)/7)),yd=Math.hypot(x,z)<290&&!isRoad(x,z)&&!(Math.abs(x)<56&&Math.abs(z)<56)?1:0;cl[i*3]=(1-g*.45)*(1-yd*.42);cl[i*3+1]=(1-g*.18)*(1-yd*.2);cl[i*3+2]=(1-g*.5)*(1-yd*.52)}gG.setAttribute('color',new T.BufferAttribute(cl,3));gG.computeVertexNormals()}
const gr=new T.Mesh(gG,new T.MeshLambertMaterial({map:gT,vertexColors:true}));S.add(gr);
// ウォール・マリア
const wT=cv(256,128,(x,w,h)=>{x.fillStyle='#4a4742';x.fillRect(0,0,w,h);for(let r=0;r<4;r++)for(let c=0;c<4;c++){x.fillStyle=`hsl(40,5%,${52+rnd()*14}%)`;x.fillRect(c*64+(r%2)*32+1.5,r*32+1.5,61,29)}spk(x,w,h,500,.2)},48,5);
const wall=new T.Mesh(new T.CylinderGeometry(300,300,75,72,1,true,Math.PI/2+.0667,Math.PI*2-.1333),new T.MeshLambertMaterial({map:wT,side:T.DoubleSide}));wall.position.y=37.5;S.add(wall);
const wtop=new T.Mesh(new T.RingGeometry(292,302,72),new T.MeshLambertMaterial({color:0x8a8780,side:T.DoubleSide}));wtop.rotation.x=-Math.PI/2;wtop.position.y=75;S.add(wtop);
const gate=new T.Mesh(new T.BoxGeometry(10,37,38),new T.MeshLambertMaterial({color:0x77736b}));gate.position.set(299,56.5,0);S.add(gate);
// 街
const B=[],ALL=[],wcol=['#d8c9a8','#cdbb97','#e2d6bc','#c9b8a2','#d4c2a0'];
const roofT=cv(64,64,(x,w,h)=>{x.fillStyle='#9a4632';x.fillRect(0,0,w,h);for(let y=0;y<h;y+=8){x.fillStyle='rgba(0,0,0,.28)';x.fillRect(0,y,w,2)}spk(x,w,h,60,.3)},4,3);
const wallTex=wcol.map(c=>cv(128,128,(x,w,h)=>{x.fillStyle=c;x.fillRect(0,0,w,h);spk(x,w,h,400,.12);x.fillStyle='#5a4630';x.fillRect(38,24,52,70);x.fillStyle='#2b3640';x.fillRect(42,28,20,62);x.fillRect(66,28,20,62);x.fillStyle='#5a4630';x.fillRect(38,58,52,4);x.fillStyle='#8a8070';x.fillRect(34,94,60,5)}));
function houseOld(cx,cz,w,d,h,k){const t=wallTex[k].clone();t.needsUpdate=true;t.repeat.set(Math.max(1,Math.round(w/3.5)),Math.max(1,Math.round(h/7)));
 const a=new T.Mesh(new T.BoxGeometry(w*2,h,d*2),new T.MeshLambertMaterial({map:t}));a.position.set(cx,h/2,cz);
 const rh=3+rnd()*3,cg=new T.ConeGeometry(1,rh,4);cg.rotateY(Math.PI/4);
 const ro=new T.Mesh(cg,new T.MeshLambertMaterial({map:roofT}));ro.scale.set((w+1)*1.414,1,(d+1)*1.414);ro.position.set(cx,h+rh/2,cz);
 S.add(a,ro);const b={x:cx,z:cz,w,d,h:h+1.2,pk:h+rh,m:[a,ro]};B.push(b);ALL.push(b)}
function buildCity(){for(let ix=-8;ix<=8;ix++)for(let iz=-8;iz<=8;iz++){const cx=ix*36+(rnd()-.5)*4,cz=iz*36+(rnd()-.5)*4;if(Math.hypot(cx,cz)>275||(Math.abs(ix)<=1&&Math.abs(iz)<=1&&(ix||iz))||((ix||iz)&&rnd()<.12))continue;
 if(!ix&&!iz)house(0,0,12,18,30,2);else house(cx,cz,6+rnd()*4,6+rnd()*4,9+rnd()*11,Math.floor(rnd()*5))}}
// 人間（調査兵団風）
const BG=new T.BoxGeometry(1,1,1),SG=new T.SphereGeometry(1,12,10);
function mk(geo,mat,sx,sy,sz,x,y,z,par){const o=new T.Mesh(geo,mat);o.scale.set(sx,sy,sz);o.position.set(x,y,z);par.add(o);return o}
const M=c=>new T.MeshLambertMaterial({color:c});
const shM=new T.MeshBasicMaterial({color:0,transparent:true,opacity:.35,depthWrite:false}),shG=new T.CircleGeometry(1,16);shG.rotateX(-Math.PI/2);
function mkHumanOld(){const g=new T.Group(),skin=M(0xf0c8a8),jk=M(0x8a6a45),pn=M(0xe8e4d8),bt=M(0x3a2a20),gy=M(0x777b80);
 mk(BG,jk,.5,.7,.3,0,1.2,0,g);mk(BG,M(0x3b5d3a),.56,.95,.1,0,1.1,-.22,g);
 mk(SG,skin,.15,.17,.15,0,1.72,0,g);mk(SG,M(0x3a2a1c),.16,.13,.16,0,1.78,-.02,g);
 mk(BG,gy,.14,.2,.22,.3,.85,0,g);mk(BG,gy,.14,.2,.22,-.3,.85,0,g);mk(BG,M(0x5a4630),.52,.08,.32,0,.88,0,g);
 const leg=x=>{const l=new T.Group();l.position.set(x,.82,0);g.add(l);mk(BG,pn,.2,.55,.22,0,-.28,0,l);mk(BG,bt,.22,.35,.28,0,-.7,.02,l);return l};
 const arm=x=>{const a=new T.Group();a.position.set(x,1.48,0);g.add(a);mk(BG,jk,.15,.6,.15,0,-.28,0,a);mk(SG,skin,.08,.08,.08,0,-.62,0,a);return a};
 const o={g,lL:leg(-.14),lR:leg(.14),aL:arm(-.36),aR:arm(.36)};
 mk(BG,M(0xdde3e8),.03,.04,1.15,0,-.62,.6,o.aR);mk(BG,M(0x222222),.06,.06,.2,0,-.62,.05,o.aR);
 g.scale.setScalar(1.35);g.rotation.order='YXZ';S.add(g);return o}
const H=mkHuman(),pSh=new T.Mesh(shG,shM);S.add(pSh);
const P={p:new T.Vector3(126,gh(126,18),18),v:new T.Vector3(),gas:100,hp:5,inv:0,g:true,a:null,sl:0,slc:0};
const rope=new T.Line(new T.BufferGeometry().setFromPoints([new T.Vector3(),new T.Vector3()]),new T.LineBasicMaterial({color:0x222222}));rope.frustumCulled=false;rope.visible=false;S.add(rope);
const arc=new T.Mesh(new T.RingGeometry(1.2,5,24,1,-Math.PI/2-1.1,2.2).rotateX(-Math.PI/2),new T.MeshBasicMaterial({color:0xffffff,transparent:true,opacity:0,side:T.DoubleSide,depthWrite:false}));S.add(arc);
// パーティクル（蒸気・粉塵）
const PG=new T.SphereGeometry(1,6,5),pool=[];
for(let i=0;i<50;i++){const m=new T.Mesh(PG,new T.MeshBasicMaterial({color:0xffffff,transparent:true,opacity:0,depthWrite:false}));m.visible=false;S.add(m);pool.push({m,v:new T.Vector3(),l:0,L:1,r:1})}
function puff(pos,n,r,col=0xffffff){for(let k=0;k<n;k++){const q=pool.find(q=>q.l<=0);if(!q)return;q.m.position.copy(pos);q.v.set((rnd()-.5)*4,2+rnd()*3,(rnd()-.5)*4);q.L=q.l=.8+rnd()*.8;q.r=r*(.6+rnd()*.6);q.m.material.color.setHex(col);q.m.visible=true}}
// 巨人
const sk=[0xe3bf9f,0xd9ae8c,0xe8c9ae,0xcfa58a].map(M),hairM=M(0x2e2218),blk=new T.MeshBasicMaterial({color:0x111111}),wht=M(0xf2eee6),redM=new T.MeshBasicMaterial({color:0xff2a1a});
const NAPE=new T.Vector3(0,5.8,-1.6);
let titans=[],wave=0,score=0,run=false,shake=0;
function mkTitanOld(x,z,runner){const g=new T.Group(),m=sk[Math.floor(rnd()*4)],s=(runner?.62:.72)+rnd()*.4;
 const up=new T.Group();up.position.y=6.5;up.rotation.x=.18;g.add(up);
 mk(BG,m,4.4,5.6,2.7,0,2.9,0,up);mk(BG,m,6,1.6,2.4,0,5.3,0,up);
 const hd=new T.Group();hd.position.set(0,6.8,.6);up.add(hd);
 mk(SG,m,1.7,1.9,1.8,0,0,0,hd);mk(BG,m,2.4,1.1,1.8,0,-1.5,.45,hd);mk(BG,blk,2,.5,.3,0,-1.1,1.45,hd);
 for(let i=-2;i<=2;i++)mk(BG,wht,.3,.38,.2,i*.36,-1.1,1.6,hd);
 for(const e of[-.75,.75]){mk(SG,wht,.38,.38,.3,e,.35,1.45,hd);mk(SG,blk,.17,.17,.12,e,.35,1.72,hd)}
 mk(BG,m,.5,.6,.5,0,-.3,1.7,hd);mk(BG,m,2.6,.3,.5,0,.85,1.5,hd);mk(SG,hairM,1.8,1.5,1.9,0,.6,-.3,hd);
 mk(SG,redM,.5,.5,.5,NAPE.x,NAPE.y,NAPE.z,up);
 const arm=x=>{const a=new T.Group();a.position.set(x,5.1,0);up.add(a);mk(BG,m,1.4,6.6,1.4,0,-3.1,0,a);mk(SG,m,.9,.9,.9,0,-6.6,0,a);return a};
 const leg=x=>{const l=new T.Group();l.position.set(x,6.5,0);g.add(l);mk(BG,m,2,6.4,2.2,0,-3.2,0,l);mk(BG,m,2.1,.7,3.4,0,-6.2,.7,l);return l};
 const o={g,up,aR:arm(3.4),aL:arm(-3.4),lR:leg(1.2),lL:leg(-1.2),s,runner,sp:(runner?7:3+rnd()*1.4)+wave*.25,st:0,tm:0,cd:1.5,ph:rnd()*6,dead:0,dt:0,nw:new T.Vector3()};
 mk(BG,m,4,2,2.5,0,6.5,0,g);mk(shG,shM,1,1,1,0,.06,0,g).scale.set(5,1,5);
 g.scale.setScalar(s);g.position.set(x,0,z);g.rotation.y=Math.PI/2*3;S.add(g);return o}
function spawn(){wave++;const n=Math.min(10,4+wave*2);for(let i=0;i<n;i++){let x,z;if(i<n/2){x=330+rnd()*14;z=(i-n/4)*14+(rnd()-.5)*6}else{do{const a=rnd()*6.283,r=40+rnd()*230;x=Math.cos(a)*r;z=Math.sin(a)*r}while(Math.hypot(x-P.p.x,z-P.p.z)<70)}titans.push(bigify(mkTitan(x,z,wave>1&&rnd()<.3)))}for(let k=0;k<2;k++){const a=rnd()*6.283,r=60+rnd()*40;let x=P.p.x+Math.cos(a)*r,z=P.p.z+Math.sin(a)*r;const rr=Math.hypot(x,z);if(rr>540){x*=540/rr;z*=540/rr}titans.push(bigify(mkTitan(x,z,false)))}
if(wave%5==0){const b=bigify(mkTitan(340,0,false));b.s=2.9;b.g.scale.setScalar(2.9);b.hp=4;b.sp=2.4;toast('超大型が現れた！');titans.push(b)}toast('巨人の群れが侵入！')}
// 入力
let yaw=-Math.PI/2,pitch=.35,jx=0,jy=0,gasHeld=false,stick=null,look=null;
const jb=$('jb'),jk=$('jk');
addEventListener('pointerdown',e=>{if(e.target.closest('.btn,#ov,#mp,#home'))return;
 if(e.clientX<innerWidth*.45){if(!stick){stick={id:e.pointerId,x:e.clientX,y:e.clientY};jb.style.display='block';jb.style.left=e.clientX+'px';jb.style.top=e.clientY+'px'}}
 else if(!look)look={id:e.pointerId,x:e.clientX,y:e.clientY}});
addEventListener('pointermove',e=>{
 if(stick&&e.pointerId===stick.id){let dx=e.clientX-stick.x,dy=e.clientY-stick.y;const l=Math.hypot(dx,dy),m=55;if(l>m){dx*=m/l;dy*=m/l}jx=dx/m;jy=dy/m;jk.style.transform=`translate(${dx}px,${dy}px)`}
 if(look&&e.pointerId===look.id){lkIdle=performance.now();yaw-=(e.clientX-look.x)*.006;pitch=Math.max(-1.3,Math.min(1.1,pitch+(e.clientY-look.y)*.004));look.x=e.clientX;look.y=e.clientY}});
const up=e=>{if(stick&&e.pointerId===stick.id){stick=null;jx=jy=0;jb.style.display='none';jk.style.transform=''}if(look&&e.pointerId===look.id)look=null};
addEventListener('pointerup',up);addEventListener('pointercancel',up);
function bindBtn(el,down,rel){el.addEventListener('pointerdown',e=>{e.preventDefault();el.setPointerCapture(e.pointerId);el.classList.add('on');down()});
 const r=()=>{el.classList.remove('on');rel()};el.addEventListener('pointerup',r);el.addEventListener('pointercancel',r)}
bindBtn($('gas'),()=>gasHeld=true,()=>gasHeld=false);
bindBtn($('hook'),hookPress,()=>{P.a=null;rope.visible=false});
bindBtn($('sl'),slash,()=>{});
function flash(c){const f=$('fl');f.style.background=c;f.style.opacity=.55;setTimeout(()=>f.style.opacity=0,120)}
function hookPress(){if(!run||P.tf||P.held)return;sfx(320,.12,'square',.06);const fw=new T.Vector3();C.getWorldDirection(fw);let best=null,bs=.3;
 const cand=[];for(const b of B)cand.push({pos:new T.Vector3(b.x,b.pk,b.z),bonus:0});
 for(let i=0;i<40;i++){const a=i/40*6.283;cand.push({pos:new T.Vector3(Math.cos(a)*295,66,Math.sin(a)*295),bonus:0})}
 for(const t of titans)if(!t.dead)cand.push({pos:t.nw.clone(),t,bonus:t===lockT?3:.15});
 for(const c of cand){const d=c.pos.clone().sub(P.p),L=d.length();if(L<8||L>120)continue;const s=d.divideScalar(L).dot(fw)-L*.001+c.bonus;if(s>bs){bs=s;best=c}}
 if(best){P.a=best;rope.visible=true}else if(P.g){P.v.y=13;P.g=false}}
function slashOld(){if(!run||P.sl>0||P.slc>0)return;P.sl=.28;P.slc=.5;
 let bn=null,bd=24;const c=P.p.clone().setY(P.p.y+1);for(const t of titans)if(!t.dead){const d=t.nw.distanceTo(c);if(d<bd){bd=d;bn=t.nw}}
 if(bn)P.v.addScaledVector(bn.clone().sub(c).normalize(),18)}
function hurt(fx,fz){if(P.inv>0)return;sfx(110,.4,'sine',.35);navigator.vibrate&&navigator.vibrate(80);if(P.tf){P.th-=F[form].armor?.5:1;P.inv=1;shake=.8;flash('#f00');return}P.hp--;P.inv=1.6;P.v.set(fx*22,10,fz*22);P.a=null;rope.visible=false;shake=.6;flash('#f00');if(P.hp<=0){run=false;gameOver()}}
function strike(t){const g=t.g,s=t.s,fx=Math.sin(g.rotation.y),fz=Math.cos(g.rotation.y);
 if(new T.Vector3(g.position.x+fx*5.5*s,6*s,g.position.z+fz*5.5*s).distanceTo(P.p)<7.5*s)hurt(fx,fz)}
function kill(t){t.dead=1;combo=cT>0?combo+1:1;cT=5;if((score+1)%5==0&&P.hp<7)P.hp++;slow=.3;P.tg=Math.min(100,P.tg+20);sfx(520,.3,'triangle',.2);navigator.vibrate&&navigator.vibrate(40);score++;P.gas=Math.min(100,P.gas+30);puff(t.nw,10,1.4);flash('#fff')}
const V=(x=0,y=0,z=0)=>new T.Vector3(x,y,z);
let lockT=null,sid=0,ttT=0;P.sd=V(0,0,-1);bindBtn($('lk'),lockPress,()=>{});
function toast(m){const e=$('tt');e.textContent=m;e.style.opacity=1;clearTimeout(ttT);ttT=setTimeout(()=>e.style.opacity=0,900)}
// 多様な家
const rfc=[0xffffff,0xd8c0b0,0x8a929c,0xd9a97a],roofG=roofT.clone();roofG.repeat.set(.35,.35);roofG.needsUpdate=true;
function part(cx,cz,w,d,h,k,rt,rh,ci){const t=wallTex[k].clone();t.needsUpdate=true;t.repeat.set(Math.max(1,Math.round(w/3.5)),Math.max(1,Math.round(h/7)));
 const a=new T.Mesh(new T.BoxGeometry(w*2,h,d*2),new T.MeshLambertMaterial({map:t}));a.position.set(cx,h/2,cz);const ms=[a];let ro,top=h+rh;
 if(rt==0){const cg=new T.ConeGeometry(1,rh,4);cg.rotateY(Math.PI/4);ro=new T.Mesh(cg,new T.MeshLambertMaterial({map:roofT,color:rfc[ci]}));ro.scale.set((w+1)*1.414,1,(d+1)*1.414);ro.position.set(cx,h+rh/2,cz)}
 else if(rt==3){ro=new T.Mesh(new T.BoxGeometry(w*2+.6,.7,d*2+.6),M(0x8a8780));ro.position.set(cx,h+.35,cz);top=h+.7}
 else{const hw=(rt==1?d:w)+.8,dp=2*(rt==1?w:d)+1.6,sh=new T.Shape();sh.moveTo(-hw,0);sh.lineTo(hw,0);sh.lineTo(0,rh);const gg=new T.ExtrudeGeometry(sh,{depth:dp,bevelEnabled:false});gg.translate(0,0,-dp/2);if(rt==1)gg.rotateY(Math.PI/2);
  ro=new T.Mesh(gg,new T.MeshLambertMaterial({map:roofG,color:rfc[ci]}));ro.position.set(cx,h,cz)}
 ms.push(ro);if(rt!=3&&rnd()<.5){const c=new T.Mesh(BG,M(0x6e4a3e));c.scale.set(1.3,4,1.3);c.position.set(cx+w*.4,h+rh*.5+1.5,cz);ms.push(c)}
 S.add(...ms);if(rt!=3&&w>3){const dr=new T.Mesh(BG,M(0x4a3420));dr.scale.set(1.6,2.8,.25);dr.position.set(cx+(rnd()-.5)*w*.8,1.4,cz+d);ms.push(dr)}
 const gy=gh(cx,cz);ms.forEach(o=>o.position.y+=gy);const fd=new T.Mesh(BG,M(0x6d675d));fd.scale.set(w*2+.3,5.6,d*2+.3);fd.position.set(cx,gy-2.2,cz);ms.push(fd);S.add(fd);const b={x:cx,z:cz,w,d,gy,h:gy+(rt==3?h+.7:h+1.2),pk:gy+top,h0:gy+h,rt,rh,mhp:60+w*d*1.2,col:parseInt((wcol[k]||'#d8c9a8').slice(1),16),chimY:ms.length>(rt!=3&&w>3?4:3)?gy+h+rh*.5+5.5:0,cx:w*.4,m:ms};B.push(b);ALL.push(b)}
function house(cx,cz,w,d,h,k){w=Math.min(11,w*(rnd()<.3?.5+rnd()*.25:.85+rnd()*.4));d=Math.min(11,d*(rnd()<.3?.5+rnd()*.25:.85+rnd()*.4));h=Math.max(5,h*(.55+rnd()*.95));const ci=rnd()<.7?0:Math.floor(rnd()*4),r=rnd();
 if(!cx&&!cz){if(!wallTex[5])wallTex[5]=cv(128,128,(x,w,h)=>{x.fillStyle='#8b8780';x.fillRect(0,0,w,h);for(let r=0;r<8;r++)for(let c=0;c<4;c++){x.fillStyle='hsl(40,4%,'+(48+rnd()*16)+'%)';x.fillRect(c*32+(r%2)*16+1,r*16+1,30,14)}spk(x,w,h,300,.2);x.fillStyle='#1d2228';x.fillRect(58,28,12,44)});
  const n0=ALL.length;part(0,0,14,14,34,5,0,13,2);[[-14,-14],[14,-14],[-14,14],[14,14]].forEach(([a,b])=>part(a,b,4.5,4.5,44,5,0,9,2));
  part(0,-44,44,2.5,15,5,3,.7,0);part(-44,0,2.5,44,15,5,3,.7,0);part(44,0,2.5,44,15,5,3,.7,0);part(-26,44,18,2.5,15,5,3,.7,0);part(26,44,18,2.5,15,5,3,.7,0);
  [[-44,-44],[44,-44],[-44,44],[44,44]].forEach(([a,b])=>part(a,b,6.5,6.5,28,5,0,11,2));
  for(let i=n0;i<ALL.length;i++)ALL[i].keep=1;return}
 if(r<.08)part(cx,cz,9+rnd()*2,3.6+rnd()*1.2,6+rnd()*4,k,1,3,ci);else if(r<.14)part(cx,cz,3.6+rnd()*1.2,9+rnd()*2,6+rnd()*4,k,2,3,ci);else if(r<.16)part(cx,cz,9+rnd()*3,4.3+rnd()*1.4,8+rnd()*5,k,1,3.5,ci);
 else if(r<.27){const q=3.8+rnd()*1.3;part(cx,cz,q,q,24+rnd()*10,k,0,8+rnd()*3,ci)}
 else if(r<.39)part(cx,cz,11+rnd(),11+rnd()*2,12+rnd()*4,k,rnd()<.5?1:2,5,ci);
 else if(r<.52){part(cx-w*.3,cz,w*.7,d,h,k,2,4,ci);part(cx+w*.5,cz+d*.35,w*.55,d*.6,h*.8,k,1,3,ci)}
 else if(r<.62)part(cx,cz,w,d,h,k,3,.7,ci);
 else part(cx,cz,w,d,h,k,r<.8?0:2,3+rnd()*3,ci)}
// 人間
function mkHuman(){const g=new T.Group(),skin=M(0xf0c8a8),jk=M(0x8a6a45),pn=M(0xe8e4d8),bt=M(0x3a2a20),gy=M(0x777b80),gn=M(0x3b5d3a),bl=M(0xdde3e8),wh=M(0xf4f1ea),o={g};
 const leg=x=>{const l=new T.Group();l.position.set(x,.9,0);g.add(l);mk(BG,pn,.2,.46,.22,0,-.23,0,l);const k=new T.Group();k.position.y=-.46;l.add(k);mk(BG,pn,.18,.42,.2,0,-.21,0,k);mk(BG,bt,.21,.14,.3,0,-.44,.05,k);return k};
 o.kR=leg(.13);o.kL=leg(-.13);o.lR=o.kR.parent;o.lL=o.kL.parent;
 mk(BG,pn,.34,.2,.24,0,.92,0,g);mk(BG,gy,.09,.34,.09,.33,.78,.12,g);mk(BG,gy,.09,.34,.09,-.33,.78,.12,g);mk(BG,M(0x4a3420),.2,.06,.24,.13,.72,0,g);mk(BG,M(0x4a3420),.2,.06,.24,-.13,.72,0,g);mk(BG,M(0x5a4630),.4,.07,.27,0,1,0,g);mk(BG,gy,.14,.2,.22,.27,.9,.03,g);mk(BG,gy,.14,.2,.22,-.27,.9,.03,g);
 const ub=new T.Group();ub.position.y=1;g.add(ub);o.ub=ub;
 mk(BG,jk,.44,.56,.28,0,.3,0,ub);mk(BG,wh,.46,.06,.3,0,.42,0,ub);mk(BG,wh,.3,.1,.3,0,.62,0,ub);mk(SG,gn,.17,.12,.18,0,.7,-.08,ub);mk(BG,M(0x4a3420),.06,.6,.3,.1,.3,0,ub);mk(BG,M(0x4a3420),.06,.6,.3,-.1,.3,0,ub);mk(SG,skin,.13,.15,.13,0,.78,0,ub);mk(SG,M(0x3a2a1c),.14,.11,.14,0,.84,-.02,ub);
 const cp=new T.Group();cp.position.set(0,.6,-.15);ub.add(cp);mk(BG,gn,.5,.85,.04,0,-.4,-.03,cp);o.cape=cp;
 const arm=x=>{const a=new T.Group();a.position.set(x,.56,0);ub.add(a);mk(BG,jk,.12,.28,.12,0,-.14,0,a);const e=new T.Group();e.position.y=-.28;a.add(e);mk(BG,jk,.1,.26,.1,0,-.13,0,e);mk(SG,skin,.05,.05,.05,0,-.28,0,e);mk(BG,bl,.025,.035,1,0,-.28,.5,e);mk(BG,M(0x222222),.05,.05,.16,0,-.28,.05,e);a.e=e;return a};
 o.aR=arm(.3);o.aL=arm(-.3);o.eR=o.aR.e;o.eL=o.aL.e;g.scale.setScalar(1.35);g.rotation.order='YXZ';S.add(g);return o}
// 巨人（目・足・うなじの弱点付き）
function mkTitanV2(x,z,runner){const g=new T.Group(),m=sk[Math.floor(rnd()*4)],s=(runner?.62:.72)+rnd()*.5,lm=[m.clone(),m.clone()],em=wht.clone(),hm=M([0x2e2218,0x5a4630,0x1a1410][Math.floor(rnd()*3)]);
 const up=new T.Group();up.position.y=6.5;up.rotation.x=.18;g.add(up);
 mk(BG,m,4.4,5.6,2.7,0,2.9,0,up);mk(BG,m,6,1.6,2.4,0,5.3,0,up);mk(SG,m,1.7,1.1,1,-1.2,4,1.2,up);mk(SG,m,1.7,1.1,1,1.2,4,1.2,up);if(rnd()<.5)mk(SG,m,2.4,2.4,1.7,0,.8,1,up);
 const hd=new T.Group();hd.position.set(0,6.8,.6);up.add(hd);
 mk(SG,m,1.7,1.9,1.8,0,0,0,hd);mk(BG,m,2.4,1.1,1.8,0,-1.5,.45,hd);mk(BG,blk,2,.5,.3,0,-1.1,1.45,hd);for(let i=-2;i<=2;i++)mk(BG,wht,.3,.38,.2,i*.36,-1.1,1.6,hd);
 for(const e of[-.75,.75]){mk(SG,em,.38,.38,.3,e,.35,1.45,hd);mk(SG,blk,.17,.17,.12,e,.35,1.72,hd)}
 mk(BG,m,.5,.6,.5,0,-.3,1.7,hd);mk(BG,m,2.6,.3,.5,0,.85,1.5,hd);mk(SG,hm,1.8,1.5,1.9,0,.6,-.3,hd);if(rnd()<.4)mk(BG,hm,1.9,2.4,.7,0,-.5,-1.5,hd);mk(SG,redM,.5,.5,.5,NAPE.x,NAPE.y,NAPE.z,up);
 const arm=x=>{const a=new T.Group();a.position.set(x,5.1,0);up.add(a);mk(BG,m,1.4,3.4,1.4,0,-1.7,0,a);const e=new T.Group();e.position.y=-3.4;a.add(e);mk(BG,m,1.25,3.3,1.25,0,-1.65,0,e);mk(SG,m,.9,.9,.9,0,-3.4,0,e);a.e=e;return a};
 const leg=(x,i)=>{const l=new T.Group();l.position.set(x,6.5,0);g.add(l);mk(BG,lm[i],2,3.3,2.2,0,-1.65,0,l);const k=new T.Group();k.position.y=-3.3;l.add(k);mk(BG,lm[i],1.8,3.2,2,0,-1.6,0,k);mk(BG,lm[i],2.1,.7,3.2,0,-3.2,.7,k);l.k=k;return l};
 const aR=arm(3.4),aL=arm(-3.4);mk(BG,m,4,2,2.5,0,6.5,0,g);mk(shG,shM,5,1,5,0,.06,0,g);g.scale.setScalar(s);g.position.set(x,0,z);g.rotation.y=Math.PI*1.5;S.add(g);
 return{g,up,hd,aR,aL,eR:aR.e,eL:aL.e,lg:[leg(1.2,0),leg(-1.2,1)],lm,em,skin:m.color,cut:[0,0],blind:0,lastE:-1,lastN:-1,hp:1,lastL:[-1,-1],s,runner,sp:(runner?7:3+rnd()*1.4)+wave*.25,st:0,at:1,tm:0,cd:1.5,ph:rnd()*6,dead:0,dt:0,aim:-1,hit:0,nw:V(),ew:V(),lw:[V(),V()]}}
function titanStep(dt,pc){const p=P.p,gy=P.p.y-gh(P.p.x,P.p.z),sc=pc.clone().addScaledVector(P.sd,2.5);
 for(const t of titans){const g=t.g,s=t.s;
  if(t.dead){t.dt+=dt;g.rotation.x=Math.min(t.dt*1.1,1.45);if(t.dt>1.2)g.position.y-=3*dt;if(rnd()<dt*14)puff(g.localToWorld(V(0,9,0)),1,1.5);if(P.held===t)P.held=null;if(t.eatC){if(t.eatC.sol)t.eatC.sol.ct=3;t.eatC.carried=0;t.eatC=null}continue}
  if(!Number.isFinite(t.sp))t.sp=3.5;if(!Number.isFinite(g.position.x+g.position.z))g.position.set(330,0,0);t.px=g.position.x;t.pz=g.position.z;t.blind=Math.max(0,t.blind-dt);if(t.wasB&&t.blind<=0){t.em.color.setHex(0xf2eee6);t.wasB=0}
  if(t.armCut>0){t.armCut-=dt;if(t.armCut<=0)t.aR.visible=true}
  for(let i=0;i<2;i++)if(t.cut[i]>0){t.cut[i]-=dt;if(rnd()<dt*8)puff(t.lw[i],1,.7);if(t.cut[i]<=0)t.lm[i].color.copy(t.skin)}
  const kneel=t.cut[0]>0&&t.cut[1]>0,limp=t.cut[0]>0||t.cut[1]>0,blind=t.blind>0;
  const dx=p.x-g.position.x,dz=p.z-g.position.z,L=Math.hypot(dx,dz)||1;
  let cvT=t.eatC&&t.eatC.alive?t.eatC:null;if(!cvT&&t.st==0&&!blind&&!kneel){let bd=70*s;for(const c of CV)if(c.alive&&!c.carried){const d=Math.hypot(c.x-g.position.x,c.z-g.position.z);if(d<bd&&d<L*.9){bd=d;cvT=c}}}
  let sT=null;if(!cvT&&t.st==0&&!blind){let bd=Math.min(L*.9,70*s);for(const q of SOL)if(q.alive){const d=Math.hypot(q.p.x-g.position.x,q.p.z-g.position.z);if(d<bd){bd=d;sT=q}}}
  let tdx=cvT?cvT.x-g.position.x:sT?sT.p.x-g.position.x:dx,tdz=cvT?cvT.z-g.position.z:sT?sT.p.z-g.position.z:dz;
  {const rt=Math.hypot(g.position.x,g.position.z),tr=Math.hypot(g.position.x+tdx,g.position.z+tdz),lane=Math.abs(g.position.z)<=10;if(rt>=300&&tr<297){tdx=(lane?285:318)-g.position.x;tdz=-g.position.z}else if(rt<300&&tr>303){tdx=(lane?320:282)-g.position.x;tdz=-g.position.z}}
  if(blind)g.rotation.y+=Math.sin(t.ph*.6)*dt*1.2;else{let da=Math.atan2(tdx,tdz)-g.rotation.y;da=Math.atan2(Math.sin(da),Math.cos(da));const tn=(t.st==0?2.4:t.st==1?2.2:.5)*dt;g.rotation.y+=Math.max(-tn,Math.min(tn,da))}
  const spd=t.sp*(kneel?.2:limp?.55:1);t.cd-=dt;if(blind&&t.st==0&&t.cd<=0&&rnd()<dt*1.5){t.at=[1,3,2][Math.floor(rnd()*3)];t.st=1;t.tm=.7;t.hit=0;t.aim=-1.2-rnd()*.8;g.rotation.y+=(rnd()-.5)*2}if(blind)g.rotation.y+=(rnd()-.5)*dt*5;
  if(t.st==0){g.position.x+=Math.sin(g.rotation.y)*spd*dt;g.position.z+=Math.cos(g.rotation.y)*spd*dt;t.ph+=dt*spd*.9;{const sn=Math.sin(t.ph);if(sn<-.95&&!t.fs){t.fs=1;if(L<90){shake=Math.max(shake,.15*Math.min(1,s*40/L));puff(V(g.position.x+(rnd()-.5)*4*s,g.position.y+.5,g.position.z+(rnd()-.5)*4*s),2,1.3*s,0xb8aa94);sfx(55,.25,'sine',Math.min(.3,9/L))}}else if(sn>0)t.fs=0}
   if(!blind&&t.cd<=0&&cvT){if(Math.hypot(cvT.x-g.position.x,cvT.z-g.position.z)<5*s+2){t.st=4;t.tm=1.6;t.eatC=cvT;cvT.carried=1;scream(cvT.x,cvT.z)}}else if(!blind&&t.cd<=0&&sT&&!(t.armCut>0)&&Math.hypot(sT.p.x-g.position.x,sT.p.z-g.position.z)<8*s+5){t.at=1;t.atS=1;t.sTg=sT;t.st=1;t.tm=.7;t.hit=0}else if(!blind&&t.cd<=0){const near=L<6*s&&gy<5&&!kneel,rg=L<8*s+6&&gy<17*s;if((near||rg)&&!(t.armCut>0&&!near)){const r=rnd();t.atS=0;t.at=t.armCut>0?2:(r<.18&&!P.held&&!P.tf&&gy<10*s)?5:near?(r<.55?2:r<.82?3:1):(gy>9*s?1:(r<.4?1:r<.7?3:4));t.st=1;t.tm=t.at==2?.6:t.at==4?.5:.7;t.hit=0}else if(L<30*s&&!kneel&&!(t.armCut>0)&&rnd()<dt*.6){t.atS=0;t.at=4;t.st=1;t.tm=.5;t.hit=0}}}
  else{t.tm-=dt;if(t.st==1&&t.at!=2&&!blind){const T2=t.atS&&t.sTg&&t.sTg.alive?t.sTg.p:null,dy=(T2?T2.y+1:pc.y)-(g.position.y+11*s),LL2=T2?Math.hypot(T2.x-g.position.x,T2.z-g.position.z):L;t.aim=Math.max(-3,Math.min(-.2,Math.atan2(-LL2,-dy)))-.7}
   if(t.tm<=0){if(t.st==1){t.st=2;t.tm=.35}else if(t.st==2){t.st=3;t.tm=.8}else{t.st=0;t.cd=1.8}}}
  const sw=Math.sin(t.ph)*(t.runner?.9:.5)*(kneel?.1:1);
  t.lg.forEach((l,i)=>{const q=sw*(i?-1:1);l.rotation.x=q;l.k.rotation.x=Math.max(0,q)*1.1});
  let ta=t.runner?-1.2+sw*.9:-sw*.8,tl=t.bl+(t.runner?.35:0),te=t.runner?-.9:-.3;
  if(P.held===t){const hw=t.eR.localToWorld(V(0,-3.6,0));p.set(hw.x,hw.y-1,hw.z);P.v.set(0,0,0);P.a=null;if(t.eatP&&t.tm<.8){const mw=t.hd.localToWorld(V(0,-1.2,1.6)),k=1-t.tm/.8;p.set(hw.x+(mw.x-hw.x)*k,hw.y-1+(mw.y-hw.y+1)*k,hw.z+(mw.z-hw.z)*k)}
   if(P.mash>=4){P.held=null;t.holding=0;t.st=3;t.tm=1.2;P.v.set(0,7,0);P.inv=1.2;toast('腕を斬り落とした！ 脱出！');puff(hw,10,1.2,0xcc2222);t.armCut=14;t.aR.visible=false;{const am=new T.Mesh(CG,M(t.skin.getHex()));am.scale.set(1.1*t.s,6*t.s,1.1*t.s);am.position.copy(hw);S.add(am);DB.push({m:am,v:V(0,2,0),w:V(1,0,1)});setTimeout(()=>S.remove(am),15000)}}
   else if(t.st!=5){P.held=null;t.holding=0;if(t.eatP){scream(P.p.x,P.p.z,1);decal(P.p.x,P.p.z,3);P.hp=0;toast('食べられた…');run=false;gameOver()}else{hurt(0,0);P.v.set(Math.sin(g.rotation.y)*38,15,Math.cos(g.rotation.y)*38);toast('投げ飛ばされた！');shake=1}}}
  if(t.eatC){const c=t.eatC;if(t.st==4&&c.alive){g.updateMatrixWorld(true);const hw=t.eR.localToWorld(V(0,-3.6,0)),mw=t.hd.localToWorld(V(0,-1.2,1.6)),k=1-Math.max(0,t.tm)/1.1;if(t.tm>1.1){const d=Math.hypot(c.x-g.position.x,c.z-g.position.z)||1;if(d>2.5*s){g.position.x+=(c.x-g.position.x)/d*3*dt;g.position.z+=(c.z-g.position.z)/d*3*dt}}else c.g.position.set(hw.x+(mw.x-hw.x)*k,hw.y+(mw.y-hw.y)*k,hw.z+(mw.z-hw.z)*k)}else{if(c.alive){c.alive=0;if(c.sol){c.sol.h.g.visible=false}else{S.remove(c.g);ate++}puff(t.ew,10,1.2,0xaa1111);decal(c.x,c.z,2);toast(c.sol?'仲間が食べられた…':'市民が食べられた…');sfx(90,.4,'sine',.2)}t.eatC=null}}
  let tw=t.st==0?Math.sin(t.ph)*.1:0;if(blind&&t.st==0){ta=-2.4;te=-1.6;tl=.3}else if(t.st==1){if(t.at==1||t.at==5){ta=-2.8;te=-1}else if(t.at==3){ta=t.aim;te=-.1;tw=-1.1}else if(t.at==4){ta=-2.4;te=-1}tl=t.at==4?-.2:-.1}else if(t.st==2){if(t.at==3){ta=t.aim;te=0;tw=1.1}else if(t.at!=2){ta=t.aim;te=0}tl=t.at==2?.2:.7;if(t.at==4){g.position.x+=Math.sin(g.rotation.y)*16*dt;g.position.z+=Math.cos(g.rotation.y)*16*dt}}else if(t.st==4){const a4=t.tm>1.1;ta=a4?-.7:-2.2;te=a4?-.2:-2;tl=a4?.95:.05}else if(t.st==5){ta=-2.3;te=-1.6;tl=.1}else if(t.st==3){if(t.at!=2)ta=t.aim*.6;te=-.2;tl=.4}t.up.rotation.y+=(tw-t.up.rotation.y)*Math.min(1,(t.st==2?20:8)*dt);
  const k=Math.min(1,(t.st==2?30:9)*dt);t.aR.rotation.x+=(ta-t.aR.rotation.x)*k;t.eR.rotation.x+=(te-t.eR.rotation.x)*k;
  t.aL.rotation.x=blind?-2.4:sw*.8;t.eL.rotation.x=blind?-1.6:-.3;t.up.rotation.x+=(tl-t.up.rotation.x)*Math.min(1,8*dt);
  if(t.at==2&&!blind){if(t.st==1)t.lg[0].rotation.x=-1.4;else if(t.st==2)t.lg[0].rotation.x=-.5}
  if(kneel)t.lg.forEach(l=>{l.rotation.x=-1.4;l.k.rotation.x=1.6});
  for(let i=B.length-1;i>=0;i--){const b=B[i];if(b.keep){const kx=b.w+2.5*s,kz=b.d+2.5*s,ex=g.position.x-b.x,ez=g.position.z-b.z;if(Math.abs(ex)<kx&&Math.abs(ez)<kz){if(kx-Math.abs(ex)<kz-Math.abs(ez))g.position.x=b.x+Math.sign(ex||1)*kx;else g.position.z=b.z+Math.sign(ez||1)*kz}}else if(Math.abs(g.position.x-b.x)<b.w+2*s&&Math.abs(g.position.z-b.z)<b.d+2*s){b.dc=(b.dc||0)-dt;if(b.dc<=0){b.dc=.7;if(dmgHouse(b,g.position.x,g.position.z,22*s*s))B.splice(i,1)}}}
  const by=gh(g.position.x,g.position.z)+(kneel?-3.4*s:(t.st==0?Math.abs(Math.sin(t.ph))*.3*s:0));g.position.y+=(by-g.position.y)*Math.min(1,10*dt);
  {const gx=g.position.x,gz=g.position.z,rr=Math.hypot(gx,gz)||1,md=3.2*s+1,lane=gx>0&&Math.abs(gz)<17;if(Math.abs(rr-300)<md&&!lane){const n=Math.hypot(t.px,t.pz)<300?300-md:300+md;g.position.x=gx*n/rr;g.position.z=gz*n/rr}}
  for(const o of titans){if(o===t||o.dead)continue;const ox=g.position.x-o.g.position.x,oz=g.position.z-o.g.position.z,od=Math.hypot(ox,oz)||.1,mn=3.2*(s+o.s);if(od<mn){g.position.x+=ox/od*(mn-od)*.5;g.position.z+=oz/od*(mn-od)*.5}}
  if(t.st==1&&!t.ro){t.ro=1;roar(t)}if(t.st!=1)t.ro=0;if(rnd()<dt*2.5)puff(t.nw,1,.45,0xffffff);t.up.rotation.z=Math.sin(t.ph)*(t.runner?.12:.05);t.hd.rotation.y=blind?Math.sin(t.ph*9)*.35:Math.sin(t.ph*.3)*.25;t.up.scale.y=1+Math.sin(performance.now()/500+t.ph)*.02;t.hd.rotation.z=Math.sin(t.ph*.7)*.12;t.hd.rotation.x=Math.sin(t.ph*.5)*.08;g.updateMatrixWorld(true);t.up.localToWorld(t.nw.copy(t.np));t.hd.localToWorld(t.ew.set(0,.35,1.8));t.lg.forEach((l,i)=>l.localToWorld(t.lw[i].set(0,-3.3,0)));if(t.frag&&P.sl>0&&[t.nw,t.ew,t.lw[0],t.lw[1],V(g.position.x,g.position.y+6*s,g.position.z)].some(q=>hitD(pc,q)<2+s)){kill(t);toast('脆い！');continue}
  if(t.st==2){const hw=t.eR.localToWorld(V(0,-3.6,0));for(const q of SOL)if(q.alive&&q.inv<=0&&hw.distanceTo(V(q.p.x,q.p.y+1,q.p.z))<6.4*s+2){if(!t.eatC&&t.st!=4&&rnd()<.5&&q.p.y-gh(q.p.x,q.p.z)<6){q.alive=0;q.rt=10;q.ct=0;q.a=null;q.rp.visible=false;q.v.set(0,0,0);t.eatC={g:q.h.g,x:q.p.x,z:q.p.z,alive:1,carried:1,sol:q};t.st=4;t.tm=1.6;scream(q.p.x,q.p.z)}else killSol(q,Math.sin(g.rotation.y),Math.cos(g.rotation.y))}}
  if(t.st==2&&!t.hit){const ry=g.rotation.y;
   if(t.at!=2){if(t.eR.localToWorld(V(0,-3.6,0)).distanceTo(pc)<6.4*s+1+(P.tf?5*P.tm.s:0)){t.hit=1;if(t.at==5&&!P.tf&&P.inv<=0&&!P.held){P.held=t;P.mash=0;P.a=null;rope.visible=false;t.holding=1;t.st=5;t.tm=2.2;t.eatP=rnd()<.5;toast('掴まれた！ 「斬る」連打で脱出！')}else hurt(Math.sin(ry),Math.cos(ry))}}
   else{const f=t.lg[0].localToWorld(V(0,-6.4,.7));if(Math.hypot(f.x-p.x,f.z-p.z)<7*s+(P.tf?4*P.tm.s:0)&&gy<5){t.hit=1;puff(f,6,2.5,0xb8aa94);shake=.5;hurt(Math.sin(ry),Math.cos(ry))}}}
  if(P.sl>0){
   if(t.lastN!=sid&&behind(t,p)&&hitD(pc,t.nw)<1.4+1.1*s){t.lastN=sid;if(--t.hp<=0){kill(t);toast('うなじを削いだ！');continue}puff(t.nw,6,1,0xcc2222);toast('浅い！もう一撃！')}
   if(t.lastE!=sid&&!t.arm&&!behind(t,p)&&hitD(pc,t.ew)<1.3+.8*s){t.lastE=sid;t.blind=4;t.wasB=1;t.em.color.setHex(0x6a1010);puff(t.ew,5,.8,0xcc2222);toast('目を潰した！')}
   for(let i=0;i<2;i++)if(t.lastL[i]!=sid&&!t.arm&&hitD(pc,t.lw[i])<1.8+1.2*s){t.lastL[i]=sid;t.cut[i]=9;t.lm[i].color.setHex(0xa03a30);puff(t.lw[i],6,1,0xcc2222);toast(t.cut[0]>0&&t.cut[1]>0?'両足を断った！倒れた！':'足を切った！')}}}}
function slash(){if(P.held){P.mash=(P.mash||0)+1;sfx(300,.05,'square',.1);return}if(P.tf){tAtk();return}if(!run||P.sl>0||P.slc>0)return;
 if(!P.g&&Math.hypot(P.v.x,P.v.z)>8){P.sl=P.sp=.45;P.slc=.8;P.spy=H.g.rotation.y;P.v.y+=3;sid++;sfx(700,.3,'sawtooth',.1);puff(V(P.p.x,P.p.y+1,P.p.z),4,1);return}P.sl=.28;P.slc=.5;sid++;sfx(900,.15,'sawtooth',.08);
 const c=P.p.clone().setY(P.p.y+1);let bp=null,bd=1e9;
 for(const t of titans)if(!t.dead)for(const[q,w]of[[t.nw,1],[t.ew,1.4],[t.lw[0],1.9],[t.lw[1],1.9]]){const d=q.distanceTo(c)*w;if(d<bd&&d<26){bd=d;bp=q}}
 if(lockT&&!lockT.dead)bp=lockT.nw;
 if(bp){P.sd.copy(bp).sub(c).normalize();P.v.addScaledVector(P.sd,18)}else P.sd.set(-Math.sin(yaw),0,-Math.cos(yaw))}
function lockPress(){if(lockT){lockT=null;return}const f=new T.Vector3();C.getWorldDirection(f);let bt=null,bs=-9;
 for(const t of titans)if(!t.dead){const d=t.nw.clone().sub(C.position),L=d.length(),s=d.divideScalar(L).dot(f)-L*.002;if(s>bs){bs=s;bt=t}}
 lockT=bt}
function render(dt){const p=P.p,v=P.v,tm=performance.now()/1000,g=H.g,sp=Math.hypot(v.x,v.z);
 if(lockT&&(lockT.dead||!titans.includes(lockT)))lockT=null;
 if(lockT&&!look&&performance.now()-lkIdle>900){const d=lockT.nw.clone().sub(p),hh=Math.hypot(d.x,d.z)||1;let da=Math.atan2(-d.x,-d.z)-yaw;da=Math.atan2(Math.sin(da),Math.cos(da));yaw+=da*Math.min(1,5*dt);pitch+=(Math.max(-1,Math.min(.8,.32-Math.atan2(d.y,hh)*.7))-pitch)*Math.min(1,4*dt)}
 g.position.copy(p);g.visible=!(P.inv>0&&Math.floor(P.inv*10)%2);
 if(P.tf)g.visible=false;if(P.g&&!H.pg&&H.pv<-8){H.land=.25;puff(V(p.x,p.y+.3,p.z),3,.8,0xb8aa94)}H.pg=P.g;H.pv=v.y;H.land=Math.max(0,(H.land||0)-dt);g.scale.set(1.35,1.35*(1-.18*H.land/.25),1.35);
 if(P.g&&sp>12&&rnd()<dt*14)puff(V(p.x,p.y+.2,p.z),1,.35,0xb8aa94);H.cape.rotation.z=Math.sin(tm*9)*.1*Math.min(1,sp/20);
 const rn=P.g?Math.min(1,sp/9):0,ph=tm*13,s1=Math.sin(ph)*.95*rn;
 if(P.sl>0)g.rotation.y=Math.atan2(P.sd.x,P.sd.z);else if(sp>1)g.rotation.y=Math.atan2(v.x,v.z);
 if(P.g){H.lR.rotation.x=s1;H.lL.rotation.x=-s1;H.kR.rotation.x=Math.max(0,s1)*1.3;H.kL.rotation.x=Math.max(0,-s1)*1.3;H.aR.rotation.x=-s1*.8;H.aL.rotation.x=s1*.8;H.eR.rotation.x=H.eL.rotation.x=-1.1*rn-.15;H.ub.rotation.x=.2*rn;g.rotation.x=0;g.position.y+=Math.abs(Math.cos(ph))*.07*rn;H.ub.position.y=1+Math.sin(tm*2)*.01*(1-rn)}
 else{H.lR.rotation.x=-.5;H.kR.rotation.x=1.1;H.lL.rotation.x=.25;H.kL.rotation.x=.5;H.aR.rotation.x=P.a?-2.7:.5;H.aL.rotation.x=P.a?-2.7:-.5;H.eR.rotation.x=H.eL.rotation.x=P.a?-.1:-.5;H.ub.rotation.x=.1;g.rotation.x=Math.min(.8,sp/35)}
 if(P.sp>0){g.rotation.y=P.spy+(1-P.sp/.45)*6.283;H.ub.rotation.y=0;H.aR.rotation.x=H.aL.rotation.x=-1.5;H.eR.rotation.x=H.eL.rotation.x=-.2;g.rotation.x=.3}else if(P.sl>0){const k=1-P.sl/.28;H.ub.rotation.y=-1.1+2.2*k;H.aR.rotation.x=-1.5;H.eR.rotation.x=-.3;H.aL.rotation.x=-.9;H.eL.rotation.x=-.6;g.rotation.x=.15}else H.ub.rotation.y*=.85;
 H.cape.rotation.x=.2+Math.min(1,Math.hypot(sp,v.y)/28)*1.1;
 arc.position.set(p.x,p.y+1.2,p.z);arc.rotation.y=g.rotation.y;arc.material.opacity=P.sl>0?P.sl/.28*.8:0;
 pSh.position.set(p.x,.06,p.z);pSh.scale.setScalar(Math.max(.3,.9-p.y/60));
 if(P.a){const a=rope.geometry.attributes.position;a.setXYZ(0,p.x,p.y+1.4,p.z);a.setXYZ(1,P.a.pos.x,P.a.pos.y,P.a.pos.z);a.needsUpdate=true}
 shake=Math.max(0,shake-dt*1.5);const cp=Math.cos(pitch);
 C.position.set(p.x+Math.sin(yaw)*cp*10+(rnd()-.5)*shake,Math.max(.6,p.y+2.5+Math.sin(pitch)*10)+(rnd()-.5)*shake,p.z+Math.cos(yaw)*cp*10);
 C.lookAt(p.x,p.y+2,p.z);C.fov+=(68+Math.min(18,Math.hypot(sp,v.y)*.45)-C.fov)*Math.min(1,5*dt);const cz=P.tf?3*P.tm.s:1;{const gq=gh(p.x,p.z);pSh.position.y=gq+.06;pSh.scale.setScalar(Math.max(.3,.9-(p.y-gq)/60));const ry=p.y+(2.5+Math.sin(pitch)*10)*cz,cxx=p.x+Math.sin(yaw)*cp*10*cz,czz=p.z+Math.cos(yaw)*cp*10*cz,cy=Math.max(gh(cxx,czz)+1,ry);C.position.set(cxx+(rnd()-.5)*shake,cy+(rnd()-.5)*shake,czz);C.lookAt(p.x,p.y+2*cz+Math.max(0,cy-ry)*3,p.z)}C.updateProjectionMatrix();sun.position.set(p.x-80,p.y+120,p.z+60);sun.target.position.copy(p);C.updateMatrixWorld();sky.position.copy(C.position);sunD.position.copy(C.position).addScaledVector(sunDir,540);
 $('hp').textContent='♥'.repeat(Math.max(0,P.hp));$('gb').style.width=P.gas+'%';
 const al=titans.filter(t=>!t.dead);$('wv').innerHTML='WAVE '+wave+'<br>残り '+al.length+'体／討伐 '+score;
 $('hp').textContent=P.tf?'🔥'+'■'.repeat(Math.max(0,Math.ceil(P.th))):'♥'.repeat(Math.max(0,P.hp));$('tb').style.width=(P.tf?P.th/F[form].hp*100:P.tg)+'%';
 $('vr').style.opacity=P.tf?0:(P.hp<=2?.35+Math.sin(tm*6)*.2:0);$('sp').style.opacity=Math.max(0,Math.min(.55,(Math.hypot(sp,v.y)-20)/30));cT=Math.max(0,cT-dt);$('wv').innerHTML='討伐 '+score+'　巨人 '+al.length+'体'+(cT>0&&combo>1?'<br>連続撃破 x'+combo:'')+'<br>市民 '+CV.filter(c=>c.alive).length+' 犠牲 '+ate+'<br>仲間 '+SOL.filter(q=>q.alive).length+'/'+SOL.length;
 const lb=$('lk'),want=lockT?'解除':'ロック';if(lb.textContent!==want)lb.textContent=want;lb.style.background=lockT?'#a21c':'';
 let nt=lockT,nd=1e9;if(!nt)for(const t of al){const d=Math.hypot(t.g.position.x-p.x,t.g.position.z-p.z);if(d<nd){nd=d;nt=t}}
 $('ar').style.display=nt&&run?'block':'none';
 if(nt){const dx=nt.g.position.x-p.x,dz=nt.g.position.z-p.z;$('ar').style.transform=`rotate(${Math.atan2(dx*Math.cos(yaw)-dz*Math.sin(yaw),-dx*Math.sin(yaw)-dz*Math.cos(yaw))}rad) translateY(-85px)`}
 const rc=$('rd').getContext('2d');rc.clearRect(0,0,90,90);rc.fillStyle='#fff';rc.fillRect(43,43,4,4);
 for(const t of al){const dx=t.g.position.x-p.x,dz=t.g.position.z-p.z;let rx=(dx*Math.cos(yaw)-dz*Math.sin(yaw))*.25,ry=(dx*Math.sin(yaw)+dz*Math.cos(yaw))*.25;const l=Math.hypot(rx,ry);if(l>40){rx*=40/l;ry*=40/l}rc.fillStyle=t===lockT?'#ff0':'#f33';rc.beginPath();rc.arc(45+rx,45+ry,3,0,6.3);rc.fill()}
 const lm=$('lm');
 {let k=0;for(const t of al){if(k>=14)break;const q=t.nw.clone().project(C),d=Math.hypot(t.g.position.x-p.x,t.g.position.z-p.z),m=TM[k++];if(q.z<1&&d>25){m.style.display='block';m.style.left=(q.x*.5+.5)*innerWidth+'px';m.style.top=(-q.y*.5+.5)*innerHeight-8+'px';m.textContent='▼ '+Math.round(d)+'m'}else m.style.display='none'}for(;k<14;k++)TM[k].style.display='none'}if(lockT){const q=lockT.nw.clone().project(C);if(q.z<1){lm.style.display='block';lm.style.left=(q.x*.5+.5)*innerWidth+'px';lm.style.top=(-q.y*.5+.5)*innerHeight+'px'}else lm.style.display='none'}else lm.style.display='none';
 R.render(S,C)}
buildCity();
let slow=0,AC=null,lkIdle=0;bindBtn($('jp'),jump,()=>{});
function jump(){if(!run||!P.g||P.held)return;P.v.y=14;P.g=false;sfx(400,.1,'square',.05)}
function bigify(t,w=wave){skinize(t);t.sp*=.8;t.aR.scale.set(.85,1,.85);t.aL.scale.set(.85,1,.85);t.g.traverse(o=>{if(o.isMesh&&o.material!==shM)o.castShadow=true});const rr=rnd();if(rr<.04){t.s=1.7+rnd()*.5;t.g.scale.setScalar(t.s);t.sp=2.6+rnd()*.8+w*.15;t.hp=2;t.runner=false;toast('大型巨人が現れた！')}else if(rr<.055&&!titans.some(o=>o.arm&&!o.dead)){armorize(t)}else if(rr<.06&&!titans.some(o=>o.col&&!o.dead)){colossalize(t)}else if(rr<.12){t.frag=1;t.s=.5+rnd()*.15;t.g.scale.setScalar(t.s);t.sp=5+rnd()*2+w*.2;t.skin.setHex(0xc9c2b8);t.lm.forEach(l=>l.color.setHex(0xc9c2b8));toast('脆い巨人が混ざっている！')}return t}
function sfx(f,d,ty='sawtooth',v=.12){try{AC=AC||new(window.AudioContext||window.webkitAudioContext)();const o=AC.createOscillator(),g=AC.createGain(),n=AC.currentTime;o.type=ty;o.frequency.setValueAtTime(f,n);o.frequency.exponentialRampToValueAtTime(Math.max(30,f*.4),n+d);g.gain.setValueAtTime(v,n);g.gain.exponentialRampToValueAtTime(.001,n+d);o.connect(g);g.connect(AC.destination);o.start();o.stop(n+d)}catch(e){}}
[-22,22].forEach(z=>{const q=new T.Mesh(BG,M(0x77736b));q.scale.set(8,48,6);q.position.set(296,24,z);S.add(q)});
{const crate=M(0x7a5a3a),barrel=M(0x6a4a2a),lamp=M(0x2a2a2a),glow=M(0xffe9a0);
 for(let i=0;i<90;i++){const a=rnd()*6.283,r=rnd()*270,x=Math.cos(a)*r,z=Math.sin(a)*r;if(B.some(b=>Math.abs(x-b.x)<b.w+3&&Math.abs(z-b.z)<b.d+3))continue;const k=rnd();
  if(k<.4){const c=new T.Mesh(BG,crate);c.scale.set(1.4,1.4,1.4);c.position.set(x,gh(x,z)+.7,z);c.rotation.y=rnd()*3;S.add(c)}
  else if(k<.75){const c=new T.Mesh(new T.CylinderGeometry(.6,.6,1.3,8),barrel);c.position.set(x,gh(x,z)+.65,z);S.add(c)}
  else{const c=new T.Mesh(BG,lamp);c.scale.set(.25,5,.25);c.position.set(x,gh(x,z)+2.5,z);S.add(c);const l=new T.Mesh(BG,glow);l.scale.set(.7,.7,.7);l.position.set(x,gh(x,z)+5.2,z);S.add(l)}}}
function segD(a,d,q){const w=q.clone().sub(a),t=Math.max(0,Math.min(4.2,w.dot(d)));return q.distanceTo(a.clone().addScaledVector(d,t))}
function behind(t,p){const dx=p.x-t.g.position.x,dz=p.z-t.g.position.z,l=Math.hypot(dx,dz)||1;return(dx*Math.sin(t.g.rotation.y)+dz*Math.cos(t.g.rotation.y))/l<.45}
R.shadowMap.enabled=true;R.shadowMap.type=T.PCFSoftShadowMap;sun.castShadow=true;sun.shadow.mapSize.set(1024,1024);sun.shadow.bias=-.0006;{const c=sun.shadow.camera;c.left=c.bottom=-100;c.right=c.top=100;c.far=500;c.updateProjectionMatrix()}S.add(sun.target);
S.traverse(o=>{if(!o.isMesh||o===sky||o===arc||o.geometry===PG||o.material===shM)return;o.receiveShadow=true;if(o!==gr&&o!==wtop)o.castShadow=true});
{const gs=new T.Mesh(new T.RingGeometry(304,900,48),M(0x586b3f));gs.rotation.x=-Math.PI/2;gs.position.y=.03;gs.receiveShadow=true;S.add(gs)}
function mkTitanV3(x,z,runner,fo){const g=new T.Group(),ty=fo?fo.ty:Math.floor(rnd()*5),fc=fo?fo.fc:Math.floor(rnd()*4),hs=fo?fo.hs:Math.floor(rnd()*4),s=(runner?.62:.72)+rnd()*.5,
 m=M([0xe8c9ae,0xdcb496,0xcfa58a,0xe3bf9f,0xf0d6c0,0xb88f78,0xd9b0a0][Math.floor(rnd()*7)]),lm=[m.clone(),m.clone()],em=wht.clone(),hm=M([0x2e2218,0x5a4630,0x1a1410,0xb8a070,0x8a8a88,0x6a3a22][Math.floor(rnd()*6)]),
 W=[1,.78,1.3,1.25,1][ty],A=[1,1.2,1.15,.95,1][ty],LL=[1,1.12,.95,.85,1][ty],HS=[1,.9,1,1,1.35][ty],bl=.08+rnd()*.3,H0=6.5*LL,ew=.3+rnd()*.2;
 const up=new T.Group();up.position.y=H0;up.rotation.x=bl;g.add(up);
 mk(BG,m,4.4*W,5.6,2.7*W,0,2.9,0,up);mk(BG,m,6*W,1.6,2.4*W,0,5.3,0,up);mk(BG,m,1.3,1.4,1.3,0,6.1,0,up);for(let i=0;i<4;i++)mk(BG,lineM,3.2*W,.08,.05,0,1.2+i*.9,1.38*W,up);mk(BG,lineM,.08,3.4,.05,0,2.6,1.38*W,up);for(let i=0;i<6;i++)mk(SG,m,.4,.35,.35,0,.8+i*.8,-1.38*W,up);
 if(ty==2){mk(SG,m,1.9,1.5,1.1,-1.3,4,1.3,up);mk(SG,m,1.9,1.5,1.1,1.3,4,1.3,up)}else if(ty==3)mk(SG,m,3,3,2.4,0,1,1.1,up);else{mk(SG,m,1.7,1.1,1,-1.2,4,1.2,up);mk(SG,m,1.7,1.1,1,1.2,4,1.2,up)}
 const hd=new T.Group();hd.position.set(0,6.8,.6);hd.scale.setScalar(HS);up.add(hd);
 mk(SG,m,1.7,1.9,1.8,0,0,0,hd);mk(BG,m,2.4,1.1,1.8,0,-1.5,.45,hd);mk(SG,m,.35,.6,.3,-1.7,0,0,hd);mk(SG,m,.35,.6,.3,1.7,0,0,hd);
 const mw=[2,1.6,2.5,1.2][fc],mh=[.5,1.2,.7,.3][fc],nt=[5,3,7,0][fc],my=-1.2-mh*.2;mk(BG,blk,mw,mh,.3,0,my,1.45,hd);
 for(let r=0;r<(fc==1?2:1);r++)for(let i=0;i<nt;i++){const sp=mw/(nt+1);mk(BG,wht,sp*.8,.36,.2,(i-(nt-1)/2)*sp,my+(r?-1:1)*mh*.35,1.6,hd)}
 for(const e of[-.75,.75]){mk(SG,em,ew,ew,.3,e,.35,1.45,hd);mk(SG,blk,ew*.45,ew*.45,.12,e,.35,1.72,hd);mk(BG,m,ew*2.1,ew*.8,.35,e,.35+ew*.9,1.62,hd);mk(BG,lineM,ew*2,.06,.05,e,.35-ew*1.2,1.75,hd)}
 mk(BG,m,.4+rnd()*.4,.5+rnd()*.4,.5,0,-.3,1.7,hd);mk(SG,m,.6,.5,.5,-1.1,-.35,1.15,hd);mk(SG,m,.6,.5,.5,1.1,-.35,1.15,hd);mk(BG,lineM,.14,.14,.1,-.2,-.55,1.95,hd);mk(BG,lineM,.14,.14,.1,.2,-.55,1.95,hd);mk(BG,m,2.6,.3,.5,0,.85,1.5,hd);
 if(hs>0){mk(SG,hm,hs==3?2:1.8,hs==3?1.7:1.5,hs==3?2.1:1.9,0,.6,-.3,hd);if(hs>=2)mk(BG,hm,1.9,hs==2?3.4:2.4,.7,0,-.5,-1.5,hd);if(hs==3){mk(BG,hm,.5,2.6,1.2,-1.8,-.4,0,hd);mk(BG,hm,.5,2.6,1.2,1.8,-.4,0,hd)}}
 if(rnd()<.25)mk(BG,hm,2.3,1,1.2,0,-1.75,.5,hd);
 const np=V(0,5.8,-1.6-(HS-1)*2.2);mk(SG,redM,.5,.5,.5,np.x,np.y,np.z,up);
 const arm=x=>{const a=new T.Group();a.position.set(x*W,5.1,0);up.add(a);mk(BG,m,1.4*W,3.4*A,1.4*W,0,-1.7*A,0,a);const e=new T.Group();e.position.y=-3.4*A;a.add(e);mk(BG,m,1.25*W,3.3*A,1.25*W,0,-1.65*A,0,e);mk(SG,m,.9,.9,.9,0,-3.4*A,0,e);mk(SG,m,1.1*W,1.1*W,1.1*W,0,0,0,a);mk(SG,m,.8*W,.8*W,.8*W,0,0,0,e);for(let i=0;i<4;i++)mk(BG,m,.3,.9,.32,(i-1.5)*.36,-3.4*A-.75,.1,e);mk(BG,m,.32,.7,.32,.6,-3.4*A-.35,.5,e);a.e=e;return a};
 const leg=(x,i)=>{const l=new T.Group();l.position.set(x*W,H0,0);g.add(l);mk(BG,lm[i],2*W,3.3*LL,2.2*W,0,-1.65*LL,0,l);const k=new T.Group();k.position.y=-3.3*LL;l.add(k);mk(BG,lm[i],1.8*W,3.2*LL,2*W,0,-1.6*LL,0,k);mk(BG,lm[i],2.1,.7,3.2,0,-3.2*LL,.7,k);mk(SG,lm[i],1.2*W,1.2*W,1.2*W,0,0,0,k);mk(SG,lm[i],1.5*W,1.5*W,1.5*W,0,0,0,l);for(let j=-1;j<=1;j++)mk(BG,lm[i],.6,.45,.8,j*.7,-3.25*LL,2.45,k);l.k=k;return l};
 const aR=arm(3.4),aL=arm(-3.4);mk(BG,m,4*W,2,2.5*W,0,H0,0,g);mk(shG,shM,5,1,5,0,.06,0,g);g.scale.setScalar(s);g.position.set(x,0,z);g.rotation.y=Math.PI*1.5;S.add(g);
 return{g,up,hd,aR,aL,eR:aR.e,eL:aL.e,lg:[leg(1.2,0),leg(-1.2,1)],lm,em,skin:m.color,cut:[0,0],blind:0,lastE:-1,lastN:-1,hp:1,lastL:[-1,-1],s,runner,np,bl,sp:(runner?7:3+rnd()*1.4)+wave*.25,st:0,at:1,tm:0,cd:1.5,ph:rnd()*6,dead:0,dt:0,aim:-1,hit:0,nw:V(),ew:V(),lw:[V(),V()]}}
const F=[{n:'格闘型',ty:2,fc:0,hs:2,s:1.15,sp:15,hp:6,col:0xe0b89a,cd:.55,atk:'punch'},{n:'超大型',ty:1,fc:3,hs:0,s:3.4,sp:8,hp:10,col:0xc2503f,cd:3,atk:'blast'},{n:'獣型',ty:1,fc:1,hs:3,s:1.5,sp:17,hp:5,col:0x6b4a30,cd:1,atk:'throw'},{n:'装甲型',ty:2,fc:0,hs:0,s:1.3,sp:12,hp:8,col:0xd2b497,cd:.7,atk:'punch',armor:1}];
let form=0;const PR=[];P.tg=100;P.tf=0;P.th=0;P.tt=0;P.ac=0;P.ap=0;
{const fs=$('fs');F.forEach((f,i)=>{const b=document.createElement('button');b.textContent=f.n;b.className='fb';b.onclick=()=>{form=i;[...fs.children].forEach((c,j)=>c.style.background=j==i?'#e8553a':'#444')};fs.appendChild(b)});fs.children[0].style.background='#e8553a'}
bindBtn($('tf'),()=>P.tf?endTransform():doTransform(),()=>{});
function wreckB(i){const b=B[i];if(b.keep)return;collapse(b,P.p.x,P.p.z);sfx(80,.5,'sine',.3);B.splice(i,1)}
function buildForm(k){const f=F[k],t=mkTitan(P.p.x,P.p.z,false,f);t.skin.setHex(f.col);t.lm.forEach(l=>l.color.setHex(f.col));t.s=f.s;t.g.scale.setScalar(f.s);t.g.rotation.y=Math.atan2(-Math.sin(yaw),-Math.cos(yaw));
 if(k==1)t.em.color.setHex(0xffffff);
 if(k==2){t.aR.scale.y=t.aL.scale.y=1.5;t.bl=.45}
 if(k==3){const ar=M(0x6f6a60);mk(BG,ar,5.2,3.4,3.2,0,3.4,.2,t.up);mk(BG,ar,2.4,1.2,2.8,3.2,5.7,0,t.up);mk(BG,ar,2.4,1.2,2.8,-3.2,5.7,0,t.up);mk(SG,ar,1.9,1.5,1.95,0,.7,-.1,t.hd);[t.eR,t.eL].forEach(e=>mk(BG,ar,1.7,2.8,1.7,0,-1.65,0,e));t.lg.forEach(l=>mk(BG,ar,2.4,2.6,2.6,0,-1.6,0,l))}
 skinize(t);t.g.traverse(o=>{if(o.isMesh&&o.material!==shM)o.castShadow=true});return t}
function doTransform(){if(!run||P.tf||P.tg<100)return;lightning(P.p.x,P.p.y,P.p.z);P.tf=1;P.tg=0;P.tt=30;P.th=F[form].hp;P.ac=0;P.ap=0;P.a=null;rope.visible=false;P.v.set(0,0,0);P.tm=buildForm(form);H.g.visible=false;puff(V(P.p.x,P.p.y+3,P.p.z),20,4);shake=1.2;flash('#fff');sfx(60,.8,'sawtooth',.4);toast('巨人化！')}
function endTransform(){S.remove(P.tm.g);P.tf=0;H.g.visible=true;puff(V(P.p.x,P.p.y+3,P.p.z),12,3);PR.forEach(q=>S.remove(q.m));PR.length=0;P.inv=1;P.p.y=gh(P.p.x,P.p.z);toast('巨人化解除')}
function nearT(){let b=null,bd=1e9;for(const t of titans)if(!t.dead){const d=Math.hypot(t.g.position.x-P.p.x,t.g.position.z-P.p.z);if(d<bd){bd=d;b=t}}return b}
function hitT(t,d){t.hp-=d;puff(t.nw,6,2,0xffffff);if(t.hp<=0){kill(t);toast('撃破！')}else{t.st=3;t.tm=1;toast('ひるんだ！')}}
function tAtk(){if(!run||!P.tf||P.ac>0)return;const f=F[form],m=P.tm,g=m.g,tg=lockT||nearT();
 if(tg)g.rotation.y=Math.atan2(tg.g.position.x-P.p.x,tg.g.position.z-P.p.z);
 P.ac=f.cd;P.ap=.35;sfx(120,.3,'sawtooth',.2);const fx=Math.sin(g.rotation.y),fz=Math.cos(g.rotation.y);
 if(f.atk=='blast'){puff(V(P.p.x,P.p.y+8*m.s,P.p.z),14,5*m.s,0xffffff);shake=1;for(let i=B.length-1;i>=0;i--)if(Math.hypot(B[i].x-P.p.x,B[i].z-P.p.z)<45)wreckB(i);titans.forEach(t=>{if(!t.dead&&Math.hypot(t.g.position.x-P.p.x,t.g.position.z-P.p.z)<60)hitT(t,2)})}
 else if(f.atk=='throw'){const b=new T.Mesh(SG,M(0x777166));b.scale.setScalar(1.3);b.position.set(P.p.x+fx*3*m.s,P.p.y+9*m.s,P.p.z+fz*3*m.s);S.add(b);PR.push({m:b,v:V(fx*45,6,fz*45),l:3})}
 else titans.forEach(t=>{if(t.dead)return;const dx=t.g.position.x-P.p.x,dz=t.g.position.z-P.p.z,L=Math.hypot(dx,dz)||1;if(L<9*m.s+4*t.s&&(dx*fx+dz*fz)/L>.2)hitT(t,f.armor?2:1)})}
function tfMove(dt){const f=F[form],p=P.p,m=P.tm,g=m.g,fx=-Math.sin(yaw),fz=-Math.cos(yaw),mx=Math.cos(yaw)*jx-fx*jy,mz=-Math.sin(yaw)*jx-fz*jy,l=Math.hypot(mx,mz),sp=f.sp*(gasHeld?1.6:1);
 if(l>.1){const k=Math.min(1,l);p.x+=mx/l*sp*k*dt;p.z+=mz/l*sp*k*dt;let da=Math.atan2(mx,mz)-g.rotation.y;da=Math.atan2(Math.sin(da),Math.cos(da));g.rotation.y+=da*Math.min(1,8*dt);m.ph+=dt*sp*.25}
 P.v.y-=28*dt;p.y+=P.v.y*dt;const gq=gh(p.x,p.z);if(p.y<=gq+.5&&P.v.y<=0){p.y=gq;P.v.y=0;P.g=true}else P.g=false;
 wallClamp(p);
 for(let i=B.length-1;i>=0;i--){const b=B[i];if(Math.abs(p.x-b.x)<b.w+2*m.s&&Math.abs(p.z-b.z)<b.d+2*m.s&&p.y<b.h){b.dc=(b.dc||0)-dt;if(b.dc<=0){b.dc=.6;if(dmgHouse(b,p.x,p.z,30*m.s*m.s))B.splice(i,1)}}}
 if(form==1&&rnd()<dt*10)puff(V(p.x+(rnd()-.5)*10,p.y+rnd()*20*m.s,p.z+(rnd()-.5)*10),1,2*m.s);
 for(let i=PR.length-1;i>=0;i--){const q=PR[i];q.v.y-=20*dt;q.m.position.addScaledVector(q.v,dt);q.l-=dt;let h=0;for(const t of titans)if(!t.dead&&t.nw.distanceTo(q.m.position)<6*t.s){hitT(t,1);h=1;break}if(h||q.l<=0||q.m.position.y<0){puff(q.m.position,5,2,0xb8aa94);S.remove(q.m);PR.splice(i,1)}}
 const sw=l>.1?Math.sin(m.ph)*.6:0;m.lg.forEach((q,i)=>{const a=sw*(i?-1:1);q.rotation.x=a;q.k.rotation.x=Math.max(0,a)*1.1});
 P.ac-=dt;P.ap=Math.max(0,P.ap-dt);const ka=P.ap>0?1-P.ap/.35:1;
 m.aR.rotation.x=P.ap>0?-2.6+ka*2.4:-sw*.8;m.eR.rotation.x=-.3;m.aL.rotation.x=sw*.8;m.eL.rotation.x=-.3;m.up.rotation.x=m.bl+(P.ap>0?.3*ka:0);m.hd.rotation.z=Math.sin(m.ph*.7)*.08;
 g.position.set(p.x,p.y,p.z);P.inv-=dt;g.visible=!(P.inv>0&&Math.floor(P.inv*10)%2);
 if(P.th<=0)endTransform()}
P.sp=0;P.spy=0;
function hitD(a,q){return P.sp>0?Math.max(0,a.distanceTo(q)-3.8):segD(a,P.sd,q)}
const skinT=cv(128,128,(x,w,h)=>{x.fillStyle='#fff';x.fillRect(0,0,w,h);for(let i=0;i<140;i++){x.strokeStyle=`rgba(150,50,40,${.04+rnd()*.07})`;x.lineWidth=1+rnd()*2;x.beginPath();x.moveTo(rnd()*w,rnd()*h);x.bezierCurveTo(rnd()*w,rnd()*h,rnd()*w,rnd()*h,rnd()*w,rnd()*h);x.stroke()}spk(x,w,h,500,.12)});
function skinize(t){const hx=t.skin.getHex(),pm=()=>new T.MeshPhongMaterial({color:hx,map:skinT,shininess:7,specular:0x2c2c2c}),b=pm(),l0=pm(),l1=pm(),ob=t.skin,o0=t.lm[0],o1=t.lm[1];
 t.g.traverse(o=>{if(!o.isMesh)return;const m=o.material;if(m.color===ob)o.material=b;else if(m===o0)o.material=l0;else if(m===o1)o.material=l1});t.skin=b.color;t.lm=[l0,l1]}
{const cm=new T.MeshBasicMaterial({color:0xffffff,transparent:true,opacity:.7,fog:false,depthWrite:false});for(let i=0;i<16;i++){const c=new T.Mesh(SG,cm),a=rnd()*6.283,r=300+rnd()*200;c.scale.set(50+rnd()*60,8+rnd()*8,30+rnd()*30);c.position.set(Math.cos(a)*r,160+rnd()*90,Math.sin(a)*r);S.add(c)}}
R.toneMapping=T.ACESFilmicToneMapping;R.toneMappingExposure=1.2;
const lineM=new T.MeshBasicMaterial({color:0x2a1008,transparent:true,opacity:.28,depthWrite:false});
{const mm=new T.MeshBasicMaterial({color:0x7f93a8,fog:false});for(let i=0;i<22;i++){const a=i/22*6.283+rnd()*.2,r=470+rnd()*50,h=100+rnd()*160,c=new T.Mesh(new T.ConeGeometry(1,1,6),mm);c.scale.set(110+rnd()*90,h,110+rnd()*90);c.position.set(Math.cos(a)*r,h/2-10,Math.sin(a)*r);S.add(c)}}
let ammo=6,rel=0,combo=0,cT=0;const BL=[];
function roofY(b,x,z){const dx=Math.abs(x-b.x),dz=Math.abs(z-b.z),w=b.w+1,d=b.d+1;if(dx>w||dz>d)return -1;if(b.rt==3)return b.h0+.7;if(b.rt==0)return b.h0+b.rh*(1-Math.max(dx/w,dz/d));return b.h0+b.rh*(1-(b.rt==1?dz/d:dx/w))}
function collide(b,p,v,prevY,o){const r=.6,ry=roofY(b,p.x,p.z);if(ry<0||p.y>=ry)return;
 if(p.y<b.h0&&!(p.x>b.x-b.w-r&&p.x<b.x+b.w+r&&p.z>b.z-b.d-r&&p.z<b.z+b.d+r))return;
 if(prevY>=ry-.5){p.y=ry;if(v.y<0)v.y=0;(o||P).g=true;return}
 const lo=p.y<b.h0,bw=(lo?b.w:b.w+1)+r,bd=(lo?b.d:b.d+1)+r,px=Math.min(p.x-(b.x-bw),b.x+bw-p.x),pz=Math.min(p.z-(b.z-bd),b.z+bd-p.z);
 if(px<pz){p.x+=p.x<b.x?-px:px;v.x=0}else{p.z+=p.z<b.z?-pz:pz;v.z=0}}
function shoot(){return;ammo--;if(ammo==0)rel=1.8;sfx(1100,.08,'square',.14);
 const c=V(P.p.x,P.p.y+1.4,P.p.z),d=new T.Vector3();C.getWorldDirection(d);let best=null,bs=.985;
 if(lockT&&!lockT.dead)best=behind(lockT,P.p)?lockT.nw:lockT.ew;
 else for(const t of titans)if(!t.dead)for(const q of[t.nw,t.ew,t.lw[0],t.lw[1]]){const s=q.clone().sub(c).normalize().dot(d);if(s>bs){bs=s;best=q}}
 if(best)d.copy(best).sub(c).normalize();
 const m=new T.Mesh(SG,new T.MeshBasicMaterial({color:0xffe08a}));m.scale.setScalar(.25);m.position.copy(c);S.add(m);BL.push({m,v:d.multiplyScalar(160),l:1.2});puff(c,2,.5,0xffddaa);shake=Math.max(shake,.12)}
function bulletStep(dt){rel=Math.max(0,rel-dt);if(ammo==0&&rel<=0)ammo=6;
 for(let i=BL.length-1;i>=0;i--){const b=BL[i],q=b.m.position;q.addScaledVector(b.v,dt);b.l-=dt;let h=0;
  for(const t of titans){if(t.dead||h)continue;const r=1.3+.6*t.s,ry=t.g.rotation.y,fb=b.v.x*Math.sin(ry)+b.v.z*Math.cos(ry)>0;
   if(t.frag&&[t.nw,t.ew,t.lw[0],t.lw[1]].some(w=>q.distanceTo(w)<r+1)){kill(t);toast('脆い！');h=1}
   else if(fb&&q.distanceTo(t.nw)<r){t.hp-=.5;puff(q,5,1,0xcc2222);if(t.hp<=0){kill(t);toast('うなじを撃ち抜いた！')}else toast('命中！');h=1}
   else if(!t.blind&&!fb&&q.distanceTo(t.ew)<r){t.blind=4;t.wasB=1;t.em.color.setHex(0x6a1010);puff(q,5,.8,0xcc2222);toast('目を撃ち抜いた！');h=1}
   else for(let k=0;k<2;k++)if(!h&&t.cut[k]<=0&&q.distanceTo(t.lw[k])<r+.4){t.cut[k]=9;t.lm[k].color.setHex(0xa03a30);puff(q,6,1,0xcc2222);toast('足を撃ち抜いた！');h=1}}
  if(h||b.l<=0||q.y<0){S.remove(b.m);BL.splice(i,1)}}}
{const tr=M(0x5a4028),fl=[M(0x3f6b34),M(0x4b7a3a),M(0x35592d)];for(let i=0;i<160;i++){const a=rnd()*6.283,r=40+rnd()*235,x=Math.cos(a)*r,z=Math.sin(a)*r,y=gh(x,z);if((y<3&&rnd()<.6)||isRoad(x,z)||B.some(b=>Math.abs(x-b.x)<b.w+4&&Math.abs(z-b.z)<b.d+4))continue;const s=.8+rnd()*.7,t=new T.Mesh(BG,tr),c=new T.Mesh(SG,fl[i%3]);t.scale.set(.6*s,4*s,.6*s);t.position.set(x,y+2*s,z);c.scale.set(2.6*s,2.4*s,2.6*s);c.position.set(x,y+5*s,z);S.add(t,c)}}
const CV=[];let ate=0,idleT=0;const cvCols=[0x8a4b3a,0x3a5a8a,0x6a7a3a,0x8a7a4a,0x7a3a6a,0x4a4a4a];
function mkCivOld(x,z,ax,st){const g=new T.Group(),sk2=M(0xf0c8a8),cl=M(cvCols[Math.floor(rnd()*6)]),pn2=M(0x3a3028);
 mk(BG,cl,.45,.65,.28,0,1.05,0,g);mk(SG,sk2,.13,.15,.13,0,1.58,0,g);mk(BG,cl,.12,.5,.12,-.3,1.1,0,g);mk(BG,cl,.12,.5,.12,.3,1.1,0,g);
 const l1=new T.Group(),l2=new T.Group();l1.position.set(-.12,.75,0);l2.position.set(.12,.75,0);g.add(l1,l2);mk(BG,pn2,.17,.75,.2,0,-.37,0,l1);mk(BG,pn2,.17,.75,.2,0,-.37,0,l2);
 g.scale.setScalar(1.35);g.position.set(x,gh(x,z),z);S.add(g);
 return{g,l1,l2,x,z,ax,st,dir:rnd()<.5?1:-1,sp:2+rnd()*1.5,ph:rnd()*6,alive:1,carried:0,cell:Math.floor(((ax?z:x)-18)/36)}}
function spawnCiv(){const ax=rnd()<.5?0:1,st=18+36*(Math.floor(rnd()*15)-7),al=(rnd()-.5)*480,x=ax?st:al,z=ax?al:st;if(Math.hypot(x,z)>262||(Math.abs(x)<54&&Math.abs(z)<54))return;CV.push(mkCiv(x,z,ax,st))}
function civStep(dt){
 for(let i=CV.length-1;i>=0;i--)if(!CV[i].alive)CV.splice(i,1);
 if(CV.length<28&&rnd()<dt*.6)spawnCiv();
 for(const c of CV){if(c.carried)continue;
  let nt=null,nd=70;for(const t of titans)if(!t.dead){const d=Math.hypot(t.g.position.x-c.x,t.g.position.z-c.z);if(d<nd){nd=d;nt=t}}
  if(nt&&nd<3.2*nt.s){c.alive=0;S.remove(c.g);scream(c.x,c.z);ate++;puff(V(c.x,gh(c.x,c.z)+1,c.z),6,1,0xaa1111);decal(c.x,c.z,3);toast('市民が踏み潰された…');continue}let sp=c.sp;if(nt){if(rnd()<dt*.12)scream(c.x,c.z,.6);sp*=1.8;c.dir=(c.ax?c.z-nt.g.position.z:c.x-nt.g.position.x)>=0?1:-1}
  const m=sp*dt*c.dir;if(c.ax)c.z+=m;else c.x+=m;
  const cc=c.ax?c.z:c.x,cell=Math.floor((cc-18)/36);
  if(cell!=c.cell){c.cell=cell;if(!nt&&rnd()<.35){const k=Math.round((cc-18)/36);if(c.ax){c.z=18+36*k;c.ax=0}else{c.x=18+36*k;c.ax=1}c.dir=rnd()<.5?1:-1;c.cell=Math.floor(((c.ax?c.z:c.x)-18)/36)}}
  {const rr=Math.hypot(c.x,c.z);if(rr>262){c.x*=262/rr;c.z*=262/rr;c.dir=-c.dir}}if(Math.abs(c.x)<54&&Math.abs(c.z)<54)c.dir=(c.ax?c.z:c.x)>=0?1:-1;
  c.ph+=dt*sp*3;const q=Math.sin(c.ph)*.7;c.l1.rotation.x=q;c.l2.rotation.x=-q;c.a1.rotation.x=nt?-2.4+Math.sin(c.ph)*.4:-q*.8;c.a2.rotation.x=nt?-2.4-Math.sin(c.ph)*.4:q*.8;
  c.g.position.set(c.x,gh(c.x,c.z),c.z);c.g.rotation.y=c.ax?(c.dir>0?0:Math.PI):(c.dir>0?Math.PI/2:-Math.PI/2)}}
function ensureAction(dt){let nd=1e9;for(const t of titans)if(!t.dead)nd=Math.min(nd,Math.hypot(t.g.position.x-P.p.x,t.g.position.z-P.p.z));
 idleT=nd>110?idleT+dt:0;if(idleT>6&&titans.length<18){idleT=0;const a=rnd()*6.283,r=70+rnd()*30;let x=P.p.x+Math.cos(a)*r,z=P.p.z+Math.sin(a)*r;const rr=Math.hypot(x,z);if(rr>540){x*=540/rr;z*=540/rr}titans.push(bigify(mkTitan(x,z,false)));toast('巨人が接近！')}}
let mapOpen=false;const mp=$('mp'),TM=[];
for(let i=0;i<14;i++){const d=document.createElement('div');d.className='tm';document.body.appendChild(d);TM.push(d)}
addEventListener('error',e=>{const d=$('tt');d.textContent='ERR: '+e.message;d.style.opacity=1});
mp.onclick=()=>{mapOpen=false;mp.style.display='none'};
bindBtn($('mb'),()=>{mapOpen=!mapOpen;mp.style.display=mapOpen?'block':'none'},()=>{});
function drawMap(){const c=mp.getContext('2d'),W=mp.width=innerWidth,Hh=mp.height=innerHeight,sc=Math.min(W,Hh)/1000,cx=W/2,cy=Hh/2;
 c.fillStyle='#3a5a38';c.fillRect(0,0,W,Hh);
 for(let x=-300;x<300;x+=15)for(let z=-300;z<300;z+=15){if(Math.hypot(x,z)>302)continue;const g=Math.max(0,Math.min(1,(gh(x,z)+10)/30));c.fillStyle='rgb('+(60+g*80|0)+','+(70+g*90|0)+','+(55+g*50|0)+')';c.fillRect(cx+x*sc,cy+z*sc,15*sc+1,15*sc+1)}
 c.strokeStyle='#cfcfcf';c.lineWidth=6*sc;c.beginPath();c.arc(cx,cy,300*sc,0,6.3);c.stroke();c.fillStyle='#111';c.fillRect(cx+296*sc,cy-19*sc,9*sc,38*sc);
 for(const b of ALL){c.fillStyle=b.rub&&b.rub.visible?'#555':'#c9a27c';c.fillRect(cx+(b.x-b.w)*sc,cy+(b.z-b.d)*sc,b.w*2*sc,b.d*2*sc)}
 c.fillStyle='#6af';for(const v of CV)if(v.alive)c.fillRect(cx+v.x*sc-1,cy+v.z*sc-1,3,3);c.fillStyle='#6f6';for(const q of SOL)if(q.alive)c.fillRect(cx+q.p.x*sc-2,cy+q.p.z*sc-2,4,4);
 for(const t of titans){if(t.dead)continue;c.fillStyle=t.frag?'#6cf':t.hp>1?'#f90':'#f33';c.beginPath();c.arc(cx+t.g.position.x*sc,cy+t.g.position.z*sc,Math.max(3,t.s*3.5),0,6.3);c.fill()}
 const px=cx+P.p.x*sc,py=cy+P.p.z*sc,a=Math.atan2(-Math.cos(yaw),-Math.sin(yaw));c.fillStyle='#ff0';c.beginPath();c.moveTo(px+Math.cos(a)*13,py+Math.sin(a)*13);c.lineTo(px+Math.cos(a+2.5)*9,py+Math.sin(a+2.5)*9);c.lineTo(px+Math.cos(a-2.5)*9,py+Math.sin(a-2.5)*9);c.fill();
 c.fillStyle='#fff';c.font='14px sans-serif';c.fillText('マップ（タップで閉じる）黄：自分　赤：巨人　青：市民　黒い門：城門',12,24)}
function wallClamp(p){const r=Math.hypot(p.x,p.z),gt=p.x>0&&Math.abs(p.z)<19;if(r>292&&r<308&&!gt&&p.y<75){const n=r<300?292:308;p.x*=n/r;p.z*=n/r}if(r>540){p.x*=540/r;p.z*=540/r}}
const DB=[],CO=[],dm=[0xd8c9a8,0xcdbb97,0xc9b8a2,0x6f665a,0x8a7a68].map(M),dRoof=M(0x9a4632),dWood=M(0x5a4028);
function collapseOld(b,fx,fz){const G=b.rub||new T.Group();if(!b.rub)S.add(G);b.rub=G;const gy=b.gy,hg=b.h0-gy;
 b.m.forEach((o,i)=>{if(i<b.m.length-1){o.userData.y0=o.position.y;o.userData.s0=o.scale.y}});(b.dm||[]).forEach(o=>o.visible=false);CO.push({b,t:0});
 for(let i=0;i<4;i++){const h=.8+rnd()*Math.max(1,hg*.3),m=new T.Mesh(BG,dm[i%5]);m.scale.set(1+rnd()*3,h,.6+rnd()*1.2);m.position.set(b.x+(rnd()*2-1)*b.w,gy+h/2-.3,b.z+(rnd()*2-1)*b.d);m.rotation.y=rnd()*3;G.add(m)}
 for(let i=0;i<8;i++){const s=.4+rnd()*1.1,m=new T.Mesh(BG,dm[Math.floor(rnd()*5)]);m.scale.set(s*2,s,s*1.6);m.position.set(b.x+(rnd()*2-1)*b.w*.9,gy+s*.4+rnd()*.8,b.z+(rnd()*2-1)*b.d*.9);m.rotation.set(rnd()*.6,rnd()*3,rnd()*.6);G.add(m)}
 const dx=b.x-fx,dz=b.z-fz,l=Math.hypot(dx,dz)||1;
 for(let i=0;i<12;i++){const k=i<5?0:i<10?1:2,s=.7+rnd()*1.4,m=new T.Mesh(BG,k==0?dRoof:k==1?dm[i%3]:dWood);m.scale.set(k==0?s*2.2:k==1?s:.3,k==0?.3:k==1?s*.7:s*3,k==0?s*1.4:k==1?s:.3);
  m.position.set(b.x+(rnd()*2-1)*b.w,gy+rnd()*hg*.6+(k==0?hg*.7:0),b.z+(rnd()*2-1)*b.d);m.rotation.set(rnd()*3,rnd()*3,rnd()*3);G.add(m);
  DB.push({m,v:V(dx/l*(2+rnd()*5)+(rnd()-.5)*4,2+rnd()*5,dz/l*(2+rnd()*5)+(rnd()-.5)*4),w:V(rnd()*4-2,rnd()*4-2,rnd()*4-2)})}
 puff(V(b.x,gy+hg*.5,b.z),14,Math.max(b.w,b.d)*.5,0xb8aa94);puff(V(b.x,gy+hg,b.z),8,3,0x9a8f80);if(rnd()<.6)SM.push({x:b.x,y:gy,z:b.z,t:10+rnd()*8})}
function debrisStep(dt){ambStep(dt);for(const s of SM){s.t-=dt;if(s.t>0&&rnd()<dt*3)puff(V(s.x+(rnd()-.5)*4,s.y+1,s.z+(rnd()-.5)*4),1,1.8,0x555555)}for(let i=SM.length-1;i>=0;i--)if(SM[i].t<=0)SM.splice(i,1);for(let i=LT.length-1;i>=0;i--){const l=LT[i];l.t+=dt;const o=Math.max(0,1-l.t/.45);l.ms.forEach(m=>{m.material.opacity=o*(m.userData.k||1)});if(l.t>.45){l.ms.forEach(m=>S.remove(m));LT.splice(i,1)}}
 for(let i=DB.length-1;i>=0;i--){const d=DB[i],m=d.m;d.v.y-=22*dt;m.position.addScaledVector(d.v,dt);m.rotation.x+=d.w.x*dt;m.rotation.y+=d.w.y*dt;m.rotation.z+=d.w.z*dt;const g0=gh(m.position.x,m.position.z)+.3;if(m.position.y<g0){m.position.y=g0;if(d.v.y<-3){d.v.y*=-.25;d.v.x*=.6;d.v.z*=.6;d.w.multiplyScalar(.5)}else DB.splice(i,1)}}
 for(let i=CO.length-1;i>=0;i--){const c=CO[i],b=c.b;c.t+=dt;const u=Math.min(1,c.t/.35);b.m.forEach((o,j)=>{if(j<b.m.length-1)o.rotation.z=Math.sin(c.t*55)*.035*(1-u*.3)});if(u>=1){b.m.forEach((o,j)=>{if(j<b.m.length-1)o.visible=false});burst(b,c.fx,c.fz);CO.splice(i,1)}}}
for(let i=-3;i<=3;i++){const q=new T.Mesh(BG,M(0x2a2a2e));q.scale.set(.5,12,.5);q.position.set(299,32,i*5.5);S.add(q)}
{const q=new T.Mesh(BG,M(0x2a2a2e));q.scale.set(.5,.8,38);q.position.set(299,28,0);S.add(q);const rd=new T.Mesh(new T.PlaneGeometry(250,30),M(0x5a4a38));rd.rotation.x=-Math.PI/2;rd.position.set(425,.06,0);S.add(rd)}
{const tr=M(0x5a4028),fl=[M(0x3f6b34),M(0x4b7a3a),M(0x35592d)],rk=M(0x7a766e);for(let i=0;i<90;i++){const a=rnd()*6.283,r=320+rnd()*200,x=Math.cos(a)*r,z=Math.sin(a)*r;if(Math.abs(z)<25&&x>0)continue;const s=.8+rnd()*.7;if(i%3){const t=new T.Mesh(BG,tr),c=new T.Mesh(SG,fl[i%3]);t.scale.set(.6*s,4*s,.6*s);t.position.set(x,2*s,z);c.scale.set(2.6*s,2.4*s,2.6*s);c.position.set(x,5*s,z);S.add(t,c)}else{const c=new T.Mesh(SG,rk);c.scale.set(2*s,1.3*s,1.7*s);c.position.set(x,.5*s,z);S.add(c)}}}
const LT=[];let spT=3;
function lightning(x,y,z){const pts=[];let cx=x,cz=z;for(let i=0;i<=14;i++){pts.push(V(cx,y+210*(1-i/14),cz));cx+=(rnd()-.5)*16;cz+=(rnd()-.5)*16}pts[14].set(x,y,z);const ms=[];
 for(let k=0;k<3;k++){const l=new T.Line(new T.BufferGeometry().setFromPoints(pts.map(q=>V(q.x+(rnd()-.5)*k*3,q.y,q.z+(rnd()-.5)*k*3))),new T.LineBasicMaterial({color:k?0x9fd0ff:0xffffff,transparent:true}));l.frustumCulled=false;S.add(l);ms.push(l)}
 const c=new T.Mesh(new T.CylinderGeometry(1.3,1.3,210,8),new T.MeshBasicMaterial({color:0xaad4ff,transparent:true,opacity:.7,depthWrite:false}));c.userData.k=.7;c.position.set(x,y+105,z);S.add(c);ms.push(c);LT.push({ms,t:0});
 flash('#fff');setTimeout(()=>flash('#bcd'),120);shake=1.6;sfx(45,.9,'sawtooth',.5);sfx(2000,.12,'square',.25);puff(V(x,y+1,z),16,3,0xcfe8ff)}
function armorize(t){t.arm=1;t.hp=3;t.sp=2.6+rnd()*.6;t.s=1.15+rnd()*.3;t.g.scale.setScalar(t.s);const ar=M(0x6f6a60);mk(BG,ar,5.2,3.4,3.2,0,3.4,.2,t.up);mk(BG,ar,2.4,1.2,2.8,3.2,5.7,0,t.up);mk(BG,ar,2.4,1.2,2.8,-3.2,5.7,0,t.up);mk(SG,ar,1.8,1.3,1.7,0,.9,.3,t.hd);[t.eR,t.eL].forEach(e=>mk(BG,ar,1.7,2.8,1.7,0,-1.65,0,e));t.lg.forEach(l=>mk(BG,ar,2.4,2.6,2.6,0,-1.6,0,l));toast('装甲巨人が出現！')}
function colossalize(t){t.col=1;t.s=2.9+rnd()*.5;t.g.scale.setScalar(t.s);t.hp=4;t.sp=2.2;t.runner=false;t.skin.setHex(0xc2503f);t.lm.forEach(l=>l.color.setHex(0xc2503f));toast('超大型が出現！')}
function infSpawn(dt){spT-=dt;wave=1+Math.floor(score/6);const al=titans.filter(t=>!t.dead).length,tg=Math.min(9,4+Math.floor(score/8));if(al<1&&spT>1)spT=1;
 if(spT<=0&&al<tg){spT=al<3?1.5:4.5+rnd()*3;let x,z;if(rnd()<.55){x=330+rnd()*14;z=(rnd()-.5)*60}else{const a=rnd()*6.283,r=90+rnd()*120;x=P.p.x+Math.cos(a)*r;z=P.p.z+Math.sin(a)*r;const rr=Math.hypot(x,z);if(rr>285&&rr<312){x*=262/rr;z*=262/rr}}
  titans.push(bigify(mkTitan(x,z,rnd()<.12),wave))}}
const CG=new T.CylinderGeometry(.85,.62,1,10),CG2=new T.CylinderGeometry(.66,.46,1,10);
function mkTitan(x,z,runner,fo){const g=new T.Group(),ty=fo?fo.ty:Math.floor(rnd()*5),fc=fo?fo.fc:(rnd()<.65?[0,2][Math.floor(rnd()*2)]:Math.floor(rnd()*4)),hs=fo?fo.hs:Math.floor(rnd()*4),s=(runner?.62:.72)+rnd()*.5,
 m=M([0xe8c9ae,0xdcb496,0xcfa58a,0xe3bf9f,0xf0d6c0,0xb88f78,0xd9b0a0][Math.floor(rnd()*7)]),lm=[m.clone(),m.clone()],em=wht.clone(),hm=M([0x2e2218,0x5a4630,0x1a1410,0xb8a070,0x8a8a88,0x6a3a22][Math.floor(rnd()*6)]),
 W=[1,.78,1.3,1.25,1][ty],A=[1,1.2,1.15,.95,1][ty],LL=[1,1.12,.95,.85,1][ty],HS=[1,.9,1,1,1.3][ty],bl=.08+rnd()*.3,H0=6.5*LL,ew=.32+rnd()*.2;
 const up=new T.Group();up.position.y=H0;up.rotation.x=bl;g.add(up);
 mk(SG,m,2.5*W,2.3,1.65*W,0,3.9,.05,up);mk(SG,m,2.2*W*(ty==3?1.3:1),2.1,1.55*W*(ty==3?1.35:1),0,1.9,.2,up);mk(SG,m,2.1*W,1.5,1.5*W,0,.3,0,up);mk(SG,m,3.3*W,1.2,1.5*W,0,5.2,0,up);mk(CG,m,.95,1.4,.95,0,6,.1,up);
 if(ty==2){mk(SG,m,1.3,1.1,.8,-1.3,4.2,1.2,up);mk(SG,m,1.3,1.1,.8,1.3,4.2,1.2,up);for(let i=0;i<3;i++){mk(SG,m,.8,.5,.5,-.6,1.2+i*.8,1.55,up);mk(SG,m,.8,.5,.5,.6,1.2+i*.8,1.55,up)}}else{mk(SG,m,1,.8,.6,-1.2,4,1.3,up);mk(SG,m,1,.8,.6,1.2,4,1.3,up)}
 for(let i=0;i<6;i++)mk(SG,m,.4,.35,.35,0,.8+i*.8,-1.4*W,up);
 const hd=new T.Group();hd.position.set(0,6.8,.6);hd.scale.setScalar(HS);up.add(hd);
 mk(SG,m,1.7,1.9,1.8,0,0,0,hd);mk(SG,m,1.4,.85,1.35,0,-1.45,.5,hd);mk(SG,m,.3,.55,.28,-1.7,0,0,hd);mk(SG,m,.3,.55,.28,1.7,0,0,hd);
 const mw=[1,.8,1.25,.6][fc],mh=[.5,1.2,.7,.3][fc],nt=[5,3,7,0][fc],my=-1.25-mh*.2;mk(SG,blk,mw,mh*.55,.3,0,my,1.68,hd);
 for(let r=0;r<(fc==1?2:1);r++)for(let i=0;i<nt;i++){const sp=2*mw/(nt+1);mk(BG,wht,sp*.8,.36,.2,(i-(nt-1)/2)*sp,my+(r?-1:1)*mh*.3,1.82,hd)}
 for(const e of[-.75,.75]){mk(SG,em,ew,ew*1.1,.3,e,.35,1.45,hd);mk(SG,blk,ew*.45,ew*.45,.12,e,.35,1.72,hd);mk(SG,m,ew*1.1,ew*.5,.35,e,.35+ew*.9,1.62,hd);mk(SG,m,.55,.2,.5,e,.9,1.5,hd)}
 mk(SG,m,.35+rnd()*.15,.45+rnd()*.15,.45,0,-.3,1.75,hd);mk(SG,m,.6,.5,.5,-1.1,-.35,1.15,hd);mk(SG,m,.6,.5,.5,1.1,-.35,1.15,hd);
 if(hs>0){mk(SG,hm,hs==3?2:1.8,hs==3?1.7:1.5,hs==3?2.1:1.9,0,.6,-.3,hd);if(hs>=2)mk(BG,hm,1.9,hs==2?3.4:2.4,.7,0,-.5,-1.5,hd);if(hs==3){mk(BG,hm,.5,2.6,1.2,-1.8,-.4,0,hd);mk(BG,hm,.5,2.6,1.2,1.8,-.4,0,hd)}}
 if(rnd()<.25)mk(SG,hm,1.3,.5,.7,0,-1.75,1,hd);
 const np=V(0,5.8,-1.6-(HS-1)*2.2);mk(SG,redM,.5,.5,.5,np.x,np.y,np.z,up);
 const arm=x=>{const a=new T.Group();a.position.set(x*W,5.1,0);up.add(a);mk(SG,m,1.05*W,1.05*W,1.05*W,0,0,0,a);mk(CG,m,1*W,3.4*A,1*W,0,-1.7*A,0,a);const e=new T.Group();e.position.y=-3.4*A;a.add(e);mk(SG,m,.72*W,.72*W,.72*W,0,0,0,e);mk(CG2,m,1*W,3.3*A,1*W,0,-1.65*A,0,e);mk(SG,m,.75,.85,.45,0,-3.45*A,0,e);
  for(let i=0;i<4;i++)mk(CG2,m,.32,.9,.32,(i-1.5)*.3,-3.4*A-.95,.1,e);mk(CG2,m,.35,.7,.35,.6,-3.4*A-.5,.45,e);a.e=e;return a};
 const leg=(x,i)=>{const l=new T.Group();l.position.set(x*W,H0,0);g.add(l);mk(SG,lm[i],1.45*W,1.45*W,1.45*W,0,0,0,l);mk(CG,lm[i],1.3*W,3.3*LL,1.4*W,0,-1.65*LL,0,l);const k=new T.Group();k.position.y=-3.3*LL;l.add(k);mk(SG,lm[i],1.05*W,1.05*W,1.05*W,0,0,0,k);mk(CG2,lm[i],1.2*W,3.2*LL,1.3*W,0,-1.6*LL,0,k);mk(SG,lm[i],1,.55,1.9,0,-3.15*LL,.9,k);for(let j=-1;j<=1;j++)mk(SG,lm[i],.4,.35,.55,j*.65,-3.2*LL,2.5,k);l.k=k;return l};
 const aR=arm(3.4),aL=arm(-3.4);mk(SG,m,2.1*W,1.3,1.5*W,0,H0,0,g);mk(shG,shM,5,1,5,0,.06,0,g);g.scale.setScalar(s);g.position.set(x,0,z);g.rotation.y=Math.PI*1.5;S.add(g);
 return{g,up,hd,aR,aL,eR:aR.e,eL:aL.e,lg:[leg(1.2,0),leg(-1.2,1)],lm,em,skin:m.color,cut:[0,0],blind:0,lastE:-1,lastN:-1,hp:1,lastL:[-1,-1],s,runner,np,bl,sp:(runner?7:3+rnd()*1.4)+wave*.25,st:0,at:1,tm:0,cd:1.5,ph:rnd()*6,dead:0,dt:0,aim:-1,hit:0,nw:V(),ew:V(),lw:[V(),V()]}}
const SOL=[];
function mkSol(){const h=mkHuman();h.g.visible=false;const rp=new T.Line(new T.BufferGeometry().setFromPoints([V(),V()]),new T.LineBasicMaterial({color:0x222222}));rp.frustumCulled=false;rp.visible=false;S.add(rp);return{h,rp,gas:100,rtmr:rnd()*5,off:V(),pw:.8+rnd()*.5,p:V(),v:V(),alive:0,rt:0,inv:0,tg:null,a:null,cd:0,sl:0,g:true,g0:false,ph:rnd()*6}}
for(let i=0;i<5;i++)SOL.push(mkSol());
function respawnSol(q){q.alive=1;q.p.set(18+(rnd()-.5)*5,gh(18,52)+.5,50+rnd()*4);q.v.set(0,0,0);q.tg=null;q.a=null;q.inv=2;q.cd=1;q.ct=0;q.h.g.rotation.x=0;q.h.g.visible=true}
function killSol(q,fx=0,fz=0){if(!q.alive)return;q.alive=0;q.rt=9;q.ct=5;q.rp.visible=false;q.a=null;q.v.set(fx*10,7,fz*10);scream(q.p.x,q.p.z);puff(V(q.p.x,q.p.y+1,q.p.z),6,1,0xaa1111);decal(q.p.x,q.p.z,3);toast('仲間が倒された…');sfx(100,.3,'sine',.2)}
function solStep(dt){for(const q of SOL){if(!q.alive){q.rt-=dt;if(q.ct>0){q.ct-=dt;const p=q.p,v=q.v,gy=gh(p.x,p.z);v.y-=28*dt;p.addScaledVector(v,dt);if(p.y<=gy){p.y=gy;v.x*=.8;v.z*=.8;v.y=0}q.h.g.position.copy(p);q.h.g.rotation.x+=(1.45-q.h.g.rotation.x)*Math.min(1,6*dt);if(q.ct<=0)q.h.g.visible=false}if(q.rt<=0)respawnSol(q);continue}
 q.inv-=dt;q.cd-=dt;q.sl=Math.max(0,q.sl-dt);q.rtmr-=dt;if(q.rtmr<=0){q.rtmr=5+rnd()*6;q.off.set((rnd()-.5)*10,(rnd()-.5)*4,(rnd()-.5)*10);if(rnd()<.35)q.tg=null}const p=q.p,v=q.v,prevY=p.y;
 if(!q.tg||q.tg.dead){q.tg=null;let bd=1e9;for(const t of titans)if(!t.dead&&Math.hypot(t.g.position.x,t.g.position.z)<292){const d=Math.hypot(t.g.position.x-p.x,t.g.position.z-p.z)+SOL.filter(o=>o.alive&&o!==q&&o.tg===t).length*50;if(d<bd){bd=d;q.tg=t}}}
 const t=q.tg;q.a=null;
 if(t){const L=t.nw.distanceTo(p),dir=(L>14?t.nw.clone().add(q.off):t.nw.clone()).sub(p);
  if(L<110&&q.gas>0){q.gas-=14*dt;q.a=L>14?t.nw.clone().add(q.off):t.nw;dir.normalize();v.addScaledVector(dir,44*q.pw*dt);v.y+=(L>20?34:0)*dt;
   if(L<5.5&&q.cd<=0){q.sl=.3;q.cd=3.2;sfx(800,.1,'sawtooth',.05);if(behind(t,p)&&rnd()<.4){puff(t.nw,5,1,0xcc2222);t.hp-=1;if(t.frag||t.hp<=0){t.dead=1;score++;puff(t.nw,10,1.4);sfx(500,.25,'triangle',.12)}}}}
  else{const dx=t.g.position.x-p.x,dz=t.g.position.z-p.z,l=Math.hypot(dx,dz)||1,k=Math.min(1,4*dt);v.x+=(dx/l*12-v.x)*k;v.z+=(dz/l*12-v.z)*k}}
 for(const o of SOL)if(o!==q&&o.alive){const dx=p.x-o.p.x,dy=p.y-o.p.y,dz=p.z-o.p.z,dd=Math.hypot(dx,dy,dz)||1;if(dd<8)v.addScaledVector(V(dx/dd,dy/dd,dz/dd),36*(1-dd/8)*dt)}
 v.y-=28*dt;const sp=v.length();if(sp>30)v.multiplyScalar(30/sp);p.addScaledVector(v,dt);q.g=false;
 for(const b of B)collide(b,p,v,prevY,q);
 const gy=gh(p.x,p.z);if(p.y<=gy+(q.g0&&v.y<=0&&!q.a?.7:0)){p.y=gy;if(v.y<0)v.y=0;q.g=true}q.g0=q.g;if(q.g)q.gas=Math.min(100,q.gas+25*dt);
 const rr=Math.hypot(p.x,p.z);if(rr>285){p.x*=285/rr;p.z*=285/rr}
 const g=q.h.g,hs=Math.hypot(v.x,v.z),H2=q.h;g.position.copy(p);if(hs>1)g.rotation.y=Math.atan2(v.x,v.z);
 q.ph+=dt*hs*1.1;const s1=q.g?Math.sin(q.ph)*.9*Math.min(1,hs/9):0;
 if(q.g){H2.lR.rotation.x=s1;H2.lL.rotation.x=-s1;H2.kR.rotation.x=Math.max(0,s1)*1.3;H2.kL.rotation.x=Math.max(0,-s1)*1.3;H2.aR.rotation.x=-s1*.8;H2.aL.rotation.x=s1*.8;H2.eR.rotation.x=H2.eL.rotation.x=-1;g.rotation.x=.1}
 else{H2.lR.rotation.x=-.5;H2.kR.rotation.x=1.1;H2.lL.rotation.x=.25;H2.kL.rotation.x=.5;H2.aR.rotation.x=q.a?-2.7:.5;H2.aL.rotation.x=q.a?-2.7:-.5;H2.eR.rotation.x=H2.eL.rotation.x=-.3;g.rotation.x=Math.min(.8,hs/35)}
 if(q.sl>0){H2.ub.rotation.y=-1.1+2.2*(1-q.sl/.3);H2.aR.rotation.x=-1.5}else H2.ub.rotation.y*=.85;
 H2.cape.rotation.x=.2+Math.min(1,v.length()/28)*1.1;
 q.rp.visible=!!q.a;if(q.a){const a=q.rp.geometry.attributes.position;a.setXYZ(0,p.x,p.y+1.4,p.z);a.setXYZ(1,q.a.x,q.a.y,q.a.z);a.needsUpdate=true}}}
const DC=[];
function decal(x,z,r){let m=DC.length<40?null:DC.shift();if(!m){m=new T.Mesh(new T.CircleGeometry(1,10),new T.MeshBasicMaterial({color:0x5a1010,transparent:true,opacity:.65,depthWrite:false}));m.rotation.x=-Math.PI/2;S.add(m)}m.position.set(x,gh(x,z)+.08,z);m.scale.setScalar(r*(.8+rnd()*.6));DC.push(m)}
P.held=null;P.mash=0;const SM=[];
function isRoad(x,z){const m=((x-18)%36+36)%36,n=((z-18)%36+36)%36;return Math.min(m,36-m)<6||Math.min(n,36-n)<6}
const sunDir=V(-80,120,60).normalize(),sunD=new T.Mesh(SG,new T.MeshBasicMaterial({color:0xfff3c0,fog:false}));sunD.scale.setScalar(26);S.add(sunD);
{const lp=M(0x2a2a2a),gl=M(0xffe9a0);for(let i=-7;i<=7;i++)for(let j=-7;j<=7;j++){if((i+j)&1)continue;const x=18+36*i+6.5,z=18+36*j+6.5;if(Math.hypot(x,z)>270||(Math.abs(x)<56&&Math.abs(z)<56)||B.some(b=>Math.abs(x-b.x)<b.w+2&&Math.abs(z-b.z)<b.d+2))continue;const y=gh(x,z),a=new T.Mesh(BG,lp),b=new T.Mesh(BG,gl);a.scale.set(.25,5,.25);a.position.set(x,y+2.5,z);b.scale.set(.7,.7,.7);b.position.set(x,y+5.3,z);S.add(a,b)}}
{const cols=[0xb03a2e,0x2e5a9a,0xe8e0c8,0x3a8a4a],tb=M(0x6a4a2a);for(let n=0;n<40;n++){const i=Math.floor(rnd()*13)-6,j=Math.floor(rnd()*13)-6,x=18+36*i+(rnd()<.5?7.5:-7.5),z=18+36*j+(rnd()-.5)*18;if(Math.hypot(x,z)>250||(Math.abs(x)<60&&Math.abs(z)<60)||B.some(b=>Math.abs(x-b.x)<b.w+3&&Math.abs(z-b.z)<b.d+3))continue;const y=gh(x,z),t=new T.Mesh(BG,tb),c=new T.Mesh(BG,M(cols[n%4])),p1=new T.Mesh(BG,tb),p2=new T.Mesh(BG,tb);t.scale.set(1.6,1,3);t.position.set(x,y+.5,z);c.scale.set(2.2,.15,3.6);c.position.set(x,y+2.6,z);p1.scale.set(.12,2.6,.12);p2.scale.set(.12,2.6,.12);p1.position.set(x-.9,y+1.3,z-1.7);p2.position.set(x+.9,y+1.3,z+1.7);S.add(t,c,p1,p2)}}
let lite=false;$('lq').onclick=()=>{lite=!lite;$('lq').textContent=lite?'画質：軽量（低スペック向け）':'画質：標準'};
function scream(x,z,k=1){const d=Math.hypot(x-P.p.x,z-P.p.z);if(d>260)return;const vol=.2*k*Math.min(1,80/Math.max(20,d));
 try{AC=AC||new(window.AudioContext||window.webkitAudioContext)();const n=AC.currentTime,o=AC.createOscillator(),l=AC.createOscillator(),lg=AC.createGain(),g=AC.createGain(),f=AC.createBiquadFilter();
  o.type='sawtooth';o.frequency.setValueAtTime(650+rnd()*300,n);o.frequency.linearRampToValueAtTime(1400+rnd()*400,n+.35);o.frequency.linearRampToValueAtTime(850,n+.95);
  l.frequency.value=9;lg.gain.value=60;l.connect(lg);lg.connect(o.frequency);f.type='bandpass';f.frequency.value=1500;f.Q.value=2;
  g.gain.setValueAtTime(.001,n);g.gain.linearRampToValueAtTime(vol,n+.08);g.gain.exponentialRampToValueAtTime(.001,n+1);
  o.connect(f);f.connect(g);g.connect(AC.destination);o.start(n);l.start(n);o.stop(n+1);l.stop(n+1)}catch(e){}}
let started=false;bindBtn($('stb'),()=>{run=false;$('ov').style.display='flex';$('go').textContent='続ける'},()=>{});
addEventListener('pointerdown',()=>{if(AC&&AC.state==='suspended')AC.resume()});
function mkCiv(x,z,ax,st){const g=new T.Group(),sk2=M([0xf0c8a8,0xe3b894,0xd2a07c,0x8d5a3c][Math.floor(rnd()*4)]),cl=M(cvCols[Math.floor(rnd()*6)]),pn2=M([0x3a3028,0x4a4a58,0x5a4630][Math.floor(rnd()*3)]),hr=M([0x2a1c12,0x6a4a2a,0xb09a60,0x1a1a1a,0x8a3a1a][Math.floor(rnd()*5)]),dress=rnd()<.4;
 mk(BG,cl,.42,.55,.26,0,1.2,0,g);mk(SG,sk2,.13,.15,.13,0,1.62,0,g);mk(SG,hr,.14,.1,.145,0,1.7,-.01,g);if(rnd()<.35)mk(BG,hr,.16,.3,.1,0,1.5,-.12,g);if(rnd()<.2)mk(BG,hr,.22,.05,.22,0,1.78,0,g);if(dress)mk(BG,cl,.5,.55,.34,0,.78,0,g);
 const leg=sx=>{const l=new T.Group();l.position.set(sx,.78,0);g.add(l);mk(BG,dress?sk2:pn2,.15,.75,.18,0,-.37,0,l);mk(BG,M(0x2a2018),.17,.12,.26,0,-.76,.04,l);return l};
 const arm=sx=>{const a=new T.Group();a.position.set(sx,1.42,0);g.add(a);mk(BG,cl,.11,.5,.11,0,-.25,0,a);mk(SG,sk2,.05,.05,.05,0,-.52,0,a);return a};
 const l1=leg(-.12),l2=leg(.12),a1=arm(-.28),a2=arm(.28);g.scale.setScalar(1.35);g.position.set(x,gh(x,z),z);S.add(g);
 return{g,l1,l2,a1,a2,x,z,ax,st,dir:rnd()<.5?1:-1,sp:2+rnd()*1.5,ph:rnd()*6,alive:1,carried:0,cell:Math.floor(((ax?z:x)-18)/36)}}
{const bm=M(0x9a968c);for(let i=0;i<60;i++){const a=i/60*6.283;if(a<.1||a>6.18)continue;const q=new T.Mesh(BG,bm);q.scale.set(9,76,6);q.position.set(Math.cos(a)*304,38,Math.sin(a)*304);q.rotation.y=Math.PI/2-a;S.add(q)}}
{const fc=[0x6f8f3f,0x8a9a45,0xb0a050,0x5f7f38,0x7a9a4a];for(let i=0;i<34;i++){const a=rnd()*6.283,r=340+rnd()*180,f=new T.Mesh(new T.PlaneGeometry(30+rnd()*40,40+rnd()*50),M(fc[i%5]));f.rotation.x=-Math.PI/2;f.rotation.z=rnd()*3;f.position.set(Math.cos(a)*r,.12,Math.sin(a)*r);S.add(f)}
 const tr=M(0x5a4028),fl=[M(0x3f6b34),M(0x4b7a3a),M(0x35592d)];for(let k=0;k<8;k++){const a=rnd()*6.283,r=360+rnd()*150,cx=Math.cos(a)*r,cz=Math.sin(a)*r;for(let i=0;i<16;i++){const x=cx+(rnd()-.5)*50,z=cz+(rnd()-.5)*50,s=.9+rnd()*.8;if(Math.abs(z)<25&&x>0)continue;const t=new T.Mesh(BG,tr),c=new T.Mesh(SG,fl[i%3]);t.scale.set(.6*s,4*s,.6*s);t.position.set(x,2*s,z);c.scale.set(2.6*s,2.6*s,2.6*s);c.position.set(x,5*s,z);S.add(t,c)}}}
const BR=[],FL=[];let amT=0;
for(let i=0;i<14;i++){const g=new T.Group(),w1=new T.Mesh(BG,M(0x222222)),w2=new T.Mesh(BG,M(0x222222));w1.scale.set(1.2,.08,.35);w1.position.x=-.6;w2.scale.set(1.2,.08,.35);w2.position.x=.6;g.add(w1,w2);S.add(g);BR.push({g,w1,w2,a:rnd()*6.28,r:70+rnd()*80,h:90+rnd()*50,sp:.15+rnd()*.15,ph:rnd()*6})}
{const fm=[0x7a1f1f,0x1f3a6a];[[-14,-14],[14,-14],[-14,14],[14,14]].forEach(([a,b],i)=>{const f=new T.Mesh(BG,M(fm[i%2]));f.scale.set(.2,2.6,5);f.position.set(a,gh(a,b)+50,b);S.add(f);FL.push({m:f,ph:i})})}
function ambStep(dt){amT+=dt;for(const b of BR){b.a+=b.sp*dt;b.g.position.set(Math.cos(b.a)*b.r,b.h+Math.sin(amT*.7+b.ph)*4,Math.sin(b.a)*b.r);b.g.rotation.y=-b.a;b.w1.rotation.z=Math.sin(amT*9+b.ph)*.6;b.w2.rotation.z=-Math.sin(amT*9+b.ph)*.6}
 for(const f of FL){f.m.rotation.y=Math.sin(amT*2+f.ph)*.25;f.m.scale.z=5+Math.sin(amT*3+f.ph)*.4}
 if(rnd()<dt*3&&B.length){const b=B[Math.floor(rnd()*B.length)];if(b.chimY&&Math.hypot(b.x-P.p.x,b.z-P.p.z)<140)puff(V(b.x+b.cx,b.chimY,b.z),1,1.1,0xdddddd)}}
function roar(t){const d=Math.hypot(t.g.position.x-P.p.x,t.g.position.z-P.p.z);if(d>180)return;const k=Math.min(1,70/Math.max(25,d));sfx(55+rnd()*35,.7,'sawtooth',.28*k);sfx(130+rnd()*60,.4,'square',.1*k)}
const holeM=M(0x1a1410);
function dmgHouse(b,fx,fz,amt){if(b.keep)return false;b.hp=(b.hp==null?b.mhp:b.hp)-amt;
 if(b.hp<=0){collapse(b,fx,fz);shake=Math.max(shake,.4);sfx(80,.5,'sine',.3);return true}
 const f=1-b.hp/b.mhp,dx=fx-b.x,dz=fz-b.z,xf=Math.abs(dx)/b.w>Math.abs(dz)/b.d,sg=xf?Math.sign(dx||1):Math.sign(dz||1),
  px=xf?b.x+sg*b.w:b.x+(rnd()-.5)*b.w,pz=xf?b.z+(rnd()-.5)*b.d:b.z+sg*b.d,py=b.gy+1+rnd()*Math.max(1,b.h0-b.gy-3);
 if(!b.rub){b.rub=new T.Group();S.add(b.rub)}
 for(let i=0;i<4;i++){const roof=rnd()<.4,s=.5+rnd()*.9,m=new T.Mesh(BG,roof?dRoof:dm[Math.floor(rnd()*5)]);m.scale.set(s*(roof?2:1),roof?.25:s*.7,s);m.position.set(px,py,pz);m.rotation.set(rnd()*3,rnd()*3,rnd()*3);b.rub.add(m);DB.push({m,v:V((xf?sg:0)*(2+rnd()*4)+(rnd()-.5)*3,1+rnd()*4,(xf?0:sg)*(2+rnd()*4)+(rnd()-.5)*3),w:V(rnd()*4-2,rnd()*4-2,rnd()*4-2)})}
 if(!b.dm)b.dm=[];if(b.dm.length<6){const h=new T.Mesh(BG,holeM);h.scale.set(xf?.3:1.8+rnd()*1.5,1.4+rnd(),xf?1.8+rnd()*1.5:.3);h.position.set(px,py,pz);S.add(h);b.dm.push(h)}
 const stg=Math.floor(f*3);if(stg>(b.stg||0)){b.stg=stg;const ro=b.m[1];if(ro){if(b.ry0==null)b.ry0=ro.position.y;ro.rotation.z=(rnd()<.5?1:-1)*.07*stg;ro.position.y-=.5*stg}b.m[0].rotation.z=(rnd()<.5?1:-1)*.012*stg}
 puff(V(px,py,pz),6,2,0xb8aa94);shake=Math.max(shake,.15);sfx(90,.3,'sine',.2);return false}
const CH=[];
function collapse(b,fx,fz){const G=b.rub||new T.Group();if(!b.rub)S.add(G);b.rub=G;(b.dm||[]).forEach(o=>o.visible=false);CO.push({b,t:0,fx,fz});puff(V(b.x,b.gy+(b.h0-b.gy)*.5,b.z),10,Math.max(b.w,b.d)*.4,0xb8aa94);sfx(70,.9,'sawtooth',.25)}
function dk(c,f){return(((c>>16&255)*f|0)<<16)|(((c>>8&255)*f|0)<<8)|((c&255)*f|0)}
function burst(b,fx,fz){const G=b.rub,gy=b.gy,hh=Math.max(4,b.h0-gy),W=b.w,D=b.d,c0=b.col||0xd8c9a8,mats=[M(c0),M(dk(c0,.85)),M(dk(c0,.7)),M(0x8a7a68)];
 const dxx=b.x-fx,dzz=b.z-fz,ll=Math.hypot(dxx,dzz)||1;
 const add=(m,vx,vy,vz,st)=>{G.add(m);CH.push([G,m]);if(CH.length>420){const o=CH.shift();o[0].remove(o[1])}if(!st)DB.push({m,v:V(vx,vy,vz),w:V(rnd()*5-2.5,rnd()*5-2.5,rnd()*5-2.5)})};
 const cs=3.4,nx=Math.max(2,Math.round(2*W/cs)),nz=Math.max(2,Math.round(2*D/cs)),ny=Math.max(2,Math.round(hh/cs));
 for(let side=-1;side<=1;side+=2)for(let ax=0;ax<2;ax++){const n=ax?nx:nz;for(let i=0;i<n;i++)for(let j=0;j<ny;j++){const wd=(ax?2*W:2*D)/n,ht=hh/ny,m=new T.Mesh(BG,mats[Math.floor(rnd()*4)]);
  const px=ax?b.x-W+(i+.5)*wd+(rnd()-.5)*.6:b.x+side*W,pz=ax?b.z+side*D:b.z-D+(i+.5)*wd+(rnd()-.5)*.6,py=gy+(j+.5)*ht;
  m.scale.set(ax?wd*.95:.7+rnd()*.4,ht*.95,ax?.7+rnd()*.4:wd*.95);m.position.set(px,py,pz);
  if(j==0){if(rnd()<.5){m.scale.y*=.4+rnd()*.4;m.position.y=gy+m.scale.y/2;add(m,0,0,0,1)}else if(rnd()<.5)G.add(m),CH.push([G,m]),DB.push({m,v:V(0,0,0),w:V(0,0,0)});else add(m,0,0,0,0)}
  else{const ox=ax?0:side,oz=ax?side:0;add(m,ox*(1.5+rnd()*3.5)+dxx/ll*(1+rnd()*2)+(rnd()-.5)*2,(j/ny)*2.5+rnd()*1.5,oz*(1.5+rnd()*3.5)+dzz/ll*(1+rnd()*2)+(rnd()-.5)*2,0)}}}
 const nr=6+Math.floor(W*D/18);for(let i=0;i<nr;i++){const m=new T.Mesh(BG,dRoof);m.scale.set(3.4,.3,2.8);m.position.set(b.x+(rnd()*2-1)*W*.9,gy+hh+1+rnd()*3,b.z+(rnd()*2-1)*D*.9);m.rotation.set((rnd()-.5)*.6,rnd()*3,(rnd()-.5)*.6);add(m,(rnd()-.5)*3,-1-rnd()*2,(rnd()-.5)*3,0)}
 for(let i=0;i<6;i++){const m=new T.Mesh(BG,dWood);m.scale.set(.35,3.2,.35);m.position.set(b.x+(rnd()*2-1)*W,gy+rnd()*hh,b.z+(rnd()*2-1)*D);m.rotation.set(rnd()*3,rnd()*3,rnd()*3);add(m,(rnd()-.5)*3,rnd()*2,(rnd()-.5)*3,0)}
 for(let i=0;i<8;i++){const s=.4+rnd()*.9,m=new T.Mesh(BG,mats[i%4]);m.scale.set(s*2,s,s*1.6);m.position.set(b.x+(rnd()*2-1)*W*.8,gy+s*.4,b.z+(rnd()*2-1)*D*.8);m.rotation.set(rnd()*.5,rnd()*3,rnd()*.5);add(m,0,0,0,1)}
 for(let k=0;k<3;k++)puff(V(b.x+(rnd()-.5)*W,gy+hh*.4,b.z+(rnd()-.5)*D),8,Math.max(W,D)*.5,0xb8aa94);
 SM.push({x:b.x,y:gy,z:b.z,t:12+rnd()*8});shake=Math.max(shake,.5);sfx(70,.8,'sawtooth',.3);sfx(190,.35,'square',.15)}
/* ===== iPad等の拡大・ダブルタップ・長押し防止 ===== */
['gesturestart','gesturechange','gestureend'].forEach(ev=>document.addEventListener(ev,e=>e.preventDefault()));
let lastTouchEnd=0;document.addEventListener('touchend',e=>{const n=Date.now();if(n-lastTouchEnd<=350&&!(e.target&&e.target.tagName==='INPUT'))e.preventDefault();lastTouchEnd=n},{passive:false});
document.addEventListener('touchmove',e=>{if(e.touches.length>1||(e.scale&&e.scale!==1))e.preventDefault()},{passive:false});
document.addEventListener('dblclick',e=>e.preventDefault());
document.addEventListener('contextmenu',e=>e.preventDefault());
/* ===== ホーム画面 ===== */
const NET={peer:null,conn:null,open:false,acc:0,name:'プレイヤー',role:null};
const RM={on:false,h:null,p:V(),tx:0,ty:0,tz:0,r:0,vx:0,vy:0,vz:0,g:1,sl:0,slPrev:0,slT:0,sp:0,ga:0,a:null,ph:0,name:'',tag:null,rope:null};
function cleanName(n){return String(n||'').replace(/[\u0000-\u001f<>]/g,'').trim().slice(0,12)}
function showHome(){try{$('nick').value=localStorage.getItem('th_nick')||''}catch(e){}$('home').style.display='flex';$('hm1').style.display='flex';$('hm2').style.display='none'}
function setMyName(){NET.name=cleanName($('nick').value)||'プレイヤー';try{localStorage.setItem('th_nick',NET.name)}catch(e){}}
function startGame(){$('home').style.display='none';if(!started){if(navigator.hardwareConcurrency&&navigator.hardwareConcurrency<=4){lite=true;sun.castShadow=false;R.setPixelRatio(1)}reset();started=true}run=true;ensureLocalTag();toast('左：移動　右：視点　フック／ガス／斬る')}
$('solo').onclick=()=>{setMyName();startGame()};
$('onb').onclick=()=>{setMyName();$('hm1').style.display='none';$('hm2').style.display='flex';$('rcw').style.display='none';$('jw').style.display='none';netStatus('')};
$('mk').onclick=()=>hostRoom();
$('jn').onclick=()=>{netCleanup();$('rcw').style.display='none';$('jw').style.display='block';netStatus('友達に教えてもらったパスワードを入力してください')};
$('jgo').onclick=()=>joinRoom();
$('bk').onclick=()=>{netCleanup();$('hm2').style.display='none';$('hm1').style.display='flex'};
$('hmb').onclick=()=>location.reload();
/* ===== 名前表示（頭の上） ===== */
function makeTag(txt,col){const c=document.createElement('canvas');c.width=384;c.height=64;const x=c.getContext('2d');x.fillStyle='rgba(0,0,0,.55)';x.fillRect(0,8,384,48);x.font='bold 30px sans-serif';x.textAlign='center';x.fillStyle=col;x.fillText(txt,192,44);
 const s=new T.Sprite(new T.SpriteMaterial({map:new T.CanvasTexture(c),transparent:true,depthTest:false}));s.renderOrder=999;S.add(s);return s}
let LTAG=null,LTAGn='';
function ensureLocalTag(){if(LTAG&&LTAGn===NET.name)return;if(LTAG)S.remove(LTAG);LTAG=makeTag(NET.name,'#ffffff');LTAGn=NET.name}
function placeTag(sp,pos,up){const d=C.position.distanceTo(pos),k=Math.max(.6,d*.035);sp.position.set(pos.x,pos.y+up,pos.z);sp.scale.set(k*6,k,1)}
/* ===== P2P（PeerJS） ===== */
function netStatus(m,err){const e=$('nst');e.textContent=m;e.style.color=err?'#ff8a80':'#fff'}
function netCleanup(){try{if(NET.conn)NET.conn.close()}catch(e){}try{if(NET.peer)NET.peer.destroy()}catch(e){}NET.peer=null;NET.conn=null;NET.open=false;NET.role=null}
function genCode(){const A='ABCDEFGHJKLMNPQRSTUVWXYZ23456789';let s='';for(let i=0;i<5;i++)s+=A[Math.floor(Math.random()*A.length)];return s}
function hostRoom(){if(typeof Peer==='undefined'){netStatus('PeerJSを読み込めませんでした（通信環境を確認してください）',1);return}
 netCleanup();const code=genCode();NET.role='host';let peer;try{peer=new Peer('titanhunt-'+code)}catch(e){netStatus('P2Pを開始できませんでした',1);return}NET.peer=peer;$('jw').style.display='none';netStatus('部屋を作成中...');
 peer.on('open',()=>{$('rc').textContent=code;$('rcw').style.display='block';netStatus('待機中...（このパスワードを友達に教えてください）')});
 peer.on('connection',c=>{if(NET.conn){c.on('open',()=>c.close());return}setupConn(c)});
 peer.on('error',e=>{if(e&&e.type==='unavailable-id')hostRoom();else netStatus('エラー: '+(e&&e.type||'不明'),1)})}
function joinRoom(){const code=($('jin').value||'').trim().toUpperCase();if(!code){netStatus('パスワードを入力してください',1);return}
 if(typeof Peer==='undefined'){netStatus('PeerJSを読み込めませんでした（通信環境を確認してください）',1);return}
 netCleanup();NET.role='guest';let peer;try{peer=new Peer()}catch(e){netStatus('P2Pを開始できませんでした',1);return}NET.peer=peer;netStatus('接続中...');
 peer.on('open',()=>{const c=peer.connect('titanhunt-'+code);const to=setTimeout(()=>{if(!NET.open)netStatus('接続できませんでした（パスワードを確認してください）',1)},12000);setupConn(c,to)});
 peer.on('error',e=>netStatus(e&&e.type==='peer-unavailable'?'その部屋は見つかりません（パスワードを確認してください）':'エラー: '+(e&&e.type||'不明'),1))}
function setupConn(c,to){NET.conn=c;const op=()=>{if(NET.open)return;if(to)clearTimeout(to);NET.open=true;try{c.send({t:'hi',n:NET.name})}catch(e){}netStatus('接続しました！');startGame()};
 if(c.open)op();else c.on('open',op);c.on('data',onNet);c.on('close',onNetClose);c.on('error',()=>onNetClose())}
function onNetClose(){if(!NET.open)return;NET.open=false;NET.conn=null;RM.on=false;if(RM.h)RM.h.g.visible=false;if(RM.tag)RM.tag.visible=false;if(RM.rope)RM.rope.visible=false;toast('相手が切断しました')}
function ensureRemote(){if(RM.h)return;RM.h=mkHuman();RM.h.g.visible=false;RM.h.cape.children[0].material.color.setHex(0x3a5a9a);RM.rope=new T.Line(new T.BufferGeometry().setFromPoints([V(),V()]),new T.LineBasicMaterial({color:0x222222}));RM.rope.frustumCulled=false;RM.rope.visible=false;S.add(RM.rope)}
function onNet(d){if(!d||typeof d!=='object')return;
 if(d.t==='hi'){ensureRemote();RM.name=cleanName(d.n)||'プレイヤー';if(RM.tag)S.remove(RM.tag);RM.tag=makeTag(RM.name,'#8fd0ff');RM.on=true;RM.h.g.visible=true;toast('参加：'+RM.name)}
 else if(d.t==='s'){ensureRemote();const f=v=>Number.isFinite(v)?v:0;if(!RM.on)return;RM.tx=f(d.x);RM.ty=f(d.y);RM.tz=f(d.z);RM.r=f(d.r);RM.vx=f(d.vx);RM.vy=f(d.vy);RM.vz=f(d.vz);RM.g=d.g?1:0;RM.sl=d.sl?1:0;RM.sp=d.sp?1:0;RM.ga=d.ga?1:0;
  RM.a=Array.isArray(d.a)?V(f(d.a[0]),f(d.a[1]),f(d.a[2])):null;if(!RM.seen){RM.seen=1;RM.p.set(RM.tx,RM.ty,RM.tz)}}}
function netTick(dt){if(LTAG&&started){LTAG.visible=true;placeTag(LTAG,H.g.position,3.4*(P.tf?P.tm.s*4:1))}
 if(!NET.conn||!NET.open)return;NET.acc+=dt;
 if(NET.acc>.066){NET.acc=0;const p=P.p,v=P.v,q=n=>+n.toFixed(2);try{NET.conn.send({t:'s',x:q(p.x),y:q(p.y),z:q(p.z),r:q(H.g.rotation.y),vx:q(v.x),vy:q(v.y),vz:q(v.z),g:P.g?1:0,sl:P.sl>0?1:0,sp:P.sp>0?1:0,ga:gasHeld?1:0,a:P.a?[q(P.a.pos.x),q(P.a.pos.y),q(P.a.pos.z)]:0})}catch(e){}}
 updateRemote(dt)}
function updateRemote(dt){if(!RM.on||!RM.h)return;const g=RM.h.g,H2=RM.h,p=RM.p,k=Math.min(1,12*dt);
 p.x+=(RM.tx-p.x)*k;p.y+=(RM.ty-p.y)*k;p.z+=(RM.tz-p.z)*k;if(Math.hypot(RM.tx-p.x,RM.ty-p.y,RM.tz-p.z)>40)p.set(RM.tx,RM.ty,RM.tz);
 g.position.copy(p);const hs=Math.hypot(RM.vx,RM.vz);if(!RM.sp&&hs>1){let da=Math.atan2(RM.vx,RM.vz)-g.rotation.y;da=Math.atan2(Math.sin(da),Math.cos(da));g.rotation.y+=da*Math.min(1,14*dt)}
 if(RM.sl&&!RM.slPrev)RM.slT=.28;RM.slPrev=RM.sl;RM.slT=Math.max(0,RM.slT-dt);if(RM.sp)g.rotation.y+=dt*14;
 RM.ph+=dt*hs*1.1;const s1=RM.g?Math.sin(RM.ph)*.9*Math.min(1,hs/9):0;
 if(RM.g){H2.lR.rotation.x=s1;H2.lL.rotation.x=-s1;H2.kR.rotation.x=Math.max(0,s1)*1.3;H2.kL.rotation.x=Math.max(0,-s1)*1.3;H2.aR.rotation.x=-s1*.8;H2.aL.rotation.x=s1*.8;H2.eR.rotation.x=H2.eL.rotation.x=-1;g.rotation.x=.1}
 else{H2.lR.rotation.x=-.5;H2.kR.rotation.x=1.1;H2.lL.rotation.x=.25;H2.kL.rotation.x=.5;H2.aR.rotation.x=RM.a?-2.7:.5;H2.aL.rotation.x=RM.a?-2.7:-.5;H2.eR.rotation.x=H2.eL.rotation.x=-.3;g.rotation.x=Math.min(.8,hs/35)}
 if(RM.slT>0){H2.ub.rotation.y=-1.1+2.2*(1-RM.slT/.28);H2.aR.rotation.x=-1.5}else H2.ub.rotation.y*=.85;
 H2.cape.rotation.x=.2+Math.min(1,Math.hypot(hs,RM.vy)/28)*1.1;
 if(RM.ga&&rnd()<dt*25)puff(V(p.x,p.y+1,p.z),1,.5);
 RM.rope.visible=!!RM.a;if(RM.a){const a=RM.rope.geometry.attributes.position;a.setXYZ(0,p.x,p.y+1.4,p.z);a.setXYZ(1,RM.a.x,RM.a.y,RM.a.z);a.needsUpdate=true}
 if(RM.tag){RM.tag.visible=true;placeTag(RM.tag,p,3.4)}}
function reset(){lockT=null;P.held=null;SM.length=0;DC.forEach(m=>S.remove(m));DC.length=0;SOL.forEach(q=>{q.alive=0;q.rt=rnd()*6;q.ct=0;q.h.g.rotation.x=0;q.h.g.visible=false;q.rp.visible=false});DB.length=0;CO.length=0;CV.forEach(c=>S.remove(c.g));CV.length=0;ate=0;idleT=0;for(let i=0;i<28;i++)spawnCiv();BL.forEach(b=>S.remove(b.m));BL.length=0;ammo=6;rel=0;if(P.tf)endTransform();P.tg=100;titans.forEach(t=>S.remove(t.g));titans=[];wave=0;score=0;B.length=0;ALL.forEach(b=>{b.m.forEach(o=>{o.visible=true;if(o.userData.y0!==undefined){o.position.y=o.userData.y0;o.scale.y=o.userData.s0;o.rotation.z=0}});if(b.rub){S.remove(b.rub);b.rub=null}(b.dm||[]).forEach(o=>S.remove(o));b.dm=[];b.hp=null;b.stg=0;if(b.ry0!=null){b.m[1].position.y=b.ry0;b.ry0=null}b.m[0].rotation.z=0;b.m[1].rotation.z=0;B.push(b)});
 Object.assign(P,{hp:7,gas:100,inv:0,a:null,sl:0,slc:0,g:true});P.p.set(126,gh(126,18),18);P.v.set(0,0,0);yaw=-Math.PI/2;rope.visible=false;spawn()}
$('go').onclick=()=>{if(lite){sun.castShadow=false;R.setPixelRatio(1);R.setSize(innerWidth,innerHeight)}if(!started){reset();started=true}$('ov').style.display='none';run=true};
function step(dt){
 const v=P.v,p=P.p,prevY=p.y,pg=P.g;if(P.tf)tfMove(dt);else{
 const fx=-Math.sin(yaw),fz=-Math.cos(yaw),rx=Math.cos(yaw),rz=-Math.sin(yaw);
 const mx=rx*jx-fx*jy,mz=rz*jx-fz*jy;
 if(P.g){const k=Math.min(1,10*dt);v.x+=(mx*10-v.x)*k;v.z+=(mz*10-v.z)*k}else{v.x+=mx*9*dt;v.z+=mz*9*dt}
 v.y-=28*dt;P.sl=Math.max(0,P.sl-dt);P.slc=Math.max(0,P.slc-dt);P.sp=Math.max(0,P.sp-dt);P.tg=Math.min(100,P.tg+1.2*dt);P.hr=(P.hr||0)+dt;if(P.hr>20){P.hr=0;if(P.hp<7)P.hp++}P.inv-=dt;
 if(gasHeld&&P.gas>0){let dx=fx,dz=fz;const l=Math.hypot(mx,mz);if(l>.1){dx=mx/l;dz=mz/l}v.x+=dx*38*dt;v.z+=dz*38*dt;v.y+=10*dt;P.gas-=22*dt;if(rnd()<dt*25)puff(new T.Vector3(p.x,p.y+1,p.z),1,.5)}
 else if(P.g)P.gas=Math.min(100,P.gas+18*dt);
 if(P.a){const a=P.a;if(a.t){if(a.t.dead)P.a=null;else a.pos.copy(a.t.nw)}
  if(P.a){const d=a.pos.clone().sub(p),L=d.length();if(L<4)P.a=null;else v.addScaledVector(d.divideScalar(L),62*dt)}
  if(!P.a)rope.visible=false}
 const sp=v.length();if(sp>42)v.multiplyScalar(42/sp);
 p.addScaledVector(v,dt);P.g=false;
 for(let k=0;k<2;k++)for(const b of B)collide(b,p,v,prevY);for(const b of []){const r=.6;
  if(p.x>b.x-b.w-r&&p.x<b.x+b.w+r&&p.z>b.z-b.d-r&&p.z<b.z+b.d+r&&p.y<b.h){
   if(prevY>=b.h-.3){p.y=b.h;if(v.y<0)v.y=0;P.g=true}
   else{const px=Math.min(p.x-(b.x-b.w-r),b.x+b.w+r-p.x),pz=Math.min(p.z-(b.z-b.d-r),b.z+b.d+r-p.z);
    if(px<pz){p.x+=p.x<b.x?-px:px;v.x=0}else{p.z+=p.z<b.z?-pz:pz;v.z=0}}}}
 const gy0=gh(p.x,p.z);if(p.y<=gy0+(pg&&v.y<=0&&!P.a?.7:0)){p.y=gy0;if(v.y<0)v.y=0;P.g=true}
 wallClamp(p);
 }const pc=new T.Vector3(p.x,p.y+(P.tf?6*P.tm.s:1),p.z);titanStep(dt,pc);bulletStep(dt);civStep(dt);ensureAction(dt);debrisStep(dt);solStep(dt);
 for(const t of []){const g=t.g;
  if(t.dead){t.dt+=dt;g.rotation.x=Math.min(t.dt*1.1,1.45);if(t.dt>1.2)g.position.y-=3*dt;if(rnd()<dt*14)puff(g.localToWorld(new T.Vector3(0,9,0)),1,1.5);continue}
  const dx=p.x-g.position.x,dz=p.z-g.position.z,L=Math.hypot(dx,dz)||1;
  let da=Math.atan2(dx,dz)-g.rotation.y;da=Math.atan2(Math.sin(da),Math.cos(da));
  const tn=(t.st==0?2.6:.6)*dt;g.rotation.y+=Math.max(-tn,Math.min(tn,da));
  t.cd-=dt;
  if(t.st==0){g.position.x+=Math.sin(g.rotation.y)*t.sp*dt;g.position.z+=Math.cos(g.rotation.y)*t.sp*dt;t.ph+=dt*t.sp*.9;
   if(L<8*t.s+4&&t.cd<=0&&p.y<15*t.s){t.st=1;t.tm=.8}}
  else{t.tm-=dt;if(t.tm<=0){if(t.st==1){t.st=2;t.tm=.3;strike(t)}else if(t.st==2){t.st=3;t.tm=.9}else{t.st=0;t.cd=1.2}}}
  const sw=Math.sin(t.ph)*(t.runner?.9:.5);t.lR.rotation.x=sw;t.lL.rotation.x=-sw;
  const ta=t.st==1?-2.7:t.st==2?-.2:t.st==3?-.1:-sw*.8;
  t.aR.rotation.x+=(ta-t.aR.rotation.x)*Math.min(1,(t.st==2?30:8)*dt);t.aL.rotation.x=sw*.8;
  t.up.rotation.x=.18+(t.runner?.25:0)+(t.st==2?.25:0);
  for(let i=B.length-1;i>=0;i--){const b=B[i];if(Math.abs(g.position.x-b.x)<b.w+2*t.s&&Math.abs(g.position.z-b.z)<b.d+2*t.s){b.m.forEach(o=>o.visible=false);puff(new T.Vector3(b.x,b.h/2,b.z),8,3,0xb8aa94);B.splice(i,1)}}
  g.updateMatrixWorld(true);t.up.localToWorld(t.nw.copy(NAPE));
  if(P.sl>0&&t.nw.distanceTo(pc)<8)kill(t)}
 for(let i=titans.length-1;i>=0;i--)if(titans[i].dead&&titans[i].dt>2.5){S.remove(titans[i].g);titans.splice(i,1)}
 infSpawn(dt);
 for(const q of pool)if(q.l>0){q.l-=dt;q.m.position.addScaledVector(q.v,dt);const k=Math.max(0,q.l/q.L);q.m.scale.setScalar(q.r*(2-k)*.8);q.m.material.opacity=k*.6;if(q.l<=0)q.m.visible=false}
}
function gameOver(){started=false;const o=$('ov');o.style.display='flex';o.querySelector('h1').textContent='敗北… 討伐数 '+score;$('go').textContent='もう一度'}
function renderOld(dt){
 const p=P.p,v=P.v,tm=performance.now()/1000,g=H.g,sp=Math.hypot(v.x,v.z);
 g.position.copy(p);g.visible=!(P.inv>0&&Math.floor(P.inv*10)%2);
 if(P.sl>0)g.rotation.y=Math.atan2(-Math.sin(yaw),-Math.cos(yaw));else if(sp>1)g.rotation.y=Math.atan2(v.x,v.z);
 if(P.g){const k=Math.min(1,sp/9);H.lR.rotation.x=Math.sin(tm*12)*.9*k;H.lL.rotation.x=-H.lR.rotation.x;H.aL.rotation.x=H.lR.rotation.x*.7;g.rotation.x=.1*k}
 else{H.lR.rotation.x=-.4;H.lL.rotation.x=.3;H.aL.rotation.x=P.a?-2.6:-.8;g.rotation.x=Math.min(.6,sp/40)}
 H.aR.rotation.x=P.sl>0?-2.4+(1-P.sl/.28)*2.9:(P.a?-2.6:(P.g?-H.lR.rotation.x*.7:-.8));
 arc.position.set(p.x,p.y+1.2,p.z);arc.rotation.y=g.rotation.y;arc.material.opacity=P.sl>0?P.sl/.28*.8:0;
 pSh.position.set(p.x,.06,p.z);pSh.scale.setScalar(Math.max(.3,.9-p.y/60));
 if(P.a){const a=rope.geometry.attributes.position;a.setXYZ(0,p.x,p.y+1.4,p.z);a.setXYZ(1,P.a.pos.x,P.a.pos.y,P.a.pos.z);a.needsUpdate=true}
 shake=Math.max(0,shake-dt*1.5);const cp=Math.cos(pitch);
 C.position.set(p.x+Math.sin(yaw)*cp*10+(rnd()-.5)*shake,Math.max(.6,p.y+2.5+Math.sin(pitch)*10)+(rnd()-.5)*shake,p.z+Math.cos(yaw)*cp*10);
 C.lookAt(p.x,p.y+2,p.z);sky.position.copy(C.position);
 $('hp').textContent='♥'.repeat(Math.max(0,P.hp));$('gb').style.width=P.gas+'%';
 const al=titans.filter(t=>!t.dead);$('wv').innerHTML='WAVE '+wave+'<br>残り '+al.length+'体／討伐 '+score;
 let nt=null,nd=1e9;for(const t of al){const d=Math.hypot(t.g.position.x-p.x,t.g.position.z-p.z);if(d<nd){nd=d;nt=t}}
 $('ar').style.display=nt&&run?'block':'none';
 if(nt){const dx=nt.g.position.x-p.x,dz=nt.g.position.z-p.z;$('ar').style.transform=`rotate(${Math.atan2(dx*Math.cos(yaw)-dz*Math.sin(yaw),-dx*Math.sin(yaw)-dz*Math.cos(yaw))}rad)`}
 R.render(S,C)}
let last=performance.now();
(function loop(n){requestAnimationFrame(loop);const dt=Math.min(.05,(n-last)/1000);last=n;slow=Math.max(0,slow-dt);if(run&&!mapOpen)step(dt*(slow>0?.3:1));if(mapOpen&&run)drawMap();netTick(dt);render(dt)})(last);
showHome();
addEventListener('resize',()=>{R.setSize(innerWidth,innerHeight);C.aspect=innerWidth/innerHeight;C.updateProjectionMatrix()});
</script></body></html>
