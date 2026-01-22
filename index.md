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
    display: inline-flex;
    align-items: center;
    gap: 8px;
  }

  /* 4. Profile Section */
  .profile-container {
    display: flex;
    align-items: center;
    gap: 30px;
    flex-wrap: wrap;
    margin-bottom: 30px;
  }

  .profile-img {
    width: 160px !important;
    height: auto;
    border-radius: 12px;
    border: 2px solid #4da6ff;
    box-shadow: 0 10px 30px rgba(0,0,0,0.5);
  }

  .name-heading {
    font-size: 2.8em;
    font-weight: 800;
    margin: 0;
    color: #ffffff;
    letter-spacing: -1px;
  }

  /* 5. Resource Links & Boxes */
  .resource-link {
    display: inline-flex;
    align-items: center;
    background: rgba(77, 166, 255, 0.08);
    border: 1px solid rgba(77, 166, 255, 0.2);
    color: #4da6ff !important;
    padding: 6px 12px;
    border-radius: 6px;
    font-size: 0.85em;
    text-decoration: none;
    margin-top: 10px;
    transition: 0.3s;
    margin-right: 10px;
  }
  .resource-link:hover {
    background: rgba(77, 166, 255, 0.15);
    border-color: #4da6ff;
    transform: translateY(-2px);
  }
  .project-box {
    margin-top: 20px;
    padding-left: 15px;
    border-left: 2px solid #3d446d;
  }
  .project-title {
    font-size: 0.9em;
    font-weight: 600;
    color: #82aaff;
    display: block;
    margin-bottom: 8px;
    text-transform: uppercase;
    letter-spacing: 0.5px;
  }

  /* 6. Research Group Table */
  .research-table {
    width: 100%;
    font-size: 0.9em;
    border-collapse: collapse;
    color: #ffffff;
    margin-top: 15px;
  }
  .research-table th {
    text-align: left;
    background: rgba(0, 255, 204, 0.15);
    padding: 12px;
    color: #00ffcc;
    border-bottom: 2px solid #00ffcc;
  }
  .research-table td {
    padding: 15px 12px;
    border-bottom: 1px solid #3d446d;
  }

  /* 7. Skills & Portfolio Containers */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;
    margin-top: 20px;
  }
  .skill-card {
    background-color: #24283b;
    border: 1px solid #3d446d;
    padding: 20px;
    border-radius: 10px;
  }
  .course-container { display: flex; flex-wrap: wrap; gap: 15px; margin-top: 15px; }
  .semester-box {
    flex: 1;
    min-width: 300px;
    background-color: #24283b;
    border: 1px solid #3d446d;
    padding: 20px;
    border-radius: 10px;
  }
  .course-item-container { margin-bottom: 40px; }
</style>

<div class="navbar">
  <a href="#research">Research</a>
  <a href="#skills">Skills</a>
  <a href="#pedagogy">Pedagogy</a>
  <a href="#teaching-portfolio">Teaching</a> 
  <a href="#activities">Activities</a>
</div>

<div class="profile-container">
  <img src="profile.jpg" class="profile-img" alt="Anupam Sharma">
  <div>
    <h1 class="name-heading">Anupam Sharma</h1>
    <h3 style="margin:5px 0 15px 0; color:#4da6ff !important; font-weight:400;">Assistant Professor</h3>
    <div style="display: flex; gap: 10px; flex-wrap: wrap;">
      <span class="tag-box">
        <img src="logo_cu.png" alt="CU" style="height: 18px; width: auto;">
        Chanakya University
      </span>
      <span class="tag-box">Bengaluru, India</span>
    </div>
  </div>
</div>

