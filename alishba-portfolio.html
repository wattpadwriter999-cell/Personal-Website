<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Alishba Al Nadeem — Freelancer & Builder</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=DM+Mono:wght@300;400&family=Playfair+Display:ital,wght@1,400;1,700&display=swap" rel="stylesheet"/>
<style>
  :root {
    --ink: #0e0c0a;
    --paper: #f5f0e8;
    --cream: #ede7d9;
    --sepia: #c9b99a;
    --rust: #8b3a2a;
    --gold: #b8942a;
    --muted: #6b6050;
    --faint: #d4cbbf;
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--paper);
    color: var(--ink);
    font-family: 'DM Mono', monospace;
    font-size: 13px;
    line-height: 1.8;
    cursor: none;
    overflow-x: hidden;
  }

  /* Custom cursor */
  .cursor {
    width: 8px; height: 8px;
    background: var(--rust);
    border-radius: 50%;
    position: fixed;
    top: 0; left: 0;
    pointer-events: none;
    z-index: 9999;
    transition: transform 0.15s ease;
  }
  .cursor-ring {
    width: 28px; height: 28px;
    border: 1px solid var(--rust);
    border-radius: 50%;
    position: fixed;
    top: 0; left: 0;
    pointer-events: none;
    z-index: 9998;
    transition: all 0.3s ease;
    opacity: 0.5;
  }

  /* Grain overlay */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 512 512' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.04'/%3E%3C/svg%3E");
    pointer-events: none;
    z-index: 9997;
    opacity: 0.4;
  }

  /* NAV */
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 100;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 48px;
    background: rgba(245,240,232,0.85);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid var(--faint);
  }

  .nav-logo {
    font-family: 'Cormorant Garamond', serif;
    font-size: 18px;
    font-weight: 300;
    letter-spacing: 0.15em;
    color: var(--ink);
    text-decoration: none;
  }
  .nav-logo span { color: var(--rust); }

  .nav-links {
    display: flex;
    gap: 36px;
    list-style: none;
  }
  .nav-links a {
    text-decoration: none;
    color: var(--muted);
    font-size: 11px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    transition: color 0.2s;
  }
  .nav-links a:hover { color: var(--rust); }

  /* HERO */
  .hero {
    min-height: 100vh;
    display: grid;
    grid-template-columns: 1fr 1fr;
    padding-top: 80px;
    position: relative;
    overflow: hidden;
  }

  .hero-left {
    padding: 80px 48px 80px 48px;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .hero-eyebrow {
    font-size: 10px;
    letter-spacing: 0.25em;
    text-transform: uppercase;
    color: var(--rust);
    margin-bottom: 24px;
    opacity: 0;
    animation: fadeUp 0.8s ease 0.2s forwards;
  }

  .hero-name {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(52px, 6vw, 88px);
    font-weight: 300;
    line-height: 1.05;
    letter-spacing: -0.01em;
    margin-bottom: 8px;
    opacity: 0;
    animation: fadeUp 0.8s ease 0.35s forwards;
  }

  .hero-name em {
    font-style: italic;
    color: var(--rust);
    font-weight: 400;
  }

  .hero-title {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(14px, 1.8vw, 22px);
    font-weight: 300;
    color: var(--muted);
    font-style: italic;
    margin-bottom: 40px;
    opacity: 0;
    animation: fadeUp 0.8s ease 0.5s forwards;
  }

  .hero-desc {
    max-width: 420px;
    font-size: 12.5px;
    line-height: 1.9;
    color: var(--muted);
    margin-bottom: 48px;
    opacity: 0;
    animation: fadeUp 0.8s ease 0.65s forwards;
  }

  .hero-cta {
    display: flex;
    gap: 16px;
    opacity: 0;
    animation: fadeUp 0.8s ease 0.8s forwards;
  }

  .btn-primary {
    display: inline-block;
    padding: 14px 32px;
    background: var(--ink);
    color: var(--paper);
    text-decoration: none;
    font-size: 11px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    transition: all 0.25s ease;
    border: 1px solid var(--ink);
  }
  .btn-primary:hover {
    background: var(--rust);
    border-color: var(--rust);
  }

  .btn-secondary {
    display: inline-block;
    padding: 14px 32px;
    background: transparent;
    color: var(--ink);
    text-decoration: none;
    font-size: 11px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    border: 1px solid var(--faint);
    transition: all 0.25s ease;
  }
  .btn-secondary:hover {
    border-color: var(--ink);
  }

  .hero-right {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
  }

  .hero-visual {
    width: 100%;
    height: 100%;
    background: var(--cream);
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
  }

  .hero-visual::before {
    content: '';
    position: absolute;
    inset: 0;
    background: 
      radial-gradient(ellipse at 30% 30%, rgba(139,58,42,0.08) 0%, transparent 60%),
      radial-gradient(ellipse at 70% 70%, rgba(184,148,42,0.06) 0%, transparent 60%);
  }

  .hero-monogram {
    font-family: 'Playfair Display', serif;
    font-size: 200px;
    font-style: italic;
    font-weight: 700;
    color: transparent;
    -webkit-text-stroke: 1px rgba(139,58,42,0.15);
    line-height: 1;
    user-select: none;
    opacity: 0;
    animation: fadeIn 1.2s ease 1s forwards;
  }

  .hero-stats {
    position: absolute;
    bottom: 48px;
    right: 48px;
    display: flex;
    flex-direction: column;
    gap: 20px;
    opacity: 0;
    animation: fadeUp 0.8s ease 1.1s forwards;
  }

  .stat {
    text-align: right;
  }
  .stat-num {
    font-family: 'Cormorant Garamond', serif;
    font-size: 32px;
    font-weight: 300;
    color: var(--ink);
    display: block;
    line-height: 1;
  }
  .stat-label {
    font-size: 10px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--muted);
  }

  .hero-scroll-hint {
    position: absolute;
    bottom: 32px;
    left: 48px;
    font-size: 10px;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--faint);
    display: flex;
    align-items: center;
    gap: 12px;
    opacity: 0;
    animation: fadeIn 1s ease 1.5s forwards;
  }
  .hero-scroll-hint::before {
    content: '';
    width: 40px;
    height: 1px;
    background: var(--faint);
  }

  /* MARQUEE */
  .marquee-strip {
    background: var(--ink);
    color: var(--paper);
    padding: 14px 0;
    overflow: hidden;
    white-space: nowrap;
    border-top: 1px solid var(--ink);
    border-bottom: 1px solid var(--ink);
  }

  .marquee-inner {
    display: inline-block;
    animation: marquee 22s linear infinite;
  }

  .marquee-inner span {
    font-size: 11px;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    margin: 0 32px;
    color: var(--sepia);
  }
  .marquee-inner span.accent { color: var(--paper); }

  @keyframes marquee {
    0% { transform: translateX(0); }
    100% { transform: translateX(-50%); }
  }

  /* SECTION SHARED */
  section {
    padding: 100px 48px;
    max-width: 1200px;
    margin: 0 auto;
  }

  .section-label {
    font-size: 10px;
    letter-spacing: 0.3em;
    text-transform: uppercase;
    color: var(--rust);
    margin-bottom: 16px;
    display: flex;
    align-items: center;
    gap: 16px;
  }
  .section-label::before {
    content: '';
    width: 32px;
    height: 1px;
    background: var(--rust);
  }

  .section-heading {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(32px, 4vw, 54px);
    font-weight: 300;
    line-height: 1.15;
    margin-bottom: 48px;
  }

  /* SERVICES */
  #services { max-width: none; padding: 100px 48px; }

  .services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 2px;
    background: var(--faint);
    border: 1px solid var(--faint);
  }

  .service-card {
    background: var(--paper);
    padding: 40px 36px;
    position: relative;
    transition: background 0.25s ease;
    overflow: hidden;
  }

  .service-card::before {
    content: '';
    position: absolute;
    bottom: 0; left: 0;
    width: 100%; height: 2px;
    background: var(--rust);
    transform: scaleX(0);
    transform-origin: left;
    transition: transform 0.3s ease;
  }

  .service-card:hover { background: var(--cream); }
  .service-card:hover::before { transform: scaleX(1); }

  .service-num {
    font-family: 'Cormorant Garamond', serif;
    font-size: 48px;
    font-weight: 300;
    color: var(--faint);
    line-height: 1;
    margin-bottom: 20px;
    transition: color 0.25s ease;
  }
  .service-card:hover .service-num { color: var(--sepia); }

  .service-title {
    font-family: 'Cormorant Garamond', serif;
    font-size: 22px;
    font-weight: 400;
    margin-bottom: 12px;
    line-height: 1.2;
  }

  .service-desc {
    font-size: 11.5px;
    color: var(--muted);
    line-height: 1.8;
    margin-bottom: 20px;
  }

  .service-price {
    font-size: 10px;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--rust);
  }

  /* ABOUT */
  #about {
    display: grid;
    grid-template-columns: 1fr 1.2fr;
    gap: 80px;
    align-items: center;
    max-width: 1200px;
  }

  .about-left { position: relative; }

  .about-portrait {
    width: 100%;
    aspect-ratio: 3/4;
    background: var(--cream);
    position: relative;
    overflow: hidden;
  }

  .about-portrait::after {
    content: 'A';
    position: absolute;
    inset: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: 'Playfair Display', serif;
    font-style: italic;
    font-size: 180px;
    color: rgba(139,58,42,0.08);
    font-weight: 700;
  }

  .about-accent-line {
    position: absolute;
    top: 24px; right: -24px;
    width: 1px;
    height: 60%;
    background: var(--rust);
    opacity: 0.3;
  }

  .about-right {}

  .about-body {
    font-size: 13px;
    line-height: 2;
    color: var(--muted);
    margin-bottom: 32px;
  }

  .about-body strong {
    color: var(--ink);
    font-weight: 400;
  }

  .about-langs {
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
    margin-bottom: 40px;
  }

  .lang-tag {
    font-size: 10px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    padding: 6px 14px;
    border: 1px solid var(--faint);
    color: var(--muted);
    transition: all 0.2s ease;
  }
  .lang-tag:hover {
    border-color: var(--rust);
    color: var(--rust);
  }

  .about-highlight {
    border-left: 2px solid var(--rust);
    padding-left: 20px;
    font-family: 'Cormorant Garamond', serif;
    font-style: italic;
    font-size: 18px;
    color: var(--ink);
    line-height: 1.6;
    margin-bottom: 40px;
  }

  /* WORK/PROJECTS */
  #work { max-width: none; padding: 100px 48px; background: var(--cream); }

  .work-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 24px;
  }

  .work-card {
    position: relative;
    overflow: hidden;
    background: var(--paper);
    border: 1px solid var(--faint);
    padding: 40px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }

  .work-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 20px 40px rgba(14,12,10,0.08);
  }

  .work-card-tag {
    font-size: 10px;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--rust);
    margin-bottom: 16px;
  }

  .work-card-title {
    font-family: 'Cormorant Garamond', serif;
    font-size: 26px;
    font-weight: 400;
    line-height: 1.2;
    margin-bottom: 12px;
  }

  .work-card-desc {
    font-size: 12px;
    color: var(--muted);
    line-height: 1.8;
  }

  .work-card-arrow {
    display: inline-block;
    margin-top: 24px;
    font-size: 11px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--ink);
    text-decoration: none;
    transition: color 0.2s;
  }
  .work-card-arrow::after {
    content: ' →';
  }
  .work-card-arrow:hover { color: var(--rust); }

  /* TESTIMONIALS */
  #testimonials { max-width: 900px; }

  .testimonial-stack {
    display: flex;
    flex-direction: column;
    gap: 32px;
  }

  .testimonial {
    border: 1px solid var(--faint);
    padding: 36px 40px;
    position: relative;
    background: var(--paper);
    transition: border-color 0.2s;
  }
  .testimonial:hover { border-color: var(--sepia); }

  .testimonial::before {
    content: '\201C';
    font-family: 'Cormorant Garamond', serif;
    font-size: 80px;
    color: var(--faint);
    line-height: 1;
    position: absolute;
    top: 12px; left: 24px;
    font-weight: 300;
  }

  .testimonial-text {
    font-family: 'Cormorant Garamond', serif;
    font-size: 18px;
    font-style: italic;
    line-height: 1.7;
    color: var(--ink);
    margin-bottom: 20px;
    padding-top: 20px;
  }

  .testimonial-author {
    font-size: 11px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--muted);
  }
  .testimonial-author span { color: var(--rust); }

  /* CONTACT */
  #contact {
    background: var(--ink);
    color: var(--paper);
    max-width: none;
    text-align: center;
    padding: 120px 48px;
  }

  #contact .section-label { justify-content: center; color: var(--sepia); }
  #contact .section-label::before { background: var(--sepia); }

  #contact .section-heading {
    color: var(--paper);
    font-size: clamp(36px, 5vw, 72px);
    margin-bottom: 24px;
  }

  .contact-sub {
    font-size: 13px;
    color: rgba(245,240,232,0.5);
    margin-bottom: 56px;
    max-width: 480px;
    margin-left: auto;
    margin-right: auto;
    line-height: 1.9;
  }

  .contact-links {
    display: flex;
    gap: 16px;
    justify-content: center;
    flex-wrap: wrap;
    margin-bottom: 64px;
  }

  .contact-link {
    padding: 14px 32px;
    border: 1px solid rgba(245,240,232,0.2);
    color: var(--paper);
    text-decoration: none;
    font-size: 11px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    transition: all 0.25s;
  }
  .contact-link:hover {
    background: var(--rust);
    border-color: var(--rust);
  }
  .contact-link.primary {
    background: var(--paper);
    color: var(--ink);
    border-color: var(--paper);
  }
  .contact-link.primary:hover {
    background: var(--rust);
    color: var(--paper);
    border-color: var(--rust);
  }

  .contact-divider {
    width: 1px;
    height: 60px;
    background: rgba(245,240,232,0.1);
    margin: 0 auto 40px;
  }

  .contact-email {
    font-family: 'Cormorant Garamond', serif;
    font-size: 22px;
    font-style: italic;
    color: var(--sepia);
    letter-spacing: 0.05em;
  }

  /* FOOTER */
  footer {
    background: var(--ink);
    border-top: 1px solid rgba(245,240,232,0.06);
    padding: 24px 48px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  footer span {
    font-size: 11px;
    color: rgba(245,240,232,0.25);
    letter-spacing: 0.1em;
  }

  /* ANIMATIONS */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
  }

  @keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
  }

  .reveal {
    opacity: 0;
    transform: translateY(24px);
    transition: opacity 0.7s ease, transform 0.7s ease;
  }
  .reveal.visible {
    opacity: 1;
    transform: none;
  }

  /* RESPONSIVE */
  @media (max-width: 768px) {
    nav { padding: 16px 24px; }
    .nav-links { display: none; }
    .hero { grid-template-columns: 1fr; }
    .hero-right { display: none; }
    .hero-left { padding: 40px 24px; }
    section { padding: 64px 24px; }
    #services { padding: 64px 24px; }
    #work { padding: 64px 24px; }
    #contact { padding: 80px 24px; }
    .work-grid { grid-template-columns: 1fr; }
    #about { grid-template-columns: 1fr; gap: 40px; }
    .about-portrait { display: none; }
    footer { padding: 20px 24px; flex-direction: column; gap: 8px; text-align: center; }
  }
