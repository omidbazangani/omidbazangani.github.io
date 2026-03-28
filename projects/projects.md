---
layout: page
title: Projects — Omid Bazangani
description: Embedded systems projects by Omid Bazangani — firmware, connectivity, security tooling, and industrial systems.
---

<style>
body {
    background-color: #f2f2f2;
}

.projects-intro {
    font-size: 16px;
    color: #555;
    margin-bottom: 30px;
    line-height: 1.6;
}

/* Project Card */
.project-card {
    margin-bottom: 30px;
    padding: 30px;
    position: relative;
    transition: all 0.3s ease;
    border-radius: 10px;
    background: linear-gradient(135deg, #ffffff 0%, #f9f9f9 100%);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    border-left: 4px solid #2c3e50;
}

.project-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
}

.project-card h2 {
    font-size: 22px;
    color: #2c3e50;
    margin-top: 0;
    margin-bottom: 15px;
    transition: text-shadow 0.3s ease;
}

.project-card:hover h2 {
    text-shadow: 2px 2px 8px rgba(50, 152, 219, 0.4);
}

.project-card h3 {
    font-size: 15px;
    color: #2c3e50;
    margin-top: 18px;
    margin-bottom: 6px;
    text-transform: uppercase;
    letter-spacing: 0.5px;
}

.project-card p {
    font-size: 15px;
    color: #555;
    line-height: 1.6;
    margin: 0 0 8px 0;
}

.project-card ul {
    padding-left: 20px;
    margin: 0 0 8px 0;
}

.project-card ul li {
    font-size: 14px;
    color: #555;
    margin-bottom: 4px;
}

.project-tags {
    margin-top: 12px;
}

.project-tag {
    display: inline-block;
    background-color: #ecf0f1;
    color: #2c3e50;
    font-size: 12px;
    padding: 3px 10px;
    border-radius: 3px;
    margin-right: 5px;
    margin-bottom: 5px;
}

</style>

<p class="projects-intro">
A selection of embedded systems work spanning firmware development, connectivity, industrial automation, fleet management, and security research. Some project details are generalized to respect confidentiality.
</p>

<!-- Project 1: Naya Create -->
<div class="project-card">
    <h2>Naya Create — Connected Product Firmware</h2>

    <h3>Overview</h3>
    <p>Firmware development for Naya Create and its modular accessories — a connected embedded product environment built on Zephyr RTOS with BLE connectivity.</p>

    <h3>Problem / Constraints</h3>
    <p>The product required robust firmware supporting modular hardware accessories, reliable BLE communication, and seamless hardware/software integration across STM32 and Nordic-based platforms. Firmware had to be maintainable, testable, and production-ready.</p>

    <h3>My Role</h3>
    <p>Senior Embedded Software Engineer at NayaTech. Responsible for firmware development in C, C++, and Python using Zephyr RTOS. Work on BLE connectivity, low-level debugging with GDB and J-Trace, firmware architecture, and hardware/software integration during bring-up and feature development.</p>

    <h3>Stack</h3>
    <p>C, C++, Python, Zephyr RTOS, STM32, Nordic nRF, BLE, GDB, J-Trace, Git</p>

    <h3>Key Technical Decisions</h3>
    <ul>
        <li>Used Zephyr RTOS for its modular driver model and native BLE stack support</li>
        <li>Designed modular firmware architecture to support interchangeable accessories</li>
        <li>Employed J-Trace and GDB for deep hardware-level debugging during bring-up</li>
    </ul>

    <h3>Outcome</h3>
    <p>Delivered production firmware for a connected embedded product with reliable BLE connectivity and modular accessory support.</p>

    <div class="project-tags">
        <span class="project-tag">Zephyr RTOS</span>
        <span class="project-tag">BLE</span>
        <span class="project-tag">Nordic nRF</span>
        <span class="project-tag">STM32</span>
        <span class="project-tag">C/C++</span>
        <span class="project-tag">GDB</span>
    </div>
</div>

<!-- Project 2: SEPAHTAN Fleet Management -->
<div class="project-card">
    <h2>SEPAHTAN — National Fleet Management System</h2>

    <h3>Overview</h3>
    <p>Embedded software development and technical management for SEPAHTAN, a national fleet management system based on ARM Cortex-M4.</p>

    <h3>Problem / Constraints</h3>
    <p>The system had to support real-time vehicle tracking and fleet-wide communication over CAN, TCP/IP, and FTP, with firmware-over-the-air (FOTA) update capability. Compliance with MISRA C and rigorous static and dynamic testing were required.</p>

    <h3>My Role</h3>
    <p>Senior Embedded Software Engineer and Technical Manager at SRC. Led the embedded software development team. Designed and implemented embedded software in C, C++, and Python. Contributed to hardware design and verification workflows.</p>

    <h3>Stack</h3>
    <p>ARM Cortex-M4, C, C++, Python, CAN, TCP/IP, FTP, FOTA, CMSIS, MISRA C, IAR EWARM</p>

    <h3>Key Technical Decisions</h3>
    <ul>
        <li>Designed the communication stack to support CAN, TCP, and FTP for diverse fleet data exchange</li>
        <li>Implemented FOTA for field-upgradable firmware across a deployed fleet</li>
        <li>Enforced MISRA C compliance with static and dynamic testing throughout development</li>
    </ul>

    <h3>Outcome</h3>
    <p>Delivered a national-scale fleet management system with reliable real-time tracking, multi-protocol communication, and field-updatable firmware.</p>

    <div class="project-tags">
        <span class="project-tag">ARM Cortex-M4</span>
        <span class="project-tag">CAN</span>
        <span class="project-tag">TCP/IP</span>
        <span class="project-tag">FOTA</span>
        <span class="project-tag">MISRA C</span>
        <span class="project-tag">Fleet Management</span>
    </div>
