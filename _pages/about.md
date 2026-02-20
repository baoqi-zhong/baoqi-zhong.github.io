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

I'm Ziyang Zhong, a third-year Computer Engineering student at HKUST. 
I lead embedded hardware and software development in the RoboMaster team, and have delivered multiple full‑cycle projects from PCB design to CNC enclosure.

My core interest is in Robotics and Automation. Especially focuses on embedded hardware and software design with STM32 & embedded linux Soc. I also have rich experience in mechanical structure design and optimization, 3D printing, and CNC structure design.

# 📖 Education
- *2023.09 - now*, **The Hong Kong University of Science and Technology**  
BEng in Computer Engineering | GPA: 3.8/4.3


# Research Experience
- *2025.03-2025.07* Advisor: [Prof. Qiye Zheng](https://seng.hkust.edu.hk/about/people/faculty/qiye-zheng).

<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/ThermalMemristor.jpg' alt="ThermalMemristor" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Thermal memristor development**  

Conceptualized and built the mechanical structure for a thermal memristor from scratch using fiberglass board and 3D-printed PBT fixtures. Experimentally validated the memristor's core thermal memory effect, demonstrating hysteresis in thermal conductivity based on historical heat flow.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/ThermalTrans.jpg' alt="ThermalTrans" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Thermoelectric triode fixture development using 3D printed PBT material**  

The low thermal conductivity of novel PBT material was utilized to design and optimize the low thermal conductivity lattice structure, and the fixture was manufactured using 3D printing.  
Achieved a high thermal on/off ratio of 14:1, enabling efficient thermal switching for heat flow control.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/TempCtrl.jpg' alt="TempCtrl" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Engineered a **high-precision, 3-channel (80W x 3) temperature controller** for Peltier devices, achieving ±0.1°C closed-loop accuracy using PID and model based control.
Developed a **Python-based "thermal oscilloscope"** for real-time data visualization, multi-channel waveform generation (sine/cosine sweeps), and synchronized data acquisition from temperature and heat flux sensors.  
Designed **custom software for a heat flux sensor**, enabling synchronized multi-modal data recording alongside the 3-channel temperature.
</div>
</div>


# 💻 Internship
- *2025.09-now*, **HDSmart Technology Co., Ltd.** Shenzhen, China.  
Embedded Hardware & Software research and design Intern.  
Project outcome:  

<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/Knob.jpg' alt="KnobDisplay" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**STM32U5 Knob Display** 

- **Tech stack:** STM32U5, TouchGFX, 4‑layer PCB, Embedded C, CNC machining.
- **Hardware:** Designed 4-layer PCB with STM32U5 ultra-low-power MCU and capacitive touch panel.
- **Software:** Developed TouchGFX HAL driver; implemented physics‑based UI drag‑and‑drop for smooth interaction.
- **Application:** Chinese invention patent pending; demo samples presented to STMicroelectronics for embedded world 2026.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/Eye.jpg' alt="RoboEye" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Robo Eye**

- **Tech stack:** PCB design, HDMI/MIPI protocol, CNC machining.
- **Hardware:** 4-layer PCB with impedance-controlled routing for high-speed HDMI to MIPI signal conversion; precision‑machined CNC enclosure for seamless robot eye assembly.
- **Software:** Firmware for bridge chip initialization, I2C touch controller driver, and automatic resolution detection
- **Application:** Full‑cycle prototype development for a companion robot project; enables realistic, touch‑responsive animated eyes; delivered to end customers as a ready‑to‑integrate module.

</div>
</div>

# 🔥 Personal Projects 
<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/SMT.jpg' alt="SMT" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Autonomous SMT Pick-and-Place Machine](https://github.com/baoqi-zhong/Awesome-SMT-Machine)

**Ziyang Zhong**, Ziming Xian

- **Tech stack:** STM32, PCB design, Embedded C/C++, Python.
- **Mechanical:** Engineered CoreXY 4‑DOF (X/Y/Z/$\theta$) for 0402 placement; rigid frame achieves sub-50$\mu$m repeatability.
- **Hardware:** Custom stepper driver and main board with onboard Li‑Po charging for untethered operation.
- **Software:** Embedded C firmware on both boards implements high‑precision position control and trajectory planning. Python GUI handles automatic placement and real‑time monitoring; custom serial protocol with retransmission ensures reliable communication.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/WPT.jpg' alt="WPT" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[120W Wireless Charging System with Bidirectional Communication](https://github.com/hkustenterprize/RM2025-PowerControlBoard-WirelessCharging)

Ziming Xian, **Ziyang Zhong**

- **Tech stack:** STM32, PCB design, Embedded C, FreeRTOS, bidirectional communication protocol.
- **Hardware:** Co‑optimized TX/RX hardware and debugged communication circuits to ensure reliable communication and 120W power transfer under weak coupling.
- **Algorithm:** Designed robust bidirectional communication protocol enabling stable data exchange under fluctuating power. Implemented low‑quiescent‑current optimization, foreign object detection, and comprehensive fault handling with automatic recovery.
- **Application:** Deployed on robots with supercapacitor modules for automatic protocol handshaking and stable 120W charging; applicable to drones and industrial automation.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/FOC.jpg' alt="FOC" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**High-Power-Density 20A FOC Brushless Motor Driver**

- **Tech stack:** STM32G4, 6‑layer PCB, Embedded C, FOC, CNC machining.
- **Hardware:** Designed 6‑layer high‑density PCB with STM32G4; performed power integrity and thermal simulations. Achieved higher power density than DJI C620 commercial ESC.
- **Algorithm:** Implemented custom FOC with back‑EMF feedforward, dead‑time compensation, and automatic fault handling/recovery.
- **Application:** Integrated into a swerve‑drive robot, demonstrating accurate current and torque control.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/FOC_42.jpg' alt="FOC Stepper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Stepper Motor FOC Closed-Loop Driver](https://github.com/baoqi-zhong/Awesome-SMT-Machine)

- **Tech stack:** STM32G4, 4‑layer PCB, Embedded C, FOC, Kalman filtering.
- **Hardware:** Designed 4-layer PCB with STM32G4 and individual mosfet driver. Implements CAN bus interface communication for multi-axis synchronization.
- **Algorithm:** Run custom FOC with multi-axis synchronization CAN protocol. Additional zero-speed position control algorithm.
- **Application:** Integrated into the Autonomous SMT Pick-and-Place Machine project. Enables high response synchronized position control.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/CAN.jpg' alt="Multi-Protocol Debugger" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Multi-Protocol Portable Debugger**  

- **Tech stack:** STM32F4, 4‑layer PCB, Embedded C, LVGL, FreeRTOS, USB protocol, CNC machining.
- **Hardware:** Designed 4‑layer PCB with STM32F4 and capacitive touch screen; integrated 15W lithium battery fast charging for untethered field use.
- **Software:** Built LVGL-based UI with driver-UI separation architecture. Supports dynamic protocol decoding for CAN FD, RS485, UART.
- **Application:** Enables on‑site monitoring and control of motors via custom protocols; ideal for embedded system debugging and motor drive diagnostics.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/MotorTest.jpg' alt="MotorTestr" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Active Motor Testing Bench** 

- **Tech stack:** Python, Embedded C, STM32, PCB design, real‑time control, data analysis.
- **Hardware:** High‑rigidity mechanical test bench with active/passive motors; integrates torque sensor (0.1 Nm precision, high‑bandwidth amplification) and current sensing for power calculation.
- **Software:** Python‑based automation suite executes arbitrary motion profiles, logs synchronized CSV data, and automatically extracts motor parameters (torque constant, bandwidth, inertia, friction) and evaluates closed‑loop response.
- **Application:** Enables comprehensive motor characterization for R&D, production testing, and controller tuning.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/WirelessJLink.jpg' alt="WirelessJLink" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Wireless JLink Debugger](https://github.com/hkustenterprize/RM2025-Wireless-JLink)  

- **Tech stack:** PCB design, Embedded Linux, Kernel Drivers, CNC machining.
- **Hardware:** Designed a 4‑layer PCB integrating Allwinner V3s SoC, JLink‑OB, and Realtek WiFi module; performed EM simulation to optimize antenna placement for signal integrity.
- **Software:** Customized and compiled Linux kernel, built device tree, and ported JLink driver to enable wireless debugging over WiFi.
- **Application:** Achieved electrical isolation and mounted on a rotary stage, enabling remote debugging in friction‑testing setups and safe high‑power motor control scenarios.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/SolarFeeder.jpg' alt="SolarFeeder" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Solar-Powered Cat Shelter & Feeder**
Chinese invention patents and utility model patents pending.

- **Tech stack:** PCB design, Solar pannel, Edge computing, Embedded Linux, YOLO.
- **Hardware:** Developed a custom 4‑layer PCB integrating STM32G4 MCU, 9‑axis IMU, GPS, and high‑precision voltage/current sampling circuits. Implemented a digitally controlled buck converter for adaptive MPPT charging.
- **Software:** Hybrid sun‑tracking algorithm (astronomical + IMU/GPS feedback + current perturbation); adaptive MPPT with variable‑step perturbation, real‑time battery estimation (internal resistance, capacity), and multi‑level protection; YOLO‑based object detection on Embedded Linux.
- **Mechanical:** Designed a dual‑axis solar tracker with yaw and pitch mechanisms driven by servo motors and gear‑rack transmissions, enabling precise sun alignment
- **Application:** Autonomous outdoor cat shelter that maximizes solar harvest, intelligently charges batteries, and dispenses food via vision‑based detection, ensuring reliable off‑grid operation.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/MIPI.jpg' alt="Portable Display" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Ultra-thin Portable Display**

- **Tech stack:** PCB design, MIPI DSI protocol, CNC machining.
- **Hardware:** 4-layer PCB with impedance matching for high-speed signal integrity, delivering 1080p 60fps video over MIPI and PD; integrated audio amplifier and speakers using enclosure as resonant chamber for hi-fi sound.
- **Software:** Instant plug-and-play with automatic resolution adaptation.
- **Application:** Successfully small-batch produced and received highly positive user feedback.
</div>
</div>

# 💬 Invited Talks
<div class='paper-box'><div class='paper-box-image'><div><img src='images/Projects/kicon.jpg' alt="Kicon" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Video: How we use KiCad in a robotics team](https://youtu.be/mwfNEBjSK9c)

Speaker: **Ziyang Zhong**  
Invited to speak on KiCad Asia Developer Conference **KiCon 2025**.  
I share how our robotics team uses KiCad as our go-to EDA tool. I covered our full hardware workflow, version control with Git, and the pre-fabrication review process. I also walk through the essential KiCad plugins we rely on and how we document designs for software and mechanical teams. Finally, a peek at our open-source projects.
</div>
</div>

# 🔧 Skills
- **Hardware:** High-speed PCB design (up to 6 layers), Kicad, EasyEDA, MATLAB/Simulink.
- **Embedded:** STM32 (HAL), FreeRTOS, Embedded Linux, FOC motor control, Sensor fusion, TouchGFX, LVGL.
- **Software:** C/C++, Python, OpenCV, Qt, JavaScript/React.
- **Mechanical:** SolidWorks, C4D, 3D printing, CNC machining.
- **Others:** Web stack(JS, React). Reverse Engineering(ghidra)

# 🏆️ Honors and Awards
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
