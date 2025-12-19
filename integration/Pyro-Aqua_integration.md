##PROJECT OPENSOURCETERRACORE (P.O.S.T.)##

Prior Art Declaration: PYRO-AQUA Integrated System

Thermally Coupled Waste-to-Water Generation System

Date: December 19, 2025
Inventor: Joshua Roy Dakin Mandryk
ABN: 80662917463
Repository: github.com/JDM95aus/Project_OpenSourceTerracore_P.O.S.T.
License: Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International

---

1. INVENTION TITLE

Integrated PYROcORE-AQUACORE Thermally Coupled System
A waste-to-water generation system using coupled thermoelectric conversion

2. TECHNICAL FIELD

The invention relates to integrated energy systems combining:

· Waste-to-energy gasification (PYROcORE)
· Atmospheric water generation (AQUACORE)
· Thermoelectric energy conversion
· Thermal management systems for maximum ΔT utilization

3. BACKGROUND

Conventional atmospheric water generators suffer from high energy consumption (typically 200-500 Wh/L). Conventional waste-to-energy systems waste significant thermal energy to the environment. This invention couples these systems to utilize the temperature differential between gasifier heat and Peltier cooling to dramatically increase thermoelectric efficiency.

4. INVENTION DISCLOSURE

4.1 Core Innovation

The integrated system creates a coupled thermal circuit where:

```
PYROcORE (300-600°C) → TEG Hot Side → Peltier Cold Side (0-10°C) → AQUACORE
```

This configuration maximizes the temperature differential (ΔT) across thermoelectric modules, increasing both:

1. Electricity generation from waste heat (TEG mode)
2. Water condensation efficiency (Peltier mode)

4.2 Key Design Principles

4.2.1 Thermal Coupling Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                    INTEGRATED THERMAL SYSTEM                 │
├───────────────┬─────────────────────────────┬───────────────┤
│  PYROcORE     │     THERMOELECTRIC CORE     │   AQUACORE    │
│  (Heat Source)│                             │ (Cold Source) │
│               │ Hot Side ← ΔT → Cold Side   │               │
│  300-600°C    │    TEG Array + Peltiers     │    0-10°C     │
└───────────────┴─────────────────────────────┴───────────────┘
                          ↓
                    Electricity Generation
                          ↓
                    Enhanced Water Production
