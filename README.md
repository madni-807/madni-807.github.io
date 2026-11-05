<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#071525">
<meta name="description" content="Muhammad Madni - Electrical Engineer specializing in power generation, industrial electrical systems, protection and maintenance.">
<title>Muhammad Madni | Electrical Engineer</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700;800&family=Space+Grotesk:wght@400;500;600;700&display=swap" rel="stylesheet">

<style>
:root {
  --navy: #071525;
  --navy2: #0d2238;
  --gold: #d6aa55;
  --gold-light: #f1d18d;
  --white: #ffffff;
  --muted: #aab6c4;
  --light: #f4f6f9;
  --ink: #172538;
  --line: #e2e7ed;
  --max: 1160px;
}

* { margin:0; padding:0; box-sizing:border-box; }
html { scroll-behavior:smooth; scroll-padding-top:85px; }
body {
  font-family:'DM Sans',sans-serif;
  color:var(--ink);
  background:white;
  line-height:1.7;
}
a { text-decoration:none; color:inherit; }
button { font:inherit; }
.container { width:min(92%,var(--max)); margin:auto; }
.section { padding:95px 0; }
.section-light { background:var(--light); }
.section-dark { background:var(--navy); color:white; }

.eyebrow {
  color:#a8792e;
  font-size:.78rem;
  font-weight:800;
  letter-spacing:2.5px;
  text-transform:uppercase;
}
.section-title {
  font-family:'Space Grotesk',sans-serif;
  font-size:clamp(2rem,4vw,3rem);
  line-height:1.2;
  margin:10px 0 15px;
  letter-spacing:-1.5px;
}
.section-intro {
  max-width:690px;
  color:#69788a;
  margin-bottom:40px;
}
.section-dark .section-intro { color:var(--muted); }

header {
  position:fixed;
  inset:0 0 auto;
  z-index:1000;
  background:rgba(7,21,37,.96);
  border-bottom:1px solid rgba(255,255,255,.08);
  backdrop-filter:blur(14px);
}
.nav {
  height:76px;
  display:flex;
  align-items:center;
  justify-content:space-between;
}
.logo {
  font-family:'Space Grotesk',sans-serif;
  color:white;
  font-size:1.35rem;
  font-weight:700;
}
.logo span { color:var(--gold); }
.nav-links {
  display:flex;
  align-items:center;
  gap:27px;
  list-style:none;
}
.nav-links a {
  color:#d3dce6;
  font-size:.86rem;
  transition:.2s;
}
.nav-links a:hover { color:var(--gold-light); }
.nav-contact {
  border:1px solid var(--gold);
  padding:9px 17px;
  border-radius:4px;
}
.menu-toggle {
  display:none;
  background:none;
  border:0;
  color:white;
  font-size:1.8rem;
  cursor:pointer;
}

