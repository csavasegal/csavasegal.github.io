---
layout: category
title: 
permalink: /publications/
---

<style>
  :root {
  --accent-mint: #4FC3A1;        /* borders, outlines */
  --accent-mint-dark: #1F7A5E;   /* hover fills, text on white */
  --accent-mint-light: #EDFAF4;  /* button fill */

  --fs-title: 1.563rem; /* page title only — matches the h1 on the Teaching page */
  --fs-lg: 1.25rem;     /* section headers (= About Me h2) */
  --fs-base: 1rem;      /* all prose: titles, authors, links, filter labels */
  --fs-sm: 0.85rem;     /* chrome: tags, buttons, labels, legend */
}

  .page-header {
    text-align: center;
    margin-bottom: 2.5rem;
    padding: 1.5rem 0;
    background: none;
    border-bottom: 1px solid #e6e6e6;
  }

  .page-header h1 {
    font-size: var(--fs-title);
    color: #4169E1;
    margin-bottom: 0.5rem;
  }

  .page-intro {
    font-size: var(--fs-base);
    line-height: 1.8;
    margin-bottom: 2rem;
    color: #555;
  }

  .meta-row {
    display: flex;
    flex-wrap: wrap;
    align-items: baseline;
    gap: 0.3rem 1.5rem;
    font-size: var(--fs-sm);
    color: #777;
    font-weight: 400;
    margin-bottom: 1.5rem;
    padding-bottom: 0.75rem;
    border-bottom: 1px solid #eee;
  }

  /* the marker itself picks up the same blue as the star in the gutter */
  .meta-row .mark {
    color: #4169E1;
    font-weight: 700;
    margin-right: 0.15rem;
  }

  .section-header {
    font-size: var(--fs-lg);
    font-weight: 700;
    color: #4169E1;
    margin-top: 3rem;
    margin-bottom: 1.5rem;
    padding-bottom: 0.4rem;
    border-bottom: 1px solid #ddd;
  }

  body {
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-size: var(--fs-base);
    color: #333;
    line-height: 1.7;
  }

.publication-item {
  margin: 0;
  padding: 1.25rem 0;
  border-bottom: 1px solid #eee;
  line-height: 1.55;

  /* narrow left gutter holds the featured star; entry body sits right */
  display: grid;
  grid-template-columns: 1.75rem 1fr;
  column-gap: 0.75rem;
  align-items: start;
}

.publication-item:last-of-type { border-bottom: 0; }

.rep-label { grid-column: 1; grid-row: 1; }

.pub-title         { grid-column: 2; grid-row: 1; }
.pub-meta          { grid-column: 2; grid-row: 2; }
.publication-icons { grid-column: 2; grid-row: 3; }

/* stack on narrow screens rather than squeeze the gutter */
@media (max-width: 600px) {
  .publication-item { display: block; }
}

  .publication-icons {
    margin-top: 0.6rem;
    gap: 6px;
    flex-wrap: wrap;
  }

  .publication-icons img {
    height: 40px;
    transition: transform 0.2s;
  }

  .publication-icons img:hover {
    transform: scale(1.1);
  }

 .award-badge {
  display: inline-block;
  background-color: var(--accent-mint-light);
  border: 2px solid var(--accent-mint);
  padding: 0.35rem 0.75rem;
  border-radius: 15px;
  font-size: var(--fs-sm);
  font-weight: 600;
  color: #333;
  margin-top: 0.5rem;
}

  .talk-item, .poster-item {
  margin: 1.5rem 0;
  padding: 1.25rem 1.5rem;
  background-color: white;
  border-left: 3px solid #e0e0e0;
  border-radius: 6px;
  }

  .talk-item:hover, .poster-item:hover {
    border-left-color: #4169E1;
    transform: translateY(-2px);
    box-shadow: 0 2px 6px rgba(0,0,0,0.08);
  }

  .divider {
    margin: 3rem 0;
    border: 0;
    border-top: 1px solid #ddd;
  }

.publication-icons {
  display: flex;
  gap: 4px;
  align-items: center;
}

.pub-btn {
  display: inline-block;
  padding: 0.35rem 0.75rem;
  background-color: var(--accent-mint-light);
  border: 2px solid var(--accent-mint);
  color: #333 !important;
  text-decoration: none;
  border-radius: 6px;
  font-weight: 600;
  font-size: var(--fs-sm);
  line-height: 1.2;
  box-shadow: 0 1px 2px rgba(0,0,0,0.05);
  transition: background-color 0.2s ease, color 0.2s ease, transform 0.1s ease;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}

