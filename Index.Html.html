<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Manish B — Finance & Business Analytics</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;0,700;1,400&family=DM+Sans:opsz,wght@9..40,300;9..40,400;9..40,500;9..40,600&display=swap" rel="stylesheet">
    <style>
        :root {
            --navy: #08111f;
            --navy-mid: #0d1929;
            --card: #101c30;
            --card-hover: #152238;
            --gold: #c9933a;
            --gold-light: #e8b55a;
            --gold-dim: rgba(201,147,58,0.12);
            --text: #dde4f0;
            --text-muted: #7a8aaa;
            --border: rgba(201,147,58,0.18);
        }
        * { margin: 0; padding: 0; box-sizing: border-box; }
        html { scroll-behavior: smooth; }
        body { background: var(--navy); color: var(--text); font-family: 'DM Sans', sans-serif; overflow-x: hidden; }

        /* ── NAV ── */
        nav {
            position: fixed; top: 0; left: 0; right: 0; z-index: 100;
            padding: 1.3rem 4rem; display: flex; justify-content: space-between; align-items: center;
            transition: all 0.4s ease;
        }
        nav.scrolled {
            background: rgba(8,17,31,0.93); backdrop-filter: blur(20px);
            border-bottom: 1px solid var(--border); padding: 0.9rem 4rem;
        }
        .nav-logo {
            font-family: 'Playfair Display', serif; font-size: 1.4rem;
            color: var(--gold); letter-spacing: 0.05em;
        }
        .nav-links { display: flex; gap: 2.5rem; list-style: none; }
        .nav-links a {
            color: var(--text-muted); text-decoration: none; font-size: 0.82rem;
            letter-spacing: 0.12em; text-transform: uppercase; font-weight: 500; transition: color 0.3s;
        }
        .nav-links a:hover { color: var(--gold); }

        /* ── HERO ── */
        #hero {
            min-height: 100vh; display: flex; align-items: center; justify-content: center;
            position: relative; overflow: hidden; padding: 0 2rem; text-align: center;
        }
        canvas#particles { position: absolute; inset: 0; z-index: 0; }
        .hero-content { position: relative; z-index: 1; max-width: 860px; }

        .hero-label {
            font-size: 0.75rem; letter-spacing: 0.35em; text-transform: uppercase;
            color: var(--gold); margin-bottom: 1.6rem;
            opacity: 0; animation: fadeUp 0.8s ease 0.4s forwards;
        }
        .hero-name {
            font-family: 'Playfair Display', serif;
            font-size: clamp(3.8rem, 10vw, 8rem);
            font-weight: 700; line-height: 0.95; letter-spacing: -0.02em; color: #fff;
            opacity: 0; animation: fadeUp 0.9s ease 0.6s forwards;
        }
        .hero-name span { color: var(--gold); font-style: normal; font-weight: 400; letter-spacing: 0.04em; }
        .hero-tagline {
            margin: 1.6rem auto 0; font-size: 1.05rem; color: var(--text-muted);
            max-width: 580px; line-height: 1.8;
            opacity: 0; animation: fadeUp 0.9s ease 0.8s forwards;
        }
        .hero-cta {
            margin-top: 2.8rem; display: flex; gap: 1.2rem; justify-content: center;
            opacity: 0; animation: fadeUp 0.9s ease 1s forwards; flex-wrap: wrap;
        }
        .btn-p {
            padding: 0.9rem 2.4rem; background: var(--gold); color: var(--navy);
            border: none; font-family: 'DM Sans', sans-serif; font-size: 0.88rem;
            font-weight: 600; letter-spacing: 0.06em; cursor: pointer;
            text-decoration: none; transition: all 0.3s;
        }
        .btn-p:hover { background: var(--gold-light); transform: translateY(-3px); }
        .btn-s {
            padding: 0.9rem 2.4rem; background: transparent; color: var(--gold);
            border: 1px solid var(--gold); font-family: 'DM Sans', sans-serif; font-size: 0.88rem;
            font-weight: 600; letter-spacing: 0.06em; cursor: pointer;
            text-decoration: none; transition: all 0.3s;
        }
        .btn-s:hover { background: var(--gold-dim); transform: translateY(-3px); }

        .hero-scroll {
            position: absolute; bottom: 2.5rem; left: 50%; transform: translateX(-50%);
            display: flex; flex-direction: column; align-items: center; gap: 0.5rem;
            color: var(--text-muted); font-size: 0.7rem; letter-spacing: 0.2em;
            text-transform: uppercase; z-index: 1;
            opacity: 0; animation: fadeUp 0.9s ease 1.3s forwards;
        }
        .scroll-line {
            width: 1px; height: 48px;
            background: linear-gradient(to bottom, var(--gold), transparent);
            animation: pulse 2s ease-in-out infinite;
        }
        @keyframes pulse { 0%,100%{opacity:.4} 50%{opacity:1} }
        @keyframes fadeUp { from{opacity:0;transform:translateY(28px)} to{opacity:1;transform:translateY(0)} }

        /* ── LAYOUT ── */
        .wrap { max-width: 1140px; margin: 0 auto; padding: 6rem 3rem; }
        .eyebrow { font-size: 0.73rem; letter-spacing: 0.3em; text-transform: uppercase; color: var(--gold); margin-bottom: 0.6rem; }
        .sec-title {
            font-family: 'Playfair Display', serif;
            font-size: clamp(2rem, 4vw, 2.9rem); font-weight: 700; color: #fff; line-height: 1.2; margin-bottom: 0.8rem;
        }
        .divider { width: 54px; height: 2px; background: var(--gold); margin-bottom: 3.5rem; }

        /* ── ABOUT ── */
        .about-inner { display: grid; grid-template-columns: 1fr 1fr; gap: 5rem; align-items: center; }
        .about-p { font-size: 1rem; line-height: 1.95; color: var(--text-muted); }
        .about-p + .about-p { margin-top: 1rem; }
        .stat-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 1.4rem; }
        .stat-card {
            background: var(--card); border: 1px solid var(--border); padding: 2rem 1.4rem;
            text-align: center; transition: all 0.3s; position: relative; overflow: hidden;
        }
        .stat-card::after {
            content: ''; position: absolute; top: 0; left: 0; right: 0; height: 2px;
            background: var(--gold); transform: scaleX(0); transition: transform 0.4s;
        }
        .stat-card:hover::after { transform: scaleX(1); }
        .stat-card:hover { background: var(--card-hover); }
        .sn { font-family: 'Playfair Display', serif; font-size: 2.4rem; font-weight: 700; color: var(--gold); display: block; }
        .sl { font-size: 0.74rem; color: var(--text-muted); text-transform: uppercase; letter-spacing: 0.1em; margin-top: 0.3rem; display: block; }

        /* ── TIMELINE ── */
        .timeline { position: relative; padding-left: 1.8rem; }
        .timeline::before {
            content: ''; position: absolute; left: 0; top: 4px; bottom: 0;
            width: 1px; background: linear-gradient(to bottom, var(--gold), rgba(201,147,58,0.1));
        }
        .titem {
            position: relative; padding: 0 0 3.5rem 2.5rem;
            opacity: 0; transform: translateX(-18px); transition: all 0.6s ease;
        }
        .titem.vis { opacity: 1; transform: translateX(0); }
        .tdot {
            position: absolute; left: -0.38rem; top: 0.45rem;
            width: 13px; height: 13px; background: var(--gold);
            border-radius: 50%; border: 2.5px solid var(--navy);
            box-shadow: 0 0 8px rgba(201,147,58,0.5);
        }
        .tdate { font-size: 0.75rem; letter-spacing: 0.12em; color: var(--gold); text-transform: uppercase; margin-bottom: 0.4rem; }
        .tco { font-family: 'Playfair Display', serif; font-size: 1.35rem; color: #fff; margin-bottom: 0.2rem; }
        .trole { font-size: 0.88rem; color: var(--text-muted); margin-bottom: 1rem; font-weight: 500; }
        .tpts { list-style: none; display: flex; flex-direction: column; gap: 0.55rem; }
        .tpts li { font-size: 0.9rem; color: var(--text-muted); padding-left: 1.3rem; position: relative; line-height: 1.65; }
        .tpts li::before { content: '→'; position: absolute; left: 0; color: var(--gold); font-size: 0.78rem; top: 0.1rem; }

        /* ── SKILLS ── */
        .skills-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 1.8rem; }
        .scat {
            background: var(--card); border: 1px solid var(--border); padding: 2rem 1.8rem;
            transition: all 0.3s; opacity: 0; transform: translateY(20px);
        }
        .scat.vis { opacity: 1; transform: translateY(0); }
        .scat:hover { border-color: var(--gold); }
        .scat-title {
            font-family: 'Playfair Display', serif; font-size: 1.05rem; color: var(--gold);
            margin-bottom: 1.2rem; padding-bottom: 0.8rem; border-bottom: 1px solid var(--border);
        }
        .tags { display: flex; flex-wrap: wrap; gap: 0.55rem; }
        .tag {
            padding: 0.32rem 0.85rem; background: var(--gold-dim);
            color: var(--gold-light); font-size: 0.76rem; font-weight: 500;
            border: 1px solid rgba(201,147,58,0.25); transition: all 0.3s; cursor: default;
        }
        .tag:hover { background: var(--gold); color: var(--navy); }

        /* ── PROJECTS ── */
        .proj-card {
            background: var(--card); border: 1px solid var(--border); padding: 3rem;
            position: relative; transition: all 0.3s;
        }
        .proj-card:hover { border-color: var(--gold); }
        .proj-card::after {
            content: '↗'; position: absolute; top: 1.6rem; right: 1.8rem;
            font-size: 1.3rem; color: var(--gold); opacity: 0.4;
        }
        .plabel { font-size: 0.7rem; letter-spacing: 0.2em; text-transform: uppercase; color: var(--gold); margin-bottom: 0.8rem; }
        .ptitle { font-family: 'Playfair Display', serif; font-size: 1.4rem; color: #fff; margin-bottom: 1rem; line-height: 1.4; }
        .pdesc { color: var(--text-muted); font-size: 0.93rem; line-height: 1.85; }

        /* ── EDUCATION ── */
        .edu-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(290px, 1fr)); gap: 1.8rem; }
        .edu-card {
            background: var(--card); border: 1px solid var(--border); padding: 2.4rem 2rem;
            transition: all 0.3s; opacity: 0; transform: translateY(20px);
        }
        .edu-card.vis { opacity: 1; transform: translateY(0); }
        .edu-card:hover { border-color: var(--gold); }
        .edegree { font-family: 'Playfair Display', serif; font-size: 1.15rem; color: #fff; margin-bottom: 0.4rem; }
        .eschool { color: var(--gold); font-size: 0.85rem; font-weight: 600; margin-bottom: 0.4rem; }
        .eyear { font-size: 0.76rem; color: var(--text-muted); letter-spacing: 0.08em; }

        /* ── CERTS ── */
        .cert-list { display: flex; flex-direction: column; gap: 1rem; }
        .citem {
            display: flex; justify-content: space-between; align-items: center;
            padding: 1.2rem 1.8rem; background: var(--card); border: 1px solid var(--border);
            border-left: 3px solid var(--gold); transition: all 0.3s;
            opacity: 0; transform: translateX(-18px);
        }
        .citem.vis { opacity: 1; transform: translateX(0); }
        .citem:hover { background: var(--card-hover); }
        .cname { font-size: 0.93rem; color: var(--text); }
        .cissuer { font-size: 0.78rem; color: var(--text-muted); margin-top: 0.2rem; }
        .cdate { font-size: 0.76rem; color: var(--gold); font-weight: 600; white-space: nowrap; margin-left: 1rem; }

        /* ── CONTACT ── */
        #cta {
            background: var(--navy-mid); border-top: 1px solid var(--border); border-bottom: 1px solid var(--border);
            padding: 6rem 2rem; text-align: center;
        }
        #cta .sec-title { margin-bottom: 0.5rem; }
        #cta p { color: var(--text-muted); font-size: 0.98rem; margin-bottom: 2.5rem; }
        .clinks { display: flex; gap: 1.2rem; justify-content: center; flex-wrap: wrap; }
        .clink {
            display: flex; align-items: center; gap: 0.7rem;
            padding: 1rem 1.8rem; background: var(--card); border: 1px solid var(--border);
            color: var(--text); text-decoration: none; font-size: 0.88rem; transition: all 0.3s;
        }
        .clink:hover { border-color: var(--gold); color: var(--gold); transform: translateY(-3px); }
        .cicon { font-size: 1rem; }

        footer { padding: 2rem; text-align: center; font-size: 0.76rem; color: var(--text-muted); letter-spacing: 0.05em; }

        /* ── REVEAL ── */
        .reveal { opacity: 0; transform: translateY(28px); transition: opacity 0.7s ease, transform 0.7s ease; }
        .reveal.vis { opacity: 1; transform: translateY(0); }

        /* ── RESPONSIVE ── */
        @media (max-width: 820px) {
            nav { padding: 1rem 1.5rem; }
            nav.scrolled { padding: 0.8rem 1.5rem; }
            .nav-links { gap: 1.2rem; }
            .nav-links a { font-size: 0.72rem; letter-spacing: 0.08em; }
            .wrap { padding: 4rem 1.5rem; }
            .about-inner { grid-template-columns: 1fr; gap: 3rem; }
            .hero-cta { flex-direction: column; align-items: center; }
        }
        @media (max-width: 480px) {
            .nav-links { gap: 0.8rem; }
        }
    </style>