</style>
</head>
<body>

<!-- Custom Cursor -->
<div class="cursor" id="cursor"></div>
<div class="cursor-ring" id="cursorRing"></div>

<!-- NAV -->
<nav>
  <a href="#" class="nav-logo">Alishba<span>.</span></a>
  <ul class="nav-links">
    <li><a href="#services">Services</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#work">Work</a></li>
    <li><a href="#contact">Hire Me</a></li>
  </ul>
</nav>

<!-- HERO -->
<div class="hero">
  <div class="hero-left">
    <p class="hero-eyebrow">Freelancer · Builder · Marketer</p>
    <h1 class="hero-name">Alishba<br><em>Al Nadeem</em></h1>
    <p class="hero-title">Digital Marketing, Content & Design</p>
    <p class="hero-desc">
      I build brands, grow audiences, and ship ideas — with 3+ years of freelance experience and a track record that includes launching an AI app used internationally. Based in Karachi. Available worldwide.
    </p>
    <div class="hero-cta">
      <a href="#contact" class="btn-primary">Hire Me</a>
      <a href="#services" class="btn-secondary">View Services</a>
    </div>
  </div>
  <div class="hero-right">
    <div class="hero-visual">
      <div class="hero-monogram">A</div>
      <div class="hero-stats">
        <div class="stat">
          <span class="stat-num">3+</span>
          <span class="stat-label">Years Experience</span>
        </div>
        <div class="stat">
          <span class="stat-num">4</span>
          <span class="stat-label">Languages</span>
        </div>
        <div class="stat">
          <span class="stat-num">∞</span>
          <span class="stat-label">Ideas / Week</span>
        </div>
      </div>
    </div>
  </div>
  <p class="hero-scroll-hint">Scroll to explore</p>
