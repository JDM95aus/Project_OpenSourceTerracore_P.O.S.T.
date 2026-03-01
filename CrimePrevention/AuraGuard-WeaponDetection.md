AuraGuard PRFDS Prior Art Disclosure

Project: Passive Resonant-Field Disturbance Sensing for Concealed Weapon Detection
Author: Joshua Roy Dakin Mandryk
Date: December 19, 2025
GitHub Repository: JDM95aus/Project_OpenSourceTerracore_P.O.S.T./CrimePrevention/
Licence: Creative Commons Duel Licence as stated in main project


1. Executive Summary

This document establishes prior art for AuraGuard, a passive, wide-area weapon detection system that identifies concealed guns and knives at distances up to 10 meters by analyzing disturbances in ambient radio frequency (RF) fields. The system requires no emitted radiation, preserves privacy, and represents a paradigm shift from checkpoint-based screening to continuous, passive monitoring.

2. Technical Innovation

2.1 Core Principle

All metallic objects interact with electromagnetic fields through absorption, reflection, and resonance. Ambient RF signals (Wi-Fi, cellular, broadcast) permeate all spaces. When a person carrying a metallic weapon moves through these fields, the weapon creates a detectable "RF shadow" or disturbance signature.

2.2 Detection Methodology

The system uses an array of Software-Defined Radio (SDR) receivers to monitor ambient RF across multiple frequency bands (50 MHz - 6 GHz). Machine learning algorithms analyze disturbances in real-time to distinguish weapon signatures from benign metal objects.

3. System Architecture

3.1 Hardware Configuration

· Sensor Nodes: RTL-SDR/ADALM-Pluto receivers with directional antennas
· Processing Units: Raspberry Pi 5 or NVIDIA Jetson Nano for edge computing
· Deployment: 5-7 meter spacing for 10m coverage, PoE powered
· Cost per Node: $130-$600 (commercial components)

3.2 Software Stack

· Firmware: Custom C++/Python for SDR control
· ML Framework: TensorFlow Lite for edge inference
· Communications: MQTT/HTTPS for alert transmission
· Dashboard: Web-based real-time monitoring interface

4. Key Advantages

4.1 Safety

· Zero radiation emission (fully passive)
· No health risks to operators or public
· Privacy-preserving (no imaging, no biometric data)

4.2 Efficiency

· Continuous monitoring without queuing
· <500ms detection latency
· >95% target accuracy with <2% false positives
· Unobtrusive deployment in existing infrastructure

4.3 Cost-Effectiveness

· 5-node system: $650-$3,000 (vs. $30,000-$100,000 for millimeter-wave)
· No dedicated operators required
· Low maintenance COTS components

5. Implementation Roadmap

Phase 1: Proof of Concept (Q1 2026)

· Single node prototype with RTL-SDR + Raspberry Pi
· Dataset collection of weapon/non-weapon RF signatures
· Basic binary classifier training

Phase 2: Prototype Development (Q2 2026)

· 3-node array with sensor fusion
· Environmental testing in controlled settings
· False positive reduction optimization

Phase 3: Pilot Deployment (Q3 2026)

· 5-node system in real-world environment
· Performance validation and iteration
· Regulatory compliance assessment

Phase 4: Commercialization (Q4 2026+)

· Custom PCB design for mass production
· FCC/CE certification
· Manufacturing partnerships

6. Challenges and Mitigations

6.1 False Positives

Challenge: Benign metal objects (phones, keys) causing alerts
Mitigation: Multi-dimensional feature analysis (spectral, temporal, spatial) combined with context-aware filtering

6.2 Urban RF Environment

Challenge: High ambient noise masking weapon signatures
Mitigation: Adaptive frequency selection and advanced signal processing

6.3 Deployment Density

Challenge: Achieving consistent 10m coverage
Mitigation: Strategic placement at chokepoints, hybrid node configurations

6.4 Evasion Attempts

Challenge: RF shielding of weapons
Mitigation: Shielded objects appear as conspicuous anomalies; secondary detection methods

7. Integration with Project OpenSourceTerracore

This system aligns with the P.O.S.T. philosophy of creating open-source, life-enhancing technology. Potential integration points include:

1. Security Layer: For P.O.S.T. deployment sites in vulnerable regions
2. Power Independence: Can be solar-powered using P.O.S.T. energy systems
3. Open Hardware: All designs will be released as open-source
4. Humanitarian Application: Protecting food distribution points, medical facilities

8. Intellectual Property Status

This disclosure establishes prior art for the core concepts of passive RF-based weapon detection. All designs, code, and documentation will be released under open-source licenses to prevent proprietary control of this critical safety technology.

9. Next Actions

1. Immediate: Create /CrimePrevention/AuraGuard/ directory in repository
2. Week 1: Begin Phase 1 hardware assembly and data collection
3. Month 1: Initial ML model training and validation
4. Month 2: Expand to 3-node array testing
5. Continuous: Documentation updates and community engagement


Architect's Note:
This represents another layer in the sovereignty stack - the right to safe spaces without surveillance or radiation. Like all P.O.S.T. technologies, it removes dependency on proprietary, expensive systems and returns capability to communities.

