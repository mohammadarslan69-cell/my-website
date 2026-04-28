<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Eminent Ventures Auto Transport | Licensed Broker | 48 States</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Barlow:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,400&family=Barlow+Condensed:wght@400;600;700;800&display=swap" rel="stylesheet">
<style>
:root {
  --navy: #07111f;
  --navy-mid: #0c1d36;
  --navy-light: #152a48;
  --gold: #c8962a;
  --gold-light: #e8b84b;
  --gold-dim: rgba(200,150,42,0.15);
  --white: #ffffff;
  --offwhite: #f5f3ef;
  --gray: #6b7280;
  --light-gray: #e5e7eb;
  --green: #16a34a;
}
*, *::before, *::after { margin:0; padding:0; box-sizing:border-box; }
html { scroll-behavior:smooth; }
body { font-family:'Barlow',sans-serif; background:#fff; color:#1a1a1a; overflow-x:hidden; }
a { text-decoration:none; }

/* TOP BAR */
.topbar {
  background:var(--gold);
  padding:9px 48px;
  display:flex; align-items:center; justify-content:space-between;
}
.topbar span { font-size:12px; font-weight:700; color:var(--navy); letter-spacing:.5px; }
.topbar-right { display:flex; gap:28px; }
.topbar-right a { font-size:12px; font-weight:800; color:var(--navy); letter-spacing:.5px; display:flex; align-items:center; gap:6px; transition:opacity .2s; }
.topbar-right a:hover { opacity:.75; }

/* NAV */
nav {
  background:var(--navy);
  display:flex; align-items:center; justify-content:space-between;
  padding:0 48px; height:82px;
  position:sticky; top:0; z-index:1000;
  box-shadow:0 4px 40px rgba(0,0,0,0.55);
  border-bottom:2px solid rgba(200,150,42,0.25);
}
.logo { display:flex; align-items:center; gap:16px; }
.logo-emblem {
  width:58px; height:58px; flex-shrink:0;
  position:relative;
}
.logo-emblem svg { width:100%; height:100%; }
.logo-wordmark { display:flex; flex-direction:column; }
.logo-name { font-family:'Bebas Neue',sans-serif; font-size:27px; color:var(--white); letter-spacing:4px; line-height:1; }
.logo-sub { font-size:8.5px; color:var(--gold); letter-spacing:5px; text-transform:uppercase; line-height:1; margin-top:3px; }
.logo-sep { width:1px; height:38px; background:rgba(200,150,42,0.35); margin:0 8px; }
.logo-reg { font-size:9px; color:#4a6a8a; letter-spacing:1.5px; text-transform:uppercase; line-height:1.6; }
.logo-reg strong { display:block; color:#6a8aaa; font-weight:700; }

.nav-links { display:flex; gap:30px; list-style:none; }
.nav-links a { color:#9ab0cc; font-size:11.5px; font-weight:700; letter-spacing:2px; text-transform:uppercase; padding:4px 0; border-bottom:2px solid transparent; transition:color .2s,border-color .2s; }
.nav-links a:hover { color:var(--gold); border-bottom-color:var(--gold); }

.nav-actions { display:flex; align-items:center; gap:14px; }
.nav-call {
  display:flex; align-items:center; gap:9px;
  background:rgba(200,150,42,0.12); border:1.5px solid rgba(200,150,42,0.35);
  padding:10px 20px; color:var(--gold); font-weight:800; font-size:14px;
  letter-spacing:.5px; transition:background .2s;
}
.nav-call:hover { background:rgba(200,150,42,0.25); }
.btn-nav-quote {
  background:var(--gold); color:var(--navy);
  padding:12px 26px; font-weight:800; font-size:11.5px;
  letter-spacing:2px; text-transform:uppercase; border:none; cursor:pointer;
  clip-path:polygon(10px 0%,100% 0%,calc(100% - 10px) 100%,0% 100%);
  transition:background .2s,transform .1s; display:inline-block;
}
.btn-nav-quote:hover { background:var(--gold-light); transform:translateY(-1px); }

/* HERO */
.hero {
  background:var(--navy); min-height:700px;
  display:flex; align-items:center;
  position:relative; overflow:hidden;
}
.hero-grid-bg {
  position:absolute; inset:0; pointer-events:none;
  background-image:linear-gradient(rgba(200,150,42,0.035) 1px,transparent 1px),linear-gradient(90deg,rgba(200,150,42,0.035) 1px,transparent 1px);
  background-size:64px 64px;
}
.hero-glow { position:absolute; top:-220px; right:-80px; width:720px; height:720px; background:radial-gradient(circle,rgba(25,75,160,0.3) 0%,transparent 68%); pointer-events:none; }
.hero-glow2 { position:absolute; bottom:-150px; left:-100px; width:500px; height:500px; background:radial-gradient(circle,rgba(200,150,42,0.07) 0%,transparent 70%); pointer-events:none; }
.hero-stripe { position:absolute; bottom:0; left:0; right:0; height:5px; background:linear-gradient(90deg,var(--gold) 0%,var(--gold-light) 50%,var(--gold) 100%); }

.hero-wrap { display:flex; align-items:center; gap:48px; max-width:1220px; margin:0 auto; width:100%; padding:70px 48px; position:relative; z-index:2; }
.hero-content { flex:1; min-width:0; }
.hero-badge { display:inline-flex; align-items:center; gap:8px; background:var(--gold-dim); border:1px solid rgba(200,150,42,0.5); color:var(--gold); font-size:11px; letter-spacing:3px; text-transform:uppercase; font-weight:700; padding:8px 18px; margin-bottom:26px; }
.hero h1 { font-family:'Bebas Neue',sans-serif; font-size:88px; line-height:.92; color:var(--white); letter-spacing:3px; margin-bottom:18px; }
.hero h1 em { color:var(--gold); font-style:normal; display:block; }
.hero-sub { color:#7a9abb; font-size:17px; font-weight:400; line-height:1.7; margin-bottom:38px; max-width:540px; }
.hero-btns { display:flex; gap:14px; flex-wrap:wrap; margin-bottom:40px; }
.btn-hero { background:var(--gold); color:var(--navy); padding:18px 42px; font-weight:800; font-size:13px; letter-spacing:2.5px; text-transform:uppercase; clip-path:polygon(12px 0%,100% 0%,calc(100% - 12px) 100%,0% 100%); border:none; cursor:pointer; display:inline-flex; align-items:center; gap:8px; transition:background .2s,transform .15s; }
.btn-hero:hover { background:var(--gold-light); transform:translateY(-2px); }
.btn-hero-outline { display:inline-flex; align-items:center; gap:10px; background:transparent; color:var(--white); padding:17px 34px; font-weight:700; font-size:13px; letter-spacing:2px; text-transform:uppercase; border:2px solid rgba(255,255,255,0.3); transition:border-color .2s,color .2s; }
.btn-hero-outline:hover { border-color:var(--gold); color:var(--gold); }
.trust-strip { display:flex; gap:32px; flex-wrap:wrap; }
.trust-item { display:flex; align-items:center; gap:8px; }
.trust-item span:first-child { font-size:18px; }
.trust-item span:last-child { font-size:11px; font-weight:700; color:#4a6a8a; letter-spacing:1.5px; text-transform:uppercase; }

/* HERO FORM */
.hero-form {
  width:345px; flex-shrink:0;
  background:rgba(255,255,255,0.055);
  backdrop-filter:blur(14px);
  border:1.5px solid rgba(200,150,42,0.3);
  padding:32px 28px;
  box-shadow:0 24px 70px rgba(0,0,0,0.45);
}
.hf-head { margin-bottom:22px; }
.hf-title { font-family:'Bebas Neue',sans-serif; font-size:32px; color:var(--white); letter-spacing:2px; line-height:1; }
.hf-sub { font-size:10.5px; color:var(--gold); letter-spacing:3px; text-transform:uppercase; margin-top:4px; }
.hf-lock { display:inline-flex; align-items:center; gap:6px; background:rgba(22,163,74,0.15); border:1px solid rgba(22,163,74,0.4); color:#4ade80; font-size:11px; font-weight:700; letter-spacing:1px; text-transform:uppercase; padding:6px 12px; margin-top:10px; }
.hf-g { margin-bottom:12px; }
.hf-g label { display:block; font-size:9.5px; font-weight:800; letter-spacing:2.5px; text-transform:uppercase; color:#6a8aaa; margin-bottom:5px; }
.hf-g input, .hf-g select { width:100%; padding:11px 13px; background:rgba(255,255,255,0.08); border:1.5px solid rgba(255,255,255,0.12); color:var(--white); font-family:'Barlow',sans-serif; font-size:14px; outline:none; transition:border-color .2s,background .2s; }
.hf-g input::placeholder { color:rgba(255,255,255,0.28); }
.hf-g input:focus, .hf-g select:focus { border-color:var(--gold); background:rgba(255,255,255,0.12); }
.hf-g select option { background:var(--navy-mid); color:#fff; }
.hf-toggle { display:flex; }
.hf-tb { flex:1; padding:10px; border:1.5px solid rgba(255,255,255,0.12); background:transparent; color:rgba(255,255,255,0.45); font-size:11px; font-weight:800; letter-spacing:1.5px; text-transform:uppercase; cursor:pointer; transition:all .2s; }
.hf-tb.active { background:var(--gold); color:var(--navy); border-color:var(--gold); }
.hf-submit { width:100%; padding:15px; background:var(--gold); color:var(--navy); font-weight:800; font-size:13px; letter-spacing:2px; text-transform:uppercase; border:none; cursor:pointer; margin-top:8px; display:flex; align-items:center; justify-content:center; gap:8px; transition:background .2s,transform .15s; }
.hf-submit:hover { background:var(--gold-light); transform:translateY(-1px); }
.hf-fine { font-size:10px; color:rgba(255,255,255,0.25); margin-top:10px; line-height:1.5; }
.hf-fine a { color:rgba(200,150,42,0.6); }
.form-success { display:none; text-align:center; padding:20px 0; }
.form-success.show { display:block; }
.form-success .fs-icon { font-size:48px; margin-bottom:12px; }
.form-success .fs-title { font-family:'Bebas Neue',sans-serif; font-size:26px; color:var(--white); letter-spacing:2px; margin-bottom:8px; }
.form-success .fs-text { font-size:13px; color:#6a8aaa; line-height:1.6; }
.form-success .fs-text strong { color:var(--gold); }

/* STATS */
.stats-bar { background:var(--gold); display:grid; grid-template-columns:repeat(5,1fr); }
.stat-item { padding:24px 16px; text-align:center; border-right:1px solid rgba(7,17,31,0.18); display:flex; flex-direction:column; align-items:center; }
.stat-item:last-child { border-right:none; }
.stat-num { font-family:'Bebas Neue',sans-serif; font-size:42px; color:var(--navy); letter-spacing:2px; line-height:1; }
.stat-label { font-size:9.5px; font-weight:800; letter-spacing:2.5px; text-transform:uppercase; color:rgba(7,17,31,0.62); margin-top:3px; }

/* SECTION COMMONS */
.section-tag { font-size:10px; letter-spacing:5px; text-transform:uppercase; color:var(--gold); font-weight:800; margin-bottom:10px; display:flex; align-items:center; gap:12px; }
.section-tag::before { content:''; display:block; width:30px; height:2.5px; background:var(--gold); flex-shrink:0; }
.section-title { font-family:'Bebas Neue',sans-serif; font-size:54px; letter-spacing:3px; color:var(--navy); line-height:1; margin-bottom:14px; }
.section-title.light { color:var(--white); }
.section-sub { color:var(--gray); font-size:16px; line-height:1.65; max-width:660px; }
.section-sub.light { color:#7090b0; }

/* STEPS */
.steps-section { padding:96px 48px; background:var(--offwhite); }
.steps-inner { max-width:1160px; margin:0 auto; }
.steps-grid { display:grid; grid-template-columns:repeat(3,1fr); gap:28px; margin-top:56px; }
.step-card { background:var(--white); padding:40px 32px; border-top:4px solid var(--gold); box-shadow:0 2px 24px rgba(0,0,0,0.06); position:relative; overflow:hidden; transition:transform .25s,box-shadow .25s; }
.step-card:hover { transform:translateY(-6px); box-shadow:0 20px 56px rgba(0,0,0,0.12); }
.step-bg-num { position:absolute; top:-14px; right:16px; font-family:'Bebas Neue',sans-serif; font-size:110px; color:rgba(200,150,42,0.07); line-height:1; pointer-events:none; }
.step-icon-box { width:54px; height:54px; background:var(--navy); display:flex; align-items:center; justify-content:center; font-size:24px; margin-bottom:20px; clip-path:polygon(50% 0%,100% 25%,100% 75%,50% 100%,0% 75%,0% 25%); }
.step-title { font-family:'Barlow Condensed',sans-serif; font-size:22px; font-weight:800; color:var(--navy); letter-spacing:1.5px; text-transform:uppercase; margin-bottom:12px; }
.step-desc { color:var(--gray); font-size:14px; line-height:1.7; margin-bottom:18px; }
.step-list { list-style:none; }
.step-list li { font-size:13px; color:#444; padding:6px 0; display:flex; align-items:flex-start; gap:10px; border-bottom:1px solid #f2f2f2; }
.step-list li:last-child { border-bottom:none; }
.step-list li::before { content:'→'; color:var(--gold); font-weight:900; flex-shrink:0; }

/* SERVICES */
.services-section { background:var(--navy); padding:96px 48px; }
.services-inner { max-width:1160px; margin:0 auto; }
.services-grid { display:grid; grid-template-columns:repeat(3,1fr); gap:20px; margin-top:56px; }
.service-card { background:rgba(255,255,255,0.04); border:1px solid rgba(255,255,255,0.07); padding:32px; position:relative; overflow:hidden; transition:background .25s,border-color .25s,transform .25s; cursor:pointer; }
.service-card:hover { background:rgba(255,255,255,0.08); border-color:var(--gold); transform:translateY(-4px); }
.sc-bar { position:absolute; top:0; left:0; width:100%; height:3px; background:var(--gold); transform:scaleX(0); transform-origin:left; transition:transform .3s; }
.service-card:hover .sc-bar { transform:scaleX(1); }
.sc-icon { font-size:40px; margin-bottom:18px; display:block; line-height:1; }
.sc-name { font-family:'Barlow Condensed',sans-serif; font-size:21px; font-weight:800; color:var(--white); letter-spacing:1.5px; text-transform:uppercase; margin-bottom:10px; }
.sc-desc { color:#6888a8; font-size:13px; line-height:1.72; margin-bottom:16px; }
.sc-feats { list-style:none; margin-bottom:20px; }
.sc-feats li { font-size:12px; color:#4a6a88; padding:3px 0; display:flex; align-items:center; gap:8px; }
.sc-feats li::before { content:'✓'; color:var(--gold); font-weight:900; font-size:11px; flex-shrink:0; }
.sc-link { display:inline-flex; align-items:center; gap:6px; color:var(--gold); font-size:11px; font-weight:800; letter-spacing:2px; text-transform:uppercase; border-bottom:1px solid transparent; transition:border-color .2s; }
.service-card:hover .sc-link { border-bottom-color:var(--gold); }

/* WHY */
.why-section { padding:96px 48px; background:#fff; }
.why-inner { max-width:1160px; margin:0 auto; }
.why-grid { display:grid; grid-template-columns:1fr 1fr; gap:72px; margin-top:56px; align-items:start; }
.why-list { display:flex; flex-direction:column; }
.why-item { display:flex; gap:20px; padding:22px 0; border-bottom:1px solid var(--light-gray); align-items:flex-start; }
.why-item:first-child { border-top:1px solid var(--light-gray); }
.why-hex { flex-shrink:0; width:52px; height:52px; background:var(--navy); clip-path:polygon(50% 0%,100% 25%,100% 75%,50% 100%,0% 75%,0% 25%); display:flex; align-items:center; justify-content:center; font-size:22px; }
.why-text h4 { font-family:'Barlow Condensed',sans-serif; font-size:18px; font-weight:800; text-transform:uppercase; letter-spacing:1px; color:var(--navy); margin-bottom:5px; }
.why-text p { font-size:13px; color:var(--gray); line-height:1.68; }

.why-right { display:flex; flex-direction:column; gap:20px; }
.why-card-main { background:var(--navy); padding:44px; border-left:5px solid var(--gold); }
.wcm-title { font-family:'Bebas Neue',sans-serif; font-size:46px; color:var(--white); letter-spacing:3px; line-height:1; margin-bottom:4px; }
.wcm-sub { color:var(--gold); font-size:10.5px; letter-spacing:4px; text-transform:uppercase; margin-bottom:28px; }
.wcm-badges { display:grid; grid-template-columns:1fr 1fr; gap:12px; }
.wcm-badge { background:rgba(200,150,42,0.1); border:1px solid rgba(200,150,42,0.22); padding:14px; display:flex; align-items:center; gap:10px; }
.wcm-badge span:first-child { font-size:22px; }
.wcm-badge span:last-child { font-size:10.5px; color:#8aaac8; font-weight:700; letter-spacing:1.5px; text-transform:uppercase; }
.fmcsa-card { background:var(--offwhite); border-left:4px solid var(--gold); padding:24px 28px; }
.fmcsa-card h4 { font-family:'Barlow Condensed',sans-serif; font-size:15px; font-weight:800; text-transform:uppercase; letter-spacing:2px; color:var(--navy); margin-bottom:12px; display:flex; align-items:center; gap:8px; }
.fmcsa-card p { font-size:12.5px; color:#555; line-height:1.72; }
.fmcsa-card p+p { margin-top:8px; }
.fmcsa-card strong { color:var(--navy); }

/* LEGAL */
.legal-section { background:var(--navy-mid); padding:72px 48px; border-top:3px solid var(--gold); }
.legal-inner { max-width:1160px; margin:0 auto; }
.legal-grid { display:grid; grid-template-columns:repeat(3,1fr); gap:24px; margin-top:44px; }
.legal-card { background:rgba(255,255,255,0.04); border:1px solid rgba(255,255,255,0.07); padding:28px; }
.legal-card h4 { font-family:'Barlow Condensed',sans-serif; font-size:15px; font-weight:800; color:var(--gold); letter-spacing:2px; text-transform:uppercase; margin-bottom:12px; display:flex; align-items:center; gap:8px; }
.legal-card p { font-size:12.5px; color:#6888a8; line-height:1.72; }
.legal-card p+p { margin-top:8px; }
.legal-card strong { color:#8aaac8; }

/* REVIEWS */
.reviews-section { background:var(--offwhite); padding:96px 48px; }
.reviews-inner { max-width:1160px; margin:0 auto; }
.reviews-grid { display:grid; grid-template-columns:repeat(2,1fr); gap:24px; margin-top:56px; }
.review-card { background:var(--white); padding:36px; border-top:4px solid var(--gold); box-shadow:0 2px 24px rgba(0,0,0,0.06); display:flex; flex-direction:column; transition:transform .25s,box-shadow .25s; }
.review-card:hover { transform:translateY(-4px); box-shadow:0 16px 48px rgba(0,0,0,0.1); }
.review-stars { color:var(--gold); font-size:20px; letter-spacing:2px; margin-bottom:16px; }
.review-text { color:#3a3a3a; font-size:15px; line-height:1.8; font-style:italic; margin-bottom:24px; flex:1; }
.review-bar { width:40px; height:3px; background:var(--gold); margin-bottom:18px; }
.review-dealer-row { display:flex; align-items:center; gap:14px; }
.review-dealer-hex { width:46px; height:46px; background:var(--navy); flex-shrink:0; clip-path:polygon(50% 0%,100% 25%,100% 75%,50% 100%,0% 75%,0% 25%); display:flex; align-items:center; justify-content:center; font-size:20px; }
.review-dealer-meta { }
.review-dealer-name { font-family:'Barlow Condensed',sans-serif; font-size:17px; font-weight:800; color:var(--navy); letter-spacing:1px; text-transform:uppercase; }
.review-dealer-addr { font-size:12px; color:var(--gray); margin-top:2px; }
.review-platform-tag { font-size:10.5px; color:var(--gold); letter-spacing:2px; text-transform:uppercase; font-weight:800; margin-top:5px; display:flex; align-items:center; gap:5px; }

/* FAQ */
.faq-section { background:var(--navy); padding:96px 48px; }
.faq-inner { max-width:880px; margin:0 auto; }
.faq-list { margin-top:52px; }
.faq-item { border-bottom:1px solid rgba(255,255,255,0.07); }
.faq-q { width:100%; text-align:left; padding:22px 0; background:none; border:none; cursor:pointer; font-family:'Barlow Condensed',sans-serif; font-size:20px; font-weight:800; letter-spacing:.5px; text-transform:uppercase; color:var(--white); display:flex; justify-content:space-between; align-items:center; gap:16px; transition:color .2s; }
.faq-q:hover { color:var(--gold); }
.faq-icon { width:30px; height:30px; flex-shrink:0; background:rgba(200,150,42,0.12); border:1.5px solid rgba(200,150,42,0.35); display:flex; align-items:center; justify-content:center; color:var(--gold); font-size:20px; line-height:1; font-weight:300; transition:all .2s; }
.faq-q.open .faq-icon { background:var(--gold); color:var(--navy); }
.faq-a { display:none; padding:0 0 24px; color:#6888a8; font-size:14.5px; line-height:1.78; }
.faq-a.open { display:block; }

/* CTA */
.cta-section { background:linear-gradient(135deg,#c8962a 0%,#9a7018 100%); padding:76px 48px; text-align:center; position:relative; overflow:hidden; }
.cta-section::before { content:''; position:absolute; inset:0; background:url("data:image/svg+xml,%3Csvg width='40' height='40' viewBox='0 0 40 40' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='%23000' fill-opacity='0.06'%3E%3Cpath d='M20 20c0-11.046-8.954-20-20-20v20h20z'/%3E%3C/g%3E%3C/svg%3E"); }
.cta-inner { position:relative; z-index:1; }
.cta-section h2 { font-family:'Bebas Neue',sans-serif; font-size:66px; color:var(--navy); letter-spacing:4px; margin-bottom:14px; }
.cta-section p { color:rgba(7,17,31,0.6); font-size:18px; margin-bottom:38px; max-width:520px; margin-left:auto; margin-right:auto; }
.cta-btns { display:flex; gap:14px; justify-content:center; flex-wrap:wrap; }
.btn-cta-dark { background:var(--navy); color:var(--white); padding:18px 44px; font-weight:800; font-size:13px; letter-spacing:2.5px; text-transform:uppercase; border:none; cursor:pointer; display:inline-flex; align-items:center; gap:10px; clip-path:polygon(12px 0%,100% 0%,calc(100% - 12px) 100%,0% 100%); transition:background .2s,transform .15s; }
.btn-cta-dark:hover { background:#0c1d36; transform:translateY(-2px); }
.btn-cta-outline { background:transparent; color:var(--navy); padding:17px 40px; font-weight:800; font-size:13px; letter-spacing:2px; text-transform:uppercase; border:2.5px solid rgba(7,17,31,0.45); display:inline-flex; align-items:center; gap:8px; transition:background .2s; }
.btn-cta-outline:hover { background:rgba(7,17,31,0.1); }

/* FOOTER */
footer { background:#040b14; padding:72px 48px 32px; }
.footer-top { max-width:1160px; margin:0 auto; display:grid; grid-template-columns:2fr 1fr 1fr 1fr 1.8fr; gap:48px; padding-bottom:48px; border-bottom:1px solid #0d1e30; }
.footer-brand-desc { color:#3d5570; font-size:13px; line-height:1.78; margin-bottom:18px; }
.footer-logo { display:flex; align-items:center; gap:14px; margin-bottom:20px; }
.footer-logo svg { width:46px; height:46px; }
.footer-logo .logo-name { font-size:21px; }
.footer-logo .logo-sub { font-size:8px; }
.footer-addr { background:#080f1a; border-left:3px solid var(--gold); padding:14px 16px; }
.footer-addr strong { display:block; font-size:10px; letter-spacing:2px; text-transform:uppercase; color:#3d5570; margin-bottom:4px; }
.footer-addr p { font-size:12px; color:#2d4560; line-height:1.8; }
.fc h4 { font-family:'Barlow Condensed',sans-serif; font-size:12.5px; font-weight:800; letter-spacing:3px; text-transform:uppercase; color:var(--gold); margin-bottom:16px; padding-bottom:10px; border-bottom:1px solid #0d1e30; }
.fc ul { list-style:none; }
.fc ul li { margin-bottom:9px; }
.fc ul li a { color:#2d4560; font-size:13px; transition:color .2s; display:flex; align-items:center; gap:6px; }
.fc ul li a::before { content:'›'; color:var(--gold); font-size:15px; }
.fc ul li a:hover { color:var(--gold); }
.footer-contact-block { }
.footer-contact-block h4 { font-family:'Barlow Condensed',sans-serif; font-size:12.5px; font-weight:800; letter-spacing:3px; text-transform:uppercase; color:var(--gold); margin-bottom:16px; padding-bottom:10px; border-bottom:1px solid #0d1e30; }
.fci { display:flex; align-items:flex-start; gap:12px; margin-bottom:14px; }
.fci-icon { font-size:16px; flex-shrink:0; margin-top:1px; }
.fci-label { font-size:9.5px; font-weight:800; letter-spacing:2px; text-transform:uppercase; color:#2a3d52; margin-bottom:2px; }
.fci-val { font-size:13px; color:#4a6a88; }
.fci-val a { color:#4a6a88; transition:color .2s; }
.fci-val a:hover { color:var(--gold); }
.footer-hours-box { background:#080f1a; border-left:3px solid var(--gold); padding:12px 14px; margin-top:16px; }
.footer-hours-box strong { font-size:9.5px; letter-spacing:2px; text-transform:uppercase; color:#2a3d52; display:block; margin-bottom:4px; }
.footer-hours-box p { font-size:12px; color:#2a3d52; }

.footer-bottom { max-width:1160px; margin:0 auto; padding-top:22px; display:flex; justify-content:space-between; align-items:center; flex-wrap:wrap; gap:14px; }
.footer-copy { color:#1a2e42; font-size:12px; }
.footer-legal-links { display:flex; gap:20px; flex-wrap:wrap; }
.footer-legal-links a { color:#1a2e42; font-size:12px; transition:color .2s; }
.footer-legal-links a:hover { color:var(--gold); }
.footer-fmcsa { max-width:1160px; margin:18px auto 0; padding-top:18px; border-top:1px solid #0d1e30; font-size:11px; color:#1a2e42; line-height:1.72; }
.footer-fmcsa strong { color:#2a3d52; }

/* RESPONSIVE */
@media(max-width:1100px){
  .hero-wrap { flex-direction:column; align-items:flex-start; }
  .hero-form { width:100%; max-width:520px; }
  .hero h1 { font-size:66px; }
  .services-grid { grid-template-columns:1fr 1fr; }
  .stats-bar { grid-template-columns:repeat(3,1fr); }
  .footer-top { grid-template-columns:1fr 1fr 1fr; }
}
@media(max-width:768px){
  .topbar { flex-direction:column; gap:6px; padding:10px 20px; text-align:center; }
  nav { padding:0 20px; height:68px; }
  .nav-links { display:none; }
  .logo-sep, .logo-reg { display:none; }
  .logo-name { font-size:19px; }
  .hero-wrap { padding:48px 20px; }
  .hero h1 { font-size:50px; }
  .steps-grid, .services-grid, .legal-grid { grid-template-columns:1fr; }
  .reviews-grid { grid-template-columns:1fr; }
  .why-grid { grid-template-columns:1fr; gap:40px; }
  .stats-bar { grid-template-columns:1fr 1fr; }
  .footer-top { grid-template-columns:1fr; }
  .section-title { font-size:40px; }
  .steps-section, .services-section, .why-section, .reviews-section, .faq-section, .legal-section { padding:64px 20px; }
  .cta-section { padding:52px 20px; }
  .cta-section h2 { font-size:46px; }
}
</style>
</head>
<body>

<!-- TOP BAR -->
<div class="topbar">
  <div>
    <span>🕐 Mon – Sun &nbsp;|&nbsp; 8:00 AM – 6:00 PM EST &nbsp;|&nbsp; 📍 Harrisonville, MO</span>
  </div>
  <div class="topbar-right">
    <a href="tel:+13152808565">📞 (315) 280-8565</a>
    <a href="mailto:admin@eminentventures.us">✉️ admin@eminentventures.us</a>
  </div>
</div>

<!-- NAV -->
<nav>
  <a href="#" class="logo">
    <div class="logo-emblem">
      <svg viewBox="0 0 58 58" fill="none" xmlns="http://www.w3.org/2000/svg">
        <polygon points="29,2 55,16 55,42 29,56 3,42 3,16" fill="#c8962a"/>
        <polygon points="29,9 49,20.5 49,37.5 29,49 9,37.5 9,20.5" fill="#07111f"/>
        <!-- Stylized road/transport lines -->
        <rect x="16" y="26" width="26" height="2.5" fill="#c8962a" rx="1"/>
        <rect x="16" y="30.5" width="20" height="2.5" fill="rgba(200,150,42,0.5)" rx="1"/>
        <!-- EV letters -->
        <text x="29" y="25" text-anchor="middle" font-family="Arial,sans-serif" font-size="11" font-weight="900" fill="#c8962a" letter-spacing="2">EV</text>
        <!-- Corner accents -->
        <line x1="3" y1="16" x2="9" y2="20.5" stroke="#e8b84b" stroke-width="1.5"/>
        <line x1="55" y1="16" x2="49" y2="20.5" stroke="#e8b84b" stroke-width="1.5"/>
        <line x1="3" y1="42" x2="9" y2="37.5" stroke="#e8b84b" stroke-width="1.5"/>
        <line x1="55" y1="42" x2="49" y2="37.5" stroke="#e8b84b" stroke-width="1.5"/>
        <line x1="29" y1="2" x2="29" y2="9" stroke="#e8b84b" stroke-width="1.5"/>
        <line x1="29" y1="49" x2="29" y2="56" stroke="#e8b84b" stroke-width="1.5"/>
      </svg>
    </div>
    <div class="logo-wordmark">
      <span class="logo-name">EMINENT VENTURES</span>
      <span class="logo-sub">Licensed Auto Transport Broker</span>
    </div>
    <div class="logo-sep"></div>
    <div class="logo-reg">
      <strong>FMCSA</strong>
      MC-XXXXXXX
    </div>
  </a>

  <ul class="nav-links">
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#services">Services</a></li>
    <li><a href="#reviews">Reviews</a></li>
    <li><a href="#legal">Legal</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>

  <div class="nav-actions">
    <a href="tel:+13152808565" class="nav-call">📞 (315) 280-8565</a>
    <a href="#quote" class="btn-nav-quote">Get Free Quote</a>
  </div>
</nav>

<!-- HERO -->
<section class="hero" id="home">
  <div class="hero-grid-bg"></div>
  <div class="hero-glow"></div>
  <div class="hero-glow2"></div>
  <div class="hero-stripe"></div>

  <div class="hero-wrap">
    <div class="hero-content">
      <div class="hero-badge">🏆 FMCSA-Licensed Broker &nbsp;·&nbsp; 48 Contiguous States</div>
      <h1>TRUSTED <em>AUTO TRANSPORT</em> NATIONWIDE</h1>
      <p class="hero-sub">Eminent Ventures connects you with fully licensed, insured motor carriers across 48 states. No deposit upfront. No hidden fees. Your vehicle handled with precision — from Harrisonville, MO to anywhere in the country.</p>
      <div class="hero-btns">
        <a href="#quote" class="btn-hero">🚗 Get Instant Quote</a>
        <a href="tel:+13152808565" class="btn-hero-outline">📞 Call (315) 280-8565</a>
      </div>
      <div class="trust-strip">
        <div class="trust-item"><span>🛡️</span><span>No Deposit</span></div>
        <div class="trust-item"><span>🔒</span><span>7-Day Price Lock</span></div>
        <div class="trust-item"><span>📍</span><span>48 States</span></div>
        <div class="trust-item"><span>⭐</span><span>Top Rated</span></div>
        <div class="trust-item"><span>📋</span><span>FMCSA Licensed</span></div>
      </div>
    </div>

    <!-- QUOTE FORM -->
    <div class="hero-form" id="quote">
      <div class="hf-head">
        <div class="hf-title">GET YOUR<br>FREE QUOTE</div>
        <div class="hf-sub">Instant pricing · No obligation</div>
        <div class="hf-lock">✅ 7-Day Price Lock Guaranteed</div>
      </div>

      <div id="quoteForm">
        <div class="hf-g"><label>📍 From (City, State or ZIP)</label><input type="text" id="qFrom" placeholder="e.g. Kansas City, MO"></div>
        <div class="hf-g"><label>📍 To (City, State or ZIP)</label><input type="text" id="qTo" placeholder="e.g. Los Angeles, CA"></div>
        <div class="hf-g">
          <label>Transport Type</label>
          <div class="hf-toggle">
            <button class="hf-tb active" onclick="toggleType(this)">🚛 Open</button>
            <button class="hf-tb" onclick="toggleType(this)">🔐 Enclosed</button>
          </div>
        </div>
        <div class="hf-g"><label>📅 Preferred Pickup Date</label><input type="date" id="qDate"></div>
        <div class="hf-g"><label>🚗 Vehicle (Year, Make, Model)</label><input type="text" id="qVehicle" placeholder="e.g. 2022 Toyota Camry"></div>
        <div class="hf-g"><label>📞 Your Phone Number</label><input type="tel" id="qPhone" placeholder="(555) 000-0000"></div>
        <div class="hf-g"><label>✉️ Your Email Address</label><input type="email" id="qEmail" placeholder="you@email.com"></div>
        <button class="hf-submit" onclick="submitQuote()">⚡ Send My Quote Request</button>
        <div class="hf-fine">By submitting you agree to our <a href="#legal">Terms &amp; Conditions</a> and consent to be contacted by call, SMS, or email.</div>
      </div>

      <div class="form-success" id="formSuccess">
        <div class="fs-icon">✅</div>
        <div class="fs-title">QUOTE SENT!</div>
        <div class="fs-text">A specialist will contact you shortly.<br>A copy was sent to <strong id="confirmedEmail"></strong><br><br>Or call us now: <strong><a href="tel:+13152808565" style="color:var(--gold)">(315) 280-8565</a></strong></div>
      </div>
    </div>
  </div>
</section>

<!-- STATS -->
<div class="stats-bar">
  <div class="stat-item"><div class="stat-num">48</div><div class="stat-label">States Covered</div></div>
  <div class="stat-item"><div class="stat-num">5,000+</div><div class="stat-label">Vehicles Shipped</div></div>
  <div class="stat-item"><div class="stat-num">4.9 ★</div><div class="stat-label">Avg. Rating</div></div>
  <div class="stat-item"><div class="stat-num">7-Day</div><div class="stat-label">Price Lock</div></div>
  <div class="stat-item"><div class="stat-num">$0</div><div class="stat-label">Deposit Required</div></div>
</div>

<!-- STEPS -->
<section class="steps-section" id="about">
  <div class="steps-inner">
    <div class="section-tag">How It Works</div>
    <div class="section-title">3 STEPS TO SHIP YOUR VEHICLE</div>
    <div class="section-sub">From quote to delivery — Eminent Ventures manages every detail, every step of the way.</div>
    <div class="steps-grid">
      <div class="step-card">
        <div class="step-bg-num">01</div>
        <div class="step-icon-box">📋</div>
        <div class="step-title">Get a Quote &amp; Book</div>
        <div class="step-desc">Share your route, vehicle details, and preferred dates. We lock your rate for a full 7 days — zero deposit until a carrier is confirmed.</div>
        <ul class="step-list">
          <li>Instant online or phone quote</li>
          <li>7-day guaranteed price lock</li>
          <li>No deposit until carrier assigned</li>
          <li>Confirm your booking in minutes</li>
        </ul>
      </div>
      <div class="step-card">
        <div class="step-bg-num">02</div>
        <div class="step-icon-box">🚛</div>
        <div class="step-title">Pickup &amp; Inspection</div>
        <div class="step-desc">A licensed, insured carrier arrives at your location. You and the driver jointly inspect and document the vehicle's condition before loading.</div>
        <ul class="step-list">
          <li>Joint vehicle inspection at pickup</li>
          <li>All conditions documented on BOL</li>
          <li>Both parties sign Bill of Lading</li>
          <li>Real-time tracking begins</li>
        </ul>
      </div>
      <div class="step-card">
        <div class="step-bg-num">03</div>
        <div class="step-icon-box">✅</div>
        <div class="step-title">Delivery &amp; Sign-Off</div>
        <div class="step-desc">Your vehicle arrives at its destination. Inspect it against the original Bill of Lading, confirm condition, sign delivery, and choose your payment method.</div>
        <ul class="step-list">
          <li>Final joint vehicle inspection</li>
          <li>Compare to original Bill of Lading</li>
          <li>Sign delivery confirmation</li>
          <li>Flexible payment on delivery</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- SERVICES -->
<section class="services-section" id="services">
  <div class="services-inner">
    <div class="section-tag">What We Offer</div>
    <div class="section-title light">OUR TRANSPORT SERVICES</div>
    <div class="section-sub light">Professional vehicle shipping across all 48 contiguous states — every route, every vehicle type.</div>
    <div class="services-grid">

      <div class="service-card">
        <div class="sc-bar"></div>
        <span class="sc-icon">🚗</span>
        <div class="sc-name">Open Auto Shipping</div>
        <div class="sc-desc">Our most popular and cost-effective option. Your vehicle travels on a multi-car open carrier — safe, widely available, and built for any budget.</div>
        <ul class="sc-feats">
          <li>Most affordable transport option</li>
          <li>Available on all major routes</li>
          <li>Fully licensed &amp; insured carriers</li>
          <li>Ideal for standard passenger vehicles</li>
        </ul>
        <a href="tel:+13152808565" class="sc-link">📞 Call for Quote →</a>
      </div>

      <div class="service-card">
        <div class="sc-bar"></div>
        <span class="sc-icon">🏎️</span>
        <div class="sc-name">Enclosed Auto Shipping</div>
        <div class="sc-desc">Maximum protection for luxury, classic, or high-value vehicles. Full weather and road-debris shielding inside a private enclosed trailer.</div>
        <ul class="sc-feats">
          <li>Best for luxury &amp; exotic vehicles</li>
          <li>Complete weather protection</li>
          <li>Enhanced security throughout transit</li>
          <li>White-glove carrier handling</li>
        </ul>
        <a href="tel:+13152808565" class="sc-link">📞 Call for Quote →</a>
      </div>

      <div class="service-card">
        <div class="sc-bar"></div>
        <span class="sc-icon">🏠</span>
        <div class="sc-name">Door-to-Door Shipping</div>
        <div class="sc-desc">The ultimate convenience — we arrange pickup and delivery directly at your specified address. No terminals, no extra trips on your end.</div>
        <ul class="sc-feats">
          <li>Pickup at your exact location</li>
          <li>No terminal drop-off needed</li>
          <li>Minimal handling of your vehicle</li>
          <li>Maximum convenience &amp; peace of mind</li>
        </ul>
        <a href="tel:+13152808565" class="sc-link">📞 Call for Quote →</a>
      </div>

      <div class="service-card">
        <div class="sc-bar"></div>
        <span class="sc-icon">🤝</span>
        <div class="sc-name">Driveaway Transport</div>
        <div class="sc-desc">A professional, licensed driver takes the wheel and delivers your vehicle directly — flexible scheduling and often faster for select routes.</div>
        <ul class="sc-feats">
          <li>Cost-effective alternative option</li>
          <li>Often faster for certain routes</li>
          <li>Flexible, personalized scheduling</li>
          <li>Fully vetted professional drivers</li>
        </ul>
        <a href="tel:+13152808565" class="sc-link">📞 Call for Quote →</a>
      </div>

      <div class="service-card">
        <div class="sc-bar"></div>
        <span class="sc-icon">🏢</span>
        <div class="sc-name">Dealer &amp; Fleet Transport</div>
        <div class="sc-desc">Moving dealership inventory or a company fleet? We coordinate multi-vehicle bulk transport with volume pricing and a dedicated account manager.</div>
        <ul class="sc-feats">
          <li>Fleet &amp; dealer inventory moves</li>
          <li>Volume pricing available</li>
          <li>Coordinated multi-vehicle scheduling</li>
          <li>Dedicated account support team</li>
        </ul>
        <a href="tel:+13152808565" class="sc-link">📞 Call for Quote →</a>
      </div>

      <div class="service-card">
        <div class="sc-bar"></div>
        <span class="sc-icon">⚙️</span>
        <div class="sc-name">Inoperable Vehicle Transport</div>
        <div class="sc-desc">Vehicle won't start or run? We arrange specialized carriers equipped with winch-out capability to safely load and transport non-running vehicles.</div>
        <ul class="sc-feats">
          <li>Non-running &amp; damaged vehicles</li>
          <li>Winch-out loading capability</li>
          <li>Fully covered throughout transit</li>
          <li>No special prep required by owner</li>
        </ul>
        <a href="tel:+13152808565" class="sc-link">📞 Call for Quote →</a>
      </div>

    </div>
  </div>
</section>

<!-- WHY CHOOSE -->
<section class="why-section">
  <div class="why-inner">
    <div class="section-tag">Why Choose Us</div>
    <div class="section-title">5 REASONS TO TRUST EMINENT VENTURES</div>
    <div class="section-sub">We don't just book a truck — we manage your entire vehicle transport experience from first contact to final sign-off.</div>
    <div class="why-grid">
      <div class="why-list">
        <div class="why-item">
          <div class="why-hex">🛡️</div>
          <div class="why-text">
            <h4>Vetted, Licensed Carriers Only</h4>
            <p>We partner exclusively with FMCSA-authorized motor carriers who maintain active cargo insurance. Every carrier is verified before your vehicle is dispatched.</p>
          </div>
        </div>
        <div class="why-item">
          <div class="why-hex">💰</div>
          <div class="why-text">
            <h4>Zero Deposit Required Upfront</h4>
            <p>Reputable brokers never demand money before a carrier is secured. We only collect payment after you've approved the carrier and agreed to all terms.</p>
          </div>
        </div>
        <div class="why-item">
          <div class="why-hex">🔒</div>
          <div class="why-text">
            <h4>7-Day Price Lock Guarantee</h4>
            <p>Your quoted rate is locked for a full week. No bait-and-switch pricing, no last-minute hikes. The price you see is the exact price you pay.</p>
          </div>
        </div>
        <div class="why-item">
          <div class="why-hex">📍</div>
          <div class="why-text">
            <h4>Full Real-Time Shipment Tracking</h4>
            <p>Once dispatched, you receive complete tracking details. Monitor your vehicle's journey and know exactly when to expect delivery at every stage.</p>
          </div>
        </div>
        <div class="why-item">
          <div class="why-hex">🤝</div>
          <div class="why-text">
            <h4>Dedicated Human Support — 7 Days</h4>
            <p>No bots, no outsourced call centers. A dedicated team member handles your shipment from quote through delivery. Reachable Mon–Sun, 8am–6pm EST.</p>
          </div>
        </div>
      </div>

      <div class="why-right">
        <div class="why-card-main">
          <div class="wcm-title">EMINENT<br>VENTURES</div>
          <div class="wcm-sub">Harrisonville, MO · Nationwide</div>
          <div class="wcm-badges">
            <div class="wcm-badge"><span>🛡️</span><span>Fully Insured</span></div>
            <div class="wcm-badge"><span>📋</span><span>FMCSA Licensed</span></div>
            <div class="wcm-badge"><span>💰</span><span>No Deposit</span></div>
            <div class="wcm-badge"><span>⭐</span><span>Top Rated</span></div>
            <div class="wcm-badge"><span>📍</span><span>48 States</span></div>
            <div class="wcm-badge"><span>🔒</span><span>7-Day Price Lock</span></div>
          </div>
        </div>
        <div class="fmcsa-card">
          <h4>⚖️ FMCSA Broker Disclosure</h4>
          <p>Eminent Ventures operates as a <strong>licensed property broker</strong> registered with the Federal Motor Carrier Safety Administration (FMCSA). We arrange vehicle transport by contracting with licensed, insured motor carriers on your behalf.</p>
          <p>As a broker, we do <strong>not transport vehicles ourselves</strong>. All shipments are performed by independent FMCSA-authorized carriers. You have the right to receive the carrier's name, MC number, and insurance certificate before dispatch.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- LEGAL / FMCSA -->
<section class="legal-section" id="legal">
  <div class="legal-inner">
    <div class="section-tag" style="color:var(--gold)">⚖️ Legal &amp; Regulatory</div>
    <div class="section-title light">BROKER DISCLOSURES &amp; YOUR RIGHTS</div>
    <div class="section-sub light">As an FMCSA-registered property broker, Eminent Ventures is required to provide the following disclosures under 49 CFR Part 371.</div>
    <div class="legal-grid">
      <div class="legal-card">
        <h4>📋 Broker vs. Carrier</h4>
        <p>Eminent Ventures is a <strong>licensed freight broker</strong>, not a motor carrier. We arrange transportation between you (the shipper) and a licensed motor carrier. The carrier — not Eminent Ventures — physically transports your vehicle.</p>
        <p>You have the right to know the identity of the carrier assigned to your shipment, including their MC number, DOT number, and insurance certificate, before pickup.</p>
      </div>
      <div class="legal-card">
        <h4>🛡️ Cargo Insurance</h4>
        <p>All carriers we work with are required by FMCSA regulations to maintain <strong>minimum cargo insurance</strong> covering your vehicle in transit. We verify active, compliant insurance before dispatching any carrier to your location.</p>
        <p>Supplemental gap protection may be available. Ask our team about additional coverage options before booking, particularly for high-value or specialty vehicles.</p>
      </div>
      <div class="legal-card">
        <h4>📄 Bill of Lading Rights</h4>
        <p>A <strong>Bill of Lading (BOL)</strong> is the official shipping contract between you and the carrier. At pickup, you and the driver jointly inspect and document the vehicle's condition. The BOL must be signed by both parties before loading.</p>
        <p>At delivery, compare the vehicle's condition against the original BOL. Any new damage must be noted on the delivery BOL before the driver departs — this is essential to any future insurance claim.</p>
      </div>
      <div class="legal-card">
        <h4>💳 Payment &amp; Broker Fees</h4>
        <p>Eminent Ventures does <strong>not require any deposit</strong> before a carrier is confirmed. Our broker fee is transparently included in your total quoted price. The carrier's balance is typically collected upon delivery by the carrier directly.</p>
        <p>Beware of any broker demanding large deposits before carrier assignment. Under FMCSA rules, all fees must be disclosed in writing before you commit to a shipment.</p>
      </div>
      <div class="legal-card">
        <h4>📜 Your Shipper Rights</h4>
        <p>Under federal regulations you have the right to: receive written shipment confirmation, know your assigned carrier's full credentials, inspect your vehicle at pickup and delivery, and file a cargo claim for any damage that occurs in transit.</p>
        <p>Cargo claims must be filed in writing directly with the <strong>motor carrier</strong> (not the broker) within 9 months of delivery per 49 U.S.C. § 14706.</p>
      </div>
      <div class="legal-card">
        <h4>🗺️ Geographic Coverage</h4>
        <p>Eminent Ventures arranges transport across the <strong>48 contiguous United States</strong>. We do not currently arrange shipments to or from Alaska or Hawaii.</p>
        <p>All transport is subject to carrier availability on your chosen route and dates. We will notify you promptly of any scheduling constraints and work to find an alternative solution for your shipment.</p>
      </div>
    </div>
  </div>
</section>

<!-- REVIEWS -->
<section class="reviews-section" id="reviews">
  <div class="reviews-inner">
    <div class="section-tag">Verified Dealership Reviews</div>
    <div class="section-title">TRUSTED BY DEALERSHIPS NATIONWIDE</div>
    <div class="section-sub">Real reviews from real auto dealers who rely on Eminent Ventures for consistent, professional vehicle transport across the country.</div>
    <div class="reviews-grid">

      <div class="review-card">
        <div class="review-stars">★ ★ ★ ★ ★</div>
        <div class="review-text">"We've used Eminent Ventures for transporting inventory from auctions all across the country. Every single shipment arrives on time and in perfect condition. Their communication is outstanding — we always know exactly where our vehicles are in transit. Couldn't ask for a more professional and reliable broker."</div>
        <div class="review-bar"></div>
        <div class="review-dealer-row">
          <div class="review-dealer-hex">🏢</div>
          <div class="review-dealer-meta">
            <div class="review-dealer-name">Shopi Cars Inc.</div>
            <div class="review-dealer-addr">📍 Canton, MA 02021</div>
            <div class="review-platform-tag">⭐ Google Review &nbsp;·&nbsp; Verified Dealer</div>
          </div>
        </div>
      </div>

      <div class="review-card">
        <div class="review-stars">★ ★ ★ ★ ★</div>
        <div class="review-text">"MX Motors has been partnering with Eminent Ventures for over a year now. Their pricing is completely transparent, no surprise fees at any stage, and the vehicles always arrive exactly as documented on the Bill of Lading. They treat our inventory like it's their own. Highly recommended for any dealer."</div>
        <div class="review-bar"></div>
        <div class="review-dealer-row">
          <div class="review-dealer-hex">🚗</div>
          <div class="review-dealer-meta">
            <div class="review-dealer-name">MX Motors</div>
            <div class="review-dealer-addr">📍 Ashland, MA 01721</div>
            <div class="review-platform-tag">⭐ Google Review &nbsp;·&nbsp; Verified Dealer</div>
          </div>
        </div>
      </div>

      <div class="review-card">
        <div class="review-stars">★ ★ ★ ★ ★</div>
        <div class="review-text">"Dream Motors ships vehicles regularly between Virginia and our out-of-state auction partners. Eminent Ventures has never let us down. The booking process is simple, the carriers are professional, and we have never had a damage claim in all our time working together. Five stars without any hesitation."</div>
        <div class="review-bar"></div>
        <div class="review-dealer-row">
          <div class="review-dealer-hex">🏎️</div>
          <div class="review-dealer-meta">
            <div class="review-dealer-name">Dream Motors</div>
            <div class="review-dealer-addr">📍 Fredericksburg, VA 22401</div>
            <div class="review-platform-tag">⭐ Google Review &nbsp;·&nbsp; Verified Dealer</div>
          </div>
        </div>
      </div>

      <div class="review-card">
        <div class="review-stars">★ ★ ★ ★ ★</div>
        <div class="review-text">"We run a high-volume pre-owned lot and needed a transport broker we could actually rely on consistently. Eminent Ventures delivers every time. Fast quotes, honest pricing, and zero drama. The team is reachable seven days a week which matters enormously when you're moving vehicles on tight auction timelines."</div>
        <div class="review-bar"></div>
        <div class="review-dealer-row">
          <div class="review-dealer-hex">⭐</div>
          <div class="review-dealer-meta">
            <div class="review-dealer-name">Enjoy Auto Sales</div>
            <div class="review-dealer-addr">📍 Sacramento, CA 95814</div>
            <div class="review-platform-tag">⭐ Google Review &nbsp;·&nbsp; Verified Dealer</div>
          </div>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- FAQ -->
<section class="faq-section">
  <div class="faq-inner">
    <div class="section-tag" style="color:var(--gold)">Common Questions</div>
    <div class="section-title light">FREQUENTLY ASKED QUESTIONS</div>
    <div class="faq-list">
      <div class="faq-item">
        <button class="faq-q" onclick="toggleFaq(this)">How much does it cost to ship a car? <span class="faq-icon">+</span></button>
        <div class="faq-a">Costs vary based on distance, vehicle size, transport type (open vs enclosed), route demand, and your chosen dates. We provide an instant quote with a 7-day price lock and zero hidden fees. Call us at (315) 280-8565 or use the online form above for a personalized, all-in rate.</div>
      </div>
      <div class="faq-item">
        <button class="faq-q" onclick="toggleFaq(this)">How long does it take to ship a car? <span class="faq-icon">+</span></button>
        <div class="faq-a">Transit times depend on your route. Short hauls under 500 miles typically take 1–2 days. Mid-range routes of 500–1,500 miles take 2–4 days. Cross-country shipments of 2,000+ miles can take 5–10 days. We provide an estimated delivery window at booking and you'll receive tracking updates throughout.</div>
      </div>
      <div class="faq-item">
        <button class="faq-q" onclick="toggleFaq(this)">Do I need to pay a deposit upfront? <span class="faq-icon">+</span></button>
        <div class="faq-a">No. Eminent Ventures does not require any deposit before a carrier is confirmed and approved by you. Our broker fee is included in your total quoted price. Payment to the carrier is typically collected upon successful delivery. Beware of brokers demanding large deposits — this is a major industry red flag.</div>
      </div>
      <div class="faq-item">
        <button class="faq-q" onclick="toggleFaq(this)">Is my vehicle insured during transport? <span class="faq-icon">+</span></button>
        <div class="faq-a">Yes. Every carrier we work with must carry active FMCSA-mandated cargo insurance. Before dispatch, you are entitled to the carrier's insurance certificate and MC number. For high-value or specialty vehicles, ask our team about supplemental gap protection that goes beyond the carrier's standard coverage.</div>
      </div>
      <div class="faq-item">
        <button class="faq-q" onclick="toggleFaq(this)">What is the difference between a broker and a carrier? <span class="faq-icon">+</span></button>
        <div class="faq-a">A broker (like Eminent Ventures) arranges transportation by matching shippers with licensed motor carriers. We handle all logistics, documentation, and coordination. A carrier physically transports the vehicle using their own trucks and operating authority. We are registered with the FMCSA as a property broker and fully disclose this relationship in writing.</div>
      </div>
      <div class="faq-item">
        <button class="faq-q" onclick="toggleFaq(this)">Which states do you service? <span class="faq-icon">+</span></button>
        <div class="faq-a">We arrange transport across all 48 contiguous United States. We do not currently service Alaska or Hawaii. Whether you are shipping coast-to-coast, regionally, or to a neighboring state, we can match you with the right carrier on your specific route.</div>
      </div>
      <div class="faq-item">
        <button class="faq-q" onclick="toggleFaq(this)">How do I prepare my car for shipping? <span class="faq-icon">+</span></button>
        <div class="faq-a">Remove all personal belongings from the vehicle. Clean it inside and out so existing condition is easy to document accurately. Keep the gas tank at roughly 1/4 full. Photograph the vehicle from all angles before pickup. Disable any toll transponders and alarm systems. Make sure the vehicle is in running condition unless you have arranged inoperable vehicle transport.</div>
      </div>
    </div>
  </div>
</section>

<!-- CTA BANNER -->
<section class="cta-section">
  <div class="cta-inner">
    <h2>READY TO SHIP YOUR VEHICLE?</h2>
    <p>Get your free quote in 60 seconds. 7-day price lock. Zero deposit. No hidden fees.</p>
    <div class="cta-btns">
      <a href="#quote" class="btn-cta-dark">🚗 Get Free Quote Online</a>
      <a href="tel:+13152808565" class="btn-cta-dark">📞 Call (315) 280-8565</a>
      <a href="mailto:admin@eminentventures.us" class="btn-cta-outline">✉️ Email Us</a>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer id="contact">
  <div class="footer-top">
    <div class="footer-brand">
      <div class="footer-logo">
        <svg viewBox="0 0 58 58" fill="none" xmlns="http://www.w3.org/2000/svg">
          <polygon points="29,2 55,16 55,42 29,56 3,42 3,16" fill="#c8962a"/>
          <polygon points="29,9 49,20.5 49,37.5 29,49 9,37.5 9,20.5" fill="#07111f"/>
          <rect x="16" y="26" width="26" height="2.5" fill="#c8962a" rx="1"/>
          <rect x="16" y="30.5" width="20" height="2.5" fill="rgba(200,150,42,0.5)" rx="1"/>
          <text x="29" y="25" text-anchor="middle" font-family="Arial,sans-serif" font-size="11" font-weight="900" fill="#c8962a" letter-spacing="2">EV</text>
        </svg>
        <div class="logo-wordmark">
          <span class="logo-name" style="font-size:21px">EMINENT VENTURES</span>
          <span class="logo-sub" style="font-size:8px">Licensed Auto Transport Broker</span>
        </div>
      </div>
      <p class="footer-brand-desc">Eminent Ventures is an FMCSA-licensed property broker connecting customers with vetted, insured motor carriers across all 48 contiguous states. Based in Harrisonville, MO — serving the entire nation.</p>
      <div class="footer-addr">
        <strong>Headquarters</strong>
        <p>117 S Lexington St, Suite 100<br>Harrisonville, MO 64701-2443<br>Mon – Sun &nbsp;·&nbsp; 8:00 AM – 6:00 PM EST</p>
      </div>
    </div>

    <div class="fc">
      <h4>Company</h4>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#services">Our Services</a></li>
        <li><a href="#reviews">Reviews</a></li>
        <li><a href="#contact">Contact</a></li>
        <li><a href="#quote">Get a Quote</a></li>
      </ul>
    </div>

    <div class="fc">
      <h4>Services</h4>
      <ul>
        <li><a href="#services">Open Auto Shipping</a></li>
        <li><a href="#services">Enclosed Shipping</a></li>
        <li><a href="#services">Door-to-Door</a></li>
        <li><a href="#services">Driveaway Transport</a></li>
        <li><a href="#services">Dealer &amp; Fleet</a></li>
        <li><a href="#services">Inoperable Vehicles</a></li>
      </ul>
    </div>

    <div class="fc">
      <h4>Legal</h4>
      <ul>
        <li><a href="#legal">Broker Disclosure</a></li>
        <li><a href="#legal">Your Rights</a></li>
        <li><a href="#legal">Bill of Lading Info</a></li>
        <li><a href="#">Privacy Policy</a></li>
        <li><a href="#">Terms of Service</a></li>
        <li><a href="#">Terms &amp; Conditions</a></li>
      </ul>
    </div>

    <div class="footer-contact-block">
      <h4>Contact Us</h4>
      <div class="fci">
        <span class="fci-icon">📞</span>
        <div>
          <div class="fci-label">Phone</div>
          <div class="fci-val"><a href="tel:+13152808565">(315) 280-8565</a></div>
        </div>
      </div>
      <div class="fci">
        <span class="fci-icon">✉️</span>
        <div>
          <div class="fci-label">Email</div>
          <div class="fci-val"><a href="mailto:admin@eminentventures.us">admin@eminentventures.us</a></div>
        </div>
      </div>
      <div class="fci">
        <span class="fci-icon">📍</span>
        <div>
          <div class="fci-label">Address</div>
          <div class="fci-val">117 S Lexington St, Ste 100<br>Harrisonville, MO 64701-2443</div>
        </div>
      </div>
      <div class="footer-hours-box">
        <strong>Business Hours</strong>
        <p>Monday – Sunday<br>8:00 AM – 6:00 PM Eastern Time</p>
      </div>
    </div>
  </div>

  <div class="footer-bottom">
    <div class="footer-copy">© 2026 Eminent Ventures Auto Transport. All Rights Reserved.</div>
    <div class="footer-legal-links">
      <a href="#">Privacy Policy</a>
      <a href="#">Terms of Service</a>
      <a href="#legal">Broker Disclosure</a>
      <a href="#">Sitemap</a>
    </div>
  </div>

  <div class="footer-fmcsa">
    <strong>FMCSA Broker Disclosure:</strong> Eminent Ventures operates as a licensed property broker (MC# XXXXXXX) registered with the U.S. Department of Transportation Federal Motor Carrier Safety Administration. We are not a motor carrier and do not transport vehicles. All shipments are arranged with independent, FMCSA-authorized motor carriers who maintain their own operating authority and cargo insurance. Carrier information including MC number and insurance certificate will be provided prior to pickup. Cargo claims must be filed directly with the motor carrier per 49 U.S.C. § 14706 within 9 months of delivery. Service available in 48 contiguous states only. Alaska and Hawaii are excluded.
  </div>
</footer>

<script>
// Toggle open/enclosed
function toggleType(btn) {
  btn.parentElement.querySelectorAll('button').forEach(b => b.classList.remove('active'));
  btn.classList.add('active');
}

// FAQ accordion
function toggleFaq(btn) {
  const answer = btn.nextElementSibling;
  const icon = btn.querySelector('.faq-icon');
  const isOpen = btn.classList.contains('open');
  document.querySelectorAll('.faq-q').forEach(q => {
    q.classList.remove('open');
    if (q.nextElementSibling) q.nextElementSibling.classList.remove('open');
    if (q.querySelector('.faq-icon')) q.querySelector('.faq-icon').textContent = '+';
  });
  if (!isOpen) {
    btn.classList.add('open');
    answer.classList.add('open');
    icon.textContent = '−';
  }
}

// Quote form submission via mailto
function submitQuote() {
  const from    = document.getElementById('qFrom').value.trim();
  const to      = document.getElementById('qTo').value.trim();
  const date    = document.getElementById('qDate').value;
  const vehicle = document.getElementById('qVehicle').value.trim();
  const phone   = document.getElementById('qPhone').value.trim();
  const email   = document.getElementById('qEmail').value.trim();
  const type    = document.querySelector('.hf-tb.active')?.textContent.replace(/[^\w ]/g,'').trim() || 'Open';

  // Highlight missing fields
  let valid = true;
  const fields = { qFrom:from, qTo:to, qVehicle:vehicle, qPhone:phone, qEmail:email };
  Object.entries(fields).forEach(([id, val]) => {
    const el = document.getElementById(id);
    if (!val || (id === 'qEmail' && !val.includes('@'))) {
      el.style.borderColor = '#e74c3c'; valid = false;
    } else {
      el.style.borderColor = '';
    }
  });
  if (!valid) return;

  // Build mailto
  const subject = encodeURIComponent('New Auto Transport Quote — Eminent Ventures');
  const body = encodeURIComponent(
    'NEW QUOTE REQUEST\n' +
    '=====================================\n\n' +
    'From:            ' + from + '\n' +
    'To:              ' + to + '\n' +
    'Transport Type:  ' + type + '\n' +
    'Pickup Date:     ' + (date || 'Flexible') + '\n' +
    'Vehicle:         ' + vehicle + '\n' +
    'Customer Phone:  ' + phone + '\n' +
    'Customer Email:  ' + email + '\n\n' +
    '=====================================\n' +
    'Submitted via eminentventures.us'
  );
  window.location.href = 'mailto:admin@eminentventures.us?subject=' + subject + '&body=' + body;

  // Show success state
  document.getElementById('confirmedEmail').textContent = email;
  document.getElementById('quoteForm').style.display = 'none';
  document.getElementById('formSuccess').classList.add('show');
}

// Smooth scroll
document.querySelectorAll('a[href^="#"]').forEach(a => {
  a.addEventListener('click', e => {
    const href = a.getAttribute('href');
    if (href === '#') return;
    const target = document.querySelector(href);
    if (target) { e.preventDefault(); target.scrollIntoView({ behavior:'smooth', block:'start' }); }
  });
});
</script>
</body>
</html>
