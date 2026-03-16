<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KING — Social E-Commerce AI Research Portfolio</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;0,900;1,400;1,700&family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=Space+Mono:wght@400;700&display=swap" rel="stylesheet">
<style>
  :root {
    --gold: #C9A84C;
    --gold-light: #F0D080;
    --gold-pale: #F7E8B0;
    --black: #080808;
    --deep: #0A0A12;
    --navy: #080E1E;
    --ink: #111827;
    --mid: #1E2A3A;
    --muted: #8896A8;
    --white: #F8F4EE;
    --cream: #EDE5D4;
    --teal: #0D8A94;
    --teal-glow: rgba(13,138,148,0.25);
  }

  *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }

  html { scroll-behavior: smooth; }

  body {
    font-family: 'Cormorant Garamond', serif;
    background: var(--deep);
    color: var(--white);
    overflow-x: hidden;
    cursor: none;
  }

  /* ── CUSTOM CURSOR ── */
  .cursor {
    position: fixed; width: 10px; height: 10px;
    background: var(--gold); border-radius: 50%;
    pointer-events: none; z-index: 9999;
    transform: translate(-50%,-50%);
    transition: transform 0.1s, width 0.3s, height 0.3s, background 0.3s;
  }
  .cursor-ring {
    position: fixed; width: 36px; height: 36px;
    border: 1.5px solid var(--gold); border-radius: 50%;
    pointer-events: none; z-index: 9998;
    transform: translate(-50%,-50%);
    transition: transform 0.18s ease, width 0.3s, height 0.3s, opacity 0.3s;
    opacity: 0.5;
  }

  /* ── NOISE TEXTURE OVERLAY ── */
  body::after {
    content: '';
    position: fixed; inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.035'/%3E%3C/svg%3E");
    pointer-events: none; z-index: 9990; opacity: 0.4;
  }

  /* ── NAV ── */
  nav {
    position: fixed; top: 0; left: 0; right: 0; z-index: 100;
    display: flex; align-items: center; justify-content: space-between;
    padding: 1.4rem 4rem;
    background: linear-gradient(to bottom, rgba(8,8,18,0.95) 0%, transparent 100%);
    backdrop-filter: blur(2px);
  }
  .nav-logo {
    font-family: 'Playfair Display', serif;
    font-size: 1.5rem; font-weight: 900;
    letter-spacing: 0.25em;
    color: var(--gold);
    text-decoration: none;
  }
  .nav-logo span { color: var(--white); font-style: italic; font-weight: 400; }
  .nav-links { display: flex; gap: 2.5rem; list-style: none; }
  .nav-links a {
    font-family: 'Space Mono', monospace;
    font-size: 0.65rem; letter-spacing: 0.18em; text-transform: uppercase;
    color: var(--muted); text-decoration: none;
    transition: color 0.3s;
  }
  .nav-links a:hover { color: var(--gold); }
  .nav-cta {
    font-family: 'Space Mono', monospace;
    font-size: 0.65rem; letter-spacing: 0.15em; text-transform: uppercase;
    color: var(--gold); border: 1px solid rgba(201,168,76,0.4);
    padding: 0.55rem 1.4rem; text-decoration: none;
    transition: background 0.3s, color 0.3s;
  }
  .nav-cta:hover { background: var(--gold); color: var(--black); }

  /* ── HERO ── */
  .hero {
    min-height: 100vh;
    display: grid;
    grid-template-columns: 1fr 1fr;
    position: relative;
    overflow: hidden;
  }

  .hero-left {
    display: flex; flex-direction: column; justify-content: center;
    padding: 8rem 4rem 6rem 6rem;
    position: relative; z-index: 2;
  }

  .hero-eyebrow {
    font-family: 'Space Mono', monospace;
    font-size: 0.6rem; letter-spacing: 0.3em; text-transform: uppercase;
    color: var(--teal); margin-bottom: 1.5rem;
    display: flex; align-items: center; gap: 1rem;
  }
  .hero-eyebrow::before {
    content: ''; display: block;
    width: 2rem; height: 1px; background: var(--teal);
  }

  .hero-title {
    font-family: 'Playfair Display', serif;
    font-size: clamp(3.5rem, 6vw, 7rem);
    line-height: 0.92;
    font-weight: 900;
    margin-bottom: 1rem;
  }
  .hero-title .line-gold { color: var(--gold); font-style: italic; }
  .hero-title .line-muted { color: rgba(248,244,238,0.3); font-size: 0.55em; font-weight: 400; letter-spacing: 0.08em; }

  .hero-desc {
    font-size: 1.15rem; line-height: 1.7;
    color: rgba(248,244,238,0.6);
    max-width: 38ch; margin: 2rem 0;
    font-style: italic;
  }

  .hero-actions { display: flex; gap: 1.2rem; align-items: center; margin-top: 1rem; }
  .btn-primary {
    font-family: 'Space Mono', monospace;
    font-size: 0.65rem; letter-spacing: 0.18em; text-transform: uppercase;
    background: var(--gold); color: var(--black);
    padding: 0.9rem 2.2rem; text-decoration: none; font-weight: 700;
    transition: transform 0.25s, box-shadow 0.25s;
    position: relative; overflow: hidden;
  }
  .btn-primary::before {
    content: ''; position: absolute; inset: 0;
    background: var(--gold-light); transform: translateX(-101%);
    transition: transform 0.3s;
  }
  .btn-primary:hover::before { transform: translateX(0); }
  .btn-primary:hover { transform: translateY(-2px); box-shadow: 0 12px 40px rgba(201,168,76,0.4); }
  .btn-primary span { position: relative; z-index: 1; }

  .btn-ghost {
    font-family: 'Space Mono', monospace;
    font-size: 0.65rem; letter-spacing: 0.18em; text-transform: uppercase;
    color: var(--muted); text-decoration: none;
    display: flex; align-items: center; gap: 0.7rem;
    transition: color 0.3s;
  }
  .btn-ghost:hover { color: var(--white); }
  .btn-ghost .arrow { transition: transform 0.3s; }
  .btn-ghost:hover .arrow { transform: translateX(5px); }

  /* Hero right — image collage */
  .hero-right {
    position: relative; overflow: hidden;
  }
  .hero-right::before {
    content: ''; position: absolute; inset: 0; z-index: 1;
    background: linear-gradient(to right, var(--deep) 0%, transparent 30%);
  }

  .hero-img-main {
    width: 100%; height: 100%;
    object-fit: cover;
    filter: brightness(0.55) saturate(0.8);
  }

  .hero-badge {
    position: absolute; bottom: 3rem; right: 3rem; z-index: 3;
    width: 130px; height: 130px;
    border: 1px solid rgba(201,168,76,0.3);
    border-radius: 50%;
    display: flex; flex-direction: column; align-items: center; justify-content: center;
    background: rgba(8,8,18,0.7); backdrop-filter: blur(8px);
    animation: rotate 20s linear infinite;
  }
  .hero-badge-text {
    font-family: 'Space Mono', monospace;
    font-size: 0.5rem; letter-spacing: 0.2em; text-transform: uppercase;
    color: var(--gold);
    text-align: center; line-height: 1.8;
  }
  .hero-badge-icon { font-size: 1.4rem; margin-bottom: 0.3rem; }

  @keyframes rotate {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
  }

  /* Hero stats bar */
  .hero-stats {
    position: absolute; bottom: 0; left: 0; right: 50%;
    z-index: 3;
    display: grid; grid-template-columns: repeat(3,1fr);
    border-top: 1px solid rgba(201,168,76,0.15);
  }
  .stat-item {
    padding: 1.5rem 1.8rem;
    border-right: 1px solid rgba(201,168,76,0.1);
    background: rgba(8,8,18,0.6); backdrop-filter: blur(10px);
  }
  .stat-num {
    font-family: 'Playfair Display', serif;
    font-size: 2rem; font-weight: 700; color: var(--gold);
    line-height: 1;
  }
  .stat-label {
    font-family: 'Space Mono', monospace;
    font-size: 0.55rem; letter-spacing: 0.15em; text-transform: uppercase;
    color: var(--muted); margin-top: 0.3rem;
  }

  /* ── MARQUEE ── */
  .marquee-wrap {
    background: var(--gold);
    overflow: hidden; padding: 0.7rem 0;
  }
  .marquee-track {
    display: flex; gap: 0;
    animation: marquee 30s linear infinite;
    white-space: nowrap;
  }
  .marquee-item {
    font-family: 'Space Mono', monospace;
    font-size: 0.6rem; letter-spacing: 0.2em; text-transform: uppercase;
    color: var(--black); padding: 0 2rem;
    display: flex; align-items: center; gap: 1.5rem;
  }
  .marquee-dot { width: 4px; height: 4px; background: rgba(0,0,0,0.4); border-radius: 50%; }
  @keyframes marquee {
    from { transform: translateX(0); }
    to { transform: translateX(-50%); }
  }

  /* ── SECTION COMMON ── */
  section { padding: 7rem 6rem; }
  .section-label {
    font-family: 'Space Mono', monospace;
    font-size: 0.6rem; letter-spacing: 0.3em; text-transform: uppercase;
    color: var(--teal); margin-bottom: 1rem;
    display: flex; align-items: center; gap: 0.8rem;
  }
  .section-label::before {
    content: ''; width: 1.5rem; height: 1px; background: var(--teal);
  }
  .section-title {
    font-family: 'Playfair Display', serif;
    font-size: clamp(2.2rem, 4vw, 3.5rem);
    font-weight: 900; line-height: 1.1;
  }
  .section-title em { color: var(--gold); font-style: italic; }

  /* ── ABOUT / OVERVIEW ── */
  .about {
    display: grid; grid-template-columns: 1fr 1fr;
    gap: 6rem; align-items: center;
    background: var(--navy);
  }

  .about-text p {
    font-size: 1.1rem; line-height: 1.85;
    color: rgba(248,244,238,0.65); margin-top: 1.5rem;
  }
  .about-text p strong { color: var(--gold-pale); font-weight: 600; }

  .about-img-grid {
    display: grid; grid-template-columns: 1fr 1fr;
    grid-template-rows: 200px 200px;
    gap: 1rem; position: relative;
  }
  .about-img-grid img {
    width: 100%; height: 100%; object-fit: cover;
    filter: brightness(0.7) saturate(0.75);
    transition: filter 0.4s, transform 0.4s;
  }
  .about-img-grid img:hover { filter: brightness(0.9) saturate(1); transform: scale(1.02); }
  .about-img-grid .img-tall {
    grid-row: span 2;
    filter: brightness(0.65) saturate(0.75);
  }
  .about-img-accent {
    position: absolute; bottom: -1rem; right: -1rem;
    background: var(--gold); color: var(--black);
    font-family: 'Playfair Display', serif;
    font-size: 1.1rem; font-weight: 700; font-style: italic;
    padding: 1rem 1.4rem; z-index: 2;
  }

  /* ── PROBLEMS GRID ── */
  .problems { background: var(--deep); }
  .problems-header { display: flex; justify-content: space-between; align-items: flex-end; margin-bottom: 3.5rem; }

  .problems-grid {
    display: grid; grid-template-columns: repeat(3,1fr);
    gap: 1.5px;
    background: rgba(201,168,76,0.1);
    border: 1px solid rgba(201,168,76,0.1);
  }
  .problem-card {
    background: var(--deep);
    padding: 2.5rem 2rem;
    position: relative; overflow: hidden;
    transition: background 0.4s;
  }
  .problem-card::before {
    content: ''; position: absolute;
    top: 0; left: 0; width: 3px; height: 0;
    background: var(--gold);
    transition: height 0.4s;
  }
  .problem-card:hover { background: rgba(13,138,148,0.06); }
  .problem-card:hover::before { height: 100%; }

  .problem-num {
    font-family: 'Playfair Display', serif;
    font-size: 3.5rem; font-weight: 900;
    color: rgba(201,168,76,0.12);
    line-height: 1; margin-bottom: 0.5rem;
  }
  .problem-icon { font-size: 1.6rem; margin-bottom: 0.8rem; }
  .problem-title {
    font-family: 'Playfair Display', serif;
    font-size: 1.15rem; font-weight: 700;
    color: var(--white); margin-bottom: 0.7rem;
  }
  .problem-desc {
    font-size: 0.95rem; line-height: 1.7;
    color: var(--muted);
  }
  .problem-tag {
    font-family: 'Space Mono', monospace;
    font-size: 0.5rem; letter-spacing: 0.15em; text-transform: uppercase;
    color: var(--teal); border: 1px solid rgba(13,138,148,0.35);
    padding: 0.3rem 0.7rem; display: inline-block; margin-top: 1rem;
  }

  /* ── SOLUTIONS SHOWCASE ── */
  .solutions {
    background: var(--mid);
    position: relative; overflow: hidden;
  }
  .solutions::before {
    content: 'AI'; position: absolute;
    right: -2rem; top: 50%; transform: translateY(-50%);
    font-family: 'Playfair Display', serif;
    font-size: 22rem; font-weight: 900;
    color: rgba(255,255,255,0.02); line-height: 1;
    pointer-events: none;
  }

  .solutions-grid {
    display: grid; grid-template-columns: repeat(2,1fr);
    gap: 2rem; margin-top: 3.5rem;
  }
  .solution-card {
    background: rgba(8,8,18,0.5);
    border: 1px solid rgba(201,168,76,0.1);
    padding: 2.5rem;
    display: grid; grid-template-columns: auto 1fr;
    gap: 1.5rem; align-items: start;
    transition: border-color 0.4s, transform 0.3s;
    position: relative; overflow: hidden;
  }
  .solution-card:hover {
    border-color: rgba(201,168,76,0.4);
    transform: translateY(-4px);
  }
  .solution-card::after {
    content: ''; position: absolute;
    bottom: 0; left: 0; right: 0; height: 2px;
    background: linear-gradient(90deg, var(--teal), var(--gold));
    transform: scaleX(0); transition: transform 0.4s;
    transform-origin: left;
  }
  .solution-card:hover::after { transform: scaleX(1); }

  .solution-icon-wrap {
    width: 52px; height: 52px;
    background: rgba(201,168,76,0.1);
    border: 1px solid rgba(201,168,76,0.2);
    display: flex; align-items: center; justify-content: center;
    font-size: 1.4rem; flex-shrink: 0;
  }
  .solution-title {
    font-family: 'Playfair Display', serif;
    font-size: 1.2rem; font-weight: 700; color: var(--white);
    margin-bottom: 0.6rem;
  }
  .solution-desc {
    font-size: 0.95rem; line-height: 1.7; color: var(--muted);
  }
  .solution-tech {
    font-family: 'Space Mono', monospace;
    font-size: 0.5rem; letter-spacing: 0.12em; color: var(--teal);
    margin-top: 1rem;
  }

  /* ── FEATURED IMAGE SECTION ── */
  .featured-showcase {
    padding: 0; position: relative;
    height: 70vh; overflow: hidden;
  }
  .featured-showcase img {
    width: 100%; height: 100%;
    object-fit: cover;
    filter: brightness(0.45) saturate(0.7);
  }
  .featured-overlay {
    position: absolute; inset: 0; z-index: 2;
    display: flex; align-items: center; justify-content: center;
    background: linear-gradient(135deg, rgba(8,8,18,0.7) 0%, rgba(13,138,148,0.15) 100%);
  }
  .featured-content { text-align: center; max-width: 700px; padding: 2rem; }
  .featured-content h2 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(2.5rem, 5vw, 4.5rem); font-weight: 900;
    line-height: 1.05; margin-bottom: 1.5rem;
  }
  .featured-content h2 em { color: var(--gold); font-style: italic; display: block; }
  .featured-content p {
    font-size: 1.1rem; line-height: 1.7;
    color: rgba(248,244,238,0.65); font-style: italic;
  }

  /* ── RESULTS METRICS ── */
  .metrics {
    background: var(--navy);
    display: grid; grid-template-columns: 1fr 1fr;
    gap: 0; padding: 0;
  }
  .metrics-left {
    padding: 7rem 5rem 7rem 6rem;
    border-right: 1px solid rgba(201,168,76,0.1);
  }
  .metrics-right {
    display: grid; grid-template-columns: 1fr 1fr;
  }
  .metric-box {
    padding: 3.5rem 2.5rem;
    border-bottom: 1px solid rgba(201,168,76,0.08);
    border-right: 1px solid rgba(201,168,76,0.08);
    position: relative; overflow: hidden;
    transition: background 0.4s;
  }
  .metric-box:hover { background: rgba(201,168,76,0.04); }
  .metric-box::before {
    content: ''; position: absolute; top: 0; left: 0; right: 0; height: 2px;
    background: var(--gold); transform: scaleX(0);
    transition: transform 0.4s; transform-origin: left;
  }
  .metric-box:hover::before { transform: scaleX(1); }

  .metric-value {
    font-family: 'Playfair Display', serif;
    font-size: 3.5rem; font-weight: 900;
    color: var(--gold); line-height: 1;
  }
  .metric-unit {
    font-size: 1.5rem; color: var(--teal);
  }
  .metric-label {
    font-family: 'Space Mono', monospace;
    font-size: 0.55rem; letter-spacing: 0.2em; text-transform: uppercase;
    color: var(--muted); margin-top: 0.5rem;
  }
  .metric-change {
    font-size: 0.85rem; color: #4ADE80; margin-top: 0.3rem;
    font-family: 'Space Mono', monospace;
  }

  .metrics-left .section-title { margin-top: 1rem; }
  .metrics-left p {
    font-size: 1.05rem; line-height: 1.85;
    color: rgba(248,244,238,0.55); margin-top: 1.5rem; font-style: italic;
  }

  /* ── IMAGE STRIP ── */
  .image-strip {
    display: grid; grid-template-columns: repeat(4,1fr);
    height: 280px; gap: 0; padding: 0;
  }
  .strip-item {
    position: relative; overflow: hidden;
  }
  .strip-item img {
    width: 100%; height: 100%; object-fit: cover;
    filter: brightness(0.5) saturate(0.6);
    transition: filter 0.5s, transform 0.5s;
  }
  .strip-item:hover img { filter: brightness(0.75) saturate(1); transform: scale(1.08); }
  .strip-item-label {
    position: absolute; bottom: 1rem; left: 1rem;
    font-family: 'Space Mono', monospace;
    font-size: 0.55rem; letter-spacing: 0.15em; text-transform: uppercase;
    color: var(--gold); opacity: 0; transition: opacity 0.4s;
  }
  .strip-item:hover .strip-item-label { opacity: 1; }

  /* ── RESEARCH MODULES ── */
  .modules { background: var(--deep); }
  .modules-grid {
    display: grid; grid-template-columns: repeat(4,1fr);
    gap: 1rem; margin-top: 3.5rem;
  }
  .module-card {
    padding: 2rem 1.5rem;
    border: 1px solid rgba(201,168,76,0.08);
    background: rgba(14,20,32,0.6);
    position: relative; overflow: hidden;
    transition: border-color 0.4s, transform 0.3s;
  }
  .module-card:hover {
    border-color: rgba(201,168,76,0.3);
    transform: translateY(-5px);
  }
  .module-num {
    font-family: 'Playfair Display', serif;
    font-size: 0.8rem; font-weight: 700; color: var(--gold);
    letter-spacing: 0.1em; margin-bottom: 1rem;
  }
  .module-title {
    font-family: 'Playfair Display', serif;
    font-size: 1rem; font-weight: 700; color: var(--white);
    margin-bottom: 0.7rem; line-height: 1.3;
  }
  .module-desc {
    font-size: 0.85rem; line-height: 1.6; color: var(--muted);
  }
  .module-bar {
    margin-top: 1.5rem; height: 2px;
    background: rgba(201,168,76,0.1); position: relative;
  }
  .module-bar-fill {
    height: 100%; background: linear-gradient(90deg, var(--teal), var(--gold));
    transition: width 1s ease; width: 0;
  }

  /* ── PUBLICATIONS ── */
  .publications {
    background: var(--mid);
    position: relative;
  }
  .pub-list { margin-top: 3rem; }
  .pub-item {
    display: grid; grid-template-columns: auto 1fr auto;
    gap: 2rem; align-items: start;
    padding: 2rem 0;
    border-bottom: 1px solid rgba(201,168,76,0.1);
    transition: background 0.3s; position: relative;
  }
  .pub-item::before {
    content: ''; position: absolute; left: -6rem; right: -6rem;
    top: 0; bottom: 0; background: rgba(201,168,76,0.03);
    opacity: 0; transition: opacity 0.3s;
  }
  .pub-item:hover::before { opacity: 1; }

  .pub-year {
    font-family: 'Space Mono', monospace;
    font-size: 0.7rem; color: var(--teal); letter-spacing: 0.1em;
    padding-top: 0.2rem;
  }
  .pub-venue {
    font-family: 'Space Mono', monospace;
    font-size: 0.55rem; letter-spacing: 0.15em; text-transform: uppercase;
    color: var(--muted); margin-bottom: 0.5rem;
  }
  .pub-title {
    font-family: 'Playfair Display', serif;
    font-size: 1.1rem; font-weight: 700; color: var(--white);
    font-style: italic; margin-bottom: 0.5rem;
  }
  .pub-authors {
    font-size: 0.85rem; color: var(--muted);
  }
  .pub-badge {
    font-family: 'Space Mono', monospace;
    font-size: 0.5rem; letter-spacing: 0.12em; text-transform: uppercase;
    padding: 0.3rem 0.8rem; font-weight: 700;
    white-space: nowrap; align-self: center;
  }
  .badge-accepted { background: rgba(74,222,128,0.15); color: #4ADE80; border: 1px solid rgba(74,222,128,0.3); }
  .badge-published { background: rgba(13,138,148,0.2); color: var(--teal); border: 1px solid rgba(13,138,148,0.4); }
  .badge-review { background: rgba(201,168,76,0.12); color: var(--gold); border: 1px solid rgba(201,168,76,0.3); }
  .badge-poster { background: rgba(139,92,246,0.15); color: #A78BFA; border: 1px solid rgba(139,92,246,0.3); }

  /* ── TECH STACK ── */
  .tech-stack { background: var(--navy); padding: 5rem 6rem; }
  .tech-label {
    font-family: 'Space Mono', monospace;
    font-size: 0.6rem; letter-spacing: 0.3em; text-transform: uppercase;
    color: var(--muted); text-align: center; margin-bottom: 2.5rem;
    display: flex; align-items: center; justify-content: center; gap: 1rem;
  }
  .tech-label::before, .tech-label::after {
    content: ''; flex: 1; max-width: 6rem; height: 1px;
    background: rgba(201,168,76,0.2);
  }
  .tech-tags {
    display: flex; flex-wrap: wrap; gap: 0.7rem;
    justify-content: center;
  }
  .tech-tag {
    font-family: 'Space Mono', monospace;
    font-size: 0.6rem; letter-spacing: 0.12em; text-transform: uppercase;
    color: var(--muted); border: 1px solid rgba(255,255,255,0.08);
    padding: 0.5rem 1.1rem;
    transition: color 0.3s, border-color 0.3s, background 0.3s;
  }
  .tech-tag:hover {
    color: var(--gold); border-color: rgba(201,168,76,0.35);
    background: rgba(201,168,76,0.05);
  }

  /* ── CONTACT / CTA ── */
  .contact-cta {
    background: var(--deep);
    display: grid; grid-template-columns: 1fr 1fr;
    min-height: 60vh;
    padding: 0;
  }
  .contact-left {
    padding: 7rem 5rem 7rem 6rem;
    display: flex; flex-direction: column; justify-content: center;
    border-right: 1px solid rgba(201,168,76,0.1);
  }
  .contact-right {
    position: relative; overflow: hidden;
  }
  .contact-right img {
    width: 100%; height: 100%;
    object-fit: cover;
    filter: brightness(0.4) saturate(0.6);
  }
  .contact-right::before {
    content: ''; position: absolute; inset: 0; z-index: 1;
    background: linear-gradient(to right, rgba(8,8,18,0.4) 0%, transparent 60%);
  }

  .contact-left h2 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(2.2rem,3.5vw,3.5rem); font-weight: 900;
    line-height: 1.1; margin-top: 1rem;
  }
  .contact-left h2 em { color: var(--gold); font-style: italic; display: block; }
  .contact-left p {
    font-size: 1.05rem; line-height: 1.8;
    color: rgba(248,244,238,0.55); margin: 1.5rem 0 2.5rem;
    font-style: italic;
  }

  .contact-form { display: flex; flex-direction: column; gap: 1rem; }
  .form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; }
  .form-input {
    background: rgba(255,255,255,0.04);
    border: 1px solid rgba(201,168,76,0.15);
    color: var(--white); padding: 0.85rem 1.1rem;
    font-family: 'Cormorant Garamond', serif; font-size: 1rem;
    outline: none; transition: border-color 0.3s;
    width: 100%;
  }
  .form-input::placeholder { color: rgba(255,255,255,0.25); font-style: italic; }
  .form-input:focus { border-color: rgba(201,168,76,0.5); }
  .form-textarea {
    resize: vertical; min-height: 100px;
  }

  .btn-submit {
    font-family: 'Space Mono', monospace;
    font-size: 0.65rem; letter-spacing: 0.2em; text-transform: uppercase;
    background: var(--gold); color: var(--black); font-weight: 700;
    padding: 1rem 2.5rem; border: none; cursor: pointer;
    transition: background 0.3s, transform 0.2s;
    align-self: flex-start;
  }
  .btn-submit:hover { background: var(--gold-light); transform: translateY(-2px); }

  /* ── FOOTER ── */
  footer {
    background: var(--black);
    padding: 3rem 6rem;
    display: flex; align-items: center; justify-content: space-between;
    border-top: 1px solid rgba(201,168,76,0.12);
  }
  .footer-logo {
    font-family: 'Playfair Display', serif;
    font-size: 1.3rem; font-weight: 900; color: var(--gold);
    letter-spacing: 0.2em;
  }
  .footer-copy {
    font-family: 'Space Mono', monospace;
    font-size: 0.55rem; letter-spacing: 0.15em; text-transform: uppercase;
    color: var(--muted);
  }
  .footer-links { display: flex; gap: 2rem; }
  .footer-links a {
    font-family: 'Space Mono', monospace;
    font-size: 0.55rem; letter-spacing: 0.15em; text-transform: uppercase;
    color: var(--muted); text-decoration: none;
    transition: color 0.3s;
  }
  .footer-links a:hover { color: var(--gold); }

  /* ── SCROLL REVEAL ── */
  .reveal { opacity: 0; transform: translateY(30px); transition: opacity 0.8s ease, transform 0.8s ease; }
  .reveal.visible { opacity: 1; transform: translateY(0); }

  /* ── GOLD LINE DECORATION ── */
  .gold-line {
    width: 40px; height: 2px;
    background: linear-gradient(90deg, var(--gold), var(--teal));
    margin: 1.5rem 0;
  }

  @media (max-width: 1024px) {
    nav { padding: 1.2rem 2rem; }
    .nav-links { display: none; }
    section { padding: 5rem 3rem; }
    .hero { grid-template-columns: 1fr; }
    .hero-right { display: none; }
    .hero-left { padding: 9rem 3rem 4rem; }
    .hero-stats { right: 0; left: 0; grid-template-columns: repeat(3,1fr); }
    .about { grid-template-columns: 1fr; gap: 3rem; }
    .problems-grid { grid-template-columns: 1fr 1fr; }
    .solutions-grid { grid-template-columns: 1fr; }
    .metrics { grid-template-columns: 1fr; }
    .modules-grid { grid-template-columns: 1fr 1fr; }
    .contact-cta { grid-template-columns: 1fr; }
    .contact-right { display: none; }
    .image-strip { grid-template-columns: repeat(2,1fr); }
    footer { flex-direction: column; gap: 1.5rem; text-align: center; }
  }
