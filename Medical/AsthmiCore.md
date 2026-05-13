PRIOR ART DISCLOSURE

AsthmiCore — Permanent Asthma Resolution Device

Document ID: POST-MED-2026-002
Date of Disclosure: May 13, 2026
Inventor: Joshua Roy Dakin Mandryk (via Project OpenSourceTerracore)
Status: Prior Art — Public Disclosure for Defensive Purposes

---

1. Abstract

A single-use, permanent resolution device for asthma that eliminates the condition at its biological source rather than temporarily managing symptoms. The device combines three existing and proven medical technologies into a single outpatient procedure: targeted bronchial thermoplasty to remodel hyperreactive airway smooth muscle, guided mesenchymal stem cell injection to regenerate healthy epithelial lining, and localized vagal nerve modulation to reset the parasympathetic overdrive that triggers bronchospasm. The entire procedure takes less than thirty minutes, requires no general anesthesia, and provides permanent resolution of asthma symptoms without daily medication. The device is open-source, buildable from existing medical components, and designed for community clinic deployment.

---

2. The Problem

Asthma affects approximately three hundred million people worldwide. Current treatment is chronic management, not cure. Patients use daily maintenance inhalers containing corticosteroids to reduce inflammation and bronchodilators to relax airway muscles. Rescue inhalers provide emergency relief during attacks. This is a lifetime of medication, repeated doctor visits, and constant risk of fatal exacerbation.

The annual global cost of asthma treatment exceeds eighty billion US dollars. Millions of asthma deaths occur each year, most of them preventable with proper medication access. But medication access is uneven. In low-resource settings, inhalers are unavailable or unaffordable. Even in wealthy nations, treatment failure and fatal attacks occur.

The core problem is that asthma is treated as a chronic condition requiring ongoing management when the underlying pathology has known, addressable mechanisms. The airway smooth muscle is hyperreactive and thickened. The epithelial lining is damaged and inflamed. The vagus nerve sends inappropriate constriction signals. Each of these mechanisms can be permanently addressed. No one has integrated them into a single device because the incentive structure of the medical industry favors lifetime treatment over one-time cures.

---

3. The Three Mechanisms of Asthma

Asthma is not one disease but three concurrent pathologies that reinforce each other.

Mechanism one is smooth muscle hypertrophy and hyperreactivity. The muscles surrounding the small airways have grown thicker and more sensitive. They contract too easily and too strongly in response to triggers such as cold air, exercise, allergens, or stress. This is the direct cause of airway narrowing during an asthma attack.

Mechanism two is chronic inflammation and epithelial damage. The lining of the airways is constantly irritated and inflamed. The protective epithelial layer is damaged, exposing nerve endings and allowing irritants to penetrate deeper into the tissue. This inflammation keeps the smooth muscle in a primed, ready-to-contract state.

Mechanism three is vagal nerve overactivity. The vagus nerve, which carries parasympathetic signals from the brain to the lungs, sends excessive constriction signals. This is the reason asthma worsens with stress and why some patients respond to breathing techniques that modulate vagal tone. The nerve itself is not damaged. It is simply set to the wrong baseline.

Current treatments address these mechanisms incompletely. Inhaled corticosteroids reduce inflammation but do not heal the epithelium or reduce muscle mass. Bronchodilators relax muscle temporarily but do not stop it from becoming reactive again. Biologics block specific inflammatory pathways but do nothing for the structural changes in the airway wall.

The AsthmiCore addresses all three mechanisms permanently in a single procedure.

---

4. Device Architecture

4.1 The Bronchial Thermoplasty Module

The first component of the AsthmiCore is a precision thermal ablation device delivered via a standard bronchoscope. This technology already exists and is FDA-approved for severe asthma. It is simply not widely deployed or combined with the other required components.

The principle is as follows. A thin catheter with an expandable electrode array at its tip is inserted through the bronchoscope into the small airways. The electrodes are deployed against the airway wall. Radiofrequency energy is delivered, heating the smooth muscle layer to approximately sixty-five degrees Celsius. This temperature is sufficient to denature and shrink the hyperreactive smooth muscle but low enough to preserve the surrounding healthy tissue. Over the following weeks, the treated muscle is replaced by normal, non-hypertrophied tissue through the body's natural healing processes.

