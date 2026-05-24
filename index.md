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

.button-secondary:visited {
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





/* ---------- Info Card ---------- */

.info-card {
  background-color: #f7f9fc;
  padding: 1.75rem;
  border-radius: 10px;
  border: 1px solid #e4eaf5;
  border-top: 3px solid var(--accent);
  margin: 2rem 0;
}

.info-card h2 {
  margin-top: 0;
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
  height: 2px;
  background: linear-gradient(to right, transparent, var(--accent), transparent);
  opacity: 0.5;
}
</style>

<div class="hero-section">
  <img src="/img/sava-segal_clara.png" alt="Clara A. Sava-Segal" class="profile-photo">

  <h1>Clara A. Sava-Segal</h1>
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

  <p><strong>
    How and why do two people "see" (interpret) and remember the same experience so differently?
  </strong></p>

  <p>
    Using neuroimaging and behavioral methods, I investigate how we integrate incoming
    information with existing knowledge and how this differs meaningfully at the individual level.
    Specifically, I study how two people—or the same person at different times—can reach
    different perceptions of identical information, and how these differences shape memory.
  </p>

  <p>
    I am a Cognitive Neuroscience PhD candidate advised by
    <a href="https://thefinnlab.github.io/">Emily Finn</a> at Dartmouth College,
    working in the Functional Imaging and Naturalistic Neuroscience Lab (FINN Lab).
    I am currently funded by an <span style="color: #4169E1; font-weight: 500;">NIMH F31 NRSA Fellowship</span>
    and was previously supported by an <span style="color: #4169E1; font-weight: 500;">NSF GRFP</span>.
    I am finishing up this spring and will be starting a postdoc this fall.
  </p>

  <p style="text-align: center; margin-top: 2rem; display: flex; justify-content: center; gap: 1rem; flex-wrap: wrap;">
    <a href="/publications/" class="button button-secondary">
      Learn More About My Research
    </a>
  </p>

</div>




  <hr class="section-divider">

  <div class="info-card">
    <h2>Background</h2>

    <p>
      I earned my Bachelor’s degree from the University of Chicago, where I studied a combination of psychology,
      neurobiology, and human development, and completed my undergraduate thesis with
      <a href="http://casasanto.com/">Daniel Casasanto</a>. I also worked with
      <a href="https://voices.uchicago.edu/gomezlab/">Christopher Gomez</a> and in the
      <a href="https://awhvogellab.com/">Awh-Vogel Lab</a>. Following graduation, I worked as a
      lab manager and research assistant at Stanford in
      <a href="https://med.stanford.edu/parvizi-lab.html">Josef Parvizi’s lab</a>. My training
      spans electrophysiology, functional network dynamics, and the cognitive neuroscience of
      symbolic systems. In my PhD work, I have tended to favor more "naturalistic" paradigms,
      but I also try to balance the richness of real-world stimuli with the experimental control
      needed to isolate specific mechanisms. I hope to continue to do that in future work.
    </p>
  </div>

  <div class="info-card">
    <h2>Beyond Research</h2>

    <p>
      I’m passionate about science communication and public education. Prior to graduate school,
      I did medical editing and worked in classrooms at both ends of the K–12 spectrum
      (Pre-K and 12th grade). More recently, I’ve designed and taught 5+ discussion-based
      neuroscience and psychology courses for adult learners (ages 50+) at the
      Osher Lifelong Learning Institute at Dartmouth — an experience I’ve found incredibly rewarding.
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
