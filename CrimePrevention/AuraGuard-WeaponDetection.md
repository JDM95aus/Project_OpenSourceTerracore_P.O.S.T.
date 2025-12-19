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
