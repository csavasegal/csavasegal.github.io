---
layout: posts
title:
---

<style>
:root {
  --accent: #4169E1;
  --accent-dark: #2952CC;
  --text-main: #333;
  --text-muted: #666;
  --bg-soft: #F0F4F8;
  --mint: #4FC3A1;
  --mint-dark: #1F7A5E;
  --mint-light: #EDFAF4;
}

/* ---------- Base ---------- */

.content-section {
  max-width: 800px;
  margin: 0 auto;
  line-height: 1.8;
  color: var(--text-main);
}

.content-section p {
  margin-bottom: 1.5rem;
}

h1, h2 {
  color: var(--accent);
}

a {
  color: var(--accent);
  font-weight: 500;
  text-decoration: none;
}

a:hover {
  color: var(--accent-dark);
}

/* ---------- Hero ---------- */

.hero-section {
  text-align: center;
  padding: 2.5rem 2rem;
  background: var(--bg-soft);
  border-radius: 12px;
  margin-bottom: 3rem;
}

.profile-photo {
  width: 180px;
  height: 180px;
  object-fit: cover;
  object-position: center;
  border-radius: 50%;
  margin-bottom: 1.5rem;
  border: 4px solid var(--accent);
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.12);
}

.hero-section h1 {
  font-size: 2.2rem;
  font-weight: 600;
  letter-spacing: -0.02em;
  margin-bottom: 0.25rem;
}

.hero-section p {
  color: var(--text-muted);
  margin: 0;
}

.hero-subtitle {
  font-size: 1.1rem;
}

.hero-affiliation {
  font-size: 1rem;
}

/* ---------- Social Links ---------- */

.social-links {
  display: flex;
  justify-content: center;
  gap: 2rem;
  flex-wrap: wrap;
  margin-top: 1.75rem;
}

.social-link {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0.5rem;
  border-radius: 6px;
  color: var(--accent);
  transition: transform 0.15s, background-color 0.15s;
}

.social-link:hover {
  transform: translateY(-2px);
  background-color: rgba(65, 105, 225, 0.08);
}

.social-link img {
  width: 34px;
  height: 34px;
  margin-bottom: 0.25rem;
}

.social-link span {
  font-size: 0.85rem;
  font-weight: 500;
}

/* ---------- Buttons ---------- */

.button {
  display: inline-block;
  padding: 0.75rem 1.5rem;
  border-radius: 6px;
  font-weight: 500;
  transition: background-color 0.2s, transform 0.15s;
}

.button-primary {
  background-color: var(--mint-dark);
  color: white;
}

.button-primary:hover {
  background-color: #17614A;
  color: white;
  transform: translateY(-1px);
}

.button-secondary {
  background-color: var(--mint-light);
  border: 2px solid var(--mint);
  color: var(--mint-dark);
}

.button-secondary:visited {
  color: var(--mint-dark);
}

.button-secondary:hover {
  background-color: var(--mint-dark);
  border-color: var(--mint-dark);
  color: white;
  transform: translateY(-1px);
}

/* ---------- Content sections ---------- */

.research-highlight,
.info-card {
  margin: 2.5rem 0;
}

.research-highlight h2,
.info-card h2 {
  margin-top: 0;
  margin-bottom: 1.25rem;
  text-align: center;
  padding-bottom: 0.4rem;
  border-bottom: 1px solid #ddd;
}

.research-highlight p strong {
  font-weight: 600;
}

.centered-heading {
  text-align: center;
}


.info-card p:last-child {
  margin-bottom: 0;
}

.info-card a {
  color: #4169E1;
  font-weight: 500;
}

/* ---------- Divider ---------- */

.section-divider {
  margin: 3.5rem 0;
  border: 0;
  border-top: 1px solid #ddd;
}
</style>

