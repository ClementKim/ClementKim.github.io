<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Junsung Kim</title>
  <meta name="description" content="Junsung Kim, M.S. student at GIST working on vision–language models and mixture-of-experts. Open to Research Engineer roles; graduating February 2027.">
  <meta name="author" content="Junsung Kim">
  <link rel="canonical" href="https://clementkim.github.io/">
  <meta property="og:type" content="profile">
  <meta property="og:title" content="Junsung Kim (김준성)">
  <meta property="og:description" content="M.S. student at GIST working on vision–language models and mixture-of-experts. Open to Research Engineer roles; graduating February 2027.">
  <meta property="og:url" content="https://clementkim.github.io/">
  <meta name="color-scheme" content="light dark">
  <meta name="theme-color" content="#ffffff" media="(prefers-color-scheme: light)">
  <meta name="theme-color" content="#0e1116" media="(prefers-color-scheme: dark)">
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='14' fill='%230a5bb5'/%3E%3Ctext x='32' y='42' font-family='Georgia,serif' font-size='28' font-weight='700' text-anchor='middle' fill='white'%3EJK%3C/text%3E%3C/svg%3E">
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Junsung Kim",
    "alternateName": "김준성",
    "url": "https://clementkim.github.io/",
    "email": "mailto:wnstjd123@gm.gist.ac.kr",
    "affiliation": { "@type": "CollegeOrUniversity", "name": "Gwangju Institute of Science and Technology (GIST)" },
    "alumniOf": { "@type": "CollegeOrUniversity", "name": "Ajou University" },
    "knowsAbout": ["Vision–language models", "Visual reasoning", "Mixture-of-experts", "Hyperspectral imaging"],
    "sameAs": ["https://github.com/ClementKim", "https://www.linkedin.com/in/ClementKim"]
  }
  </script>
  <style>
    :root {
      --bg: #ffffff;
      --text: #1c1f23;
      --muted: #59626d;
      --rule: #e2e6eb;
      --accent: #0a5bb5;
      --accent-soft: #eef4fc;
      --tag-bg: #eef1f4;
      --tag-text: #39424c;
      --serif: "Iowan Old Style", "Palatino Linotype", Palatino, "Book Antiqua", Georgia, "Noto Serif KR", "AppleMyungjo", serif;
      --sans: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Apple SD Gothic Neo", "Noto Sans KR", "Malgun Gothic", sans-serif;
      color-scheme: light;
    }
    @media (prefers-color-scheme: dark) {
      :root {
        --bg: #0e1116;
        --text: #e3e6ea;
        --muted: #a2abb6;
        --rule: #262c34;
        --accent: #7ab6ff;
        --accent-soft: #13223a;
        --tag-bg: #1c222b;
        --tag-text: #c7cfd8;
        color-scheme: dark;
      }
    }

    *, *::before, *::after { box-sizing: border-box; }
    html { -webkit-text-size-adjust: 100%; }
    body {
      margin: 0;
      background: var(--bg);
      color: var(--text);
      font: 16.5px/1.62 var(--sans);
      font-feature-settings: "kern";
    }
    .page { max-width: 820px; margin: 0 auto; padding: 64px 24px 48px; }

    a { color: var(--accent); text-decoration: none; }
    a:hover { text-decoration: underline; text-underline-offset: 2px; }
    a:focus-visible { outline: 2px solid var(--accent); outline-offset: 2px; border-radius: 2px; }
    p { margin: 0 0 0.9rem; }
    ul, ol { margin: 0; padding: 0; list-style: none; }

    /* Intro */
    .intro { display: grid; grid-template-columns: 1fr auto; gap: 28px; align-items: center; }
    h1 {
      font-family: var(--serif);
      font-size: 2.5rem;
      font-weight: 600;
      line-height: 1.15;
      letter-spacing: -0.01em;
      margin: 0 0 0.5rem;
    }
    h1 .ko { font-size: 0.55em; font-weight: 400; color: var(--muted); margin-left: 0.4em; letter-spacing: 0; white-space: nowrap; }
    .role { color: var(--muted); margin: 0 0 1rem; }
    .links { display: flex; flex-wrap: wrap; gap: 0.35rem 1.25rem; font-weight: 600; }
    .avatar {
      position: relative;
      width: 136px; height: 136px;
      border-radius: 50%;
      overflow: hidden;
      background: var(--accent-soft);
      color: var(--accent);
      display: grid; place-items: center;
      font: 600 2.6rem/1 var(--serif);
      letter-spacing: 0.02em;
    }
    .avatar img { position: absolute; inset: 0; width: 100%; height: 100%; object-fit: cover; }

    .callout {
      margin: 2.25rem 0 0;
      padding: 0.9rem 1.15rem;
      background: var(--accent-soft);
      border-left: 3px solid var(--accent);
      border-radius: 0 8px 8px 0;
    }

    /* Sections */
    section { margin-top: 3rem; }
    h2 {
      font-size: 0.78rem;
      font-weight: 700;
      letter-spacing: 0.09em;
      text-transform: uppercase;
      color: var(--muted);
      margin: 0 0 1.2rem;
      padding-bottom: 0.45rem;
      border-bottom: 1px solid var(--rule);
    }
    h3 { font-size: 1rem; font-weight: 600; margin: 1.75rem 0 0.75rem; }
    h3:first-of-type { margin-top: 0; }

    /* News + dated rows */
    .rows li {
      display: grid;
      grid-template-columns: 11rem 1fr;
      gap: 0.25rem 1.25rem;
      padding: 0.3rem 0;
    }
    .news li { grid-template-columns: 5.5rem 1fr; }
    .when { color: var(--muted); font-variant-numeric: tabular-nums; white-space: nowrap; }
    .rows .sub { display: block; color: var(--muted); font-size: 0.94rem; }

    /* Publications + projects */
    .entries > li { margin-bottom: 1.4rem; }
    .entries > li:last-child { margin-bottom: 0; }
    .title { font-weight: 600; margin: 0 0 0.15rem; }
    .authors { color: var(--muted); font-size: 0.95rem; margin: 0 0 0.3rem; }
    .me { color: var(--text); font-weight: 600; }
    .meta { font-size: 0.92rem; margin: 0 0 0.35rem; display: flex; flex-wrap: wrap; align-items: center; gap: 0.3rem 0.75rem; }
    .meta .note { color: var(--muted); }
    .tag {
      display: inline-block;
      padding: 0.08rem 0.6rem;
      border-radius: 999px;
      background: var(--tag-bg);
      color: var(--tag-text);
      font-size: 0.8rem;
      font-weight: 600;
    }
    .summary { font-size: 0.95rem; margin: 0; }

    .skills p { margin: 0 0 0.35rem; }
    .skills strong { font-weight: 600; }

    footer {
      margin-top: 3.5rem;
      padding-top: 1rem;
      border-top: 1px solid var(--rule);
      color: var(--muted);
      font-size: 0.88rem;
    }

    @media (max-width: 640px) {
      body { font-size: 16px; }
      .page { padding: 32px 16px 40px; }
      .intro { grid-template-columns: 1fr; gap: 18px; }
      .avatar { order: -1; width: 96px; height: 96px; font-size: 1.9rem; }
      h1 { font-size: 2rem; }
      .rows li, .news li { grid-template-columns: 1fr; gap: 0; padding: 0.45rem 0; }
      section { margin-top: 2.5rem; }
    }
    @media print {
      .page { padding: 0; }
      .callout { border-left-width: 2px; }
      a { color: inherit; }
    }
  </style>