</style>
</head>
<body>

<!-- Custom Cursor -->
<div class="cursor" id="cursor"></div>
<div class="cursor-ring" id="cursorRing"></div>

<!-- ══ NAVIGATION ══ -->
<nav>
  <a href="#" class="nav-logo">KING <span>Research</span></a>
  <ul class="nav-links">
    <li><a href="#about">Overview</a></li>
    <li><a href="#problems">Problems</a></li>
    <li><a href="#solutions">Solutions</a></li>
    <li><a href="#modules">Modules</a></li>
    <li><a href="#publications">Publications</a></li>
  </ul>
  <a href="#contact" class="nav-cta">Get in Touch</a>
</nav>

<!-- ══ HERO ══ -->
<section class="hero" id="home">
  <div class="hero-left">
    <div class="hero-eyebrow">AI Research Portfolio — 2025</div>
    <h1 class="hero-title">
      <span class="line-muted">Social</span><br>
      <span class="line-gold">E-Commerce</span><br>
      Intelligence
    </h1>
    <p class="hero-desc">Architecting the future of digital commerce through advanced artificial intelligence — solving real problems at the intersection of social platforms and e-commerce.</p>
    <div class="hero-actions">
      <a href="#solutions" class="btn-primary"><span>Explore Research ↓</span></a>
      <a href="#publications" class="btn-ghost">View Publications <span class="arrow">→</span></a>
    </div>
  </div>
  <div class="hero-right">
    <img class="hero-img-main" src="https://images.unsplash.com/photo-1611532736597-de2d4265fba3?w=900&auto=format&fit=crop&q=80" alt="Social Commerce" />
    <div class="hero-badge">
      <div class="hero-badge-icon">♛</div>
      <div class="hero-badge-text">AI<br>DRIVEN<br>RESEARCH<br>2025</div>
    </div>
  </div>

  <!-- Stats Bar -->
  <div class="hero-stats">
    <div class="stat-item">
      <div class="stat-num">93.2<span style="font-size:1rem">%</span></div>
      <div class="stat-label">Precision Score</div>
    </div>
    <div class="stat-item">
      <div class="stat-num">8</div>
      <div class="stat-label">AI Modules</div>
    </div>
    <div class="stat-item">
      <div class="stat-num">4</div>
      <div class="stat-label">Publications</div>
    </div>
  </div>