</div>

<!-- Project 3: ABBY -->
<div class="project-card">
    <h2>ABBY — Automated Side-Channel Leakage Profiler</h2>

    <h3>Overview</h3>
    <p>An open-source framework that automatically characterizes the microarchitectural leakage behavior of ARM Cortex-M devices, enabling data-driven side-channel simulator design.</p>

    <h3>Problem / Constraints</h3>
    <p>Traditional side-channel analysis requires significant manual effort for setup, trace recording, and leakage model creation. Existing profiling approaches are device-specific and hard to extend. There was no systematic, automated way to capture instruction-level leakage interactions at the microarchitectural layer.</p>

    <h3>My Role</h3>
    <p>Main researcher and developer during PhD at Radboud University. Designed the data collection methodology, built the profiling framework, created datasets, and evaluated leakage models against real-world cryptographic implementations.</p>

    <h3>Stack</h3>
    <p>Python, ARM Cortex-M0/M3, ARM Assembly, ChipWhisperer, QEMU, embedded C, machine learning (scikit-learn)</p>

    <h3>Key Technical Decisions</h3>
    <ul>
        <li>Targeted the microarchitectural layer rather than gate-level or software-only modeling</li>
        <li>Designed the data collection to be device-agnostic and extendable to other ARM cores</li>
        <li>Used systematic instruction interaction profiling to capture transition-based leakage</li>
    </ul>

    <h3>Outcome</h3>
    <p>Created two novel datasets capturing detailed instruction interaction leakage for ARM Cortex-M0/M3. The resulting leakage models match state-of-the-art simulator performance. Published at a peer-reviewed venue. Framework is open-source.</p>

    <div class="project-tags">
        <span class="project-tag">ARM Cortex-M</span>
        <span class="project-tag">Python</span>
        <span class="project-tag">QEMU</span>
        <span class="project-tag">Security</span>
        <span class="project-tag">Machine Learning</span>
        <span class="project-tag">Side-Channel Analysis</span>
    </div>
</div>

<!-- Project 4: Industrial QC Test Systems -->
<div class="project-card">
    <h2>Industrial QC &amp; Test Systems</h2>

    <h3>Overview</h3>
    <p>Multiple embedded test and quality control systems built for industrial and university customers, including a windshield wiper motor QC test system, Barkhausen noise test setup, and a QC laboratory water-meter test system using laser-beam modulation.</p>

    <h3>Problem / Constraints</h3>
    <p>Industrial production and laboratory environments needed repeatable, automated test setups to validate embedded hardware and products. Each system had unique requirements — from motor characterization to water-flow testing across multiple conditions and meter types.</p>

    <h3>My Role</h3>
    <p>Embedded Systems Engineer (freelance / independent). Designed and implemented firmware, control systems, and host-side automation. Later served as Technical Advisor for the water-meter QC system at Talayeh Industrial Complex.</p>

    <h3>Stack</h3>
    <p>ARM Cortex-M3, embedded C, Qt, LabVIEW, Modbus, UART, SPI, I2C, Python, custom test fixtures</p>

    <h3>Key Technical Decisions</h3>
    <ul>
        <li>Used Qt and LabVIEW for host-side interfaces depending on customer environment preferences</li>
        <li>Designed modular firmware test routines adaptable to different product types</li>
        <li>Built the water-meter system around laser-beam modulation with adaptation for different meter types and three water-flow conditions</li>
    </ul>

    <h3>Outcome</h3>
    <p>Delivered multiple production-grade test systems adopted into industrial workflows. The water-meter QC system supported testing across different meter types and flow conditions.</p>

    <div class="project-tags">
        <span class="project-tag">LabVIEW</span>
        <span class="project-tag">Qt</span>
        <span class="project-tag">ARM Cortex-M</span>
        <span class="project-tag">Modbus</span>
        <span class="project-tag">Test Automation</span>
    </div>
</div>

