---
layout: frontpage
title: Omid Bazangani — Senior Embedded Software Engineer
description: Omid Bazangani is a Senior Embedded Software Engineer with 10+ years of experience in firmware, RTOS, connectivity, and embedded security.
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600&display=swap');

body {
    font-family: 'Open Sans', sans-serif;
    font-size: 16px;
    line-height: 1.6;
    color: #333;
    background-color: #f9f9f9;
    margin: 0;
    padding: 0;
}

h4 {
    font-size: 26px;
    margin-top: 0;
    text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.1);
    color: #2c3e50;
    border-bottom: 2px solid #2c3e50;
    padding-bottom: 10px;
}

a {
    color: #3498db;
    transition: color 0.3s ease;
}

a:hover {
    color: #2980b9;
    text-decoration: none;
}

/* Hero Section */
.hero-section {
    text-align: center;
    padding: 40px 20px 30px;
}

.hero-section .profile-img {
    max-width: 160px;
    border-radius: 50%;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    margin-bottom: 20px;
    pointer-events: none;
    user-select: none;
    -webkit-user-drag: none;
}

.hero-section h1 {
    font-size: 32px;
    color: #2c3e50;
    margin: 0 0 5px 0;
}

.hero-subtitle {
    font-size: 17px;
    color: #555;
    margin-bottom: 12px;
}

.hero-tagline {
    font-size: 15px;
    color: #777;
    max-width: 600px;
    margin: 0 auto 20px;
    line-height: 1.5;
}

.hero-buttons {
    display: flex;
    justify-content: center;
    gap: 12px;
    flex-wrap: wrap;
}

.hero-btn {
    display: inline-block;
    padding: 10px 22px;
    border: 2px solid #2c3e50;
    border-radius: 5px;
    color: #2c3e50;
    text-decoration: none;
    font-weight: 600;
    font-size: 14px;
    transition: all 0.3s ease;
}

.hero-btn:hover {
    background-color: #2c3e50;
    color: #fff;
    text-decoration: none;
}

.hero-btn.primary {
    background-color: #2c3e50;
    color: #fff;
}

.hero-btn.primary:hover {
    background-color: #1a252f;
    border-color: #1a252f;
}