</section>

<!-- ══ MARQUEE ══ -->
<div class="marquee-wrap">
  <div class="marquee-track">
    <!-- duplicated for seamless loop -->
    <span class="marquee-item">Social E-Commerce AI <span class="marquee-dot"></span></span>
    <span class="marquee-item">Recommendation Systems <span class="marquee-dot"></span></span>
    <span class="marquee-item">NLP & Sentiment Analysis <span class="marquee-dot"></span></span>
    <span class="marquee-item">Federated Learning <span class="marquee-dot"></span></span>
    <span class="marquee-item">Reinforcement Learning Pricing <span class="marquee-dot"></span></span>
    <span class="marquee-item">Graph Neural Networks <span class="marquee-dot"></span></span>
    <span class="marquee-item">Computer Vision <span class="marquee-dot"></span></span>
    <span class="marquee-item">KING Research Portfolio <span class="marquee-dot"></span></span>
    <span class="marquee-item">Social E-Commerce AI <span class="marquee-dot"></span></span>
    <span class="marquee-item">Recommendation Systems <span class="marquee-dot"></span></span>
    <span class="marquee-item">NLP & Sentiment Analysis <span class="marquee-dot"></span></span>
    <span class="marquee-item">Federated Learning <span class="marquee-dot"></span></span>
    <span class="marquee-item">Reinforcement Learning Pricing <span class="marquee-dot"></span></span>
    <span class="marquee-item">Graph Neural Networks <span class="marquee-dot"></span></span>
    <span class="marquee-item">Computer Vision <span class="marquee-dot"></span></span>
    <span class="marquee-item">KING Research Portfolio <span class="marquee-dot"></span></span>
  </div>