### 🔗 Connect 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anupam-s-energy) 
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=qLdXot0AAAAJ&hl=en) 
[![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?style=for-the-badge&logo=ResearchGate&logoColor=white)](https://www.researchgate.net/profile/Anupam-S)

I am an Energy Engineer and Researcher dedicated to the harmony of complex systems. My work exists at the intersection of **Power Systems and Cybersecurity**, where I explore the mathematical and philosophical foundations of resilience. 

<hr>

<h2 id="research">🔬 Research Projects</h2>
<div class="research-card">
  <span class="research-tag">Cyber-Physical Security</span>
  <h3 style="margin:0 0 10px 0; color:#fff !important;">Smart Grid Resilience with Artificial Intelligence</h3>
  <p style="font-size:0.95em; color:#cbd5e0; margin:0;">
    Developing advanced frameworks to detect and mitigate <b>False Data Injection Attacks (FDIA)</b> in renewable-heavy energy systems.
  </p>
</div>

<h2 id="skills">🛠️ Interdisciplinary Expertise</h2>
<div class="skills-grid">
  <div class="skill-card">
    <div class="skill-header">⚡ Electrical Engineering</div>
    <ul class="skill-list" style="list-style: none; padding: 0; font-size: 0.9em; color: #cbd5e0;">
      <li>Power Systems Analysis</li>
      <li>Smart Grid Resilience</li>
      <li>Renewable Energy Integration</li>
    </ul>
  </div>
  <div class="skill-card">
    <div class="skill-header">🔢 Mathematical Sciences</div>
    <ul class="skill-list" style="list-style: none; padding: 0; font-size: 0.9em; color: #cbd5e0;">
      <li>Engineering Mathematics</li>
      <li>Cyber-Physical Modeling</li>
      <li>Python-based Visualization</li>
    </ul>
  </div>
</div>

<h2 id="pedagogy">📖 Pedagogy</h2>
<div class="pedagogy-depth-box">
  <span class="philosophy-quote">
    "Education is not the filling of a pail, but the lighting of a fire—a fire that must illuminate both the circuit and the soul."
  </span>
  <div style="line-height: 1.8; font-size: 1.05em; color: #cbd5e0;">
    My practice of <b>Interdisciplinary Pedagogy</b> bridges <b>Mathematical Rigor</b> with <b>Cognitive Psychology</b> to guide students into the realm of 'Deep Understanding.'
  </div>
</div>

<h2 id="teaching-portfolio">📚 Teaching Portfolio</h2>
<div class="course-container">
  
  <div class="semester-box">
    <div style="color:#4da6ff; font-weight:bold; margin-bottom:15px; font-size: 1.1em; border-bottom: 1px solid #3d446d; padding-bottom: 5px;">
      Current Semester (2026)
    </div>
    <ul style="list-style:none; padding:0;">
      
      <li class="course-item-container">
        <span class="course-tag">EEC 206</span> <b style="font-size: 1.1em;">Power & Energy Engineering</b>
        <div class="project-box" style="border-left-color: #4da6ff;">
          <span class="project-title">📚 Active Course Resources</span>
          <div style="display: flex; flex-wrap: wrap; gap: 5px;">
            <a href="https://drive.google.com/file/d/1gno0vbTaHJ9TO_xrS9dujNnhCGPwxVYW/view?usp=sharing" class="resource-link">Lecture 1 Handout (Karnataka)</a>
            <a href="https://drive.google.com/file/d/1qqxNkeUaeQMwT8CTcod_krdLyCIFLo1E/view?usp=sharing" class="resource-link">Lecture 2 Handout (India)</a>
            <a href="https://drive.google.com/file/d/1hUTMhjqRDcAgFi0Ujqo4jI5fiQBdHPfL/view?usp=sharing" class="resource-link" style="border-color: #ff4d4d; color: #ff4d4d !important;">📝 Quiz 1 Paper</a>
          </div>
        </div>

        <div class="project-box" style="border-left: 2px solid #00ffcc; background: rgba(0, 255, 204, 0.05); padding: 20px; border-radius: 0 10px 10px 0; margin-top: 20px;">
          <span class="project-title" style="color: #00ffcc; font-weight: 700; letter-spacing: 1px;">🔬 POWER & ENERGY RESEARCH GROUP (PERG)</span>
          <table class="research-table">
            <thead>
              <tr>
                <th>Group Member</th>
                <th>Research Project Title</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td><b>Monish Y</b></td>
                <td style="font-style: italic;">"132/33kV Substation Design with Protection Schemes."</td>
              </tr>
              <tr>
                <td><b>Supriya A M, Manikanta RA, Shrusti J</b></td>
                <td style="font-style: italic;">"Block Chain Peer-to-Peer Energy Trading in Prosumer Centric Society"</td>
              </tr>
            </tbody>
          </table>
        </div>
      </li>

      <li class="course-item-container">
        <span class="course-tag">EVE 208</span> <b style="font-size: 1.1em;">Analog Systems</b>
        <div class="project-box" style="border-left-color: #82aaff;">
          <span class="project-title">📑 Assessment</span>
          <a href="https://drive.google.com/file/d/1MZ_lKUCFu9hK0UXtzVeF-f8u_jf7X7Ap/view?usp=sharing" class="resource-link" style="border-color: #ff4d4d; color: #ff4d4d !important;">📝 Quiz 1 Paper</a>
        </div>
      </li>
    </ul>
  </div>

  <div class="semester-box">
    <div style="color:#4da6ff; font-weight:bold; margin-bottom:15px; font-size: 1.1em; border-bottom: 1px solid #3d446d; padding-bottom: 5px;">
      Previous Semester (2025)
    </div>
    <ul style="list-style:none; padding:0;">
      
      <li class="course-item-container">
        <span class="course-tag">EBS 105</span> <b style="font-size: 1.1em;">Engineering Mathematics III</b>
        <div class="project-box">
          <span class="project-title">📑 Course Handouts</span>
          <a href="https://drive.google.com/file/d/1pPQ9Hb1LsV7vNUL05UflZ9BNbnYdtAfr/view?usp=sharing" class="resource-link">Module 1</a>
          <a href="https://drive.google.com/file/d/1hkcCUNMupXrSfPFgP4GpyfXC8_2ZCsqj/view?usp=sharing" class="resource-link">Module 4</a>
          <a href="https://drive.google.com/file/d/1A1GTUVFAz75ApxzmyMeI3LZcZj0SQKSL/view?usp=sharing" class="resource-link" style="border-color: #ff4d4d; color: #ff4d4d !important;">Mid-Sem</a>
          <a href="https://drive.google.com/file/d/1arKXuai_l1WCrmfcECOg51B_pGMzwhaA/view?usp=sharing" class="resource-link" style="border-color: #ff4d4d; color: #ff4d4d !important;">End-Sem</a>
        </div>
        <div class="project-box" style="border-left-color: #ffd700; background: rgba(255, 215, 0, 0.03); padding-bottom: 15px;">
          <span class="project-title" style="color: #ffd700;">🚀 Student Innovation</span>
          <a href="https://drive.google.com/drive/folders/1m40JeT4f-BFwqWuPyEwQs3OP4uCZjTQL?usp=sharing" class="resource-link" style="border-color: #ffd700; color: #ffd700 !important; font-weight: bold;">📂 View 42 Reports</a>
        </div>
      </li>

      <li class="course-item-container" style="border-top: 1px solid #3d446d; padding-top: 25px;">
        <span class="course-tag">EVE 201</span> <b style="font-size: 1.1em;">Electrical Circuits & Networks</b>
        <div class="project-box" style="border-left-color: #4da6ff;">
          <span class="project-title">📑 Course Resources</span>
          <a href="https://drive.google.com/file/d/1MpNvY-1dcJMheWKnCUxPPhLf4ogVZvuH/view?usp=sharing" class="resource-link">Lab Manual</a>
          <a href="https://drive.google.com/file/d/15YuIidPokCKyR7rnbDjcm6wmNagPdIQe/view?usp=sharing" class="resource-link">Lab Videos</a>
        </div>
        <div class="project-box" style="border-left-color: #ff4d4d;">
          <span class="project-title" style="color: #ff4d4d;">🎯 Assessment Archive</span>
          <a href="https://drive.google.com/file/d/1ANuHKQUO-MUd4oOLY_2HwB_I3d2wlT4y/view?usp=sharing" class="resource-link" style="border-color: #ff4d4d; color: #ff4d4d !important;">Mid-Sem</a>
          <a href="https://drive.google.com/file/d/1iAmq5YH-mwjNZko_6nzF6kKj_W3q9cj6/view?usp=sharing" class="resource-link" style="border-color: #ff4d4d; color: #ff4d4d !important;">End-Sem</a>
        </div>
      </li>
    </ul>
  </div>
</div>

<h2 id="activities">🤝 Professional Activities</h2>
<div class="activity-grid">
  <div class="activity-item">
    <img src="Y_HR3985.JPG" class="activity-img-standard" alt="Counselling Cell">
    <div class="activity-desc">Inauguration of the Counselling Cell at Chanakya University.</div>
  </div>
  <div class="activity-item">
    <img src="UGC.png" class="activity-img-standard" alt="Goa University FDP">
    <div class="activity-desc">124th Guru Dakshata FDP at Goa University.</div>
  </div>
  <div class="activity-item">
    <img src="Neurocon.jpg" class="activity-img-standard" alt="NeuroConsciousness">
    <div class="activity-desc">NeuroConsciousness Workshop at IISc.</div>
  </div>
</div>

<div style="text-align: center; padding: 100px 20px 60px 20px; max-width: 800px; margin: 0 auto;">
  <div style="color: #4da6ff; font-size: 1.5em; letter-spacing: 15px; margin-bottom: 40px; opacity: 0.6;">✦ ✦ ✦</div>
  <p style="font-style: italic; color: #cbd5e0; line-height: 1.9; font-size: 1.15em; margin-bottom: 30px;">
    "In the grid, as in life, resilience is not just about resisting the storm, but about having the internal architecture to keep the light burning when the world goes dark."
  </p>
  <div style="color: #ffffff; font-weight: 700; letter-spacing: 5px; font-size: 0.75em; text-transform: uppercase; opacity: 0.7;">Anupam Sharma</div>
</div>