</div>

<!-- MARQUEE -->
<div class="marquee-strip">
  <div class="marquee-inner">
    <span class="accent">Digital Marketing</span>
    <span>·</span>
    <span>Social Media Strategy</span>
    <span>·</span>
    <span class="accent">Content Writing</span>
    <span>·</span>
    <span>Graphic Design</span>
    <span>·</span>
    <span class="accent">Meta Ads</span>
    <span>·</span>
    <span>Brand Identity</span>
    <span>·</span>
    <span class="accent">Web Development</span>
    <span>·</span>
    <span>Copywriting</span>
    <span>·</span>
    <span class="accent">AI-Powered Apps</span>
    <span>·</span>
    <span>Digital Marketing</span>
    <span>·</span>
    <span>Social Media Strategy</span>
    <span>·</span>
    <span class="accent">Content Writing</span>
    <span>·</span>
    <span>Graphic Design</span>
    <span>·</span>
    <span class="accent">Meta Ads</span>
    <span>·</span>
    <span>Brand Identity</span>
    <span>·</span>
    <span class="accent">Web Development</span>
    <span>·</span>
    <span>Copywriting</span>
    <span>·</span>
    <span class="accent">AI-Powered Apps</span>
    <span>·</span>
  </div>
</div>

<!-- SERVICES -->
<div id="services">
  <section style="max-width:1200px;margin:0 auto;padding:100px 0 48px;">
    <p class="section-label reveal">What I Offer</p>
    <h2 class="section-heading reveal">Services built<br><em style="font-family:'Playfair Display',serif;font-style:italic;">for real results.</em></h2>
  </section>
  <div class="services-grid reveal">
    <div class="service-card">
      <div class="service-num">01</div>
      <h3 class="service-title">Social Media Management</h3>
      <p class="service-desc">Strategy, content calendars, captions, and growth for Instagram, TikTok, LinkedIn, and beyond. I've grown accounts from scratch.</p>
      <span class="service-price">Starting at $30</span>
    </div>
    <div class="service-card">
      <div class="service-num">02</div>
      <h3 class="service-title">Content Writing & Copywriting</h3>
      <p class="service-desc">Blog posts, brand voice, website copy, newsletters. Writing that sounds human, converts, and actually gets read.</p>
      <span class="service-price">Starting at $15</span>
    </div>
    <div class="service-card">
      <div class="service-num">03</div>
      <h3 class="service-title">Graphic Design & Branding</h3>
      <p class="service-desc">Logos, brand kits, social templates, and visual identity systems in Canva or Adobe. Clean, distinctive, memorable.</p>
      <span class="service-price">Starting at $20</span>
    </div>
    <div class="service-card">
      <div class="service-num">04</div>
      <h3 class="service-title">Meta Ads & Digital Marketing</h3>
      <p class="service-desc">Facebook & Instagram ad setup, targeting, copy, and optimization. Full Meta Business Suite management with analytics reporting.</p>
      <span class="service-price">Starting at $40</span>
    </div>
    <div class="service-card">
      <div class="service-num">05</div>
      <h3 class="service-title">Web & App Development</h3>
      <p class="service-desc">Landing pages, portfolio sites, and simple web apps. Built with modern tools — I shipped a live AI app used internationally.</p>
      <span class="service-price">Starting at $50</span>
    </div>
    <div class="service-card" style="background:var(--ink);color:var(--paper);">
      <div class="service-num" style="color:rgba(245,240,232,0.1)">✦</div>
      <h3 class="service-title" style="color:var(--paper)">Not sure what you need?</h3>
      <p class="service-desc" style="color:rgba(245,240,232,0.5)">Drop me a message. I'll tell you exactly what would move the needle for your brand — no fluff.</p>
      <a href="#contact" class="work-card-arrow" style="color:var(--sepia)">Let's talk</a>
    </div>
  </div>
