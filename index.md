---
layout: default
title: Anupam Sharma
---

<style>
  /* 1. Universal Theme & Layout */
  body, .main-content, header { 
    background-color: #1a1c2c !important;
    color: #ffffff !important;
  }

  /* 2. Sticky Navbar */
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

  .navbar a:hover { color: #4da6ff !important; }

  /* 3. Global Section Styling */
  h2 { 
    color: #4da6ff !important; 
    border-bottom: none !important; 
    scroll-margin-top: 100px; 
    margin-top: 45px;
  }

  .tag-box {
    background-color: #24283b !important;
    border: 1px solid #3d446d !important;
    padding: 5px 12px;
    border-radius: 4px;
    font-size: 0.9em;
    margin-right: 5px;
  }

  /* 4. Profile Section */
  .profile-container {
    display: flex;
    align-items: center;
    gap: 25px;
    flex-wrap: wrap;
    margin-bottom: 20px;
  }

  .profile-img {
    width: 150px !important;
    height: auto;
    border-radius: 12px;
    border: 2px solid #4da6ff;
    object-fit: cover;
  }

  /* 5. Skills Grid */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;
  }

  .skill-card {
    background-color: #24283b;
    border: 1px solid #3d446d;
    padding: 20px;
    border-radius: 10px;
    transition: 0.3s;
  }

  .skill-card:hover { border-color: #4da6ff; transform: translateY(-5px); }
  .skill-header { color: #4da6ff; font-weight: bold; margin-bottom: 10px; }
  .skill-list { list-style: none; padding: 0; font-size: 0.9em; color: #cbd5e0; }
  .skill-list li { margin-bottom: 5px; padding-left: 15px; position: relative; }
  .skill-list li::before { content: "▹"; position: absolute; left: 0; color: #4da6ff; }

  /* 6. Pedagogy & Portfolio */
  .pedagogy-highlight {
    background: linear-gradient(135deg, #24283b 0%, #1a1c2c 100%);
    border-left: 5px solid #4da6ff;
    padding: 25px;
    border-radius: 10px;
    margin-bottom: 20px;
    border: 1px solid #3d446d;
  }

  .framework-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 15px;
    margin-bottom: 10px;
  }

  .framework-pill {
    background: #24283b;
    border: 1px solid #4da6ff;
    padding: 12px;
    border-radius: 50px;
    text-align: center;
    font-size: 0.85em;
    font-weight: 600;
  }

  .course-container { display: flex; flex-wrap: wrap; gap: 15px; margin-top: 15px; }

  .semester-box {
    flex: 1;
    min-width: 300px;
    background-color: #24283b;
    border: 1px solid #3d446d;
    padding: 15px;
    border-radius: 10px;
  }

  .course-tag {
    display: inline-block;
    background: #1a1c2c;
    border: 1px solid #4da6ff;
    padding: 2px 8px;
    border-radius: 4px;
    font-size: 0.8em;
    margin-right: 5px;
  }

  /* 7. Activities Grid */
  .activity-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 25px;
    margin-top: 20px;
  }

  .activity-img-standard {
    width: 100%;
    height: 250px;
    object-fit: contain;
    background-color: #1a1c2c;
    border-radius: 8px;
    border: 1px solid #3d446d;
    transition: 0.3s;
  }

  .activity-img-standard:hover { border-color: #4da6ff; transform: scale(1.02); }
  .activity-desc { margin-top: 12px; font-size: 0.85em; font-style: italic; color: #cbd5e0; }
</style>

<div class="navbar">
  <a href="#research">Research</a>
  <a href="#skills">Skills</a>
  <a href="#pedagogy">Pedagogy</a>
  <a href="#activities">Activities</a>
</div>

<div class="profile-container">
  <img src="profile.jpg" class="profile-img" alt="Anupam Sharma">
  <div>
    <h2 style="margin:0;">Assistant Professor</h2>
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

<hr>

<h2 id="research">🔬 Research Projects</h2>
* **Smart Grid Resilience with AI:** Developing frameworks to detect and mitigate false data injection in renewable energy systems.

<h2 id="skills">🛠️ Interdisciplinary Expertise</h2>
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

<h2 id="pedagogy">📖 Pedagogy</h2>

<style>
  .pedagogy-depth-box {
    background: linear-gradient(135deg, #1a1c2c 0%, #24283b 100%);
    border: 1px solid #3d446d;
    border-top: 4px solid #4da6ff;
    padding: 30px;
    border-radius: 12px;
    margin-bottom: 25px;
    position: relative;
    overflow: hidden;
  }

  .philosophy-quote {
    font-size: 1.2em;
    font-style: italic;
    color: #82aaff;
    margin-bottom: 20px;
    display: block;
    line-height: 1.5;
  }

  .pedagogy-manifesto {
    line-height: 1.8;
    font-size: 1.05em;
    color: #cbd5e0;
  }

  .depth-keywords {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 25px;
  }

  .depth-tag {
    background: rgba(77, 166, 255, 0.1);
    border: 1px solid rgba(77, 166, 255, 0.3);
    color: #4da6ff;
    padding: 6px 15px;
    border-radius: 20px;
    font-size: 0.85em;
    font-weight: 500;
  }
</style>

<div class="pedagogy-depth-box">
  <span class="philosophy-quote">
    "Education is not the filling of a pail, but the lighting of a fire—a fire that must illuminate both the circuit and the soul."
  </span>
  
  <div class="pedagogy-manifesto">
    My practice of <b>Interdisciplinary Pedagogy</b> is rooted in the belief that technical systems are reflections of human logic and universal order. I bridge <b>Mathematical Rigor</b> with <b>Cognitive Psychology</b> to guide students beyond rote memorization into the realm of 'Deep Understanding.' 
    <br><br>
    I view the classroom as a space for <b>Holistic Mentoring</b>, where we don't just solve for variables, but cultivate the resilience and philosophical clarity required to navigate the complexities of life and technology alike.
  </div>

  <div class="depth-keywords">
    <span class="depth-tag">✧ Existential Clarity</span>
    <span class="depth-tag">✧ Cognitive Scaffolding</span>
    <span class="depth-tag">✧ Ethical Engineering</span>
    <span class="depth-tag">✧ Conscious Mentorship</span>
  </div>
</div>

<h2 id="activities">🤝 Professional Activities</h2>
<div class="activity-grid">
  <div class="activity-item">
    <img src="Y_HR3985.JPG" class="activity-img-standard" alt="Counselling Cell">
    <div class="activity-desc">Inauguration of the Counselling Cell at Chanakya University with Dr. Amey Agharkar.</div>
  </div>
  <div class="activity-item">
    <img src="UGC.png" class="activity-img-standard" alt="Goa University FDP">
    <div class="activity-desc">124th Guru Dakshata (Online) Faculty Induction Program at Goa University.</div>
  </div>
  <div class="activity-item">
    <img src="Neurocon.jpg" class="activity-img-standard" alt="NeuroConsciousness">
    <div class="activity-desc">Engaging with Prof. CA Tomy (UoH) during NeuroConsciousness Workshop at IISc.</div>
  </div>
  <div class="activity-item">
    <img src="Ganesha.jpg" class="activity-img-standard" alt="IISc Festival">
    <div class="activity-desc">Engaging with Scholars and Masters Students at IISc during Ganesh Chaturthi.</div>
  </div>
  <div class="activity-item">
    <img src="SIP.jpg" class="activity-img-standard" alt="Student Induction">
    <div class="activity-desc">During Student Induction Program at Chanakya University with Prof. Akhila.</div>
  </div>
  <div class="activity-item">
    <img src="Lovish.jpg" class="activity-img-standard" alt="Manotsava">
    <div class="activity-desc">Engaging with Lovish Raheja (IIT Bombay-Monash) during Manotsava 2025.</div>
  </div>
</div>
