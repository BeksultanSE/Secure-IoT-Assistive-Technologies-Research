# Research Methods and Tools – Final Course Project (Fall 2025)
**Astana IT University**

**Students:**\
B. Aitkazy,
A. Bekbulat,
A.P. Baktash, 
A. Kurmanbekov,
R. Turtulov\
**Course:** Research Methods and Tools  
**Supervisor:** Altynbek Seitenov  
**Submission:** November 2025

![Completed](https://img.shields.io/badge/Status-Completed-brightgreen) ![Reproducible](https://img.shields.io/badge/Reproducible-100%25-blue)

## Project Title
**Privacy and Security of Data Concerns of IoT Technologies for Visually Impaired People**

## Research Question
How do current IoT communication protocols create privacy and security risks for assistive devices designed for visually impaired users, and what lightweight, accessible solutions can be realistically implemented on low-cost hardware?

## Research Aim
To critically examine privacy and security weaknesses of widely used IoT communication protocols when applied to assistive devices for visually impaired users and to implement and test lightweight, accessible security solutions.

## Full Transparent Research Process (100 % reproducible – all stages)

| Stage | Description & Justification | Deliverables in this Repository | Status |
|-------|-----------------------------|---------------------------------|--------|
| 1. Literature Review | Systematic review of 25+ sources on IoT security, assistive technologies and privacy-by-design | → 01 Literature Review Process | Completed |
| 2. Research Questions & Introduction | Formulation of main research question and objectives, writing introduction chapter | → 02 Research Questions and Introduction Development | Completed |
| 3. Methodology | Qualitative exploratory design using semi-structured expert interviews + practical implementation; chosen for depth and real-world insight | → 03 Methodology | Completed |
| 4. Research Instruments | 9-question interview guide developed, piloted and finalised | → 04 Research Instruments | Completed |
| 5. Data Collection | Three expert interviews conducted and fully documented | → 05 Data collection | Completed |
| 6. Data Analysis | Thematic analysis, word-frequency, visualisations (word cloud, charts, thematic map) | → 06 Data analysis | Completed |
| 7. Practical Implementation | Secure MQTT (TLS 1.3) and BLE+DTLS implemented on ESP32 as proof-of-concept | → 07 Prototype Implementation (link + screenshots) | Completed |
| 8. Results & Final Report | Interpretation, comparison with literature, recommendations | Final report PDF + defense slides (root) | Completed |

## Experts Interviewed (3 participants)

1. **Mahdi Habibi**  
   Master’s student at Nazarbayev University, active IoT researcher, developed health-monitoring systems for elderly people using sensors and BLE/MQTT communication.

2. **Altynbek (Smart Technologies student, Astana IT University)**  
   3rd-year undergraduate with multiple award-winning IoT and AI projects since school; hands-on experience with MQTT and BLE in wearable and sensor projects.

3. **Dr Gulnara Abitova**  
   Associate professor, experienced academic and practitioner; real-world deployment of Zigbee-based smart-home systems.


## Key Findings (summary)
- MQTT and CoAP are responsible for >219 million publicly leaked messages in just four months (Trend Micro & Politecnico di Milano, 2023)
- 100 % of experts agree that current IoT standards do not sufficiently embed privacy-by-design principles for vulnerable users (including visually impaired persons)
- Resource constraints (battery, memory, cost) remain the biggest barrier to strong security in low-cost assistive devices
- Successful proof-of-concept: secure MQTT over TLS 1.3 and BLE+DTLS implemented on ESP32 with minimal battery overhead (<8 %)
- Recommended accessible solution: voice-biometric multi-factor authentication instead of visual PINs

## Practical Deliverable – Working Prototype
Fully functional secure IoT communication code (ESP32):  
→ https://github.com/Rasikrr/SATP  
(Link and screenshots are also in folder 07)

## How to Fully Reproduce This Research (step-by-step)
1. Begin with folder 01 – see how the literature gap was identified  
2. Follow the numbered folders sequentially – every draft, feedback, and iteration is preserved  
3. Open raw transcripts of conducted interviews in folder 05  
4. Recreate the thematic analysis using files in folder 06  
5. Flash and test the prototype from folder 07  
6. Read the complete final report and presentation slides (root directory)

**All materials are publicly accessible.**  
No login or special software is required. Anyone can verify every stage of this research.

Thank you for reviewing our complete and transparent research journey!

**GitHub Repository:**  
https://github.com/BeksultanSE/Secure-IoT-Assistive-Technologies-Research