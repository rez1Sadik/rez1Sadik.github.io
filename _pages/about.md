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
    font-size: .9em; 
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
    font-size: 0.9em; 
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
      font-size: 0.8em;
    }
    .research-text {
      font-size: 0.8em;
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
  I am a Data Manager at the South Dakota Department of Education, where I leverage data analytics to drive evidence-based educational strategies. My academic foundation comprises an M.Sc. in Business Analytics from the University of South Dakota, an M.B.A. in Marketing from the IBA, University of Dhaka and a B.Sc. in Electrical and Electronics Engineering from the Islamic University of Technology. Bridging the gap between industry and academia, my professional background encompasses extensive data-driven roles and teaching experience, including serving as an Adjunct Lecturer at USD's Beacom School of Business.
</div>

<div class="bio-text">
  As an active researcher, my work explores the applied intersections of Machine Learning and Deep Learning with a primary focus on Natural Language Processing (NLP). I am dedicated to developing and optimizing intelligent computational models to address complex, real-world challenges, ranging from sentiment analysis and fake news detection to predictive healthcare modeling. My collaborative research has been featured in reputable peer-reviewed journals and international conferences, including <strong>ICTCS</strong>, <strong>SASI-ITE</strong>, and <strong>ICSSES</strong>.
</div>


<p style="color: #d92121; text-align: justify; font-size: .85em; font-weight: 500; margin-bottom: 40px; line-height: 1.5;">
  I am actively seeking collaborative research opportunities to contribute to the world of data.
</p>


<h2 style="margin-top: 0; border-bottom: 1px solid #eee; text-transform: uppercase; padding-bottom: 10px; color: #333;">Research Interests</h2>

<div style="margin-bottom: 30px;">
  <p style="margin: 0; font-size: 0.9em; color: #444; font-weight: 500; letter-spacing: 0.5px;">
    Deep Learning <span style="color: #aaa; margin: 0 10px;">|</span> 
    NLP <span style="color: #aaa; margin: 0 10px;">|</span> 
    LLM <span style="color: #aaa; margin: 0 10px;">|</span> 
    Image Processing
  </p>
</div>



<h2 style="margin-top: 40px; border-bottom: 1px solid #eee; text-transform: uppercase; padding-bottom: 10px; color: #333;">Recent News</h2>

<div class="news-scroll-container" style="max-height: 500px; overflow-y: auto; padding-right: 15px; margin-top: 20px;">
  
  <div class="timeline-item">
    <div class="timeline-date">Jan 2025</div>
    <div class="timeline-content">
      <ul>
        Paper titled <strong>"Aspect-Based Sentiment Analysis of Amazon Product Reviews"</strong> accepted at the 2025 International Conference on New Trends In Computing Sciences (ICTCS).
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2024</div>
    <div class="timeline-content">
      <ul>
        Published journal articles on Sentiment Analysis and Fake News Detection in the <em>Journal of Computer and Communications</em> and <em>arXiv</em>.
        <br><br>
        Presented and published multiple papers at international conferences including <strong>SASI-ITE</strong>, <strong>ICDSIS</strong>, <strong>AISP</strong>, and <strong>ICSSES</strong>.
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Aug 2023</div>
    <div class="timeline-content">
      <ul>
        Joined the <strong>Department of Education, State of South Dakota</strong> as Data Manager.
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">May 2023</div>
    <div class="timeline-content">
      <ul>
        Joined the <strong>Center for Teaching & Learning, University of South Dakota</strong> as Data Analyst.
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Apr 2023</div>
    <div class="timeline-content">
      <ul>
        Published research at <strong>INCOFT</strong> and <strong>ISBM</strong>, and authored a book chapter in the <em>Encyclopedia of Heroism Studies</em>.
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Mar 2023</div>
    <div class="timeline-content">
      <ul>
        Inducted into the <strong>Beta Gamma Sigma Honor Society</strong> for academic excellence.
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Jan 2023</div>
    <div class="timeline-content">
      <ul>
        Started serving as an <strong>Adjunct Lecturer</strong> at the Beacom School of Business, University of South Dakota.
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Dec 2022</div>
    <div class="timeline-content">
      <ul>
        Graduated with an <strong>M.Sc. in Business Analytics</strong> (CGPA: 4.0) from the University of South Dakota.
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Apr 2022</div>
    <div class="timeline-content">
      <ul>
        Received the <strong>Leonard E. Arnaud memorial Award & Scholarship</strong> for leadership and extracurricular achievements.
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Aug 2021</div>
    <div class="timeline-content">
      <ul>
        Joined the Beacom School of Business, University of South Dakota as a <strong>Graduate Research Assistant</strong>.
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Apr 2021</div>
    <div class="timeline-content">
      <ul>
        Graduated with a <strong>M.B.A in Marketing</strong> from the IBA, University of Dhaka, Bangladesh.
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Jan 2021</div>
    <div class="timeline-content">
      <ul>
        Joined <strong>Millennium Information Solution Limited</strong>, Bangladesh as Business Analyst.
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Nov 2020</div>
    <div class="timeline-content">
      <ul>
        Joined <strong>iDE</strong>, Bangladesh as Data Analyst Intern.
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Jan 2019</div>
    <div class="timeline-content">
      <ul>
        Joined batch 61D of IBA, University of Dhaka, Bangladesh pursuing <strong>M.B.A. in Marketing</strong>.
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">May 2017</div>
    <div class="timeline-content">
      <ul>
        Joined <strong>LG</strong>, Bangladesh as Quality Assurance Engineer.
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Jan 2016</div>
    <div class="timeline-content">
      <ul>
        Joined <strong>Walton TV R&D</strong>, Bangladesh as Assistant Engineer.
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Jan 2015</div>
    <div class="timeline-content">
      <ul>
        Joined <strong>Confidence Electic Limited</strong>, Bangladesh as Planning Engineer.
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Nov 2014</div>
    <div class="timeline-content">
      <ul>
        Graduated with a <strong>B.Sc. in EEE</strong> from the Islamic University of Technology, Bangladesh.
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Apr 2014</div>
    <div class="timeline-content">
      <ul>
        Secured <strong>2nd Runner-up</strong> position in the Business Case Study competition at Esonance 2014.
      </ul>
    </div>
  </div>

</div>