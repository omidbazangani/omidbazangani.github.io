---
layout: page
title: Tutorials — Omid Bazangani
description: Hands-on tutorials on side-channel analysis, TVLA, and fault injection for embedded systems by Omid Bazangani.
---

<style>
body {
    background-color: #f2f2f2;
}

.tutorial-section {
    margin-bottom: 60px;
    padding: 30px;
    position: relative;
    transition: all 0.3s ease;
    border-radius: 10px;
    background: linear-gradient(135deg, #ffffff 0%, #f9f9f9 100%);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
}

.tutorial-section:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
}

.tutorial-section:not(:last-child)::after {
    content: '';
    position: absolute;
    bottom: -30px;
    left: 10%;
    right: 10%;
    height: 1px;
    background: linear-gradient(to right, transparent 10%, #e0e0e0 50%, transparent 90%);
}

.tutorial-title {
    font-size: 24px;
    color: #2c3e50;
    margin-bottom: 25px;
    transition: text-shadow 0.3s ease;
}

.tutorial-section:hover .tutorial-title {
    text-shadow: 2px 2px 8px rgba(50, 152, 219, 0.4);
}

.tutorial-link {
    display: block;
    margin-bottom: 15px;
    color: #3498db;
    text-decoration: none;
    transition: color 0.3s ease, padding-left 0.3s ease;
}

.tutorial-link:hover {
    color: #2980b9;
    padding-left: 15px;
}

.tutorial-link::before {
    content: '🔗 ';
    display: inline-block;
    margin-right: 8px;
    transition: transform 0.3s ease;
}

.pdf-link::before {
    content: '📄 ';
}

.notebook-link::before {
    content: '📓 ';
}

.tutorial-link:hover::before {
    transform: scale(1.1);
}

</style>

<div class="tutorial-section">
    <h2 class="tutorial-title">Test Vector Leakage Assessment(TVLA)</h2>
    <a class="tutorial-link pdf-link" href="{{ BASE_PATH }}/PDFDocs/TVLA_Tutorial.pdf">Instruction in PDF</a>
    <a class="tutorial-link notebook-link" href="https://github.com/omidbazangani/Teaching_Content/blob/main/PhysicalAttack_2023/TinyAES_TVLA-Student.ipynb">Companion Jupyter Notebook</a>
    <a class="tutorial-link notebook-link" href="https://github.com/omidbazangani/Teaching_Content/blob/main/PhysicalAttack_2023/TinyAES_TVLA_Teacher.ipynb">Solution Jupyter Notebook</a>
</div>

<div class="tutorial-section">
    <h2 class="tutorial-title">Fault Injection (FI) Attack</h2>
    <a class="tutorial-link pdf-link" href="{{ BASE_PATH }}/PDFDocs/FI_Toturial.pdf">Instruction in PDF</a>
    <a class="tutorial-link notebook-link" href="https://github.com/omidbazangani/Teaching_Content/blob/main/PhysicalAttack_2023/FI_Tutorial_ClockGlitch_Student.ipynb">Companion Jupyter Notebook</a>
    <a class="tutorial-link notebook-link" href="https://github.com/omidbazangani/Teaching_Content/blob/main/PhysicalAttack_2023/FI_Tutorial_ClockGlitch_Teacher.ipynb">Solution Jupyter Notebook</a>
</div>
