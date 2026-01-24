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
  background: linear-gradient(135deg, var(--bg-soft) 0%, #E8EEF2 100%);
  border-radius: 12px;
  margin-bottom: 3rem;
}

.profile-photo {
  width: 180px;
  height: 180px;
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
  background-color: var(--accent);
  color: white;
}

.button-primary:hover {
  background-color: var(--accent-dark);
  transform: translateY(-1px);
}

.button-secondary {
  background-color: #e8ecf8;
  color: var(--accent);
}

.button-secondary:hover {
  background-color: var(--accent-dark);
  color: white;
}

/* ---------- Research Highlight ---------- */

.research-highlight {
  background-color: #f7f9fc;
  padding: 1.75rem;
  border-radius: 10px;
  border-top: 3px solid var(--accent);
  margin: 2.5rem 0;
}

.research-highlight h2 {
  margin-top: 0;
  text-align: center;

}

.research-highlight p strong {
  font-weight: 600;
}
.centered-heading {
  text-align: center;
}





/* ---------- Divider ---------- */

.section-divider {
  margin: 3.5rem 0;
  border: 0;
  height: 2px;
  background: linear-gradient(to right, transparent, var(--accent), transparent);
  opacity: 0.5;
}
</style>

<div class="hero-section">
  <img src="/img/sava-segal_clara.png" alt="Clara Sava-Segal" class="profile-photo">

  <h1>Clara Sava-Segal</h1>
  <p class="hero-subtitle">PhD Candidate in Cognitive Neuroscience</p>
  <p class="hero-affiliation">Dartmouth College</p>

  <div class="social-links">
    <a href="mailto:csava.gr@dartmouth.edu" class="social-link">
      <img src="/img/email.png" alt="Email">
      <span>Email</span>
    </a>
    <a href="https://scholar.google.com/citations?user=c0vFC1MAAAAJ&hl=en" class="social-link">
      <img src="/img/scholar.png" alt="Google Scholar">
      <span>Scholar</span>
    </a>
    <a href="https://twitter.com/csavasegal" class="social-link">
      <img src="/img/twitter.png" alt="Twitter">
      <span>Twitter</span>
    </a>
    <a href="https://github.com/csavasegal" class="social-link">
      <img src="/img/github.png" alt="GitHub">
      <span>GitHub</span>
    </a>
  </div>
</div>

<div class="research-highlight">

  <h2>Research Focus</h2>

  <p><strong>
    How do our past experiences inform how we process new information?
    How do individuals reach different interpretations of the exact same experience?
  </strong></p>

  <p>
    Using neuroimaging and behavioral methods, I investigate how we integrate incoming
    information with existing knowledge and how this differs meaningfully at the individual level.
    Specifically, I study how two people—or the same person at different times—can reach
    different perceptions of identical information, and the impact this has on our memories.
  </p>

  <p>
    My training spans electrophysiology, functional network dynamics, and the cognitive
    neuroscience of symbolic systems. Building on this foundation, my current work focuses on
    naturalistic stimuli, examining how state-dependent changes in neural activity during the
    encoding of dynamic, real-world information influence interpretation and memory.
  </p>

  <p>
    I am a Cognitive Neuroscience PhD candidate advised by
    <a href="https://thefinnlab.github.io/">Emily Finn</a> at Dartmouth College,
    working in the Functional Imaging and Naturalistic Neuroscience Lab (Finn Lab).
    I am currently funded by an F31 NRSA Fellowship and was previously supported by an NSF GRFP.
  </p>

  <p style="text-align: center; margin-top: 2rem;">
    <a href="/publications/" class="button button-secondary">
      Learn More About My Research
    </a>
  </p>

</div>




  <hr class="section-divider">

  <h2 class="centered-heading">Background</h2>

  <p>
    I earned my Bachelor's degree from the University of Chicago, where I completed my thesis
    with <a href="http://casasanto.com/">Daniel Casasanto</a> and worked with
    <a href="https://voices.uchicago.edu/gomezlab/">Christopher Gomez</a> and in the
    <a href="https://awhvogellab.com/">Awh-Vogel Lab</a>.
  </p>

  <p>
    Following graduation, I worked as a lab manager and research assistant at Stanford in
    <a href="https://med.stanford.edu/parvizi-lab.html">Josef Parvizi’s lab</a>,
    gaining experience with intracranial recordings and human neuroscience research.
  </p>

  <h2 class="centered-heading">Beyond Research</h2>

  <p>
    I'm passionate about science communication and public education. Prior to graduate school,
    I did medical editing and worked in classrooms at both ends of the K–12 spectrum
    (Pre-K and 12th grade). Most recently, I’ve been designing and teaching discussion-based
    courses for older students (ages 50+) at the Osher Lifelong Learning Institute at Dartmouth,
    which I’ve found incredibly rewarding.
  </p>

  <p>
    Outside of research, I also enjoy bringing science to creative projects in the real world —
    check out <a href="http://finnlabmuseum.com/">ArtLibs</a>, a collaborative art project with the
    Hood Museum at Dartmouth, funded by an internal Arts Integration Grant.
  </p>

  <p style="text-align: center; margin-top: 2.5rem;">
    <a href="/teaching/" class="button button-secondary">
      Learn More About My Teaching
    </a>
  </p>
