---
layout: posts
title:
---

<style>
:root {
  --accent: #4169E1;
  --accent-dark: #2952CC;
  --text-main: #1F3328;
  --text-muted: #56665C;
  --bg-soft: #F0F4F8;
  --mint: #4169E1;
  --mint-dark: #4169E1;
  --mint-light: #EEF2FC;
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
  padding: 1.5rem 0 0;
  margin-bottom: 2rem;
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

/* ---------- Content section ---------- */

.research-highlight {
  margin: 2.5rem 0;
}

/* ragged-right prose, no hyphenation */
.research-highlight p {
  text-align: left;
}

.research-highlight p strong {
  font-weight: 600;
}

/* ---------- Links in the bio: ink text on a periwinkle highlighter stripe ---------- */

.research-highlight a {
  color: var(--text-main);
  font-weight: 600;
  text-decoration: none;
  background: linear-gradient(#DCE3FB, #DCE3FB) no-repeat left bottom / 100% 0.45em;
  -webkit-box-decoration-break: clone;
  box-decoration-break: clone;
  transition: background-size 0.2s;
}

.research-highlight a:hover {
  color: var(--text-main);
  background-size: 100% 100%;
}

/* ---------- Skyline ---------- */

.skyline {
  position: relative;
  margin: -1.5rem 0 2.5rem;
}

/* three hover zones over the drawing; hovering one fades the other two */
.sky-zone {
  position: absolute;
  top: 0;
  bottom: 0;
  background: rgba(255, 255, 255, 0);
  transition: background-color 0.3s;
  cursor: default;
  outline: none;
}

.skyline:hover .sky-zone,
.skyline:focus-within .sky-zone {
  background: rgba(255, 255, 255, 0.8);
}

.skyline .sky-zone:hover,
.skyline .sky-zone:focus {
  background: rgba(255, 255, 255, 0);
}

.sky-label {
  position: absolute;
  top: 100%;
  left: 50%;
  transform: translate(-50%, 0.2rem);
  white-space: nowrap;
  font-size: 0.8rem;
  color: var(--text-muted);
  opacity: 0;
  transition: opacity 0.3s;
  pointer-events: none;
}

.sky-zone:hover .sky-label,
.sky-zone:focus .sky-label,
.sky-zone.lit .sky-label {
  opacity: 1;
}

/* hovering a place name in the text lights up that part of the drawing */
.skyline.text-hover .sky-zone {
  background: rgba(255, 255, 255, 0.8);
}

.skyline.text-hover .sky-zone.lit {
  background: rgba(255, 255, 255, 0);
}


.skyline img {
  display: block;
  width: 100%;
  height: auto;
  opacity: 0.85;
}

.centered-heading {
  text-align: center;
}
</style>

<div class="hero-section">
  <img src="/img/sava-segal_clara.jpg" alt="Clara A. Sava-Segal" class="profile-photo">

  <h1>Clara A. Sava-Segal</h1>
  <p class="hero-subtitle">Wu Tsai Institute Postdoctoral Fellow</p>
  <p class="hero-affiliation"><span class="sky-ref" data-sky="yale">Yale University</span></p>

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

  <p>
    <span class="sky-ref" data-sky="yale">I am a <a href="https://wti.yale.edu/">Wu Tsai Institute Postdoctoral Fellow</a> at Yale,
    working with <a href="https://medicine.yale.edu/lab/goldfarb/research/">Elizabeth Goldfarb</a> (Psychiatry)
    and <a href="https://www.wendyberrymendes.com/">Wendy Berry Mendes</a> (Psychology).</span>
    <span class="sky-ref" data-sky="dartmouth">I got my PhD in Cognitive Neuroscience at Dartmouth College with
    <a href="https://thefinnlab.github.io/">Emily Finn</a>, using neuroimaging and behavioral methods
    to study how we integrate incoming information with existing knowledge.
    I focused on why two people—or the same person at different times—can perceive identical
    information differently, and how these differences shape reinterpretation and memory.
    That work was supported by an <span style="font-weight: 600;">NIMH F31 NRSA Fellowship</span>
    and an <span style="font-weight: 600;">NSF GRFP</span>.</span>
    <span class="sky-ref" data-sky="yale">In my postdoc, I am extending this work to brain–body–behavior interactions.
    I examine how endocrine and physiological processes shape these behaviors, with a particular
    focus on stress.</span>
    I tend to favor more "naturalistic" paradigms, but I also try to balance the richness of
    real-world stimuli with the experimental control needed to isolate specific mechanisms.
  </p>

  <p>
    <span class="sky-ref" data-sky="chicago">Before graduate school, I received my Bachelor’s degree from the University of Chicago,
    where I completed my undergraduate thesis with <a href="http://casasanto.com/">Daniel Casasanto</a>
    and was fortunate enough to also work with
    <a href="https://voices.uchicago.edu/gomezlab/">Christopher Gomez</a> and in the
    <a href="https://awhvogellab.com/">Awh-Vogel Lab</a>.</span> Following graduation, I worked at Stanford in
    <a href="https://med.stanford.edu/parvizi-lab.html">Josef Parvizi’s lab</a>.
  </p>

  <p>
    I care a lot about teaching. I've taught at all ends of the spectrum, from Pre-K to older adults. Most recently, I've designed and
    taught 5+ discussion-based <a href="/osher/">neuroscience and psychology courses</a> for adults 50+
    at Dartmouth's <a href="https://osher.dartmouth.edu/get_involved/study_leaders/meet_study_leaders/clarasavasegal/index.php">Osher Lifelong Learning Institute</a>. I also care about bringing science
    outside the lab: check out <a href="http://finnlabmuseum.com/">ArtLibs</a>, our project with
    Dartmouth's Hood Museum.
  </p>

</div>

<!-- Chicago → Hanover → New Haven -->
<div class="skyline">
  <img src="/img/skyline_chicago_hanover_newhaven.png"
       alt="Line drawing of the Chicago skyline, a stretch of trees, and New Haven's Yale towers, joined by one rolling line">
  <div class="sky-zone" data-sky="chicago" style="left: 0; width: 37.5%;" tabindex="0">
    <span class="sky-label">Chicago · University of Chicago</span>
  </div>
  <div class="sky-zone" data-sky="dartmouth" style="left: 37.5%; width: 28.5%;" tabindex="0">
    <span class="sky-label">Hanover · Dartmouth College</span>
  </div>
  <div class="sky-zone" data-sky="yale" style="left: 66%; width: 34%;" tabindex="0">
    <span class="sky-label">New Haven · Yale University</span>
  </div>
</div>

<script>
  // Hovering a Chicago, Dartmouth or Yale sentence in the text highlights that part of the skyline
  (function () {
    var skyline = document.querySelector('.skyline');
    if (!skyline) return;
    document.querySelectorAll('.sky-ref').forEach(function (ref) {
      var zone = skyline.querySelector('.sky-zone[data-sky="' + ref.dataset.sky + '"]');
      ref.addEventListener('mouseenter', function () {
        skyline.classList.add('text-hover');
        zone.classList.add('lit');
      });
      ref.addEventListener('mouseleave', function () {
        skyline.classList.remove('text-hover');
        zone.classList.remove('lit');
      });
    });
  })();
</script>