</div>

<!-- ══ ABOUT ══ -->
<section class="about" id="about">
  <div class="about-text reveal">
    <div class="section-label">Research Overview</div>
    <h2 class="section-title">Where Social<br><em>Meets Commerce</em><br>& Intelligence</h2>
    <div class="gold-line"></div>
    <p>The global social commerce market has surpassed <strong>$1.3 trillion</strong> in 2024, yet platforms remain plagued by recommendation failures, trust deficits, and algorithmic bias.</p>
    <p>This research constructs <strong>AISCOF</strong> — an AI-Integrated Social Commerce Optimization Framework — weaving together eight specialist AI modules into a unified, scalable, and privacy-preserving intelligence layer for modern commerce platforms.</p>
    <p>The framework demonstrates <strong>+34% engagement</strong>, <strong>+28% conversion rates</strong>, and <strong>+41% user retention</strong> over industry-standard baselines.</p>
  </div>
  <div class="about-img-grid reveal">
    <img class="img-tall" src="https://images.unsplash.com/photo-1556742049-0cfed4f6a45d?w=500&auto=format&fit=crop&q=80" alt="E-commerce" />
    <img src="https://images.unsplash.com/photo-1591696205602-2f950c417cb9?w=500&auto=format&fit=crop&q=80" alt="AI Technology" />
    <img src="https://images.unsplash.com/photo-1504868584819-f8e8b4b6d7e3?w=500&auto=format&fit=crop&q=80" alt="Data Analytics" />
    <div class="about-img-accent">AISCOF<br><em style="font-size:0.75rem;font-weight:400">Framework</em></div>
  </div>
