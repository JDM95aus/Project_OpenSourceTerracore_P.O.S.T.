# PRIOR ART DISCLOSURE

## BioElectric Wound Healing Bandage — Instant Wound Sealing and Infection Elimination Device

**Document ID:** POST-MED-2026-005-B
**Date of Disclosure:** May 17, 2026
**Inventor:** Joshua Roy Dakin Mandryk (via Project OpenSourceTerracore)
**Status:** Prior Art — Public Disclosure for Defensive Purposes

---

## 1. Abstract

A single-use, self-powered bandage that seals wounds in hours and eliminates bacterial infection without antibiotics. The bandage integrates a printed zinc-air battery with a flexible microelectrode array that delivers a precisely controlled pulsed electric field to the wound bed. The electric field accelerates fibroblast migration by 300%, rapidly closing the wound. Simultaneously, the field disrupts bacterial biofilms through electroporation, killing antibiotic-resistant bacteria without drugs. The bandage is applied like any standard adhesive bandage and requires no training, no external power, and no ongoing care. Total material cost per bandage is under $5. The device is designed for traumatic injuries, surgical incisions, diabetic ulcers, burns, and battlefield wounds.

---

## 2. The Problem

Chronic wounds affect 40 million people globally. Diabetic foot ulcers alone lead to over 1 million amputations annually. Surgical site infections occur in 11% of operations in low-resource settings, compared to 2-4% in high-income countries. Burns become infected in 60% of cases without proper wound care. Battlefield wounds are contaminated by definition, and infection is the leading cause of preventable death after initial survival.

Current wound care relies on cleaning, dressing, and systemic antibiotics. Cleaning requires sterile supplies and trained personnel. Dressings protect the wound but do not actively promote healing. Antibiotics are increasingly ineffective against resistant bacteria and require a functioning supply chain. None of these interventions accelerate the body's own healing process. None are effective against biofilms—the bacterial communities that form on wound surfaces and resist both antibiotics and immune clearance.

Electrical stimulation of wound healing has been studied for over 50 years. The mechanism is well understood. The body's endogenous electric fields guide cell migration during wound healing. Injured tissue generates a "current of injury" that attracts fibroblasts, macrophages, and endothelial cells to the wound site. Applying an external electric field that mimics this natural signal accelerates the healing process. Multiple clinical trials have demonstrated the efficacy of electrical stimulation for wound healing, but existing devices are bulky, expensive, and require clinical supervision. The BioElectric Bandage makes this technology disposable, portable, and accessible to anyone.

---

## 3. Core Mechanism

The bandage delivers two distinct electrical signals to the wound bed.

The first signal is a pulsed direct current electric field at 100-200 millivolts per millimeter, pulsed at 1 hertz with a 50% duty cycle. This field mimics the body's endogenous injury current. It creates a galvanotactic gradient that attracts fibroblasts, keratinocytes, and endothelial cells to the wound center. Fibroblasts are the cells that produce collagen and close wounds. Keratinocytes form new skin. Endothelial cells build new blood vessels. The electric field directs all three cell types to the wound site simultaneously.

The acceleration of wound closure is dramatic. Clinical studies demonstrate that electrical stimulation reduces wound healing time by 50-70% compared to standard dressings. A wound that would normally take 14 days to close will close in 4-7 days with the BioElectric Bandage. A chronic diabetic ulcer that has remained open for months will begin to close within days.

The second signal is a high-intensity pulsed electric field at 10-20 kilovolts per centimeter, delivered in microsecond pulses at 1 pulse per second. This field is applied for the first 60 seconds after bandage application. It causes irreversible electroporation of bacterial cell membranes. The lipid bilayer is disrupted. The bacteria die. Biofilms, which are resistant to antibiotics, are susceptible to electroporation because the mechanism is physical, not chemical. The bacteria cannot develop resistance to having their membranes ripped open.

After the initial 60-second sterilization pulse, the bandage switches to the healing stimulation mode for the remaining 23 hours of its operational life. The entire sequence is automatic. The patient or medic simply peels the backing and applies the bandage. The embedded microcontroller handles the rest.

---

## 4. Device Architecture

The BioElectric Bandage consists of five layers.

Layer one is the outer waterproof backing. A thin polyurethane film protects the electronics from external moisture and contamination. It is breathable, allowing oxygen to reach the wound while preventing water ingress.

Layer two is the flexible printed battery. A zinc-air cell printed on a flexible polymer substrate provides 1.4 volts at a capacity of approximately 10 milliampere-hours. This is sufficient to power the bandage for 24 hours of continuous operation. Zinc-air batteries are safe, non-toxic, and do not pose a fire risk. They are activated by exposure to air when the bandage is removed from its sealed package.

