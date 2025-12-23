
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>TERROR SMP — Season 8 Winter</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
  :root {
    --red: #d62828;
    --red-soft: #ff595e;
    --bg-dark: #050505;
    --bg-card: rgba(255,255,255,0.04);
    --border: rgba(255,255,255,0.08);
    --text: #eaeaea;
    --text-muted: #9a9a9a;
  }

  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Inter", "Segoe UI", sans-serif;
  }

  body {
    background: linear-gradient(125deg, #080808, #0c0c0c);
    color: var(--text);
    overflow-x: hidden;
  }

  /* ===== NAVBAR ===== */
  nav {
    position: sticky;
    top: 0;
    background: rgba(10,10,10,0.7);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid var(--border);
    z-index: 10;
  }
  .nav-inner {
    max-width: 1200px;
    margin: auto;
    padding: 18px 22px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .logo {
    font-size: 1.4rem;
    font-weight: 800;
    letter-spacing: 2px;
    color: var(--red);
  }
  .links a {
    margin-left: 28px;
    text-decoration: none;
    color: var(--text-muted);
    font-size: 0.9rem;
    transition: 0.25s;
  }
  .links a:hover { color: var(--red-soft); }

  /* ===== HERO ===== */
  header {
    padding: 130px 20px 150px;
    text-align: center;
  }

  .hero-title {
    font-size: clamp(2.8rem, 5vw, 4rem);
    font-weight: 900;
    letter-spacing: 3px;
    color: var(--red);
  }
  .hero-sub {
    margin-top: 14px;
    font-size: 0.95rem;
    color: var(--text-muted);
    letter-spacing: 4px;
    text-transform: uppercase;
  }
  .hero-desc {
    margin: 32px auto 0;
    max-width: 700px;
    color: var(--text-muted);
    line-height: 1.7;
  }

  /* ---- Premium Divider Line ---- */
  .divider {
    width: 100px;
    height: 3px;
    margin: 45px auto;
    background: var(--red);
    border-radius: 999px;
    box-shadow: 0 0 10px var(--red-soft);
  }

  /* ===== SECTION TITLE ===== */
  .section-title {
    text-align: center;
    font-size: 2rem;
    font-weight: 700;
    margin-bottom: 15px;
  }
  .section-sub {
    text-align: center;
    max-width: 700px;
    color: var(--text-muted);
    margin: 0 auto 60px;
    line-height: 1.6;
  }

  /* ===== FEATURES ===== */
  .features {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 26px;
    max-width: 1200px;
    margin: auto;
    padding: 0 20px;
  }

  .card {
    padding: 28px;
    border: 1px solid var(--border);
    border-radius: 14px;
    background: var(--bg-card);
    transition: 0.3s;
  }

  .card:hover {
    border-color: var(--red-soft);
    box-shadow: 0 0 20px rgba(214,40,40,0.25);
    transform: translateY(-4px);
  }

  .card h3 {
    font-size: 1.15rem;
    color: var(--red);
    margin-bottom: 10px;
  }
  .card p {
    color: var(--text-muted);
    font-size: 0.9rem;
    line-height: 1.6;
  }

  /* ===== STRIP SECTION ===== */
  .strip {
    margin-top: 120px;
    padding: 80px 20px;
    background: linear-gradient(90deg, rgba(214,40,40,0.04), rgba(255,255,255,0.01));
    border-top: 1px solid var(--border);
    border-bottom: 1px solid var(--border);
    text-align: center;
  }

  .strip h2 {
    font-size: 2rem;
    margin-bottom: 15px;
  }
  .strip p {
    max-width: 780px;
    margin: auto;
    line-height: 1.7;
    color: var(--text-muted);
  }

  /* ===== FOOTER ===== */
  footer {
    padding: 50px 20px;
    text-align: center;
    border-top: 1px solid var(--border);
    margin-top: 100px;
  }
  footer p {
    font-size: 0.8rem;
    color: var(--text-muted);
  }

</style>
</head>

<body>

<nav>
  <div class="nav-inner">
    <div class="logo">TERROR SMP</div>
    <div class="links">
      <a href="#">HOME</a>
      <a href="#">ABOUT</a>
      <a href="#">S8 FEATURES</a>
      <a href="#">DISCORD</a>
    </div>
  </div>
</nav>

<header>
  <div class="hero-title">TERROR SMP — S8</div>
  <div class="hero-sub">Winter Era • Premium Survival Experience</div>
  <p class="hero-desc">
    A long-term, polished, studio-grade Minecraft SMP.
    Built for quality, community and a premium multiplayer experience.
    Designed for Malayali & Kerala players who want a smooth,
    professional and competitive SMP environment.
  </p>
</header>

<div class="divider"></div>

<section>
  <h2 class="section-title">What Makes Us Premium?</h2>
  <p class="section-sub">
    Clean gameplay. Balanced systems. No pay-to-win.  
    Just a pure, professional SMP designed to last years.
  </p>

  <div class="features">

    <div class="card">
      <h3>Long-Term Season</h3>
      <p>Season 8 is structured for year-long play with no resets unless needed.</p>
    </div>

    <div class="card">
      <h3>Winter Atmosphere</h3>
      <p>A dark, cold, minimal winter world giving the SMP a premium identity.</p>
    </div>

    <div class="card">
      <h3>Optimized Performance</h3>
      <p>Stable TPS, optimized plugins, and smooth chunk loading for all players.</p>
    </div>

    <div class="card">
      <h3>Geyser Compatible</h3>
      <p>Full Bedrock + Java support without performance loss.</p>
    </div>

    <div class="card">
      <h3>No Pay-to-Win</h3>
      <p>Only cosmetics/QoL — no gameplay advantage for money.</p>
    </div>

    <div class="card">
      <h3>Community First</h3>
      <p>Friendly Malayali player base with events, clans and alliances.</p>
    </div>

  </div>
</section>

<div class="strip">
  <h2>S8 Winter Era Has Begun</h2>
  <p>
    A new identity for TERROR SMP.  
    Cleaner. Stronger. More professional than ever.  
    This is not a short seasonal SMP — this is a long-term world meant to evolve.
  </p>
</div>

<footer>
  <p>© 2025 TERROR SMP — Season 8 Winter Edition</p>
</footer>

</body>
</html>