/* Section Cards */
.section-card {
    background: linear-gradient(135deg, #ffffff 0%, #f9f9f9 100%);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
    padding: 30px;
    margin-bottom: 30px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.section-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
}

.section-card h3 {
    font-size: 22px;
    color: #2c3e50;
    margin-top: 0;
    border-bottom: 2px solid #2c3e50;
    padding-bottom: 8px;
    margin-bottom: 15px;
}

/* Work Area Grid */
.work-grid {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
}

.work-card {
    flex: 1;
    min-width: 200px;
    background: linear-gradient(135deg, #ffffff 0%, #f9f9f9 100%);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
    padding: 25px;
    text-align: center;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.work-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
}

.work-card .work-icon {
    font-size: 36px;
    margin-bottom: 10px;
}

.work-card h4 {
    font-size: 17px;
    color: #2c3e50;
    border: none;
    padding: 0;
    margin-bottom: 8px;
}

.work-card p {
    font-size: 14px;
    color: #555;
    margin: 0;
}

/* Highlights List */
.highlights-list {
    list-style: none;
    padding: 0;
    margin: 0;
}

.highlights-list li {
    padding: 10px 0;
    border-bottom: 1px solid #eee;
    font-size: 15px;
    color: #444;
}

.highlights-list li:last-child {
    border-bottom: none;
}

.highlights-list li strong {
    color: #2c3e50;
}

/* Project Preview Cards */
.project-preview-grid {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
}

.project-preview-card {
    flex: 1;
    min-width: 220px;
    background: linear-gradient(135deg, #ffffff 0%, #f9f9f9 100%);
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
    border-radius: 10px;
    padding: 20px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    border-left: 4px solid #2c3e50;
}

.project-preview-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
}

.project-preview-card h4 {
    font-size: 16px;
    color: #2c3e50;
    border: none;
    padding: 0;
    margin: 0 0 6px 0;
}

.project-preview-card p {
    font-size: 13px;
    color: #666;
    margin: 0 0 8px 0;
}

.project-preview-card .tag {
    display: inline-block;
    background-color: #ecf0f1;
    color: #2c3e50;
    font-size: 11px;
    padding: 2px 8px;
    border-radius: 3px;
    margin-right: 4px;
    margin-bottom: 4px;
}

/* Links Row */
.links-row {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
}

.links-row .section-card {
    flex: 1;
    min-width: 220px;
}

.links-row .section-card ul {
    list-style: none;
    padding: 0;
    margin: 0;
}

.links-row .section-card ul li {
    margin-bottom: 8px;
}

.links-row .section-card ul li a {
    text-decoration: none;
    font-size: 14px;
}

/* Contact Footer */
.contact-footer {
    background: linear-gradient(135deg, #ffffff 0%, #f9f9f9 100%);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
    padding: 30px;
    margin-bottom: 30px;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 20px;
}

.contact-footer h3 {
    width: 100%;
    font-size: 22px;
    color: #2c3e50;
    margin-top: 0;
    border-bottom: 2px solid #2c3e50;
    padding-bottom: 8px;
    margin-bottom: 10px;
}

.contact-info {
    font-size: 14px;
    color: #555;
    line-height: 1.8;
}

.contact-info a {
    color: #3498db;
}

</style>

<!-- Hero Section -->
<div class="hero-section">
    <img src="pics/omid.jpg" alt="Omid Bazangani" class="profile-img">
    <h1>Omid Bazangani</h1>
    <p class="hero-subtitle">Senior Embedded Software Engineer &nbsp;|&nbsp; RTOS, Connectivity, Low-Level Firmware</p>
    <p class="hero-tagline">I build reliable embedded systems with strengths in firmware architecture, RTOS, BLE connectivity, debugging, and embedded security. 10+ years of industry experience.</p>
    <div class="hero-buttons">
        <a class="hero-btn primary" href="{{ BASE_PATH }}/projects/projects.html">View Projects</a>
        <a class="hero-btn" href="{{ BASE_PATH }}/PDFDocs/bazangani_cv.pdf">Download CV</a>
        <a class="hero-btn" href="https://www.linkedin.com/in/omid-bazangani/">LinkedIn</a>
        <a class="hero-btn" href="https://github.com/omidbazangani">GitHub</a>
    </div>
</div>

<hr>

<!-- Professional Summary -->
<div class="section-card">
    <h3>About Me</h3>
    <p>Senior Embedded Software Engineer with 10+ years of experience in embedded firmware, RTOS-based development, low-level debugging, hardware/software integration, and industrial product development. Strong background in C, C++, Python, ARM Cortex-M platforms, Zephyr RTOS, BLE, communication protocols, and system bring-up.</p>
    <p>Experience spans connected products, industrial automation, fleet management, laboratory and test systems, and embedded security research. PhD research on Embedded System Security from <a href="https://cescalab.cs.ru.nl/members/">Radboud University</a> (side-channel simulation for ARM Cortex-M). M.Sc. in Embedded System Security from <a href="https://esisar.grenoble-inp.fr/">Grenoble-INP</a>.</p>
</div>

<!-- What I Work On -->
<h3 style="color:#2c3e50; margin-bottom:20px;">What I Work On</h3>
<div class="work-grid">
    <div class="work-card">
        <div class="work-icon">⚙️</div>
        <h4>Embedded Firmware</h4>
        <p>Zephyr RTOS, bare-metal firmware on STM32 and Nordic nRF. Device drivers, hardware bring-up, firmware architecture, and MISRA C.</p>
    </div>
    <div class="work-card">
        <div class="work-icon">📡</div>
        <h4>Connectivity &amp; Low-Level Systems</h4>
        <p>BLE, UART, SPI, I2C, CAN, FOTA, Modbus, GPS, GSM. Low-level debugging with GDB and J-Trace. Hardware/software integration.</p>
    </div>
    <div class="work-card">
        <div class="work-icon">🔒</div>
        <h4>Embedded Security &amp; Research</h4>
        <p>Side-channel analysis, leakage profiling, microarchitectural security tooling, and machine learning for security evaluation.</p>
    </div>
</div>

<br>

<!-- Selected Highlights -->
<div class="section-card">
    <h3>Selected Highlights</h3>
    <ul class="highlights-list">
        <li><strong>Senior Embedded Software Engineer at NayaTech</strong> — Firmware for Naya Create and modular accessories using Zephyr RTOS on STM32 and Nordic platforms, BLE connectivity, GDB/J-Trace debugging</li>
        <li><strong>Senior Embedded Software Engineer &amp; Technical Manager at SRC</strong> — Led development of SEPAHTAN, a national fleet management system on ARM Cortex-M4 with CAN, TCP, FTP, and FOTA</li>
        <li><strong>PhD Candidate in Embedded System Security, Radboud University</strong> — Side-channel simulation using microarchitectural features of ARM Cortex-M, QEMU-based emulation, and embedded cryptographic firmware</li>
        <li><strong>10+ years across connected products, industrial automation, fleet management, lab systems, and security research</strong></li>
    </ul>
</div>

<!-- Featured Projects Preview -->
<div class="section-card">
    <h3>Featured Projects</h3>
    <div class="project-preview-grid">
        <div class="project-preview-card">
            <h4>Naya Create — Connected Product Firmware</h4>
            <p>Firmware for a connected embedded product and modular accessories using Zephyr RTOS, BLE, and Nordic/STM32 platforms.</p>
            <span class="tag">Zephyr RTOS</span>
            <span class="tag">BLE</span>
            <span class="tag">Nordic nRF</span>
            <span class="tag">STM32</span>
        </div>
        <div class="project-preview-card">
            <h4>SEPAHTAN — Fleet Management System</h4>
            <p>National fleet management platform on ARM Cortex-M4 with CAN, TCP/IP, FTP, and FOTA capabilities.</p>
            <span class="tag">ARM Cortex-M4</span>
            <span class="tag">CAN</span>
            <span class="tag">FOTA</span>
        </div>
        <div class="project-preview-card">
            <h4>ABBY — Side-Channel Leakage Profiler</h4>
            <p>Open-source framework that automatically characterizes microarchitectural leakage behavior of ARM Cortex-M devices.</p>
            <span class="tag">Python</span>
            <span class="tag">ARM Cortex-M</span>
            <span class="tag">Security</span>
        </div>
    </div>
    <p style="text-align:center; margin-top:18px;">
        <a class="hero-btn" href="{{ BASE_PATH }}/projects/projects.html">See All Projects →</a>
    </p>
</div>

<!-- Publications & Tutorials Preview -->
<div class="links-row">
    <div class="section-card">
        <h3>Publications</h3>
        <ul>
            <li><a href="{{ BASE_PATH }}/publications/pubs.html">ABBY: Automating the creation of transition-based leakage models</a></li>
        </ul>
        <p><a href="{{ BASE_PATH }}/publications/pubs.html">View all publications →</a></p>
    </div>
    <div class="section-card">
        <h3>Tutorials</h3>
        <ul>
            <li><a href="{{ BASE_PATH }}/tutorials/tutorials.html">Test Vector Leakage Assessment (TVLA)</a></li>
            <li><a href="{{ BASE_PATH }}/tutorials/tutorials.html">Fault Injection Attack</a></li>
        </ul>
        <p><a href="{{ BASE_PATH }}/tutorials/tutorials.html">View all tutorials →</a></p>
    </div>
</div>

<!-- Contact Footer -->
<div class="contact-footer" id="contact">
    <h3>Contact</h3>
    <div class="contact-info">
        &#x1F4CD; The Netherlands<br>
        &#x2709; <a href="mailto:omid.bazangani@gmail.com">omid.bazangani@gmail.com</a><br>
        &#x1F517; <a href="https://www.linkedin.com/in/omid-bazangani/">LinkedIn</a><br>
        &#x1F517; <a href="https://github.com/omidbazangani">GitHub</a><br>
        &#x1F4C4; <a href="{{ BASE_PATH }}/PDFDocs/bazangani_cv.pdf">Download CV (PDF)</a>
    </div>
</div>