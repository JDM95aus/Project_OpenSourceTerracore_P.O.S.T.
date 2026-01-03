# CORE DESIGN PRINCIPLES:
Cold Side: Use multiple Peltier chips on a single, massive copper cold plate for uniform cooling.

Heat Sink: Use active water cooling for the hot side. This is MORE efficient than air cooling for moving large amounts of heat. It allows the Peltiers to run at maximum power without throttling.

Condensation Surface: Use a dedicated, finned aluminum radiator (like a car heater core) as the cold-side heat exchanger. This gives us maximum surface area for condensation.

Airflow: Use high-CFM (Cubic Feet per Minute) fans to move maximum air volume across the cold radiator.

# BILL OF MATERIALS (BOM) - Performance Focused
Part	Purpose	Recommended Spec	Est. Cost (AUD)	Why This Choice
Peltier Modules	Primary cooling	4x TEC1-12706 (40x40mm)	$20	Four chips share the load, run cooler, more reliable.
Cold Plate	Spread cold evenly	150x150x10mm Copper Plate	$40	Copper transfers cold 4x better than aluminum. Critical for multi-Peltier setup.
Cold Side Radiator	Condensation surface	120mm x 240mm Aluminum Heater Core	$25 (junkyard)	Massive surface area, designed for heat/air exchange.
Hot Side Cooler	Remove waste heat	CPU AIO Water Cooler (120mm)	$50 (used)	Actively pumps heat away. Far more effective than any air cooler.
Fans (x2)	Move air through radiator	120mm, >70 CFM each	$25	High static pressure to push air through dense fins.
Thermal Paste	Interface material	High-performance (Arctic MX-6)	$10	Better paste = better heat transfer = more water.
Power Supply	Run the system	12V 30A (360W) Switching PSU	$50	Provides clean, stable power at high amperage.
Microcontroller	Brain	Raspberry Pi Pico W	$10	Controls fans based on sensor data.
Sensors	Feedback	DHT22 (Temp/Humidity)	$10	Monitors ambient and output conditions.
Insulation	Prevent thermal leakage	Closed-cell foam sheets	$15	Isolates cold side from hot side and ambient air.
Piping/Reservoir	Water cooling loop	Tubing, fittings, reservoir	$30	Completes the water cooling circuit.
Frame	Structure	2020 Aluminum Extrusion	$40	Rigid, modular, professional.
Misc	Wires, bolts, sealant	-	$25	-
**TOTAL			≈ $350 AUD**	
# ASSEMBLY BLUEPRINT:
Step 1: The Core "Cold Block"

Thermal Epoxy the 4 Peltier chips in a 2x2 grid onto the Copper Plate. Ensure perfect flat contact.

Thermal Paste and bolt the Hot Side of the Peltiers to the CPU Water Cooler's cold plate.

Thermal Paste and bolt the Cold Side Radiator (Heater Core) to the Copper Plate.

Insulate the entire assembly so only the cold radiator fins are exposed to air.

Step 2: The Air System

Mount the Cold Block vertically in the 2020 frame.

Mount one high-CFM fan on each side of the radiator in a "push-pull" configuration.

Design a simple duct (can be cardboard for MVP) to ensure all air passes through the radiator.

Step 3: The Water Cooling Loop

Connect the CPU Water Cooler to a reservoir and pump.

Fill with distilled water + biocide.

The reservoir can be a simple bucket. The goal is to move heat from the Peltiers into this water mass.

Step 4: Brain & Sensors

Mount the Raspberry Pi Pico W and DHT22 sensor.

Program it to:

Read ambient temp/humidity.

Control fan speed (PWM) based on humidity (higher humidity = higher fan speed).

Log data to a simple text file or display.

Safety: Shut down if the cold radiator approaches 0°C (to prevent freezing/ice).

Step 5: Collection

Place a food-grade plastic tray at the bottom of the cold radiator.

Angle it towards a collection spout with a tube leading to a 5L water jug.
