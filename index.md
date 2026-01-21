---
layout: default
title: Anupam Sharma
---

<style>
  /* 1. Universal Theme Colors */
  body, .main-content, header { 
    background-color: #1a1c2c !important;
    color: #ffffff !important;
  }

  /* 2. Sticky Navbar Styling */
  .navbar {
    position: -webkit-sticky;
    position: sticky;
    top: 0;
    background-color: #24283b;
    padding: 15px 0;
    z-index: 9999;
    border-bottom: 2px solid #4da6ff;
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-bottom: 30px;
  }

  .navbar a {
    color: #ffffff !important;
    font-weight: 600;
    font-size: 0.85em;
    text-decoration: none;
    text-transform: uppercase;
    letter-spacing: 1px;
    transition: 0.3s;
  }

  .navbar a:hover {
    color: #4da6ff !important;
  }

  /* 3. Profile Header Fix (Removes White Space) */
  .profile-container {
    display: flex;
    align-items: center;
    gap: 25px;
    flex-wrap: wrap;
    margin-bottom: 20px;
  }

  .profile-img {
    width: 150px !important; /* Reduced professional size */
    height: auto;
    border-radius: 12px;
    border: 2px solid #4da6ff;
    object-fit: cover !important; /* Crops internal white space */
    background-color: transparent !important;
  }

  /* 4. General Formatting */
  h2, h3 { 
    color: #4da6ff !important; 
    border-bottom: none !important; 
    scroll-margin-top: 80px; /* Prevents text from hiding under navbar */
  }
  
  .tag-box {
    background-color: #24283b !important;
    border: 1px solid #3d446d !important;
    padding: 5px 12px;
    border-radius: 4px;
    font-size: 0.9em;
  }

  a { color: #82aaff !important; text-decoration: none; }
  hr { border: 0; border-top: 1px solid #3d446d; margin: 25px 0; }
  
  /* Styling for the Activity Image */
  .activity-img {
    max-width: 100%;
    border-radius: 8px;
    border: 1px solid #3d446d;
    margin-top: 10px;
  }
</style>

<div class="navbar">
  <a href="#research">Research</a>
  <a href="#skills">Skills</a>
  <a href="#teaching">Teaching</a>
  <a href="#activities">Activities</a>
</div>

<div class="profile-container">
  <img src="profile.jpg" class="profile-img" alt="Anupam Sharma">
  <div>
    <h2 style="margin:0; border:none !important;">Assistant Professor</h2>
    <div style="margin-top:10px;">
      <span class="tag-box">Chanakya University</span>
      <span class="tag-box">Bengaluru, India</span>
    </div>
  </div>
</div>

### 🔗 Connect 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anupam-s-energy) 
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=qLdXot0AAAAJ&hl=en) 
[![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?style=for-the-badge&logo=ResearchGate&logoColor=white)](https://www.researchgate.net/profile/Anupam-S)

I am an Energy Engineer pursuing research at the intersection of **Power Systems and Cybersecurity**. My work focuses on making renewable energy grids more resilient against cyber-physical threats.

---

<h2 id="research">🔬 Research Projects</h2>
* **Smart Grid Resilience with AI:** Developing frameworks to detect and mitigate false data injection in renewable energy systems.

<h2 id="skills">🛠️ Interdisciplinary Expertise</h2>

<style>
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;
    margin-top: 20px;
  }

  .skill-card {
    background-color: #24283b;
    border: 1px solid #3d446d;
    padding: 15px;
    border-radius: 10px;
    transition: 0.3s;
  }

  .skill-card:hover {
    border-color: #4da6ff;
    transform: translateY(-5px);
  }

  .skill-header {
    color: #4da6ff;
    font-weight: bold;
    font-size: 1.1em;
    margin-bottom: 10px;
    display: flex;
    align-items: center;
    gap: 10px;
  }

  .skill-list {
    list-style: none;
    padding: 0;
    margin: 0;
    font-size: 0.9em;
    color: #cbd5e0;
  }

  .skill-list li {
    margin-bottom: 5px;
    padding-left: 15px;
    position: relative;
  }

  .skill-list li::before {
    content: "▹";
    position: absolute;
    left: 0;
    color: #4da6ff;
  }
</style>

<div class="skills-grid">
  <div class="skill-card">
    <div class="skill-header">⚡ Electrical Engineering</div>
    <ul class="skill-list">
      <li>Power Systems Analysis</li>
      <li>Smart Grid Resilience</li>
      <li>Renewable Energy Integration</li>
      <li>Software: SAM, SOLTRACE</li>
    </ul>
  </div>

  <div class="skill-card">
    <div class="skill-header">🔢 Mathematical Sciences</div>
    <ul class="skill-list">
      <li>Engineering Mathematics</li>
      <li>Cyber-Physical Modeling</li>
      <li>Python-based Visualization</li>
      <li>Statistical Analysis</li>
    </ul>
  </div>

  <div class="skill-card">
    <div class="skill-header">🧠 Humanities & Social Sciences</div>
    <ul class="skill-list">
      <li>Philosophy of Consciousness</li>
      <li>Educational Psychology</li>
      <li>Student-Centric Mentoring</li>
      <li>Interdisciplinary Pedagogy</li>
    </ul>
  </div>
</div>


<h2 id="teaching">📖 Pedagogy</h2>

<style>
  .pedagogy-wrapper {
    display: flex;
    flex-direction: column;
    gap: 20px;
    margin-bottom: 30px;
  }

  .philosophy-statement {
    background: linear-gradient(135deg, #24283b 0%, #1a1c2c 100%);
    border: 1px solid #3d446d;
    border-left: 5px solid #4da6ff;
    padding: 25px;
    border-radius: 8px;
  }

  .pedagogy-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
  }

  .method-box {
    background-color: #24283b;
    padding: 20px;
    border-radius: 10px;
    border: 1px solid #3d446d;
  }

  .method-box h3 {
    margin-top: 0;
    font-size: 1.1em;
    color: #4da6ff !important;
    display: flex;
    align-items: center;
    gap: 10px;
  }

  .course-tag {
    background: #1a1c2c;
    color: #4da6ff;
    padding: 2px 8px;
    border-radius: 4px;
    font-size: 0.8em;
    border: 1px solid #4da6ff;
    margin-right: 8px;
  }
</style>

<div class="pedagogy-wrapper">
  <div class="philosophy-statement">
    <p style="margin: 0; line-height: 1.7; font-size: 1.05em;">
      My <b>Interdisciplinary Pedagogy</b> bridges the gap between technical rigor and humanistic insight. By integrating <b>Mathematical Sciences</b> with <b>Cognitive Psychology</b>, I aim to create a learning environment where complex engineering concepts are simplified through logical scaffolding and student-centric mentoring.
    </p>
  </div>

  <div class="pedagogy-grid">
    <div class="method-box">
      <h3>🎯 Methodologies</h3>
      <ul style="padding-left: 18px; color: #cbd5e0; font-size: 0.95em; line-height: 1.6;">
        <li><b>Active Learning:</b> Engaging students via real-world power system simulations.</li>
        <li><b>Holistic Mentoring:</b> Supporting academic growth through the lens of educational psychology.</li>
        <li><b>Visualization:</b> Using Python and MATLAB to translate abstract equations into visual models.</li>
      </ul>
    </div>

    <div class="method-box">
      <h3>📚 Course Delivery</h3>
      <div style="margin-bottom: 15px;">
        <small style="color: #82aaff; text-transform: uppercase;">Current Semester</small>
        <div style="margin-top: 5px;">
          <div><span class="course-tag">CODE</span> <b>Course Name 1</b></div>
          <div style="margin-top:5px;"><span class="course-tag">CODE</span> <b>Course Name 2</b></div>
        </div>
      </div>
      <div>
        <small style="color: #82aaff; text-transform: uppercase;">Previous Semester</small>
        <div style="margin-top: 5px;">
          <div><span class="course-tag">EVE 201</span> <b>Electrical Circuits</b></div>
          <div style="margin-top:5px;"><span class="course-tag">EBS 105</span> <b>Eng. Mathematics III</b></div>
        </div>
      </div>
    </div>
  </div>
</div>


<style>
  .course-container {
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
    margin-bottom: 20px;
  }
  .semester-box {
    flex: 1;
    min-width: 300px;
    background-color: #24283b;
    border: 1px solid #3d446d;
    padding: 15px;
    border-radius: 10px;
  }
  .semester-title {
    color: #4da6ff;
    font-weight: bold;
    margin-bottom: 10px;
    border-bottom: 1px solid #3d446d;
    padding-bottom: 5px;
  }
  .course-tag {
    display: inline-block;
    background: #1a1c2c;
    border: 1px solid #4da6ff;
    color: #ffffff;
    padding: 2px 8px;
    border-radius: 4px;
    font-size: 0.8em;
    margin-right: 5px;
  }
</style>

<div class="course-container">
  <div class="semester-box">
    <div class="semester-title">Current Semester (Jan – May 2026)</div>
    <ul style="list-style: none; padding-left: 0;">
      <li style="margin-bottom: 10px;">
        <span class="course-tag">EEC 206</span> <b>Power & Energy Engineering </b>
      </li>
      <li>
        <span class="course-tag">EVE 208</span> <b>Analog Systems</b>
      </li>
    </ul>
  </div>

  <div class="semester-box">
    <div class="semester-title">Previous Semester (Aug – Dec 2025)</div>
    <ul style="list-style: none; padding-left: 0;">
      <li style="margin-bottom: 10px;">
        <span class="course-tag">EVE 201</span> <b>Electrical Circuits & Networks</b>
      </li>
      <li>
        <span class="course-tag">EBS 105</span> <b>Engineering Mathematics III</b>
      </li>
    </ul>
  </div>
</div>

<p style="font-size: 0.95em; color: #cbd5e0;">
  <b>Pedagogy:</b> Committed to active learning, student-centric mentoring, and developing Python-based interactive modules for mathematical visualization.
</p>

---

<h2 id="activities">🤝 Professional Activities</h2>

<style>
  /* Unified Grid for all activities and certificates */
  .activity-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 25px;
    margin-top: 20px;
  }

  .activity-item {
    display: flex;
    flex-direction: column;
  }

  /* Keeps all images sharp and exactly the same height */
  .activity-img-standard {
    width: 100%;
    height: 250px; /* Uniform height for a clean row look */
    object-fit: contain; 
    background-color: #1a1c2c;
    border-radius: 8px;
    border: 1px solid #3d446d;
    transition: transform 0.3s ease;
  }
  
  .activity-img-standard:hover {
    transform: scale(1.02);
    border-color: #4da6ff;
  }

  .activity-desc {
    margin-top: 12px;
    font-size: 0.85em;
    line-height: 1.5;
    font-style: italic;
    color: #cbd5e0;
  }
