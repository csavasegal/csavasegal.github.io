---
layout: category
title: 
permalink: /publications/
---

<style>
  :root {
  --accent-mint: #4FC3A1;
  --accent-mint-dark: #1F7A5E;

  /* the only three font sizes on this page — matched to the About Me page */
  --fs-lg: 1.25rem;   /* page title, section headers, year headers (= About Me h2) */
  --fs-base: 1rem;    /* all prose: titles, authors, links, filter labels */
  --fs-sm: 0.85rem;   /* chrome: tags, buttons, labels, legend */
}

  .page-header {
    text-align: center;
    margin-bottom: 2.5rem;
    padding: 1.5rem 0;
    background: none;
    border-bottom: 1px solid #e6e6e6;
  }

  .page-header h1 {
    font-size: var(--fs-lg);
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
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 0.5rem;
    font-size: var(--fs-sm);
    color: #4169E1;
    font-weight: 500;
    margin-bottom: 1.25rem;
    padding-bottom: 0.75rem;
    border-bottom: 1px solid #f0f0f0;
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
    font-family: "Inter", "Helvetica", sans-serif;
    font-size: var(--fs-base);
    color: #333;
    line-height: 1.7;
  }

.year-header {
  margin-top: 3rem;
  margin-bottom: 0.5rem;
  font-size: var(--fs-lg);
  font-weight: 700;
  color: #4169E1;
  letter-spacing: 0;
  text-transform: none;
  border-bottom: 1px solid #ddd;
  padding-bottom: 0.4rem;
}
.year-header::before {
  content: none;
}

.publication-item {
  margin: 0;
  padding: 1.25rem 0;
  border-bottom: 1px solid #eee;
  line-height: 1.55;
}

