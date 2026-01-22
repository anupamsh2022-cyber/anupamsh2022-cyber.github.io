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

  /* 5. Research Cards */
  .research-card {
    background: #24283b;
    border: 1px solid #3d446d;
    padding: 20px;
    border-radius: 10px;
    margin-bottom: 20px;
  }
  .research-tag {
    color: #4da6ff;
    font-size: 0.8em;
    font-weight: bold;
    text-transform: uppercase;
    display: block;
    margin-bottom: 5px;
  }

  /* 6. Skills Grid */
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
    transition: 0.3s;
  }

  .skill-card:hover { border-color: #4da6ff; transform: translateY(-5px); }
  .skill-header { color: #4da6ff; font-weight: bold; margin-bottom: 10px; }
  .skill-list { list-style: none; padding: 0; font-size: 0.9em; color: #cbd5e0; }
  .skill-list li { margin-bottom: 5px; padding-left: 15px; position: relative; }
  .skill-list li::before { content: "▹"; position: absolute; left: 0; color: #4da6ff; }

  /* 7. Deep Pedagogy Section */
  .pedagogy-depth-box {
    background: linear-gradient(135deg, #1a1c2c 0%, #24283b 100%);
    border: 1px solid #3d446d;
    border-top: 4px solid #4da6ff;
    padding: 30px;
    border-radius: 12px;
    margin-bottom: 25px;
  }

  .philosophy-quote {
    font-size: 1.2em;
    font-style: italic;
    color: #82aaff;
    margin-bottom: 20px;
    display: block;
    line-height: 1.5;
  }

  .depth-tag {
    background: rgba(77, 166, 255, 0.1);
    border: 1px solid rgba(77, 166, 255, 0.3);
    color: #4da6ff;
    padding: 6px 15px;
    border-radius: 20px;
    font-size: 0.85em;
    font-weight: 500;
    display: inline-block;
    margin-right: 10px;
    margin-top: 10px;
  }

  /* 8. Course Portfolio */
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

  /* 9. Activities Grid */
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
  <a href="#teaching-portfolio">Teaching</a> <a href="#activities">Activities</a>
</div>

<div class="profile-container">
  <img src="profile.jpg" class="profile-img" alt="Anupam Sharma">
  <div>
    <h1 class="name-heading">Anupam Sharma</h1>
    <h3 style="margin:5px 0 15px 0; color:#4da6ff !important; font-weight:400;">Assistant Professor</h3>
    <div>
      <span class="tag-box">Chanakya University</span>
      <span class="tag-box">Bengaluru, India</span>
    </div>
  </div>
</div>

### 🔗 Connect 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anupam-s-energy) 
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=qLdXot0AAAAJ&hl=en) 
[![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?style=for-the-badge&logo=ResearchGate&logoColor=white)](https://www.researchgate.net/profile/Anupam-S)

I am an Energy Engineer and Researcher dedicated to the harmony of complex systems. My work exists at the intersection of **Power Systems and Cybersecurity**, where I explore the mathematical and philosophical foundations of resilience. I believe that a truly "smart" grid must not only be efficient but also robust enough to withstand the unpredictable challenges of a digital age. Beyond the circuits, I am deeply interested in how human consciousness and psychological patterns influence our interaction with technology and education.

<hr>

<h2 id="research">🔬 Research Projects</h2>

<div class="research-card">
  <span class="research-tag">Cyber-Physical Security</span>
  <h3 style="margin:0 0 10px 0; color:#fff !important;">Smart Grid Resilience with Artificial Intelligence</h3>
  <p style="font-size:0.95em; color:#cbd5e0; margin:0;">
    Developing advanced frameworks to detect and mitigate <b>False Data Injection Attacks (FDIA)</b> in renewable-heavy energy systems. By combining machine learning with power system physics, I aim to create "self-healing" grids that maintain integrity even under sophisticated cyber-physical threats.
  </p>
</div>

<div class="research-card">
  <span class="research-tag">Interdisciplinary Systems</span>
  <h3 style="margin:0 0 10px 0; color:#fff !important;">Cognitive Frameworks for Engineering Ethics</h3>
  <p style="font-size:0.95em; color:#cbd5e0; margin:0;">
    An exploratory study into how the <b>Philosophy of Consciousness</b> and cognitive psychology can be used to model ethical decision-making in autonomous energy management systems. This project bridges the gap between technical reliability and human-centric values.
  </p>
</div>

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

<div class="pedagogy-depth-box">
  <span class="philosophy-quote">
    "Education is not the filling of a pail, but the lighting of a fire—a fire that must illuminate both the circuit and the soul."
  </span>
  
  <div class="pedagogy-manifesto" style="line-height: 1.8; font-size: 1.05em; color: #cbd5e0;">
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

<h2 id="teaching-portfolio">📚 Teaching Portfolio</h2>

<style>
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
    border-left: 2px solid #3d446d; /* Added a vertical line for better structure */
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
  .course-item-container {
    margin-bottom: 30px;
  }
</style>

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
      <a href="https://drive.google.com/file/d/1gno0vbTaHJ9TO_xrS9dujNnhCGPwxVYW/view?usp=sharing" class="resource-link">Lecture 1 (Energy scenario in KARNATAKA) Handout</a>
      <a href="https://drive.google.com/file/d/1qqxNkeUaeQMwT8CTcod_krdLyCIFLo1E/view?usp=sharing" class="resource-link">Lecture 2 (Energy scenario in INDIA) Handout</a>
      <a href="https://drive.google.com/file/d/1hUTMhjqRDcAgFi0Ujqo4jI5fiQBdHPfL/view?usp=sharing" class="resource-link" style="border-color: #ff4d4d; color: #ff4d4d !important;">📝 Quiz 1 Paper</a>
    </div>
  </div>

  <div class="project-box" style="border-left: 2px solid #00ffcc; background: rgba(0, 255, 204, 0.05); padding: 20px; border-radius: 0 10px 10px 0; margin-top: 20px;">
  <span class="project-title" style="color: #00ffcc; font-weight: 700; letter-spacing: 1px;">🔬 POWER & ENERGY RESEARCH GROUP</span>
  <p style="font-size: 0.85em; color: #cbd5e0; margin: 10px 0 20px 0; line-height: 1.6;">
    Supervising advanced research in sustainable grid architectures and system resilience.
  </p>
  
  <table style="width: 100%; font-size: 0.9em; border-collapse: collapse; color: #ffffff;">
    <thead>
      <tr style="text-align: left; background: rgba(0, 255, 204, 0.15);">
        <th style="padding: 12px; color: #00ffcc; border-bottom: 2px solid #00ffcc;">Group Member</th>
        <th style="padding: 12px; color: #00ffcc; border-bottom: 2px solid #00ffcc;">Research Project Title</th>
      </tr>
    </thead>
    <tbody>
      <tr style="border-bottom: 1px solid #3d446d; transition: 0.3s;" onmouseover="this.style.backgroundColor='rgba(255,255,255,0.05)'" onmouseout="this.style.backgroundColor='transparent'">
        <td style="padding: 15px 12px; font-weight: 600;">Monish Y</td>
        <td style="padding: 15px 12px; color: #cbd5e0; font-style: italic;">"132/33kV Substation Design with Protection Schemes."</td>
      </tr>
      <tr style="border-bottom: 1px solid #3d446d; transition: 0.3s;" onmouseover="this.style.backgroundColor='rgba(255,255,255,0.05)'" onmouseout="this.style.backgroundColor='transparent'">
        <td style="padding: 15px 12px; font-weight: 600;">Supriya A Mahajan, Manikanta RA, Shrusti J </td>
        <td style="padding: 15px 12px; color: #cbd5e0; font-style: italic;">"Block Chain Peer-to-Peer Energy Trading in Prosumer Centric Society"</td>
      </tr>
    </tbody>
  </table>
</div>

  
</li>
      
      <li class="course-item-container">
        <span class="course-tag">EVE 208</span> <b>Analog Systems</b>
        <div class="project-box" style="border-left-color: #4da6ff;">
    <span class="project-title">📚 Active Course Resources</span>
      
    <div style="display: flex; flex-wrap: wrap; gap: 5px;">
      
      <a href="https://drive.google.com/file/d/1MZ_lKUCFu9hK0UXtzVeF-f8u_jf7X7Ap/view?usp=sharing" class="resource-link" style="border-color: #ff4d4d; color: #ff4d4d !important;">📝 Quiz 1 Paper</a>
    </div>
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
        
        <div class="project-box" style="border-left-color: #4da6ff;">
          <span class="project-title">📑 Course Handouts</span>
          <a href="https://drive.google.com/file/d/1pPQ9Hb1LsV7vNUL05UflZ9BNbnYdtAfr/view?usp=sharing" class="resource-link">Module 1</a>
          <a href="https://drive.google.com/file/d/1I9osa5VRPm9-WgI5XPhP49ZDCP6l6H8v/view?usp=sharing" class="resource-link">Module 2</a>
          <a href="https://drive.google.com/file/d/1RENXKVLqOhgRMB2gaKYpaA43gADfv1PO/view?usp=sharing" class="resource-link">Module 3</a>
          <a href="https://drive.google.com/file/d/1hkcCUNMupXrSfPFgP4GpyfXC8_2ZCsqj/view?usp=sharing" class="resource-link">Module 4</a>
        </div>

        <div class="project-box" style="border-left-color: #3d446d;">
          <span class="project-title">📝 Practice & Assessment</span>
          <a href="https://drive.google.com/file/d/1FUlFmL2o6mHJBfdZJWqzAnYAsDVGQE4G/view?usp=sharing" class="resource-link">Tutesheet 1</a>
          <a href="https://drive.google.com/file/d/1pUFKXvwGb_xbJPpaRBo48DtKUZ-hG-dV/view?usp=sharing" class="resource-link">Tutesheet 2</a>
          <a href="https://drive.google.com/file/d/1A1GTUVFAz75ApxzmyMeI3LZcZj0SQKSL/view?usp=sharing" class="resource-link" style="border-color: #ff4d4d; color: #ff4d4d !important;">Mid-Sem Paper</a>
          <a href="https://drive.google.com/file/d/1arKXuai_l1WCrmfcECOg51B_pGMzwhaA/view?usp=sharing" class="resource-link" style="border-color: #ff4d4d; color: #ff4d4d !important;">End-Sem Paper</a>
        </div>

        <div class="project-box" style="border-left-color: #ffd700; background: rgba(255, 215, 0, 0.03); padding-bottom: 15px; border-radius: 0 8px 8px 0;">
          <span class="project-title" style="color: #ffd700;">🚀 Student Innovation Showcase</span>
          <p style="font-size: 0.85em; color: #cbd5e0; margin: 10px 0; line-height: 1.6;">
            Mentored <b>42 students</b> in mathematical modeling applications.
          </p>
          <a href="https://drive.google.com/drive/folders/1m40JeT4f-BFwqWuPyEwQs3OP4uCZjTQL?usp=sharing" class="resource-link" style="border-color: #ffd700; color: #ffd700 !important; font-weight: bold; padding: 8px 16px;">
            📂 View All 42 Reports
          </a>
          <div style="margin-top: 12px;">
             <a href="https://drive.google.com/file/d/1gLUrvtWevzw-nzK8IwwdEvq6kv4dBRQW/view?usp=sharing" class="resource-link" style="font-size: 0.75em; opacity: 0.9;">🌟 Featured: 3D Rocket Dynamics</a>
             <a href="https://drive.google.com/file/d/1k_AZxUBp_vlZCZJHkYD8pZTI6_oI8IPV/view?usp=sharing" class="resource-link" style="font-size: 0.75em; opacity: 0.9;">🌟 Featured: Quarter Car Suspension</a>
          </div>
        </div>
      </li>

      <li class="course-item-container" style="border-top: 1px solid #3d446d; padding-top: 25px; margin-top: 30px;">
  <span class="course-tag">EVE 201</span> <b style="font-size: 1.1em;">Electrical Circuits & Networks</b>
  
  <div class="project-box" style="border-left-color: #4da6ff;">
    <span class="project-title">📑 Course Resources</span>
    <a href="https://drive.google.com/file/d/1icZUJseGWW1wIHXJJv1brDBUDAeeJrs-/view?usp=sharing" class="resource-link">Lab Manual</a>
    <a href="https://drive.google.com/file/d/15YuIidPokCKyR7rnbDjcm6wmNagPdIQe/view?usp=sharing" class="resource-link">Lab Videos</a>
  </div>

  <div class="project-box" style="border-left-color: #ff4d4d; margin-top: 10px;">
    <span class="project-title" style="color: #ff4d4d;">🎯 Assessment Archive</span>
    <a href="https://drive.google.com/file/d/1ANuHKQUO-MUd4oOLY_2HwB_I3d2wlT4y/view?usp=sharing" class="resource-link" style="border-color: #ff4d4d; color: #ff4d4d !important;">Mid-Sem Paper</a>
    <a href="https://drive.google.com/file/d/1iAmq5YH-mwjNZko_6nzF6kKj_W3q9cj6/view?usp=sharing" class="resource-link" style="border-color: #ff4d4d; color: #ff4d4d !important;">End-Sem Paper</a>
  </div>

  <div class="project-box" style="border-left-color: #ffd700; background: rgba(255, 215, 0, 0.03); padding-bottom: 15px; border-radius: 0 8px 8px 0;">
    <span class="project-title" style="color: #ffd700;">🚀 Student Innovation Projects</span>
    <div style="display: flex; flex-wrap: wrap; gap: 8px;">
      <a href="https://drive.google.com/file/d/1qDMkhz9DzY9TZ2p1jgd1VGzZ9G2f7Huv/view?usp=sharing" class="resource-link" style="border-color: #ffd700; color: #ffd700 !important;">📁 Incandescent Bulb</a>
      
    </div>
  </div>
</li>

    </ul>
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

<div style="text-align: center; padding: 100px 20px 60px 20px; max-width: 800px; margin: 0 auto;">
  
  <div style="color: #4da6ff; font-size: 1.5em; letter-spacing: 15px; margin-bottom: 40px; opacity: 0.6;">
    ✦ ✦ ✦
  </div>
  
  <p style="font-style: italic; color: #cbd5e0; line-height: 1.9; font-size: 1.15em; margin-bottom: 30px;">
    "In the grid, as in life, resilience is not just about resisting the storm, but about having the internal architecture to keep the light burning when the world goes dark. Whether I am securing a power system or mentoring a student, my goal remains the same: to build systems—and souls—that are unbreakable."
  </p>
  
  <div style="color: #ffffff; font-weight: 700; letter-spacing: 5px; font-size: 0.75em; text-transform: uppercase; opacity: 0.7;">
    Anupam Sharma
  </div>
</div>