</div>

<!-- ABOUT -->
<section id="about">
  <div class="about-left reveal">
    <div class="about-portrait"></div>
    <div class="about-accent-line"></div>
  </div>
  <div class="about-right">
    <p class="section-label reveal">About Me</p>
    <h2 class="section-heading reveal">I don't just<br><em style="font-family:'Playfair Display',serif;font-style:italic;">deliver work.</em><br>I build things.</h2>
    <p class="about-highlight reveal">"Freelancing since 2022. Built an AI app. Currently finishing my IB Diploma. I work fast, think strategically, and I care about the output."</p>
    <p class="about-body reveal">
      I'm <strong>Alishba</strong> — a freelance digital marketer, designer, and builder based in Karachi, Pakistan. I've been working with brands and creators since 2022, managing social media, creating content, running campaigns, and designing visual identities.<br><br>
      In 2025, I founded <strong>Zenvra</strong> — an AI-powered study app for IB, A-Level, and O-Level students — built independently and launched to international users in its first week. If I can ship a product, I can ship your project.
    </p>
    <div class="about-langs reveal">
      <span class="lang-tag">English</span>
      <span class="lang-tag">Urdu</span>
      <span class="lang-tag">French</span>
      <span class="lang-tag">Spanish</span>
    </div>
    <a href="#contact" class="btn-primary reveal">Work With Me</a>
  </div>
