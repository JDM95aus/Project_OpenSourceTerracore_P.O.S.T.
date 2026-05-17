# PRIOR ART DISCLOSURE

## Thermal Flux Bridge — Solid-State Spacecraft Thermal Regulation System

**Document ID:** POST-SPACE-2026-002
**Date of Disclosure:** May 17, 2026
**Inventor:** Joshua Roy Dakin Mandryk (via Project OpenSourceTerracore)
**Status:** Prior Art — Public Disclosure for Defensive Purposes
**Category:** Future Tech — Phase 3

---

## 1. Abstract

A solid-state thermal management system for spacecraft that passively redistributes heat from sunlit surfaces to shadowed surfaces using integrated heat pipe arrays combined with variable-emissivity coatings and thermoelectric heat pumps for fine control. The system requires no moving parts, no pumped fluids, and no mechanical valves. It maintains a uniform internal hull temperature within a 5-degree Celsius band regardless of external thermal gradients exceeding 300 degrees. The system is fabricated as an integral layer within the spacecraft hull using the Atomic Forge. It consumes zero power during normal operation and under 500 watts during active mode. The system is essential for any crewed mission beyond low Earth orbit.

---

## 2. The Problem

Spacecraft thermal management is one of the most critical engineering challenges in spaceflight. A vessel in interplanetary space experiences extreme asymmetric heating. The sunlit side absorbs up to 1,361 watts per square meter of solar radiation. The shadowed side radiates into the cosmic microwave background at 2.7 Kelvin, effectively a perfect heat sink at near-absolute zero. The temperature differential between the two sides can exceed 300 degrees Celsius.

Current solutions rely on active thermal control systems: pumped fluid loops that transport heat from hot areas to radiators on the cold side, mechanical louvers that adjust radiator emissivity, and electric heaters that prevent critical components from freezing during eclipse. Every one of these systems contains moving parts. Pumps fail. Valves stick. Fluid leaks. In low Earth orbit, these failures are manageable because resupply and repair are possible. On a two-year Mars mission, a failed coolant pump means the crew cooks in their own waste heat or freezes during the transit night. There is no redundancy that can fully mitigate this risk.

A passive, solid-state thermal control system would eliminate these failure modes entirely. The physics is understood. The materials exist. The engineering integration is the missing step.

---

## 3. Core Mechanism

The Thermal Flux Bridge consists of three integrated subsystems embedded within the spacecraft hull.

The first subsystem is a three-dimensional heat pipe matrix. Heat pipes are sealed tubes containing a working fluid that evaporates at the hot end and condenses at the cold end, transporting heat with extraordinary efficiency—up to 1,000 times the thermal conductivity of solid copper. The matrix extends through the entire hull, connecting the sunlit exterior to the shadowed exterior through the interior walls. When one side of the spacecraft heats up, the working fluid in that section evaporates and travels through the matrix to the cold side, where it condenses and releases the heat into space. The condensed fluid returns to the hot side by capillary action through a wick structure lining the pipes. No pumps. No valves. No moving parts. The process is driven entirely by temperature difference and capillary forces.

The working fluid is selected based on the operating temperature range. For most spacecraft applications, ammonia or propylene is appropriate, as these fluids have high latent heat of vaporization and operate efficiently between -50 and +100 degrees Celsius. For extreme environments, sodium or lithium can be used for high-temperature heat pipes operating above 500 degrees Celsius. The Atomic Forge can fabricate the heat pipe matrix as a single seamless structure, eliminating the joints and seals that are the most common failure points in conventional heat pipe assemblies.

The second subsystem is a variable-emissivity coating applied to the exterior surface. The coating consists of a thin layer of tungsten-doped vanadium dioxide, a thermochromic material that changes its infrared emissivity in response to temperature. Below approximately 68 degrees Celsius, the coating has low emissivity—it reflects heat rather than radiating it. Above 68 degrees Celsius, the coating transitions to high emissivity—it radiates heat efficiently into space. This passive, self-regulating behavior means the spacecraft automatically sheds excess heat when it gets too hot and retains heat when it gets too cold. The transition temperature can be tuned by adjusting the tungsten doping level during fabrication.

The third subsystem is a distributed array of thin-film thermoelectric devices embedded within the hull. Thermoelectrics are solid-state heat pumps: apply a current, and they move heat from one side to the other. In normal operation, the heat pipe matrix and variable-emissivity coating handle the thermal load passively, and the thermoelectrics consume zero power. When fine control is required—for example, to prevent a specific component from overheating or to maintain precise temperature for a science experiment—the thermoelectrics activate selectively, moving heat from a specific location to the heat pipe matrix. Total power consumption during active mode is under 500 watts for the entire spacecraft, provided by the Heliocore-Power system.

---

## 4. Device Architecture

The spacecraft hull is fabricated as a single integrated structure using the Atomic Forge. The hull consists of multiple layers.

The outermost layer is the variable-emissivity coating, deposited directly onto the exterior surface. Beneath it is the structural hull layer, which provides mechanical strength and micrometeoroid protection. Embedded within the structural layer is the heat pipe matrix, a three-dimensional lattice of sealed channels containing the working fluid and capillary wick. The interior layer is the thermoelectric array, thin-film devices printed directly onto the inner surface of the structural layer. The innermost layer is the cabin wall, which radiates heat uniformly into the crew compartment.