</head>
<body>

<!-- NAV -->
<nav id="nb">
    <div class="nav-logo">M. B.</div>
    <ul class="nav-links">
        <li><a href="#about-sec">About</a></li>
        <li><a href="#exp-sec">Experience</a></li>
        <li><a href="#skills-sec">Skills</a></li>
        <li><a href="#edu-sec">Education</a></li>
        <li><a href="#cta">Contact</a></li>
    </ul>
</nav>

<!-- HERO -->
<section id="hero">
    <canvas id="particles"></canvas>
    <div class="hero-content">
        <div class="hero-label">MBA · Finance &amp; Business Analytics · Bengaluru</div>
        <h1 class="hero-name">Manish <span>B.</span></h1>
        <p class="hero-tagline">Finance &amp; Analytics professional bridging data insight with strategic decision-making. Targeting FP&amp;A, MIS, and Business Analyst roles at MNCs.</p>
        <div class="hero-cta">
            <a href="#exp-sec" class="btn-p">Explore Experience</a>
            <a href="mailto:manish.mavric@gmail.com" class="btn-s">Get in Touch</a>
        </div>
    </div>
    <div class="hero-scroll"><span>Scroll</span><div class="scroll-line"></div></div>
</section>

<!-- ABOUT -->
<section id="about-sec">
    <div class="wrap">
        <div class="about-inner">
            <div>
                <div class="eyebrow reveal">About Me</div>
                <h2 class="sec-title reveal">Finance Meets<br>Data Thinking</h2>
                <div class="divider reveal"></div>
                <p class="about-p reveal">MBA candidate specialising in Finance and Business Analytics at CMS Jain University, Bengaluru. I bridge financial acumen and data-driven decision-making — equally comfortable with ledgers and dashboards.</p>
                <p class="about-p reveal" style="margin-top:1rem">My background spans client operations at Accenture, KPI-driven analytics at First Advantage, and insurance relationship management at ECPL — complemented by a hands-on Finance internship applying Tally ERP in live business contexts.</p>
            </div>
            <div class="stat-grid">
                <div class="stat-card reveal"><span class="sn">1+</span><span class="sl">Years Experience</span></div>
                <div class="stat-card reveal"><span class="sn">4.5</span><span class="sl">Avg CSAT Score</span></div>
                <div class="stat-card reveal"><span class="sn">50+</span><span class="sl">Daily Interactions</span></div>
                <div class="stat-card reveal"><span class="sn">MBA</span><span class="sl">Finance &amp; Analytics</span></div>
            </div>
        </div>
    </div>