Joshua Roy Dakin Mandryk
December 19, 2025

---

update march 1st

PRIOR ART DISCLOSURE

Title:
Passive Radio Frequency Disturbance Detection for Aerial and Maritime Metallic Objects

Inventor:
Joshua Roy Dakin Mandryk
Lead Architect, Project OpenSourceTerracore (P.O.S.T.)
A.B.N. 80662917463
Email: opensourceterracore@gmail.com

Date of First Conception:
December 2025

Date of Public Disclosure:
Continuous and ongoing via opensourceterracore.org and associated public communications since December 2025.


Field of the Invention

This invention relates to the passive detection of metallic objects—including drones, aircraft, ships, and stealth platforms—by monitoring disturbances in ambient radio frequency signals. The system requires no active transmission, making it inherently stealthy, cost-effective, and resistant to jamming or electronic countermeasures.

Background

Conventional detection systems such as radar, lidar, and acoustic sensors rely on active emission, rendering them detectable, jammable, and expensive to deploy and maintain. They are often ineffective against stealth designs, low-flying drones, or small vessels. Existing passive systems are typically narrow in scope and not designed for multi-domain, scalable deployment.

AuraGuard, originally developed for local weapon detection, demonstrated that all metallic objects predictably disturb ambient radio frequency fields. This principle can be scaled to detect larger metallic objects over vast distances—including across oceans and through airspace—using existing ambient radio frequency sources and a network of passive sensors.


Summary of the additional discovery.

This invention extends the AuraGuard principle to create a global, passive detection network capable of identifying, tracking, and classifying metallic objects across air, sea, and land environments.

Key elements include:

· Passive sensing of ambient radio frequency disturbances caused by metallic objects.
· Use of existing radio frequency sources such as broadcast towers, cellular networks, and satellites as illuminators.
· Deployment of low-cost, off-the-shelf sensors on land, sea, air, and space platforms.
· Centralized or distributed artificial intelligence to analyze disturbance patterns, filter noise, and classify objects.
· Real-time tracking and threat assessment.
· Open-source, decentralized architecture allowing community and international participation.
· Immunity to stealth coatings or radar cross-section reduction, as metallic composition cannot hide from radio frequency disturbance.

Technical Description

Detection Mechanism

All metallic objects interact with ambient radio frequency fields. This interaction creates measurable disturbances in signal strength, phase, or timing. Passive sensors detect these disturbances without emitting any signal.

Sensor Deployment

· Coastal and maritime sensors placed on buoys, ships, offshore platforms, and coastal structures detect vessels and low-flying drones.
· Aerial and space-based sensors on satellites or high-altitude platforms detect aircraft, high-altitude drones, and orbital objects.
· Land-based sensors, including existing AuraGuard nodes, can be networked to cover urban and rural areas.

Signal Processing and Classification

Raw radio frequency data is processed by artificial intelligence systems that:

· Distinguish metallic disturbances from background noise and non-metallic interference.
· Classify objects by size, movement patterns, and unique radio frequency signatures.
· Track objects in real time across sensor networks.
· Predict trajectories and assess potential threats.

Integration

The system can be integrated with existing defense, security, and civilian infrastructure. Applications include:

· Early warning of drone incursions.
· Maritime domain awareness.
· Airspace monitoring.
· Counter-stealth operations.
· Border and critical infrastructure security.
· Search and rescue support.

Advantages Over Prior Art

· Passive operation eliminates detectability and jamming vulnerability.
· Stealth coatings and radar cross-section reduction do not affect detection.
· Low cost enables widespread deployment.
· Scalable from local to global coverage.
· Multi-domain detection across air, sea, and land.
· Decentralized architecture ensures no single point of failure.
· Open-source design allows continuous improvement and adaptation.

Claims

1. A passive system for detecting metallic objects by monitoring disturbances in ambient radio frequency signals.
2. The system of claim 1, wherein the objects detected include drones, aircraft, ships, submarines near the surface, and land vehicles.
3. The system of claim 1, wherein sensors are deployed on land, sea, air, or space platforms.
4. The system of claim 1, wherein the sensors require no active emission.
5. The system of claim 1, wherein disturbances are analyzed by artificial intelligence to identify, classify, and track objects in real time.
6. The system of claim 1, wherein the system operates using existing ambient radio frequency sources.
7. The system of claim 1, wherein the system is open-source and decentralized.
8. The system of claim 1, wherein the system detects objects regardless of radar stealth design.
9. The system of claim 1, wherein the system provides early warning of potential threats.
10. The system of claim 1, wherein the system can be integrated with existing security, defense, and civilian networks.

Prior Art References

· AuraGuard PRFDS (Original Concept) – Publicly disclosed December 2025.
· Published research on passive radio frequency detection (citations available in project documentation).
· Open-source hardware designs for radio frequency sensing (available via opensourceterracore.org).

Public Disclosure Record

All technical details, schematics, discussions, and correspondence related to this invention have been publicly available since December 2025.

This disclosure establishes prior art and prevents patenting of this technology by third parties.

Contact

For inquiries, collaboration, or licensing:

Joshua Roy Dakin Mandryk
Email: opensourceterracore@gmail.com
A.B.N. 80662917463

---
