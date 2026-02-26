# Dynamo-Powered Bicycle Safety Light

**Project Type:** Schematic Design & PCB Layout (OrCAD)
**Hardware:** CD4093 (CMOS Logic), BC556 Transistor, NiCd Battery, Relays, THT/SMD Components

##  Project Overview
This project involves the end-to-end design of a smart, dynamo-powered safety flashing light for bicycles. The circuit ensures rider visibility not only while moving but also when stopped at traffic lights. 

It utilizes a dynamo to charge a 4.8V NiCd battery during motion. Once the bicycle stops, a timer circuit takes over, keeping the rear lights flashing for approximately 4 minutes before automatically shutting down to preserve battery life.

##  Technical Specifications & Features
* **Power Supply:** Bicycle dynamo coupled with a voltage doubler (C1, C2, D1, D2) to efficiently charge the backup battery.
* **Logic Control:** Implemented using a **CD4093** (Quad 2-Input NAND Schmitt Trigger) to detect motion and generate the timing/flashing logic.
* **Standlight Function:** Maintains flashing illumination for exactly 4 minutes post-stop.
* **Battery Protection:** Auto-shutdown feature to prevent deep discharge of the NiCd battery.

##  PCB Layout Specifications
The Printed Circuit Board was meticulously designed to meet strict industrial constraints:
* **Layers:** 2-Layer Board (Top & Bottom). All components placed on the Top layer.
* **Dimensions:** 50 mm x 50 mm footprint with diagonal mounting holes.
* **Routing Constraints:** * Signal traces: 0.2 mm width.
  * Power/High-current traces: 1.2 mm width.
  * Clearance: 0.35 mm minimum spacing.
* **Grounding:** Implementation of a Dynamic Copper Ground Plane on the Bottom layer to minimize noise.
* **Deliverables:** Generated full Gerber files, NC Drill data, and Assembly drawings.



## 📂 Repository Structure
* **/Docs:** Full technical documentation and design constraints.
* **/Datasheets:** Component specifications (CD4093, Relays, etc.).

---
*Project developed by David-Gabriel Popescu, Student at the National University of Science and Technology Politehnica Bucharest, Faculty of Electronics (ETTI).*