.pub-btn:hover {
  background-color: var(--accent-mint-dark);
  color: white;
  border-color: var(--accent-mint-dark);
  transform: translateY(-1px);
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.pub-title {
  margin-top: 0.5rem;
  font-weight: 700;
  color: #222;
}

.pub-meta {
  color: #555;
  font-size: var(--fs-base);
}

/* DOI written out as part of the citation text */
.pub-doi {
  color: #4169E1;
  text-decoration: none;
  word-break: break-word;
}

.pub-doi:hover { text-decoration: underline; }

.page-content {
  max-width: 900px;
  margin: auto;
}

.publication-item {
  line-height: 1.55;
}

/* featured marker: a star at twice the size of the title it sits beside */
.rep-label {
  font-size: calc(var(--fs-base) * 2);
  line-height: 1;
  font-weight: 700;
  color: #4169E1;
  text-align: center;
}

/* ---- tags inside citations: icon only, no label ---- */
.method-tag,
.topic-tag {
  display: inline-flex;
  align-items: center;
  font-size: var(--fs-sm);
  font-weight: 400;
  color: var(--accent-mint-dark);
  background: none;
  border: 0;
  padding: 0;
  margin: 0;
}

.method-tags {
  margin-left: auto;
  display: inline-flex;
  align-items: center;
  gap: 0.55rem;
}

.method-tags svg {
  width: 1.6em;
  height: 1.6em;
  fill: none;
  stroke: currentColor;
  stroke-width: 1.3;
  stroke-linecap: round;
  stroke-linejoin: round;
}

/* ---- filter legend: icon above label, comma separated, no box ---- */
.method-legend {
  display: flex;
  align-items: flex-start;
  flex-wrap: wrap;
  gap: 0.9rem;
  row-gap: 1.1rem;
  margin-bottom: 1.5rem;
  font-size: var(--fs-sm);
  color: #999;
}

.method-legend span.label {
  font-weight: 500;
  margin-right: 0.2rem;
  color: #111;
  align-self: center;
}

.method-legend .method-tag,
.method-legend .topic-tag {
  cursor: pointer;
  display: inline-flex;
  flex-direction: column;
  align-items: center;
  gap: 0.3rem;
  color: #666;
  transition: color 0.15s;
}

.method-legend .method-tag svg,
.method-legend .topic-tag svg {
  width: 2em;
  height: 2em;
  flex-shrink: 0;
  color: var(--accent-mint-dark);  /* icons stay green; the label shows state */
  fill: none;
  stroke: currentColor;
  stroke-width: 1.3;
  stroke-linecap: round;
  stroke-linejoin: round;
}

/* comma after every label except the last one in its group */
.method-legend .method-tag:not(.group-end) > span::after,
.method-legend .topic-tag:not(.group-end) > span::after {
  content: ",";
}

.method-legend .method-tag:hover,
.method-legend .topic-tag:hover,
.method-legend .method-tag.active,
.method-legend .topic-tag.active {
  color: var(--accent-mint-dark);
}

/* underline rather than embolden, so selecting doesn't reflow the row */
.method-legend .method-tag.active > span,
.method-legend .topic-tag.active > span {
  text-decoration: underline;
  text-underline-offset: 2px;
}

/* ---------- Filter panel ---------- */

.filter-panel {
  background: var(--accent-mint-light);
  border: 1px solid #CFE9DC;
  border-radius: 8px;
  padding: 1.25rem 1.5rem;
  margin-bottom: 2.5rem;
}

.filter-panel .method-legend { margin-bottom: 0; }

</style>

<div class="page-header">
  <h1>Research & Publications</h1>
</div>

<p class="page-intro">
  I've been lucky to work on a number of different intersecting topics and methods.
  Publications, preprints, and conference proceedings are listed below, and can be
  filtered accordingly.
  See my <a href="../Sava_Segal_CV_2.pdf" style="color: #4169E1; font-weight: 500;">CV</a>
  for a complete list of publications and presentations.
</p>

<div class="meta-row">
  <span><span class="mark">*</span>work that may be indicative of future directions</span>
  <span><span class="mark">✨</span>student I've mentored</span>
  <span>PDF copies are for personal use only; copyright remains with the respective publishers.</span>
</div>

<div class="filter-panel">

<div class="method-legend">
  <span class="label">filter further:</span>
  <span class="method-tag method-fmri" data-filter="method-fmri"><svg viewBox="0 0 24 24" aria-hidden="true" focusable="false"><path d="M12 5.6C10.6 3.9 7.6 4.4 6.8 6.5 5.1 6.8 4 8.5 4.4 10.2c-1 1.3-.7 3.2.7 4.1.2 1.8 1.9 3 3.6 2.6.9 1.3 2.7 1.6 3.3.7"/><path d="M12 5.6c1.4-1.7 4.4-1.2 5.2.9 1.7.3 2.8 2 2.4 3.7 1 1.3.7 3.2-.7 4.1-.2 1.8-1.9 3-3.6 2.6-.9 1.3-2.7 1.6-3.3.7"/><path d="M12 5.6v13.4"/><rect x="13.4" y="8.6" width="3.4" height="3.4" rx=".4"/></svg><span>fMRI</span></span>
  <span class="method-tag method-ieeg" data-filter="method-ieeg"><svg viewBox="0 0 24 24" aria-hidden="true" focusable="false"><circle cx="12" cy="12.5" r="7"/><circle cx="9.2" cy="10" r="1"/><circle cx="14.6" cy="11.4" r="1"/><circle cx="11.2" cy="15.6" r="1"/><path d="M9.2 10 5.6 6.4M14.6 11.4 19.2 9.4M11.2 15.6 9.4 20.2"/></svg><span>iEEG</span></span>
  <span class="method-tag method-eeg" data-filter="method-eeg"><svg viewBox="0 0 24 24" aria-hidden="true" focusable="false"><circle cx="12" cy="12" r="8"/><path d="M6.4 12h2.1l1.6-3.4 2.1 6.8 1.6-3.4h2.2"/></svg><span>EEG</span></span>
  <span class="method-tag method-behav" data-filter="method-behav"><svg viewBox="0 0 24 24" aria-hidden="true" focusable="false"><rect x="3.2" y="8.4" width="17.6" height="8.4" rx="2"/><circle cx="8" cy="12.6" r="1.5"/><circle cx="12" cy="12.6" r="1.5"/><circle cx="16" cy="12.6" r="1.5"/><path d="M12 8.4V5.6"/></svg><span>behavior</span></span>
  <span class="method-tag method-clin group-end" data-filter="method-clin"><svg viewBox="0 0 24 24" aria-hidden="true" focusable="false"><path d="M6 3.2v4.9a4 4 0 0 0 8 0V3.2"/><path d="M4.4 3.2h3.1M12.5 3.2h3.1"/><path d="M10 12.1v3.1a3.9 3.9 0 0 0 7.8 0v-1.4"/><circle cx="17.8" cy="10.4" r="2.1"/></svg><span>clinical</span></span>
  <span style="margin: 0 0.3rem; color: #ddd; align-self: center;">|</span>
  <span class="topic-tag topic-symbolic" data-filter="topic-symbolic"><svg viewBox="0 0 24 24" aria-hidden="true" focusable="false"><circle cx="4.6" cy="12" r="2.6"/><rect x="9.6" y="9.4" width="5.2" height="5.2" rx="0.4"/><path d="M19.4 9.2 22 14.6h-5.2z"/><path d="M7.2 12h2.4M14.8 12h1.6"/></svg><span>symbolic systems</span></span>
  <span class="topic-tag topic-subjective" data-filter="topic-subjective"><svg viewBox="0 0 24 24" aria-hidden="true" focusable="false"><path d="M12 5.6c5.2 0 9.2 6.4 9.2 6.4s-4 6.4-9.2 6.4S2.8 12 2.8 12 6.8 5.6 12 5.6z"/><path d="M12 9.4l.9 1.7 1.7.9-1.7.9-.9 1.7-.9-1.7L9.4 12l1.7-.9z"/></svg><span>subjectivity</span></span>
  <span class="topic-tag topic-memory" data-filter="topic-memory"><svg viewBox="0 0 24 24" aria-hidden="true" focusable="false"><path d="M12 5.6C10.6 3.9 7.6 4.4 6.8 6.5 5.1 6.8 4 8.5 4.4 10.2c-1 1.3-.7 3.2.7 4.1.2 1.8 1.9 3 3.6 2.6.9 1.3 2.7 1.6 3.3.7"/><path d="M12 5.6c1.4-1.7 4.4-1.2 5.2.9 1.7.3 2.8 2 2.4 3.7 1 1.3.7 3.2-.7 4.1-.2 1.8-1.9 3-3.6 2.6-.9 1.3-2.7 1.6-3.3.7"/><path d="M13.8 10.2a2.1 2.1 0 1 0-1.9 2.9 3.1 3.1 0 0 0 3.1-3.4"/></svg><span>memory</span></span>
  <span class="topic-tag topic-eventseg" data-filter="topic-eventseg"><svg viewBox="0 0 24 24" aria-hidden="true" focusable="false"><path d="M2.4 12h19.2"/><circle cx="8" cy="12" r="1.2" fill="currentColor" stroke="none"/><circle cx="12" cy="12" r="1.2" fill="currentColor" stroke="none"/><circle cx="16" cy="12" r="1.2" fill="currentColor" stroke="none"/><path d="M5.8 6.4v11.2M10 6.4v11.2M14.2 6.4v11.2" stroke-dasharray="2 2.2"/></svg><span>event segmentation</span></span>
  <span class="topic-tag topic-vision" data-filter="topic-vision"><svg viewBox="0 0 24 24" aria-hidden="true" focusable="false"><path d="M12 8.2c4.4 0 7.3 3.8 7.3 3.8s-2.9 3.8-7.3 3.8S4.7 12 4.7 12s2.9-3.8 7.3-3.8z"/><circle cx="12" cy="12" r="1.9"/><path d="M12 3.4v2.1M5.9 5.1l1.2 1.7M18.1 5.1l-1.2 1.7M12 18.5v2.1M5.9 18.9l1.2-1.7M18.1 18.9l-1.2-1.7"/></svg><span>vision</span></span>
  <span class="topic-tag topic-networks group-end" data-filter="topic-networks"><svg viewBox="0 0 24 24" aria-hidden="true" focusable="false"><g transform="rotate(-90 12 12)"><path d="M12 6.4 7.2 9.4M12 6.4l4.8 3M7.2 9.4h9.6M7.2 9.4 12 12.6M16.8 9.4 12 12.6M12 12.6 7.6 17.4M12 12.6l4.4 4.8"/><circle cx="12" cy="5" r="1.7"/><circle cx="6" cy="9.6" r="1.7"/><circle cx="18" cy="9.6" r="1.7"/><circle cx="12" cy="13.2" r="1.8"/><circle cx="6.8" cy="18.4" r="1.7"/><circle cx="17.2" cy="18.4" r="1.7"/></g></svg><span>networks</span></span>
</div>

</div>

<h2 class="section-header">In Preparation <span style="text-transform: none; font-style: italic; color: #4169E1; font-weight: 500; font-size: var(--fs-base); letter-spacing: 0;">— check back soon for a preprint</span></h2>

<div class="publication-item" data-inprep="true">
  <div class="publication-icons"></div>
<span class="method-tag method-fmri" title="fMRI"><svg viewBox="0 0 24 24" role="img" aria-label="fMRI"><path d="M12 5.6C10.6 3.9 7.6 4.4 6.8 6.5 5.1 6.8 4 8.5 4.4 10.2c-1 1.3-.7 3.2.7 4.1.2 1.8 1.9 3 3.6 2.6.9 1.3 2.7 1.6 3.3.7"/><path d="M12 5.6c1.4-1.7 4.4-1.2 5.2.9 1.7.3 2.8 2 2.4 3.7 1 1.3.7 3.2-.7 4.1-.2 1.8-1.9 3-3.6 2.6-.9 1.3-2.7 1.6-3.3.7"/><path d="M12 5.6v13.4"/><rect x="13.4" y="8.6" width="3.4" height="3.4" rx=".4"/></svg></span><span class="method-tag method-behav" title="behavior"><svg viewBox="0 0 24 24" role="img" aria-label="behavior"><rect x="3.2" y="8.4" width="17.6" height="8.4" rx="2"/><circle cx="8" cy="12.6" r="1.5"/><circle cx="12" cy="12.6" r="1.5"/><circle cx="16" cy="12.6" r="1.5"/><path d="M12 8.4V5.6"/></svg></span><span class="topic-tag topic-subjective" title="subjectivity"><svg viewBox="0 0 24 24" role="img" aria-label="subjectivity"><path d="M12 5.6c5.2 0 9.2 6.4 9.2 6.4s-4 6.4-9.2 6.4S2.8 12 2.8 12 6.8 5.6 12 5.6z"/><path d="M12 9.4l.9 1.7 1.7.9-1.7.9-.9 1.7-.9-1.7L9.4 12l1.7-.9z"/></svg></span>
  <div class="pub-title">
    Shifts in neural representations of ambiguous information predict reinterpretation.
  </div>
  <div class="pub-meta">
    <strong>Sava-Segal, C.</strong>, Benson, T.✨, Finn, E.S.
  </div>
</div>

<div class="publication-item" data-inprep="true">
  <div class="publication-icons"></div>
<span class="method-tag method-fmri" title="fMRI"><svg viewBox="0 0 24 24" role="img" aria-label="fMRI"><path d="M12 5.6C10.6 3.9 7.6 4.4 6.8 6.5 5.1 6.8 4 8.5 4.4 10.2c-1 1.3-.7 3.2.7 4.1.2 1.8 1.9 3 3.6 2.6.9 1.3 2.7 1.6 3.3.7"/><path d="M12 5.6c1.4-1.7 4.4-1.2 5.2.9 1.7.3 2.8 2 2.4 3.7 1 1.3.7 3.2-.7 4.1-.2 1.8-1.9 3-3.6 2.6-.9 1.3-2.7 1.6-3.3.7"/><path d="M12 5.6v13.4"/><rect x="13.4" y="8.6" width="3.4" height="3.4" rx=".4"/></svg></span><span class="method-tag method-behav" title="behavior"><svg viewBox="0 0 24 24" role="img" aria-label="behavior"><rect x="3.2" y="8.4" width="17.6" height="8.4" rx="2"/><circle cx="8" cy="12.6" r="1.5"/><circle cx="12" cy="12.6" r="1.5"/><circle cx="16" cy="12.6" r="1.5"/><path d="M12 8.4V5.6"/></svg></span><span class="topic-tag topic-subjective" title="subjectivity"><svg viewBox="0 0 24 24" role="img" aria-label="subjectivity"><path d="M12 5.6c5.2 0 9.2 6.4 9.2 6.4s-4 6.4-9.2 6.4S2.8 12 2.8 12 6.8 5.6 12 5.6z"/><path d="M12 9.4l.9 1.7 1.7.9-1.7.9-.9 1.7-.9-1.7L9.4 12l1.7-.9z"/></svg></span><span class="topic-tag topic-memory" title="memory"><svg viewBox="0 0 24 24" role="img" aria-label="memory"><path d="M12 5.6C10.6 3.9 7.6 4.4 6.8 6.5 5.1 6.8 4 8.5 4.4 10.2c-1 1.3-.7 3.2.7 4.1.2 1.8 1.9 3 3.6 2.6.9 1.3 2.7 1.6 3.3.7"/><path d="M12 5.6c1.4-1.7 4.4-1.2 5.2.9 1.7.3 2.8 2 2.4 3.7 1 1.3.7 3.2-.7 4.1-.2 1.8-1.9 3-3.6 2.6-.9 1.3-2.7 1.6-3.3.7"/><path d="M13.8 10.2a2.1 2.1 0 1 0-1.9 2.9 3.1 3.1 0 0 0 3.1-3.4"/></svg></span>
  <div class="pub-title">
    Reinterpretation counters self-bias in memory through representational updating.
  </div>
  <div class="pub-meta">
    <strong>Sava-Segal, C.</strong>, Benson, T.✨, Finn, E.S.
  </div>
</div>

<div class="publication-item" data-inprep="true">
  <div class="publication-icons"></div>
<span class="method-tag method-fmri" title="fMRI"><svg viewBox="0 0 24 24" role="img" aria-label="fMRI"><path d="M12 5.6C10.6 3.9 7.6 4.4 6.8 6.5 5.1 6.8 4 8.5 4.4 10.2c-1 1.3-.7 3.2.7 4.1.2 1.8 1.9 3 3.6 2.6.9 1.3 2.7 1.6 3.3.7"/><path d="M12 5.6c1.4-1.7 4.4-1.2 5.2.9 1.7.3 2.8 2 2.4 3.7 1 1.3.7 3.2-.7 4.1-.2 1.8-1.9 3-3.6 2.6-.9 1.3-2.7 1.6-3.3.7"/><path d="M12 5.6v13.4"/><rect x="13.4" y="8.6" width="3.4" height="3.4" rx=".4"/></svg></span><span class="method-tag method-clin" title="clinical"><svg viewBox="0 0 24 24" role="img" aria-label="clinical"><path d="M6 3.2v4.9a4 4 0 0 0 8 0V3.2"/><path d="M4.4 3.2h3.1M12.5 3.2h3.1"/><path d="M10 12.1v3.1a3.9 3.9 0 0 0 7.8 0v-1.4"/><circle cx="17.8" cy="10.4" r="2.1"/></svg></span><span class="topic-tag topic-vision" title="vision"><svg viewBox="0 0 24 24" role="img" aria-label="vision"><path d="M12 8.2c4.4 0 7.3 3.8 7.3 3.8s-2.9 3.8-7.3 3.8S4.7 12 4.7 12s2.9-3.8 7.3-3.8z"/><circle cx="12" cy="12" r="1.9"/><path d="M12 3.4v2.1M5.9 5.1l1.2 1.7M18.1 5.1l-1.2 1.7M12 18.5v2.1M5.9 18.9l1.2-1.7M18.1 18.9l-1.2-1.7"/></svg></span>
  <div class="pub-title">
    Neural representational alignment in developmental prosopagnosia differs beyond visual regions during naturalistic visual processing.
  </div>
  <div class="pub-meta">
    Kidder, A., <strong>Sava-Segal, C.</strong>, Finn, E.S., Duchaine, B., Baker, C.I. <span style="font-style: italic; color: #888;">VSS, 2026.</span>
  </div>
</div>

<h2 class="section-header">Publications, Preprints &amp; Conference Proceedings</h2>

<div class="publication-item">
  <div class="publication-icons">
    <a class="pub-btn" href="papers/sava-segal-et-al-2026-narrative-twist-shifts-within-individual-neural-representations-of-dissociable-story-features (2).pdf" target="_blank">PDF</a>
    <a class="pub-btn" href="https://github.com/csavasegal/darkend_narrative_rep" target="_blank">Code</a>
    <a class="pub-btn" href="https://openneuro.org/datasets/ds007407/versions/1.0.0" target="_blank">OpenNeuro</a>
  </div>
  <div class="rep-label" title="May be indicative of future directions" aria-label="May be indicative of future directions">*</div><span class="method-tag method-fmri" title="fMRI"><svg viewBox="0 0 24 24" role="img" aria-label="fMRI"><path d="M12 5.6C10.6 3.9 7.6 4.4 6.8 6.5 5.1 6.8 4 8.5 4.4 10.2c-1 1.3-.7 3.2.7 4.1.2 1.8 1.9 3 3.6 2.6.9 1.3 2.7 1.6 3.3.7"/><path d="M12 5.6c1.4-1.7 4.4-1.2 5.2.9 1.7.3 2.8 2 2.4 3.7 1 1.3.7 3.2-.7 4.1-.2 1.8-1.9 3-3.6 2.6-.9 1.3-2.7 1.6-3.3.7"/><path d="M12 5.6v13.4"/><rect x="13.4" y="8.6" width="3.4" height="3.4" rx=".4"/></svg></span><span class="topic-tag topic-subjective" title="subjectivity"><svg viewBox="0 0 24 24" role="img" aria-label="subjectivity"><path d="M12 5.6c5.2 0 9.2 6.4 9.2 6.4s-4 6.4-9.2 6.4S2.8 12 2.8 12 6.8 5.6 12 5.6z"/><path d="M12 9.4l.9 1.7 1.7.9-1.7.9-.9 1.7-.9-1.7L9.4 12l1.7-.9z"/></svg></span>
  <div class="pub-title">
    Narrative 'twist' shifts within-individual neural representations of dissociable story features.
  </div>
  <div class="pub-meta">
    <strong>Sava-Segal, C.</strong>, Grall, C., Finn, E.S. (2026). <i>Proceedings of the National Academy of Sciences (PNAS).</i> <a class="pub-doi" href="https://doi.org/10.1073/pnas.2512071123" target="_blank">https://doi.org/10.1073/pnas.2512071123</a>
  </div>
</div>

<div class="publication-item">
  <div class="publication-icons">
    <a class="pub-btn" href="https://osf.io/preprints/psyarxiv/7rbhy_v1" target="_blank">Preprint</a>
    </div>
  <span class="method-tag method-fmri" title="fMRI"><svg viewBox="0 0 24 24" role="img" aria-label="fMRI"><path d="M12 5.6C10.6 3.9 7.6 4.4 6.8 6.5 5.1 6.8 4 8.5 4.4 10.2c-1 1.3-.7 3.2.7 4.1.2 1.8 1.9 3 3.6 2.6.9 1.3 2.7 1.6 3.3.7"/><path d="M12 5.6c1.4-1.7 4.4-1.2 5.2.9 1.7.3 2.8 2 2.4 3.7 1 1.3.7 3.2-.7 4.1-.2 1.8-1.9 3-3.6 2.6-.9 1.3-2.7 1.6-3.3.7"/><path d="M12 5.6v13.4"/><rect x="13.4" y="8.6" width="3.4" height="3.4" rx=".4"/></svg></span><span class="topic-tag topic-eventseg" title="event segmentation"><svg viewBox="0 0 24 24" role="img" aria-label="event segmentation"><path d="M2.4 12h19.2"/><circle cx="8" cy="12" r="1.2" fill="currentColor" stroke="none"/><circle cx="12" cy="12" r="1.2" fill="currentColor" stroke="none"/><circle cx="16" cy="12" r="1.2" fill="currentColor" stroke="none"/><path d="M5.8 6.4v11.2M10 6.4v11.2M14.2 6.4v11.2" stroke-dasharray="2 2.2"/></svg></span>
  <div class="pub-title">
    Idiosyncratic event segmentation as a neural marker of loneliness.
  </div>
  <div class="pub-meta">
    Lu, C., <strong>Sava-Segal, C.</strong>, Baek, E.C. (2025). <i>OSF.</i> <span style="font-style: italic; color: #888;">Revise and resubmit.</span> <a class="pub-doi" href="https://doi.org/10.31234/osf.io/7rbhy_v1" target="_blank">https://doi.org/10.31234/osf.io/7rbhy_v1</a>
  </div>
</div>


<div class="publication-item">
  <div class="publication-icons">
    </div>
  <span class="method-tag method-ieeg" title="iEEG"><svg viewBox="0 0 24 24" role="img" aria-label="iEEG"><circle cx="12" cy="12.5" r="7"/><circle cx="9.2" cy="10" r="1"/><circle cx="14.6" cy="11.4" r="1"/><circle cx="11.2" cy="15.6" r="1"/><path d="M9.2 10 5.6 6.4M14.6 11.4 19.2 9.4M11.2 15.6 9.4 20.2"/></svg></span><span class="topic-tag topic-vision" title="vision"><svg viewBox="0 0 24 24" role="img" aria-label="vision"><path d="M12 8.2c4.4 0 7.3 3.8 7.3 3.8s-2.9 3.8-7.3 3.8S4.7 12 4.7 12s2.9-3.8 7.3-3.8z"/><circle cx="12" cy="12" r="1.9"/><path d="M12 3.4v2.1M5.9 5.1l1.2 1.7M18.1 5.1l-1.2 1.7M12 18.5v2.1M5.9 18.9l1.2-1.7M18.1 18.9l-1.2-1.7"/></svg></span>
  <div class="pub-title">
    Spatiotemporal hierarchies of face representation in the human ventral temporal cortex.
  </div>
  <div class="pub-meta">
    Salehi, S., Schrouff, J., Dehaqani, M.R.A., <strong>Sava-Segal, C.</strong>, Raccah, O., Baek, S. (2024).
    <i>Scientific Reports.</i> <a class="pub-doi" href="https://doi.org/10.1038/s41598-024-77895-5" target="_blank">https://doi.org/10.1038/s41598-024-77895-5</a>
  </div>
</div>

<div class="publication-item" data-type="proceedings">
  <div class="publication-icons">
    <a class="pub-btn" href="papers/520_Paper_authored_CSS_CCN_2024_Final.pdf" target="_blank">PDF</a>
  </div>
  <div class="rep-label" title="May be indicative of future directions" aria-label="May be indicative of future directions">*</div><span class="method-tag method-behav" title="behavior"><svg viewBox="0 0 24 24" role="img" aria-label="behavior"><rect x="3.2" y="8.4" width="17.6" height="8.4" rx="2"/><circle cx="8" cy="12.6" r="1.5"/><circle cx="12" cy="12.6" r="1.5"/><circle cx="16" cy="12.6" r="1.5"/><path d="M12 8.4V5.6"/></svg></span><span class="topic-tag topic-memory" title="memory"><svg viewBox="0 0 24 24" role="img" aria-label="memory"><path d="M12 5.6C10.6 3.9 7.6 4.4 6.8 6.5 5.1 6.8 4 8.5 4.4 10.2c-1 1.3-.7 3.2.7 4.1.2 1.8 1.9 3 3.6 2.6.9 1.3 2.7 1.6 3.3.7"/><path d="M12 5.6c1.4-1.7 4.4-1.2 5.2.9 1.7.3 2.8 2 2.4 3.7 1 1.3.7 3.2-.7 4.1-.2 1.8-1.9 3-3.6 2.6-.9 1.3-2.7 1.6-3.3.7"/><path d="M13.8 10.2a2.1 2.1 0 1 0-1.9 2.9 3.1 3.1 0 0 0 3.1-3.4"/></svg></span>
  <div class="pub-title">
    Self- versus other-generated interpretations of ambiguous social stimuli are asymmetrically remembered.
  </div>
  <div class="pub-meta">
    <strong>Sava-Segal, C.</strong>, Finn, E.S. (2024).
    <i>Proceedings of the 8th Annual Conference on Cognitive Computational Neuroscience.</i>
  </div>
</div>

<div class="publication-item" data-type="proceedings">
  <div class="publication-icons">
    <a class="pub-btn" href="papers/521_Paper_authored_TB_CCN_2024.pdf" target="_blank">PDF</a>
  </div>
  <div class="rep-label" title="May be indicative of future directions" aria-label="May be indicative of future directions">*</div><span class="method-tag method-behav" title="behavior"><svg viewBox="0 0 24 24" role="img" aria-label="behavior"><rect x="3.2" y="8.4" width="17.6" height="8.4" rx="2"/><circle cx="8" cy="12.6" r="1.5"/><circle cx="12" cy="12.6" r="1.5"/><circle cx="16" cy="12.6" r="1.5"/><path d="M12 8.4V5.6"/></svg></span><span class="topic-tag topic-subjective" title="subjectivity"><svg viewBox="0 0 24 24" role="img" aria-label="subjectivity"><path d="M12 5.6c5.2 0 9.2 6.4 9.2 6.4s-4 6.4-9.2 6.4S2.8 12 2.8 12 6.8 5.6 12 5.6z"/><path d="M12 9.4l.9 1.7 1.7.9-1.7.9-.9 1.7-.9-1.7L9.4 12l1.7-.9z"/></svg></span>
  <div class="pub-title">
    Personality Traits Predict the Valence but not Semantic Content of Narrative Interpretations.
  </div>
  <div class="pub-meta">
    Benson, T.✨, <strong>Sava-Segal, C.</strong>, Finn, E.S. (2024).
    <i>Proceedings of the 8th Annual Conference on Cognitive Computational Neuroscience.</i>
  </div>
</div>

<div class="publication-item">
  <div class="publication-icons">
    </div>
  <span class="method-tag method-ieeg" title="iEEG"><svg viewBox="0 0 24 24" role="img" aria-label="iEEG"><circle cx="12" cy="12.5" r="7"/><circle cx="9.2" cy="10" r="1"/><circle cx="14.6" cy="11.4" r="1"/><circle cx="11.2" cy="15.6" r="1"/><path d="M9.2 10 5.6 6.4M14.6 11.4 19.2 9.4M11.2 15.6 9.4 20.2"/></svg></span><span class="topic-tag topic-symbolic" title="symbolic systems"><svg viewBox="0 0 24 24" role="img" aria-label="symbolic systems"><circle cx="4.6" cy="12" r="2.6"/><rect x="9.6" y="9.4" width="5.2" height="5.2" rx="0.4"/><path d="M19.4 9.2 22 14.6h-5.2z"/><path d="M7.2 12h2.4M14.8 12h1.6"/></svg></span>
  <div class="pub-title">
    Spatiotemporal dynamics of successive activations across the human brain during a simple cognitive task.
  </div>
  <div class="pub-meta">
    Pinheiro-Chagas, P., <strong>Sava-Segal, C.</strong>, Serdar Akkol, Daitch, A., Parvizi, J. (2024).
    <i>Journal of Neuroscience.</i> <a class="pub-doi" href="https://doi.org/10.1523/JNEUROSCI.2118-22.2024" target="_blank">https://doi.org/10.1523/JNEUROSCI.2118-22.2024</a>
  </div>
</div>


<div class="publication-item" data-type="proceedings">
  <div class="publication-icons">
    <a class="pub-btn" href="https://cds.ismrm.org/protected/23MProceedings/PDFfiles/1024_1DHBtNPae.html" target="_blank">Proceedings</a>
    </div>
  <span class="method-tag method-fmri" title="fMRI"><svg viewBox="0 0 24 24" role="img" aria-label="fMRI"><path d="M12 5.6C10.6 3.9 7.6 4.4 6.8 6.5 5.1 6.8 4 8.5 4.4 10.2c-1 1.3-.7 3.2.7 4.1.2 1.8 1.9 3 3.6 2.6.9 1.3 2.7 1.6 3.3.7"/><path d="M12 5.6c1.4-1.7 4.4-1.2 5.2.9 1.7.3 2.8 2 2.4 3.7 1 1.3.7 3.2-.7 4.1-.2 1.8-1.9 3-3.6 2.6-.9 1.3-2.7 1.6-3.3.7"/><path d="M12 5.6v13.4"/><rect x="13.4" y="8.6" width="3.4" height="3.4" rx=".4"/></svg></span>
  <div class="pub-title">
    A multi-subject deconvolution algorithm for the analysis of naturalistic fMRI data.
  </div>
  <div class="pub-meta">
    Uruñuela, E., <strong>Sava-Segal, C.</strong>, Leung, M.✨, Finn, E.S., Caballero-Gaudes, C. (2023).
    <i>Proceedings of the International Society for Magnetic Resonance in Medicine (ISMRM).</i> <a class="pub-doi" href="https://doi.org/10.58530/2023/1024" target="_blank">https://doi.org/10.58530/2023/1024</a>
  </div>
</div>

<div class="publication-item">
  <div class="publication-icons">
    <a class="pub-btn" href="papers/css_2023_individual_event-seg.pdf" target="_blank">PDF</a>
    <a class="pub-btn" href="https://github.com/csavasegal/individual_event_seg/" target="_blank">Code</a>
    <a class="pub-btn" href="https://openneuro.org/datasets/ds004516/versions/2.0.3" target="_blank">OpenNeuro</a>
  </div>
  <div class="rep-label" title="May be indicative of future directions" aria-label="May be indicative of future directions">*</div><span class="method-tag method-fmri" title="fMRI"><svg viewBox="0 0 24 24" role="img" aria-label="fMRI"><path d="M12 5.6C10.6 3.9 7.6 4.4 6.8 6.5 5.1 6.8 4 8.5 4.4 10.2c-1 1.3-.7 3.2.7 4.1.2 1.8 1.9 3 3.6 2.6.9 1.3 2.7 1.6 3.3.7"/><path d="M12 5.6c1.4-1.7 4.4-1.2 5.2.9 1.7.3 2.8 2 2.4 3.7 1 1.3.7 3.2-.7 4.1-.2 1.8-1.9 3-3.6 2.6-.9 1.3-2.7 1.6-3.3.7"/><path d="M12 5.6v13.4"/><rect x="13.4" y="8.6" width="3.4" height="3.4" rx=".4"/></svg></span><span class="method-tag method-behav" title="behavior"><svg viewBox="0 0 24 24" role="img" aria-label="behavior"><rect x="3.2" y="8.4" width="17.6" height="8.4" rx="2"/><circle cx="8" cy="12.6" r="1.5"/><circle cx="12" cy="12.6" r="1.5"/><circle cx="16" cy="12.6" r="1.5"/><path d="M12 8.4V5.6"/></svg></span><span class="topic-tag topic-subjective" title="subjectivity"><svg viewBox="0 0 24 24" role="img" aria-label="subjectivity"><path d="M12 5.6c5.2 0 9.2 6.4 9.2 6.4s-4 6.4-9.2 6.4S2.8 12 2.8 12 6.8 5.6 12 5.6z"/><path d="M12 9.4l.9 1.7 1.7.9-1.7.9-.9 1.7-.9-1.7L9.4 12l1.7-.9z"/></svg></span><span class="topic-tag topic-eventseg" title="event segmentation"><svg viewBox="0 0 24 24" role="img" aria-label="event segmentation"><path d="M2.4 12h19.2"/><circle cx="8" cy="12" r="1.2" fill="currentColor" stroke="none"/><circle cx="12" cy="12" r="1.2" fill="currentColor" stroke="none"/><circle cx="16" cy="12" r="1.2" fill="currentColor" stroke="none"/><path d="M5.8 6.4v11.2M10 6.4v11.2M14.2 6.4v11.2" stroke-dasharray="2 2.2"/></svg></span><span class="topic-tag topic-memory" title="memory"><svg viewBox="0 0 24 24" role="img" aria-label="memory"><path d="M12 5.6C10.6 3.9 7.6 4.4 6.8 6.5 5.1 6.8 4 8.5 4.4 10.2c-1 1.3-.7 3.2.7 4.1.2 1.8 1.9 3 3.6 2.6.9 1.3 2.7 1.6 3.3.7"/><path d="M12 5.6c1.4-1.7 4.4-1.2 5.2.9 1.7.3 2.8 2 2.4 3.7 1 1.3.7 3.2-.7 4.1-.2 1.8-1.9 3-3.6 2.6-.9 1.3-2.7 1.6-3.3.7"/><path d="M13.8 10.2a2.1 2.1 0 1 0-1.9 2.9 3.1 3.1 0 0 0 3.1-3.4"/></svg></span>
  <div class="pub-title">
    Individual differences in neural event segmentation of continuous experiences.
  </div>
  <div class="pub-meta">
    <strong>Sava-Segal, C.</strong>, Richards, C., Leung, M.✨, &amp; Finn, E.S. (2023).
    <i>Cerebral Cortex.</i> <a class="pub-doi" href="https://doi.org/10.1093/cercor/bhad106" target="_blank">https://doi.org/10.1093/cercor/bhad106</a>
  </div>
</div>


<div class="publication-item">
  <div class="publication-icons">
    </div>
  <span class="method-tag method-ieeg" title="iEEG"><svg viewBox="0 0 24 24" role="img" aria-label="iEEG"><circle cx="12" cy="12.5" r="7"/><circle cx="9.2" cy="10" r="1"/><circle cx="14.6" cy="11.4" r="1"/><circle cx="11.2" cy="15.6" r="1"/><path d="M9.2 10 5.6 6.4M14.6 11.4 19.2 9.4M11.2 15.6 9.4 20.2"/></svg></span><span class="method-tag method-clin" title="clinical"><svg viewBox="0 0 24 24" role="img" aria-label="clinical"><path d="M6 3.2v4.9a4 4 0 0 0 8 0V3.2"/><path d="M4.4 3.2h3.1M12.5 3.2h3.1"/><path d="M10 12.1v3.1a3.9 3.9 0 0 0 7.8 0v-1.4"/><circle cx="17.8" cy="10.4" r="2.1"/></svg></span><span class="topic-tag topic-networks" title="networks"><svg viewBox="0 0 24 24" role="img" aria-label="networks"><g transform="rotate(-90 12 12)"><path d="M12 6.4 7.2 9.4M12 6.4l4.8 3M7.2 9.4h9.6M7.2 9.4 12 12.6M16.8 9.4 12 12.6M12 12.6 7.6 17.4M12 12.6l4.4 4.8"/><circle cx="12" cy="5" r="1.7"/><circle cx="6" cy="9.6" r="1.7"/><circle cx="18" cy="9.6" r="1.7"/><circle cx="12" cy="13.2" r="1.8"/><circle cx="6.8" cy="18.4" r="1.7"/><circle cx="17.2" cy="18.4" r="1.7"/></g></svg></span>
  <div class="pub-title">
    Intracranial electroencephalography reveals selective task-evoked responses and resting state connectivity of periventricular heterotopias.
  </div>
  <div class="pub-meta">
    Akkol, S., Kucyi, A., Hu, W.H., Zhao, B., Zhang, C., <strong>Sava-Segal, C.</strong>, Liu, S., Razavi, B., Zhang, J., Zhang, K., &amp; Parvizi, J. (2021).
    <i>Journal of Neuroscience.</i> <a class="pub-doi" href="https://doi.org/10.1523/JNEUROSCI.2785-20.2021" target="_blank">https://doi.org/10.1523/JNEUROSCI.2785-20.2021</a>
  </div>
</div>

<div class="publication-item">
  <div class="publication-icons">
    </div>
  <span class="method-tag method-ieeg" title="iEEG"><svg viewBox="0 0 24 24" role="img" aria-label="iEEG"><circle cx="12" cy="12.5" r="7"/><circle cx="9.2" cy="10" r="1"/><circle cx="14.6" cy="11.4" r="1"/><circle cx="11.2" cy="15.6" r="1"/><path d="M9.2 10 5.6 6.4M14.6 11.4 19.2 9.4M11.2 15.6 9.4 20.2"/></svg></span><span class="topic-tag topic-symbolic" title="symbolic systems"><svg viewBox="0 0 24 24" role="img" aria-label="symbolic systems"><circle cx="4.6" cy="12" r="2.6"/><rect x="9.6" y="9.4" width="5.2" height="5.2" rx="0.4"/><path d="M19.4 9.2 22 14.6h-5.2z"/><path d="M7.2 12h2.4M14.8 12h1.6"/></svg></span>
  <div class="pub-title">
    Overlapping neuronal population responses in the human parietal cortex during visuospatial attention and arithmetic processing.
  </div>
  <div class="pub-meta">
    Liu, N., Pinheiro-Chagas, P., <strong>Sava-Segal, C.</strong>, Kastner, S., Chen, Q., &amp; Parvizi, J. (2021).
    <i>Journal of Cognitive Neuroscience</i>. <a class="pub-doi" href="https://doi.org/10.1162/jocn_a_01775" target="_blank">https://doi.org/10.1162/jocn_a_01775</a>
  </div>
</div>

<div class="publication-item">
  <div class="publication-icons">
    </div>
  <span class="method-tag method-eeg" title="EEG"><svg viewBox="0 0 24 24" role="img" aria-label="EEG"><circle cx="12" cy="12" r="8"/><path d="M6.4 12h2.1l1.6-3.4 2.1 6.8 1.6-3.4h2.2"/></svg></span>
  <div class="pub-title">
    Expertise modulates neural stimulus-tracking.
  </div>
  <div class="pub-meta">
    Brookshire, G., Mangelsdorf, H.H., <strong>Sava-Segal, C.</strong>, Reis, K., Nusbaum, H.,
    Goldin-Meadow, S., &amp; Casasanto, D. (2021).
    <i>ENeuro</i>. <a class="pub-doi" href="https://doi.org/10.1523/ENEURO.0065-21.2021" target="_blank">https://doi.org/10.1523/ENEURO.0065-21.2021</a>
  </div>
</div>

<div class="publication-item">
  <div class="publication-icons">
    </div>
  <span class="method-tag method-ieeg" title="iEEG"><svg viewBox="0 0 24 24" role="img" aria-label="iEEG"><circle cx="12" cy="12.5" r="7"/><circle cx="9.2" cy="10" r="1"/><circle cx="14.6" cy="11.4" r="1"/><circle cx="11.2" cy="15.6" r="1"/><path d="M9.2 10 5.6 6.4M14.6 11.4 19.2 9.4M11.2 15.6 9.4 20.2"/></svg></span><span class="method-tag method-clin" title="clinical"><svg viewBox="0 0 24 24" role="img" aria-label="clinical"><path d="M6 3.2v4.9a4 4 0 0 0 8 0V3.2"/><path d="M4.4 3.2h3.1M12.5 3.2h3.1"/><path d="M10 12.1v3.1a3.9 3.9 0 0 0 7.8 0v-1.4"/><circle cx="17.8" cy="10.4" r="2.1"/></svg></span>
  <div class="pub-title">
    Altered sense of self during seizures in the posteromedial cortex.
  </div>
  <div class="pub-meta">
    Parvizi, J., Braga, R.M., Kucyi, A., Veit, M.J., Pinheiro-Chagas, P., Perry, C.,
    <strong>Sava-Segal, C.</strong>, Zeineh, M., van Staalduinen, E.K., Henderson, J.M., &amp; Markert, M. (2021).
    <i>Proceedings of the National Academy of Sciences (PNAS).</i> <a class="pub-doi" href="https://doi.org/10.1073/pnas.2100522118" target="_blank">https://doi.org/10.1073/pnas.2100522118</a>
  </div>
</div>

<div class="publication-item">
  <div class="publication-icons">
    </div>
  <span class="method-tag method-ieeg" title="iEEG"><svg viewBox="0 0 24 24" role="img" aria-label="iEEG"><circle cx="12" cy="12.5" r="7"/><circle cx="9.2" cy="10" r="1"/><circle cx="14.6" cy="11.4" r="1"/><circle cx="11.2" cy="15.6" r="1"/><path d="M9.2 10 5.6 6.4M14.6 11.4 19.2 9.4M11.2 15.6 9.4 20.2"/></svg></span><span class="topic-tag topic-networks" title="networks"><svg viewBox="0 0 24 24" role="img" aria-label="networks"><g transform="rotate(-90 12 12)"><path d="M12 6.4 7.2 9.4M12 6.4l4.8 3M7.2 9.4h9.6M7.2 9.4 12 12.6M16.8 9.4 12 12.6M12 12.6 7.6 17.4M12 12.6l4.4 4.8"/><circle cx="12" cy="5" r="1.7"/><circle cx="6" cy="9.6" r="1.7"/><circle cx="18" cy="9.6" r="1.7"/><circle cx="12" cy="13.2" r="1.8"/><circle cx="6.8" cy="18.4" r="1.7"/><circle cx="17.2" cy="18.4" r="1.7"/></g></svg></span>
  <div class="pub-title">
    Temporal order of signal propagation within and across intrinsic brain networks.
  </div>
  <div class="pub-meta">
    Veit, M.J., Kucyi, A., Hu, W., Zhang, C., Zhao, B., Guo, Z., Yang, B., <strong>Sava-Segal, C.</strong>,
    Perry, C., Zhang, J., Zhang, K., &amp; Parvizi, J. (2021).
    <i>Proceedings of the National Academy of Sciences (PNAS).</i> <a class="pub-doi" href="https://doi.org/10.1073/pnas.2105031118" target="_blank">https://doi.org/10.1073/pnas.2105031118</a>
  </div>
</div>


<div class="publication-item">
  <div class="publication-icons">
    </div>
  <span class="method-tag method-ieeg" title="iEEG"><svg viewBox="0 0 24 24" role="img" aria-label="iEEG"><circle cx="12" cy="12.5" r="7"/><circle cx="9.2" cy="10" r="1"/><circle cx="14.6" cy="11.4" r="1"/><circle cx="11.2" cy="15.6" r="1"/><path d="M9.2 10 5.6 6.4M14.6 11.4 19.2 9.4M11.2 15.6 9.4 20.2"/></svg></span><span class="method-tag method-behav" title="behavior"><svg viewBox="0 0 24 24" role="img" aria-label="behavior"><rect x="3.2" y="8.4" width="17.6" height="8.4" rx="2"/><circle cx="8" cy="12.6" r="1.5"/><circle cx="12" cy="12.6" r="1.5"/><circle cx="16" cy="12.6" r="1.5"/><path d="M12 8.4V5.6"/></svg></span><span class="method-tag method-clin" title="clinical"><svg viewBox="0 0 24 24" role="img" aria-label="clinical"><path d="M6 3.2v4.9a4 4 0 0 0 8 0V3.2"/><path d="M4.4 3.2h3.1M12.5 3.2h3.1"/><path d="M10 12.1v3.1a3.9 3.9 0 0 0 7.8 0v-1.4"/><circle cx="17.8" cy="10.4" r="2.1"/></svg></span>
  <div class="pub-title">
    Deep posteromedial cortical rhythm in dissociation.
  </div>
  <div class="pub-meta">
    Vesuna, S., Kauvar, I.V., Richman, E., Gore, F., Oskotsky, T.,
    <strong>Sava-Segal, C.</strong>, Luo, L., Malenka, R.C., Henderson, J.M.,
    Nuyujukian, P., Parvizi, J., &amp; Deisseroth, K. (2020).
    <i>Nature</i>. <a class="pub-doi" href="https://doi.org/10.1038/s41586-020-2731-9" target="_blank">https://doi.org/10.1038/s41586-020-2731-9</a>
  </div>
</div>

<div class="publication-item">
  <div class="publication-icons">
    </div>
  <span class="method-tag method-eeg" title="EEG"><svg viewBox="0 0 24 24" role="img" aria-label="EEG"><circle cx="12" cy="12" r="8"/><path d="M6.4 12h2.1l1.6-3.4 2.1 6.8 1.6-3.4h2.2"/></svg></span><span class="method-tag method-behav" title="behavior"><svg viewBox="0 0 24 24" role="img" aria-label="behavior"><rect x="3.2" y="8.4" width="17.6" height="8.4" rx="2"/><circle cx="8" cy="12.6" r="1.5"/><circle cx="12" cy="12.6" r="1.5"/><circle cx="16" cy="12.6" r="1.5"/><path d="M12 8.4V5.6"/></svg></span><span class="topic-tag topic-symbolic" title="symbolic systems"><svg viewBox="0 0 24 24" role="img" aria-label="symbolic systems"><circle cx="4.6" cy="12" r="2.6"/><rect x="9.6" y="9.4" width="5.2" height="5.2" rx="0.4"/><path d="M19.4 9.2 22 14.6h-5.2z"/><path d="M7.2 12h2.4M14.8 12h1.6"/></svg></span><span class="topic-tag topic-vision" title="vision"><svg viewBox="0 0 24 24" role="img" aria-label="vision"><path d="M12 8.2c4.4 0 7.3 3.8 7.3 3.8s-2.9 3.8-7.3 3.8S4.7 12 4.7 12s2.9-3.8 7.3-3.8z"/><circle cx="12" cy="12" r="1.9"/><path d="M12 3.4v2.1M5.9 5.1l1.2 1.7M18.1 5.1l-1.2 1.7M12 18.5v2.1M5.9 18.9l1.2-1.7M18.1 18.9l-1.2-1.7"/></svg></span>
  <div class="pub-title">
    Unconscious number discrimination in the human visual system.
  </div>
  <div class="pub-meta">
    Lucero, C., Brookshire, G., <strong>Sava-Segal, C.</strong>, Bottini, R.,
    Goldin-Meadow, S., Vogel, E.K., &amp; Casasanto, D. (2020).
    <i>Cerebral Cortex</i>. <a class="pub-doi" href="https://doi.org/10.1093/cercor/bhaa155" target="_blank">https://doi.org/10.1093/cercor/bhaa155</a>
  </div>
</div>

<div class="publication-item">
  <div class="publication-icons">
    </div>
  <span class="method-tag method-behav" title="behavior"><svg viewBox="0 0 24 24" role="img" aria-label="behavior"><rect x="3.2" y="8.4" width="17.6" height="8.4" rx="2"/><circle cx="8" cy="12.6" r="1.5"/><circle cx="12" cy="12.6" r="1.5"/><circle cx="16" cy="12.6" r="1.5"/><path d="M12 8.4V5.6"/></svg></span><span class="topic-tag topic-vision" title="vision"><svg viewBox="0 0 24 24" role="img" aria-label="vision"><path d="M12 8.2c4.4 0 7.3 3.8 7.3 3.8s-2.9 3.8-7.3 3.8S4.7 12 4.7 12s2.9-3.8 7.3-3.8z"/><circle cx="12" cy="12" r="1.9"/><path d="M12 3.4v2.1M5.9 5.1l1.2 1.7M18.1 5.1l-1.2 1.7M12 18.5v2.1M5.9 18.9l1.2-1.7M18.1 18.9l-1.2-1.7"/></svg></span>
  <div class="pub-title">
    Effects of repetition suppression on sound-induced flash illusion with aging.
  </div>
  <div class="pub-meta">
    Sun, Y., Liu, X., Li, B., <strong>Sava-Segal, C.</strong>, Wang, A., &amp; Zhang, M. (2020).
    <i>Frontiers in Psychology</i>, 11, 216. <a class="pub-doi" href="https://doi.org/10.3389/fpsyg.2020.00216" target="_blank">https://doi.org/10.3389/fpsyg.2020.00216</a>
  </div>
</div>


<div class="publication-item">
  <div class="publication-icons">
    </div>
  <span class="method-tag method-behav" title="behavior"><svg viewBox="0 0 24 24" role="img" aria-label="behavior"><rect x="3.2" y="8.4" width="17.6" height="8.4" rx="2"/><circle cx="8" cy="12.6" r="1.5"/><circle cx="12" cy="12.6" r="1.5"/><circle cx="16" cy="12.6" r="1.5"/><path d="M12 8.4V5.6"/></svg></span><span class="topic-tag topic-vision" title="vision"><svg viewBox="0 0 24 24" role="img" aria-label="vision"><path d="M12 8.2c4.4 0 7.3 3.8 7.3 3.8s-2.9 3.8-7.3 3.8S4.7 12 4.7 12s2.9-3.8 7.3-3.8z"/><circle cx="12" cy="12" r="1.9"/><path d="M12 3.4v2.1M5.9 5.1l1.2 1.7M18.1 5.1l-1.2 1.7M12 18.5v2.1M5.9 18.9l1.2-1.7M18.1 18.9l-1.2-1.7"/></svg></span>
  <div class="pub-title">
    The effects of cognitive expectation on sound-induced flash illusion.
  </div>
  <div class="pub-meta">
    Wang, A., Sang, H., He, J., <strong>Sava-Segal, C.</strong>, Tang, X., &amp; Zhang, M. (2019).
    <i>Perception</i>, 48(12), 1214–1234. <a class="pub-doi" href="https://doi.org/10.1177/0301006619885796" target="_blank">https://doi.org/10.1177/0301006619885796</a>
  </div>
</div>

<p style="margin-top: 2rem; color: #666;">
  See my <a href="../Sava_Segal_CV_2.pdf" style="color: #4169E1; font-weight: 500;">CV</a> for a complete list of publications and presentations.
</p>


<!-- ===== CONFERENCE TALKS (commented out for now) =====

<hr class="divider">

<h2 class="section-header">Selected Conference Talks</h2>

<div class="talk-item">
  <strong>Self- versus other-generated interpretations of ambiguous social information are asymmetrically remembered.</strong> Symposium Talk – New Directions in Social Learning and Memory, Social Affective Neuroscience Society (SANS). April 2026.
</div>

<div class="talk-item">
  <strong>Within-individual neural patterns differ for memories of self- and other-generated interpretations of the same stimuli.</strong> Data Blitz, Cognitive Neuroscience Society, Boston, MA. March 2025.
</div>

<div class="talk-item">
  <strong>Real-world social inputs trigger shifts in neural activity patterns and reinterpretations of ambiguous stimuli.</strong> Nanosymposium on Neural Bases of Human Social Cognition and Connection, Society for Neuroscience (SfN). October 2024.
</div>

<p style="margin-top: 2rem; color: #666;">
  See my <a href="../Sava_Segal_CV_2.pdf" style="color: #4169E1; font-weight: 500;">CV</a> for a complete list of talks and presentations.
</p>

===== END CONFERENCE TALKS ===== -->


<!-- ===== POSTERS (commented out for now) =====

<hr class="divider">

<h2 class="section-header">Selected Poster Presentations</h2>

<div class="poster-item">
  <strong>Sava-Segal, C.</strong>, Benson, T., Finn, E.S. (2024). Multivariate neural pattern changes reflect within-subject shifts in subjective interpretations. Organization for Human Brain Mapping, Seoul, Korea.
</div>

<div class="poster-item">
  <strong>Sava-Segal, C.</strong>, Grall, C., Bartolino, K., Equita, J., Benson, T., Finn, E.S. (2023). Narrative 'twists' shift neural representations. Organization of Human Brain Mapping, Montreal, CA.
</div>

<div class="poster-item">
  <strong>Sava-Segal, C.</strong>, Finn, E.S. (2023). Shifting interpretations of multistable, "naturalistic" stimuli. Cognitive Neuroscience Society, San Francisco, CA.
</div>

<div class="poster-item">
  <strong>Sava-Segal, C.</strong>, Finn, E.S. (2022). Individual variability in neural event segmentation reflects stimulus content and interpretation. Organization of Human Brain Mapping, Glasgow, UK.
</div>

<div class="poster-item">
  <strong>Sava-Segal, C.</strong>*, Zhang, C.*, Zhao, B., Kucyi, A., Tao, A., Ko, H.J., Yih, J., Parvizi, J. (2022). Direct cortical recordings in the human brain during race categorization of faces. Cognitive Neuroscience Society, San Francisco, CA.
  <br>
  <span class="award-badge">🏆 Graduate Student Award Winner</span>
</div>

<div class="poster-item">
  <strong>Sava-Segal, C.</strong>, Finn, E.S. (2021). Exploring the role of event boundaries in idiosyncratic memory formation. Organization of Human Brain Mapping (virtual).
</div>

<p style="margin-top: 2rem; color: #666;">
  See my <a href="../Sava_Segal_CV_2.pdf" style="color: #4169E1; font-weight: 500;">CV</a> for a complete list of publications and presentations.
</p>

===== END POSTERS ===== -->


<script>
(function() {
  // Move method tags into the icons row, right-aligned
  document.querySelectorAll('.publication-item').forEach(function(item) {
    var icons = item.querySelector('.publication-icons');
    var tags = item.querySelectorAll('.method-tag, .topic-tag');
    if (tags.length > 0 && icons) {
      var wrapper = document.createElement('div');
      wrapper.className = 'method-tags';
      tags.forEach(function(tag) { wrapper.appendChild(tag); });
      icons.appendChild(wrapper);
    }
  });

  // Reorder: move icons row to after pub-meta (title > authors > buttons/tags)
  document.querySelectorAll('.publication-item').forEach(function(item) {
    var icons = item.querySelector('.publication-icons');
    var meta = item.querySelector('.pub-meta');
    if (icons && meta) {
      meta.after(icons);
    }
  });

  var activeFilters = new Set();

  document.querySelectorAll('.method-legend [data-filter]').forEach(function(pill) {
    pill.addEventListener('click', function() {
      var filter = this.dataset.filter;
      if (activeFilters.has(filter)) {
        activeFilters.delete(filter);
        this.classList.remove('active');
      } else {
        activeFilters.add(filter);
        this.classList.add('active');
      }
      applyFilter();
    });
  });

  function applyFilter() {
    document.querySelectorAll('.publication-item').forEach(function(item) {
      // combinations: an entry must carry EVERY selected tag, not just one
      var hide = false;
      activeFilters.forEach(function(f) {
        if (!item.querySelector('.' + f)) hide = true;
      });
      item.style.display = hide ? 'none' : '';
    });

    document.querySelectorAll('h2.section-header').forEach(function(header) {
      var sibling = header.nextElementSibling;
      var hasVisible = false;
      while (sibling && !sibling.classList.contains('section-header')) {
        if (sibling.classList.contains('publication-item') && sibling.style.display !== 'none') {
          hasVisible = true;
          break;
        }
        sibling = sibling.nextElementSibling;
      }
      header.style.display = hasVisible ? '' : 'none';
    });
  }
})();
</script>
