# PRIOR ART DISCLOSURE

## PneumoPatch — Instantaneous Tension Pneumothorax Decompression Device

**Document ID:** POST-MED-2026-004-A  
**Date of Disclosure:** May 15, 2026  
**Inventor:** Joshua Roy Dakin Mandryk (via Project OpenSourceTerracore)  
**Status:** Prior Art — Public Disclosure for Defensive Purposes

---

## 1. Abstract

A single-use, self-adhesive patch applied to the chest wall that automatically detects, decompresses, and vents a life-threatening tension pneumothorax in under one second. The device combines a pressure-sensitive triggering membrane, a spring-loaded micro-trocar, and a one-way flutter valve into a package the size of a standard adhesive bandage. No training, no anatomical knowledge, and no manual insertion are required. The device is designed for battlefield medics, paramedics, first responders, and public access first aid kits. Total material cost per unit is under $20.

---

## 2. The Problem

A tension pneumothorax occurs when air enters the pleural cavity through a lung injury and cannot escape. The accumulating air compresses the lung, shifts the mediastinum, kinks the great vessels, and stops the heart. Death occurs within minutes.

Current pre-hospital treatment is needle decompression: a medic inserts a large-bore needle into the second intercostal space at the midclavicular line. This procedure requires anatomical knowledge, steely nerves, and luck. Failure rates in the field exceed 40% due to incorrect placement, insufficient catheter length, or re-occlusion. The patient who could have been saved dies while the medic struggles with a needle in a moving ambulance.

A tension pneumothorax is a mechanical problem. Air is trapped where it should not be. It needs a hole to escape. Making that hole should not require a trained medic with a steady hand. It should be automatic.

---

## 3. Core Mechanism

The PneumoPatch is a self-adhesive patch applied to the chest wall that automatically detects, decompresses, and vents a tension pneumothorax. It combines three integrated functions into a single device.

The first function is detection. The patch contains a pressure-sensitive membrane that bulges outward when exposed to elevated intrapleural pressure. When the membrane reaches a threshold displacement corresponding to a tension pneumothorax, it triggers the second stage.

The second function is penetration. A spring-loaded micro-trocar fires through the chest wall into the pleural space. The trocar is 14-gauge, the same diameter as a standard decompression needle, and is designed to penetrate to a calibrated depth of 4 centimeters, sufficient to reach the pleural space in most adults without risking lung parenchyma injury. The firing mechanism is activated by the pressure membrane and requires no user judgment.

The third function is one-way venting. Once the trocar is in place, a one-way flutter valve allows air to escape the pleural cavity while preventing air from re-entering. The valve is identical in principle to the Asherman chest seal already in military use, but integrated with the automatic insertion mechanism.

The entire sequence from application to decompression takes under one second. The medic or bystander simply removes the backing and sticks the patch on the patient's chest in the correct anatomical region. The patch does the rest.

---

## 4. Device Architecture

The PneumoPatch consists of four layers.

Layer one is the adhesive backing. A medical-grade hydrocolloid adhesive bonds the patch to the skin and provides a sterile seal. The adhesive is the same as standard chest seals and is hypoallergenic.

Layer two is the pressure-sensing membrane. A thin elastomeric diaphragm with a conductive coating forms one plate of a capacitor. The chest wall forms the other plate. As intrapleural pressure rises, the diaphragm deflects, changing the capacitance. A tiny microcontroller monitors the capacitance and detects the threshold crossing.

Layer three is the firing mechanism. A compressed spring holds the trocar in a retracted position. A fusible link or solenoid pin, powered by a small onboard battery, restrains the spring. When the microcontroller detects the pressure threshold, it passes a current through the fusible link, releasing the spring. The trocar fires. The entire mechanism is similar to an automatic epinephrine injector, adapted for chest penetration.

Layer four is the one-way valve. A flexible silicone flap valve covers the external opening of the trocar. Air can exit but not enter. The valve is protected by a plastic cap that also serves as the activation tab: pulling the cap arms the device and exposes the adhesive.

---

## 5. Clinical Application

A paramedic arrives at a car crash. The driver has chest trauma, is cyanotic, and has absent breath sounds on the left. The paramedic tears open a PneumoPatch, pulls the activation tab, and sticks it to the patient's left chest. The patch fires, the trocar enters the pleural space, and air hisses out through the one-way valve. The patient's lung reinflates. The cyanosis resolves. The patient survives.

A soldier is hit by shrapnel. His buddy rips open his IFAK, finds a PneumoPatch, and applies it. The soldier breathes again. Evacuation proceeds.

A construction worker falls onto rebar. His colleagues call an ambulance but the nearest hospital is 45 minutes away. Someone grabs the site's first aid kit, finds a PneumoPatch, and applies it. The worker survives the transport.

---

## 6. Safety and Limitations

The primary risk is misplacement. If the patch is placed over the heart or a major vessel, the trocar could cause fatal hemorrhage. This is mitigated by clear anatomical markings on the patch showing correct placement (second intercostal space, midclavicular line) and by the trocar depth limit of 4 centimeters, which is insufficient to reach the heart in most adults.

The secondary risk is failure to fire. If the pressure membrane does not reach the threshold, the device will not activate. This is a design feature, not a bug: it prevents unnecessary chest penetration. The patch can be manually activated by pressing firmly on the center, which forces the membrane past the threshold and triggers the mechanism.

The tertiary risk is infection. The trocar penetrates the skin and introduces bacteria to the pleural space. This risk is accepted in a life-threatening emergency. The patient will receive prophylactic antibiotics at the hospital. The benefit of surviving the tension pneumothorax outweighs the risk of subsequent infection.

The device is not suitable for pediatric patients due to the fixed trocar depth. A pediatric version with a shorter trocar and smaller patch is a separate design.

---

## 7. Prior Art Declaration

This document constitutes prior art for defensive purposes. The inventor, Joshua Roy Dakin Mandryk on behalf of Project OpenSourceTerracore, places this disclosure in the public record to prevent future patents on any of the described techniques.

No patent may be granted on any claim that is anticipated by this disclosure. The described automatic tension pneumothorax decompression device, the pressure-sensing membrane trigger, the spring-loaded micro-trocar, and the integrated one-way venting valve are dedicated to the public.

Anyone is free to build this device. No one is free to own the idea.

---

**End of Prior Art Disclosure**

*Joshua Roy Dakin Mandryk*  
*Project OpenSourceTerracore*  
*From a tent, with clarity, and with an open hand.*  
*May 15, 2026*