</style>

<div class="activity-grid">
  <div class="activity-item">
    <img src="Y_HR3985.JPG" class="activity-img-standard" alt="Counselling Cell">
    <div class="activity-desc">Engaging with Dr. Amey Agharkar during the inauguration of the Counselling Cell at Chanakya University.</div>
  </div>

  <div class="activity-item">
    <img src="UGC.png" class="activity-img-standard" alt="Goa University FDP">
    <div class="activity-desc">124th Guru Dakshata (Online) Faculty Induction Program at Goa University.</div>
  </div>

  <div class="activity-item">
    <img src="Neurocon.jpg" class="activity-img-standard" alt="NeuroConsciousness">
    <div class="activity-desc">Engaging with Prof. CA Tomy (University of Hyderabad) during NeuroConsciousness Workshop at IISc.</div>
  </div>

  <div class="activity-item">
    <img src="Ganesha.jpg" class="activity-img-standard" alt="IISc Festival">
    <div class="activity-desc">Engaging with Research Scholars and Masters Students at IISc during Ganesh Chaturthi Festival.</div>
  </div>

  <div class="activity-item">
    <img src="SIP.jpg" class="activity-img-standard" alt="Student Induction">
    <div class="activity-desc">During Student Induction Program at Chanakya University along with Prof. Akhila.</div>
  </div>

  <div class="activity-item">
    <img src="Lovish.jpg" class="activity-img-standard" alt="Manotsava">
    <div class="activity-desc">Engaging with Lovish Raheja (Doctoral student at IIT Bombay-Monash) during Manotsava 2025.</div>
  </div>
</div>