.publication-item:last-of-type { border-bottom: 0; }

  .subsection-header {
  font-weight: 500;
  letter-spacing: 0.02em;
  margin-top: 1.5rem;
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
  background-color: #EDFAF4;
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
    height: 2px;
    background: linear-gradient(to right, transparent, #4169E1, transparent);
  }

.publication-icons {
  display: flex;
  gap: 4px;
  align-items: center;
}

.pub-btn {
  display: inline-block;
  padding: 0.35rem 0.75rem;
  background-color: #EDFAF4;
  border: 2px solid var(--accent-mint);
  color: #333 !important;
  text-decoration: none;
  border-radius: 6px;
  font-weight: 600;
  font-size: var(--fs-sm);
  line-height: 1.2;
  box-shadow: 0 1px 2px rgba(0,0,0,0.05);
  transition: background-color 0.2s ease, color 0.2s ease, transform 0.1s ease;
  font-family: "Inter", "Helvetica", sans-serif;
}

.pub-btn:hover {
  background-color: #1F7A5E;
  color: white;
  border-color: #1F7A5E;
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

.page-content {
  max-width: 900px;
  margin: auto;
}

.publication-item {
  line-height: 1.55;
}

.rep-label {
  display: inline-block;
  margin-top: 0.4rem;
  font-size: var(--fs-sm);
  font-weight: 600;
  letter-spacing: 0.04em;
  color: #4169E1;
  background: #eef2fc;
  border: 1px solid #c5d0ef;
  padding: 0.15rem 0.55rem;
  border-radius: 20px;
  text-transform: uppercase;
}

.method-tag {
  display: inline-block;
  margin-top: 0.4rem;
  margin-left: 0.3rem;
  font-size: var(--fs-sm);
  font-weight: 600;
  letter-spacing: 0.04em;
  padding: 0.1rem 0.45rem;
  border-radius: 5px;
}

.method-tags {
  margin-left: auto;
  display: flex;
  gap: 4px;
  align-items: center;
}

.method-tags .method-tag,
.method-tags .topic-tag {
  margin-top: 0;
  margin-left: 0;
}

.method-legend {
  display: flex;
  align-items: center;
  gap: 0.4rem;
  flex-wrap: wrap;
  margin-bottom: 1.5rem;
  font-size: var(--fs-sm);
  color: #999;
}

.method-legend span.label {
  font-weight: 500;
  margin-right: 0.2rem;
  color: #111;
}

.method-legend .method-tag,
.method-legend .topic-tag {
  cursor: pointer;
  margin-top: 0;
  margin-left: 0;
  opacity: 0.5;
  transition: opacity 0.15s, box-shadow 0.15s;
}

.method-legend .method-tag:hover,
.method-legend .method-tag.active,
.method-legend .topic-tag:hover,
.method-legend .topic-tag.active {
  opacity: 1;
  box-shadow: 0 0 0 2px currentColor;
}

.topic-tag {
  display: inline-block;
  margin-top: 0.4rem;
  margin-left: 0.3rem;
  font-size: var(--fs-sm);
  font-weight: 600;
  letter-spacing: 0.04em;
  padding: 0.1rem 0.45rem;
  border-radius: 5px;
  background: white;
  border: 1.5px solid;
}

.topic-tags {
  margin-left: auto;
  display: flex;
  gap: 4px;
  align-items: center;
}

.topic-tags .topic-tag {
  margin-top: 0;
  margin-left: 0;
}

.topic-symbolic   { color: #333; border-color: #999; }
.topic-subjective { color: #333; border-color: #999; }
.topic-memory     { color: #333; border-color: #999; }
.topic-eventseg   { color: #333; border-color: #999; }
.topic-vision     { color: #333; border-color: #999; }
.topic-networks   { color: #333; border-color: #999; }

.inprep-label {
  display: inline-block;
  margin-top: 0.4rem;
  font-size: var(--fs-sm);
  font-weight: 600;
  letter-spacing: 0.04em;
  color: #888;
  background: #f0f0f0;
  border: 1px solid #ddd;
  padding: 0.15rem 0.55rem;
  border-radius: 20px;
  text-transform: uppercase;
  font-style: italic;
}

.method-fmri   { background: #b8b8b8; color: #111; border: 1px solid #999; }
.method-ieeg   { background: #b8b8b8; color: #111; border: 1px solid #999; }
.method-eeg    { background: #b8b8b8; color: #111; border: 1px solid #999; }
.method-behav  { background: #b8b8b8; color: #111; border: 1px solid #999; }
.method-clin   { background: #b8b8b8; color: #111; border: 1px solid #999; }


/* ---------- Rep filter ---------- */

.rep-filter {
  display: flex;
  align-items: center;
  gap: 0.6rem;
  margin: 0 0 0.6rem;
  cursor: pointer;
}

.filter-group {
  margin-bottom: 2rem;
}

.rep-filter input[type="checkbox"] {
  appearance: none;
  -webkit-appearance: none;
  width: 36px;
  height: 20px;
  background: #ccd5f0;
  border-radius: 20px;
  cursor: pointer;
  transition: background 0.2s;
  position: relative;
  flex-shrink: 0;
}

.rep-filter input[type="checkbox"]::before {
  content: '';
  position: absolute;
  width: 14px;
  height: 14px;
  background: white;
  border-radius: 50%;
  top: 3px;
  left: 3px;
  transition: left 0.2s;
}

.rep-filter input[type="checkbox"]:checked {
  background: #4169E1;
}

.rep-filter input[type="checkbox"]:checked::before {
  left: 19px;
}

.rep-filter span {
  font-size: var(--fs-base);
  font-weight: 500;
  color: #4169E1;
  cursor: pointer;
  user-select: none;
}

</style>

<div class="page-header">
  <h1>Research & Publications</h1>
</div>


<div class="filter-group">
  <label class="rep-filter">
    <input type="checkbox" id="rep-only">
    <span>Show featured work only</span>
  </label>
  <label class="rep-filter">
    <input type="checkbox" id="journals-only">
    <span>Hide conference proceedings</span>
  </label>
  <label class="rep-filter">
    <input type="checkbox" id="hide-inprep">
    <span>Hide in prep. work</span>
  </label>
</div>

<div class="method-legend">
  <span class="label">filter further:</span>
  <span class="method-tag method-fmri" data-filter="method-fmri">fMRI</span>
  <span class="method-tag method-ieeg" data-filter="method-ieeg">iEEG</span>
  <span class="method-tag method-eeg" data-filter="method-eeg">EEG</span>
  <span class="method-tag method-behav" data-filter="method-behav">behavior</span>
  <span class="method-tag method-clin" data-filter="method-clin">clinical</span>
  <span style="margin: 0 0.3rem; color: #ddd;">|</span>
  <span class="topic-tag topic-symbolic" data-filter="topic-symbolic">symbolic systems</span>
  <span class="topic-tag topic-subjective" data-filter="topic-subjective">subjectivity</span>
  <span class="topic-tag topic-memory" data-filter="topic-memory">memory</span>
  <span class="topic-tag topic-eventseg" data-filter="topic-eventseg">event segmentation</span>
  <span class="topic-tag topic-vision" data-filter="topic-vision">vision</span>
  <span class="topic-tag topic-networks" data-filter="topic-networks">networks</span>
</div>

<h2 class="section-header">Selected Publications, Preprints & Conference Proceedings</h2>

<div class="meta-row">
  <span>📄 PDF copies for personal use only; copyright with respective publishers.</span>
  <span>✨ indicates student I've mentored</span>
</div>

<p style="color: #666; margin-bottom: 0.5rem;">
  See my <a href="../Sava_Segal_CV_2.pdf" style="color: #4169E1; font-weight: 500;">CV</a> for a complete list of publications and presentations.
</p>

<h3 class="year-header">In Preparation <span style="text-transform: none; font-style: italic; color: #4169E1; font-weight: 500; font-size: var(--fs-base); letter-spacing: 0;">— check back soon for a preprint</span></h3>

<div class="publication-item">
  <div class="publication-icons"></div>
  <div class="inprep-label">In preparation</div><span class="method-tag method-fmri">fMRI</span><span class="method-tag method-behav">behavior</span><span class="topic-tag topic-subjective">subjectivity</span>
  <div class="pub-title">
    Shifts in neural representations of ambiguous information predict reinterpretation.
  </div>
  <div class="pub-meta">
    <strong>Sava-Segal, C.</strong>, Benson, T.✨, Finn, E.S.
  </div>
</div>

<div class="publication-item">
  <div class="publication-icons"></div>
  <div class="inprep-label">In preparation</div><span class="method-tag method-fmri">fMRI</span><span class="method-tag method-behav">behavior</span><span class="topic-tag topic-subjective">subjectivity</span><span class="topic-tag topic-memory">memory</span>
  <div class="pub-title">
    Reinterpretation counters self-bias in memory through representational updating.
  </div>
  <div class="pub-meta">
    <strong>Sava-Segal, C.</strong>, Benson, T.✨, Finn, E.S.
  </div>
</div>

<div class="publication-item">
  <div class="publication-icons"></div>
  <div class="inprep-label">In preparation</div><span class="method-tag method-fmri">fMRI</span><span class="method-tag method-clin">clinical</span><span class="topic-tag topic-vision">vision</span>
  <div class="pub-title">
    Neural representational alignment in developmental prosopagnosia differs beyond visual regions during naturalistic visual processing.
  </div>
  <div class="pub-meta">
    Kidder, A., <strong>Sava-Segal, C.</strong>, Finn, E.S., Duchaine, B., Baker, C.I. <span style="font-style: italic; color: #888;">VSS, 2026.</span>
  </div>
</div>

<h3 class="year-header">2026</h3>

<div class="publication-item">
  <div class="publication-icons">
    <a class="pub-btn" href="papers/sava-segal-et-al-2026-narrative-twist-shifts-within-individual-neural-representations-of-dissociable-story-features (2).pdf" target="_blank">PDF</a>
    <a class="pub-btn" href="https://doi.org/10.1073/pnas.2512071123" target="_blank">DOI</a>
    <a class="pub-btn" href="https://github.com/csavasegal/darkend_narrative_rep" target="_blank">Code</a>
    <a class="pub-btn" href="https://openneuro.org/datasets/ds007407/versions/1.0.0" target="_blank">OpenNeuro</a>
  </div>
  <div class="rep-label">Featured</div><span class="method-tag method-fmri">fMRI</span><span class="topic-tag topic-subjective">subjectivity</span>
  <div class="pub-title">
    Narrative 'twist' shifts within-individual neural representations of dissociable story features.
  </div>
  <div class="pub-meta">
    <strong>Sava-Segal, C.</strong>, Grall, C., Finn, E.S. (2026). <i>Proceedings of the National Academy of Sciences (PNAS).</i>
  </div>
</div>

<h3 class="year-header">2025</h3>

<div class="publication-item">
  <div class="publication-icons">
    <a class="pub-btn" href="https://osf.io/preprints/psyarxiv/7rbhy_v1" target="_blank">Preprint</a>
  </div>
  <span class="method-tag method-fmri">fMRI</span><span class="topic-tag topic-eventseg">event segmentation</span>
  <div class="pub-title">
    Idiosyncratic event segmentation as a neural marker of loneliness.
  </div>
  <div class="pub-meta">
    Lu, C., <strong>Sava-Segal, C.</strong>, Baek, E.C. (2025). <i>OSF.</i> <span style="font-style: italic; color: #888;">Revise and resubmit.</span>
  </div>
</div>


<h3 class="year-header">2024</h3>

<div class="publication-item">
  <div class="publication-icons">
    <a class="pub-btn" href="https://doi.org/10.1038/s41598-024-77895-5" target="_blank">DOI</a>
  </div>
  <span class="method-tag method-ieeg">iEEG</span><span class="topic-tag topic-vision">vision</span>
  <div class="pub-title">
    Spatiotemporal hierarchies of face representation in the human ventral temporal cortex.
  </div>
  <div class="pub-meta">
    Salehi, S., Schrouff, J., Dehaqani, M.R.A., <strong>Sava-Segal, C.</strong>, Raccah, O., Baek, S. (2024).
    <i>Scientific Reports.</i>
  </div>
</div>

<div class="publication-item" data-type="proceedings">
  <div class="publication-icons">
    <a class="pub-btn" href="papers/520_Paper_authored_CSS_CCN_2024_Final.pdf" target="_blank">PDF</a>
  </div>
  <div class="rep-label">Featured</div><span class="method-tag method-behav">behavior</span><span class="topic-tag topic-memory">memory</span>
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
  <div class="rep-label">Featured</div><span class="method-tag method-behav">behavior</span><span class="topic-tag topic-subjective">subjectivity</span>
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
    <a class="pub-btn" href="https://doi.org/10.1523/JNEUROSCI.2118-22.2024" target="_blank">DOI</a>
  </div>
  <span class="method-tag method-ieeg">iEEG</span><span class="topic-tag topic-symbolic">symbolic systems</span>
  <div class="pub-title">
    Spatiotemporal dynamics of successive activations across the human brain during a simple cognitive task.
  </div>
  <div class="pub-meta">
    Pinheiro-Chagas, P., <strong>Sava-Segal, C.</strong>, Serdar Akkol, Daitch, A., Parvizi, J. (2024).
    <i>Journal of Neuroscience.</i>
  </div>
</div>


<h3 class="year-header">2023</h3>

<div class="publication-item" data-type="proceedings">
  <div class="publication-icons">
    <a class="pub-btn" href="https://cds.ismrm.org/protected/23MProceedings/PDFfiles/1024_1DHBtNPae.html" target="_blank">Proceedings</a>
  </div>
  <span class="method-tag method-fmri">fMRI</span>
  <div class="pub-title">
    A multi-subject deconvolution algorithm for the analysis of naturalistic fMRI data.
  </div>
  <div class="pub-meta">
    Uruñuela, E., <strong>Sava-Segal, C.</strong>, Leung, M.✨, Finn, E.S., Caballero-Gaudes, C. (2023).
    <i>Proceedings of the International Society for Magnetic Resonance in Medicine (ISMRM).</i>
  </div>
</div>

<div class="publication-item">
  <div class="publication-icons">
    <a class="pub-btn" href="papers/css_2023_individual_event-seg.pdf" target="_blank">PDF</a>
    <a class="pub-btn" href="https://doi.org/10.1093/cercor/bhad106" target="_blank">DOI</a>
    <a class="pub-btn" href="https://github.com/csavasegal/individual_event_seg/" target="_blank">Code</a>
    <a class="pub-btn" href="https://openneuro.org/datasets/ds004516/versions/2.0.3" target="_blank">OpenNeuro</a>
  </div>
  <div class="rep-label">Featured</div><span class="method-tag method-fmri">fMRI</span><span class="method-tag method-behav">behavior</span><span class="topic-tag topic-subjective">subjectivity</span><span class="topic-tag topic-eventseg">event segmentation</span><span class="topic-tag topic-memory">memory</span>
  <div class="pub-title">
    Individual differences in neural event segmentation of continuous experiences.
  </div>
  <div class="pub-meta">
    <strong>Sava-Segal, C.</strong>, Richards, C., Leung, M.✨, &amp; Finn, E.S. (2023).
    <i>Cerebral Cortex.</i>
  </div>
</div>


<h3 class="year-header">2021</h3>

<div class="publication-item">
  <div class="publication-icons">
    <a class="pub-btn" href="https://doi.org/10.1523/JNEUROSCI.2785-20.2021" target="_blank">DOI</a>
  </div>
  <span class="method-tag method-ieeg">iEEG</span><span class="method-tag method-clin">clinical</span><span class="topic-tag topic-networks">networks</span>
  <div class="pub-title">
    Intracranial electroencephalography reveals selective task-evoked responses and resting state connectivity of periventricular heterotopias.
  </div>
  <div class="pub-meta">
    Akkol, S., Kucyi, A., Hu, W.H., Zhao, B., Zhang, C., <strong>Sava-Segal, C.</strong>, Liu, S., Razavi, B., Zhang, J., Zhang, K., &amp; Parvizi, J. (2021).
    <i>Journal of Neuroscience.</i>
  </div>
</div>

<div class="publication-item">
  <div class="publication-icons">
    <a class="pub-btn" href="https://doi.org/10.1162/jocn_a_01775" target="_blank">DOI</a>
  </div>
  <span class="method-tag method-ieeg">iEEG</span><span class="topic-tag topic-symbolic">symbolic systems</span>
  <div class="pub-title">
    Overlapping neuronal population responses in the human parietal cortex during visuospatial attention and arithmetic processing.
  </div>
  <div class="pub-meta">
    Liu, N., Pinheiro-Chagas, P., <strong>Sava-Segal, C.</strong>, Kastner, S., Chen, Q., &amp; Parvizi, J. (2021).
    <i>Journal of Cognitive Neuroscience</i>.
  </div>
</div>

<div class="publication-item">
  <div class="publication-icons">
    <a class="pub-btn" href="https://doi.org/10.1523/ENEURO.0065-21.2021" target="_blank">DOI</a>
  </div>
  <span class="method-tag method-eeg">EEG</span>
  <div class="pub-title">
    Expertise modulates neural stimulus-tracking.
  </div>
  <div class="pub-meta">
    Brookshire, G., Mangelsdorf, H.H., <strong>Sava-Segal, C.</strong>, Reis, K., Nusbaum, H.,
    Goldin-Meadow, S., &amp; Casasanto, D. (2021).
    <i>ENeuro</i>.
  </div>
</div>

<div class="publication-item">
  <div class="publication-icons">
    <a class="pub-btn" href="https://doi.org/10.1073/pnas.2100522118" target="_blank">DOI</a>
  </div>
  <span class="method-tag method-ieeg">iEEG</span><span class="method-tag method-clin">clinical</span>
  <div class="pub-title">
    Altered sense of self during seizures in the posteromedial cortex.
  </div>
  <div class="pub-meta">
    Parvizi, J., Braga, R.M., Kucyi, A., Veit, M.J., Pinheiro-Chagas, P., Perry, C.,
    <strong>Sava-Segal, C.</strong>, Zeineh, M., van Staalduinen, E.K., Henderson, J.M., &amp; Markert, M. (2021).
    <i>Proceedings of the National Academy of Sciences (PNAS).</i>
  </div>
</div>

<div class="publication-item">
  <div class="publication-icons">
    <a class="pub-btn" href="https://doi.org/10.1073/pnas.2105031118" target="_blank">DOI</a>
  </div>
  <span class="method-tag method-ieeg">iEEG</span><span class="topic-tag topic-networks">networks</span>
  <div class="pub-title">
    Temporal order of signal propagation within and across intrinsic brain networks.
  </div>
  <div class="pub-meta">
    Veit, M.J., Kucyi, A., Hu, W., Zhang, C., Zhao, B., Guo, Z., Yang, B., <strong>Sava-Segal, C.</strong>,
    Perry, C., Zhang, J., Zhang, K., &amp; Parvizi, J. (2021).
    <i>Proceedings of the National Academy of Sciences (PNAS).</i>
  </div>
</div>


<h3 class="year-header">2020</h3>

<div class="publication-item">
  <div class="publication-icons">
    <a class="pub-btn" href="https://doi.org/10.1038/s41586-020-2731-9" target="_blank">DOI</a>
  </div>
  <span class="method-tag method-ieeg">iEEG</span><span class="method-tag method-behav">behavior</span><span class="method-tag method-clin">clinical</span>
  <div class="pub-title">
    Deep posteromedial cortical rhythm in dissociation.
  </div>
  <div class="pub-meta">
    Vesuna, S., Kauvar, I.V., Richman, E., Gore, F., Oskotsky, T.,
    <strong>Sava-Segal, C.</strong>, Luo, L., Malenka, R.C., Henderson, J.M.,
    Nuyujukian, P., Parvizi, J., &amp; Deisseroth, K. (2020).
    <i>Nature</i>.
  </div>
</div>

<div class="publication-item">
  <div class="publication-icons">
    <a class="pub-btn" href="https://doi.org/10.1093/cercor/bhaa155" target="_blank">DOI</a>
  </div>
  <span class="method-tag method-eeg">EEG</span><span class="method-tag method-behav">behavior</span><span class="topic-tag topic-symbolic">symbolic systems</span><span class="topic-tag topic-vision">vision</span>
  <div class="pub-title">
    Unconscious number discrimination in the human visual system.
  </div>
  <div class="pub-meta">
    Lucero, C., Brookshire, G., <strong>Sava-Segal, C.</strong>, Bottini, R.,
    Goldin-Meadow, S., Vogel, E.K., &amp; Casasanto, D. (2020).
    <i>Cerebral Cortex</i>.
  </div>
</div>

<div class="publication-item">
  <div class="publication-icons">
    <a class="pub-btn" href="https://doi.org/10.3389/fpsyg.2020.00216" target="_blank">DOI</a>
  </div>
  <span class="method-tag method-behav">behavior</span><span class="topic-tag topic-vision">vision</span>
  <div class="pub-title">
    Effects of repetition suppression on sound-induced flash illusion with aging.
  </div>
  <div class="pub-meta">
    Sun, Y., Liu, X., Li, B., <strong>Sava-Segal, C.</strong>, Wang, A., &amp; Zhang, M. (2020).
    <i>Frontiers in Psychology</i>, 11, 216.
  </div>
</div>


<h3 class="year-header">2019</h3>

<div class="publication-item">
  <div class="publication-icons">
    <a class="pub-btn" href="https://doi.org/10.1177/0301006619885796" target="_blank">DOI</a>
  </div>
  <span class="method-tag method-behav">behavior</span><span class="topic-tag topic-vision">vision</span>
  <div class="pub-title">
    The effects of cognitive expectation on sound-induced flash illusion.
  </div>
  <div class="pub-meta">
    Wang, A., Sang, H., He, J., <strong>Sava-Segal, C.</strong>, Tang, X., &amp; Zhang, M. (2019).
    <i>Perception</i>, 48(12), 1214–1234.
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

  var repCheckbox = document.getElementById('rep-only');
  var journalsCheckbox = document.getElementById('journals-only');
  var inprepCheckbox = document.getElementById('hide-inprep');

  function applyFilter() {
    var repOnly = repCheckbox.checked;
    var journalsOnly = journalsCheckbox.checked;
    var hideInprep = inprepCheckbox.checked;

    document.querySelectorAll('.publication-item').forEach(function(item) {
      var hide = false;
      if (repOnly && !item.querySelector('.rep-label')) hide = true;
      if (journalsOnly && item.dataset.type === 'proceedings') hide = true;
      if (hideInprep && item.querySelector('.inprep-label')) hide = true;
      if (activeFilters.size > 0) {
        var matched = false;
        activeFilters.forEach(function(f) {
          if (item.querySelector('.' + f)) matched = true;
        });
        if (!matched) hide = true;
      }
      item.style.display = hide ? 'none' : '';
    });

    document.querySelectorAll('h3.year-header').forEach(function(header) {
      var sibling = header.nextElementSibling;
      var hasVisible = false;
      while (sibling && !sibling.classList.contains('year-header')) {
        if (sibling.classList.contains('publication-item') && sibling.style.display !== 'none') {
          hasVisible = true;
          break;
        }
        sibling = sibling.nextElementSibling;
      }
      header.style.display = hasVisible ? '' : 'none';
    });
  }

  repCheckbox.addEventListener('change', applyFilter);
  journalsCheckbox.addEventListener('change', applyFilter);
  inprepCheckbox.addEventListener('change', applyFilter);
})();
</script>