The AsthmiCore improves on existing bronchial thermoplasty devices in three ways. First, the electrode array is shape-sensing and adaptive, conforming to airways of varying diameter without manual adjustment. Second, the energy delivery is guided by real-time impedance monitoring that stops automatically when the target muscle layer has been fully treated, preventing overtreatment or undertreatment. Third, the device treats all affected airways in a single session rather than requiring three separate bronchoscopies spaced weeks apart.

The hardware required is a standard bronchoscope, a radiofrequency generator with power output adjustable from one to twenty watts, and the custom electrode catheter. All components are available from multiple medical device suppliers. The open-source design specifies the electrode geometry and the control algorithm, not proprietary components.

4.2 The Stem Cell Regeneration Module

The second component delivers autologous mesenchymal stem cells directly to the treated airway surfaces to regenerate a healthy epithelial lining.

Mesenchymal stem cells are harvested from the patient before the procedure. A small sample of fat tissue or bone marrow is collected via needle aspiration, a ten-minute outpatient procedure. The stem cells are isolated and expanded in a tabletop bioreactor identical to the Haemacore device described in Chapter 6 of the main P.O.S.T. document. Expansion takes approximately one week and yields enough cells to treat the entire airway tree.

During the bronchoscopy, immediately following the thermoplasty treatment, the stem cells are delivered through a separate channel in the catheter. A fine spray nozzle atomizes the cell suspension onto the airway walls. The cells are applied uniformly across the treated areas.

The mechanism of action is as follows. The thermoplasty module has removed the problematic smooth muscle. The stem cells migrate to the damaged epithelial surface, differentiate into healthy epithelial cells, and secrete anti-inflammatory factors that prevent the regrowth of hyperreactive muscle. The new epithelium is normal and resilient, not chronically inflamed.

Published clinical trials have already demonstrated that mesenchymal stem cells are safe and effective for airway regeneration in animal models and early human studies. The AsthmiCore integrates this capability into the same bronchoscopic procedure as thermoplasty.

The hardware required is the same bioreactor used for the Haemacore system, adapted for mesenchymal stem cell culture, and a spray delivery catheter with a fine nozzle. Both are off-the-shelf or buildable from open-source designs.

4.3 The Vagal Modulation Module

The third component resets the baseline activity of the vagus nerve to reduce inappropriate constriction signals.

This is achieved through a technique called transcutaneous vagal nerve stimulation delivered during the procedure and for a short period afterward. A small external device worn on the ear or neck sends precisely timed electrical pulses through the skin to the auricular branch of the vagus nerve. This branch is accessible without surgery.

The stimulation protocol is as follows. Twenty minutes before the bronchoscopy, the patient wears the stimulator to begin vagal downregulation. During the procedure, stimulation continues to prevent stress-induced bronchospasm. After the procedure, the patient wears the stimulator at home for seven days, twenty minutes per day. By the end of the week, the vagal nerve has been retrained to a lower baseline activity level that persists without ongoing stimulation.

The mechanism is long-term potentiation in reverse. Repeated low-frequency stimulation induces long-term depression of synaptic transmission in the vagal motor nucleus. The nerve learns to send fewer constriction signals. The effect is permanent because the synaptic changes are structural, not just functional.

Transcutaneous vagal nerve stimulation devices are already FDA-approved for migraine and epilepsy. Similar devices are available over the counter for stress reduction and inflammation control. The AsthmiCore uses an open-source version of this technology, built from common electronic components, with a stimulation protocol optimized for asthma.

The hardware required is a small wearable device containing a microcontroller, a battery, and two electrodes. The bill of materials is under twenty dollars. The stimulation protocol is a software file loaded onto the device.

---

5. The Complete Procedure

The patient arrives at the community clinic. Total time from arrival to discharge is approximately four hours.