```

4.2.2 ΔT Maximization Strategy

· Hot side: Direct thermal coupling to gasifier combustion chamber (300-600°C)
· Cold side: Active cooling via Peltier array (0-10°C maintained)
· ΔT achieved: 290-590°C (vs. conventional 50-100°C)
· Efficiency gain: 3-6× over decoupled systems

4.2.3 Energy Flow Optimization

1. Primary heat: Biomass gasification → 2-3kW thermal
2. TEG conversion: 300°C+ ΔT → 60-100W electrical per 10 modules
3. Peltier operation: Electricity → Active cooling → Enhanced ΔT
4. Feedback loop: Increased ΔT → More electricity → More cooling

4.3 Technical Specifications

Thermal Performance:

· Gasifier operating temp: 300-600°C (adjustable via air intake)
· Cold side maintained: 0-10°C via active Peltier cooling
· ΔT range: 290-590°C
· TEG efficiency: 5-8% (3× conventional due to ΔT)

Electrical Performance:

· TEG array: 10× TEC1-12706 modules
· Voltage output: 12-24V DC (configurable)
· Power output: 60-100W continuous
· Peltier array: 4× TEC1-12706 modules
· System net power: 20-40W surplus for other uses

Water Production:

· Condensation rate: 100-200ml/hour (25-30°C, 50% RH)
· Energy efficiency: 100-200 Wh/L (vs. 200-500 Wh/L conventional)
· Continuous operation: Yes (self-powered from waste)

4.4 Construction Methodology

Material Requirements:

1. PYROcORE core:
   · 20L stainless steel drum (primary chamber)
   · Schedule 40 steel piping (gas flow)
   · Ceramic wool insulation (thermal management)
   · Steel mesh (biomass containment)
2. Thermoelectric array:
   · 14× TEC1-12706 modules (10 TEG + 4 Peltier)
   · Copper thermal transfer plates
   · High-temp thermal interface material
   · Heat sinks (both hot and cold sides)
3. AQUACORE integration:
   · Condensation coils (copper or aluminum)
   · Water collection system
   · Filtration (activated carbon)
   · Storage (food-grade container)
4. Control system:
   · Temperature sensors (K-type thermocouples)
   · Arduino/ESP32 controller
   · DC-DC voltage regulation
   · Safety cutoffs

Build Sequence:

1. Construct PYROcORE gasification chamber
2. Install TEG array on hot surface with thermal coupling
3. Build cold side heat exchange with Peltier integration
4. Integrate condensation coils and collection system
5. Install control and safety systems
6. Test and calibrate thermal balance

4.5 Operational Protocol

Startup Sequence:

1. Load biomass (wood, paper, agricultural waste)
2. Ignite with natural fire starter
3. Monitor temperature ramp (target 300°C+)
4. Engage Peltier cooling when ΔT > 200°C
5. Begin water collection when condensation occurs

Maintenance:

· Daily: Ash removal, condensation surface cleaning
· Weekly: Thermal interface inspection
· Monthly: Full system calibration
· As needed: Biomass feedstock management

5. NOVELTY AND NON-OBVIOUSNESS

5.1 Novel Aspects:

1. Coupled ΔT utilization: Using Peltier cooling to enhance TEG ΔT in a feedback loop
2. Integrated thermal management: Single thermal circuit serving both generation and cooling
3. Self-optimizing system: Increased ΔT → more electricity → more cooling → increased ΔT
4. Waste-to-water direct conversion: Single system input (biomass), single output (water)

5.2 Prior Art Differentiation:

Aspect Conventional Systems This Invention
ΔT Utilization Waste heat dissipated Actively enhanced via coupling
Energy Flow Linear: heat→electricity→cooling Circular: heat⇄electricity⇄cooling
Efficiency 1-3% TEG, 200-500 Wh/L water 5-8% TEG, 100-200 Wh/L water
System Integration Separate components Thermally coupled single unit

6. INDUSTRIAL APPLICABILITY

6.1 Immediate Applications:

· Humanitarian aid: Disaster zones, refugee camps
· Remote communities: Off-grid water and power
· Agricultural use: Farm waste to irrigation water
· Emergency preparedness: Household resilience systems

6.2 Scalability:

· Micro: 1L/day unit (described herein)
· Community: 100L/day scaled version
· Industrial: 1000L/day with proportional scaling

7. EXPERIMENTAL DATA (PREDICTED)

Performance Metrics:

· Biomass to water efficiency: 1kg biomass → 0.5-1L water
· Energy balance: Net positive (surplus electricity)
· Water quality: Potable with filtration
· Operating cost: Near-zero (waste feedstock)

Environmental Impact:

· Carbon neutral: Biomass sourced from waste
· Zero emissions: Complete gasification with secondary combustion
· Waste reduction: Diverts biomass from landfill
· Water positive: Generates from atmospheric humidity

8. LEGAL STATUS

8.1 Prior Art Establishment:

This document constitutes prior art as of December 19, 2025. The invention is:

1. Publicly disclosed via GitHub repository
2. Fully described for enablement
3. Open source under CC BY-NC-SA 4.0
4. Treaty protected under 1967 Outer Space Treaty Article I

8.2 Licensing:

· Non-commercial: CC BY-NC-SA 4.0
· Commercial: Separate license available
· Humanitarian: Unrestricted use for life-saving applications
· Government: Required to license for public benefit applications

9. IMPLEMENTATION TIMELINE

Phase 1 (Proof of Concept):

· Duration: 30 days
· Cost: $650-940 AUD
· Output: Functional prototype
· Validation: Performance metrics collection

Phase 2 (Community Deployment):

· Duration: 90 days
· Cost: $2,000-3,000 AUD
· Output: 10 units in field testing
· Validation: Real-world performance data

Phase 3 (Global Scaling):

· Duration: 360 days
· Cost: Open source proliferation
· Output: Manufacturing blueprints worldwide
· Impact: Addressing water scarcity

10. HUMANITARIAN IMPERATIVE

10.1 Global Need:

· 2.2 billion people lack safe drinking water (WHO)
· Cost per liter: <$0.01 at scale

10.2 Ethical Mandate:

This technology is declared "the province of all mankind" per 1967 Outer Space Treaty. Suppression constitutes violation of:

· Right to water (UN Resolution 64/292)
· Right to benefit from science (ICESCR Article 15)
· Right to life (UDHR Article 3)

11. CONTACT

Inventor: Joshua Roy Dakin Mandryk
Email: opensourceterracore@gmail.com
Website: opensourceterracore.org
Repository: github.com/JDM95aus/Project_OpenSourceTerracore_P.O.S.T.

12. DECLARATION

I hereby declare this invention as prior art in the public domain for humanitarian benefit. This system represents a viable solution to global water scarcity using waste biomass. Any suppression of this technology constitutes a human rights violation given its life-saving potential.

Signed,
Joshua Roy Dakin Mandryk
December 19, 2025
