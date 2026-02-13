Advanced firewall solution for securing IoT devices against cyber threats.

#Abstract

The rapid adoption of IoT devices has introduced significant cybersecurity risks due to weak security measures. Notable incidents like the Mirai botnet attack (2016) and the water treatment facility hack (2021) highlight these vulnerabilities. This project develops an advanced firewall for IoT devices, incorporating real-time traffic monitoring, anomaly detection, and adaptive access control to ensure secure communication and mitigate cyber threats.

#Problem Statement

IoT devices are inherently vulnerable to attacks due to lack of device-level security, unencrypted communication protocols, and unauthorized access. This project addresses these issues by designing a lightweight, secure, and decentralized communication framework using ESP-NOW, focusing on scalability, energy efficiency, and ease of deployment.

#Objectives

-Implement a secure communication protocol for IoT devices.

-Minimize latency and bandwidth usage.

-Ensure scalability and flexibility across multiple devices.

-Enhance energy efficiency for low-power IoT devices.

-Provide offline functionality for uninterrupted operations.

#Implementation

-Hardware & Setup: Configured ESP8266/ESP32 modules for peer-to-peer communication using ESP-NOW.

-Security Measures: Implemented MAC filtering, AES-128 encryption, and real-time intrusion detection to prevent unauthorized access.

-Data Handling: Utilized segmentation, checksums, SPIFFS storage, and backup mechanisms for reliable data management.

-Firewall Mechanism: Blocks unauthorized devices and logs all access attempts for auditing.

-Front-End Development: Built a responsive UI using Web Serial API for real-time monitoring and control.

-OSI Layer Security: Applied encryption, authentication, and secure coding practices across all communication layers.

-Testing & Deployment: Conducted unit, functional, security, and user acceptance testing (UAT) to validate performance and reliability before deployment.

#Technology Stack

-Hardware: ESP8266, ESP32

-Communication Protocol: ESP-NOW

-Security: AES-128 encryption, MAC filtering, intrusion detection

-Data Storage: SPIFFS

-Front-End: Web Serial API

-Development Tools: Arduino IDE, VS Code

-Testing: Unit tests, functional tests, security validation, UAT
