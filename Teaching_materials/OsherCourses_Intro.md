---
layout: archive
title: 
permalink: /osher/
published: true
---

<style>
  :root {
    --osher-link: #4169E1;
    --osher-text: #1F3328;
    --osher-muted: #6B7A70;
  }

  .page-header h1 {
    font-size: 2rem;
    font-weight: 700;
    letter-spacing: -0.02em;
    color: #1F3328;
  }

  .osher-intro {
    color: #44564B;
    font-size: 1rem;
    line-height: 1.7;
    margin-bottom: 1.75rem;
  }

  .osher-intro a { color: var(--osher-link); }

  /* ---------- Course boxes ---------- */

  .course {
    border: 1px solid #E6E0D5;
    border-radius: 8px;
    overflow: hidden;
    margin-bottom: 2.75rem;
    background: transparent;
    scroll-margin-top: 90px;
  }

  .course-head {
    display: block;
    background: #F4F0E8;
    padding: 0.9rem 1.25rem 0.8rem;
    cursor: pointer;
    list-style: none;
  }

  .course-head::-webkit-details-marker { display: none; }

  /* drawing across the top of each course card */
  .course-art {
    margin: -0.9rem -1.25rem 0.8rem;
    padding: 0.75rem 1.25rem;
    background: #FFFFFF;
    border-bottom: 1px solid #E6E0D5;
    text-align: center;
  }

  .course-art img {
    height: 150px;
    width: auto;
    max-width: 100%;
    object-fit: contain;
  }

  .course[open] .course-head { border-bottom: 1px solid #E6E0D5; }

  .course-head:hover { background: #EFEAE0; }

  .course-term {
    color: var(--osher-muted);
    font-size: 0.85rem;
  }

  .course-head h2 {
    font-size: 1.2rem;
    font-weight: 600;
    line-height: 1.35;
    margin: 0.2rem 0 0;
  }

  .course-head h2 a {
    color: var(--osher-text);
    text-decoration: none;
  }

  .course-head h2 a {
    background: linear-gradient(#DCE3FB, #DCE3FB) no-repeat left bottom / 100% 0;
    -webkit-box-decoration-break: clone;
    box-decoration-break: clone;
    transition: background-size 0.2s;
  }

  .course-head h2 a:hover {
    color: var(--osher-text);
    background-size: 100% 100%;
  }

  /* "Description ↓ · Course materials →" text links under each title */
  .course-actions {
    margin-top: 0.45rem;
    font-size: 0.95rem;
    color: #aaa;
  }

  .toggle,
  .course-go {
    color: var(--osher-link);
    font-weight: 600;
    text-decoration: none;
  }

  .toggle:hover,
  .course-go:hover { text-decoration: underline; }

  .toggle-hide, .course[open] .toggle-show { display: none; }
  .course[open] .toggle-hide { display: inline; }

  .course-body {
    padding: 1rem 1.25rem 1.1rem;
  }

  .course-body p {
    color: #33463B;
    font-size: 1rem;
    line-height: 1.7;
    margin: 0 0 0.7rem;
  }

  /* lecture titles */
  .course-body .lectures-label { margin: 1rem 0 0.3rem; }

  .lectures {
    margin: 0 0 0.2rem 1.25rem;
    padding: 0;
    font-family: "Inter", "Helvetica Neue", Helvetica, Arial, sans-serif;
  }

  .lectures li {
    color: var(--osher-link);
    font-size: 0.98rem;
    font-weight: 500;
    line-height: 1.5;
    margin: 0.25rem 0;
  }

  .lectures li::marker { color: #999; font-weight: 400; }

  .lectures a {
    color: var(--osher-link);
    text-decoration: none;
  }

  .lectures a:hover { text-decoration: underline; }
</style>


<div class="page-header">
  <h1>Osher Courses, 2022–present</h1>
</div>

<p class="osher-intro">
  Below you'll find materials from five of the courses I've taught at Dartmouth's Osher Lifelong Learning Institute since 2022,
  including lecture notes, readings, and additional resources. I often update these materials after class to reflect
  our discussions.
</p>

<p class="osher-intro">
  If you're considering joining a future course, you can also read
  <a href="https://osher.dartmouth.edu/get_involved/study_leaders/meet_study_leaders/clarasavasegal/index.php">what past participants have said</a>
  about their experience.
</p>

<details class="course" id="fall-2025">
  <summary class="course-head">
    <div class="course-art"><img src="/img/osher/beholder2.png" alt="Watercolor sketch of a head and brain imagining two scenes: a lake with mountains, and three people"></div>
    <div>
      <span class="course-term">Fall 2025</span>
      <h2><a href="/osher/subjectivity2/">Experience in the Eye of the Beholder: How Individual Brains Create Reality II</a></h2>
      <div class="course-actions">
        <span class="toggle"><span class="toggle-show">Description &amp; lectures ↓</span><span class="toggle-hide">Hide description &amp; lectures ↑</span></span> ·
        <a class="course-go" href="/osher/subjectivity2/">Course materials →</a>
      </div>
    </div>
  </summary>
  <div class="course-body">
    <p><strong>Class description:</strong> This course explores the fascinating world of individual consciousness and subjective experience, examining how each person's unique mental landscape emerges from brain activity. We'll explore cutting-edge methods scientists use to study the individual brain—from neuroimaging techniques that reveal personal thought patterns to innovative approaches for measuring subjective states like emotions, memories, and perceptions.</p>
    <p>The course addresses fundamental questions: How do we study something as personal as individual experience? What makes each mind unique? How do subjective feelings translate into observable brain activity?</p>
    <p>Through case studies and current research, we'll examine both the remarkable tools available for understanding individual minds and the profound challenges that remain in bridging the gap between objective brain science and subjective human experience.</p>
    <p><strong>Format:</strong> This course will combine lecture with class discussions.</p>
    <p class="lectures-label"><strong>Lectures:</strong></p>
    <ol class="lectures">
      <li><a href="/osher/subjectivity2/lecture1/">When Expectations Meet Reality</a></li>
      <li><a href="/osher/subjectivity2/lecture2/">The Many Dimensions of Subjectivity</a></li>
      <li><a href="/osher/subjectivity2/lecture3/">Accessing Subjectivity</a></li>
    </ol>
  </div>
</details>

<details class="course" id="summer-2025">
  <summary class="course-head">
    <div class="course-art"><img src="/img/osher/beholder1.png" alt="Watercolor sketch of sound, sight and reading all flowing into a brain"></div>
    <div>
      <span class="course-term">Summer 2025</span>
      <h2><a href="/osher/subjectivity/">Experience in the Eye of the Beholder: How Individual Brains Create Reality I</a></h2>
      <div class="course-actions">
        <span class="toggle"><span class="toggle-show">Description &amp; lectures ↓</span><span class="toggle-hide">Hide description &amp; lectures ↑</span></span> ·
        <a class="course-go" href="/osher/subjectivity/">Course materials →</a>
      </div>
    </div>
  </summary>
  <div class="course-body">
    <p><strong>Class description:</strong> This course explores the fascinating world of individual consciousness and subjective experience, examining how each person's unique mental landscape emerges from brain activity. We'll explore cutting-edge methods scientists use to study the individual brain—from neuroimaging techniques that reveal personal thought patterns to innovative approaches for measuring subjective states like emotions, memories, and perceptions.</p>
    <p>The course addresses fundamental questions: How do we study something as personal as individual experience? What makes each mind unique? How do subjective feelings translate into observable brain activity?</p>
    <p>Through case studies and current research, we'll examine both the remarkable tools available for understanding individual minds and the profound challenges that remain in bridging the gap between objective brain science and subjective human experience.</p>
    <p><strong>Format:</strong> This course will combine lecture with class discussions.</p>
    <p class="lectures-label"><strong>Lectures:</strong></p>
    <ol class="lectures">
      <li><a href="/osher/subjectivity/lecture1/">Our brains construct reality</a></li>
      <li><a href="/osher/subjectivity/lecture2/">Measuring the Unmeasurable - How Scientists Study Inner Experience</a></li>
      <li><a href="/osher/subjectivity/lecture3/">The Social Brain and Interpersonal Subjectivity</a></li>
    </ol>
  </div>
</details>

<details class="course" id="winter-2025">
  <summary class="course-head">
    <div class="course-art"><img src="/img/osher/diverse_minds.png" alt="Watercolor sketch of five heads in profile, each tinted differently"></div>
    <div>
      <span class="course-term">Winter 2025 · Multi-part series</span>
      <h2><a href="/osher/DiverseMinds/coursegoals/">Diverse Minds: What We Know and Don't Know About Psychiatric Disorders and Dementias</a></h2>
      <div class="course-actions">
        <span class="toggle"><span class="toggle-show">Description &amp; lectures ↓</span><span class="toggle-hide">Hide description &amp; lectures ↑</span></span> ·
        <a class="course-go" href="/osher/DiverseMinds/coursegoals/">Course materials →</a>
      </div>
    </div>
  </summary>
  <div class="course-body">
    <p><strong>Class description:</strong> This course explores the diversity of the human brain, offering a comprehensive introduction to the complex interactions between brain structure, function, and behavior. The goal is to focus on a broad spectrum of psychiatric conditions (such as depression, anxiety, schizophrenia, and bipolar disorder) alongside neurodegenerative diseases like Alzheimer's.</p>
    <p>The course will dive into what modern neuroscience and psychiatry have uncovered about these conditions, as well as the gaps that remain in our understanding. Given this diversity of topics, we expect this to be a multiple-part series.</p>
    <p class="lectures-label"><strong>Lectures:</strong></p>
    <ol class="lectures">
      <li><a href="/osher/DiverseMinds/alzheimers/">Alzheimer's Disease</a></li>
      <li><a href="/osher/DiverseMinds/parkinsons/">Parkinson's Disease</a></li>
      <li><a href="/osher/DiverseMinds/depression/">Depression</a></li>
      <li><a href="/osher/DiverseMinds/ptsd/">PTSD</a></li>
      <li><a href="/osher/DiverseMinds/schizophrenia/">Schizophrenia</a></li>
    </ol>
  </div>
</details>

<details class="course" id="spring-2024">
  <summary class="course-head">
    <div class="course-art"><img src="/img/osher/brainbeh2.png" alt="Watercolor sketch of a person walking from trees toward a city, seeing and hearing along the way"></div>
    <div>
      <span class="course-term">Spring 2024</span>
      <h2><a href="/osher/brainbeh2/">Brain and Behavior Part 2: How Do We Process the World Around Us?</a></h2>
      <div class="course-actions">
        <span class="toggle"><span class="toggle-show">Description &amp; lectures ↓</span><span class="toggle-hide">Hide description &amp; lectures ↑</span></span> ·
        <a class="course-go" href="/osher/brainbeh2/">Course materials →</a>
      </div>
    </div>
  </summary>
  <div class="course-body">
    <p><strong>Class description:</strong> How does the brain support our behaviors such as our ability to learn, to remember, or process incoming information? How are each of our brains unique? How and why do each of us "see" the world differently? The class will introduce the broad landscape of the field of cognitive neuroscience through both readings and through doing hands-on psychological experiments.</p>
    <p>A lot of science is meant to be read by scientists, but when it comes to something as inherently interesting and relatable as the brain, it is important to make this material digestible and that is the scope of the course!</p>
    <p class="lectures-label"><strong>Lectures:</strong></p>
    <ol class="lectures">
      <li>Introduction to data collection and methods</li>
      <li>Visual system I</li>
      <li>Vision II</li>
      <li>Memory</li>
      <li>Language and social knowledge</li>
    </ol>
  </div>
</details>

<details class="course" id="fall-2022">
  <summary class="course-head">
    <div class="course-art"><img src="/img/osher/brainbeh1.png" alt="Watercolor sketch of a brain and a runner linked by arrows, with heart, muscle and smile icons"></div>
    <div>
      <span class="course-term">Fall 2022, Winter 2023</span>
      <h2><a href="/osher/brainbeh1/">Brain and Behavior: How Are They Linked?</a></h2>
      <div class="course-actions">
        <span class="toggle"><span class="toggle-show">Description &amp; lectures ↓</span><span class="toggle-hide">Hide description &amp; lectures ↑</span></span> ·
        <a class="course-go" href="/osher/brainbeh1/">Course materials →</a>
      </div>
    </div>
  </summary>
  <div class="course-body">
    <p><strong>Class description:</strong> How does the brain support our behaviors, such as our ability to learn, to remember, or process incoming information? We will start with the basics of how the brain supports the senses with a focus on vision. This will start with the development of brain regions all the way up to how specific brain regions support certain visual processing (for example: how are we able to read?)</p>
    <p>We will then discuss how modern neuroscience and psychology understands more complex processes such as language, emotion, learning and memory, and creativity. How do multiple brain regions support these complex processes? How do we study this in a robust manner? How do these vary at the individual level (i.e. how may your brain support behaviors that are unique to you)?</p>
    <p>The class will introduce the broad landscape of the field of cognitive neuroscience through both readings and through doing hands-on psychological experiments. A lot of science is meant to be read by scientists, but when it comes to something as inherently interesting and relatable as the brain, it is important to make this material digestible, and that is the scope of the course!</p>
    <p class="lectures-label"><strong>Lectures:</strong></p>
    <ol class="lectures">
      <li>Introduction to data collection and methods</li>
      <li>Visual system</li>
      <li>Language and Math</li>
      <li>Memory and Sleep</li>
      <li>Emotion and social knowledge</li>
    </ol>
  </div>
</details>