<!-- Project 5: Electrical-Machines Condition Monitoring -->
<div class="project-card">
    <h2>Electrical-Machines Condition Monitoring System</h2>

    <h3>Overview</h3>
    <p>An embedded monitoring and control system for industrial electrical machines, including monitoring and control solutions for plastic injection machinery and hydraulic press systems.</p>

    <h3>Problem / Constraints</h3>
    <p>Industrial machines needed real-time condition monitoring to detect faults early and optimize operations. The system had to interface with diverse sensors and communication buses while operating reliably in harsh factory environments.</p>

    <h3>My Role</h3>
    <p>Electronic and Automation Engineer at Talayeh Industrial Complex and later as independent engineer. Developed firmware, analog circuit interfaces, and communication stacks for embedded monitoring platforms.</p>

    <h3>Stack</h3>
    <p>AVR, ARM7, ARM Cortex-M, embedded C/C++, GPIO, UART, SPI, I2C, USB, CAN, Ethernet, LabVIEW, analog circuits</p>

    <h3>Key Technical Decisions</h3>
    <ul>
        <li>Built firmware around multiple communication interfaces (UART, SPI, I2C, CAN, Ethernet) for flexible sensor integration</li>
        <li>Used LabVIEW for real-time supervisory dashboards and data logging</li>
        <li>Integrated analog circuit design for sensor conditioning and signal processing</li>
    </ul>

    <h3>Outcome</h3>
    <p>Deployed monitoring systems for plastic injection machinery and hydraulic press operations, enabling real-time fault detection and operational optimization.</p>

    <div class="project-tags">
        <span class="project-tag">ARM Cortex-M</span>
        <span class="project-tag">CAN</span>
        <span class="project-tag">LabVIEW</span>
        <span class="project-tag">Industrial Automation</span>
        <span class="project-tag">Analog Design</span>
    </div>
</div>

<!-- Project 6: AMR Water Meter Prototype -->
<div class="project-card">
    <h2>AMR Water Meter Prototype</h2>

    <h3>Overview</h3>
    <p>Prototype development of an Automatic Meter Reading (AMR) water meter system with embedded wireless communication.</p>

    <h3>Problem / Constraints</h3>
    <p>Traditional water meters required manual reading, leading to inefficiencies and errors. The prototype needed low-power embedded design with reliable wireless data transmission and robust enclosure for deployment in water infrastructure.</p>

    <h3>My Role</h3>
    <p>Electronic and Automation Engineer at Talayeh Industrial Complex. Developed firmware and hardware for the AMR prototype using AVR and ARM platforms.</p>

    <h3>Stack</h3>
    <p>AVR, ARM7, embedded C, GPS, GSM (Cellular), UART, low-power design</p>

    <h3>Key Technical Decisions</h3>
    <ul>
        <li>Chose a low-power ARM-based platform for battery longevity in the field</li>
        <li>Used GSM/cellular for data backhaul to enable wide-area deployment</li>
        <li>Integrated GPS for meter location tracking in infrastructure mapping</li>
    </ul>

    <h3>Outcome</h3>
    <p>Delivered a working AMR prototype demonstrating automated remote meter reading with cellular connectivity.</p>

    <div class="project-tags">
        <span class="project-tag">AVR</span>
        <span class="project-tag">ARM7</span>
        <span class="project-tag">GSM</span>
        <span class="project-tag">GPS</span>
        <span class="project-tag">Low Power</span>
    </div>
</div>

<!-- Project 7: 5-DOF Robotic Arm -->
<div class="project-card">
    <h2>5-DOF Robotic Arm</h2>

    <h3>Overview</h3>
    <p>Design and firmware development for a 5-degree-of-freedom robotic arm with embedded control, built for a university customer.</p>

    <h3>Problem / Constraints</h3>
    <p>The robotic arm needed precise multi-axis control with smooth coordinated motion. The system required real-time servo control running on an embedded platform with a host-side control interface.</p>

    <h3>My Role</h3>
    <p>Independent Embedded Systems Engineer. Designed the embedded control firmware and host-side interface for real-time arm manipulation.</p>

    <h3>Stack</h3>
    <p>ARM Cortex-M3, FreeRTOS, embedded C, Qt, UART, PWM servo control</p>

    <h3>Key Technical Decisions</h3>
    <ul>
        <li>Used FreeRTOS for deterministic real-time control of multiple servo axes</li>
        <li>Built a Qt-based desktop application for real-time arm control and trajectory input</li>
        <li>Implemented smooth interpolation between waypoints for coordinated multi-axis motion</li>
    </ul>

    <h3>Outcome</h3>
    <p>Delivered a working 5-DOF robotic arm with real-time embedded control and a desktop control application.</p>

    <div class="project-tags">
        <span class="project-tag">FreeRTOS</span>
        <span class="project-tag">ARM Cortex-M3</span>
        <span class="project-tag">Qt</span>
        <span class="project-tag">Robotics</span>
        <span class="project-tag">Servo Control</span>
    </div>
</div>