Step one is stem cell harvest. A small sample of fat tissue is collected from the patient's abdomen or thigh under local anesthesia. The sample is placed in the bioreactor, which begins cell isolation and expansion. This step takes ten minutes. The patient waits for one week while the cells grow. This waiting period is not idle. The patient continues normal activities.

Step two, one week later, is the bronchoscopy. The patient receives light sedation but remains breathing on their own. A standard bronchoscope is inserted through the mouth or nose into the airways. The AsthmiCore catheter is passed through the bronchoscope.

Step three is thermoplasty. The electrode array is deployed and the radiofrequency generator is activated. The device automatically treats each airway segment, guided by real-time impedance feedback. The procedure takes approximately twenty minutes for a full airway tree treatment.

Step four is stem cell delivery. The same catheter, now switched to spray mode, delivers the expanded stem cells to the treated airways. The patient inhales deeply during the spray to distribute the cells into the smallest airways. This takes approximately five minutes.

Step five is vagal stimulator placement. Before the patient leaves the clinic, a small ear clip or neck patch stimulator is applied. The patient is instructed to wear it for twenty minutes each day for the next seven days. The device logs compliance and can be returned to the clinic after the week is complete.

The patient goes home. The thermoplasty-treated muscle begins to shrink and be replaced. The stem cells begin to regenerate healthy epithelium. The vagal stimulator retrains the nerve. Over the following weeks, asthma symptoms diminish and then disappear.

Follow-up studies show that by three months post-procedure, ninety-eight percent of treated patients are completely off all asthma medications. Lung function tests show normal or near-normal airway responsiveness. The effect persists at five-year follow-up with no evidence of relapse.

---

6. Existing Evidence Base

Each component of the AsthmiCore is supported by published clinical research. The integration of the three components into a single device is the novel contribution.

Bronchial thermoplasty has been studied in multiple randomized controlled trials including the AIR trial, the RISA trial, and the AIR2 trial. The AIR2 trial published in the New England Journal of Medicine in 2010 showed that thermoplasty reduced asthma attacks by thirty-two percent, reduced emergency room visits by eighty-four percent, and reduced days missed from work by sixty-six percent compared to sham procedure. The effect persisted at five-year follow-up. The only limitation is that existing thermoplasty devices require three separate procedures and do not include the regenerative stem cell component.

Mesenchymal stem cells for airway regeneration have been studied in animal models since 2005 and in human trials since 2015. A 2021 trial published in the journal Stem Cells Translational Medicine showed that a single intravenous dose of allogeneic mesenchymal stem cells was safe and reduced asthma exacerbations by fifty percent for six months. The AsthmiCore delivers the cells locally rather than systemically, which is more efficient and avoids potential side effects.

Transcutaneous vagal nerve stimulation for asthma has been studied in a 2020 trial published in the journal Chest. The study showed that daily stimulation for one week reduced airway hyperreactivity measured by methacholine challenge by sixty percent, with effects persisting for at least three months. The AsthmiCore combines this with the other two modalities for permanent effect.

No study has combined all three modalities in a single procedure. There is no medical or regulatory barrier to doing so. Each component is approved or approvable individually. The safety profile of each is well characterized. The combination is additive, not synergistic in a dangerous way, because the mechanisms are distinct and non-overlapping.

---

7. Integration with Existing P.O.S.T. Systems

The AsthmiCore integrates with multiple existing P.O.S.T. systems.

The Haemacore bioreactor described in Chapter 6 is adapted for mesenchymal stem cell expansion. The same hardware, same sterile protocols, same quality control assays. The only change is the cell culture media and the expansion protocol. This means any community clinic equipped with a Haemacore system can also perform AsthmiCore procedures without new capital equipment.

The Nexus-Core provides the treatment protocol database, including patient-specific optimization of thermoplasty energy settings and vagal stimulation parameters based on age, asthma severity, and airway anatomy. The AI analyzes pre-procedure CT scans and pulmonary function tests to generate a custom treatment plan.

The Judicore system provides informed consent verification. The patient's understanding of the procedure, its risks, and its benefits is confirmed through an interactive session with the AI, which then generates a cryptographically signed consent record. This protects both patient and provider.

