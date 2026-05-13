
<html lang="en">
<head>
<!-- ============================================================
     META & SEO
     ============================================================ -->
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1.0"/>
<title>Retro Hub — Premium Digital Services</title>
<meta name="description" content="Buy Discord Nitro, Spotify, Netflix, Robux, Crunchyroll and more at unbeatable prices. Trusted Discord shop. Fast delivery."/>
<meta name="keywords" content="retro hub discord shop, discord nitro cheap, netflix lifetime, robux cheap, crunchyroll, spotify premium, botted members, discord decorations"/>
<meta property="og:title" content="Retro Hub — Premium Digital Services"/>
<meta property="og:description" content="Trusted Discord shop. Nitro, Netflix, Robux, Crunchyroll and more. Instant delivery."/>
<meta property="og:type" content="website"/>
<meta name="theme-color" content="#e0001a"/>

<!-- ============================================================
     FONTS
     ============================================================ -->
<link rel="preconnect" href="https://fonts.googleapis.com"/>
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin/>
<link href="https://fonts.googleapis.com/css2?family=Rajdhani:wght@400;500;600;700&family=Exo+2:wght@300;400;500;700;900&display=swap" rel="stylesheet"/>

<style>
/* ============================================================
   CSS VARIABLES & RESET
   ============================================================ */
:root{
  --red:#e0001a;
  --red-bright:#ff1a2e;
  --red-dim:#8b0010;
  --red-glow:rgba(224,0,26,.38);
  --red-glow-soft:rgba(224,0,26,.14);
  --bg:#070707;
  --bg2:#0d0d0d;
  --bg3:#131313;
  --bg4:#1a1a1a;
  --surface:rgba(255,255,255,.04);
  --border:rgba(255,255,255,.07);
  --border-red:rgba(224,0,26,.38);
  --text:#f2f2f2;
  --text2:#aaa;
  --text3:#555;
  --font-display:'Rajdhani',sans-serif;
  --font-body:'Exo 2',sans-serif;
  --radius:12px;
  --radius-lg:18px;
  --tr:.25s cubic-bezier(.4,0,.2,1);
}
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{background:var(--bg);color:var(--text);font-family:var(--font-body);font-weight:400;line-height:1.6;overflow-x:hidden}