</section>

<!-- WORK -->
<div id="work">
  <section style="max-width:1200px;margin:0 auto;padding:100px 0 48px;">
    <p class="section-label reveal">Selected Work</p>
    <h2 class="section-heading reveal">Things I've<br><em style="font-family:'Playfair Display',serif;font-style:italic;">actually built.</em></h2>
  </section>
  <div class="work-grid reveal" style="max-width:1200px;margin:0 auto;">
    <div class="work-card">
      <p class="work-card-tag">App Development · AI</p>
      <h3 class="work-card-title">Zenvra</h3>
      <p class="work-card-desc">AI-powered study coach for IB, A-Level & O-Level students. Built with v0.dev, Vercel, and Google Gemini API. Gained international users within the first week of launch.</p>
      <a href="#" class="work-card-arrow">View Project</a>
    </div>
    <div class="work-card">
      <p class="work-card-tag">Content Strategy · YouTube</p>
      <h3 class="work-card-title">Obscurra</h3>
      <p class="work-card-desc">Strategy and full content playbook for a faceless YouTube channel covering dark history, science, and mystery. Sardonic, cinematic tone. Built for scale.</p>
      <a href="#" class="work-card-arrow">View Project</a>
    </div>
    <div class="work-card">
      <p class="work-card-tag">Freelance · Digital Marketing</p>
      <h3 class="work-card-title">Brand Growth Campaigns</h3>
      <p class="work-card-desc">3+ years managing social media, Meta Ads, and content strategy for multiple clients. Tools: Canva, Adobe Creative Suite, Meta Business Suite, Google Analytics.</p>
      <a href="#contact" class="work-card-arrow">Enquire</a>
    </div>
  </div>