<div class="hero-section">
  <img src="/img/sava-segal_clara.jpg" alt="Clara A. Sava-Segal" class="profile-photo">

  <h1>Clara A. Sava-Segal</h1>
  <p class="hero-subtitle">Wu Tsai Institute Postdoctoral Fellow</p>
  <p class="hero-affiliation">Yale University</p>

  <div class="social-links">
    <a href="mailto:clara.sava-segal@yale.edu" class="social-link">
      <img src="/img/email.png" alt="Email">
      <span>Email</span>
    </a>
    <a href="https://scholar.google.com/citations?user=c0vFC1MAAAAJ&hl=en" class="social-link">
      <img src="/img/scholar.png" alt="Google Scholar">
      <span>Scholar</span>
    </a>
    <a href="https://orcid.org/0000-0002-3010-3858" class="social-link">
      <img src="/img/orcid.png" alt="ORCID">
      <span>ORCID</span>
    </a>
    <a href="https://bsky.app/profile/csavasegal.bsky.social" class="social-link">
      <img src="/img/bsky.png" alt="bsky">
      <span>bsky</span>
    </a>
    <a href="https://github.com/csavasegal" class="social-link">
      <img src="/img/github.png" alt="GitHub">
      <span>GitHub</span>
    </a>
    <a href="/Sava_Segal_CV_2.pdf" class="social-link" target="_blank">
      <img src="/img/CV.png" alt="CV">
      <span>CV</span>
    </a>
  </div>
</div>

<div class="research-highlight">

  <h2>Research Focus</h2>

  <p>
    I am a <a href="https://wti.yale.edu/">Wu Tsai Institute Postdoctoral Fellow</a> at Yale,
    working with <a href="https://medicine.yale.edu/lab/goldfarb/research/">Elizabeth Goldfarb</a> (Psychiatry)
    and <a href="https://www.wendyberrymendes.com/">Wendy Berry Mendes</a> (Psychology).
    I got my PhD in Cognitive Neuroscience at Dartmouth College with
    <a href="https://thefinnlab.github.io/">Emily Finn</a>, using neuroimaging and behavioral methods
    to study how we integrate incoming information with existing knowledge.
    I focused on why two people—or the same person at different times—can perceive identical
    information differently, and how these differences shape reinterpretation and memory.
    That work was supported by an <span style="color: #4169E1; font-weight: 500;">NIMH F31 NRSA Fellowship</span>
    and an <span style="color: #4169E1; font-weight: 500;">NSF GRFP</span>.
    In my postdoc, I am extending this work to brain–body–behavior interactions.
    I examine how endocrine and physiological processes shape these behaviors, with a particular
    focus on stress.
  </p>

  <p>
    <strong>BACKGROUND:</strong> I received my Bachelor’s degree from the University of Chicago,
    where I completed my undergraduate thesis with <a href="http://casasanto.com/">Daniel Casasanto</a>
    and was fortunate enough to also work with
    <a href="https://voices.uchicago.edu/gomezlab/">Christopher Gomez</a> and in the
    <a href="https://awhvogellab.com/">Awh-Vogel Lab</a>. Following graduation, I worked at Stanford in
    <a href="https://med.stanford.edu/parvizi-lab.html">Josef Parvizi’s lab</a>.
    I tend to favor more "naturalistic" paradigms, but I also try to balance the richness of
    real-world stimuli with the experimental control needed to isolate specific mechanisms.
  </p>

  <p style="text-align: center; margin-top: 2rem; display: flex; justify-content: center; gap: 1rem; flex-wrap: wrap;">
    <a href="/publications/" class="button button-secondary">
      Click to See Selected Publications
    </a>
  </p>

</div>




  <hr class="section-divider">

  <div class="info-card">
    <h2>Beyond Research</h2>

    <p>
      I care a lot about science communication and public education. Prior to graduate school,
      I worked in classrooms at both ends of the K–12 spectrum (Pre-K and 12th grade). More recently, I’ve designed and taught 5+
      discussion-based neuroscience and psychology courses for adult learners (ages 50+) at the
      Osher Lifelong Learning Institute at Dartmouth.
    </p>

    <p>
      I also enjoy bridging science and the arts, and many of my research questions apply
      directly to the real world. For instance, we created
      <a href="http://finnlabmuseum.com/">ArtLibs</a>, a collaborative project with the
      Hood Museum at Dartmouth where we get to explore these ideas outside the lab,
      funded by an internal Arts Integration Grant.
    </p>

    <p style="text-align: center; margin-top: 2rem; display: flex; justify-content: center; gap: 1rem; flex-wrap: wrap;">
      <a href="/teaching/" class="button button-secondary">
        Learn More About My Teaching
      </a>
      <a href="http://finnlabmuseum.com/" class="button button-secondary" target="_blank">
        Participate in ArtLibs
      </a>
    </p>
  </div>