</section>

<!-- ══ PROBLEMS ══ -->
<section class="problems" id="problems">
  <div class="problems-header reveal">
    <div>
      <div class="section-label">Identified Challenges</div>
      <h2 class="section-title">Six Core <em>Problems</em><br>in Social Commerce</h2>
    </div>
    <p style="max-width:28ch;font-size:1rem;line-height:1.7;color:var(--muted);font-style:italic;text-align:right;">Each problem identified through systematic literature analysis and empirical platform audit.</p>
  </div>
  <div class="problems-grid">
    <div class="problem-card reveal">
      <div class="problem-num">01</div>
      <div class="problem-icon">❄️</div>
      <div class="problem-title">Cold-Start Problem</div>
      <div class="problem-desc">New users and newly listed products receive irrelevant or absent recommendations, causing high early-stage churn and missed revenue.</div>
      <div class="problem-tag">Recommendation</div>
    </div>
    <div class="problem-card reveal">
      <div class="problem-num">02</div>
      <div class="problem-icon">⚖️</div>
      <div class="problem-title">Algorithmic Bias</div>
      <div class="problem-desc">Demographic skew in collaborative filtering models leads to unfair product visibility, disproportionately disadvantaging minority groups.</div>
      <div class="problem-tag">Fairness & Ethics</div>
    </div>
    <div class="problem-card reveal">
      <div class="problem-num">03</div>
      <div class="problem-icon">🔒</div>
      <div class="problem-title">Data Privacy Crisis</div>
      <div class="problem-desc">Centralized data aggregation across social commerce platforms creates systemic GDPR exposure and user trust erosion at scale.</div>
      <div class="problem-tag">Privacy & Security</div>
    </div>
    <div class="problem-card reveal">
      <div class="problem-num">04</div>
      <div class="problem-icon">💸</div>
      <div class="problem-title">Static Pricing Models</div>
      <div class="problem-desc">Reactive, rule-based pricing systems fail to capture dynamic demand signals, leaving significant revenue on the table during peak events.</div>
      <div class="problem-tag">Revenue Optimization</div>
    </div>
    <div class="problem-card reveal">
      <div class="problem-num">05</div>
      <div class="problem-icon">🌐</div>
      <div class="problem-title">Siloed Data Ecosystems</div>
      <div class="problem-desc">Fragmentation across Instagram, TikTok, Pinterest, and Amazon prevents holistic user intent modeling and cross-platform intelligence.</div>
      <div class="problem-tag">Data Integration</div>
    </div>
    <div class="problem-card reveal">
      <div class="problem-num">06</div>
      <div class="problem-icon">🎭</div>
      <div class="problem-title">Fake Reviews & Fraud</div>
      <div class="problem-desc">Synthetic review injection and bot-driven engagement manipulation undermine platform trust, with existing detectors achieving less than 72% F1.</div>
      <div class="problem-tag">Trust & Safety</div>
    </div>
  </div>
