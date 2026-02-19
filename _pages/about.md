---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi, I'm Ziyang. Currently a Y3 Computer Engineering in Hong Kong University of Science and Technology.
I conducted extensive technical explorations in the Robomaster Lab at school and had a wealth of personal projects.    

My core interest is in Robotics and Automation. Especially focuses on embedded hardware and software design with STM32 & embedded linux Soc. I also have rich experience in mechanical structure design and optimization, 3D printing, and CNC structure design.

# 📖 Educations
- *2023.09 - now*, **The Hong Kong University of Science and Technology**  
BEng in Computer Engineering | GPA: 3.8/4.3

# 🔥 Selected Projects 
<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/SMT.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Autonomous SMT Pick-and-Place Machine](https://github.com/baoqi-zhong/Awesome-SMT-Machine)

**Ziyang Zhong**, Ziming Xian

- **Tech stack:** STM32, PCB design, Embedded C/C++, Python.
- **Mechanical:** Engineered CoreXY 4‑DOF (X/Y/Z/$\theta$) for 0402 placement; rigid frame achieves sub-50\,$\mu$m repeatability.
- **Hardware:** Custom stepper driver and main board with onboard Li‑Po charging for untethered operation.
- **Software:** Embedded C firmware on both boards implements high‑precision position control and trajectory planning. Python GUI handles automatic placement and real‑time monitoring; custom serial protocol with retransmission ensures reliable communication.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/WPT.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[120W Wireless Charging System with Bidirectional Communication](https://github.com/hkustenterprize/RM2025-PowerControlBoard-WirelessCharging)

Ziming Xian, **Ziyang Zhong**

- **Tech stack:**  STM32, PCB design, Embedded C, FreeRTOS, bidirectional communication protocol.
- **Hardware:** Co‑optimized TX/RX hardware and debugged communication circuits to ensure reliable communication and 120W power transfer under weak coupling.
- **Algorithm:** Designed robust bidirectional communication protocol enabling stable data exchange under fluctuating power. Implemented low‑quiescent‑current optimization, foreign object detection, and comprehensive fault handling with automatic recovery.
- **Application:** Deployed on robots with supercapacitor modules for automatic protocol handshaking and stable 120W charging; applicable to drones and industrial automation.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/FOC.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[High-Power-Density 20A FOC Brushless Motor Driver](https://github.com/baoqi-zhong/20A-FOC-Driver)

- **Tech stack:**  STM32G4, 6‑layer PCB, Embedded C, FOC, CNC machining.
- **Hardware:** Designed 6‑layer high‑density PCB with STM32G4; performed power integrity and thermal simulations. Achieved higher power density than DJI C620 commercial ESC.
- **Algorithm:** Implemented custom FOC with back‑EMF feedforward, dead‑time compensation, and automatic fault handling/recovery.
- **Application:** Integrated into a swerve‑drive robot, demonstrating accurate current and torque control.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/CAN.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Multi-Protocol Portable Debugger](https://github.com/baoqi-zhong/Multi-Protocol-Debugger)  

- **Tech stack:**  STM32F4, 4‑layer PCB, Embedded C, LVGL, FreeRTOS, USB protocol, CNC machining.
- **Hardware:** Designed 4‑layer PCB with STM32F4 and capacitive touch screen; integrated 15W lithium battery fast charging for untethered field use.
- **Software:** Built LVGL-based UI with driver-UI separation architecture. Supports dynamic side‑load decoding protocols for CAN FD, RS485, UART, featuring real‑time packet logging and waveform display.
- **Application:** Enables on‑site monitoring and control of motors via custom protocols; ideal for embedded system debugging and motor drive diagnostics.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/MotorTest.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Active Motor Testing Bench](https://github.com/baoqi-zhong)  

- **Tech stack:**  Python, Embedded C, STM32, PCB design, real‑time control, data analysis.
- **Hardware:** High‑rigidity mechanical test bench with active/passive motors; integrates torque sensor (0.1 Nm precision, high‑bandwidth amplification) and current sensing for power calculation.
- **Software:**  Python‑based automation suite executes arbitrary motion profiles, logs synchronized CSV data, and automatically extracts motor parameters (torque constant, bandwidth, inertia, friction) and evaluates closed‑loop response.
- **Application:** Enables comprehensive motor characterization for R&D, production testing, and controller tuning.
</div>
</div>

# 💻 Internships
- *2025-2026*, **HDSmart Technology Co., Ltd.** Shenzhen, China.  
Embedded Hardware & Software research and design Intern.  
Project outcome:  

<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/Knob.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**STM32U5 Knob Display:** Designed an interactive knob with capacitive touchscreen. Developed the TouchGFX hardware driver layer (HAL) based on the STM32U5 ultra-low power MCU and implemented a smooth UI drag-and-drop effect based on a physics engine.  
Designed full-cycle prototype (schematic, 4-layer PCB, firmware, CNC enclosure); **Chinese invention patent** in application; demo samples presented to **STMicroelectronics** for embedded world 2026 exhibition.  

- **Tech stack:**  STM32G4, 6‑layer PCB, Embedded C, FOC, CNC machining.
- **Hardware:** Designed 6‑layer high‑density PCB with STM32G4; performed power integrity and thermal simulations. Achieved higher power density than DJI C620 commercial ESC.
- **Algorithm:** Implemented custom FOC with back‑EMF feedforward, dead‑time compensation, and automatic fault handling/recovery.
- **Application:** Integrated into a swerve‑drive robot, demonstrating accurate current and torque control.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/Eye.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Robo Eye:** Based on an HDMI to MIPI output bridge chip, a dual-circular capacitive touchscreen is driven for use in companion robot eye projects for end customers.  
Designed full-cycle prototype (schematic, 4-layer PCB, firmware, CNC enclosure);  
</div>
</div>

# 💬 Invited Talks
<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/Kicon.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Video: How we use KiCad in a robotics team](https://youtu.be/mwfNEBjSK9c)

Speaker: **Ziyang Zhong**  
Invited to speak on KiCad Asia Developer Conference **KiCon 2025**.  
I share how our robotics team uses KiCad as our go-to EDA tool. I covered our full hardware workflow, version control with Git, and the pre-fabrication review process. I also walk through the essential KiCad plugins we rely on and how we document designs for software and mechanical teams. Finally, a peek at our open-source projects.
</div>
</div>

# 🔧 Skills
- **Hardware:** EDA Tool: Kicad, JLC EasyEDA. 6-layer high-speed PCB schematic design & layout. Hand-soldering and wiring. MATLAB/Simulink.
- **Embedded & Programming:** Embedded C/C++, STM32 with HAL. FreeRTOS, Embedded Linux. FOC & Motor control. Peripheral drivers, sensor fusion. UI framework: TouchGFX, LVGL, Qt. Computer vision, OpenCV.
- **Mechanical**: SolidWorks, C4D, 3D printing, CNC machining.
- **Others:** Web stack(JS, React). Reverse Engineering(ghidra)

# 🎖 Honors and Awards
## Scholarships
- *2025.12* Awarded **HKUST's Scholarship Scheme** for Continuing Undergraduate Students (2025/26)
- *2025.07* Awarded **Hongkong Government Scholarship** - Talent Development Scholarship (TDS) (2024/25)
- *2024.12* Awarded **HKUST's Scholarship Scheme** for Continuing Undergraduate Students (2024/25)
- *2024.07* Awarded **Hongkong Government Scholarship** - Talent Development Scholarship (TDS) (2023/24)

## Dean’s List
- *2025* Dean’s List for the School of Engineering (2025-26 Fall)
- *2024* Dean’s List for the School of Engineering (2024-25 Spring)
- *2024* Dean’s List for the School of Engineering (2024-25 Fall)
- *2023* Dean’s List for the School of Engineering (2023-24 Fall)

## Competition Awards
- *2025.03* 1st Place, RoboMaster 2025 University League
- *2023.12* Top 30, Hong Kong CTF Challenge – Reverse Engineering Track