</section>

<!-- EXPERIENCE -->
<section id="exp-sec" style="background: var(--navy-mid);">
    <div class="wrap">
        <div class="eyebrow reveal">Work History</div>
        <h2 class="sec-title reveal">Professional Experience</h2>
        <div class="divider reveal"></div>

        <div class="timeline">
            <div class="titem">
                <div class="tdot"></div>
                <div class="tdate">May 2025 – Aug 2025</div>
                <div class="tco">M N Service Providers</div>
                <div class="trole">Marketing and Finance Intern</div>
                <ul class="tpts">
                    <li>Designed strategic PowerPoint presentations for client pitches and internal reviews, sharpening communication clarity</li>
                    <li>Gained hands-on accounting workflow experience using Tally ERP — invoice entry, ledger tracking, and basic reconciliation</li>
                </ul>
            </div>
            <div class="titem">
                <div class="tdot"></div>
                <div class="tdate">Apr 2024 – Jun 2024</div>
                <div class="tco">Accenture</div>
                <div class="trole">Client Success · Bengaluru</div>
                <ul class="tpts">
                    <li>Managed 50+ customer interactions daily while maintaining SLA adherence and quality benchmarks</li>
                    <li>Resolved customer issues at first contact, meaningfully reducing repeat follow-ups</li>
                    <li>Maintained accurate records and supported process compliance for issue resolution workflows</li>
                </ul>
            </div>
            <div class="titem">
                <div class="tdot"></div>
                <div class="tdate">Dec 2023 – Mar 2024</div>
                <div class="tco">First Advantage</div>
                <div class="trole">Operations Analyst · Bengaluru</div>
                <ul class="tpts">
                    <li>Conducted background verification by cross-validating data across multiple databases</li>
                    <li>Prepared KPI reports on turnaround time and compliance accuracy for team leads</li>
                    <li>Ensured adherence to NDA, KYC, and regulatory requirements across all verticals</li>
                </ul>
            </div>
            <div class="titem">
                <div class="tdot"></div>
                <div class="tdate">Nov 2022 – Nov 2023</div>
                <div class="tco">ECPL</div>
                <div class="trole">Client Relationship Officer · Bengaluru</div>
                <ul class="tpts">
                    <li>Served as single point of contact for escalated and sensitive motor insurance cases</li>
                    <li>Maintained real-time customer data to expedite claims processing</li>
                    <li>Achieved a sustained average CSAT of 4.5 / 5.0 across the full engagement year</li>
                </ul>
            </div>
        </div>
    </div>
