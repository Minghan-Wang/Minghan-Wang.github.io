---
title: "Technical Portfolio"
excerpt: "Short description of portfolio item number 1<br/><img src='/images/500x300.png'>"
collection: portfolio
---

{% include base_path %}

## Featured Projects

### Google Dino Game on FPGA
**STARS Program | Summer 2024**  
*FPGA implementation with collision detection and display drivers*  
- Designed SPI controller for ili9341 LCD (320x240 resolution)  
- Implemented parallel and serial interface on ili9341 LCD
- Prototyped the game on 7-segment displays  
- Developed SystemVerilog modules: Parallel and Serial Interface, RNG, Score Counter, Collision Detector  
- Achieved 30 FPS with optimized rendering pipeline
[View Poster](files/Dino Game_ Final Presentation.pdf){: .btn .btn--primary}  
[Live Demo](https://github.com/Minghan-Wang/Google-Dino-Game-Team-8-in-STARS/){: .btn}
[Video Demo](https://github.com/Minghan-Wang/Google-Dino-Game-Team-8-in-STARS/){: .btn}  
[Source Code](https://github.com/Minghan-Wang/Google-Dino-Game-Team-8-in-STARS/){: .btn}

### RISC-V Configuration Benchmarking
**System on Chip Extension Technologies | Summer 2025**  
*Embench-IoT analysis for AFTx08 tapeout decisions*  
- Performed cache configuration sweeps (1-8KB d/i-cache)  
- Evaluated RISC-V ISA extensions (RV32I/E, zba/zbb/zbs)  
- Generated area/power estimates using Cadence Genus  
- Identified optimal configurations reducing tapeout risk by 40%  
[View Presentation](files/Tapeout Configuration and Testing Presentation - VIP 37920.pdf){: .btn .btn--primary}  
[View Poster](files/socet_tapeout_poster_spring25.pdf){: .btn .btn--primary}  


### AFTx08 Physical Design Flow
**SoCET Design Team | Spring 2025**  
*End-to-end RTL-to-GDSII implementation for RISC-V tapeout*  
- Executed physical design with Cadence Innovus
- Achieved DRC-clean layout using MITLL PDK and Simens Calibre  
- Developed reusable design flow infrastructure  
[View Documentation](files/DesignFlow_Tapeout_Verification Presentation_spring25.pdf){: .btn .btn--primary}  


### DFT Implementation for PCI Core
**SoCET Test Engineering | Fall 2024**  
*Scan chain insertion and ATPG patterns*  
- Inserted 8,000+ flip-flops into scan chains  
- Achieved 98.5% fault coverage with Synopsys TetraMAX  
- Developed clock domain crossing test strategies  
[View Methodology](/files/dft_workflow.pdf){: .btn .btn--primary}

## Technical Showcase
<div class="grid__wrapper">
  {% for post in site.portfolio %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
