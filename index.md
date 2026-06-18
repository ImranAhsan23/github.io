---
title: Imran Ahsan
permalink: /
---

<style>
:root {
  --navy: #0b2347;
  --blue: #1757a6;
  --light-blue: #eef5ff;
  --text: #1f2933;
  --muted: #5c6773;
  --line: #d9e2ec;
  --card: #ffffff;
  --accent: #0ea5a4;
}

* { box-sizing: border-box; }

body {
  margin: 0;
  color: var(--text);
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  line-height: 1.65;
  background: #f7fafc;
}

.site-wrap {
  max-width: 1080px;
  margin: 0 auto;
  padding: 32px 20px 64px;
}

.hero {
  background: linear-gradient(135deg, var(--navy), var(--blue));
  color: white;
  border-radius: 24px;
  padding: 42px;
  box-shadow: 0 18px 45px rgba(11, 35, 71, 0.22);
}

.hero-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 22px;
  align-items: center;
}

.name {
  font-size: clamp(2.1rem, 5vw, 4.4rem);
  line-height: 1.04;
  margin: 0;
  letter-spacing: -0.04em;
}

.tagline {
  font-size: clamp(1.05rem, 2vw, 1.35rem);
  margin: 16px 0 0;
  color: #dcecff;
  max-width: 920px;
}