</section>

<!-- SKILLS -->
<section id="skills-sec">
    <div class="wrap">
        <div class="eyebrow reveal">Capabilities</div>
        <h2 class="sec-title reveal">Technical Skills</h2>
        <div class="divider reveal"></div>
        <div class="skills-grid">
            <div class="scat">
                <div class="scat-title">Analytics &amp; Reporting</div>
                <div class="tags">
                    <span class="tag">Power BI</span><span class="tag">MS Excel</span>
                    <span class="tag">Pivot Tables</span><span class="tag">VLOOKUP</span>
                    <span class="tag">XLOOKUP</span><span class="tag">Data Analysis</span>
                    <span class="tag">Tableau (Exposure)</span>
                </div>
            </div>
            <div class="scat">
                <div class="scat-title">Finance</div>
                <div class="tags">
                    <span class="tag">Financial Reporting</span><span class="tag">KPI Reporting</span>
                    <span class="tag">Budgeting</span><span class="tag">Forecasting</span>
                    <span class="tag">Wealth Management</span><span class="tag">FP&amp;A</span>
                </div>
            </div>
            <div class="scat">
                <div class="scat-title">Tools &amp; Platforms</div>
                <div class="tags">
                    <span class="tag">Tally ERP</span><span class="tag">MS Office Suite</span>
                    <span class="tag">SQL (Exposure)</span>
                </div>
            </div>
            <div class="scat">
                <div class="scat-title">Core Competencies</div>
                <div class="tags">
                    <span class="tag">SLA Management</span><span class="tag">Compliance Reporting</span>
                    <span class="tag">Process Improvement</span><span class="tag">Stakeholder Coordination</span>
                    <span class="tag">Client Relationship Mgmt</span>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- PROJECT -->