</section>

<!-- ══ FEATURED SHOWCASE ══ -->
<div class="featured-showcase">
  <img src="https://images.unsplash.com/photo-1518770660439-4636190af475?w=1600&auto=format&fit=crop&q=80" alt="Technology Background" />
  <div class="featured-overlay">
    <div class="featured-content reveal">
      <h2>Solving Commerce<br><em>with Intelligence</em></h2>
      <p>A multi-layered AI framework addressing every layer of the social commerce stack — from data ingestion to real-time personalization, pricing, and trust enforcement.</p>
    </div>
  </div>
</div>

<!-- ══ SOLUTIONS ══ -->
<section class="solutions" id="solutions">
  <div class="reveal">
    <div class="section-label">Proposed Framework</div>
    <h2 class="section-title">AISCOF — Six <em>AI Solutions</em><br>for Modern Commerce</h2>
  </div>
  <div class="solutions-grid">
    <div class="solution-card reveal">
      <div class="solution-icon-wrap">🧠</div>
      <div>
        <div class="solution-title">Hybrid Recommendation Engine</div>
        <div class="solution-desc">Fuses Neural Collaborative Filtering with Graph Attention Networks and content-based signals via meta-learning. Achieves 93.2% Precision@10, handling cold-start via few-shot adaptation.</div>
        <div class="solution-tech">PyTorch · DGL · HuggingFace · LightGCN</div>
      </div>
    </div>
    <div class="solution-card reveal">
      <div class="solution-icon-wrap">💬</div>
      <div>
        <div class="solution-title">NLP Sentiment & Review Engine</div>
        <div class="solution-desc">Fine-tuned multilingual BERT for aspect-level sentiment analysis. Detects fake reviews using LSTM classifier (91.3% accuracy). Generates personalized descriptions via GPT-4.</div>
        <div class="solution-tech">BERT · SpaCy · NLTK · GPT-4 API</div>
      </div>
    </div>
    <div class="solution-card reveal">
      <div class="solution-icon-wrap">🛡️</div>
      <div>
        <div class="solution-title">Federated Privacy Layer</div>
        <div class="solution-desc">On-device training with differential privacy noise injection and secure aggregation. Maintains 94% recommendation quality with zero raw data sharing — GDPR compliant by design.</div>
        <div class="solution-tech">PySyft · Flower · DP-SGD · TensorFlow Federated</div>
      </div>
    </div>
    <div class="solution-card reveal">
      <div class="solution-icon-wrap">📈</div>
      <div>
        <div class="solution-title">Reinforcement Learning Pricing</div>
        <div class="solution-desc">Dueling DQN agent learns optimal pricing from historical transactions. LSTM demand forecasting feeds real-time signals, maximizing cumulative revenue over a 30-day horizon (+23% GMV).</div>
        <div class="solution-tech">Stable-Baselines3 · OpenAI Gym · LSTM · MLflow</div>
      </div>
    </div>
    <div class="solution-card reveal">
      <div class="solution-icon-wrap">👁️</div>
      <div>
        <div class="solution-title">Multi-Modal Search & Vision</div>
        <div class="solution-desc">ResNet-50 visual similarity search combined with transformer cross-modal embeddings for text + image + voice unified search. Enables style compatibility scoring across 50M+ SKUs.</div>
        <div class="solution-tech">ResNet-50 · CLIP · OpenCV · Elasticsearch</div>
      </div>
    </div>
    <div class="solution-card reveal">
      <div class="solution-icon-wrap">🕸️</div>
      <div>
        <div class="solution-title">Social Trust Graph Neural Net</div>
        <div class="solution-desc">GNN models peer influence and social proof across platform interaction graphs. Isolation Forest anomaly detection enforces fraud protection with 0.89 F1-score on benchmark datasets.</div>
        <div class="solution-tech">DGL · PyG · Isolation Forest · Kafka</div>
      </div>
    </div>
  </div>
</section>

<!-- ══ METRICS ══ -->
<div class="metrics" id="results">
  <div class="metrics-left reveal">
    <div class="section-label">Experimental Results</div>
    <h2 class="section-title">Numbers That <em>Speak</em></h2>
    <div class="gold-line"></div>
    <p>Evaluated across three real-world social commerce datasets spanning 2.4M users and 18M products. AISCOF outperforms all single-technique baselines across every measured KPI with statistical significance (p &lt; 0.01).</p>
  </div>
  <div class="metrics-right">
    <div class="metric-box reveal">
      <div class="metric-value">93.2<span class="metric-unit">%</span></div>
      <div class="metric-label">Precision @ 10</div>
      <div class="metric-change">↑ vs 71% baseline</div>
    </div>
    <div class="metric-box reveal">
      <div class="metric-value">6.1<span class="metric-unit">%</span></div>
      <div class="metric-label">Conversion Rate</div>
      <div class="metric-change">↑ from 3.1% baseline</div>
    </div>
    <div class="metric-box reveal">
      <div class="metric-value">+41<span class="metric-unit">%</span></div>
      <div class="metric-label">User Retention</div>
      <div class="metric-change">↑ improvement over baseline</div>
    </div>
    <div class="metric-box reveal">
      <div class="metric-value">94<span class="metric-unit">ms</span></div>
      <div class="metric-label">API Latency (p99)</div>
      <div class="metric-change">↓ from 380ms baseline</div>
    </div>
  </div>
