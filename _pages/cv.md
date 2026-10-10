---
layout: archive
title: "Curriculum Vitae"
classes: cv
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

[Download PDF version](/files/Yifan_Luo_CV.pdf)

{% include base_path %}

## Education

### Cornell University
Ph.D., Civil and Environmental Engineering *(2027, expected)*
- Concentration: Energy and Water Resource Systems
- Minors: Atmospheric Sciences, Public Policy
- Committee: Dr. Vivek Srikrishnan (Chair), Dr. Flavio Lehner, Dr. Sheila Olmstead, Dr. Danielle Grogan

M.S., Civil and Environmental Engineering *(2025)*

### University of Michigan, Ann Arbor
M.S., Environment and Sustainability *(2022)*
- Specializations: Ecosystem Science and Management, Geospatial Data Sciences
- Advisors: Dr. Andrew Gronewold, Dr. Derek van Berkel

### University of British Columbia
B.S., Forest Sciences *(2020)*
- Specialization: Forest Ecology

### Beijing Forestry University
B.S., Biotechnology *(2020)*
- Minor: Japanese

## Research Experience

### [Srikrishnan Research Group](https://viveks.bee.cornell.edu/), Cornell University
Graduate Research Assistant *(Aug. 2023 – present)*

- Developed a deep learning emulator of the University of New Hampshire Water Balance Model (WBM) to quantify natural and human contributions to water shortages across the western U.S.
- Applied multiple explainable AI (XAI) methods to the emulator and combined their results into consensus-strength maps showing where methods agree on the main drivers of water shortage
- Quantified uncertainty in XAI attributions, separating disagreement among explanation methods from numerical instability caused by the emulator's training seed

### [Hydrologic Science & Uncertainty Assessment Lab](https://sites.google.com/umich.edu/gronewoldgroup/), University of Michigan
Graduate Student Research Assistant *(Mar. 2021 – May 2023)*

- Led three research projects on Great Lakes hydrologic and hydrodynamic modeling within a Bayesian Markov chain Monte Carlo framework
- Conducted statistical research on water balance model optimization and analyzed quantitative and qualitative data
- Delivered research presentations and wrote technical reports to communicate findings

### [Center for Sustainable Systems](https://css.umich.edu/), University of Michigan
GIS Specialist *(May 2022 – Sept. 2022)*

- Analyzed potential carbon storage in energy crops, agricultural production, and forest resources at the county level
- Mapped distances from heavy-duty vehicle charging stations to the nearest existing transmission line in each capacity class to compare transmission expansion costs with wholesale purchase costs

### [Environmental Spatial Analysis Lab](https://esalab.blogspot.com/p/about.html), University of Michigan
Research Assistant *(May 2021 – Dec. 2021)*

- Managed the geodatabase, map composites, and related metadata on land-cover and land-use change for University of Michigan properties
- Created a user manual for MField, a comprehensive data repository and information management system for field-based research on University of Michigan-owned properties
- Validated and cleaned up geospatial datasets and data products from recent research projects to ensure data integrity

### Institute of Applied Ecology, Shanghai Academy of Environmental Science
Lab Intern *(June 2018 – Aug. 2018)*

- Conducted field experiments on precipitation runoff, nitrogen transition, soil evaporation, and plant transpiration
- Collaborated with research investigators to design experiments and review experimental data
- Performed routine calibration and function checks on laboratory equipment to ensure accuracy, and managed laboratory inventory, including organizing supplies, placing orders, and scheduling equipment use

### Environmental Functional Nanomaterials Lab, Beijing Forestry University
Research Assistant *(Sept. 2017 – May 2018)*

- Coded and analyzed quantitative data on carbon capture and utilization in Excel
- Supported research on the synthesis and design of multifunctional nanomaterials by creating research posters, delivering presentations, and writing annotated bibliographies
- Attended and organized weekly professional seminars, networking with other research students and faculty

### State Key Laboratory of Pollution Control & Resource Reuse, Tongji University
Laboratory Technician *(Jan. 2018 – Feb. 2018)*

- Assisted graduate researchers with sample preparation and laboratory analyses for water and wastewater treatment experiments
- Prepared reagents and maintained and calibrated laboratory instruments in accordance with laboratory safety protocols
- Recorded, organized, and checked experimental data for the research team

## Publications

### Manuscripts in Preparation
  {% assign pubs = site.publications | where: "pubtype", "manuscript" | reverse %}
  <ul class="cv-list">{% for post in pubs %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

### Reports
  {% assign pubs = site.publications | where: "pubtype", "report" | reverse %}
  <ul class="cv-list">{% for post in pubs %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

### Theses
  {% assign pubs = site.publications | where: "pubtype", "thesis" | reverse %}
  <ul class="cv-list">{% for post in pubs %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Presentations

### Talks
  {% assign talks = site.talks | where: "type", "Presentation" | reverse %}
  <ul class="cv-list">{% for post in talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

### Posters
  {% assign talks = site.talks | where: "type", "Poster" | reverse %}
  <ul class="cv-list">{% for post in talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

## Teaching
  <ul class="cv-list">{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Workshops and Professional Training
* Deep Learning for Science (DL4Sci) Summer School. Lawrence Berkeley National Laboratory. *June 2025*
* Community Earth System Model (CESM) Workshop. National Center for Atmospheric Research (virtual). *June 2025*
* Workshop & Hackathon on Climate Risk, Insurance, and Reinsurance. Cornell University. *May 2025*
* Groundwater & Society Workshop. Pennsylvania State University. *May 2024*
* Wilderness First Aid CPR/AED Certification. Cornell Wilderness & Environmental Medicine Program. *Oct. 2023*
* Water Balance Model (WBM) User Community Meeting & Workshop. University of New Hampshire. *July 2023*
* Great Lakes Groundwater Workshop. U.S. Geological Survey (USGS) John Wesley Powell Center. *May 2023*
* Large Lake Statistical Water Balance Model (L2SWBM) & Copula Workshop. University of Michigan. *July 2022*

## Outreach and Science Communication
* "[One Model, Many Stories: Why Your AI's Explanation Might Be Misleading You](https://waterprogramming.wordpress.com/2025/10/28/one-model-many-stories-why-your-ais-explanation-might-be-misleading-you/)" blog post, Water Programming: A Collaborative Research Blog, Blog contributor. *Oct. 28, 2025*
* "[People of PCHES: Yifan Luo Spotlight](https://www.pches.psu.edu/yifan-luo-spotlight)" research profile, Program on Coupled Human and Earth Systems (PCHES), Pennsylvania State University, Featured researcher. *July 2025*
* "[EPA Considers Ann Arbor's Gelman Plume for List of Nation's Most Serious Contamination Sites](https://www.michigandaily.com/news/research/epa-considers-ann-arbors-gelman-plume-for-list-of-nations-most-serious-contamination-sites/)" news article, The Michigan Daily, Featured research. *Mar. 2025*

## Service
* Committee Member, Cornell Civil and Environmental Engineering Graduate Research Symposium. *2024–2025*

## Skills
* **Programming & Computing**: Python, R, Julia, Jupyter, Bash/Shell scripting, Git/GitHub, conda, LaTeX, HPC (Slurm)
* **Geospatial & Modeling Tools**: ArcGIS, ERDAS Imagine, Google Earth Engine, NetLogo, QGIS
* **Statistical & Analytical Methods**: Bayesian inference, regression & multivariate analysis, time-series & spatial statistics, uncertainty quantification and characterization, data visualization
* **Languages**: English (Fluent), Mandarin Chinese (Native), Japanese (Conversational), German (Conversational)
