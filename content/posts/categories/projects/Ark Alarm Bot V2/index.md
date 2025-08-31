+++
date = '2025-08-30T21:47:09-07:00'
draft = false
title = 'Ark Alarm Bot V2'
description = "Ark Alarm Bot V2 is an automated monitoring and alerting tool for ARK: Survival Ascended, built for Windows. Originally based on the first-generation project ASA-Faerie, which suffered from instability and messy code, this version was carefully refactored over several months for improved reliability and maintainability. Implemented in C++17 with Qt, it combines OCR and image processing to deliver unattended game-guarding features—allowing the system to detect critical in-game events and respond without player intervention."
summary = "An automated Windows tool for ARK: Survival Ascended that uses C++17, Qt, and OCR-based image processing to provide reliable, unattended monitoring and alerts."
tags = ["projects", "posts"]
+++

# Ark Alarm Bot V2

**Ark Alarm Bot V2** ([GitHub repository](https://github.com/K1ngSY/Ark_Alarm_V2)) is an automated monitoring and alerting tool for Windows, designed for *ARK: Survival Ascended*.  

The first generation of the project was called **ASA-Faerie** ([GitHub repository](https://github.com/K1ngSY/ASA-Faerie)). Since the initial version suffered from frequent crashes and was filled with spaghetti code (the V2 codebase is still not fully standardized but represents a significant improvement), I spent several months gradually refactoring and rewriting the project.  

This V2 version is re-implemented in **C++17** and **Qt 6.9**, leveraging **OpenCV** and **Tesseract OCR** to provide unattended game-guarding functionality.  

---

## 🛠 Tech Stack
- **C++17**  
- **Qt 6.9**  
- **OpenCV**  
- **Tesseract OCR**

