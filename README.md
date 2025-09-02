<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Ikramidin Zhakypaliev — Academic Website</title>
  <meta name="description" content="Academic homepage of Ikramidin Zhakypaliev — interests: political economy, semiconductor supply chains, Central Asia, climate & security." />
  <meta name="author" content="Ikramidin Zhakypaliev" />
  <meta property="og:title" content="Ikramidin Zhakypaliev — Academic Website" />
  <meta property="og:description" content="Political economy, IPE, semiconductor supply chains, climate & security in Central Asia." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="assets/profile.jpg" />
  <meta name="theme-color" content="#0e1217" />
  <link rel="icon" href="assets/favicon.ico" />
  <style>
    :root{
      --bg:#0e1217; --text:#e6e6e6; --muted:#9aa4b2; --card:#161b22; --acc:#5da9e9; --line:#283142; --link:#7dc4ff; --shadow:rgba(0,0,0,.35);
      --font: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji", "Segoe UI Emoji";
    }
    [data-theme="light"]{ --bg:#ffffff; --text:#181a1f; --muted:#49515c; --card:#f6f8fa; --acc:#0f62fe; --line:#e5e7eb; --link:#065cc6; --shadow:rgba(0,0,0,.08);} 
    html, body { height:100%; }
    body { margin:0; background:var(--bg); color:var(--text); font-family:var(--font); line-height:1.6; }
    a { color:var(--link); text-decoration:none; }
    a:hover{ text-decoration:underline; }
    .container { max-width:1024px; margin:auto; padding:24px; }
    header { position:sticky; top:0; backdrop-filter: saturate(180%) blur(10px); background:color-mix(in oklab, var(--bg) 90%, transparent); border-bottom:1px solid var(--line); z-index:50; }
    .nav { display:flex; align-items:center; justify-content:space-between; gap:12px; padding:12px 0; }
    .nav a { padding:8px 10px; border-radius:12px; }
    .nav a:hover { background:var(--card); text-decoration:none; }
    .brand { display:flex; align-items:center; gap:14px; }
    .brand img { width:56px; height:56px; border-radius:50%; object-fit:cover; box-shadow:0 6px 22px var(--shadow); }
    .brand .name { font-weight:800; font-size:1.25rem; }
    .grid { display:grid; gap:20px; }
    @media (min-width:900px){ .grid-2{ grid-template-columns: 1.2fr .8fr; } }
    section { padding:28px 0; border-bottom:1px dashed var(--line); }
    h1{ font-size:2.1rem; margin:0 0 6px; }
    h2{ font-size:1.35rem; margin:0 0 12px; }
    h3{ font-size:1.05rem; margin:14px 0 6px; }
    p, li { color:var(--text); }
    .muted{ color:var(--muted); }
    .chip { display:inline-block; padding:6px 10px; border-radius:999px; background:var(--card); border:1px solid var(--line); margin:2px 6px 0 0; font-size:.86rem; }
    .card { background:var(--card); border:1px solid var(--line); border-radius:16px; padding:18px; box-shadow: 0 10px 30px var(--shadow); }
    .list{ margin:0; padding-left:18px; }
    .pub { margin:10px 0; }
    .pub .title{ font-weight:600; }
    .cta { display:inline-flex; align-items:center; gap:8px; padding:10px 14px; border-radius:12px; background:var(--acc); color:white; font-weight:700; text-decoration:none; box-shadow:0 10px 30px var(--shadow); }
    .cta:hover{ filter:brightness(1.05); text-decoration:none; }
    .toolbar { display:flex; align-items:center; gap:10px; flex-wrap:wrap; }
    .right { text-align:right; }
    .foot { display:flex; flex-wrap:wrap; justify-content:space-between; gap:14px; font-size:.95rem; }
    .kicker { color:var(--muted); text-transform:uppercase; letter-spacing:.08em; font-size:.8rem; }
    .project-grid{ display:grid; gap:14px; grid-template-columns: repeat(auto-fill, minmax(240px, 1fr)); }
    .project{ padding:14px; border:1px solid var(--line); border-radius:14px; background:var(--card); }
    .project h3{ margin:0 0 6px; font-size:1rem; }
    .badge { font-size:.78rem; padding:3px 8px; border:1px solid var(--line); border-radius:999px; background:transparent; color:var(--muted); }
    .sr-only{ position:absolute; width:1px; height:1px; padding:0; margin:-1px; overflow:hidden; clip:rect(0,0,0,0); white-space:nowrap; border:0; }
    @media print{ header{ position:static; } .cta, .toolbar { display:none; } body{ background:white; color:black; } }
  </style>
</head>
<body>
  <a class="sr-only" href="#main">Skip to content</a>
  <header>
    <div class="container nav">
      <div class="brand">
        <img src="assets/profile.jpg" alt="Portrait of Ikramidin Zhakypaliev" />
        <div>
          <div class="name">Ikramidin Zhakypaliev</div>
          <div class="muted">Political Economy • IPE • Semiconductor Supply Chains • Central Asia</div>
        </div>
      </div>
      <nav class="toolbar">
        <a href="#about">About</a>
        <a href="#research">Research</a>
        <a href="#publications">Publications</a>
        <a href="#teaching">Teaching</a>
        <a href="#talks">Talks</a>
        <a href="#contact">Contact</a>
        <button id="themeToggle" aria-label="Toggle dark mode" style="padding:8px 10px;border-radius:12px;border:1px solid var(--line);background:transparent;color:var(--text);cursor:pointer">🌓</button>
      </nav>
    </div>
  </header>

  <main id="main" class="container grid grid-2">
    <section id="about">
      <p class="kicker">Profile</p>
      <h1>About</h1>
      <p>
        I am an <strong>IMPACT Climate & DRR Assessment Assistant</strong> at Acted Kyrgyzstan and researcher in International Political Economy. My research explores the geopolitics of the
        <em>semiconductor supply chain</em>, climate–security linkages, and development in Central Asia. Previously at OSCE Academy projects; incoming applicant to PhD programs focusing on political economy and technology.
      </p>
      <div>
        <span class="chip">International Political Economy</span>
        <span class="chip">Semiconductor Supply Chains</span>
        <span class="chip">Climate & Security</span>
        <span class="chip">Central Asia</span>
        <span class="chip">Data Visualization</span>
      </div>
      <p style="margin-top:12px" class="toolbar">
        <a class="cta" href="cv/Ikramidin_Zhakypaliev_CV.pdf" target="_blank" rel="noopener">Download CV</a>
        <a href="https://scholar.google.com" target="_blank" rel="noopener">Google Scholar</a>
        <a href="https://orcid.org" target="_blank" rel="noopener">ORCID</a>
        <a href="https://github.com" target="_blank" rel="noopener">GitHub</a>
        <a href="https://www.linkedin.com" target="_blank" rel="noopener">LinkedIn</a>
      </p>
    </section>

    <aside aria-label="News & Highlights">
      <section class="card">
        <p class="kicker">News</p>
        <h2>Recent</h2>
        <ul class="list">
          <li><strong>Sep 2025</strong> — Planning CBS trainings in Kyrgyzstan, Tajikistan, Uzbekistan.</li>
          <li><strong>Aug 2025</strong> — Revising community-based monitoring analysis plan.</li>
          <li><strong>Apr 2025</strong> — Drafting PhD proposal on climate–aid–security in Fergana Valley.</li>
        </ul>
      </section>
      <section class="card" style="margin-top:16px">
        <p class="kicker">Quick Links</p>
        <ul class="list">
          <li><a href="#publications">Selected publications</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#teaching">Teaching materials</a></li>
        </ul>
      </section>
    </aside>

    <section id="research">
      <p class="kicker">Research</p>
      <h2>Research Interests</h2>
      <p>Political economy of technology; regional integration; climate adaptation and security; water governance; Central Asian studies.</p>
      <div id="projects" class="project-grid" aria-label="Project list">
        <article class="project">
          <h3>Semiconductor Supply Chains & Geopolitics</h3>
          <p class="muted">Mapping chokepoints, policy risks, and resilience strategies.</p>
          <span class="badge">Working Paper</span>
        </article>
        <article class="project">
          <h3>Fergana Valley Climate–Aid–Security</h3>
          <p class="muted">How adaptation finance affects conflict risk and cooperation.</p>
          <span class="badge">PhD Proposal</span>
        </article>
        <article class="project">
          <h3>Community-Based Monitoring</h3>
          <p class="muted">Water meters, irrigation governance, and local capacity.</p>
          <span class="badge">Fieldwork</span>
        </article>
      </div>
    </section>

    <section id="publications">
      <p class="kicker">Publications</p>
      <h2>Selected Publications & Writing</h2>
      <ol class="list">
        <li class="pub">
          <span class="title">Turkey's Soft Power in Central Asia</span> — Master's thesis (Year). <a href="#">PDF</a>
        </li>
        <li class="pub">
          <span class="title">China and Regional Economic Integration</span> — Bachelor's thesis (Year). <a href="#">PDF</a>
        </li>
        <li class="pub">
          <span class="title">Climate Risks & Water Governance in the Fergana Valley</span> — Policy memo, (Year). <a href="#">Link</a>
        </li>
      </ol>
    </section>

    <section id="teaching">
      <p class="kicker">Teaching</p>
      <h2>Courses & Materials</h2>
      <ul class="list">
        <li><strong>Nation, State, and Nationalism</strong> — Undergraduate syllabus, Manas University. <a href="#">Syllabus</a></li>
        <li><strong>International Political Economy</strong> — Course outline and readings. <a href="#">Syllabus</a></li>
      </ul>
    </section>

    <section id="talks">
      <p class="kicker">Talks</p>
      <h2>Invited Talks & Conferences</h2>
      <ul class="list">
        <li>"Water, Technology, and Security in Central Asia" — Workshop, (Year).</li>
        <li>"Semiconductor Governance in Emerging Economies" — Seminar, (Year).</li>
      </ul>
    </section>

    <section id="service">
      <p class="kicker">Service</p>
      <h2>Academic & Professional Service</h2>
      <ul class="list">
        <li>Reviewer, Journal/Conference (Year–present).</li>
        <li>Organizer, Climate & DRR community training (Year).</li>
      </ul>
    </section>

    <section id="contact">
      <p class="kicker">Contact</p>
      <h2>Get in Touch</h2>
      <p>Email: <a href="mailto:firstname.lastname@university.edu">firstname.lastname@university.edu</a> · Office: Bishkek, KG</p>
      <p>Social: <a href="#">Google Scholar</a> · <a href="#">ORCID</a> · <a href="#">GitHub</a> · <a href="#">LinkedIn</a></p>
    </section>
  </main>

  <footer class="container foot">
    <div>© <span id="year"></span> Ikramidin Zhakypaliev</div>
    <div class="muted">Built with plain HTML/CSS • Dark/Light mode • Accessible</div>
  </footer>

  <!-- JSON-LD structured data for better academic SEO -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Ikramidin Zhakypaliev",
    "jobTitle": "Researcher",
    "affiliation": {"@type": "Organization", "name": "Acted Kyrgyzstan"},
    "url": "https://yourusername.github.io/",
    "image": "https://yourusername.github.io/assets/profile.jpg",
    "sameAs": [
      "https://scholar.google.com/", 
      "https://orcid.org/", 
      "https://github.com/yourusername",
      "https://www.linkedin.com/"
    ],
    "knowsAbout": ["International Political Economy", "Semiconductor Supply Chains", "Central Asia", "Climate & Security"]
  }
  </script>

  <script>
    // Current year
    document.getElementById('year').textContent = new Date().getFullYear();

    // Theme toggle with localStorage
    const root = document.documentElement;
    const key = 'pref-theme';
    const saved = localStorage.getItem(key);
    if(saved){
      document.documentElement.setAttribute('data-theme', saved);
    } else if (window.matchMedia && window.matchMedia('(prefers-color-scheme: light)').matches) {
      document.documentElement.setAttribute('data-theme', 'light');
    }
    document.getElementById('themeToggle').addEventListener('click', () => {
      const cur = document.documentElement.getAttribute('data-theme') === 'light' ? 'dark' : 'light';
      document.documentElement.setAttribute('data-theme', cur);
      localStorage.setItem(key, cur);
    });

    // Smooth scroll for anchor links
    document.querySelectorAll('a[href^="#"]').forEach(a => {
      a.addEventListener('click', e => {
        const id = a.getAttribute('href').slice(1);
        const el = document.getElementById(id);
        if(el){ e.preventDefault(); el.scrollIntoView({behavior:'smooth', block:'start'}); }
      });
    });
  </script>
</body>
</html>