.hero {
  min-height:760px;
  padding:145px 0 80px;
  background:
    radial-gradient(circle at 82% 38%,rgba(214,170,85,.12),transparent 30%),
    linear-gradient(120deg,#071525,#102b46);
  color:white;
  position:relative;
  overflow:hidden;
}
.hero:after {
  content:"";
  position:absolute;
  right:-120px;
  bottom:-250px;
  width:560px;
  height:560px;
  border:1px solid rgba(214,170,85,.16);
  border-radius:50%;
  box-shadow:0 0 0 45px rgba(214,170,85,.025),
             0 0 0 90px rgba(214,170,85,.025);
}
.hero-grid {
  display:grid;
  grid-template-columns:1.3fr .7fr;
  align-items:center;
  gap:60px;
  position:relative;
  z-index:1;
}
.hero-tag {
  color:var(--gold-light);
  font-size:.82rem;
  font-weight:700;
  letter-spacing:2px;
  text-transform:uppercase;
  margin-bottom:20px;
}
.hero h1 {
  font-family:'Space Grotesk',sans-serif;
  font-size:clamp(3rem,7vw,5.4rem);
  line-height:1.05;
  letter-spacing:-3px;
  margin-bottom:18px;
}
.hero h1 span { color:var(--gold-light); }
.hero-role {
  font-size:1.08rem;
  color:#d3dce6;
  max-width:650px;
  margin-bottom:20px;
}
.hero-description {
  color:#aab9c9;
  max-width:600px;
  margin-bottom:32px;
}
.hero-actions {
  display:flex;
  flex-wrap:wrap;
  gap:14px;
}
.btn {
  display:inline-flex;
  align-items:center;
  justify-content:center;
  padding:13px 22px;
  border-radius:4px;
  font-weight:700;
  font-size:.9rem;
  transition:.25s;
  cursor:pointer;
}
.btn-gold { background:var(--gold); color:#101b29; }
.btn-gold:hover { background:var(--gold-light); transform:translateY(-3px); }
.btn-outline { border:1px solid #8494a6; color:white; }
.btn-outline:hover { border-color:var(--gold); color:var(--gold-light); }

.profile-wrap {
  display:flex;
  justify-content:center;
  position:relative;
}
.profile-frame {
  width:min(340px,100%);
  aspect-ratio:4/5;
  border:1px solid rgba(214,170,85,.7);
  padding:9px;
  position:relative;
  background:rgba(255,255,255,.04);
}
.profile-frame:before {
  content:"";
  position:absolute;
  inset:18px -15px -15px 18px;
  border:1px solid rgba(214,170,85,.3);
  z-index:-1;
}
.profile-frame img {
  width:100%;
  height:100%;
  object-fit:cover;
  object-position:center top;
  display:block;
}
.profile-placeholder {
  width:100%;
  height:100%;
  background:#19344d;
  display:grid;
  place-items:center;
  color:var(--gold-light);
  text-align:center;
  padding:25px;
}
.profile-placeholder span { font-size:4rem; display:block; }

.hero-stats {
  display:flex;
  gap:35px;
  flex-wrap:wrap;
  margin-top:55px;
}
.stat strong {
  display:block;
  color:var(--gold-light);
  font-family:'Space Grotesk',sans-serif;
  font-size:1.8rem;
}
.stat span { color:#aab9c9; font-size:.8rem; }

.about-grid {
  display:grid;
  grid-template-columns:1.1fr .9fr;
  gap:55px;
  align-items:start;
}
.about-text p { color:#617083; margin-bottom:17px; }
.about-highlight {
  border-left:3px solid var(--gold);
  background:#f6f7f9;
  padding:23px 25px;
  margin-top:24px;
  color:#394b60;
}
.info-card {
  background:white;
  border:1px solid var(--line);
  padding:28px;
  border-radius:7px;
}
.info-row {
  padding:13px 0;
  border-bottom:1px solid var(--line);
}
.info-row:last-child { border:0; }
.info-row small {
  display:block;
  color:#8390a0;
  text-transform:uppercase;
  font-size:.68rem;
  letter-spacing:1px;
  font-weight:700;
}
.info-row strong { font-size:.95rem; }

.experience-card {
  background:white;
  border:1px solid var(--line);
  border-radius:7px;
  padding:30px;
  position:relative;
  margin-bottom:20px;
}
.experience-card:before {
  content:"";
  position:absolute;
  top:0; left:0; bottom:0;
  width:4px;
  background:var(--gold);
  border-radius:7px 0 0 7px;
}
.experience-top {
  display:flex;
  justify-content:space-between;
  gap:20px;
  flex-wrap:wrap;
  margin-bottom:15px;
}
.experience-card h3 {
  font-family:'Space Grotesk',sans-serif;
  font-size:1.35rem;
}
.company { color:#9a702f; font-weight:700; }
.date {
  font-size:.82rem;
  color:#64748b;
  background:#f0f3f6;
  padding:5px 12px;
  border-radius:30px;
  height:max-content;
}
.experience-card p, .experience-card li { color:#64748b; font-size:.92rem; }
.experience-card ul { padding-left:20px; margin-top:12px; }
.experience-card li { margin:5px 0; }

.skills-grid {
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:18px;
}
.skill-card {
  padding:25px;
  background:#102941;
  border:1px solid rgba(255,255,255,.08);
  border-radius:6px;
  transition:.25s;
}
.skill-card:hover {
  transform:translateY(-5px);
  border-color:var(--gold);
}
.skill-icon { font-size:1.7rem; margin-bottom:12px; }
.skill-card h3 {
  color:white;
  font-family:'Space Grotesk',sans-serif;
  font-size:1.08rem;
  margin-bottom:9px;
}
.skill-card p { color:#aab9c9; font-size:.86rem; }

.tool-list {
  display:flex;
  flex-wrap:wrap;
  gap:12px;
  margin-top:28px;
}
.tool {
  border:1px solid rgba(214,170,85,.45);
  color:#f1d18d;
  padding:9px 17px;
  border-radius:3px;
  font-size:.88rem;
}
.tool small { color:#aab9c9; }

.project-card {
  display:grid;
  grid-template-columns:.8fr 1.2fr;
  gap:30px;
  align-items:center;
  background:white;
  border:1px solid var(--line);
  border-radius:7px;
  padding:30px;
}
.project-visual {
  min-height:235px;
  background:linear-gradient(140deg,#0c243b,#1b405c);
  display:grid;
  place-items:center;
  text-align:center;
  color:var(--gold-light);
  padding:25px;
}
.project-visual .symbol { font-size:3.2rem; }
.project-visual strong { display:block; margin-top:10px; }
.project-card p { color:#657487; margin:12px 0; }
.project-tags { display:flex; flex-wrap:wrap; gap:8px; margin-top:15px; }
.project-tags span {
  font-size:.75rem;
  background:#f0f3f6;
  padding:5px 10px;
  color:#43556b;
  border-radius:3px;
}

.gallery-grid {
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:18px;
}
.gallery-item {
  min-height:200px;
  border:1px dashed #b5c0cb;
  background:#f7f9fb;
  display:grid;
  place-items:center;
  text-align:center;
  padding:20px;
  color:#68798c;
  border-radius:5px;
}
.gallery-item span { font-size:2rem; display:block; }
.gallery-item strong { display:block; color:#283c52; margin:7px 0; }
.gallery-note { color:#8491a0; font-size:.8rem; margin-top:18px; }

.learning-grid {
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:15px;
}
.learning-item {
  padding:20px;
  border:1px solid var(--line);
  border-radius:5px;
  background:white;
}
.learning-item strong { display:block; margin-bottom:5px; }
.learning-item p { color:#6d7b8c; font-size:.88rem; }

.contact-grid {
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:45px;
}
.contact-details { display:grid; gap:15px; }
.contact-item {
  background:#102941;
  border:1px solid rgba(255,255,255,.08);
  padding:18px;
  border-radius:5px;
}
.contact-item small {
  color:var(--gold-light);
  display:block;
  text-transform:uppercase;
  letter-spacing:1px;
  font-size:.7rem;
  margin-bottom:5px;
}
.contact-item a { color:white; overflow-wrap:anywhere; }
.contact-message {
  border:1px solid rgba(214,170,85,.3);
  padding:28px;
  border-radius:6px;
  color:#b7c4d1;
}
.contact-message h3 {
  color:white;
  font-family:'Space Grotesk',sans-serif;
  font-size:1.5rem;
  margin-bottom:12px;
}

footer {
  background:#04101d;
  color:#8999aa;
  padding:25px 0;
  font-size:.82rem;
}
.footer-inner {
  display:flex;
  justify-content:space-between;
  flex-wrap:wrap;
  gap:12px;
}
footer strong { color:var(--gold-light); }

.reveal {
  opacity:0;
  transform:translateY(20px);
  transition:opacity .6s ease,transform .6s ease;
}
.reveal.visible { opacity:1; transform:translateY(0); }

@media(max-width:850px) {
  .menu-toggle { display:block; }
  .nav-links {
    display:none;
    position:absolute;
    top:76px; left:0; right:0;
    background:#071525;
    padding:20px 5%;
    flex-direction:column;
    align-items:flex-start;
    gap:18px;
  }
  .nav-links.active { display:flex; }
  .hero-grid,.about-grid,.contact-grid { grid-template-columns:1fr; }
  .hero-grid { gap:45px; }
  .profile-wrap { order:-1; }
  .profile-frame { width:250px; }
  .skills-grid { grid-template-columns:repeat(2,1fr); }
  .project-card { grid-template-columns:1fr; }
}
@media(max-width:560px) {
  .section { padding:70px 0; }
  .hero { min-height:auto; padding-top:125px; }
  .hero h1 { letter-spacing:-2px; }
  .skills-grid,.gallery-grid,.learning-grid { grid-template-columns:1fr; }
  .hero-stats { gap:22px; }
  .experience-card { padding:23px; }
  .footer-inner { flex-direction:column; }
}
</style>
</head>

<body>

<header>
  <nav class="nav container">
    <a href="#home" class="logo">MM<span>.</span></a>
    <button class="menu-toggle" id="menuToggle" aria-label="Toggle navigation">☰</button>
    <ul class="nav-links" id="navLinks">
      <li><a href="#about">About</a></li>
      <li><a href="#experience">Experience</a></li>
      <li><a href="#expertise">Expertise</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#gallery">Gallery</a></li>
      <li><a href="#contact" class="nav-contact">Contact</a></li>
    </ul>
  </nav>
</header>

<main>

<!-- HERO -->
<section class="hero" id="home">
  <div class="container hero-grid">
    <div>
      <div class="hero-tag">Electrical Engineer · Power & Industry</div>
      <h1>Muhammad<br><span>Madni.</span></h1>
      <p class="hero-role">
        Electrical Engineer | Power Generation | Industrial Electrical Systems |
        Protection & Maintenance
      </p>
      <p class="hero-description">
        Building practical engineering knowledge through industrial training,
        technical exploration and a commitment to reliable electrical power systems.
      </p>
      <div class="hero-actions">
        <a class="btn btn-gold" href="#experience">Explore My Journey</a>
        <a class="btn btn-outline"
           href="https://drive.google.com/file/d/1QA2pC1pNH7mWJDBzB1SvyrurNlGPT7oU/view?usp=drivesdk"
           target="_blank" rel="noopener">View My CV ↗</a>
      </div>
      <div class="hero-stats">
        <div class="stat"><strong>2026</strong><span>Graduate</span></div>
        <div class="stat"><strong>E&I</strong><span>Training Department</span></div>
        <div class="stat"><strong>01</strong><span>Engineering Mindset</span></div>
      </div>
    </div>

    <div class="profile-wrap">
      <div class="profile-frame">
        <img src="assets/profile.jpg" alt="Muhammad Madni - Electrical Engineer"
             onerror="this.style.display='none';this.nextElementSibling.style.display='grid';">
        <div class="profile-placeholder" style="display:none">
          <div><span>MM</span>Upload your profile photo as<br>assets/profile.jpg</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section class="section" id="about">
  <div class="container about-grid">
    <div class="about-text reveal">
      <div class="eyebrow">Professional Profile</div>
      <h2 class="section-title">Engineering with purpose.<br>Learning through practice.</h2>
      <p>
        I am an Electrical Engineering graduate from The Islamia University
        of Bahawalpur, Pakistan, currently working as a Trainee Engineer at
        Lalpir & Pakgen Power Limited.
      </p>
      <p>
        My professional interests include power generation, electrical
        maintenance, protection systems, transformers, switchgear and
        industrial instrumentation. I am developing my engineering
        understanding through plant exposure, equipment studies and
        practical learning.
      </p>
      <p>
        I believe in understanding not only how electrical equipment operates,
        but also why it is designed, protected, controlled and maintained
        in a particular way.
      </p>
      <div class="about-highlight">
        My goal is to grow into a capable electrical power and industrial
        systems engineer through continuous learning, technical discipline
        and real-world engineering experience.
      </div>
    </div>

    <div class="info-card reveal">
      <div class="eyebrow">At a Glance</div>
      <div class="info-row"><small>Full Name</small><strong>Muhammad Madni</strong></div>
      <div class="info-row"><small>Qualification</small><strong>Bachelor's in Electrical Engineering</strong></div>
      <div class="info-row"><small>University</small><strong>The Islamia University of Bahawalpur</strong></div>
      <div class="info-row"><small>Graduation</small><strong>2026</strong></div>
      <div class="info-row"><small>Current Position</small><strong>Trainee Engineer</strong></div>
      <div class="info-row"><small>Department</small><strong>Electrical & Instrumentation</strong></div>
      <div class="info-row"><small>Location</small><strong>Kot Addu, Punjab, Pakistan</strong></div>
    </div>
  </div>
</section>

<!-- EXPERIENCE -->
<section class="section section-light" id="experience">
  <div class="container">
    <div class="eyebrow reveal">Professional Journey</div>
    <h2 class="section-title reveal">Experience & Industrial Training</h2>
    <p class="section-intro reveal">
      Building a strong foundation in electrical power engineering
      through industrial training and practical exposure.
    </p>

    <article class="experience-card reveal">
      <div class="experience-top">
        <div>
          <h3>Trainee Engineer</h3>
          <div class="company">Lalpir & Pakgen Power Limited</div>
        </div>
        <span class="date">September 2026 – Present</span>
      </div>
      <p><strong>Primary Department:</strong> Electrical & Instrumentation (E&I)</p>
      <p>
        Participating in a one-year industrial training program with a
        primary focus on E&I and exposure to other plant departments.
      </p>
      <ul>
        <li>Learning electrical power plant systems and operating principles.</li>
        <li>Studying transformers, generators, switchgear and switchyard equipment.</li>
        <li>Exploring CTs, PTs, protection relays and circuit breakers.</li>
        <li>Developing knowledge of electrical maintenance and troubleshooting.</li>
        <li>Observing motors, control circuits and industrial instrumentation.</li>
      </ul>
    </article>

    <article class="experience-card reveal">
      <div class="experience-top">
        <div>
          <h3>Internship Trainee</h3>
          <div class="company">Kot Addu Power Company (KAPCO)</div>
        </div>
        <span class="date">August 2025 – September 2025</span>
      </div>
      <p>
        Industrial exposure to power generation, electrical plant
        operations, maintenance practices and engineering safety.
      </p>
    </article>

    <article class="experience-card reveal">
      <div class="experience-top">
        <div>
          <h3>Internship Trainee</h3>
          <div class="company">MEPCO – 132 kV Grid Station, South Gujrat</div>
        </div>
        <span class="date">July 2025 – August 2025</span>
      </div>
      <p>
        Exposure to electrical power distribution, grid station equipment
        and high-voltage substation systems.
      </p>
    </article>
  </div>
</section>

<!-- EXPERTISE -->
<section class="section section-dark" id="expertise">
  <div class="container">
    <div class="eyebrow reveal">Technical Foundation</div>
    <h2 class="section-title reveal">Areas of Engineering Interest</h2>
    <p class="section-intro reveal">
      Core technical areas I am developing through academic knowledge,
      industrial exposure and independent equipment studies.
    </p>

    <div class="skills-grid">
      <div class="skill-card reveal">
        <div class="skill-icon">⚡</div>
        <h3>Power Generation</h3>
        <p>Power plant systems, generators, excitation systems and electrical power distribution.</p>
      </div>
      <div class="skill-card reveal">
        <div class="skill-icon">🛠</div>
        <h3>Electrical Maintenance</h3>
        <p>Equipment inspection, maintenance principles, troubleshooting and plant reliability.</p>
      </div>
      <div class="skill-card reveal">
        <div class="skill-icon">◈</div>
        <h3>Protection Systems</h3>
        <p>Motor protection, overload, overcurrent, earth fault, phase failure and trip/alarm operation.</p>
      </div>
      <div class="skill-card reveal">
        <div class="skill-icon">▤</div>
        <h3>Transformers & Switchgear</h3>
        <p>Transformer configurations, CTs, PTs, switchgear and circuit breaker principles.</p>
      </div>
      <div class="skill-card reveal">
        <div class="skill-icon">⌁</div>
        <h3>Instrumentation</h3>
        <p>Industrial measurement, instrumentation fundamentals and control systems.</p>
      </div>
      <div class="skill-card reveal">
        <div class="skill-icon">⌘</div>
        <h3>Automation Fundamentals</h3>
        <p>Developing knowledge of PLC, SCADA and industrial automation concepts.</p>
      </div>
    </div>

    <div class="eyebrow" style="margin-top:55px;color:#f1d18d">Engineering Software</div>
    <div class="tool-list">
      <span class="tool">ETAP <small>· Beginner</small></span>
      <span class="tool">AutoCAD Electrical <small>· Beginner</small></span>
      <span class="tool">PLC & SCADA <small>· Learning</small></span>
    </div>
  </div>
</section>

<!-- PROJECT -->
<section class="