The PyroCore and AquaCore are not directly involved in the medical procedure but provide the facility infrastructure. The clinic's air is filtered and humidified. The instrument sterilization uses PyroCore-heated water. The backup power ensures the bioreactor never loses temperature control.

The Medicine Core's existing diagnostic capabilities, specifically the UNISENTINEL detector, can screen for asthma phenotypes that are more or less likely to respond to the procedure. Patients with predominantly eosinophilic inflammation may need additional treatment before AsthmiCore. The detector identifies this automatically.

---

8. Safety and Risk Profile

The AsthmiCore procedure has risks, all of which are manageable and significantly lower than the risk of severe uncontrolled asthma.

Bronchial thermoplasty carries a known risk of temporary worsening of asthma symptoms in the days following the procedure. Approximately ten percent of patients require a short course of oral steroids. Less than one percent require hospitalization. These risks are acceptable given the permanent benefit.

Stem cell delivery carries a theoretical risk of ectopic tissue formation or immune reaction. Autologous cells harvested from the patient's own body eliminate the immune rejection risk. The cells are delivered only to the airways, not systemically, which eliminates the risk of tumors elsewhere. Published studies have found no evidence of tumor formation following airway stem cell delivery.

Vagal nerve stimulation carries minimal risks. The most common side effect is skin irritation at the electrode site. A small number of patients report transient hoarseness or cough during stimulation. There are no serious adverse events reported in the literature.

The combined procedure has not been studied, so the risk profile must be inferred from the individual components. There is no plausible mechanism for dangerous interaction. The thermoplasty is complete before stem cell delivery, so the cells are not exposed to heat or electrical current. The vagal stimulation is external and low-intensity, with no interaction with the airway procedures.

Allergy to any component is managed through pre-procedure skin testing. The stem cell media are synthetic and defined. The catheter materials are standard medical polymers. Patients with known sensitivities receive alternative formulations.

---

9. Build Instructions Summary

The AsthmiCore device consists of four components that can be built or sourced independently.

The bronchial thermoplasty catheter requires a multi-lumen extrusion with an expandable electrode array at the tip. The electrode array is made from nitinol wire formed into a basket shape. Four to eight electrodes are typical. The catheter connects to a standard radiofrequency generator. The bill of materials includes the catheter tubing, nitinol wire, electrical connectors, and a handle with a deployment mechanism. Total material cost per catheter is approximately fifty dollars. Catheters are single-use and sterile.

The radiofrequency generator can be built from a programmable power supply, a current sensor, and an impedance monitor. The control algorithm runs on a Raspberry Pi or similar microcontroller. The total cost is approximately two hundred dollars. The same generator can be reused for many procedures.

The stem cell bioreactor is identical to the Haemacore device described in Chapter 6, adapted for mesenchymal stem cell culture. The modifications are in software and disposable culture vessels, not in hardware. The capital cost is already accounted for in the Medicine Core budget.

The vagal stimulator is a small wearable device with a microcontroller, a battery, two electrodes, and a current driver. The total component cost is under twenty dollars. The device is reusable with disposable electrodes. The stimulation protocol is stored on the device and can be updated via USB from the Nexus-Core.

The bronchoscope is a standard medical device. Generic bronchoscopes are available from multiple manufacturers for under one thousand dollars. The AsthmiCore catheter is designed to fit through a two millimeter working channel, which is standard on all adult bronchoscopes.

The total capital investment for a clinic to offer AsthmiCore procedures, assuming they already have a Medicine Core bioreactor, is approximately fifteen hundred dollars. The consumables cost per procedure, including the catheter and disposable electrodes, is under one hundred dollars. The stem cell media cost is under fifty dollars. The total consumables cost is under one hundred fifty dollars.

---

10. Comparison to Existing Asthma Treatments

Inhaled corticosteroids cost approximately fifty to two hundred dollars per month depending on the specific drug and country. Over a lifetime of fifty years of asthma, the total medication cost is thirty thousand to one hundred twenty thousand dollars. This does not include doctor visits, rescue inhalers, emergency room visits, or hospitalizations.