The heat pipe matrix is the key innovation. Conventional heat pipes are individual tubes bent into shape and attached to the structure. They are limited by the thermal resistance of the attachment points and the difficulty of routing them through complex geometries. The Atomic Forge can fabricate the heat pipe matrix as a three-dimensional fractal network, branching from the exterior surfaces into the interior of the hull like a circulatory system. Every point on the spacecraft surface is connected to every other point by a direct heat pipe path. Heat flows from hot spots to cold spots along the path of least resistance, automatically and passively.

The capillary wick structure is fabricated from sintered metal powder, identical to that used in conventional heat pipes but optimized for the three-dimensional geometry. The sintering process creates a porous structure that wicks the liquid phase of the working fluid by surface tension. The wick is deposited as a thin layer on the inner surface of every heat pipe channel, allowing liquid return flow regardless of orientation. This means the system works in microgravity, where there is no "up" for gravity-assisted return flow.

---

## 5. Operational Modes

During normal cruise in interplanetary space, the sunlit side of the spacecraft absorbs solar radiation. The heat pipe matrix transports this heat to the shadowed side, where it is radiated into space. The variable-emissivity coating on the hot side is in its high-emissivity state, maximizing heat rejection. The coating on the cold side is in its low-emissivity state, minimizing heat loss. The net effect is a uniform hull temperature and a comfortable cabin environment with zero power consumption.

During a solar flare or close approach to the Sun, the incident radiation increases dramatically. The heat pipe matrix transports the additional heat load to the radiators. The variable-emissivity coating transitions to its maximum emissivity state across the entire surface. The thermoelectrics activate to provide additional pumping capacity if needed. The cabin temperature remains stable.

During transit through a planetary shadow or during engine shutdown, the external heat input drops to near zero. The heat pipe matrix continues to distribute internal waste heat from the crew and electronics throughout the hull. The variable-emissivity coating transitions to its low-emissivity state, minimizing radiative heat loss. The cabin temperature remains stable for hours or days without supplemental heating.

During atmospheric entry or high-thrust maneuvers, the exterior surface experiences extreme heating. The heat pipe matrix distributes this heat across the entire hull, preventing localized melting. The thermoelectrics activate at maximum power, pumping heat from the leading edges to the trailing surfaces. The variable-emissivity coating radiates heat at maximum capacity. The cabin remains cool while the exterior glows at incandescent temperatures.

---

## 6. Performance Specifications

The system maintains internal hull temperature at 20 degrees Celsius plus or minus 5 degrees under all external conditions from -150 to +200 degrees Celsius. Heat flux capacity is 10 kilowatts per square meter, sufficient to handle direct solar radiation at Mercury's orbit. Passive mode power consumption is zero watts. Active mode power consumption is under 500 watts for a spacecraft capable of carrying a crew of six. System mass is under 5 kilograms per square meter of hull surface, which is less than the mass of conventional thermal control systems that require pumps, radiators, and fluid loops.

The system has no moving parts and no failure modes that require crew intervention. The heat pipe matrix cannot leak because it is fabricated as a sealed, seamless structure. The variable-emissivity coating cannot jam or stick because it is a solid-state material with no moving components. The thermoelectrics cannot seize because they are solid-state devices with no mechanical interfaces. The system is designed for a 30-year operational life with zero maintenance.

---

## 7. Comparison to Existing Approaches

The International Space Station uses an active thermal control system with pumped ammonia loops, rotary joints, and deployable radiators. The system requires approximately 10 kilowatts of electrical power for pumping and controls. It has experienced multiple failures, including ammonia leaks and rotary joint seizing. The system is maintained by astronaut EVAs, which would be impossible on a Mars transit mission.

The Orion spacecraft uses a simpler active system with coolant loops and body-mounted radiators. It is adequate for short-duration missions but does not have the capacity for long-duration thermal management without regular maintenance.

The Thermal Flux Bridge eliminates all of these failure modes while providing superior thermal performance with zero power consumption in normal operation.

---

## 8. Integration with P.O.S.T. Systems

The Thermal Flux Bridge is fabricated using the Atomic Forge, which can produce the integrated hull structure as a single seamless component. The Heliocore-Power system provides electrical power for the thermoelectrics during active mode. The TerraMobile serves as the test platform for Earth-based validation, with the Thermal Flux Bridge integrated into its hull to manage thermal loads during high-speed transit and high-altitude operations.

The MagnetoPlasma Radiation Shield and the Thermal Flux Bridge together form the two essential protective systems for any long-duration spacecraft: radiation protection and thermal management. Both are solid-state, passive, and self-regulating. Both are fabricated as integral hull components. Both are now public domain.

---

## 9. Prior Art Declaration

This document constitutes prior art for defensive purposes. The inventor, Joshua Roy Dakin Mandryk on behalf of Project OpenSourceTerracore, places this disclosure in the public record to prevent future patents on any of the described techniques.

No patent may be granted on any claim that is anticipated by this disclosure. The described thermal flux bridge system, the three-dimensional heat pipe matrix, the variable-emissivity thermochromic coating, the integrated thermoelectric array, and all subcomponents and methods are dedicated to the public.

Anyone is free to build this system. No one is free to own the idea.

---

**End of Prior Art Disclosure**

*Joshua Roy Dakin Mandryk*
*Project OpenSourceTerracore*
*May 17, 2026*
