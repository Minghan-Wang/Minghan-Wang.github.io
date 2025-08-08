---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in West Lafayette, Purdue University, 2026 (Expected)
  GPA: 3.98/4.00  
  *Certifications:* Semiconductor Fabrication 101, STARS Certificate  
  *Relevant Coursework:* Digital System Design, Advanced C Programming, Data Structures & Algorithms, Electrical Engineering Fundamentals II
  
Work experience
======
* May 2025 - Present: Digital Design Team Member
  * System on Chip Extension Technologies (SoCET), Purdue University
  * Duties included: 
    - Validating tapeout flow for AFTx08 RISC-V processor using AFTx07 test platform
    - Benchmarking cache configurations (1-8KB d/i-cache) and RISC-V ISA extensions (RV32I/E, zba/zbb/zbs)
    - Optimizing memory latency models (4-132 cycles) through Embench-IoT benchmarking
    - Conducting synthesis with Cadence Genus for area/power estimation

* Jan 2025 - Present: Design Flow Team Member
  * System on Chip Extension Technologies (SoCET), Purdue University
  * Duties included:
    - Performing pre-layout DRC verification using MITLL PDK and Cadence tools
    - Preparing GDSII layout for Skywater 130nm tapeout
    - Developing scalable design flow documentation for future projects

* Aug 2024 - Dec 2024: Test Engineer Team Member
  * System on Chip Extension Technologies (SoCET), Purdue University
  * Duties included:
    - Implemented scan chain insertion and ATPG for PCI core
    - Researched DFT methodologies for RISC-V SoC testability
    - Performed pre/post-DFT DRC checks and violation resolution

* May 2024 - July 2024: Hardware Engineer Intern
  * STARS Program, Purdue University
  * Duties included:
    - Led team developing FPGA-based Google Dino game using SystemVerilog
    - Designed key modules (RNG, Score Counter, Collision Detector)
    - Integrated display drivers for ili9341 LCD and Seven-Segment outputs
    - Presented project milestones to faculty reviewers
  
Skills
======
* Hardware Design:
  - RTL Design (SystemVerilog)
  - FPGA Prototyping
  - ASIC Tapeout Flows
  - Power Analysis
  - DFT/ATPG Implementation
* EDA Tools:
  - Cadence Genus/Innovus/Virtuoso
  - Siemens Calibre
  - Synopsys Fusion Compiler
  - OpenLane
* Programming:
  - C (Advanced)
  - Python
  - Git Version Control
* Standards:
  - RISC-V ISA (RV32I/E, Zba/Zbb/Zbs)
  - Memory Subsystem Optimization

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
* **Summer 2025**: Teaching Assistant - ECE 20002 & ECE 36800
  * Purdue University, West Lafayette
  * Duties included:
    - Conducted weekly office hours (in-person/online) for 200+ students across two courses
    - Provided individualized guidance on circuit analysis (Laplace transforms, frequency response) and data structures (trees, graphs, hashing)
    - Proctored examinations and ensured academic integrity compliance
    - Proofread course materials and exams for technical accuracy

* **Spring 2025**: Teaching Assistant - ECE 26400 (Advanced C Programming)
  * Purdue University, West Lafayette
  * Duties included:
    - Mentored students on advanced C concepts (pointers, memory management, data structures)
    - Debugged complex programming assignments and provided optimization feedback
    - Developed supplementary materials for core topics (file I/O, multi-threading, system calls)
    - Assisted in grading programming assignments and preparing autograders with focus on efficiency and best practices
  
Service and leadership
======
* Currently signed in to 43 different slack teams
