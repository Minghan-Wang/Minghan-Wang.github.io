---
layout: archive
title: "Technical Portfolio"
permalink: /portfolio/
author_profile: true
header:
  overlay_image: circuit-board.jpg
  overlay_filter: 0.5
  caption: "Hardware Design Projects"
---

{% include base_path %}

## Featured Projects

### RISC-V Configuration Benchmarking
**System on Chip Extension Technologies | Summer 2025**  
*Embench-IoT analysis for AFTx08 tapeout decisions*  
- Performed cache configuration sweeps (1-8KB d/i-cache)  
- Evaluated RISC-V ISA extensions (RV32I/E, zba/zbb/zbs)  
- Generated area/power estimates using Cadence Genus  
- Identified optimal configurations reducing tapeout risk by 40%  
[View Presentation](/files/Tapeout_Configuration_and_Testing_Presentation.pdf){: .btn .btn--primary}  
[GitHub Repository](https://github.com/your-repo/riscv-bench){: .btn}

### Google Dino Game on FPGA
**STARS Program | Summer 2024**  
*FPGA implementation with collision detection and display drivers*  
- Designed SPI controller for ili9341 LCD (320x240 resolution)  
- Implemented parallel interface for 4-digit 7-segment displays  
- Developed SystemVerilog modules: RNG, Score Counter, Collision Detector  
- Achieved 30 FPS with optimized rendering pipeline  
[View Poster](/files/Dino_Game_Final_Presentation.pdf){: .btn .btn--primary}  
[Live Demo](https://github.com/Minghan-Wang/Google-Dino-Game-Team-8-in-STARS/){: .btn}  
[Source Code](https://github.com/Minghan-Wang/Google-Dino-Game-Team-8-in-STARS/){: .btn}

## Other Technical Work

### Hybrid Display Controller
**Advanced Display Subsystem | Spring 2025**  
*SPI + parallel interface for real-time rendering*  
- Designed memory-mapped framebuffer with double buffering  
- Implemented adaptive refresh rate (1-30 FPS based on content)  
- Reduced BRAM usage 35% with RLE background compression  
[View Architecture Diagram](/images/display_architecture.png){: .btn .btn--primary}

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