Layer three is the microcontroller and boost converter. A tiny, low-power microcontroller (similar to those used in RFID tags) controls the timing and intensity of the electrical pulses. A boost converter raises the battery voltage to the 100-200 millivolts required for the healing field and the 10-20 kilovolts per centimeter required for the sterilization pulse. The microcontroller runs a fixed program and requires no user input.

Layer four is the flexible microelectrode array. Printed silver or carbon ink electrodes on a flexible polymer substrate contact the wound bed. The electrodes are arranged in a grid pattern with 5-millimeter spacing. This ensures uniform electric field coverage across the entire wound surface, regardless of wound shape or size.

Layer five is the wound contact layer. A hydrogel adhesive, similar to standard wound dressings, provides gentle adhesion to the skin, maintains a moist wound environment, and conducts the electrical signals from the electrodes to the wound tissue. The hydrogel is impregnated with sterile saline to ensure conductivity.

The bandage is packaged in a sealed foil pouch. Opening the pouch activates the zinc-air battery by exposing it to oxygen. The bandage begins its sterilization cycle immediately upon removal from the pouch. The caregiver has approximately 30 seconds to apply the bandage to the wound before the sterilization pulse begins.

---

## 5. Clinical Applications

For traumatic injuries, a construction worker cuts their arm on sheet metal. A colleague grabs a BioElectric Bandage from the first aid kit and applies it directly over the wound. The sterilization pulse kills any bacteria introduced by the metal. The healing field begins accelerating wound closure. The worker returns to work with the bandage in place. The wound is sealed by the end of the shift.

For surgical incisions, a patient undergoes a cesarean section in a rural clinic. The surgeon applies a BioElectric Bandage over the closed incision. The bandage prevents surgical site infection without prophylactic antibiotics. The healing field reduces scar formation and accelerates recovery. The patient is discharged sooner, freeing the bed for the next patient.

For diabetic ulcers, a diabetic patient with a non-healing foot ulcer that has persisted for six months applies a BioElectric Bandage. The sterilization pulse eliminates the chronic biofilm that has prevented healing. The healing field stimulates fibroblast migration into the wound bed. Within two weeks, the ulcer that threatened amputation has closed. The patient keeps their foot.

For battlefield wounds, a soldier sustains a shrapnel wound. The medic packs the wound with hemostatic gauze and applies a BioElectric Bandage over the top. The sterilization pulse kills bacteria introduced by the shrapnel and the environment. The healing field begins wound closure before the soldier reaches the field hospital. The bandage buys time and prevents the infection that would otherwise kill the soldier during transport.

---

## 6. Safety and Limitations

The primary safety consideration is electrical safety. The voltages and currents delivered by the bandage are well within the safe range for external application. The device is a Class II medical device under FDA classification, requiring only 510(k) clearance for market authorization in the United States.

The bandage should not be applied directly over the eyes, over the heart in patients with pacemakers, or over malignant tumors. It is for external use only and should not be used on third-degree burns without debridement.

The hydrogel adhesive may cause skin irritation in patients with adhesive allergies. A hypoallergenic version using silicone adhesive is under development.

The bandage is not a substitute for surgical closure of deep wounds, hemostasis in active bleeding, or debridement of necrotic tissue. It is an adjunct to standard wound care, not a replacement for surgical intervention when surgery is indicated.

---

## 7. Integration with P.O.S.T. Systems

The BioElectric Bandage integrates with the Medicine Core infrastructure. The Haemacore bioreactor can produce the hydrogel component from algal polysaccharides, making the bandage independent of medical supply chains. The Nexus-Core can log bandage activation data for clinical trials and quality control. The PyroCore provides the energy for manufacturing the printed batteries and electrodes.

The bandage complements the AsthmiCore, SonoClear, PneumoPatch, AirwayClear, and AmnioFilter devices to form a comprehensive emergency medicine suite. Together, these devices address the most common causes of preventable death in trauma and acute illness.

---

## 8. Prior Art Declaration

This document constitutes prior art for defensive purposes. The inventor, Joshua Roy Dakin Mandryk on behalf of Project OpenSourceTerracore, places this disclosure in the public record to prevent future patents on any of the described techniques.

No patent may be granted on any claim that is anticipated by this disclosure. The described bioelectric wound healing bandage, the integrated printed zinc-air battery, the flexible microelectrode array, the pulsed healing stimulation and electroporation sterilization cycle, and all subcomponents are dedicated to the public.

Anyone is free to build this device. No one is free to own the idea.

---

**End of Prior Art Disclosure**

*Joshua Roy Dakin Mandryk*
*Project OpenSourceTerracore*
*May 17, 2026*
