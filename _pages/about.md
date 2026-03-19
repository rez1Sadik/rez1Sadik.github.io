---
permalink: /
title: "BIOGRAPHY"
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* Global Modern Academic Style */
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
    font-size: 1.15em !important; 
    letter-spacing: 0.05em;
    font-weight: 600;
  }

  /* Standardized Text Style for Bio */
  .content-text {
    text-align: justify !important; 
    text-justify: inter-word !important;
    font-size: 0.95em; 
    line-height: 1.7; 
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
    padding: 6px 14px;
    border-radius: 4px; 
    letter-spacing: 0.03em;
    box-shadow: 0 2px 4px rgba(0,0,0,0.05);
  }

  /* News Timeline Styling */
  .news-scroll-container {
    max-height: 500px; 
    overflow-y: auto; 
    margin-top: 20px;
    padding-right: 15px;
  }
  .news-scroll-container::-webkit-scrollbar { width: 5px; }
  .news-scroll-container::-webkit-scrollbar-track { background: #fdfdfd; }
  .news-scroll-container::-webkit-scrollbar-thumb { background: #d1d5db; border-radius: 10px; }
  .news-scroll-container::-webkit-scrollbar-thumb:hover { background: #9ca3af; }

  .timeline-item {
    display: flex; 
    margin-bottom: 14px; 
    font-size: 0.9em; 
    line-height: 1.5;
    padding: 4px 0;
    align-items: baseline; 
  }
  
  .timeline-date {
    min-width: 95px; 
    font-weight: 700; 
    color: #64748b; 
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

  /* Collaboration Alert - Eye-Soothing Academic Style */
  .collab-box {
    background-color: #f8fbfd; /* Soft, clean icy blue */
    border-left: 4px solid var(--primary-color); /* Navy border */
    padding: 14px 18px;
    font-size: 0.95em;
    color: var(--text-heading);
    font-weight: 500;
    margin: 30px 0;
    border-radius: 0 4px 4px 0;
    box-shadow: 0 1px 3px rgba(0,0,0,0.03);
    line-height: 1.6;
  }

  /* Mobile & Tablet Responsiveness */
  @media (max-width: 768px) {
    .timeline-item { 
      flex-direction: column; 
      margin-bottom: 18px;
    }
    .timeline-date { 
      margin-bottom: 4px; 
      font-size: 0.85em; 
      color: var(--primary-color);
    }
    .timeline-item.milestone { 
      margin-left: 0; 
      padding: 10px 12px;
    }
  }
</style>

{% comment %}
<div class="content-text">
  <strong>Md Rezwane Sadik</strong> is a fully funded Ph.D. researcher in Computer Science at Kennesaw State University, advised by <strong>Dr. Shumit Saha</strong> in the <strong>Resonance Lab</strong>. His research applies Machine Learning and Natural Language Processing (NLP) to predictive healthcare modeling. Currently, he develops deep learning architectures to build AI-driven diagnostic tools for <strong>Obstructive Sleep Apnea (OSA)</strong>. Through multi-institutional collaborations his work aims to translate clinical algorithms into scalable solutions for healthcare systems, national laboratories, and industry. Previously, he served as a Data Manager for the South Dakota Department of Education.
</div>
{% endcomment %}

<div class="content-text">
  Sadik’s multidisciplinary foundation includes an M.Sc. in Business Analytics (University of South Dakota), an M.B.A. (IBA, University of Dhaka), and a B.Sc. in Electrical and Electronic Engineering (Islamic University of Technology). He is an inductee of the <strong>Beta Gamma Sigma Honor Society</strong> and recipient of the <strong>Leonard E. Arnaud Memorial Award</strong>. His research addressing real-world data challenges is widely published in peer-reviewed venues indexed across <strong>IEEE Xplore</strong>, the <strong>ACM Digital Library</strong>, and <strong>Springer</strong>.
</div>



<div class="collab-box">
  <i class="fas fa-lightbulb" style="color: #64748b; margin-right: 8px;"></i> I am actively seeking collaborative research opportunities to contribute to the world of data.
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

  <div class="timeline-item milestone">
    <div class="timeline-date">Mar 2026</div>
    <div class="timeline-content">Accepted a fully-funded Ph.D. offer in Computer Science at <strong>Kennesaw State University</strong>.</div>
  </div>
  
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