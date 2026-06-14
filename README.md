# Kernel-Level Access Control & Advanced Security Landscapes for Cloud-Native Environments

**Author:** Minosh Nimsara Aluthge (IT24102268)  
**Institution:** Sri Lanka Institute of Information Technology (SLIIT)  
**Module:** IE2092 - Introduction to Cyber Security  
**Date:** April 2026  

## 📌 Project Overview
This repository contains academic research evaluating the paradigm shift from legacy perimeter-based security models to OS kernel-level defenses in cloud-native environments. As organizations transition to ephemeral microservices sharing underlying host kernels, traditional security perimeters are rendered obsolete.

This research explores how to defend the OS core (Ring 0) against advanced threats where a single container breach could expose an entire host. 

## 📂 Repository Contents
*   **`Research_Report.pdf`**: Comprehensive 5000+ word technical report detailing the evolution, background, and future developments of kernel security.
*   **`Presentation_Slides.pdf`**: Slide deck covering the core concepts of the research, including Linux Security Modules (LSM), eBPF programmability, and Hardware-Assisted Isolation.
*   **`Video_Presentation.mp4`**: A 10-minute technical breakdown and presentation of the research findings. *(Note: If you uploaded to YouTube instead, replace this bullet point with a link: [Watch the Video Presentation Here](your-youtube-link))*

## 🔬 Key Security Concepts Explored
*   **Evolution of Access Paradigms:** Transitioning from Discretionary Access Control (DAC) to Mandatory Access Control (MAC) and Zero Trust models.
*   **LSM Framework & TOCTOU:** Utilizing the Linux Security Module framework for strategic inline hooking to abolish Time-of-Check to Time-of-Use vulnerabilities. 
*   **MAC Implementations:** A comparative analysis of SELinux (Label-Based) versus AppArmor (Path-Based Confinement).
*   **eBPF Programmability:** Leveraging sandboxed virtual machines inside the kernel for real-time security enforcement and the transition toward autonomous AI-driven anomaly detection.
*   **Hardware-Assisted Isolation (HIVE):** Decoupling execution environments using Trusted Execution Environments (TEEs), Pointer Authentication Codes (PAC), and Branch Target Identification (BTI) to defeat code-reuse and Return-Oriented Programming (ROP) attacks.

---
*This research was conducted as an individual assignment fulfilling the learning outcomes for SLIIT IE2092 (Academic Year 2, Semester 2).*
