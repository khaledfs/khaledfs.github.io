---
layout: default
title: Khaled Sleman | Portfolio
---

<style>
  /* Base Setup & Smooth Scrolling */
  html { scroll-behavior: smooth; }
  body { color: #2d3436; line-height: 1.6; }

  /* Typography Refinement */
  h1, h2, h3 { color: #1a1a1a; border-bottom: none !important; }
  
  /* Modern Header Design */
  .main-title { margin-bottom: 0; font-size: 2.8em; letter-spacing: -1px; }
  .sub-title { font-size: 1.3em; color: #636e72; margin-top: 5px; font-weight: 400; }

  /* Navigation: Glassmorphism effect */
  .nav-container {
    position: sticky; top: 10px; 
    background: rgba(255, 255, 255, 0.8);
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);
    padding: 12px;
    border-radius: 12px;
    border: 1px solid rgba(234, 236, 239, 0.7);
    box-shadow: 0 4px 30px rgba(0, 0, 0, 0.05);
    z-index: 1000;
    display: flex; justify-content: space-around;
    margin: 25px 0 40px 0;
  }
  .nav-link { 
    text-decoration: none; font-weight: 600; color: #4b6cb7; 
    transition: all 0.3s ease; font-size: 0.95em;
  }
  .nav-link:hover { color: #182848; transform: translateY(-1px); }

  /* Skill Tags: Vibrant & Clean */
  .skill-tag { 
    background: #ffffff; color: #4b6cb7; 
    padding: 5px 14px; border-radius: 8px; 
    font-size: 0.85em; font-weight: 600; 
    display: inline-block; margin: 4px; 
    border: 1px solid #e1e8ed;
    transition: all 0.2s ease;
    cursor: default;
  }
  .skill-tag:hover { 
    background: #4b6cb7; color: white; 
    border-color: #4b6cb7; transform: scale(1.05); 
  }

  /* Project Card: Soft Shadows */
  .project-card { 
    border: none; border-radius: 15px; 
    padding: 30px; margin-top: 25px; 
    background: #ffffff; 
    box-shadow: 0 10px 25px rgba(0,0,0,0.03); 
    border: 1px solid #f0f0f0;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  .project-card:hover { 
    transform: translateY(-5px); 
    box-shadow: 0 20px 40px rgba(0,0,0,0.06); 
  }

  /* Contact Links Buttons */
  .contact-btn {
    text-decoration: none; color: #555; font-size: 0.9em;
    padding: 8px 12px; border-radius: 6px;
    transition: background 0.2s;
  }
  .contact-btn:hover { background: #f5f5f5; color: #000; }

  hr { border: 0; height: 1px; background: #eee; margin: 40px 0; }
</style>

<header style="padding-top: 20px;">
  <h1 class="main-title">Khaled Sleman</h1>
  <p class="sub-title">Junior Full-Stack Developer</p>
</header>

<div style="margin-top: 15px;">
  <a href="mailto:Khaledsleman20@gmail.com" class="contact-btn">📧 Email</a>
  <a href="tel:0502320233" class="contact-btn">📞 050-232-0233</a>
  <a href="https://www.linkedin.com/in/khaled-s-7a144994/" class="contact-btn">🔗 LinkedIn</a>
  <a href="https://github.com/khaledfs" class="contact-btn">💻 GitHub</a>
</div>

<nav class="nav-container">
  <a href="#profile" class="nav-link">Profile</a>
  <a href="#education" class="nav-link">Education</a>
  <a href="#skills" class="nav-link">Skills</a>
  <a href="#certifications" class="nav-link">Certifications</a>
</nav>

<section id="profile">
  <h2 style="display: flex; align-items: center;">
    <span style="background:#4b6cb7; width:8px; height:24px; border-radius:4px; display:inline-block; margin-right:12px;"></span>
    Profile
  </h2>
  <p>Computer Science graduate with strong hands-on experience in <strong>Python development</strong>, <strong>backend systems</strong>, and <strong>API-based architectures</strong>, with a growing focus on <strong>automation</strong> and <strong>data-driven pipelines</strong>. Experienced in designing maintainable backend services, working with structured data, and debugging complex systems. Motivated to grow as a <strong>Software Automation Engineer</strong> in a <strong>Linux-based, product-oriented environment</strong>.</p>
</section>

<hr>

<section id="education">
  <h2>Education</h2>
  <div style="display: flex; justify-content: space-between; align-items: baseline;">
    <strong>B.Sc. in Computer Science</strong>
    <span style="color: #636e72; font-size: 0.9em;">Bar-Ilan University | 2021 – 2025</span>
  </div>

  <div class="project-card" id="projects">
    <h3 style="margin-top: 0; color: #182848;">🚀 Final Project: Smart Buy – AI-Powered Shopping Assistant</h3>
    <div style="display: inline-block; background: #e8f5e9; color: #2e7d32; padding: 2px 10px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-bottom: 15px;">Grade: 93</div>
    
    <ul style="line-height: 1.8; color: #444;">
      <li>Identified the need for reliable shared shopping lists and cost-effective decisions using real-time pricing data.</li>
      <li>Built a full-stack shopping assistant with backend pipelines to normalize raw JSON data.</li>
      <li>Implemented REST APIs with strong validation and error handling.</li>
      <li>Designed MongoDB models for products, shopping lists, and purchase history.</li>
      <li>Integrated backend services with Python-based ML experiments.</li>
      <li>Delivered a stable, maintainable system with improved robustness under unreliable inputs.</li>
    </ul>

    <div style="margin-top: 20px; border-top: 1px solid #f0f0f0; padding-top: 15px;">
      <span class="skill-tag" style="border-color:#ffd7d7">Python</span> 
      <span class="skill-tag" style="border-color:#d7eaff">Node.js</span> 
      <span class="skill-tag" style="border-color:#d7ffd9">MongoDB</span> 
      <span class="skill-tag" style="border-color:#e1d7ff">Linux</span>
    </div>
    
    <a href="https://github.com/khaledfs/SmartBuy" target="_blank" style="text-decoration: none; background: linear-gradient(to right, #4b6cb7, #182848); color: white; padding: 10px 20px; border-radius: 8px; font-size: 0.85em; display: inline-block; margin-top: 15px; font-weight: 600;">View Repository</a>
</div>
</section>

<hr>

<section id="certifications">
  <h2>Certifications</h2>
  <div style="margin-bottom: 10px;">
    <strong>Data Analyst Certification</strong> — <span style="color: #636e72;">NewTech Academy (2025)</span>
  </div>
  <ul style="line-height: 1.8; color: #444;">
    <li>Python scripting for automation and analytical workflows.</li>
    <li>Advanced SQL (MySQL, PostgreSQL familiarity).</li>
    <li>REST APIs, JSON, and structured data flows.</li>
    <li>Data validation, preprocessing, and exploratory analysis.</li>
    <li>Dashboarding with Power BI & Tableau.</li>
  </ul>
</section>

<hr>

<section id="skills">
  <h2>Technical Skills</h2>

  <p style="font-weight: bold; color: #4b6cb7; margin-bottom: 8px;">Programming & Backend</p>
  <div style="margin-bottom: 20px;">
    <span class="skill-tag">Python</span><span class="skill-tag">JavaScript</span><span class="skill-tag">TypeScript</span>
    <span class="skill-tag">C/C++</span><span class="skill-tag">Java</span><span class="skill-tag">C#</span>
    <span class="skill-tag">Node.js</span><span class="skill-tag">Express</span><span class="skill-tag">NestJS</span><span class="skill-tag">REST APIs</span>
  </div>

  <p style="font-weight: bold; color: #4b6cb7; margin-bottom: 8px;">Databases & Tools</p>
  <div style="margin-bottom: 20px;">
    <span class="skill-tag">MySQL</span><span class="skill-tag">PostgreSQL</span><span class="skill-tag">MongoDB</span><span class="skill-tag">NoSQL</span>
    <span class="skill-tag">Git/GitHub</span><span class="skill-tag">Linux (CLI)</span><span class="skill-tag">Docker</span><span class="skill-tag">AI coding assistants</span>
  </div>

  <p style="font-weight: bold; color: #4b6cb7; margin-bottom: 8px;">Strengths & Soft Skills</p>
  <div>
    <span class="skill-tag">Debugging</span><span class="skill-tag">Failure Analysis</span><span class="skill-tag">Code Optimization</span>
    <span class="skill-tag">System Integration</span><span class="skill-tag">Teamwork</span><span class="skill-tag">Reliability</span>
  </div>
</section>

<hr>

<section id="languages" style="padding-bottom: 50px;">
  <h2>Languages</h2>
  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); gap: 15px;">
    <div style="padding: 15px; border-radius: 10px; background: #f8f9fa; border: 1px solid #eee;">
      <strong>Arabic</strong><br><span style="color: #636e72; font-size: 0.9em;">Native</span>
    </div>
    <div style="padding: 15px; border-radius: 10px; background: #f8f9fa; border: 1px solid #eee;">
      <strong>Hebrew</strong><br><span style="color: #636e72; font-size: 0.9em;">Native-level</span>
    </div>
    <div style="padding: 15px; border-radius: 10px; background: #f8f9fa; border: 1px solid #eee;">
      <strong>English</strong><br><span style="color: #636e72; font-size: 0.9em;">High proficiency</span>
    </div>
  </div>
</section>