</div>

<!-- ══ IMAGE STRIP ══ -->
<div class="image-strip">
  <div class="strip-item">
    <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?w=600&auto=format&fit=crop&q=80" alt="Analytics" />
    <div class="strip-item-label">Data Analytics</div>
  </div>
  <div class="strip-item">
    <img src="https://images.unsplash.com/photo-1563986768609-322da13575f3?w=600&auto=format&fit=crop&q=80" alt="Commerce" />
    <div class="strip-item-label">Social Commerce</div>
  </div>
  <div class="strip-item">
    <img src="https://images.unsplash.com/photo-1677442135703-1787eea5ce01?w=600&auto=format&fit=crop&q=80" alt="AI" />
    <div class="strip-item-label">Artificial Intelligence</div>
  </div>
  <div class="strip-item">
    <img src="https://images.unsplash.com/photo-1558618666-fcd25c85cd64?w=600&auto=format&fit=crop&q=80" alt="Technology" />
    <div class="strip-item-label">Deep Learning</div>
  </div>
</div>

<!-- ══ MODULES ══ -->
<section class="modules" id="modules">
  <div class="reveal">
    <div class="section-label">System Architecture</div>
    <h2 class="section-title">Eight Research <em>Modules</em></h2>
  </div>
  <div class="modules-grid">
    <div class="module-card reveal" data-progress="88">
      <div class="module-num">M — 01</div>
      <div class="module-title">Data Collection & Preprocessing</div>
      <div class="module-desc">APIs, web scraping, Apache Spark pipelines, feature engineering across 15+ platforms.</div>
      <div class="module-bar"><div class="module-bar-fill" style="width:88%"></div></div>
    </div>
    <div class="module-card reveal" data-progress="93">
      <div class="module-num">M — 02</div>
      <div class="module-title">Hybrid Recommender Engine</div>
      <div class="module-desc">Neural CF + GAT + meta-learning for cold-start. Ensemble voting across all signal types.</div>
      <div class="module-bar"><div class="module-bar-fill" style="width:93%"></div></div>
    </div>
    <div class="module-card reveal" data-progress="91">
      <div class="module-num">M — 03</div>
      <div class="module-title">NLP & Sentiment Analysis</div>
      <div class="module-desc">Multilingual BERT fine-tuning, aspect mining, fake review detection, description generation.</div>
      <div class="module-bar"><div class="module-bar-fill" style="width:91%"></div></div>
    </div>
    <div class="module-card reveal" data-progress="82">
      <div class="module-num">M — 04</div>
      <div class="module-title">Computer Vision Module</div>
      <div class="module-desc">ResNet-50 similarity, attribute extraction, CLIP-based cross-modal product understanding.</div>
      <div class="module-bar"><div class="module-bar-fill" style="width:82%"></div></div>
    </div>
    <div class="module-card reveal" data-progress="86">
      <div class="module-num">M — 05</div>
      <div class="module-title">RL Pricing Engine</div>
      <div class="module-desc">Dueling DQN agent, LSTM demand forecasting, automated A/B test reward shaping.</div>
      <div class="module-bar"><div class="module-bar-fill" style="width:86%"></div></div>
    </div>
    <div class="module-card reveal" data-progress="89">
      <div class="module-num">M — 06</div>
      <div class="module-title">Trust & Fraud Detection</div>
      <div class="module-desc">GNN social scoring, Isolation Forest anomaly detection, behavioral biometric auth.</div>
      <div class="module-bar"><div class="module-bar-fill" style="width:89%"></div></div>
    </div>
    <div class="module-card reveal" data-progress="78">
      <div class="module-num">M — 07</div>
      <div class="module-title">Federated Learning Layer</div>
      <div class="module-desc">On-device training, differential privacy, secure aggregation, GDPR-compliant by design.</div>
      <div class="module-bar"><div class="module-bar-fill" style="width:78%"></div></div>
    </div>
    <div class="module-card reveal" data-progress="95">
      <div class="module-num">M — 08</div>
      <div class="module-title">API Gateway & Deployment</div>
      <div class="module-desc">FastAPI microservices, Kubernetes auto-scaling, MLflow tracking, real-time monitoring.</div>
      <div class="module-bar"><div class="module-bar-fill" style="width:95%"></div></div>
    </div>
  </div>
</section>

<!-- ══ PUBLICATIONS ══ -->
<section class="publications" id="publications">
  <div class="reveal">
    <div class="section-label">Academic Contributions</div>
    <h2 class="section-title">Research <em>Publications</em></h2>
  </div>
  <div class="pub-list">
    <div class="pub-item reveal">
      <div class="pub-year">2025</div>
      <div>
        <div class="pub-venue">AAAI 2026 — San Francisco, CA</div>
        <div class="pub-title">Privacy-Preserving Social Commerce Recommendations via Federated Graph Learning</div>
        <div class="pub-authors">King et al. — Department of Computer Science & Engineering</div>
      </div>
      <span class="pub-badge badge-accepted">Accepted</span>
    </div>
    <div class="pub-item reveal">
      <div class="pub-year">2025</div>
      <div>
        <div class="pub-venue">ACM RecSys 2025 — Singapore</div>
        <div class="pub-title">Addressing Cold-Start in Social E-Commerce with Meta-Learning</div>
        <div class="pub-authors">King et al. — Department of Computer Science & Engineering</div>
      </div>
      <span class="pub-badge badge-published">Published</span>
    </div>
    <div class="pub-item reveal">
      <div class="pub-year">2025</div>
      <div>
        <div class="pub-venue">IEEE Transactions on Neural Networks and Learning Systems</div>
        <div class="pub-title">Hybrid Neural Collaborative Filtering for Social Commerce Personalization</div>
        <div class="pub-authors">King et al. — Department of Computer Science & Engineering</div>
      </div>
      <span class="pub-badge badge-review">Under Review</span>
    </div>
    <div class="pub-item reveal">
      <div class="pub-year">2025</div>
      <div>
        <div class="pub-venue">NeurIPS 2025 Workshop — ML in Commerce</div>
        <div class="pub-title">Reinforcement Learning for Dynamic Pricing in Social Marketplaces</div>
        <div class="pub-authors">King et al. — Department of Computer Science & Engineering</div>
      </div>
      <span class="pub-badge badge-poster">Poster</span>
    </div>
  </div>
</section>

