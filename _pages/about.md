---
permalink: /
title: ""
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* Base Styles for Desktop */
  .bio-text {
    text-align: justify; 
    font-size: 1.05em; 
    line-height: 1.6; 
    margin-bottom: 25px; 
    color: #333;
  }
  .research-box {
    background-color: #fcfcfc; 
    padding: 15px; 
    border-left: 4px solid #5594d2; 
    margin-bottom: 30px; 
    border-radius: 0 4px 4px 0;
  }
  .research-text {
    margin: 0; 
    font-size: 0.95em; 
    color: #444; 
    font-weight: 600; 
    text-transform: uppercase; 
    letter-spacing: 0.8px;
    line-height: 1.6;
  }
  
  /* Timeline Scrollbar Styles */
  .news-scroll-container::-webkit-scrollbar { width: 5px; }
  .news-scroll-container::-webkit-scrollbar-track { background: #f9f9f9; }
  .news-scroll-container::-webkit-scrollbar-thumb { background: #ccc; border-radius: 10px; }
  .news-scroll-container::-webkit-scrollbar-thumb:hover { background: #5594d2; }

  /* Timeline Base Styles */
  .timeline-item {
    display: flex; 
    margin-bottom: 20px; 
    font-size: 0.85em; 
    line-height: 1.6;
  }
  .timeline-date {
    min-width: 90px; 
    font-weight: 700; 
    color: #777;
  }
  .timeline-content {
    flex: 1; 
    padding-left: 15px; 
    color: #333; 
    text-align: justify;
  }
  .timeline-content ul {
    margin: 0; 
    padding-left: 15px;
  }

  /* 📱 MOBILE RESPONSIVE FIXES */
  @media (max-width: 768px) {
    .bio-text {
      text-align: left; /* মোবাইলে justify দেখতে খারাপ লাগে, তাই left করা হলো */
      font-size: 0.95em;
    }
    .research-text {
      font-size: 0.85em;
    }
    .research-text span {
      display: inline-block; /* মোবাইলে পাইপ (|) গুলো সুন্দরভাবে নিচে নামবে */
    }
    .timeline-item {
      flex-direction: column; /* মোবাইলে তারিখ লেখার উপরে চলে যাবে */
      margin-bottom: 25px;
    }
    .timeline-date {
      min-width: auto;
      margin-bottom: 5px;
      color: #5594d2; /* মোবাইলে তারিখ হাইলাইট করার জন্য নীল রঙ */
      border-bottom: 1px dashed #eee;
      padding-bottom: 3px;
      display: inline-block;
    }
    .timeline-content {
      padding-left: 0; /* প্যাডিং শূন্য করা হলো যাতে পুরো স্ক্রিন ব্যবহার করা যায় */
      text-align: left;
    }
  }
</style>


<h2 style="margin-top: 0; border-bottom: 1px solid #eee; text-transform: uppercase; padding-bottom: 10px; color: #333;">Biography</h2>

<div class="bio-text">
  I am a Data Manager at the <a href="https://doe.sd.gov" target="_blank" style="text-decoration: none; color: #5594d2; font-weight: 500;">Department of Education, State of South Dakota</a>, where I leverage data-driven insights to inform educational strategies. I earned my M.Sc. in Business Analytics from the <a href="https://www.usd.edu" target="_blank" style="text-decoration: none; color: #5594d2; font-weight: 500;">University of South Dakota</a> (CGPA 4.0), an M.B.A. in Marketing from the <a href="#" style="text-decoration: none; color: #5594d2; font-weight: 500;">University of Dhaka</a>, and a B.Sc. in Electrical and Electronics Engineering from the <a href="#" style="text-decoration: none; color: #5594d2; font-weight: 500;">Islamic University of Technology (IUT)</a>, Bangladesh. Prior to my current role, I gained extensive experience in analytical and engineering capacities, including serving as an Adjunct Lecturer at the Beacom School of Business. Our collaborative research has been featured in reputable academic venues, including <strong>ICTCS</strong>, <strong>SASI-ITE</strong>, and <strong>ICSSES</strong>.
</div>

<div class="bio-text">
  My research investigates machine learning and deep learning from an applied perspective, focusing on <strong>Natural Language Processing (NLP)</strong>, <strong>Large Language Models (LLMs)</strong>, and <strong>Computer Vision</strong>. I explore model optimization and efficient deployment for real-world challenges like sentiment analysis and predictive healthcare modeling.
</div>


<h2 style="margin-top: 0; border-bottom: 1px solid #eee; text-transform: uppercase; padding-bottom: 10px; color: #333;">Research Interests</h2>

<div class="research-box">
  <p class="research-text">
    <span style="color: #5594d2; font-weight: 800; margin-right: 12px;">FOCUS:</span>
    Deep Learning <span style="color: #ccc; margin: 0 8px;">|</span> 
    NLP <span style="color: #ccc; margin: 0 8px;">|</span> 
    LLM <span style="color: #ccc; margin: 0 8px;">|</span> 
    Image Processing
  </p>
</div>

<p style="color: #d92121; text-align: left; font-size: 1.05em; font-weight: 500; margin-bottom: 40px; line-height: 1.5;">
  I am actively seeking collaborative research opportunities and am highly motivated to contribute to the world of data.
</p>


<h2 style="margin-top: 40px; border-bottom: 1px solid #eee; text-transform: uppercase; padding-bottom: 10px; color: #333;">Recent News</h2>

<div class="news-scroll-container" style="max-height: 500px; overflow-y: auto; padding-right: 15px; margin-top: 20px;">
  
  <div class="timeline-item">
    <div class="timeline-date">2025</div>
    <div class="timeline-content">
      <ul>
        <li>Paper "Aspect-Based Sentiment Analysis of Amazon Product Reviews Using Machine Learning Models and Hybrid Feature Engineering" accepted at <strong>ICTCS 2025</strong>.</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2024</div>
    <div class="timeline-content">
      <ul>
        <li>Published journals on Sentiment Analysis in short texts and Bangla Fake News Detection.</li>
        <li>Published multiple conference papers at <strong>SASI-ITE</strong>, <strong>ICDSIS</strong>, <strong>AISP</strong>, and <strong>ICSSES</strong>.</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2023</div>
    <div class="timeline-content">
      <ul>
        <li><strong>Aug:</strong> Appointed as <strong>Data Manager</strong> at the Department of Education, State of South Dakota.</li>
        <li><strong>May-Jul:</strong> Worked as a Data Analyst at the Center for Teaching & Learning, USD.</li>
        <li><strong>Jan-May:</strong> Served as an Adjunct Lecturer at the Beacom School of Business, USD.</li>
        <li>Recognized by the Beta Gamma Sigma Honor Society for academic excellence.</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2022</div>
    <div class="timeline-content">
      <ul>
        <li>Completed <strong>M.Sc. in Business Analytics</strong> from the University of South Dakota with a perfect CGPA of 4.0.</li>
        <li>Received the Leonard E. Arnaud memorial Award & Scholarship for leadership.</li>
        <li>Served as a Graduate Research Assistant at the Beacom School of Business (Aug 2021-Dec 2022).</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2021</div>
    <div class="timeline-content">
      <ul>
        <li>Earned <strong>M.B.A. in Marketing</strong> from the University of Dhaka.</li>
        <li><strong>Jan-Jul:</strong> Worked as a Business Analyst at Millennium Information Solution Limited.</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2015-2019</div>
    <div class="timeline-content">
      <ul>
        <li><strong>2017-2019:</strong> Quality Assurance Engineer at LG, Dhaka.</li>
        <li><strong>2016-2017:</strong> Assistant Engineer (R&D) at Walton Group.</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2014</div>
    <div class="timeline-content">
      <ul>
        <li>Graduated with a <strong>B.Sc. in Electrical and Electronics Engineering</strong> from the Islamic University of Technology (IUT).</li>
      </ul>
    </div>
  </div>

</div>