/* Scrollbar */
::-webkit-scrollbar{width:5px}
::-webkit-scrollbar-track{background:var(--bg2)}
::-webkit-scrollbar-thumb{background:var(--red);border-radius:3px}
::selection{background:var(--red);color:#fff}

/* ============================================================
   LOADING SCREEN
   ============================================================ */
#ls{position:fixed;inset:0;background:var(--bg);z-index:9999;display:flex;align-items:center;justify-content:center;flex-direction:column;gap:22px;transition:opacity .6s,visibility .6s}
#ls.gone{opacity:0;visibility:hidden;pointer-events:none}
.ls-logo{width:72px;height:72px;animation:lp 1.4s ease-in-out infinite}
@keyframes lp{0%,100%{transform:scale(1);filter:drop-shadow(0 0 18px var(--red))}50%{transform:scale(1.12);filter:drop-shadow(0 0 38px var(--red-bright))}}
.ls-bar{width:180px;height:3px;background:var(--bg3);border-radius:2px;overflow:hidden}
.ls-fill{height:100%;width:0;background:linear-gradient(90deg,var(--red-dim),var(--red-bright));box-shadow:0 0 8px var(--red);transition:width .06s linear}
.ls-txt{font-family:var(--font-display);font-size:11px;letter-spacing:3px;color:var(--text3);text-transform:uppercase}

/* ============================================================
   TOS MODAL
   ============================================================ */
#tos{position:fixed;inset:0;background:rgba(0,0,0,.97);z-index:9000;display:flex;align-items:center;justify-content:center;padding:14px;transition:opacity .5s,visibility .5s}
#tos.gone{opacity:0;visibility:hidden;pointer-events:none}
.tm{background:var(--bg2);border:1px solid var(--border-red);border-radius:var(--radius-lg);max-width:660px;width:100%;max-height:92vh;display:flex;flex-direction:column;box-shadow:0 0 60px rgba(224,0,26,.18);overflow:hidden;animation:tmi .45s cubic-bezier(.34,1.56,.64,1)}
@keyframes tmi{from{opacity:0;transform:scale(.88) translateY(24px)}to{opacity:1;transform:none}}
.tm-head{padding:24px 28px 18px;border-bottom:1px solid var(--border);display:flex;align-items:center;gap:13px;flex-shrink:0}
.tm-head-txt h2{font-family:var(--font-display);font-size:18px;font-weight:700;letter-spacing:1px}
.tm-head-txt p{font-size:11px;color:var(--text3);margin-top:2px}
.tm-body{padding:22px 28px;overflow-y:auto;flex:1;font-size:13px;color:var(--text2);line-height:1.8}
.tm-body::-webkit-scrollbar{width:3px}
.tm-body::-webkit-scrollbar-thumb{background:var(--red-dim)}
.ts{margin-bottom:18px}
.ts h3{font-family:var(--font-display);font-size:12.5px;font-weight:700;letter-spacing:1.5px;text-transform:uppercase;color:var(--red-bright);margin-bottom:7px;display:flex;align-items:center;gap:7px}
.ts h3::before{content:'';display:inline-block;width:3px;height:12px;background:var(--red);border-radius:2px}
.ts ul{padding-left:16px}
.ts ul li{margin-bottom:3px}
.tm-foot{padding:18px 28px 22px;border-top:1px solid var(--border);background:var(--bg3);flex-shrink:0}
.tc-row{display:flex;align-items:center;gap:11px;margin-bottom:14px;cursor:pointer}
.tc-box{width:19px;height:19px;border:2px solid var(--border-red);border-radius:5px;display:flex;align-items:center;justify-content:center;flex-shrink:0;transition:var(--tr)}
.tc-box svg{opacity:0;transform:scale(.4);transition:var(--tr)}
.tc-row.chk .tc-box{background:var(--red);border-color:var(--red);box-shadow:0 0 10px var(--red-glow)}
.tc-row.chk .tc-box svg{opacity:1;transform:scale(1)}
.tc-lbl{font-size:12.5px;color:var(--text2)}
.ta-btn{width:100%;padding:13px;background:var(--red);color:#fff;border:none;border-radius:var(--radius);font-family:var(--font-display);font-size:15px;font-weight:700;letter-spacing:2px;text-transform:uppercase;cursor:pointer;transition:var(--tr);position:relative;overflow:hidden}
.ta-btn:disabled{opacity:.35;cursor:not-allowed}
.ta-btn:not(:disabled):hover{background:var(--red-bright);box-shadow:0 0 28px var(--red-glow);transform:translateY(-1px)}

/* ============================================================
   CURSOR GLOW
   ============================================================ */
#cg{position:fixed;width:280px;height:280px;border-radius:50%;background:radial-gradient(circle,rgba(224,0,26,.07) 0%,transparent 70%);pointer-events:none;transform:translate(-50%,-50%);z-index:0;transition:opacity .3s}

/* ============================================================
   PARTICLES
   ============================================================ -->*/
#pc{position:fixed;inset:0;pointer-events:none;z-index:0;opacity:.45}

/* ============================================================
   NOTIFICATIONS
   ============================================================ -->*/
#nc{position:fixed;bottom:22px;left:22px;z-index:800;display:flex;flex-direction:column;gap:9px;pointer-events:none}
.nc{background:rgba(13,13,13,.96);border:1px solid rgba(224,0,26,.28);border-radius:11px;padding:11px 15px;display:flex;align-items:center;gap:11px;max-width:250px;pointer-events:auto;backdrop-filter:blur(14px);box-shadow:0 8px 30px rgba(0,0,0,.5);animation:nci .35s cubic-bezier(.34,1.56,.64,1);transition:opacity .3s,transform .3s}
.nc.out{opacity:0;transform:translateX(-18px)}
@keyframes nci{from{opacity:0;transform:translateX(-18px)}to{opacity:1}}
.nc-av{width:30px;height:30px;border-radius:50%;background:var(--red);display:flex;align-items:center;justify-content:center;font-family:var(--font-display);font-size:13px;font-weight:700;flex-shrink:0}
.nc-t p{font-size:11.5px;color:var(--text);font-weight:500}
.nc-t span{font-size:11px;color:var(--red);font-weight:600}
.nc-t small{font-size:10px;color:var(--text3)}

/* ============================================================
   NAVBAR
   ============================================================ -->*/
#nav{position:fixed;top:0;left:0;right:0;z-index:700;padding:0 30px;height:62px;display:flex;align-items:center;justify-content:space-between;transition:background .3s,border-color .3s,backdrop-filter .3s}
#nav.scr{background:rgba(7,7,7,.88);backdrop-filter:blur(18px);border-bottom:1px solid var(--border)}
.nb{display:flex;align-items:center;gap:9px;text-decoration:none}
.nb-logo{width:34px;height:34px;transition:filter .3s}
.nb:hover .nb-logo{filter:drop-shadow(0 0 14px var(--red-bright))}
.nb-name{font-family:var(--font-display);font-size:19px;font-weight:700;letter-spacing:2px;color:var(--text)}
.nb-name b{color:var(--red)}
.nav-links{display:flex;align-items:center;gap:4px;list-style:none}
.nav-links a{color:var(--text2);text-decoration:none;font-size:13.5px;font-weight:500;padding:7px 13px;border-radius:8px;transition:var(--tr);letter-spacing:.3px}
.nav-links a:hover{color:var(--text);background:var(--surface)}
.nav-r{display:flex;align-items:center;gap:10px}
.sbadge{display:flex;align-items:center;gap:5px;padding:4px 11px;background:rgba(0,200,80,.07);border:1px solid rgba(0,200,80,.18);border-radius:20px;font-size:10.5px;font-weight:700;color:#00c850;letter-spacing:.5px}
.sdot{width:6px;height:6px;background:#00c850;border-radius:50%;animation:pg 2s ease-in-out infinite}
@keyframes pg{0%,100%{box-shadow:0 0 0 0 rgba(0,200,80,.4)}70%{box-shadow:0 0 0 5px rgba(0,200,80,0)}}
.ndb{display:flex;align-items:center;gap:8px;padding:7px 16px;background:var(--red);color:#fff;text-decoration:none;border-radius:8px;font-family:var(--font-display);font-size:13px;font-weight:700;letter-spacing:1px;transition:var(--tr)}
.ndb:hover{background:var(--red-bright);box-shadow:0 0 18px var(--red-glow);transform:translateY(-1px)}
.ham{display:none;flex-direction:column;gap:5px;cursor:pointer;padding:7px;background:none;border:none}
.ham span{display:block;width:21px;height:2px;background:var(--text);border-radius:2px;transition:var(--tr)}
.ham.open span:nth-child(1){transform:rotate(45deg) translate(5px,5px)}
.ham.open span:nth-child(2){opacity:0;transform:scaleX(0)}
.ham.open span:nth-child(3){transform:rotate(-45deg) translate(5px,-5px)}
.mm{display:none;position:fixed;top:62px;left:0;right:0;background:rgba(7,7,7,.98);backdrop-filter:blur(18px);border-bottom:1px solid var(--border);padding:14px 22px 20px;flex-direction:column;gap:3px;z-index:699}
.mm.open{display:flex}
.mm a{color:var(--text2);text-decoration:none;font-size:14px;font-weight:500;padding:11px 14px;border-radius:8px;transition:var(--tr)}
.mm a:hover{color:var(--text);background:var(--surface)}

/* Sound btn */
#sb{position:fixed;top:70px;right:18px;z-index:600;width:36px;height:36px;background:var(--bg3);border:1px solid var(--border);border-radius:50%;display:flex;align-items:center;justify-content:center;cursor:pointer;transition:var(--tr);color:var(--text3)}
#sb:hover{border-color:var(--border-red);color:var(--red)}

/* ============================================================
   HERO
   ============================================================ -->*/
#hero{min-height:100vh;display:flex;align-items:center;justify-content:center;position:relative;overflow:hidden;padding:96px 28px 56px}
.hgrid{position:absolute;inset:0;background-image:linear-gradient(rgba(224,0,26,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(224,0,26,.035) 1px,transparent 1px);background-size:55px 55px;mask-image:radial-gradient(ellipse 75% 75% at 50% 50%,black 40%,transparent 100%)}
.hglow{position:absolute;width:560px;height:560px;background:radial-gradient(circle,rgba(224,0,26,.1) 0%,transparent 68%);top:50%;left:50%;transform:translate(-50%,-50%);pointer-events:none}
.hglow2{position:absolute;width:240px;height:240px;background:radial-gradient(circle,rgba(224,0,26,.07) 0%,transparent 70%);top:18%;right:8%;pointer-events:none;animation:hf 5s ease-in-out infinite}
@keyframes hf{0%,100%{transform:translateY(0)}50%{transform:translateY(-18px)}}
.hc{text-align:center;position:relative;z-index:2;max-width:780px}
.hl-wrap{display:inline-block;margin-bottom:24px}
.hl{width:92px;height:92px;filter:drop-shadow(0 0 28px rgba(224,0,26,.55));animation:hlp 2.8s ease-in-out infinite}
@keyframes hlp{0%,100%{filter:drop-shadow(0 0 28px rgba(224,0,26,.55))}50%{filter:drop-shadow(0 0 52px rgba(255,26,46,.8))}}
.hbadge{display:inline-flex;align-items:center;gap:7px;padding:4px 14px;background:rgba(224,0,26,.07);border:1px solid rgba(224,0,26,.22);border-radius:20px;font-size:11px;font-weight:700;color:var(--red-bright);letter-spacing:2px;text-transform:uppercase;margin-bottom:18px;animation:fu .8s .2s both}
.htitle{font-family:var(--font-display);font-size:clamp(36px,5.5vw,70px);font-weight:700;line-height:1.06;letter-spacing:-1px;margin-bottom:18px;animation:fu .8s .35s both}
.htitle span{color:var(--red)}
.hsub{font-size:16px;color:var(--text2);max-width:520px;margin:0 auto 32px;font-weight:300;animation:fu .8s .5s both}
@keyframes fu{from{opacity:0;transform:translateY(22px)}to{opacity:1;transform:none}}
.hbtns{display:flex;gap:12px;justify-content:center;flex-wrap:wrap;animation:fu .8s .65s both}
.hstats{display:flex;gap:36px;justify-content:center;flex-wrap:wrap;margin-top:52px;padding-top:36px;border-top:1px solid var(--border);animation:fu .8s .8s both}
.hstat{text-align:center}
.hstat-n{font-family:var(--font-display);font-size:34px;font-weight:700;line-height:1}
.hstat-n b{color:var(--red)}
.hstat-l{font-size:11px;color:var(--text3);letter-spacing:1.5px;text-transform:uppercase;margin-top:4px}

/* ============================================================
   BUTTONS
   ============================================================ -->*/
.btn-p{display:inline-flex;align-items:center;gap:9px;padding:13px 28px;background:var(--red);color:#fff;text-decoration:none;border-radius:var(--radius);font-family:var(--font-display);font-size:15px;font-weight:700;letter-spacing:1.5px;text-transform:uppercase;transition:var(--tr);border:none;cursor:pointer;position:relative;overflow:hidden}
.btn-p:hover{background:var(--red-bright);box-shadow:0 0 36px var(--red-glow);transform:translateY(-2px)}
.btn-g{display:inline-flex;align-items:center;gap:9px;padding:13px 28px;background:transparent;color:var(--text);text-decoration:none;border-radius:var(--radius);border:1px solid var(--border);font-family:var(--font-display);font-size:15px;font-weight:700;letter-spacing:1.5px;text-transform:uppercase;transition:var(--tr);cursor:pointer}
.btn-g:hover{border-color:var(--border-red);color:var(--red);background:var(--red-glow-soft);transform:translateY(-2px)}

/* ============================================================
   SECTION BASE
   ============================================================ -->*/
section{padding:90px 28px;position:relative;z-index:1}
.slabel{display:inline-block;font-size:10.5px;font-weight:700;letter-spacing:3px;text-transform:uppercase;color:var(--red);margin-bottom:10px}
.stitle{font-family:var(--font-display);font-size:clamp(26px,3.5vw,44px);font-weight:700;line-height:1.1;margin-bottom:14px}
.ssub{font-size:14.5px;color:var(--text2);max-width:520px;font-weight:300}
.tc{text-align:center}
.tc .ssub{margin:0 auto}
.mxc{max-width:1160px;margin:0 auto}
.rev{opacity:0;transform:translateY(26px);transition:opacity .65s ease,transform .65s ease}
.rev.vis{opacity:1;transform:none}

/* ============================================================
   CATEGORY TABS
   ============================================================ -->*/
.cat-tabs{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:32px}
.cat-tab{padding:8px 18px;background:var(--surface);border:1px solid var(--border);border-radius:8px;color:var(--text2);font-size:13px;font-weight:500;cursor:pointer;transition:var(--tr);font-family:var(--font-body)}
.cat-tab.on,.cat-tab:hover{background:rgba(224,0,26,.1);border-color:var(--border-red);color:var(--red)}

/* Search */
.srch-wrap{position:relative;margin-bottom:32px;max-width:380px}
.srch-wrap svg{position:absolute;left:13px;top:50%;transform:translateY(-50%);color:var(--text3)}
.srch{width:100%;padding:10px 13px 10px 40px;background:var(--surface);border:1px solid var(--border);border-radius:var(--radius);color:var(--text);font-family:var(--font-body);font-size:13.5px;outline:none;transition:var(--tr)}
.srch::placeholder{color:var(--text3)}
.srch:focus{border-color:var(--border-red);box-shadow:0 0 10px var(--red-glow-soft)}

.shop-controls{display:flex;align-items:flex-start;justify-content:space-between;flex-wrap:wrap;gap:16px;margin-bottom:0}

/* ============================================================
   PRODUCT GRID
   ============================================================ -->*/
.pg{display:grid;grid-template-columns:repeat(auto-fill,minmax(250px,1fr));gap:18px}

/* ============================================================
   PRODUCT CARD
   ============================================================ -->*/
.pc{background:var(--bg2);border:1px solid var(--border);border-radius:var(--radius-lg);padding:22px;position:relative;overflow:hidden;transition:var(--tr);transform-style:preserve-3d;cursor:default}
.pc::before{content:'';position:absolute;inset:0;background:linear-gradient(135deg,var(--red-glow-soft),transparent,transparent);opacity:0;transition:opacity .3s;border-radius:var(--radius-lg)}
.pc:hover::before{opacity:1}
.pc:hover{border-color:var(--border-red);box-shadow:0 0 36px rgba(224,0,26,.1),0 18px 50px rgba(0,0,0,.4);transform:translateY(-4px)}
.pc.hot{border-color:rgba(224,0,26,.42);box-shadow:0 0 18px rgba(224,0,26,.07)}
.pc-tag{position:absolute;top:14px;right:14px;padding:3px 9px;background:var(--red);border-radius:20px;font-size:9.5px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:#fff}
.pc-tag.new{background:#1a6b3c}
.pc-tag.sale{background:#8b4500}
.pc-icon{width:48px;height:48px;background:var(--bg3);border-radius:13px;display:flex;align-items:center;justify-content:center;margin-bottom:14px;transition:var(--tr);border:1px solid var(--border);font-size:22px;flex-shrink:0}
.pc:hover .pc-icon{border-color:var(--border-red);box-shadow:0 0 14px var(--red-glow-soft)}
.pc-name{font-family:var(--font-display);font-size:17px;font-weight:700;margin-bottom:3px;letter-spacing:.3px}
.pc-desc{font-size:12px;color:var(--text3);margin-bottom:14px;line-height:1.5}
.pc-foot{display:flex;align-items:center;justify-content:space-between;gap:8px;flex-wrap:wrap}
.pc-price{font-family:var(--font-display);font-size:20px;font-weight:700;color:var(--red-bright)}
.pc-orig{font-size:12px;color:var(--text3);text-decoration:line-through;margin-right:4px;font-weight:400}
.pc-btn{padding:7px 16px;background:rgba(224,0,26,.13);border:1px solid rgba(224,0,26,.28);border-radius:7px;color:var(--red);font-family:var(--font-display);font-size:12px;font-weight:700;letter-spacing:.8px;cursor:pointer;transition:var(--tr);text-decoration:none;display:inline-flex;align-items:center;gap:5px;white-space:nowrap}
.pc-btn:hover{background:var(--red);color:#fff;box-shadow:0 0 14px var(--red-glow)}

/* Price list for multi-tier products */
.price-list{display:flex;flex-direction:column;gap:6px;margin-bottom:14px}
.pl-row{display:flex;align-items:center;justify-content:space-between;padding:5px 10px;background:var(--bg3);border-radius:7px;border:1px solid var(--border)}
.pl-label{font-size:12px;color:var(--text2)}
.pl-price{font-family:var(--font-display);font-size:13px;font-weight:700;color:var(--red-bright)}

/* ============================================================
   FEATURES
   ============================================================ -->*/
#feats{background:var(--bg2)}
.fg{display:grid;grid-template-columns:repeat(auto-fill,minmax(220px,1fr));gap:18px;margin-top:50px}
.fc{padding:26px;background:var(--bg3);border:1px solid var(--border);border-radius:var(--radius-lg);transition:var(--tr)}
.fc:hover{border-color:var(--border-red);transform:translateY(-3px);box-shadow:0 0 28px rgba(224,0,26,.07)}
.fi{width:42px;height:42px;background:rgba(224,0,26,.09);border-radius:11px;display:flex;align-items:center;justify-content:center;color:var(--red);margin-bottom:14px}
.ft{font-family:var(--font-display);font-size:16px;font-weight:700;margin-bottom:7px}
.fd{font-size:12.5px;color:var(--text3);line-height:1.6}

/* ============================================================
   REVIEWS
   ============================================================ -->*/
.rg{display:grid;grid-template-columns:repeat(auto-fill,minmax(270px,1fr));gap:18px;margin-top:50px}
.rc{background:var(--bg2);border:1px solid var(--border);border-radius:var(--radius-lg);padding:22px;transition:var(--tr);position:relative;overflow:hidden}
.rc::before{content:'"';position:absolute;top:-12px;right:18px;font-size:110px;line-height:1;font-family:serif;color:var(--red);opacity:.05}
.rc:hover{border-color:var(--border-red);transform:translateY(-3px)}
.stars{display:flex;gap:3px;margin-bottom:10px;color:var(--red);font-size:13px}
.rt{font-size:13.5px;color:var(--text2);line-height:1.7;margin-bottom:16px}
.ra{display:flex;align-items:center;gap:9px}
.rav{width:34px;height:34px;border-radius:50%;background:var(--red);display:flex;align-items:center;justify-content:center;font-family:var(--font-display);font-size:13px;font-weight:700;color:#fff;flex-shrink:0}
.ran{font-size:13.5px;font-weight:600}
.rai{font-size:11px;color:var(--text3)}

/* ============================================================
   FAQ
   ============================================================ -->*/
.fl{margin-top:44px;max-width:720px;margin-left:auto;margin-right:auto}
.fi2{border-bottom:1px solid var(--border);overflow:hidden}
.fq{display:flex;align-items:center;justify-content:space-between;padding:18px 0;cursor:pointer;font-family:var(--font-display);font-size:15.5px;font-weight:600;color:var(--text);gap:14px;transition:color .2s}
.fq:hover{color:var(--red)}
.fic{width:20px;height:20px;flex-shrink:0;border-radius:50%;border:1px solid var(--border);display:flex;align-items:center;justify-content:center;color:var(--text3);transition:var(--tr)}
.fi2.open .fic{border-color:var(--red);color:var(--red);transform:rotate(45deg)}
.fa{max-height:0;overflow:hidden;transition:max-height .4s ease,padding .3s;font-size:13.5px;color:var(--text3);line-height:1.75}
.fi2.open .fa{max-height:200px;padding-bottom:14px}

/* ============================================================
   DISCORD CTA
   ============================================================ -->*/
#dcta{background:var(--bg2);text-align:center}
.dcard{max-width:580px;margin:0 auto;background:var(--bg3);border:1px solid var(--border-red);border-radius:22px;padding:52px 36px;position:relative;overflow:hidden;box-shadow:0 0 55px rgba(224,0,26,.07)}
.dcard::before{content:'';position:absolute;top:-60%;left:-20%;width:140%;height:140%;background:radial-gradient(ellipse,rgba(224,0,26,.055),transparent 70%);pointer-events:none}
.dinv{display:flex;align-items:center;background:var(--bg2);border:1px solid var(--border);border-radius:9px;overflow:hidden;margin:26px 0 22px}
.dinv-l{flex:1;padding:11px 15px;font-size:13.5px;color:var(--text2);font-family:monospace}
.dcopy{padding:11px 18px;background:rgba(224,0,26,.1);border:none;border-left:1px solid var(--border);color:var(--red);cursor:pointer;font-size:11.5px;font-weight:700;letter-spacing:1px;text-transform:uppercase;transition:var(--tr);font-family:var(--font-display)}
.dcopy:hover{background:var(--red);color:#fff}
.dcopy.ok{background:#1a6b3c;color:#fff}

/* ============================================================
   FLOATING DISCORD
   ============================================================ -->*/
#fdisc{position:fixed;bottom:22px;right:22px;z-index:700;width:50px;height:50px;background:var(--red);border-radius:50%;display:flex;align-items:center;justify-content:center;cursor:pointer;box-shadow:0 0 22px var(--red-glow),0 8px 28px rgba(0,0,0,.4);transition:var(--tr);text-decoration:none}
#fdisc:hover{transform:scale(1.1);box-shadow:0 0 36px var(--red-glow)}

/* ============================================================
   TRUSTED STRIP
   ============================================================ -->*/
.ts-strip{background:var(--bg2);padding:28px 28px;border-top:1px solid var(--border);border-bottom:1px solid var(--border)}
.ts-logos{display:flex;align-items:center;justify-content:center;gap:36px;flex-wrap:wrap;opacity:.35;filter:grayscale(1)}
.ts-logo{font-family:var(--font-display);font-size:16px;font-weight:700;letter-spacing:1px;color:var(--text)}

/* ============================================================
   FOOTER
   ============================================================ -->*/
footer{background:var(--bg2);border-top:1px solid var(--border);padding:52px 28px 28px}
.fg2{display:grid;grid-template-columns:2fr 1fr 1fr 1fr;gap:36px;max-width:1160px;margin:0 auto 36px}
.fb p{font-size:12.5px;color:var(--text3);margin-top:10px;line-height:1.65;max-width:240px}
.fc2 h4{font-family:var(--font-display);font-size:12px;font-weight:700;letter-spacing:2px;text-transform:uppercase;color:var(--text3);margin-bottom:14px}
.fc2 ul{list-style:none}
.fc2 ul li{margin-bottom:8px}
.fc2 ul li a{font-size:12.5px;color:var(--text3);text-decoration:none;transition:color .2s}
.fc2 ul li a:hover{color:var(--red)}
.fbot{max-width:1160px;margin:0 auto;padding-top:22px;border-top:1px solid var(--border);display:flex;align-items:center;justify-content:space-between;gap:14px;flex-wrap:wrap}
.fbot p{font-size:11.5px;color:var(--text3)}
.disc-note{font-size:10.5px;color:var(--text3);text-align:center;max-width:680px;margin:16px auto 0;line-height:1.6}

/* ============================================================
   RESPONSIVE
   ============================================================ -->*/
@media(max-width:1024px){section{padding:72px 22px}}
@media(max-width:768px){#nav{padding:0 18px}.nav-links,.sbadge,.ndb{display:none}.ham{display:flex}section{padding:56px 18px}.hstats{gap:22px}}
@media(max-width:560px){.hbtns{flex-direction:column;align-items:center}.btn-p,.btn-g{width:100%;justify-content:center}.fg2{grid-template-columns:1fr 1fr}.tm-head,.tm-body,.tm-foot{padding-left:18px;padding-right:18px}}
@media(max-width:420px){.fg2{grid-template-columns:1fr}}
</style>
</head>
<body>

<!-- ============================================================
     LOADING SCREEN
     ============================================================ -->
<div id="ls">
  <svg class="ls-logo" viewBox="0 0 100 100" fill="none"><rect width="100" height="100" rx="20" fill="#0d0d0d"/><path d="M22 75V25H52C62 25 70 33 70 43C70 50 66 56 60 59L72 75H58L47 61H36V75H22ZM36 49H50C54 49 57 46 57 42C57 38 54 35 50 35H36V49Z" fill="#e0001a"/><path d="M60 59L72 75H58" fill="#8b0010"/><path d="M65 25H72L55 55H48" fill="#ff1a2e" opacity=".65"/></svg>
  <div class="ls-bar"><div class="ls-fill" id="lsf"></div></div>
  <p class="ls-txt">Loading Retro Hub</p>
</div>

<!-- ============================================================
     TOS MODAL
     ============================================================ -->
<div id="tos">
  <div class="tm">
    <div class="tm-head">
      <svg width="38" height="38" viewBox="0 0 100 100" fill="none" style="filter:drop-shadow(0 0 8px var(--red));flex-shrink:0"><rect width="100" height="100" rx="18" fill="#131313"/><path d="M22 75V25H52C62 25 70 33 70 43C70 50 66 56 60 59L72 75H58L47 61H36V75H22ZM36 49H50C54 49 57 46 57 42C57 38 54 35 50 35H36V49Z" fill="#e0001a"/><path d="M60 59L72 75H58" fill="#8b0010"/></svg>
      <div class="tm-head-txt">
        <h2>TERMS OF SERVICE — RETRO HUB</h2>
        <p>Effective: January 2025 · Read fully before proceeding</p>
      </div>
    </div>
    <div class="tm-body">
      <div class="ts">
        <h3>Age Requirement</h3>
        <p>You must be at least <strong>18 years of age</strong> to purchase from Retro Hub. By proceeding you confirm this. We reserve the right to request verification and to refuse or terminate service if this condition is unmet.</p>
      </div>
      <div class="ts">
        <h3>All Sales Are Final — No Refunds</h3>
        <p>Every purchase made through Retro Hub is <strong>final and non-refundable</strong>. Once a product or service has been delivered to you — whether credentials, an invite, access, or any other form of digital goods — no refund will be issued under any circumstances including but not limited to: change of mind, inability to use, or third-party service changes.</p>
      </div>
      <div class="ts">
        <h3>Third-Party Disclaimer & No Affiliation</h3>
        <p>Retro Hub is <strong>not affiliated with, endorsed by, or officially connected to</strong> Discord, Spotify, Netflix, Roblox, Crunchyroll, Instagram, TikTok, Twitch, YouTube, or any other brand. All trademarks are property of their respective owners. Retro Hub operates as an independent digital goods reseller.</p>
        <ul>
          <li>Digital products may stop working at any time due to third-party platform changes.</li>
          <li>We cannot guarantee perpetual access to any service depending on a third-party platform.</li>
          <li>Retro Hub bears no liability for actions third-party services take against user accounts.</li>
        </ul>
      </div>
      <div class="ts">
        <h3>User Responsibility & Account Safety</h3>
        <p>You are solely responsible for the security and appropriate use of any credentials, codes, or access provided. You must <strong>not share, resell, redistribute, leak, or abuse</strong> any delivered product. Violations result in immediate and permanent blacklisting from Retro Hub and all affiliated services.</p>
      </div>
      <div class="ts">
        <h3>Chargebacks & Payment Disputes</h3>
        <p>Initiating a chargeback, PayPal dispute, or any form of payment reversal after receiving your product constitutes <strong>fraud</strong>. Any user doing so will be permanently blacklisted. We reserve the right to report fraudulent activity to payment processors and relevant authorities.</p>
      </div>
      <div class="ts">
        <h3>Service Revocation, Bans & Right to Refuse</h3>
        <p>Retro Hub staff hold the absolute right to <strong>refuse service, revoke access, or permanently ban</strong> any user for abuse, fraud, harassment, chargebacks, reselling, leaking, or any violation of these Terms, Discord's ToS, or applicable law. No refund will be issued upon termination for violations.</p>
      </div>
      <div class="ts">
        <h3>Discord ToS & Legal Compliance</h3>
        <p>By purchasing, you agree to comply with <strong>Discord's Terms of Service</strong>, Community Guidelines, and all applicable laws and regulations in your local jurisdiction. Our services may not be used for any illegal purpose.</p>
      </div>
      <div class="ts">
        <h3>Services Provided "As-Is"</h3>
        <p>All products and services are provided <strong>"as-is" without warranty</strong> of any kind, express or implied. Retro Hub does not guarantee uninterrupted access, specific duration, or that the service will meet your expectations after delivery.</p>
      </div>
      <div class="ts">
        <h3>Misuse, Leaking & Reselling</h3>
        <p>Any form of misuse — including unauthorized reselling of products purchased from Retro Hub, leaking credentials, or using services to harm others — will result in <strong>immediate and permanent blacklisting</strong> with no recourse. We actively monitor for abuse.</p>
      </div>
      <div class="ts">
        <h3>Liability Limitation</h3>
        <p>To the maximum extent permitted by law, Retro Hub and its staff are not liable for indirect, incidental, special, or consequential damages arising from use or inability to use our products or services, even if advised of the possibility of such damages.</p>
      </div>
      <div class="ts">
        <h3>Account Termination</h3>
        <p>We may terminate your access to Retro Hub at any time for any reason, with or without notice. Users terminated for violations are not entitled to compensation or refund.</p>
      </div>
      <div class="ts">
        <h3>Governing Law</h3>
        <p>These Terms are governed by applicable international digital commerce law. Disputes shall first be pursued through good-faith negotiation, and if unresolved, through binding arbitration.</p>
      </div>
      <div class="ts">
        <h3>Agreement</h3>
        <p>By ticking the checkbox and clicking "I Agree & Enter", you confirm you have fully read and understood these Terms of Service, and agree to be legally bound by them. Your acceptance timestamp is recorded in your browser.</p>
      </div>
    </div>
    <div class="tm-foot">
      <label class="tc-row" id="tcrow">
        <div class="tc-box">
          <svg width="11" height="11" viewBox="0 0 11 11" fill="none"><path d="M1.5 5.5L4.5 8.5L9.5 2.5" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
        </div>
        <span class="tc-lbl">I have fully read and agree to the Terms of Service. I confirm I am 18 years of age or older.</span>
      </label>
      <button class="ta-btn" id="taagrn" disabled>I AGREE &amp; ENTER RETRO HUB</button>
    </div>
  </div>
</div>

<!-- Cursor glow -->
<div id="cg"></div>
<!-- Particles -->
<canvas id="pc"></canvas>
<!-- Notifications -->
<div id="nc"></div>

<!-- ============================================================
     NAVBAR
     ============================================================ -->
<nav id="nav">
  <a href="#" class="nb">
    <svg class="nb-logo" style="width:34px;height:34px;filter:drop-shadow(0 0 7px var(--red))" viewBox="0 0 100 100" fill="none"><path d="M22 75V25H52C62 25 70 33 70 43C70 50 66 56 60 59L72 75H58L47 61H36V75H22ZM36 49H50C54 49 57 46 57 42C57 38 54 35 50 35H36V49Z" fill="#e0001a"/><path d="M60 59L72 75H58" fill="#8b0010"/></svg>
    <span class="nb-name">Retro <b>Hub</b></span>
  </a>
  <ul class="nav-links">
    <li><a href="#shop">Shop</a></li>
    <li><a href="#feats">Features</a></li>
    <li><a href="#reviews">Reviews</a></li>
    <li><a href="#faq">FAQ</a></li>
  </ul>
  <div class="nav-r">
    <div class="sbadge"><div class="sdot"></div>ONLINE</div>
    <a href="https://discord.gg/DfU3ZQNgAV" target="_blank" class="ndb">
      <svg width="15" height="15" viewBox="0 0 24 24" fill="currentColor"><path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0 12.64 12.64 0 0 0-.617-1.25.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057.1 18.08.114 18.1.135 18.115a19.9 19.9 0 0 0 5.993 3.03.078.078 0 0 0 .084-.028c.462-.63.874-1.295 1.226-1.994a.076.076 0 0 0-.041-.106 13.107 13.107 0 0 1-1.872-.892.077.077 0 0 1-.008-.128 10.2 10.2 0 0 0 .372-.292.074.074 0 0 1 .077-.01c3.928 1.793 8.18 1.793 12.062 0a.074.074 0 0 1 .078.01c.12.098.246.198.373.292a.077.077 0 0 1-.006.127 12.299 12.299 0 0 1-1.873.892.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028 19.839 19.839 0 0 0 6.002-3.03.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.03z"/></svg>
      JOIN DISCORD
    </a>
    <button class="ham" id="ham" aria-label="Menu"><span></span><span></span><span></span></button>
  </div>
</nav>

<!-- Mobile menu -->
<div class="mm" id="mm">
  <a href="#shop">🛒 Shop</a>
  <a href="#feats">⚡ Features</a>
  <a href="#reviews">⭐ Reviews</a>
  <a href="#faq">❓ FAQ</a>
  <a href="https://discord.gg/DfU3ZQNgAV" target="_blank" style="color:var(--red);font-weight:600">💬 Join Discord</a>
</div>

<!-- Sound btn -->
<button id="sb" title="Toggle sound">
  <svg id="son" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polygon points="11 5 6 9 2 9 2 15 6 15 11 19 11 5"/><path d="M19.07 4.93a10 10 0 0 1 0 14.14"/><path d="M15.54 8.46a5 5 0 0 1 0 7.07"/></svg>
  <svg id="soff" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" style="display:none"><polygon points="11 5 6 9 2 9 2 15 6 15 11 19 11 5"/><line x1="23" y1="9" x2="17" y2="15"/><line x1="17" y1="9" x2="23" y2="15"/></svg>
</button>

<!-- ============================================================
     HERO
     ============================================================ -->
<section id="hero">
  <div class="hgrid"></div>
  <div class="hglow"></div>
  <div class="hglow2"></div>
  <div class="hc">
    <div class="hl-wrap">
      <svg class="hl" viewBox="0 0 100 100" fill="none"><path d="M22 75V25H52C62 25 70 33 70 43C70 50 66 56 60 59L72 75H58L47 61H36V75H22ZM36 49H50C54 49 57 46 57 42C57 38 54 35 50 35H36V49Z" fill="#e0001a"/><path d="M60 59L72 75H58" fill="#8b0010"/><path d="M65 25H72L55 55H48" fill="#ff1a2e" opacity=".65"/></svg>
    </div>
    <div class="hbadge"><div class="sdot"></div>Delivery Active — Open 24/7</div>
    <h1 class="htitle">Premium Digital<br/><span>Services</span> for Less</h1>
    <p class="hsub">Nitro, Decos, Netflix, Robux, Followers, Crunchyroll &amp; more — delivered instantly to your DMs.</p>
    <div class="hbtns">
      <a href="#shop" class="btn-p">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="9" cy="21" r="1"/><circle cx="20" cy="21" r="1"/><path d="M1 1h4l2.68 13.39a2 2 0 0 0 2 1.61h9.72a2 2 0 0 0 2-1.61L23 6H6"/></svg>
        Browse Shop
      </a>
      <a href="https://discord.gg/DfU3ZQNgAV" target="_blank" class="btn-g">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor"><path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0 12.64 12.64 0 0 0-.617-1.25.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057.1 18.08.114 18.1.135 18.115a19.9 19.9 0 0 0 5.993 3.03.078.078 0 0 0 .084-.028c.462-.63.874-1.295 1.226-1.994a.076.076 0 0 0-.041-.106 13.107 13.107 0 0 1-1.872-.892.077.077 0 0 1-.008-.128 10.2 10.2 0 0 0 .372-.292.074.074 0 0 1 .077-.01c3.928 1.793 8.18 1.793 12.062 0a.074.074 0 0 1 .078.01c.12.098.246.198.373.292a.077.077 0 0 1-.006.127 12.299 12.299 0 0 1-1.873.892.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028 19.839 19.839 0 0 0 6.002-3.03.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.03z"/></svg>
        Join Server
      </a>
    </div>
    <div class="hstats">
      <div class="hstat">
        <div class="hstat-n"><span class="ctr" data-t="100">0</span><b>+</b></div>
        <div class="hstat-l">Members</div>
      </div>
      <div class="hstat">
        <div class="hstat-n"><span class="ctr" data-t="15">0</span><b>+</b></div>
        <div class="hstat-l">Orders Fulfilled</div>
      </div>
      <div class="hstat">
        <div class="hstat-n"><span class="ctr" data-t="9">0</span><b></b></div>
        <div class="hstat-l">Categories</div>
      </div>
      <div class="hstat">
        <div class="hstat-n"><span class="ctr" data-t="99">0</span><b>%</b></div>
        <div class="hstat-l">Uptime</div>
      </div>
    </div>
  </div>
</section>

<!-- Trusted strip -->
<div class="ts-strip">
  <p class="slabel tc" style="display:block;margin-bottom:12px">We sell services for these platforms</p>
  <div class="ts-logos">
    <span class="ts-logo">DISCORD</span>
    <span class="ts-logo">SPOTIFY</span>
    <span class="ts-logo">NETFLIX</span>
    <span class="ts-logo">ROBLOX</span>
    <span class="ts-logo">CRUNCHYROLL</span>
    <span class="ts-logo">INSTAGRAM</span>
    <span class="ts-logo">TIKTOK</span>
    <span class="ts-logo">TWITCH</span>
  </div>
</div>

<!-- ============================================================
     SHOP
     ============================================================ -->
<section id="shop">
  <div class="mxc">
    <div class="tc rev">
      <span class="slabel">Digital Storefront</span>
      <h2 class="stitle">All Products</h2>
      <p class="ssub">Click any product's channel button to buy. All prices final. Delivered in minutes.</p>
    </div>

    <div class="shop-controls rev" style="margin-top:36px">
      <div class="srch-wrap" style="margin-bottom:0">
        <svg width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.35-4.35"/></svg>
        <input class="srch" id="si" type="text" placeholder="Search products…"/>
      </div>
      <div class="cat-tabs" id="ctabs">
        <button class="cat-tab on" data-cat="all">All</button>
        <button class="cat-tab" data-cat="discord">Discord</button>
        <button class="cat-tab" data-cat="streaming">Streaming</button>
        <button class="cat-tab" data-cat="gaming">Gaming</button>
        <button class="cat-tab" data-cat="social">Social</button>
        <button class="cat-tab" data-cat="crypto">Crypto</button>
      </div>
    </div>

    <div class="pg rev" id="pgrid" style="margin-top:28px">

      <!-- NITRO -->
      <div class="pc hot" data-cat="discord">
        <span class="pc-tag">HOT</span>
        <div class="pc-icon">💜</div>
        <div class="pc-name">Discord Nitro</div>
        <div class="pc-desc">All tiers available — instant delivery</div>
        <div class="price-list">
          <div class="pl-row"><span class="pl-label">Nitro Boost</span><span class="pl-price">$3.80</span></div>
          <div class="pl-row"><span class="pl-label">Nitro Basic</span><span class="pl-price">$1.30</span></div>
          <div class="pl-row"><span class="pl-label">Promo — 1 Month</span><span class="pl-price">$0.40</span></div>
          <div class="pl-row"><span class="pl-label">Promo — 3 Months</span><span class="pl-price">$1.30</span></div>
        </div>
        <a href="https://discord.gg/MZb4QfC5Au" target="_blank" class="pc-btn" style="width:100%;justify-content:center">
          <svg width="13" height="13" viewBox="0 0 24 24" fill="currentColor"><path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0 12.64 12.64 0 0 0-.617-1.25.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057.1 18.08.114 18.1.135 18.115a19.9 19.9 0 0 0 5.993 3.03.078.078 0 0 0 .084-.028c.462-.63.874-1.295 1.226-1.994a.076.076 0 0 0-.041-.106 13.107 13.107 0 0 1-1.872-.892.077.077 0 0 1-.008-.128 10.2 10.2 0 0 0 .372-.292.074.074 0 0 1 .077-.01c3.928 1.793 8.18 1.793 12.062 0a.074.074 0 0 1 .078.01c.12.098.246.198.373.292a.077.077 0 0 1-.006.127 12.299 12.299 0 0 1-1.873.892.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028 19.839 19.839 0 0 0 6.002-3.03.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.03z"/></svg>
          BUY IN CHANNEL
        </a>
      </div>

      <!-- DISCORD DECOS -->
      <div class="pc" data-cat="discord">
        <span class="pc-tag new">DECO</span>
        <div class="pc-icon">✨</div>
        <div class="pc-name">Discord Decorations</div>
        <div class="pc-desc">Profile decorations at massive discounts vs retail</div>
        <div class="price-list">
          <div class="pl-row"><span class="pl-label">Retail $4.99</span><span class="pl-price">$1.70</span></div>
          <div class="pl-row"><span class="pl-label">Retail $5.99</span><span class="pl-price">$2.00</span></div>
          <div class="pl-row"><span class="pl-label">Retail $6.99</span><span class="pl-price">$2.60</span></div>
          <div class="pl-row"><span class="pl-label">Retail $7.99</span><span class="pl-price">$2.90</span></div>
          <div class="pl-row"><span class="pl-label">Retail $8.49</span><span class="pl-price">$3.20</span></div>
          <div class="pl-row"><span class="pl-label">Retail $9.99</span><span class="pl-price">$3.70</span></div>
          <div class="pl-row"><span class="pl-label">Retail $11.99</span><span class="pl-price">$4.00</span></div>
        </div>
        <a href="https://discord.gg/a7nGt94Gr" target="_blank" class="pc-btn" style="width:100%;justify-content:center">
          <svg width="13" height="13" viewBox="0 0 24 24" fill="currentColor"><path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0 12.64 12.64 0 0 0-.617-1.25.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057.1 18.08.114 18.1.135 18.115a19.9 19.9 0 0 0 5.993 3.03.078.078 0 0 0 .084-.028c.462-.63.874-1.295 1.226-1.994a.076.076 0 0 0-.041-.106 13.107 13.107 0 0 1-1.872-.892.077.077 0 0 1-.008-.128 10.2 10.2 0 0 0 .372-.292.074.074 0 0 1 .077-.01c3.928 1.793 8.18 1.793 12.062 0a.074.074 0 0 1 .078.01c.12.098.246.198.373.292a.077.077 0 0 1-.006.127 12.299 12.299 0 0 1-1.873.892.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028 19.839 19.839 0 0 0 6.002-3.03.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.03z"/></svg>
          BUY IN CHANNEL
        </a>
      </div>

      <!-- AGED ACCOUNTS -->
      <div class="pc" data-cat="discord">
        <div class="pc-icon">🏛️</div>
        <div class="pc-name">Aged Discord Accounts</div>
        <div class="pc-desc">Vintage accounts — older = more trusted &amp; valuable</div>
        <div class="price-list">
          <div class="pl-row"><span class="pl-label">2020 Account</span><span class="pl-price">$1.00</span></div>
          <div class="pl-row"><span class="pl-label">2019 Account</span><span class="pl-price">$2.00</span></div>
          <div class="pl-row"><span class="pl-label">2018 Account</span><span class="pl-price">$3.00</span></div>
          <div class="pl-row"><span class="pl-label">2017 Account</span><span class="pl-price">$4.50</span></div>
          <div class="pl-row"><span class="pl-label">2016 Account</span><span class="pl-price">$11.00</span></div>
        </div>
        <a href="https://discord.gg/7qSrg3u2YD" target="_blank" class="pc-btn" style="width:100%;justify-content:center">
          <svg width="13" height="13" viewBox="0 0 24 24" fill="currentColor"><path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0 12.64 12.64 0 0 0-.617-1.25.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057.1 18.08.114 18.1.135 18.115a19.9 19.9 0 0 0 5.993 3.03.078.078 0 0 0 .084-.028c.462-.63.874-1.295 1.226-1.994a.076.076 0 0 0-.041-.106 13.107 13.107 0 0 1-1.872-.892.077.077 0 0 1-.008-.128 10.2 10.2 0 0 0 .372-.292.074.074 0 0 1 .077-.01c3.928 1.793 8.18 1.793 12.062 0a.074.074 0 0 1 .078.01c.12.098.246.198.373.292a.077.077 0 0 1-.006.127 12.299 12.299 0 0 1-1.873.892.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028 19.839 19.839 0 0 0 6.002-3.03.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.03z"/></svg>
          BUY IN CHANNEL
        </a>
      </div>

      <!-- BOTTED MEMBERS -->
      <div class="pc" data-cat="discord">
        <span class="pc-tag sale">BULK</span>
        <div class="pc-icon">👥</div>
        <div class="pc-name">Botted Members</div>
        <div class="pc-desc">Boost your server's member count. Open a ticket to order.</div>
        <div class="price-list">
          <div class="pl-row"><span class="pl-label">1,000 Offline Members</span><span class="pl-price">$1.00</span></div>
          <div class="pl-row"><span class="pl-label">1,000 Online Members</span><span class="pl-price">$2.00</span></div>
        </div>
        <a href="https://discord.gg/cCWtt25Tm7" target="_blank" class="pc-btn" style="width:100%;justify-content:center">
          <svg width="13" height="13" viewBox="0 0 24 24" fill="currentColor"><path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0 12.64 12.64 0 0 0-.617-1.25.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057.1 18.08.114 18.1.135 18.115a19.9 19.9 0 0 0 5.993 3.03.078.078 0 0 0 .084-.028c.462-.63.874-1.295 1.226-1.994a.076.076 0 0 0-.041-.106 13.107 13.107 0 0 1-1.872-.892.077.077 0 0 1-.008-.128 10.2 10.2 0 0 0 .372-.292.074.074 0 0 1 .077-.01c3.928 1.793 8.18 1.793 12.062 0a.074.074 0 0 1 .078.01c.12.098.246.198.373.292a.077.077 0 0 1-.006.127 12.299 12.299 0 0 1-1.873.892.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028 19.839 19.839 0 0 0 6.002-3.03.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.03z"/></svg>
          OPEN A TICKET
        </a>
      </div>

      <!-- CRYPTO FLASHER -->
      <div class="pc hot" data-cat="crypto">
        <span class="pc-tag">⚡</span>
        <div class="pc-icon">₿</div>
        <div class="pc-name">Crypto Flasher</div>
        <div class="pc-desc">Flash usable credits — bulk discounts available</div>
        <div class="price-list">
          <div class="pl-row"><span class="pl-label">1 Use</span><span class="pl-price">$0.20</span></div>
          <div class="pl-row"><span class="pl-label">10 Uses ($1)</span><span class="pl-price">$1.00</span></div>
          <div class="pl-row"><span class="pl-label">50 Uses</span><span class="pl-price">$3.50</span></div>
          <div class="pl-row"><span class="pl-label">100 Uses</span><span class="pl-price">$7.00</span></div>
          <div class="pl-row"><span class="pl-label">200 Uses</span><span class="pl-price">$13.00</span></div>
          <div class="pl-row"><span class="pl-label">Unlimited Uses</span><span class="pl-price">$35.00</span></div>
        </div>
        <a href="https://discord.gg/fj3H6DpWZt" target="_blank" class="pc-btn" style="width:100%;justify-content:center">
          <svg width="13" height="13" viewBox="0 0 24 24" fill="currentColor"><path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0 12.64 12.64 0 0 0-.617-1.25.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057.1 18.08.114 18.1.135 18.115a19.9 19.9 0 0 0 5.993 3.03.078.078 0 0 0 .084-.028c.462-.63.874-1.295 1.226-1.994a.076.076 0 0 0-.041-.106 13.107 13.107 0 0 1-1.872-.892.077.077 0 0 1-.008-.128 10.2 10.2 0 0 0 .372-.292.074.074 0 0 1 .077-.01c3.928 1.793 8.18 1.793 12.062 0a.074.074 0 0 1 .078.01c.12.098.246.198.373.292a.077.077 0 0 1-.006.127 12.299 12.299 0 0 1-1.873.892.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028 19.839 19.839 0 0 0 6.002-3.03.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.03z"/></svg>
          BUY IN CHANNEL
        </a>
      </div>

      <!-- CRUNCHYROLL -->
      <div class="pc" data-cat="streaming">
        <div class="pc-icon">🍥</div>
        <div class="pc-name">Crunchyroll</div>
        <div class="pc-desc">Ad-free anime streaming — Fan &amp; Mega Fan plans</div>
        <div class="price-list">
          <div class="pl-row"><span class="pl-label">Fan Plan</span><span class="pl-price">$0.20</span></div>
          <div class="pl-row"><span class="pl-label">Mega Fan Plan</span><span class="pl-price">$0.50</span></div>
        </div>
        <a href="https://discord.gg/X2RSAeKz2k" target="_blank" class="pc-btn" style="width:100%;justify-content:center">
          <svg width="13" height="13" viewBox="0 0 24 24" fill="currentColor"><path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0 12.64 12.64 0 0 0-.617-1.25.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057.1 18.08.114 18.1.135 18.115a19.9 19.9 0 0 0 5.993 3.03.078.078 0 0 0 .084-.028c.462-.63.874-1.295 1.226-1.994a.076.076 0 0 0-.041-.106 13.107 13.107 0 0 1-1.872-.892.077.077 0 0 1-.008-.128 10.2 10.2 0 0 0 .372-.292.074.074 0 0 1 .077-.01c3.928 1.793 8.18 1.793 12.062 0a.074.074 0 0 1 .078.01c.12.098.246.198.373.292a.077.077 0 0 1-.006.127 12.299 12.299 0 0 1-1.873.892.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028 19.839 19.839 0 0 0 6.002-3.03.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.03z"/></svg>
          BUY IN CHANNEL
        </a>
      </div>

      <!-- NETFLIX -->
      <div class="pc hot" data-cat="streaming">
        <span class="pc-tag">🎬</span>
        <div class="pc-icon">📺</div>
        <div class="pc-name">Netflix</div>
        <div class="pc-desc">Lifetime access — one-time payment, no renewals</div>
        <div class="price-list">
          <div class="pl-row"><span class="pl-label">Netflix Lifetime</span><span class="pl-price">$0.70</span></div>
        </div>
        <a href="https://discord.gg/6HDV39gmaV" target="_blank" class="pc-btn" style="width:100%;justify-content:center">
          <svg width="13" height="13" viewBox="0 0 24 24" fill="currentColor"><path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0 12.64 12.64 0 0 0-.617-1.25.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057.1 18.08.114 18.1.135 18.115a19.9 19.9 0 0 0 5.993 3.03.078.078 0 0 0 .084-.028c.462-.63.874-1.295 1.226-1.994a.076.076 0 0 0-.041-.106 13.107 13.107 0 0 1-1.872-.892.077.077 0 0 1-.008-.128 10.2 10.2 0 0 0 .372-.292.074.074 0 0 1 .077-.01c3.928 1.793 8.18 1.793 12.062 0a.074.074 0 0 1 .078.01c.12.098.246.198.373.292a.077.077 0 0 1-.006.127 12.299 12.299 0 0 1-1.873.892.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028 19.839 19.839 0 0 0 6.002-3.03.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.03z"/></svg>
          BUY IN CHANNEL
        </a>
      </div>

      <!-- FOLLOWERS & LIKES -->
      <div class="pc" data-cat="social">
        <span class="pc-tag new">SOCIAL</span>
        <div class="pc-icon">📈</div>
        <div class="pc-name">Followers &amp; Likes</div>
        <div class="pc-desc">Instagram, TikTok &amp; Twitch accounts with real follower counts</div>
        <div class="price-list">
          <div class="pl-row"><span class="pl-label">1K Instagram Followers</span><span class="pl-price">$6.00</span></div>
          <div class="pl-row"><span class="pl-label">1K TikTok Followers</span><span class="pl-price">$4.50</span></div>
          <div class="pl-row"><span class="pl-label">Twitch Acc — 2K Followers</span><span class="pl-price">$2.00</span></div>
          <div class="pl-row"><span class="pl-label">Twitch Acc — 5K Followers</span><span class="pl-price">$2.50</span></div>
          <div class="pl-row"><span class="pl-label">Twitch Acc — 9K Followers</span><span class="pl-price">$3.00</span></div>
        </div>
        <a href="https://discord.gg/TbWBUwF3G6" target="_blank" class="pc-btn" style="width:100%;justify-content:center">
          <svg width="13" height="13" viewBox="0 0 24 24" fill="currentColor"><path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0 12.64 12.64 0 0 0-.617-1.25.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057.1 18.08.114 18.1.135 18.115a19.9 19.9 0 0 0 5.993 3.03.078.078 0 0 0 .084-.028c.462-.63.874-1.295 1.226-1.994a.076.076 0 0 0-.041-.106 13.107 13.107 0 0 1-1.872-.892.077.077 0 0 1-.008-.128 10.2 10.2 0 0 0 .372-.292.074.074 0 0 1 .077-.01c3.928 1.793 8.18 1.793 12.062 0a.074.074 0 0 1 .078.01c.12.098.246.198.373.292a.077.077 0 0 1-.006.127 12.299 12.299 0 0 1-1.873.892.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028 19.839 19.839 0 0 0 6.002-3.03.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.03z"/></svg>
          BUY IN CHANNEL
        </a>
      </div>

      <!-- ROBUX -->
      <div class="pc hot" data-cat="gaming">
        <span class="pc-tag">🎮</span>
        <div class="pc-icon">R$</div>
        <div class="pc-name">Robux</div>
        <div class="pc-desc">Roblox accounts with items worth specified Robux value. 32K in stock!</div>
        <div class="price-list">
          <div class="pl-row"><span class="pl-label">1,000 Robux value</span><span class="pl-price">$3.50</span></div>
          <div class="pl-row"><span class="pl-label">2,500 Robux value</span><span class="pl-price">$6.00</span></div>
          <div class="pl-row"><span class="pl-label">5,000 Robux value</span><span class="pl-price">$9.00</span></div>
          <div class="pl-row"><span class="pl-label">10,000 Robux value</span><span class="pl-price">$13.50</span></div>
          <div class="pl-row"><span class="pl-label">50,000+ Robux value</span><span class="pl-price">$35.00</span></div>
        </div>
        <a href="https://discord.gg/kxGUTDR449" target="_blank" class="pc-btn" style="width:100%;justify-content:center">
          <svg width="13" height="13" viewBox="0 0 24 24" fill="currentColor"><path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0 12.64 12.64 0 0 0-.617-1.25.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057.1 18.08.114 18.1.135 18.115a19.9 19.9 0 0 0 5.993 3.03.078.078 0 0 0 .084-.028c.462-.63.874-1.295 1.226-1.994a.076.076 0 0 0-.041-.106 13.107 13.107 0 0 1-1.872-.892.077.077 0 0 1-.008-.128 10.2 10.2 0 0 0 .372-.292.074.074 0 0 1 .077-.01c3.928 1.793 8.18 1.793 12.062 0a.074.074 0 0 1 .078.01c.12.098.246.198.373.292a.077.077 0 0 1-.006.127 12.299 12.299 0 0 1-1.873.892.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028 19.839 19.839 0 0 0 6.002-3.03.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.03z"/></svg>
          BUY IN CHANNEL
        </a>
      </div>

      <!-- SPOTIFY -->
      <div class="pc" data-cat="streaming">
        <div class="pc-icon">🎵</div>
        <div class="pc-name">Spotify Premium</div>
        <div class="pc-desc">3 months of ad-free music — best value deal</div>
        <div class="price-list">
          <div class="pl-row"><span class="pl-label">3 Months Premium</span><span class="pl-price">$2.50</span></div>
        </div>
        <a href="https://discord.gg/DfU3ZQNgAV" target="_blank" class="pc-btn" style="width:100%;justify-content:center">
          <svg width="13" height="13" viewBox="0 0 24 24" fill="currentColor"><path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0 12.64 12.64 0 0 0-.617-1.25.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057.1 18.08.114 18.1.135 18.115a19.9 19.9 0 0 0 5.993 3.03.078.078 0 0 0 .084-.028c.462-.63.874-1.295 1.226-1.994a.076.076 0 0 0-.041-.106 13.107 13.107 0 0 1-1.872-.892.077.077 0 0 1-.008-.128 10.2 10.2 0 0 0 .372-.292.074.074 0 0 1 .077-.01c3.928 1.793 8.18 1.793 12.062 0a.074.074 0 0 1 .078.01c.12.098.246.198.373.292a.077.077 0 0 1-.006.127 12.299 12.299 0 0 1-1.873.892.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028 19.839 19.839 0 0 0 6.002-3.03.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.03z"/></svg>
          BUY IN CHANNEL
        </a>
      </div>

    </div><!-- /pgrid -->
  </div>
</section>

<!-- ============================================================
     FEATURES
     ============================================================ -->
<section id="feats">
  <div class="mxc">
    <div class="tc rev">
      <span class="slabel">Why Retro Hub</span>
      <h2 class="stitle">Built Different</h2>
      <p class="ssub">We're a growing community-backed shop that's already proven itself across 15+ orders.</p>
    </div>
    <div class="fg">
      <div class="fc rev">
        <div class="fi"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M13 2L3 14h9l-1 8 10-12h-9l1-8z"/></svg></div>
        <div class="ft">Instant Delivery</div>
        <div class="fd">Open a ticket or check the channel — most products delivered in under 5 minutes, around the clock.</div>
      </div>
      <div class="fc rev">
        <div class="fi"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg></div>
        <div class="ft">Verified Stock</div>
        <div class="fd">Every product is checked before it's listed. No dead accounts, no invalid codes — or we replace it.</div>
      </div>
      <div class="fc rev">
        <div class="fi"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg></div>
        <div class="ft">Active Support</div>
        <div class="fd">Staff respond fast on Discord. Open a ticket and get help within minutes — no waiting days for a reply.</div>
      </div>
      <div class="fc rev">
        <div class="fi"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="12" y1="1" x2="12" y2="23"/><path d="M17 5H9.5a3.5 3.5 0 0 0 0 7h5a3.5 3.5 0 0 1 0 7H6"/></svg></div>
        <div class="ft">Lowest Prices</div>
        <div class="fd">Netflix lifetime for $0.70. Crunchyroll for $0.20. Nitro promo for $0.40. You won't find these prices elsewhere.</div>
      </div>
      <div class="fc rev">
        <div class="fi"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="11" width="18" height="11" rx="2" ry="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg></div>
        <div class="ft">Safe &amp; Discreet</div>
        <div class="fd">We deliver through Discord DMs with clear instructions. No sketchy links, no unnecessary info collected.</div>
      </div>
      <div class="fc rev">
        <div class="fi"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="22 12 18 12 15 21 9 3 6 12 2 12"/></svg></div>
        <div class="ft">Growing Every Day</div>
        <div class="fd">100+ members and growing. New products added regularly. Join early and be part of the community from the start.</div>
      </div>
    </div>
  </div>
</section>

<!-- ============================================================
     REVIEWS
     ============================================================ -->
<section id="reviews">
  <div class="mxc">
    <div class="tc rev">
      <span class="slabel">Customer Feedback</span>
      <h2 class="stitle">What Buyers Say</h2>
      <p class="ssub">Real feedback from real members of Retro Hub.</p>
    </div>
    <div class="rg">
      <div class="rc rev">
        <div class="stars">★★★★★</div>
        <p class="rt">Got Nitro promo for $0.40 and it worked instantly. No way I'm ever paying full price again. Retro Hub is the real deal, already told my whole server.</p>
        <div class="ra"><div class="rav">ZK</div><div><div class="ran">Zakari K.</div><div class="rai">Discord Nitro Promo · Verified</div></div></div>
      </div>
      <div class="rc rev">
        <div class="stars">★★★★★</div>
        <p class="rt">Netflix lifetime for $0.70 is legitimately insane. Been using it for weeks no issues. Staff answered my ticket within 2 minutes. Solid shop.</p>
        <div class="ra"><div class="rav">ML</div><div><div class="ran">Marcus L.</div><div class="rai">Netflix Lifetime · Verified</div></div></div>
      </div>
      <div class="rc rev">
        <div class="stars">★★★★★</div>
        <p class="rt">Bought a 2016 Discord account and it was exactly as described. Good aged, no issues. Will come back for more when I need them. Great service.</p>
        <div class="ra"><div class="rav">AS</div><div><div class="ran">Alex S.</div><div class="rai">Aged Discord Account · Verified</div></div></div>
      </div>
      <div class="rc rev">
        <div class="stars">★★★★★</div>
        <p class="rt">Got 5000 Robux value for $9. The account had items worth way more than expected. Definitely coming back. Shop knows what they're doing.</p>
        <div class="ra"><div class="rav">DK</div><div><div class="ran">Dylan K.</div><div class="rai">Robux Account · Verified</div></div></div>
      </div>
      <div class="rc rev">
        <div class="stars">★★★★★</div>
        <p class="rt">Crunchyroll Mega Fan for literally 50 cents. Insane. No ads, full HD, works perfectly. I was skeptical but this shop keeps proving itself legit.</p>
        <div class="ra"><div class="rav">HR</div><div><div class="ran">Hina R.</div><div class="rai">Crunchyroll Mega Fan · Verified</div></div></div>
      </div>
      <div class="rc rev">
        <div class="stars">★★★★★</div>
        <p class="rt">Spotify 3 months for $2.50 is genuinely crazy value. Server is growing fast, staff are legit. Don't sleep on Retro Hub — one of the best shops I've used.</p>
        <div class="ra"><div class="rav">JT</div><div><div class="ran">Jake T.</div><div class="rai">Spotify Premium · Verified</div></div></div>
      </div>
    </div>
  </div>
</section>

<!-- ============================================================
     FAQ
     ============================================================ -->
<section id="faq" style="background:var(--bg2)">
  <div class="mxc">
    <div class="tc rev">
      <span class="slabel">Got Questions?</span>
      <h2 class="stitle">FAQ</h2>
      <p class="ssub">Can't find your answer? Open a ticket on our Discord.</p>
    </div>
    <div class="fl rev">
      <div class="fi2">
        <div class="fq">How do I buy? Where do I pay?<div class="fic"><svg width="9" height="9" viewBox="0 0 10 10" fill="none" stroke="currentColor" stroke-width="2"><line x1="5" y1="0" x2="5" y2="10"/><line x1="0" y1="5" x2="10" y2="5"/></svg></div></div>
        <div class="fa">Click the "BUY IN CHANNEL" button on any product card. This links directly to that product's channel on our Discord server. Once there, follow the pinned instructions or open a ticket to complete your purchase.</div>
      </div>
      <div class="fi2">
        <div class="fq">What payment methods are accepted?<div class="fic"><svg width="9" height="9" viewBox="0 0 10 10" fill="none" stroke="currentColor" stroke-width="2"><line x1="5" y1="0" x2="5" y2="10"/><line x1="0" y1="5" x2="10" y2="5"/></svg></div></div>
        <div class="fa">We accept various payment methods — check the specific product channel on Discord for the current accepted methods. Crypto and PayPal F&F are most commonly used. Never send PayPal as G&S.</div>
      </div>
      <div class="fi2">
        <div class="fq">Are refunds available?<div class="fic"><svg width="9" height="9" viewBox="0 0 10 10" fill="none" stroke="currentColor" stroke-width="2"><line x1="5" y1="0" x2="5" y2="10"/><line x1="0" y1="5" x2="10" y2="5"/></svg></div></div>
        <div class="fa">All sales are final per our ToS. No refunds after delivery. However, if a product arrives non-functional or invalid on arrival, we will replace it. Chargebacks result in an immediate permanent ban.</div>
      </div>
      <div class="fi2">
        <div class="fq">How fast is delivery?<div class="fic"><svg width="9" height="9" viewBox="0 0 10 10" fill="none" stroke="currentColor" stroke-width="2"><line x1="5" y1="0" x2="5" y2="10"/><line x1="0" y1="5" x2="10" y2="5"/></svg></div></div>
        <div class="fa">Most products are delivered in under 5 minutes once payment is confirmed. Botted members and some custom orders may take a bit longer. Open a ticket if there's any delay beyond 20 minutes.</div>
      </div>
      <div class="fi2">
        <div class="fq">What if my product stops working?<div class="fic"><svg width="9" height="9" viewBox="0 0 10 10" fill="none" stroke="currentColor" stroke-width="2"><line x1="5" y1="0" x2="5" y2="10"/><line x1="0" y1="5" x2="10" y2="5"/></svg></div></div>
        <div class="fa">Third-party services can change at any time beyond our control. If your product stops working early through no fault of your own, open a ticket and our staff will work with you on a replacement where possible.</div>
      </div>
      <div class="fi2">
        <div class="fq">Can I resell the products I buy?<div class="fic"><svg width="9" height="9" viewBox="0 0 10 10" fill="none" stroke="currentColor" stroke-width="2"><line x1="5" y1="0" x2="5" y2="10"/><line x1="0" y1="5" x2="10" y2="5"/></svg></div></div>
        <div class="fa">Unauthorized reselling or redistribution of any product purchased from Retro Hub is strictly prohibited and will result in an immediate, permanent ban from our server and all affiliated communities with no refund.</div>
      </div>
    </div>
  </div>
</section>

<!-- ============================================================
     DISCORD CTA
     ============================================================ -->
<section id="dcta">
  <div class="dcard rev">
    <span class="slabel">Ready to Save Money?</span>
    <h2 class="stitle" style="margin-bottom:10px">Join Retro Hub</h2>
    <p style="font-size:13.5px;color:var(--text2)">100+ members &amp; growing. All products accessible through our Discord. Click to join.</p>
    <div class="dinv">
      <span class="dinv-l" id="invl">discord.gg/DfU3ZQNgAV</span>
      <button class="dcopy" id="dcbtn">COPY</button>
    </div>
    <a href="https://discord.gg/DfU3ZQNgAV" target="_blank" class="btn-p">
      <svg width="18" height="18" viewBox="0 0 24 24" fill="currentColor"><path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0 12.64 12.64 0 0 0-.617-1.25.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057.1 18.08.114 18.1.135 18.115a19.9 19.9 0 0 0 5.993 3.03.078.078 0 0 0 .084-.028c.462-.63.874-1.295 1.226-1.994a.076.076 0 0 0-.041-.106 13.107 13.107 0 0 1-1.872-.892.077.077 0 0 1-.008-.128 10.2 10.2 0 0 0 .372-.292.074.074 0 0 1 .077-.01c3.928 1.793 8.18 1.793 12.062 0a.074.074 0 0 1 .078.01c.12.098.246.198.373.292a.077.077 0 0 1-.006.127 12.299 12.299 0 0 1-1.873.892.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028 19.839 19.839 0 0 0 6.002-3.03.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.03z"/></svg>
      JOIN RETRO HUB NOW
    </a>
    <p style="font-size:11px;color:var(--text3);margin-top:18px">Free to join · Fast support · Instant delivery</p>
  </div>
</section>

<!-- ============================================================
     FOOTER
     ============================================================ -->
<footer>
  <div class="fg2">
    <div class="fb">
      <a href="#" class="nb"><svg style="width:30px;height:30px;filter:drop-shadow(0 0 6px var(--red))" viewBox="0 0 100 100" fill="none"><path d="M22 75V25H52C62 25 70 33 70 43C70 50 66 56 60 59L72 75H58L47 61H36V75H22ZM36 49H50C54 49 57 46 57 42C57 38 54 35 50 35H36V49Z" fill="#e0001a"/><path d="M60 59L72 75H58" fill="#8b0010"/></svg><span class="nb-name" style="font-size:17px">Retro <b>Hub</b></span></a>
      <p>Premium digital services at prices you won't find anywhere else. Trusted shop on Discord since day one.</p>
    </div>
    <div class="fc2">
      <h4>Products</h4>
      <ul>
        <li><a href="https://discord.gg/MZb4QfC5Au" target="_blank">Discord Nitro</a></li>
        <li><a href="https://discord.gg/a7nGt94Gr" target="_blank">Discord Decos</a></li>
        <li><a href="https://discord.gg/7qSrg3u2YD" target="_blank">Aged Accounts</a></li>
        <li><a href="https://discord.gg/cCWtt25Tm7" target="_blank">Botted Members</a></li>
        <li><a href="https://discord.gg/fj3H6DpWZt" target="_blank">Crypto Flasher</a></li>
        <li><a href="https://discord.gg/X2RSAeKz2k" target="_blank">Crunchyroll</a></li>
        <li><a href="https://discord.gg/6HDV39gmaV" target="_blank">Netflix</a></li>
        <li><a href="https://discord.gg/TbWBUwF3G6" target="_blank">Followers</a></li>
        <li><a href="https://discord.gg/kxGUTDR449" target="_blank">Robux</a></li>
        <li><a href="https://discord.gg/DfU3ZQNgAV" target="_blank">Spotify</a></li>
      </ul>
    </div>
    <div class="fc2">
      <h4>Support</h4>
      <ul>
        <li><a href="https://discord.gg/DfU3ZQNgAV" target="_blank">Open a Ticket</a></li>
        <li><a href="https://discord.gg/DfU3ZQNgAV" target="_blank">Order Status</a></li>
        <li><a href="https://discord.gg/DfU3ZQNgAV" target="_blank">Replacements</a></li>
        <li><a href="https://discord.gg/DfU3ZQNgAV" target="_blank">Contact Staff</a></li>
      </ul>
    </div>
    <div class="fc2">
      <h4>Legal</h4>
      <ul>
        <li><a href="#" onclick="document.getElementById('tos').style.cssText='';document.body.style.overflow='hidden'">Terms of Service</a></li>
        <li><a href="#">Privacy Policy</a></li>
        <li><a href="#">Refund Policy</a></li>
      </ul>
    </div>
  </div>
  <div class="fbot">
    <p>© 2025 Retro Hub. All rights reserved.</p>
    <div class="sbadge"><div class="sdot"></div>All Systems Online</div>
  </div>
  <p class="disc-note">Retro Hub is an independent digital goods reseller. We are not affiliated with, endorsed by, or officially connected to Discord, Spotify, Netflix, Roblox, Crunchyroll, Instagram, TikTok, Twitch, YouTube, or any other platform. All product names and trademarks are property of their respective owners. All sales are final. By purchasing you agree to our Terms of Service.</p>
</footer>

<!-- Floating Discord -->
<a href="https://discord.gg/DfU3ZQNgAV" target="_blank" id="fdisc" title="Join Discord">
  <svg width="22" height="22" viewBox="0 0 24 24" fill="white"><path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0 12.64 12.64 0 0 0-.617-1.25.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057.1 18.08.114 18.1.135 18.115a19.9 19.9 0 0 0 5.993 3.03.078.078 0 0 0 .084-.028c.462-.63.874-1.295 1.226-1.994a.076.076 0 0 0-.041-.106 13.107 13.107 0 0 1-1.872-.892.077.077 0 0 1-.008-.128 10.2 10.2 0 0 0 .372-.292.074.074 0 0 1 .077-.01c3.928 1.793 8.18 1.793 12.062 0a.074.074 0 0 1 .078.01c.12.098.246.198.373.292a.077.077 0 0 1-.006.127 12.299 12.299 0 0 1-1.873.892.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028 19.839 19.839 0 0 0 6.002-3.03.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.03z"/></svg>
</a>

<!-- ============================================================
     JAVASCRIPT
     ============================================================ -->
<script>
/* Console warning */
console.log('%c⚠ STOP!','color:#e0001a;font-size:44px;font-weight:900');
console.log('%cThis is a browser developer tool. Pasting code here can compromise your account.\n— Retro Hub Security','color:#f0f0f0;font-size:13px');

/* ============================================================
   LOADING SCREEN
   ============================================================ */
const lsf=document.getElementById('lsf'),lsel=document.getElementById('ls');
let lsp=0;
const lsi=setInterval(()=>{
  lsp+=Math.random()*15+3;
  if(lsp>=100){lsp=100;clearInterval(lsi);setTimeout(()=>lsel.classList.add('gone'),350)}
  lsf.style.width=lsp+'%';
},100);

/* ============================================================
   TOS
   ============================================================ */
(function(){
  const overlay=document.getElementById('tos');
  if(localStorage.getItem('rh_tos')){overlay.classList.add('gone');return}
  document.body.style.overflow='hidden';
  let ok=false;
  document.getElementById('tcrow').addEventListener('click',()=>{
    ok=!ok;
    document.getElementById('tcrow').classList.toggle('chk',ok);
    document.getElementById('taagrn').disabled=!ok;
  });
  document.getElementById('taagrn').addEventListener('click',()=>{
    if(!ok)return;
    localStorage.setItem('rh_tos','1');
    localStorage.setItem('rh_tos_ts',new Date().toISOString());
    overlay.classList.add('gone');
    document.body.style.overflow='';
  });
})();

/* ============================================================
   NAVBAR SCROLL
   ============================================================ */
const nav=document.getElementById('nav');
window.addEventListener('scroll',()=>nav.classList.toggle('scr',scrollY>20),{passive:true});

/* ============================================================
   HAMBURGER
   ============================================================ */
const ham=document.getElementById('ham'),mm=document.getElementById('mm');
ham.addEventListener('click',()=>{ham.classList.toggle('open');mm.classList.toggle('open')});
mm.querySelectorAll('a').forEach(a=>a.addEventListener('click',()=>{ham.classList.remove('open');mm.classList.remove('open')}));

/* ============================================================
   CURSOR GLOW
   ============================================================ */
const cg=document.getElementById('cg');
window.addEventListener('mousemove',e=>{cg.style.left=e.clientX+'px';cg.style.top=e.clientY+'px'},{passive:true});

/* ============================================================
   PARTICLES
   ============================================================ */
(()=>{
  const c=document.getElementById('pc'),x=c.getContext('2d');
  let W,H,ps=[];
  function resize(){W=c.width=innerWidth;H=c.height=innerHeight}
  resize();window.addEventListener('resize',resize,{passive:true});
  class P{
    constructor(){this.r()}
    r(){this.x=Math.random()*W;this.y=Math.random()*H;this.s=Math.random()*1.4+.3;this.vx=(Math.random()-.5)*.28;this.vy=(Math.random()-.5)*.28;this.o=Math.random()*.45+.1;this.col=Math.random()<.28?'#e0001a':'#fff'}
    u(){this.x+=this.vx;this.y+=this.vy;if(this.x<0||this.x>W||this.y<0||this.y>H)this.r()}
    d(){x.beginPath();x.arc(this.x,this.y,this.s,0,Math.PI*2);x.fillStyle=this.col;x.globalAlpha=this.o;x.fill()}
  }
  for(let i=0;i<100;i++)ps.push(new P());
  function a(){x.clearRect(0,0,W,H);x.globalAlpha=1;ps.forEach(p=>{p.u();p.d()});requestAnimationFrame(a)}
  a();
})();

/* ============================================================
   SCROLL REVEAL
   ============================================================ */
const ro=new IntersectionObserver(entries=>entries.forEach(e=>{if(e.isIntersecting){e.target.classList.add('vis');ro.unobserve(e.target)}}),{threshold:.08,rootMargin:'0px 0px -36px 0px'});
document.querySelectorAll('.rev').forEach(r=>ro.observe(r));

/* ============================================================
   COUNTERS
   ============================================================ */
const co=new IntersectionObserver(entries=>entries.forEach(e=>{
  if(e.isIntersecting){
    const el=e.target,t=+el.dataset.t,dur=1800,step=t/(dur/16);
    let cur=0;const ti=setInterval(()=>{cur+=step;if(cur>=t){cur=t;clearInterval(ti)}el.textContent=Math.floor(cur).toLocaleString()},16);
    co.unobserve(el);
  }
}),{threshold:.6});
document.querySelectorAll('.ctr').forEach(c=>co.observe(c));

/* ============================================================
   CARD TILT
   ============================================================ */
document.querySelectorAll('.pc,.fc,.rc').forEach(card=>{
  card.addEventListener('mousemove',e=>{
    const r=card.getBoundingClientRect(),x=(e.clientX-r.left)/r.width-.5,y=(e.clientY-r.top)/r.height-.5;
    card.style.transform=`perspective(500px) rotateY(${x*7}deg) rotateX(${-y*7}deg) translateY(-4px)`;
  });
  card.addEventListener('mouseleave',()=>{card.style.transform=''});
});

/* ============================================================
   SEARCH & FILTER
   ============================================================ */
const si=document.getElementById('si');
let cf='all';
document.getElementById('ctabs').addEventListener('click',e=>{
  if(!e.target.matches('.cat-tab'))return;
  document.querySelectorAll('.cat-tab').forEach(b=>b.classList.remove('on'));
  e.target.classList.add('on');
  cf=e.target.dataset.cat;
  filter();
});
si.addEventListener('input',filter);
function filter(){
  const q=si.value.toLowerCase();
  document.querySelectorAll('#pgrid .pc').forEach(c=>{
    const name=c.querySelector('.pc-name').textContent.toLowerCase();
    const cat=c.dataset.cat;
    const mf=cf==='all'||cat===cf;
    const ms=!q||name.includes(q);
    c.style.display=mf&&ms?'':'none';
  });
}

/* ============================================================
   COPY DISCORD INVITE
   ============================================================ */
document.getElementById('dcbtn').addEventListener('click',function(){
  navigator.clipboard.writeText('https://discord.gg/DfU3ZQNgAV').catch(()=>{});
  this.textContent='✓ COPIED!';this.classList.add('ok');
  setTimeout(()=>{this.textContent='COPY';this.classList.remove('ok')},2500);
});

/* ============================================================
   FAQ ACCORDION
   ============================================================ */
document.querySelectorAll('.fq').forEach(q=>{
  q.addEventListener('click',()=>{
    const it=q.parentElement,open=it.classList.contains('open');
    document.querySelectorAll('.fi2.open').forEach(i=>i.classList.remove('open'));
    if(!open)it.classList.add('open');
  });
});

/* ============================================================
   SOUND TOGGLE (visual only)
   ============================================================ */
let son=false;
document.getElementById('sb').addEventListener('click',()=>{
  son=!son;
  document.getElementById('son').style.display=son?'block':'none';
  document.getElementById('soff').style.display=son?'none':'block';
});

/* ============================================================
   LIVE PURCHASE NOTIFICATIONS
   ============================================================ */
(()=>{
  const buys=[
    {u:'Z***k',p:'Discord Nitro Promo',t:'just now'},
    {u:'M***s',p:'Netflix Lifetime',t:'1m ago'},
    {u:'A***x',p:'2018 Discord Account',t:'just now'},
    {u:'D***n',p:'5000 Robux',t:'3m ago'},
    {u:'H***a',p:'Crunchyroll Mega Fan',t:'just now'},
    {u:'J***e',p:'Spotify 3 Months',t:'2m ago'},
    {u:'R***l',p:'Discord Nitro Basic',t:'just now'},
    {u:'S***h',p:'1K TikTok Followers',t:'4m ago'},
    {u:'T***o',p:'100 Crypto Flasher Uses',t:'just now'},
    {u:'K***i',p:'Discord Decorations',t:'1m ago'},
    {u:'B***y',p:'1000 Online Members',t:'just now'},
    {u:'P***s',p:'10000 Robux',t:'5m ago'},
  ];
  const nc=document.getElementById('nc');
  function show(){
    const b=buys[Math.floor(Math.random()*buys.length)];
    const d=document.createElement('div');
    d.className='nc';
    d.innerHTML=`<div class="nc-av">${b.u[0]}</div><div class="nc-t"><p>${b.u} purchased</p><span>${b.p}</span><small>${b.t}</small></div>`;
    nc.appendChild(d);
    setTimeout(()=>{d.classList.add('out');setTimeout(()=>d.remove(),350)},4200);
  }
  setTimeout(()=>{show();setInterval(show,7000+Math.random()*4000)},3500);
})();

/* Close mobile menu on scroll */
window.addEventListener('scroll',()=>{if(mm.classList.contains('open')){ham.classList.remove('open');mm.classList.remove('open')}},{passive:true});
</script>
</body>
</html>