<!-- ══ TECH STACK ══ -->
<div class="tech-stack">
  <div class="tech-label">Technology Stack</div>
  <div class="tech-tags">
    <span class="tech-tag">PyTorch 2.x</span>
    <span class="tech-tag">TensorFlow 2.x</span>
    <span class="tech-tag">HuggingFace</span>
    <span class="tech-tag">BERT</span>
    <span class="tech-tag">DGL</span>
    <span class="tech-tag">PyG</span>
    <span class="tech-tag">LightGCN</span>
    <span class="tech-tag">Stable-Baselines3</span>
    <span class="tech-tag">FastAPI</span>
    <span class="tech-tag">Django REST</span>
    <span class="tech-tag">Kubernetes</span>
    <span class="tech-tag">Docker</span>
    <span class="tech-tag">MLflow</span>
    <span class="tech-tag">Apache Kafka</span>
    <span class="tech-tag">PostgreSQL</span>
    <span class="tech-tag">Redis</span>
    <span class="tech-tag">Elasticsearch</span>
    <span class="tech-tag">PySyft</span>
    <span class="tech-tag">Flower FL</span>
    <span class="tech-tag">ResNet-50</span>
    <span class="tech-tag">CLIP</span>
    <span class="tech-tag">OpenCV</span>
    <span class="tech-tag">GPT-4 API</span>
    <span class="tech-tag">AWS / GCP</span>
  </div>
</div>

<!-- ══ CONTACT ══ -->
<div class="contact-cta" id="contact">
  <div class="contact-left">
    <div class="section-label">Get In Touch</div>
    <h2>Collaborate on <em>Future Research</em></h2>
    <p>Interested in the AISCOF framework, collaboration opportunities, or deploying AI solutions for your commerce platform? Reach out below.</p>
    <form class="contact-form" onsubmit="return false;">
      <div class="form-row">
        <input type="text" class="form-input" placeholder="Your Name" />
        <input type="email" class="form-input" placeholder="Email Address" />
      </div>
      <input type="text" class="form-input" placeholder="Subject / Research Interest" />
      <textarea class="form-input form-textarea" placeholder="Your message or collaboration proposal..."></textarea>
      <button class="btn-submit" type="submit">Send Message →</button>
    </form>
  </div>
  <div class="contact-right">
    <img src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?w=900&auto=format&fit=crop&q=80" alt="Collaboration" />
  </div>
</div>

<!-- ══ FOOTER ══ -->
<footer>
  <div class="footer-logo">KING ♛</div>
  <div class="footer-copy">© 2025 King — Social E-Commerce AI Research. All rights reserved.</div>
  <div class="footer-links">
    <a href="#home">Home</a>
    <a href="#about">Research</a>
    <a href="#publications">Publications</a>
    <a href="#contact">Contact</a>
  </div>
</footer>

<script>
  // ── CURSOR ──
  const cursor = document.getElementById('cursor');
  const ring = document.getElementById('cursorRing');
  let mx = 0, my = 0, rx = 0, ry = 0;
  document.addEventListener('mousemove', e => { mx = e.clientX; my = e.clientY; });
  function animateCursor() {
    cursor.style.left = mx + 'px'; cursor.style.top = my + 'px';
    rx += (mx - rx) * 0.12; ry += (my - ry) * 0.12;
    ring.style.left = rx + 'px'; ring.style.top = ry + 'px';
    requestAnimationFrame(animateCursor);
  }
  animateCursor();
  document.querySelectorAll('a, button, .problem-card, .solution-card, .module-card').forEach(el => {
    el.addEventListener('mouseenter', () => {
      cursor.style.width = '20px'; cursor.style.height = '20px';
      cursor.style.background = 'var(--teal)';
      ring.style.width = '56px'; ring.style.height = '56px';
    });
    el.addEventListener('mouseleave', () => {
      cursor.style.width = '10px'; cursor.style.height = '10px';
      cursor.style.background = 'var(--gold)';
      ring.style.width = '36px'; ring.style.height = '36px';
    });
  });

  // ── SCROLL REVEAL ──
  const reveals = document.querySelectorAll('.reveal');
  const observer = new IntersectionObserver((entries) => {
    entries.forEach((entry, i) => {
      if (entry.isIntersecting) {
        setTimeout(() => entry.target.classList.add('visible'), i * 80);
        observer.unobserve(entry.target);
      }
    });
  }, { threshold: 0.1 });
  reveals.forEach(el => observer.observe(el));

  // ── NAV SCROLL EFFECT ──
  const nav = document.querySelector('nav');
  window.addEventListener('scroll', () => {
    if (window.scrollY > 60) {
      nav.style.background = 'rgba(8,8,18,0.97)';
      nav.style.backdropFilter = 'blur(12px)';
    } else {
      nav.style.background = 'linear-gradient(to bottom, rgba(8,8,18,0.95) 0%, transparent 100%)';
      nav.style.backdropFilter = 'blur(2px)';
    }
  });

  // ── COUNTER ANIMATION ──
  function animateCounter(el, target, suffix = '') {
    let start = 0;
    const duration = 1800;
    const step = timestamp => {
      if (!start) start = timestamp;
      const progress = Math.min((timestamp - start) / duration, 1);
      const ease = 1 - Math.pow(1 - progress, 3);
      el.textContent = (target * ease).toFixed(target % 1 !== 0 ? 1 : 0) + suffix;
      if (progress < 1) requestAnimationFrame(step);
    };
    requestAnimationFrame(step);
  }

  const statObserver = new IntersectionObserver(entries => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        const nums = entry.target.querySelectorAll('.metric-value');
        nums.forEach(n => {
          const raw = n.textContent.replace(/[^0-9.]/g, '');
          const val = parseFloat(raw);
          if (!isNaN(val)) animateCounter(n, val);
        });
        statObserver.unobserve(entry.target);
      }
    });
  }, { threshold: 0.3 });
  document.querySelectorAll('.metrics-right').forEach(el => statObserver.observe(el));

  // ── HERO NUMBER COUNTER ──
  const heroNums = document.querySelectorAll('.stat-num');
  heroNums.forEach(n => {
    const raw = n.textContent.replace(/[^0-9.]/g, '');
    const val = parseFloat(raw);
    if (!isNaN(val)) {
      setTimeout(() => animateCounter(n, val), 600);
    }
  });

  // ── MODULE BAR ANIMATION ──
  const barObserver = new IntersectionObserver(entries => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        const bar = entry.target.querySelector('.module-bar-fill');
        if (bar) {
          const w = bar.style.width;
          bar.style.width = '0';
          setTimeout(() => bar.style.width = w, 200);
        }
        barObserver.unobserve(entry.target);
      }
    });
  }, { threshold: 0.4 });
  document.querySelectorAll('.module-card').forEach(el => barObserver.observe(el));

  // ── SMOOTH SCROLL ──
  document.querySelectorAll('a[href^="#"]').forEach(a => {
    a.addEventListener('click', e => {
      e.preventDefault();
      const target = document.querySelector(a.getAttribute('href'));
      if (target) target.scrollIntoView({ behavior: 'smooth', block: 'start' });
    });
  });
</script>
</body>
</html>
