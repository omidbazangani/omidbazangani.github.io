---
layout: page
title: Publications — Omid Bazangani
description: Peer-reviewed publications and technical reports by Omid Bazangani on embedded system security and side-channel analysis.
---

<style>
    /* Global Styles */
    body {
        font-family: 'Arial', sans-serif;
    }

    .navbar {
        background-color: #2c3e50;
        border-radius: 5px;
        margin-bottom: 30px;
    }

    .navbar-inner ul {
        list-style-type: none;
        padding: 0;
        display: flex;
        justify-content: space-around;
    }

    .navbar-inner ul li {
        display: inline;
    }

    .navbar-inner ul li a {
        padding: 10px 20px;
        display: block;
        color: white;
        text-decoration: none;
        border-radius: 5px;
        transition: background-color 0.3s ease;
    }

    .navbar-inner ul li a:hover {
        background-color: #34495e;
    }

    .article-title {
        font-size: 20px;
        font-weight: 600;
        margin: 20px 0;
        border-bottom: 2px solid #2c3e50;
        padding-bottom: 10px;
        transition: text-shadow 0.3s ease;
    }

    .article-title a {
        color: #3498db;
        text-decoration: none;
        transition: color 0.3s ease;
    }

    .article-title a:hover {
        color: #2980b9;
        text-shadow: 2px 2px 8px rgba(50, 152, 219, 0.4);
    }

    .article-summary {
        margin: 10px 0 30px;
        font-size: 16px;
        line-height: 1.6;
        color: #555;
        border-left: 5px solid #2c3e50;
        padding-left: 15px;
        background-color: #f9f9f9;
        border-radius: 5px;
        padding: 15px;
        box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    }

    h2 {
        margin-top: 40px;
        font-size: 24px;
        color: #2c3e50;
        border-bottom: 3px solid #2c3e50;
        padding-bottom: 10px;
    }

    h3 {
        margin-top: 30px;
        font-size: 22px;
        color: #34495e;
    }
</style>

<div class="navbar">
    <div class="navbar-inner">
        <ul class="nav">
            <li><a href="#articles">Articles</a></li>
            <li><a href="#techreports">Tech reports</a></li>
            <li><a href="#thesis">Thesis</a></li>
        </ul>
    </div>
</div>

<h2><a name="articles"></a>Articles</h2>


<div class="article">
    <div class="article-title">
        Can Machine Learn Pipeline Leakage? <a href="https://ieeexplore.ieee.org/abstract/document/10546629/">[IEEE]</a>
    </div>
    <div class="article-summary">
        O. Bazangani, P.A. Eliasi, S. Picek, I. Buhan, L. Batina<br>
        <em>2024 Design, Automation & Test in Europe Conference (DATE 2024)</em><br><br>
        Summary: Side-channel attacks cause a significant threat to security implementations in embedded devices. An automated framework simulating side-channel behaviours can offer invaluable insights into leakage origins and characteristics, helping developers improve those devices during the design phase. While there has been substantial effort towards crafting leakage simulators, earlier methods either necessitated significant manual work for reverse engineering the micro-architectural layer or depended on Deep Learning approaches without interpretable insights into the leakage source.
        This work investigates whether machine learning can learn pipeline leakage characteristics of ARM Cortex-M processors, advancing automated and interpretable side-channel leakage simulation.
    </div>
</div>

<div class="article">
    <div class="article-title">
        ABBY: <a href="https://eprint.iacr.org/2021/1569">Automating the creation of transition-based leakage models</a>
    </div>
    <div class="article-summary">
        Summary: Mitigating side-channel leakage in cryptographic components is
a vital concern for developers working with embedded devices.
The conventional side-channel analysis demands substantial man-
ual effort for setup preparation and trace recording, rendering it
more intricate during the dynamic design phase, where software
alterations occur frequently. Additionally, identifying the specific
instruction(s) responsible for leakage has been hindered by limited
hardware descriptions and restricted access to process technology
information.
We introduce ABBY, an open-source side-channel leakage profil-
ing framework that targets the microarchitectural layer. Existing
solutions to characterize the microarchitectural layer are device-
specific and/or require extensive manual effort. ABBY’s main inno-
vation is data collection, which can then automatically characterize
the microarchitectural behaviour of a target device and has the
additional benefit of being extendable to other similar devices.
Using ABBY, we created two datasets that capture the interaction
of instructions for the ARM CORTEX-M0/M3 architecture. These
sets are the first to capture detailed information on the microarchi-
tectural layer. They can be used to explore various leakage models
suitable for creating side-channel leakage simulators. A prelim-
inary evaluation of a leakage model produced with our dataset
of real-world cryptographic implementations shows performance
comparable to state-of-the-art leakage simulators.
        <!-- Truncated for brevity -->
    </div>
</div>

<h2><a name="thesis"></a>Thesis</h2>

<!-- Content for Thesis can be added here -->

<h2><a name="techreports"></a>Technical Reports</h2>

<!-- Content for Technical Reports can be added here -->