<section id="proj-sec" style="background: var(--navy-mid);">
    <div class="wrap">
        <div class="eyebrow reveal">Research</div>
        <h2 class="sec-title reveal">Master's Thesis</h2>
        <div class="divider reveal"></div>
        <div class="proj-card reveal">
            <div class="plabel">Secondary Research Study · CMS Jain University</div>
            <div class="ptitle">"Influence of Data Visualisation Dashboards<br>on Managerial Decision Quality"</div>
            <div class="pdesc">An in-depth secondary research study examining how BI dashboards impact the quality and speed of managerial decision-making. Explores the relationship between dashboard design principles, cognitive load reduction, and decision outcomes — with practical implications for Power BI and Tableau adoption in finance and operations contexts.</div>
        </div>
    </div>
</section>

<!-- EDUCATION -->
<section id="edu-sec">
    <div class="wrap">
        <div class="eyebrow reveal">Academic Background</div>
        <h2 class="sec-title reveal">Education</h2>
        <div class="divider reveal"></div>
        <div class="edu-grid">
            <div class="edu-card">
                <div class="edegree">MBA · Finance &amp; Business Analytics</div>
                <div class="eschool">CMS Jain University (Deemed-to-be University)</div>
                <div class="eyear">Aug 2024 – Present · Bengaluru, India</div>
            </div>
            <div class="edu-card">
                <div class="edegree">B.COM · Finance</div>
                <div class="eschool">Presidency College</div>
                <div class="eyear">Jul 2018 – Aug 2021 · Bengaluru, India</div>
            </div>
        </div>
    </div>
</section>