</head>
<body>
  <div class="page">
    <header class="intro">
      <div>
        <h1>Junsung Kim<span class="ko" lang="ko">김준성</span></h1>
        <p class="role">
          M.S. student in Electrical Engineering and Computer Science<br>
          <a href="https://www.gist.ac.kr/">GIST</a> · INFONET Lab · Gwangju, South Korea
        </p>
        <nav class="links" aria-label="Contact and profiles">
          <a href="mailto:wnstjd123@gm.gist.ac.kr">Email</a>
          <a href="Junsung_Kim_CV.pdf">CV</a>
          <a href="https://github.com/ClementKim">GitHub</a>
          <a href="https://www.linkedin.com/in/ClementKim">LinkedIn</a>
        </nav>
      </div>
      <div class="avatar">
        <span aria-hidden="true">JK</span>
        <!-- To show a photo, add a square image named profile.jpg next to this file. -->
        <img src="profile.jpg" alt="Junsung Kim" width="136" height="136" onerror="this.remove()">
      </div>
    </header>

    <p class="callout">
      <strong>Open to Research Engineer roles</strong> in multimodal and vision–language AI.
      I graduate in February 2027. <a href="mailto:wnstjd123@gm.gist.ac.kr">Get in touch</a>
    </p>

    <main>
      <section id="about" aria-labelledby="about-h">
        <h2 id="about-h">About</h2>
        <p>
          I'm an M.S. student in Electrical Engineering and Computer Science at the Gwangju Institute of Science and
          Technology (GIST), working in the INFONET Lab with Prof. Heung-No Lee. My research is on
          <strong>vision–language learning and visual reasoning</strong>, with a focus on
          <strong>interaction-conditioned mixture-of-experts</strong>: using image–text interactions to weight experts
          inside a model, and analyzing what that routing actually learns. I've also worked on
          <strong>hyperspectral imaging</strong> for face anti-spoofing and identification.
        </p>
        <p>
          My work covers both modeling and engineering, from designing vision–language connectors to building data
          pipelines and multi-GPU training with LoRA and BF16 on A100s. Before GIST, I studied Software and Computer
          Science, and Political Science and Diplomacy, at Ajou University.
        </p>
      </section>

      <section id="news" aria-labelledby="news-h">
        <h2 id="news-h">News</h2>
        <ul class="rows news">
          <li><span class="when">2026</span><span>Our paper on retrieval-augmented generation for interpreting Korean Minhwa folk art was accepted to the ORACLE Workshop at EMNLP 2026.</span></li>
          <li><span class="when">Feb 2026</span><span>Three papers at the KICS Winter Conference, including my first-author paper on hyperspectral face anti-spoofing with a CNN-MoE.</span></li>
          <li><span class="when">Apr 2025</span><span>2nd place at the AI Agent &amp; Blockchain Innovation Challenge (The Academic Frontier 2025).</span></li>
          <li><span class="when">2025</span><span>Started my M.S. at GIST with a Korean Government Scholarship.</span></li>
        </ul>
      </section>

      <section id="publications" aria-labelledby="pubs-h">
        <h2 id="pubs-h">Publications</h2>

        <h3>Under review</h3>
        <ol class="entries">
          <li>
            <p class="title">IP-MoE: Studying spatial token–patch interactions and dense expert weighting</p>
            <p class="authors"><span class="me">Junsung Kim</span>, Youngin Choi, Minjun Song, Sumin Kim, Surin Lee, Heung-No Lee</p>
            <p class="summary">
              A vision–language connector in which bilinear token–patch interactions weight a dense mixture of six
              spatial experts and condition the language model (frozen CLIP encoders + Llama-3.2-3B-Instruct). Trained in
              two stages on LLaVA-NeXT data across six A100 GPUs, compared with additive interactions and uniform
              weighting on seven benchmarks, and analyzed through routing entropy and per-subtask results.
            </p>
          </li>
          <li>
            <p class="title">Beyond answer preservation: Scientific evidence minimization for private LLM reasoning</p>
            <p class="authors">Surin Lee, <span class="me">Junsung Kim</span>, Minjun Song, Sumin Kim, Heung-No Lee</p>
            <p class="summary">
              My part: dataset construction for the benchmark (160 workflows and 800 tasks across four domains),
              feedback on the method, and review of the manuscript's reasoning.
            </p>
          </li>
        </ol>

        <h3>Workshop paper</h3>
        <ol class="entries">
          <li>
            <p class="title">Retrieval-augmented generation for symbolic folk-art interpretation: Comparing dense and graph-based retrieval using Korean Minhwa</p>
            <p class="authors">Minjun Song, Sumin Kim, <span class="me">Junsung Kim</span>, Yebeen Lee, Heung-No Lee</p>
            <p class="meta"><span class="tag">ORACLE Workshop at EMNLP 2026</span></p>
          </li>
        </ol>

        <h3>Domestic conference papers</h3>
        <ol class="entries">
          <li>
            <p class="title">An HSI-based CNN-MoE framework for face anti-spoofing and identification</p>
            <p class="authors"><span class="me">Junsung Kim</span>, Youngin Choi, Heung-No Lee</p>
            <p class="meta"><span class="tag">KICS Winter Conference 2026</span><span class="note">pp. 204–205</span><a href="https://github.com/ClementKim/cnn-moe-fas">Code</a></p>
            <p class="summary">
              A VGG-style CNN with four sparsely gated experts for hyperspectral face anti-spoofing and identification,
              on 4,374 images from 54 subjects. Raises 4-class live/spoof accuracy from 82.8% to 93.7% over a CNN-only
              baseline.
            </p>
          </li>
          <li>
            <p class="title">AI-assisted dataset creation pipeline for Korean Minhwa</p>
            <p class="authors">Minjun Song, Sumin Kim, <span class="me">Junsung Kim</span>, Heung-No Lee</p>
            <p class="meta"><span class="tag">KICS Winter Conference 2026</span><span class="note">pp. 1596–1597</span></p>
          </li>
          <li>
            <p class="title">A prompt-based pipeline for generative game asset synthesis and evaluation</p>
            <p class="authors">Yongtae Lee, <span class="me">Junsung Kim</span>, Heung-No Lee</p>
            <p class="meta"><span class="tag">KICS Winter Conference 2026</span><span class="note">pp. 1604–1605</span></p>
          </li>
        </ol>
      </section>

      <section id="projects" aria-labelledby="projects-h">
        <h2 id="projects-h">Projects</h2>
        <ul class="entries">
          <li>
            <p class="title">InteractSeg: Bilinear interaction learning for material segmentation</p>
            <p class="meta"><span class="note">Final project, Computer Vision · GIST, 2026</span><a href="https://github.com/ClementKim/InteractSeg">Code</a></p>
            <p class="summary">
              Per-pixel material segmentation on MINC and OpenSurfaces with a ViT-S + ResNet-34 dual encoder and
              mixture-of-experts modules.
            </p>
          </li>
          <li>
            <p class="title">BCAI_A2A: An agent-to-agent marketplace for AI services</p>
            <p class="meta"><span class="note">With Minjun Song · Final project, Generative AI and Blockchain · GIST, 2025</span><a href="https://github.com/paulmjsong/BCAI_A2A">Code</a></p>
            <p class="summary">
              A proof-of-concept marketplace where AI agents request and pay for services over the Agent-to-Agent (A2A)
              protocol, with payments verified on-chain by an EVM smart contract.
            </p>
          </li>
          <li>
            <p class="title">Compressive-sensing spectrometer</p>
            <p class="meta"><span class="note">Python · NumPy, SciPy</span><a href="https://github.com/ClementKim/spectrometer">Code</a></p>
            <p class="summary">
              Reconstructs spectra from measurements with non-negative L1-regularized least squares, with scripts for
              experimental data processing and infrared cut-off filter design.
            </p>
          </li>
        </ul>
      </section>

      <section id="education" aria-labelledby="edu-h">
        <h2 id="edu-h">Education</h2>
        <ul class="rows">
          <li>
            <span class="when">2025 – Feb 2027</span>
            <span><strong>M.S. in Electrical Engineering and Computer Science</strong>, GIST
              <span class="sub">Expected February 2027 · Advisor: Prof. Heung-No Lee</span></span>
          </li>
          <li>
            <span class="when">2019 – 2025</span>
            <span><strong>B.S. in Software and Computer Science</strong> and <strong>B.A. in Political Science and Diplomacy</strong>, Ajou University</span>
          </li>
        </ul>
      </section>

      <section id="honors" aria-labelledby="honors-h">
        <h2 id="honors-h">Honors &amp; awards</h2>
        <ul class="rows">
          <li>
            <span class="when">2025 – present</span>
            <span><strong>Korean Government Scholarship</strong>
              <span class="sub">Full tuition and stipend for graduate study</span></span>
          </li>
          <li>
            <span class="when">Apr 2025</span>
            <span><strong>2nd Place</strong>, AI Agent &amp; Blockchain Innovation Challenge, The Academic Frontier 2025
              <span class="sub">Presented Planisphere, a proposed decentralized platform for AI-agent prediction competitions</span></span>
          </li>
        </ul>
      </section>

      <section id="service" aria-labelledby="service-h">
        <h2 id="service-h">Service &amp; leadership</h2>
        <ul class="rows">
          <li>
            <span class="when">Mar 2025 – present</span>
            <span><strong>Knowledge-sharing volunteer</strong>, GIST PIUM
              <span class="sub">Science education and academic and career mentoring for school students, including those in underserved communities</span></span>
          </li>
          <li>
            <span class="when">Sep 2024</span>
            <span><strong>Organizer and speaker</strong>, AI Nights, Ajou University
              <span class="sub">Organized an on-campus AI conference and gave a talk on K-means and DBSCAN</span></span>
          </li>
          <li>
            <span class="when">Jul – Sep 2024</span>
            <span><strong>Team leader</strong>, Daesin-Learning, Ajou University
              <span class="sub">Led a university-supported machine-learning and deep-learning study group</span></span>
          </li>
          <li>
            <span class="when">Feb 2021 – Nov 2022</span>
            <span><strong>Social service agent</strong>, National Election Commission
              <span class="sub">Mandatory national service as an administrative assistant</span></span>
          </li>
        </ul>
      </section>

      <section id="skills" class="skills" aria-labelledby="skills-h">
        <h2 id="skills-h">Skills</h2>
        <p><strong>Programming and frameworks:</strong> Python, PyTorch</p>
        <p><strong>Training and infrastructure:</strong> multi-GPU distributed training (LoRA, BF16), Docker, Ubuntu/Linux</p>
        <p><strong>Languages:</strong> Korean, English</p>
      </section>
    </main>

    <footer>Last updated October 2026</footer>
  </div>
</body>
</html>
