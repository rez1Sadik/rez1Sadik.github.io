---
permalink: /
title: ""
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* Global Modern Academic Style - Perfectly matched to Publications Page */
  :root {
    --primary-color: #2c3e50; 
    --accent-color: #f0f7ff;  
    --text-main: #3b3b3b;     
    --text-heading: #2c3e50;  
    --font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  }

  body {
    font-family: var(--font-family);
  }

  /* Standardized Section Titles */
  .section-title {
    margin-top: 45px; 
    border-bottom: 1px solid #eaeaea; 
    padding-bottom: 8px; 
    text-transform: uppercase; 
    color: var(--text-heading);
    font-size: 1.15em !important; /* Forced to 1.15em to prevent theme overrides */
    letter-spacing: 0.05em;
    font-weight: 600;
  }

  /* Standardized Text Style for Bio and Research */
  .content-text {
    text-align: justify; 
    font-size: 0.95em; 
    line-height: 1.6; 
    margin-bottom: 20px; 
    color: var(--text-main);
  }

  /* Research Interest Badges */
  .interest-pills {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 15px;
    margin-bottom: 30px;
  }
  .pill {
    background-color: var(--primary-color); 
    color: #ffffff; 
    font-size: 0.85em; 
    font-weight: 600;
    padding: 5px 12px;
    border-radius: 4px; 
    letter-spacing: 0.03em;
  }

  /* News Timeline Styling */
  .news-scroll-container {
    max-height: 500px; 
    overflow-y: auto; 
    margin-top: 20px;
    padding-right: 15px;
  }
  .news-scroll-container::-webkit-scrollbar { width: 6px; }
  .news-scroll-container::-webkit-scrollbar-track { background: #f9f9f9; border-radius: 10px; }
  .news-scroll-container::-webkit-scrollbar-thumb { background: #ccc; border-radius: 10px; }
  .news-scroll-container::-webkit-scrollbar-thumb:hover { background: #999; }

  .timeline-item {
    display: flex; 
    margin-bottom: 12px; 
    font-size: 0.9em; 
    line-height: 1.5;
    padding: 4px 0;
    align-items: baseline; 
  }
  
  .timeline-date {
    min-width: 95px; 
    font-weight: 700; 
    color: #555; /* Matched to publications abstract button gray */
  }
  
  .timeline-content {
    flex: 1; 
    color: var(--text-main);
  }

  /* Highlighted Milestones */
  .timeline-item.milestone {
    background-color: var(--accent-color); 
    border-radius: 4px;
    padding: 8px 12px; 
    margin-left: -10px; 
    border-left: 3px solid var(--primary-color);
    margin-top: 2px;
    margin-bottom: 12px;
  }

  /* Collaboration Alert - Reverted to Original Color */
  .collab-box {
    background-color: #fffaf0; 
    border-left: 4px solid #d92121;
    padding: 12px 15px;
    font-size: 0.9em;
    color: #333;
    font-weight: 500;
    margin: 30px 0;
    border-radius: 0 4px 4px 0;
    box-shadow: 0 1px 3px rgba(0,0,0,0.05);
  }

  @media (max-width: 768px) {
    .timeline-item { flex-direction: column; }
    .timeline-date { margin-bottom: 2px; font-size: 0.9em; }
    .content-text { text-align: left; }
    .timeline-item.milestone { margin-left: 0; }
  }
</style>

<h2 class="section-title" style="margin-top: 0;">Biography</h2>

<div class="content-text">
  I am a <strong>Data Manager</strong> at the South Dakota Department of Education, where I leverage data analytics to drive evidence-based educational strategies. My academic foundation comprises an M.Sc. in Business Analytics from the University of South Dakota, an M.B.A. in Marketing from the IBA, University of Dhaka, and a B.Sc. in Electrical and Electronics Engineering from the Islamic University of Technology. 
</div>

<div class="content-text">
  As an active researcher, my work explores the applied intersections of <strong>Machine Learning</strong> and <strong>Deep Learning</strong>, with a primary focus on <strong>Natural Language Processing (NLP)</strong>. I am dedicated to addressing real-world challenges, ranging from sentiment analysis to predictive healthcare modeling. My collaborative research has been featured in reputable peer-reviewed venues including <strong>ICTCS</strong>, <strong>SASI-ITE</strong>, and <strong>ICSSES</strong>.
</div>

<div class="collab-box">
  I am actively seeking collaborative research opportunities to contribute to the world of data.
</div>

<h2 class="section-title">Research Interests</h2>
<div class="interest-pills">
  <span class="pill">Deep Learning</span>
  <span class="pill">NLP</span>
  <span class="pill">LLM</span>
  <span class="pill">Image Processing</span>
  <span class="pill">Predictive Modeling</span>
</div>

<h2 class="section-title">Recent News</h2>
<div class="news-scroll-container">
  
  <div class="timeline-item">
    <div class="timeline-date">Jan 2025</div>
    <div class="timeline-content">Amazon review sentiment analysis paper accepted at <strong>ICTCS '25</strong>.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">July 2024</div>
    <div class="timeline-content">Thyroid disease detection paper accepted at <strong>AISP '24</strong>.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Apr 2024</div>
    <div class="timeline-content">Dengue outbreak forecasting paper accepted at <strong>ICSSES '24</strong>.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Mar 2024</div>
    <div class="timeline-content">Bangla fake news detection article accepted at <strong>ICPS '24</strong>.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Feb 2024</div>
    <div class="timeline-content">Bangla sign language recognition paper accepted at <strong>ICDSIS '24</strong>.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Jan 2024</div>
    <div class="timeline-content">Crop management recommendation system paper accepted at <strong>ICSSES '24</strong>.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Dec 2023</div>
    <div class="timeline-content">Short text sentiment analysis article accepted in the <strong>Journal of Computer and Communications</strong>.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Nov 2023</div>
    <div class="timeline-content">Social media fake news identification paper accepted at <strong>SASI-ITE '23</strong>.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Oct 2023</div>
    <div class="timeline-content">Liver disease prediction paper published in <strong>ISBM '23</strong>.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Sep 2023</div>
    <div class="timeline-content">Diabetes risk prediction paper accepted at <strong>INCOFT '23</strong>.</div>
  </div>

  <div class="timeline-item milestone">
    <div class="timeline-date">Aug 2023</div>
    <div class="timeline-content">Joined the <strong>SD Department of Education</strong> as a <strong>Data Manager</strong>.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Jul 2023</div>
    <div class="timeline-content">Book chapter accepted in the <strong>Encyclopedia of Heroism Studies</strong> (Springer).</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">May 2023</div>
    <div class="timeline-content">Joined the <strong>USD Center for Teaching & Learning</strong> as a <strong>Data Analyst</strong>.</div>
  </div>

  <div class="timeline-item milestone">
    <div class="timeline-date">Mar 2023</div>
    <div class="timeline-content">Inducted into the <strong>Beta Gamma Sigma Honor Society</strong>.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Jan 2023</div>
    <div class="timeline-content">Appointed as an <strong>Adjunct Lecturer</strong> at the <strong>USD Beacom School of Business</strong>.</div>
  </div>

  <div class="timeline-item milestone">
    <div class="timeline-date">Dec 2022</div>
    <div class="timeline-content">Graduated with an <strong>M.Sc. in Business Analytics</strong> (CGPA: 4.0) from <strong>USD</strong>.</div>
  </div>

  <div class="timeline-item milestone">
    <div class="timeline-date">Apr 2022</div>
    <div class="timeline-content">Received the <strong>Leonard E. Arnaud Memorial Award & Scholarship</strong>.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Aug 2021</div>
    <div class="timeline-content">Joined the <strong>USD Beacom School of Business</strong> as a <strong>Graduate Research Assistant</strong>.</div>
  </div>

</div>