<!-- CERTIFICATIONS -->
<section style="background: var(--navy-mid);">
    <div class="wrap" style="padding-top: 4rem; padding-bottom: 4rem;">
        <div class="eyebrow reveal">Credentials</div>
        <h2 class="sec-title reveal">Certifications</h2>
        <div class="divider reveal"></div>
        <div class="cert-list">
            <div class="citem">
                <div>
                    <div class="cname">Introduction to Financial Planning &amp; Wealth Management</div>
                    <div class="cissuer">Corporate Finance Institute (CFI)</div>
                </div>
                <div class="cdate">Sep 2025</div>
            </div>
            <div class="citem">
                <div>
                    <div class="cname">Statistics Foundations</div>
                    <div class="cissuer">Meta</div>
                </div>
                <div class="cdate">Nov 2024</div>
            </div>
            <div class="citem">
                <div>
                    <div class="cname">Excel for Beginners: Introduction to Spreadsheets</div>
                    <div class="cissuer">Coursera</div>
                </div>
                <div class="cdate">Nov 2024</div>
            </div>
        </div>
    </div>
</section>

<!-- CONTACT -->
<div id="cta">
    <div class="eyebrow">Available for Opportunities</div>
    <h2 class="sec-title">Let's Connect</h2>
    <p>Open to Finance Analyst, Business Analyst, MIS Analyst, and FP&amp;A roles — Bengaluru or Remote.</p>
    <div class="clinks">
        <a href="mailto:manish.mavric@gmail.com" class="clink"><span class="cicon">✉</span> manish.mavric@gmail.com</a>
        <a href="tel:+918147212619" class="clink"><span class="cicon">☎</span> +91 81472 12619</a>
        <a href="https://www.linkedin.com" target="_blank" class="clink"><span class="cicon" style="font-weight:700;font-size:0.85rem">in</span> LinkedIn</a>
    </div>
</div>

<footer>© 2026 Manish B · Bengaluru, Karnataka · Open to Remote</footer>

<script>
// NAV SCROLL
const nb = document.getElementById('nb');
window.addEventListener('scroll', () => {
    nb.classList.toggle('scrolled', window.scrollY > 60);
});

// SCROLL REVEAL
const obs = new IntersectionObserver(entries => {
    entries.forEach(e => { if(e.isIntersecting) e.target.classList.add('vis'); });
}, { threshold: 0.1 });

document.querySelectorAll('.reveal, .titem, .scat, .edu-card, .citem').forEach(el => obs.observe(el));

// STAGGER DELAYS
document.querySelectorAll('.titem').forEach((el,i) => el.style.transitionDelay = `${i*0.14}s`);
document.querySelectorAll('.scat').forEach((el,i) => el.style.transitionDelay = `${i*0.1}s`);
document.querySelectorAll('.edu-card').forEach((el,i) => el.style.transitionDelay = `${i*0.15}s`);
document.querySelectorAll('.citem').forEach((el,i) => el.style.transitionDelay = `${i*0.1}s`);

// PARTICLE CANVAS
const canvas = document.getElementById('particles');
const ctx = canvas.getContext('2d');
function resize() { canvas.width = innerWidth; canvas.height = innerHeight; }
resize(); window.addEventListener('resize', resize);

const pts = Array.from({length: 65}, () => ({
    x: Math.random() * innerWidth, y: Math.random() * innerHeight,
    r: Math.random() * 1.4 + 0.3,
    vx: (Math.random()-.5) * 0.22, vy: (Math.random()-.5) * 0.22,
    a: Math.random() * 0.45 + 0.08
}));

function draw() {
    ctx.clearRect(0, 0, canvas.width, canvas.height);
    pts.forEach(p => {
        ctx.beginPath(); ctx.arc(p.x, p.y, p.r, 0, Math.PI*2);
        ctx.fillStyle = `rgba(201,147,58,${p.a})`; ctx.fill();
        p.x += p.vx; p.y += p.vy;
        if(p.x<0||p.x>canvas.width) p.vx*=-1;
        if(p.y<0||p.y>canvas.height) p.vy*=-1;
    });
    for(let i=0;i<pts.length;i++){
        for(let j=i+1;j<pts.length;j++){
            const dx=pts[i].x-pts[j].x, dy=pts[i].y-pts[j].y;
            const d=Math.hypot(dx,dy);
            if(d<115){ ctx.beginPath();
                ctx.strokeStyle=`rgba(201,147,58,${0.07*(1-d/115)})`;
                ctx.lineWidth=0.5;
                ctx.moveTo(pts[i].x,pts[i].y); ctx.lineTo(pts[j].x,pts[j].y); ctx.stroke();
            }
        }
    }
    requestAnimationFrame(draw);
}
draw();
</script>
</body>
</html>