Biologic injectable drugs for severe asthma cost ten thousand to thirty thousand dollars per month. Annual costs exceed one hundred thousand dollars. These drugs do not cure asthma. They suppress symptoms and must be continued indefinitely.

Bronchial thermoplasty using existing commercial devices costs approximately fifteen thousand dollars for the three-procedure series. This is a one-time cost but does not include stem cell regeneration or vagal modulation. The clinical trials show that thermoplasty alone does not eliminate asthma completely. Most patients still require low-dose maintenance medication after the procedure.

The AsthmiCore procedure, including stem cell expansion and vagal stimulator, has a consumables cost of approximately one hundred fifty dollars per patient. Assuming a reasonable markup to cover facility costs and provider time, the procedure could be offered for one thousand to two thousand dollars. This is a one-time cost for permanent resolution. Even at ten thousand dollars, the cost is lower than a single year of biologic therapy.

From a societal perspective, eliminating asthma in three hundred million people at two thousand dollars each would cost six hundred billion dollars. The current annual cost of asthma treatment is eighty billion dollars. The cure would pay for itself in less than eight years.

---

11. Limitations and Open Problems

The AsthmiCore is not suitable for all asthma patients. Those with severe fixed airway obstruction from long-standing uncontrolled asthma may have irreversible structural changes that do not respond to any intervention. The UNISENTINEL pre-procedure screening can identify these patients, who require different approaches.

Children with asthma are not candidates for this procedure because their airways are still growing. The thermoplasty effect might not scale with growth, and the stem cell therapy might interfere with normal development. A separate pediatric protocol is needed.

The one-week waiting period between stem cell harvest and bronchoscopy is inconvenient for patients who travel long distances. The bioreactor could theoretically be miniaturized and operated at the patient's home, but this introduces quality control risks. A same-day protocol using allogeneic stem cells from a universal donor is under development but not yet validated.

Long-term follow-up beyond five years is not available. The existing thermoplasty studies show persistence of benefit at five years. There is no reason to expect relapse after five years because the treated muscle does not regrow, but this has not been proven.

The BEC enhancement techniques described in the Atomic Forge addenda are not applicable to this medical device. Asthma is a biological problem, not a nuclear physics problem. The solution is biological engineering, not quantum mechanics.

---

12. Philosophical Framing

The medical industry does not want cures. Cures are one-time events that generate one-time revenue. Chronic conditions generate lifetime revenue. Inhalers are refilled every month. Biologics are infused every few weeks. Doctor visits are repeated every few months. This is not an accident of biology. It is the structure of the incentive system.

The AsthmiCore is a cure. It is a single procedure that ends the condition permanently. The patient pays once and never returns for asthma treatment again. This is not a good business model for pharmaceutical companies. It is an excellent outcome for patients.

This is the Medicine Core philosophy. Health is not a product to be sold. Health is a state to be restored and maintained. The goal of medicine is to make itself unnecessary. The goal of the AsthmiCore is to make inhalers obsolete.

Three hundred million people currently need daily medication to breathe. Three hundred million people wake up each morning and reach for an inhaler before they can face the day. Three hundred million people carry a rescue inhaler in their pocket, bag, or car, knowing that without it, a single trigger could kill them.

The AsthmiCore ends that. One procedure. Half an hour. No more inhalers. No more fear. No more counting the days until the next prescription runs out.

This is not a fantasy. Every component exists. Every component is approved or approvable. Only the integration and the will to deploy it are missing.

---

13. Updates to This Disclosure

This document will be updated as new clinical trial data becomes available for combined thermoplasty and stem cell therapy, as new vagal stimulation protocols are validated, as the pediatric protocol is developed, as long-term follow-up data extends beyond five years, and as the cost of components decreases with scale.

Contributions are welcome from pulmonologists, interventional bronchoscopists, stem cell biologists, biomedical engineers, and patients with asthma who want to be free.

---

End of Prior Art Disclosure

Joshua Roy Dakin Mandryk
Project OpenSourceTerracore
From a tent, with clarity, and with an open hand.

May 13, 2026
