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

<h2 id="skills">🛠️ Skills</h2>
* **Energy Modeling:** SAM, SOLTRACE, MATLAB.
* **Cybersecurity:** Network Security, Python (Scikit-learn).

<h2 id="teaching">📖 Teaching Portfolio</h2>
* **Courses Taught:** Electrical Circuits & Networks [EVE 201], Engineering Mathematics III [EBS 105].
* **Pedagogy:** Committed to active learning and student-centric mentoring.

---

<h2 id="activities">🤝 Professional Activities</h2>

<h2 id="activities">🤝 Professional Activities</h2>

<style>
  /* Container for the images */
  .activity-flex-container {
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
    justify-content: flex-start;
    margin-top: 20px;
  }

  /* Professional Card styling */
  .activity-item {
    flex: 1;
    min-width: 350px; /* Ensures they don't get too small and blurry */
    max-width: 48%;   /* Keeps them side-by-side on desktop */
  }

  /* High Quality Image Settings */
  .high-quality-img {
    width: 100%;      /* Fills the container width */
    height: auto;     /* Keeps original aspect ratio (No cropping) */
    display: block;
    border-radius: 10px;
    border: 1px solid #3d446d;
    /* Removed object-fit to prevent quality loss from zooming */
    image-rendering: -webkit-optimize-contrast; /* Sharper rendering for some browsers */
  }

  .activity-text {
    font-size: 0.95em;
    margin-top: 15px;
    line-height: 1.6;
    color: #f0f0f0;
  }
</style>

<div class="activity-flex-container">
  <div class="activity-item">
    <img src="Y_HR3985.JPG" class="high-quality-img" alt="Counselling Cell Inauguration">
    <p class="activity-text">
      <i>Engaging with Dr. Amey Agharkar during the inauguration of the Counselling Cell at Chanakya University.</i>
    </p>
  </div>

  <div class="activity-item">
    <img src="UGC.png" class="high-quality-img" alt="Goa University FDP">
    <p class="activity-text">
      <i>Engaging with faculty members during 124th Guru Dakshata (Online) Faculty Development Program at Goa University.</i>
    </p>
  </div>
</div>
