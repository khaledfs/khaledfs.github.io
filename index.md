---
layout: default
title: Khaled Sleman
---

<style>
  /* --- Global Styles --- */
  html { scroll-behavior: smooth; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background: #f9fafb; color: #111827; }
  h2 { border-bottom: 2px solid #e5e7eb; padding-bottom: 5px; margin-top: 40px; color: #1f2937; }
  h3 { color: #111827; }
  a { text-decoration: none; }
  
  /* --- Navigation --- */
  .sticky-nav {
    position: sticky;
    top: 0;
    background: rgba(255,255,255,0.95);
    backdrop-filter: blur(5px);
    padding: 15px 0;
    border-bottom: 1px solid #e5e7eb;
    z-index: 1000;
    display: flex;
    justify-content: center;
    gap: 40px;
    flex-wrap: wrap;
    transition: box-shadow 0.3s;
  }
  .sticky-nav:hover { box-shadow: 0 4px 12px rgba(0,0,0,0.08); }
  .nav-link {
    font-weight: 600;
    color: #2563eb;
    padding-bottom: 3px;
    transition: 0.3s;
    position: relative;
  }
  .nav-link::after {
    content: '';
    position: absolute;
    width: 0%;
    height: 2px;
    left: 0;
    bottom: -2px;
    background: #2563eb;
    transition: 0.3s;
  }
  .nav-link:hover::after { width: 100%; }

  /* --- Contact Info --- */
  .contact-info {
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
    font-weight: 500;
    margin-bottom: 25px;
  }
  .contact-info a { color: #2563eb; transition: 0.2s; }
  .contact-info a:hover { color: #1e40af; }

  /* --- Cards --- */
  .project-card {
    border: 1px solid #e5e7eb;
    border-radius: 12px;
    padding: 25px;
    margin-top: 20px;
    background: #fff;
    box-shadow: 0 6px 18px rgba(0,0,0,0.06);
    transition: transform 0.2s, box-shadow 0.2s;
  }
  .project-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 12px 24px rgba(0,0,0,0.1);
  }

  /* --- Skill Tags --- */
  .skill-tag {
    background: #e0e7ff;
    color: #3730a3;
    padding: 5px 14px;
    border-radius: 20px;
    font-size: 0.85em;
    font-weight: 600;
    display: inline-block;
    margin: 3px 5px 3px 0;
    border: 1px solid #c7d2fe;
    transition: 0.2s;
  }
  .skill-tag:hover {
    background: #c7d2fe;
    color: #1e3a8a;
    cursor: default;
  }

  /* --- Lists --- */
  ul { line-height: 1.7; }

  /* --- Buttons --- */
  .btn-github {
    text-decoration: none;
    background: #111827;
    color: white;
    padding: 10px 18px;
    border-radius: 8px;
    font-size: 0.9em;
    font-weight: 600;
    transition: 0.2s;
    display: inline-block;
  }
  .btn-github:hover { background: #1f2937; }

  /* --- Responsive --- */
  @media (max-width: 768px) {
    .sticky-nav { flex-direction: column; gap: 15px; }
    .contact-info { flex-direction: column; }
  }
</style>

<div class="contact-info">
  📧 <a href="mailto:Khaledsleman20@gmail.com">Khaledsleman20@gmail.com</a> | 
  📞 050-232-0233 | 
  🔗 <a href="https://www.linkedin.com/in/khaled-s-7a144994/">LinkedIn</a> | 
  💻 <a href="https://github.com/khaledfs">GitHub</a>
</div>

<div class="sticky-nav">
  <a href="#profile" class="nav-link">Profile</a>
  <a href="#education" class="nav-link">Education</a>
  <a href="#skills" class="nav-link">Skills</a>
  <a href="#certifications" class="nav-link">Certifications</a>
</div>

<h2 id="profile">Profile</h2>
Computer Science graduate with strong hands-on experience in **Python development**, **backend systems**, and **API-based architectures**, with a growing focus on **automation** and **data-driven pipelines**. Experienced in designing maintainable backend services, working with structured data, and debugging complex systems. Motivated to grow as a **Software Automation Engineer** in a **Linux-based, product-oriented environment**.

---

<h2 id="education">Education</h2>
**B.Sc. in Computer Science** — Bar-Ilan University (2021 – 2025)

<div class="project-card" id="projects">
  <h3 style="margin-top: 0;">Final Project: Smart Buy – AI-Powered Shopping Assistant</h3>
  <p style="color: #16a34a; font-weight: bold; margin-bottom: 10px;">Grade: 93</p>
  
  <ul>
    <li>Identified the need for reliable shared shopping lists and cost-effective decisions using real-time pricing data.</li>
    <li>Built a full-stack shopping assistant with backend pipelines to normalize raw JSON data.</li>
    <li>Implemented REST APIs with strong validation and error handling.</li>
    <li>Designed MongoDB models for products, shopping lists, and purchase history.</li>
    <li>Integrated backend services with Python-based ML experiments.</li>
    <li>Delivered a stable, maintainable system with improved robustness under unreliable inputs.</li>
  </ul>

  <div style="margin: 15px 0;">
    <strong>Tech Stack:</strong> 
    <span class="skill-tag">Python</span> <span class="skill-tag">Node.js</span> 
    <span class="skill-tag">Express</span> <span class="skill-tag">MongoDB</span> 
    <span class="skill-tag">REST APIs</span> <span class="skill-tag">Linux</span>
  </div>
  
  <a href="https://github.com/khaledfs/SmartBuy" target="_blank" class="btn-github">View on GitHub</a>
</div>

---

<h2 id="certifications">Certifications</h2>
**Data Analyst Certification** — NewTech Academy (2025)
<ul>
  <li>Python scripting for automation and analytical workflows.</li>
  <li>Advanced SQL (MySQL, PostgreSQL familiarity).</li>
  <li>REST APIs, JSON, and structured data flows.</li>
  <li>Data validation, preprocessing, and exploratory analysis.</li>
  <li>Dashboarding with Power BI & Tableau.</li>
</ul>

---

<h2 id="skills">Technical Skills</h2>

**Programming & Backend**
<div>
  <span class="skill-tag">Python</span><span class="skill-tag">JavaScript</span><span class="skill-tag">TypeScript</span>
  <span class="skill-tag">C/C++</span><span class="skill-tag">Java</span><span class="skill-tag">C#</span>
  <span class="skill-tag">Node.js</span><span class="skill-tag">Express</span><span class="skill-tag">NestJS</span><span class="skill-tag">REST APIs</span>
</div>

**Databases & Tools**
<div>
  <span class="skill-tag">MySQL</span><span class="skill-tag">PostgreSQL</span><span class="skill-tag">MongoDB</span><span class="skill-tag">NoSQL</span>
  <span class="skill-tag">Git/GitHub</span><span class="skill-tag">Linux (CLI)</span><span class="skill-tag">Docker</span><span class="skill-tag">AI coding assistants</span>
</div>

**Strengths & Soft Skills**
<div>
  <span class="skill-tag">Debugging</span><span class="skill-tag">Failure Analysis</span><span class="skill-tag">Code Optimization</span>
  <span class="skill-tag">System Integration</span><span class="skill-tag">Teamwork</span><span class="skill-tag">Reliability</span>
</div>

---

<h2 id="languages">Languages</h2>
* **Arabic:** Native
* **Hebrew:** Native-level
* **English:** High proficiency