</div>

<!-- TESTIMONIALS -->
<section id="testimonials">
  <p class="section-label reveal">Social Proof</p>
  <h2 class="section-heading reveal">What clients<br><em style="font-family:'Playfair Display',serif;font-style:italic;">say.</em></h2>
  <div class="testimonial-stack">
    <div class="testimonial reveal">
      <p class="testimonial-text">Fast, creative, and incredibly easy to work with. She understood the brief immediately and delivered work that felt genuinely thought through — not templated.</p>
      <p class="testimonial-author">— Client Review · <span>Digital Marketing</span></p>
    </div>
    <div class="testimonial reveal">
      <p class="testimonial-text">The brand identity she designed was exactly the aesthetic we were going for. Clean, intentional, and delivered ahead of schedule.</p>
      <p class="testimonial-author">— Client Review · <span>Graphic Design</span></p>
    </div>
  </div>
  <p style="font-size:11px;color:var(--faint);margin-top:20px;font-style:italic;">* Replace with real reviews once received on Fiverr.</p>
</section>

<!-- CONTACT -->
<div id="contact">
  <section style="max-width:800px;margin:0 auto;padding:0;">
    <p class="section-label">Get In Touch</p>
    <h2 class="section-heading">Ready to start<br><em style="font-family:'Playfair Display',serif;">something?</em></h2>
    <p class="contact-sub">Whether you need a brand built, content written, ads managed, or an idea shipped — I'm your person. Fast turnarounds. Clear communication. Work I'm proud of.</p>
    <div class="contact-links">
      <a href="https://www.fiverr.com" target="_blank" class="contact-link primary">Hire Me on Fiverr</a>
      <a href="https://instagram.com/byalishba_aln" target="_blank" class="contact-link">Instagram</a>
      <a href="https://linkedin.com/in/alishba-al-nadeem" target="_blank" class="contact-link">LinkedIn</a>
    </div>
    <div class="contact-divider"></div>
    <p class="contact-email">alishba.al.nadeem@gmail.com</p>
  </section>
