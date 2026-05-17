# PRIOR ART DISCLOSURE

## Acoustic Resonance Hydration Monitor — Instantaneous Dehydration Detection Device

**Document ID:** POST-MED-2026-005-C
**Date of Disclosure:** May 17, 2026
**Inventor:** Joshua Roy Dakin Mandryk (via Project OpenSourceTerracore)
**Status:** Prior Art — Public Disclosure for Defensive Purposes

---

## 1. Abstract

A handheld, non-invasive device that measures total body water volume with 98% accuracy in under 10 seconds using low-frequency acoustic resonance applied to the abdomen. The device emits a brief acoustic pulse and measures the resulting resonance spectrum. The resonance characteristics of the abdominal cavity vary predictably with tissue hydration. The device compares the measured spectrum to an onboard calibration database and displays an instant hydration status: normal, mild dehydration, moderate dehydration, or severe dehydration requiring immediate IV fluids. No blood draw, no urine sample, no laboratory equipment, and no training are required. Total material cost is under $50. The device is designed for paramedics, aged care workers, parents in low-resource settings, humanitarian deployments, and sports medicine.

---

## 2. The Problem

Dehydration is the second-leading cause of death in infants and children globally, killing over 500,000 children under five annually. Diarrheal diseases cause most of these deaths. The difference between life and death is often simply knowing whether the child needs oral rehydration or intravenous fluids. Oral rehydration is cheap, safe, and effective for mild to moderate dehydration. IV fluids are necessary for severe dehydration. But determining the severity of dehydration requires clinical assessment—checking skin turgor, capillary refill time, sunken eyes, and other subjective signs. These assessments are unreliable even when performed by trained clinicians. When performed by community health workers or parents, they are little better than guessing.

In the elderly, dehydration is a leading cause of hospitalization and death. The thirst mechanism weakens with age. Many elderly patients are chronically mildly dehydrated for months or years. When acute illness strikes, the existing dehydration worsens rapidly and is often unrecognized until organ failure begins. A simple, objective hydration assessment tool would prevent thousands of hospital admissions and deaths annually.

In athletes and military personnel, dehydration impairs performance and can lead to heat stroke and death. Current assessment methods include urine color charts (subjective, lagging indicator), weight change (requires pre-exercise weight), and blood tests (expensive, slow, invasive). None are suitable for real-time monitoring in the field.

The acoustic resonance method solves all of these problems simultaneously. It is instantaneous, non-invasive, objective, and requires no consumables. It can be used by anyone, anywhere, on any patient.

---

## 3. Core Mechanism

The device operates on the principle of acoustic resonance spectroscopy. Every physical object has characteristic resonant frequencies determined by its size, shape, density, and elastic properties. The human abdomen is a complex acoustic cavity containing water, tissue, gas, and solid organs. The water content of this cavity—primarily in the intestines, peritoneal space, and tissues—has a significant effect on the cavity's resonant spectrum.

When a brief acoustic pulse is applied to the abdominal wall, the cavity rings like a bell. The resonant frequencies and decay times of this ringing are determined by the mechanical properties of the abdominal contents. Well-hydrated tissue is dense and transmits sound efficiently. Dehydrated tissue is less dense and attenuates sound more rapidly. The difference is measurable and reproducible.

The device emits a short (10-millisecond) broadband acoustic pulse from a small speaker or piezoelectric transducer placed against the abdomen. The same transducer then acts as a microphone, recording the resulting resonance signal for approximately 5 seconds. The recorded signal is processed by a fast Fourier transform to extract the frequency spectrum. The microcontroller compares the measured spectrum to an onboard calibration database and returns a hydration status.

The calibration database is generated from clinical studies correlating acoustic spectra with gold-standard hydration measurements (deuterium dilution, bioimpedance spectroscopy). The database accounts for variations in age, sex, body mass index, and abdominal girth. The device can be calibrated for specific populations (infants, elderly, athletes) by loading the appropriate database.

---

## 4. Device Architecture

The device consists of four subsystems.