.status {
  margin-top: 16px;
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.badge {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  padding: 7px 12px;
  border: 1px solid rgba(255,255,255,0.28);
  border-radius: 999px;
  background: rgba(255,255,255,0.12);
  color: white;
  font-size: 0.92rem;
}

.links {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 26px;
}

.links a, .button {
  display: inline-block;
  text-decoration: none;
  color: var(--navy);
  background: white;
  border-radius: 999px;
  padding: 10px 15px;
  font-weight: 650;
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}

.links a:hover, .button:hover {
  transform: translateY(-1px);
  box-shadow: 0 9px 22px rgba(0,0,0,0.16);
}

.nav {
  margin: 26px 0 8px;
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}

.nav a {
  color: var(--blue);
  text-decoration: none;
  background: var(--light-blue);
  border: 1px solid var(--line);
  border-radius: 999px;
  padding: 8px 13px;
  font-weight: 600;
}

section {
  background: var(--card);
  border: 1px solid var(--line);
  border-radius: 20px;
  padding: 30px;
  margin-top: 22px;
  box-shadow: 0 8px 20px rgba(16, 42, 67, 0.04);
}

h2 {
  color: var(--navy);
  font-size: 1.55rem;
  margin: 0 0 18px;
  letter-spacing: -0.02em;
}

h3 {
  color: var(--navy);
  margin: 22px 0 8px;
  font-size: 1.1rem;
}

p { margin: 0 0 14px; }

.grid-2 {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 16px;
}

.card {
  background: #fbfdff;
  border: 1px solid var(--line);
  border-radius: 16px;
  padding: 18px;
}

.card h3 { margin-top: 0; }

.project-card {
  border-left: 5px solid var(--blue);
}

.meta {
  color: var(--muted);
  font-size: 0.95rem;
}

.pub-list {
  list-style: none;
  padding-left: 0;
  margin: 0;
}

.pub-list li {
  padding: 16px 0;
  border-bottom: 1px solid var(--line);
}

.pub-list li:last-child { border-bottom: none; }

.pub-title {
  font-weight: 700;
  color: var(--navy);
}

.venue {
  color: var(--blue);
  font-weight: 700;
}

.pill-row {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: 8px;
}

.pill {
  background: var(--light-blue);
  color: var(--blue);
  border: 1px solid #cfe3ff;
  border-radius: 999px;
  padding: 5px 10px;
  font-size: 0.88rem;
  font-weight: 600;
}

.timeline-item {
  border-left: 3px solid var(--blue);
  padding-left: 16px;
  margin: 16px 0;
}

.footer {
  text-align: center;
  color: var(--muted);
  margin: 28px 0 0;
  font-size: 0.95rem;
}

@media (max-width: 760px) {
  .hero { padding: 28px; border-radius: 18px; }
  section { padding: 22px; }
  .grid-2 { grid-template-columns: 1fr; }
}
</style>

<div class="site-wrap">

  <header class="hero">
    <div class="hero-grid">
      <div>
        <h1 class="name">Imran Ahsan</h1>
        <p class="tagline">Trustworthy Graph AI · Graph Neural Network Unlearning · Explainable AI · Privacy-Preserving Machine Learning · NLP for Software Engineering</p>
        <div class="status">
          <span class="badge">Ph.D. Defense Completed · June 2026</span>
          <span class="badge">Department of Smart City · Chung-Ang University</span>
          <span class="badge">Data Intelligence Laboratory</span>
        </div>
        <div class="links">
          <a href="mailto:Imranahsan23@gmail.com">Email</a>
          <a href="https://scholar.google.com/citations?user=h_P3dAkAAAAJ&hl=en">Google Scholar</a>
          <a href="https://github.com/ImranAhsan23">GitHub</a>
          <a href="https://www.linkedin.com/in/imran-ahsan-7042365a/">LinkedIn</a>
        </div>
      </div>
    </div>
  </header>

  <nav class="nav">
    <a href="#about">About</a>
    <a href="#research">Research</a>
    <a href="#projects">Projects</a>
    <a href="#publications">Publications</a>
    <a href="#experience">Experience</a>
    <a href="#teaching">Teaching</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About</h2>
    <p>I am a researcher in trustworthy artificial intelligence with a focus on graph neural networks, graph unlearning, explainable AI, privacy-aware model updates, membership-inference evaluation, and benchmark design. My doctoral research develops practical graph-unlearning systems that connect realistic deletion requests with efficient model updates and transparent verification evidence.</p>
    <p>My background also includes software engineering and professional software development. During my M.S., I worked on automated test-case generation from user specifications using NLP. During my Ph.D., I extended this interest in user requirements toward privacy-driven AI systems, including natural-language deletion requests for graph unlearning.</p>
  </section>

  <section id="research">
    <h2>Research Interests</h2>
    <div class="grid-2">
      <div class="card">
        <h3>Trustworthy Graph AI</h3>
        <p>Graph neural networks, graph representation learning, graph unlearning, privacy-preserving graph ML, and regulatory-compliance-motivated graph AI.</p>
      </div>
      <div class="card">
        <h3>Explainable and Auditable AI</h3>
        <p>Explainability-based verification, transparent model diagnostics, residual-influence analysis, and human-readable evidence for AI behavior.</p>
      </div>
      <div class="card">
        <h3>AI Software Engineering</h3>
        <p>Requirements-aware AI systems, NLP for software engineering, user-facing deletion requests, benchmark construction, and reproducible evaluation workflows.</p>
      </div>
      <div class="card">
        <h3>Smart-City Graph Applications</h3>
        <p>Privacy-aware learning for relational data in smart infrastructure, recommender systems, citation networks, healthcare relations, and urban data systems.</p>
      </div>
    </div>
  </section>

  <section id="projects">
    <h2>Selected Research Projects</h2>
    <div class="grid-2">
      <div class="card project-card">
        <h3>Text2Forget</h3>
        <p>Request-driven graph unlearning benchmark that converts DSAR-style natural-language deletion requests into executable graph targets using lexical and embedding-based resolution.</p>
        <div class="pill-row"><span class="pill">WWW 2026</span><span class="pill">Graph Unlearning</span><span class="pill">NLP</span></div>
      </div>
      <div class="card project-card">
        <h3>NodeVanisher</h3>
        <p>Efficient node-level GNN unlearning method based on deletion-aware subgraph extraction, capped neighbor sampling, and localized retraining initialized from a pretrained model.</p>
        <div class="pill-row"><span class="pill">Localized Updating</span><span class="pill">GNNs</span><span class="pill">Privacy</span></div>
      </div>
      <div class="card project-card">
        <h3>Forget and Explain</h3>
        <p>Explainability-driven verification framework that compares pre- and post-unlearning explanations to assess attribution shifts, local-structure changes, and residual influence.</p>
        <div class="pill-row"><span class="pill">WSDM 2026</span><span class="pill">XAI</span><span class="pill">Verification</span></div>
      </div>
      <div class="card project-card">
        <h3>GDPRBench for Graph Unlearning</h3>
        <p>Benchmarking direction for graph unlearning under error-typed forget sets, detection signals, and utility-privacy diagnostics inspired by privacy-compliance workflows.</p>
        <div class="pill-row"><span class="pill">Benchmark Design</span><span class="pill">GDPR</span><span class="pill">Evaluation</span></div>
      </div>
    </div>
  </section>

  <section id="publications">
    <h2>Selected Publications</h2>
    <ul class="pub-list">
      <li>
        <div class="pub-title">From Random Forget-Sets to Realistic Natural-Language Deletion Requests</div>
        <div class="meta">Imran Ahsan, Jinsung Kim, Mucheol Kim</div>
        <div><span class="venue">The ACM Web Conference (WWW) 2026</span> · Short Paper · Published</div>
      </li>
      <li>
        <div class="pub-title">Forget and Explain: Transparent Verification of GNN Unlearning</div>
        <div class="meta">Imran Ahsan, Hyunwook Yu, Jinsung Kim, Mucheol Kim</div>
        <div><span class="venue">ACM Web Search and Data Mining (WSDM) 2026</span> · Short Paper · Published</div>
      </li>
      <li>
        <div class="pub-title">Unlocking the Power of Graph Neural Networks: A Systematic Literature Review of Application-Oriented GNN Studies</div>
        <div class="meta">Imran Ahsan et al.</div>
        <div><span class="venue">CMES</span> · Q1 Journal · Accepted</div>
      </li>
      <li>
        <div class="pub-title">The Semantic Design Space of Retrieval-Augmented Recommender Systems: A Systematic Review of LLM-Based Approaches</div>
        <div class="meta">Minhyeok Choi, Imran Ahsan, Hyunwook Yu, Taeyoung Choe, Mucheol Kim</div>
        <div><span class="venue">CMC</span> · Q3 Journal · Accepted</div>
      </li>
      <li>
        <div class="pub-title">NodeVanisher: Efficient and Scalable Data Unlearning in GNNs through Targeted Subgraph Refinement</div>
        <div class="meta">Imran Ahsan et al.</div>
        <div><span class="venue">IEEE Transactions on Consumer Electronics</span> · Under Review / Minor Revision</div>
      </li>
    </ul>
  </section>

  <section id="experience">
    <h2>Education and Experience</h2>
    <div class="timeline-item">
      <h3>Ph.D. in Engineering · Department of Smart City</h3>
      <p class="meta">Chung-Ang University, South Korea · 2023–2026 · Expected Graduation: August 2026 · Supervisor: Prof. Mucheol Kim</p>
      <p>Dissertation research on privacy-preserving graph unlearning for graph neural networks, with emphasis on request-driven deletion, localized model updating, and explainable verification.</p>
    </div>
    <div class="timeline-item">
      <h3>M.S. in Software Engineering</h3>
      <p class="meta">National University of Sciences and Technology (NUST), Pakistan · 2014–2017</p>
      <p>Thesis: Automated Test Case Generation from User Specifications using NLP.</p>
    </div>
    <div class="timeline-item">
      <h3>Lecturer in Computer Science</h3>
      <p class="meta">National University of Modern Languages (NUML), Islamabad, Pakistan · 2017–2023</p>
      <p>Taught software engineering and computer science courses, supervised student projects, and contributed to curriculum development.</p>
    </div>
    <div class="timeline-item">
      <h3>Professional Software Development</h3>
      <p>Over four years of professional experience developing ASP.NET-based enterprise systems, including university portals, admissions systems, HR systems, and business applications.</p>
    </div>
  </section>

  <section id="teaching">
    <h2>Teaching and Mentoring</h2>
    <p>I have taught undergraduate computer science and software engineering courses including object-oriented programming, Java, C#, software development, and web/software engineering topics. My teaching approach combines conceptual clarity, hands-on implementation, and project-based assessment.</p>
  </section>

  <section id="skills">
    <h2>Technical Skills</h2>
    <div class="pill-row">
      <span class="pill">Python</span>
      <span class="pill">PyTorch</span>
      <span class="pill">Graph Neural Networks</span>
      <span class="pill">Explainable AI</span>
      <span class="pill">Graph Unlearning</span>
      <span class="pill">NLP</span>
      <span class="pill">C#</span>
      <span class="pill">Java</span>
      <span class="pill">ASP.NET</span>
      <span class="pill">HTML/CSS/JavaScript</span>
      <span class="pill">SQL Server</span>
      <span class="pill">MySQL</span>
      <span class="pill">LaTeX</span>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:Imranahsan23@gmail.com">Imranahsan23@gmail.com</a></p>
    <p>Profiles: <a href="https://scholar.google.com/citations?user=h_P3dAkAAAAJ&hl=en">Google Scholar</a> · <a href="https://github.com/ImranAhsan23">GitHub</a> · <a href="https://www.linkedin.com/in/imran-ahsan-7042365a/">LinkedIn</a></p>
  </section>

  <p class="footer">© Imran Ahsan · Last updated 2026</p>
</div>
