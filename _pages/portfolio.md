---
permalink: /portfolio/
title: "Healthcare Data Projects & Case Studies"
description: "Healthcare data case studies by Jess Hayden: HIPAA de-identification pipeline, provider deduplication, and analytics dashboards. Real-world data quality solutions."
layout: single
author_profile: false
classes: wide
---

<p style="font-size:1.05em; color:#444; margin-bottom:2em;">Explore my work in healthcare data quality, HIPAA compliance, provider data deduplication, and healthcare analytics.</p>

<a href="/assets/Jessica_Hayden_Resume.pdf" class="btn btn--primary" target="_blank">Download Resume</a>

---

<div class="jh-project">
  <h3>HIPAA De-Identification Pipeline</h3>

  <span class="jh-star-label">Situation</span>
  <p>Healthcare organizations need to analyze patient data for operational insights, but strict HIPAA regulations prevent the use of identifiable patient information (PHI/PII) outside of production systems.</p>

  <span class="jh-star-label">Task</span>
  <p>Build a compliant, reusable de-identification solution that allows healthcare data to be safely used for analytics while meeting HIPAA Safe Harbor standards.</p>

  <span class="jh-star-label">Action</span>
  <ul>
    <li>Designed end-to-end de-identification pipeline using PostgreSQL and Python (Faker library)</li>
    <li>Implemented automated PHI/PII detection across 18 HIPAA identifiers</li>
    <li>Built role-based access controls to manage who can view original vs. de-identified data</li>
    <li>Created compliance scoring system to validate Safe Harbor requirements</li>
    <li>Developed user-friendly Streamlit interface for non-technical users</li>
    <li>Documented full methodology and compliance validation process</li>
  </ul>

  <span class="jh-star-label">Result</span>
  <ul>
    <li>Produced production-ready toolkit that ensures HIPAA Safe Harbor compliance</li>
    <li>Reduced de-identification time from manual (hours) to automated (minutes)</li>
    <li>Created reusable solution applicable across any healthcare organization</li>
    <li>Published open-source project demonstrating healthcare data governance expertise</li>
  </ul>

  <div class="jh-tools">
    <strong>Tools:</strong> PostgreSQL, Python (pandas, Faker, pyodbc), Streamlit, HIPAA Safe Harbor standards
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
  <h3>IBM Data Visualization Final Project - Sales &amp; Service Dashboards</h3>

  <span class="jh-star-label">Situation</span>
  <p>Organizations need dashboards that provide quick, actionable insights without overwhelming stakeholders with unnecessary complexity. Effective dashboard design requires balancing visual appeal with functional decision support.</p>

  <span class="jh-star-label">Task</span>
  <p>Design and build two business intelligence dashboards as my final project for IBM's Data Visualization course - one for sales performance tracking and another for service operations monitoring.</p>

  <span class="jh-star-label">Action</span>
  <ul>
    <li>Built two interactive dashboards in Google Data Studio analyzing auto sales and service data</li>
    <li>Sales Dashboard: Designed KPI scorecards (Profit, Quantity Sold, Average Quantity) with performance analysis by model and dealer to provide executive summary insights at a glance</li>
    <li>Service Dashboard: Created operations monitoring with recall tracking, customer sentiment visualization (treemap), profit/quantity trends over time (combo chart), and root cause analysis via pivot table heatmap</li>
    <li>Applied dashboard design principles: choosing appropriate visualizations for different data types, designing for user workflow, and prioritizing clarity over decoration</li>
    <li>Earned 100% on final project evaluation</li>
  </ul>

  <span class="jh-star-label">Result</span>
  <ul>
    <li>Created production-quality dashboards demonstrating end-to-end BI workflow</li>
    <li>Developed practical understanding of visualization selection (when to use scorecards vs. charts vs. heatmaps)</li>
    <li>Built reusable dashboard patterns applicable to healthcare quality metrics and operational monitoring</li>
    <li>Earned IBM Data Visualization and Dashboards certificate</li>
  </ul>

  <div class="jh-tools">
    <strong>Tools:</strong> Google Data Studio, dashboard design, KPI development, data visualization, business intelligence
  </div>

  <div class="jh-project-links">
    <a href="https://www.coursera.org/account/accomplishments/verify/VIWT9WKIZDSM" class="btn btn--primary" target="_blank" rel="noopener">View Certificate</a>
  </div>

  <p><img src="{{ site.url }}{{ site.baseurl }}/assets/Data Studio - Sales tab.png" alt="Sales Dashboard" style="max-width:100%; margin-top:1em;" /></p>
  <p><img src="{{ site.url }}{{ site.baseurl }}/assets/Data Studio - Service tab.png" alt="Service Dashboard" style="max-width:100%; margin-top:1em;" /></p>
