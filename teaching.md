---
layout: category
title: 
permalink: /teaching/
published: true
---

<style>
:root {
  --accent-mint: #4FC3A1;
  --accent-mint-dark: #1F7A5E;
  --accent-mint-light: #EDFAF4;

  /* same four sizes as the Research page */
  --fs-title: 1.563rem; /* page title */
  --fs-lg: 1.25rem;     /* section headers */
  --fs-base: 1rem;      /* prose */
  --fs-sm: 0.85rem;     /* secondary text: terms, descriptions, quotes */
}

html { scroll-behavior: smooth; }

body {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: var(--fs-base);
  color: #333;
  line-height: 1.7;
}

.page-header {
  text-align: center;
  margin-bottom: 2rem;
  padding: 1.5rem 0;
  border-bottom: 1px solid #e6e6e6;
}

.page-header h1 {
  font-size: var(--fs-title);
  color: #4169E1;
  margin-bottom: 0;
}

.section-intro {
  font-size: var(--fs-base);
  line-height: 1.8;
  margin-bottom: 1.5rem;
  color: #555;
}

.intro-nav {
  font-size: var(--fs-base);
  color: #555;
  margin-bottom: 0.5rem;
}

.intro-nav a { color: #4169E1; font-weight: 500; }

/* ---------- Section scaffolding ---------- */

.t-section { scroll-margin-top: 90px; }

.section-header {
  font-size: var(--fs-lg);
  font-weight: 700;
  color: #4169E1;
  margin-top: 3rem;
  margin-bottom: 1.5rem;
  padding-bottom: 0.4rem;
  border-bottom: 1px solid #ddd;
}

/* ---------- TA list ---------- */

.ta-list { list-style: none; padding: 0; }

.ta-item { padding: 0.5rem 0; margin: 0.75rem 0; }

.ta-term { font-weight: bold; color: #333; }

.ta-course { color: #4169E1; margin-left: 0.5rem; }

.ta-award {
  font-size: var(--fs-sm);
  color: #1F7A5E;
  margin-top: 0.15rem;
}

/* ---------- Course cards ---------- */

.course-item {
  margin: 1rem 0;
  padding: 1.1rem 1.35rem 1rem;
  background: #f7f9fc;
  border: 1px solid #e4eaf5;
  border-radius: 8px;
}

.course-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  gap: 1rem;
  margin-bottom: 0.65rem;
}

.course-title {
  color: #333;
  font-weight: 600;
  font-size: var(--fs-base);
  line-height: 1.4;
}

.course-term {
  font-size: var(--fs-sm);
  color: #888;
  white-space: nowrap;
  flex-shrink: 0;
}

.course-description {
  font-size: var(--fs-sm);
  line-height: 1.65;
  color: #555;
  margin-bottom: 0.65rem;
}

.course-link {
  display: inline-block;
  font-size: var(--fs-sm);
  color: #4169E1;
  font-weight: 500;
  text-decoration: none;
}

.course-link:hover { text-decoration: underline; }

.highlight-link {
  display: inline-block;
  padding: 0.5rem 1rem;
  background-color: var(--accent-mint-light);
  border: 2px solid var(--accent-mint);
  border-radius: 6px;
  color: var(--accent-mint-dark);
  text-decoration: none;
  font-weight: 600;
  font-size: var(--fs-sm);
  transition: background-color 0.2s, border-color 0.2s, color 0.2s;
}

.highlight-link:hover {
  background-color: var(--accent-mint-dark);
  border-color: var(--accent-mint-dark);
  color: white;
  text-decoration: none;
}

/* ---------- Testimonials ---------- */

.testimonials {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1.5rem 2rem;
  margin: 2rem auto 0;
  max-width: 680px;
}

@media (max-width: 600px) {
  .testimonials { grid-template-columns: 1fr; }
}

.testimonial {
  border-left: 2px solid var(--accent-mint);
  padding-left: 1rem;
}

.testimonial p {
  font-style: italic;
  color: var(--accent-mint-dark);
  font-size: var(--fs-sm);
  line-height: 1.6;
  margin: 0 0 0.4rem;
}

.testimonial cite {
  display: block;
  font-size: var(--fs-sm);
  font-style: normal;
  color: #777;
}

.divider {
  margin: 3rem 0;
  border: 0;
  border-top: 1px solid #ddd;
}

/* ---------- Foot ---------- */

.t-foot {
  margin-top: 2.5rem;
  padding-top: 1.5rem;
  border-top: 1px solid #e6e6e6;
  text-align: center;
}

.to-top {
  font-size: var(--fs-sm);
  color: #4169E1;
  font-weight: 500;
  text-decoration: none;
}
.to-top:hover { text-decoration: underline; }
</style>


<div class="page-header">
  <h1>Teaching &amp; Mentorship</h1>
</div>

<p class="section-intro">
  I have taught across the lifespan — from pre-K and first-grade classrooms to undergraduate students
  (including mentoring thesis students) to older adults (ages 50+) at the Osher Lifelong Learning
  Institute at Dartmouth, where I design discussion-based courses for retirees eager to engage with
  cutting-edge research. My formal training includes coursework through the Dartmouth Center for
  Advanced Learning, as well as training in education policy and socioemotional learning strategies
  through the Careers in Education program at UChicago, supported by the
  <a href="https://voices.uchicago.edu/successfulpathways/milgrom-community-service-and-innovation-fellowship/"
     style="color: #4169E1; font-weight: 500;">Milgrom Education Impact Fellowship</a>.
  Overall, I approach teaching as an adaptive, learner-centered process shaped by context, age, and
  goals. For my undergraduate teaching and mentorship, I have received the Marie A. Center 1982 Award
  for Excellence in Teaching and two Outstanding Graduate Student Teacher Awards.
</p>

<p class="intro-nav">
  Read on for my <a href="#sec-teaching">undergraduate teaching</a>,
  <a href="#sec-mentorship">mentorship</a>, and
  <a href="#sec-osher">independent teaching at Osher</a>.
</p>


<!-- ===== UNDERGRADUATE TEACHING ===== -->
<section id="sec-teaching" class="t-section">
  <h3 class="section-header">Undergraduate Teaching</h3>

  <p class="section-intro">I have served as a Teaching Assistant in Dartmouth's Psychological and Brain Sciences Department for the following courses. After completing my TAships, I was awarded my department's <span style="color: #1F7A5E;">Marie A. Center 1982 Award for Excellence in Teaching</span>.</p>

  <ul class="ta-list">
    <li class="ta-item">
      <span class="ta-term">Fall 2023:</span>
      <span class="ta-course">Introduction to Neuroscience</span>
      <div class="ta-award">Outstanding Graduate Student Teacher Award</div>
    </li>
    <li class="ta-item">
      <span class="ta-term">Winter 2023:</span>
      <span class="ta-course">Introduction to Neuroscience</span>
      <div class="ta-award">Outstanding Graduate Student Teacher Award</div>
    </li>
    <li class="ta-item">
      <span class="ta-term">Fall 2022:</span>
      <span class="ta-course">Introduction to Neuroscience</span>
    </li>
    <li class="ta-item">
      <span class="ta-term">Spring 2022:</span>
      <span class="ta-course">Psychological Research Methods</span>
    </li>
  </ul>

  <div class="testimonials">
    <div class="testimonial">
      <p>"Her ability to pinpoint what was important was amazing, but she also went above and beyond by making sure that we understood — and didn't memorize — key topics."</p>
      <cite>— Undergraduate student, Intro to Neuroscience, Winter 2023</cite>
    </div>
    <div class="testimonial">
      <p>"I think she was the reason that I did well in this class and want to continue to pursue classes in the Neuroscience department."</p>
      <cite>— Undergraduate student, Intro to Neuroscience, Fall 2022</cite>
    </div>
  </div>
</section>

<hr class="divider">


<!-- ===== UNDERGRADUATE MENTORSHIP ===== -->
<section id="sec-mentorship" class="t-section">
  <h3 class="section-header">Undergraduate Mentorship</h3>

  <p class="section-intro">I have mentored several undergraduate researchers, including three thesis students across the Cognitive Science, Psychology, and Neuroscience departments, as well as two additional students on formal research projects. I enjoyed giving students the space to develop truly independent research directions, even when those extended beyond my own current work. For instance, my thesis students explored topics including social identity and reappraisal, individual variation in dialogue and conversation, and the relationship between depression and idiosyncratic perception. All three thesis students received fellowships for their work, and I supported each of their grant applications. See my <a href="../Sava_Segal_CV_2.pdf" style="color: #4169E1; font-weight: 500;">CV</a> for more details.</p>
</section>

<hr class="divider">


<!-- ===== INDEPENDENT TEACHING (OSHER) ===== -->
<section id="sec-osher" class="t-section">
  <h3 class="section-header">Independent Teaching · Osher Courses</h3>

  <p class="section-intro">I design and teach courses for the Osher Lifelong Learning Institute at Dartmouth, serving retirees and adults approaching retirement. I both design the curriculum and deliver the lectures, creating an engaging, discussion-based learning environment. <a href="https://osher.dartmouth.edu/get_involved/study_leaders/meet_study_leaders/clarasavasegal/index.php" class="highlight-link">See my courses and reviews here</a></p>

  <p class="section-intro">If you are an Osher student, class materials are on the <a href="/osher/" style="color: #4169E1; font-weight: 500;">Osher Courses page</a>.</p>

  <div class="testimonials">
    <div class="testimonial">
      <p>"I loved how she adjusted her topics to the direction of the class discussion. It is clear the instructor was very well prepared and versed in the material to be able to do this."</p>
      <cite>— Osher participant, Spring 2024</cite>
    </div>
    <div class="testimonial">
      <p>"She was very knowledgeable but was always prepared to check out something where she needed help with the answer — refreshing to have a class with a young Ph.D. student who was so enthusiastic."</p>
      <cite>— Osher participant, Fall 2022</cite>
    </div>
  </div>

  <div class="course-item">
    <div class="course-header">
      <div class="course-title">Experience in the Eye of the Beholder: How Individual Brains Create Reality II</div>
      <div class="course-term">Fall 2025</div>
    </div>
    <div class="course-description">
      This course explores the fascinating world of individual consciousness and subjective experience, examining how each person's unique mental landscape emerges from brain activity. We explore cutting-edge methods scientists use to study the individual brain—from neuroimaging techniques that reveal personal thought patterns to innovative approaches for measuring subjective states like emotions, memories, and perceptions. The course addresses fundamental questions: How do we study something as personal as individual experience? What makes each mind unique?
    </div>
    <a href="/osher/subjectivity2/" class="course-link">→ View class materials</a>
  </div>

  <div class="course-item">
    <div class="course-header">
      <div class="course-title">Experience in the Eye of the Beholder: How Individual Brains Create Reality I</div>
      <div class="course-term">Summer 2025</div>
    </div>
    <div class="course-description">
      The first version of this course exploring individual consciousness and subjective experience, examining how scientists are beginning to study not just what people are thinking, but how they experience it. This course combines lecture with class discussions and insights from my own research on how people understand the world differently from one another.
    </div>
    <a href="/osher/subjectivity/" class="course-link">→ View class materials</a>
  </div>

  <div class="course-item">
    <div class="course-header">
      <div class="course-title">Diverse Minds: What We Know and Don't Know About Psychiatric Conditions</div>
      <div class="course-term">Winter 2025</div>
    </div>
    <div class="course-description">
      This course explores the diversity of the human brain, offering a comprehensive introduction to the complex interactions between brain structure, function, and behavior. The goal is to focus on a broad spectrum of psychiatric conditions (such as depression, anxiety, schizophrenia, and bipolar disorder) alongside neurodegenerative diseases like Alzheimer's. Given the diversity of topics, this is designed as a multi-part series.
    </div>
    <a href="/osher/DiverseMinds/coursegoals/" class="course-link">→ View class materials</a>
  </div>

  <div class="course-item">
    <div class="course-header">
      <div class="course-title">Brain and Behavior Part 2: How Do We Process the World Around Us?</div>
      <div class="course-term">Spring 2024</div>
    </div>
    <div class="course-description">
      This course extends the exploration of cognitive neuroscience by examining how we perceive and interpret our surroundings, building on the concepts introduced in the first part. The class introduces the broad landscape of cognitive neuroscience through both readings and hands-on psychological experiments.
    </div>
  </div>

  <div class="course-item">
    <div class="course-header">
      <div class="course-title">Brain and Behavior: How Are They Linked?</div>
      <div class="course-term">Fall 2022, Winter 2023</div>
    </div>
    <div class="course-description">
      This course explores how the brain supports behaviors such as learning, memory, and processing information. It emphasizes the uniqueness of individual brains and how we each perceive the world differently. The course involves hands-on psychological experiments to illustrate key concepts, starting with the basics of vision and developing into more complex processes like language, emotion, and creativity.
    </div>
  </div>
</section>

<div class="t-foot" id="t-end">
  <a href="#" class="to-top" onclick="window.scrollTo({top:0,behavior:'smooth'});return false;">↑ back to top</a>
</div>

