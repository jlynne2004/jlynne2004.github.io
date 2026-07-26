---
permalink: /portfolio/
title: "Healthcare Data Projects & Case Studies"
seo_title: "Healthcare Data Portfolio"
description: "HIPAA de-identification pipeline, provider deduplication, and BI dashboards – real data quality projects by Jess Hayden for healthcare orgs and nonprofits."
layout: single
author_profile: false
classes: wide
feature_row_extra:
  - title: "Slump Dog Sluggers"
    excerpt: "A Tableau Public dashboard using a PostgreSQL database that tracked individual Philadelphia Phillies' batting performance during the 2025 season. Designed a multi-timeframe rolling average analysis (7-game, 14-game, 30-game windows) to try and test how big of a factor does age play in a player's ability to bounce back from a slump.\n\n[View on GitHub](https://github.com/jlynne2004/slump-dog-sluggers){: .btn .btn--info .btn--small} [View on Tableau Public](tinyurl.com/slump-dog-sluggers){: .btn .btn--primary .btn--small}"
  - title: "The $97.7M Hit Drought Tracker"
    excerpt: "A Streamlit dashboard set up to give a quick snapshot of the stats for the Phillies' top 4 hitters during the 2026 season and testing how effective they are compared to the rest of the team. Also includes in memoriam, injured reserved, and restricted list trackers.\n\n[View the tracker on Streamlit](https://phillies-85m-drought-tracker.streamlit.app/){: .btn .btn--primary .btn--small}"
  - title: "Workout Wednesday Challenges"
    excerpt: "Building technical skills through weekly Tableau visualization challenges that require creative problem-solving, dashboard design, and advanced techniques.\n\n[View my solutions on Tableau Public](https://public.tableau.com/app/profile/jessica.hayden/vizzes){: .btn .btn--primary .btn--small}"
  - title: "IBM Data Visualization Course Final Project"
    exceprt: "Built two dashboards (sales performance and service operations tracking) using a provided auto sales dataset as the capstone for IBM's Data Visualization course - part of my ongoing IBM Data Analyst Professional Certification. Earned 100% on the final evaluation.\n\n[View Certificate](https://www.coursera.org/account/accomplishments/verify/VIWT9WKIZDSM){: .btn .btn--info .btn--small}"
---

<p style="font-size:1.05em; color:#444; margin-bottom:2em;">Explore the projects I've worked on throughout my career and the tools I used to solve them.</p>

---

<div class="jh-project">
  <h3>HIPAA De-Identification Pipeline</h3>

  <span class="jh-star-label">The Problem</span>
  <p>Healthcare organizations need to analyze patient data for operational insights, but strict HIPAA regulations prevent the use of identifiable patient information (PHI/PII) outside of production systems.</p>

  <span class="jh-star-label">What I Built</span>
  <p>A reusable Python toolkit that automatically de-identifies patient data to meet HIPAA Safe Harbor standards.</p>

  <span class="jh-star-label">The Result</span>
  <p class="notice--primary">Reduced de-identification time from hours to minutes with a production-ready, open-source toolkit now available to any healthcare organization.</p>

  <span class="jh-star-label">Tools</span>
  <div class="jh-tool-badges">
    <span class="jh-tool-badge">PostgreSQL</span>
    <span class="jh-tool-badge">Python (pandas, Faker, pyodbc)</span>
    <span class="jh-tool-badge">Streamlit</span>
    <span class="jh-tool-badge">HIPAA Safe Harbor standards</span>
  </div>

  <div class="jh-project-links">
    <a href="https://github.com/jlynne2004/hipaa-deidentification-pipeline" class="btn btn--info" target="_blank" rel="noopener">View on GitHub</a>
    &nbsp;
    <a href="https://hipaadeidentificationtoolkit.streamlit.app/" class="btn btn--primary" target="_blank" rel="noopener">Live Demo</a>
  </div>
  <p style="font-size:0.85em; color:#666; margin-top:0.8em;"><em>Note: The demo app may take a few seconds to load if inactive. For production use with real patient data, please download the toolkit from GitHub and run it locally in your secure environment.</em></p>
</div>

---

<div class="jh-project">
  <h3>Provider Data Deduplication Case Study</h3>

  <span class="jh-star-label">The Problem</span>
  <p>Duplicate physician records from inconsistent data entry were causing patients to appear in wrong provider queues, disrupting care coordination and creating operational bottlenecks.</p>

  <span class="jh-star-label">What I Built</span>
  <p>Identified the root cause of those duplicate records, quantified the scope of the problem, and developed both immediate workarounds and long-term solutions.</p>

  <span class="jh-star-label">The Result</span>
  <p class="notice--primary">Restored accurate patient-provider matching for 1,500+ affected records and eliminated queue assignment failures that were delaying patient care.</p>

  <span class="jh-star-label">Tools</span>
  <div class="jh-tool-badges">
    <span class="jh-tool-badge">SQL Server</span>
    <span class="jh-tool-badge">T-SQL</span>
    <span class="jh-tool-badge">Python</span>
    <span class="jh-tool-badge">Microsoft Excel</span>
    <span class="jh-tool-badge">data profiling</span>
    <span class="jh-tool-badge">gap analysis</span>
    <span class="jh-tool-badge">cross-functional stakeholder management</span>
  </div>
</div>

---

<div class="jh-project">
  <h3>Patient Churn Prediction Model</h3>

  <span class="jh-star-label">The Problem</span>
  <p>Healthcare practices need to identify at-risk patients and prioritize retention outreach, but predicting churn accurately and translating it into actionable business decisions isn't as simple as it sounds.</p>
  
  <span class="jh-star-label">What I Built</span>
  <p>A synthetic patient dataset generator and a full churn-prediction pipeline -- EDA, Random Forest model with threshold tuning, feature importance validation across two models, and a revenue-at-risk layer to prioritize outreach.</p>

  <span class="jh-star-label">The Result</span>
  <div class="notice--primary">
    <p>Identified billing issues and an insurance type of 'Self Pay' as the strongest churn drivers. Built a revenue-at-risk model surfacing $52K in monthly revenue tied to at-risk patients.</p>
  </div>

  <span class="jh-star-label">Tools</span>
  <div class="jh-tool-badges">
    <span class="jh-tool-badge">Python (pandas, scikit-learn, numpy)</span>
    <span class="jh-tool-badge">Random Forest</span>
    <span class="jh-tool-badge">statistical testing (chi-square, correlation)</span>
    <span class="jh-tool-badge">Jupyter</span>
  </div>
</div>

---

<h2 class="jh-section-title">Additional Work</h2>

{% include feature_row id="feature_row_extra" %}

---

All project code and documentation available on [GitHub](https://github.com/jlynne2004){:target="_blank"}.