</div>

---

<div class="jh-project">
  <h3>Slump Dog Sluggers &mdash; Philadelphia Phillies Performance Analysis</h3>

  <span class="jh-star-label">Situation</span>
  <p>Baseball analytics often assume age-related decline follows predictable patterns, but real-world player performance can be more nuanced. I wanted to test whether age actually correlates with performance decline across a full season.</p>

  <span class="jh-star-label">Task</span>
  <p>Build an analytical framework to track individual player performance over time and identify whether age-related patterns exist in the data.</p>

  <span class="jh-star-label">Action</span>
  <ul>
    <li>Collected and cleaned player performance data for the 2024&ndash;2025 Phillies seasons</li>
    <li>Designed multi-timeframe rolling average analysis (7-game, 14-game, 30-game windows)</li>
    <li>Built interactive Power BI dashboard to visualize performance trends by player and age group</li>
    <li>Applied statistical analysis to test age-decline hypotheses</li>
    <li>Currently rebuilding in Tableau to add interactive parameter controls for dynamic timeframe selection</li>
  </ul>

  <span class="jh-star-label">Result</span>
  <ul>
    <li>Identified that performance patterns were more complex than simple age-based decline</li>
    <li>Discovered that slumps and hot streaks showed stronger correlation to external factors than age</li>
    <li>Created analytical framework applicable to any sports performance analysis</li>
    <li>Demonstrated ability to challenge assumptions with data-driven insights</li>
  </ul>

  <div class="jh-tools">
    <strong>Tools:</strong> Power BI, SQL Server, Excel, statistical analysis, Tableau (in progress)
  </div>

  <div class="jh-project-links">
    <a href="https://github.com/jlynne2004/slump-dog-sluggers" class="btn btn--info" target="_blank" rel="noopener">View on GitHub</a>
    &nbsp;
    <a href="https://public.tableau.com/views/SlumpDogSluggersPhiladelphiaPhillies2025PerformanceAnalysis_17713144180270/PlayerPerformancebyCohort?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link" class="btn btn--primary" target="_blank" rel="noopener">View on Tableau Public</a>
  </div>
</div>

---

<div class="jh-project">
  <h3>Provider Data Deduplication Case Study</h3>

  <span class="jh-star-label">Situation</span>
  <p>Duplicate physician records from inconsistent data entry across multiple systems were causing patients to appear in wrong provider queues, disrupting care coordination and creating operational bottlenecks.</p>

  <span class="jh-star-label">Task</span>
  <p>Identify the root cause of duplicate records, quantify the scope of the problem, and develop both immediate workarounds and long-term solutions.</p>

  <span class="jh-star-label">Action</span>
  <ul>
    <li>Mapped physician data tables across three inbound data sources (CSV, Excel, pipe-delimited files)</li>
    <li>Analyzed patterns in naming conventions, misspellings, and location-change duplicates</li>
    <li>Built SQL-based deduplication logic using temp tables as immediate workaround</li>
    <li>Documented root causes and presented findings to cross-functional team (clinical, IT, operations)</li>
    <li>Led remediation project to implement permanent fixes</li>
  </ul>

  <span class="jh-star-label">Result</span>
  <ul>
    <li>Restored accurate patient-provider matching for 1,200+ affected records</li>
    <li>Eliminated queue assignment failures that were delaying patient care</li>
    <li>Identified and documented issue 3 months before it escalated to crisis level</li>
    <li>Solution was production-ready when executive leadership escalated the problem</li>
  </ul>

  <div class="jh-tools">
    <strong>Tools:</strong> SQL Server, T-SQL, data profiling, gap analysis, cross-functional stakeholder management
  </div>
</div>

---

<h2 class="jh-section-title">Additional Work</h2>

**Workout Wednesday Challenges**

Building technical skills through weekly Tableau visualization challenges that require creative problem-solving, dashboard design, and advanced techniques.

View my solutions on [Tableau Public](https://public.tableau.com/app/profile/jessica.hayden/vizzes){:target="_blank"}.

---

All project code and documentation available on [GitHub](https://github.com/jlynne2004){:target="_blank"}. For consulting inquiries or custom analytics solutions, visit my [Services](/services/) page.