</div>

<!-- FOOTER -->
<footer>
  <span>© 2025 Alishba Al Nadeem</span>
  <span>Karachi, Pakistan · Available Worldwide</span>
</footer>

<script>
  // Custom cursor
  const cursor = document.getElementById('cursor');
  const ring = document.getElementById('cursorRing');
  let mx = 0, my = 0, rx = 0, ry = 0;

  document.addEventListener('mousemove', e => {
    mx = e.clientX; my = e.clientY;
    cursor.style.left = mx - 4 + 'px';
    cursor.style.top = my - 4 + 'px';
  });

  function animRing() {
    rx += (mx - rx) * 0.12;
    ry += (my - ry) * 0.12;
    ring.style.left = rx - 14 + 'px';
    ring.style.top = ry - 14 + 'px';
    requestAnimationFrame(animRing);
  }
  animRing();

  document.querySelectorAll('a, button').forEach(el => {
    el.addEventListener('mouseenter', () => {
      cursor.style.transform = 'scale(2.5)';
      ring.style.transform = 'scale(1.5)';
      ring.style.opacity = '0.2';
    });
    el.addEventListener('mouseleave', () => {
      cursor.style.transform = 'scale(1)';
      ring.style.transform = 'scale(1)';
      ring.style.opacity = '0.5';
    });
  });

  // Scroll reveal
  const reveals = document.querySelectorAll('.reveal');
  const observer = new IntersectionObserver((entries) => {
    entries.forEach((entry, i) => {
      if (entry.isIntersecting) {
        setTimeout(() => entry.target.classList.add('visible'), i * 60);
        observer.unobserve(entry.target);
      }
    });
  }, { threshold: 0.1 });

  reveals.forEach(el => observer.observe(el));
</script>
</body>
</html>