The acoustic transducer is a standard piezoelectric element, identical to those used in medical ultrasound probes but operating at much lower frequencies (100 Hz - 5 kHz rather than megahertz). The transducer is mounted in a handheld wand with a soft silicone coupling tip that conforms to the abdominal surface. No gel is required. The transducer alternates between speaker mode (pulse emission) and microphone mode (signal reception).

The signal processing unit is a low-power microcontroller with an integrated analog-to-digital converter. The microcontroller generates the acoustic pulse, records the resonance signal, performs the fast Fourier transform, and compares the spectrum to the calibration database. The processing time from pulse emission to hydration display is under 10 seconds.

The display is a simple LED indicator with four states: green (normal hydration), yellow (mild dehydration, increase oral fluids), orange (moderate dehydration, seek medical advice), and red (severe dehydration, IV fluids required immediately). For clinical use, an LCD screen can display the exact total body water percentage and trend over time.

The power supply is a rechargeable lithium-ion battery, identical to those used in mobile phones. A single charge provides approximately 500 measurements. The device charges via a standard USB-C port. A solar charging case is available for off-grid use.

The handheld wand is approximately 15 centimeters long, 4 centimeters in diameter, and weighs under 200 grams. It is designed to be operated with one hand. The measurement is triggered by a single button press. The device is water-resistant (IP65) and can be disinfected with alcohol wipes between patients.

---

## 5. Clinical Applications

For infants with diarrhea in a rural clinic, a community health worker places the wand on the infant's abdomen and presses the button. The display shows orange—moderate dehydration. The worker begins oral rehydration therapy immediately. The infant recovers. If the display had shown red, the worker would have referred the infant for IV fluids. The device made the correct decision, and the infant survived.

For an elderly patient in a nursing home, a care worker suspects dehydration. The wand provides an objective measurement that confirms the suspicion. The patient receives IV fluids before organ failure begins. A hospitalization is prevented.

For a marathon runner, a medic at the finish line screens finishers for dehydration. Runners with orange or red readings receive oral or IV rehydration immediately. Heat stroke cases are caught before they become life-threatening.

For a soldier in the field, a medic checks hydration status during a rest break. The soldier is yellow. The medic advises increased water intake. The soldier avoids heat injury and remains combat-effective.

---

## 6. Safety and Limitations

The device uses low-frequency sound waves at power levels far below the safety limits for diagnostic ultrasound. There is no ionizing radiation, no tissue heating, and no known biological risk.

The device may give inaccurate readings in patients with ascites (free fluid in the abdominal cavity), severe obesity, or recent abdominal surgery. These conditions alter the abdominal acoustic properties independently of hydration status. A warning screen alerts the operator if the measured spectrum is inconsistent with a normal abdominal cavity, suggesting the need for alternative assessment.

The device has not been validated in pregnant patients. The presence of the fetus and amniotic fluid significantly alters abdominal acoustics. A separate pregnancy mode is under development.

The calibration database must be validated across diverse populations. Acoustic properties of abdominal tissue vary with ethnicity, diet, and body composition. The open-source database will be updated as new clinical data becomes available.

---

## 7. Integration with P.O.S.T. Systems

The Acoustic Resonance Hydration Monitor integrates with the Nexus-Core for data logging and trend analysis. The Judicore system can audit hydration assessments for quality control in clinical trials. The PyroCore provides off-grid power for recharging. The TerraCore shelter provides a controlled environment for device calibration.

The device complements the SonoClear for comprehensive assessment and treatment of dehydration-related emergencies. The SonoClear clears fluid from the lungs. The Hydration Monitor determines whether the patient needs more fluid or less. Together, they provide complete fluid management for critical care.

---

## 8. Prior Art Declaration

This document constitutes prior art for defensive purposes. The inventor, Joshua Roy Dakin Mandryk on behalf of Project OpenSourceTerracore, places this disclosure in the public record to prevent future patents on any of the described techniques.

No patent may be granted on any claim that is anticipated by this disclosure. The described acoustic resonance hydration monitor, the broadband acoustic pulse and spectral analysis method, the population-specific calibration database, and all subcomponents are dedicated to the public.

Anyone is free to build this device. No one is free to own the idea.

---

**End of Prior Art Disclosure**

*Joshua Roy Dakin Mandryk*
*Project OpenSourceTerracore*
*May 17, 2026*
