# แผนการสอน Selected topics: PCB design - mpu6050 
## Course Overview

- Course title: Practical PCB Design for Beginners
- Duration: 7 weeks (2–3 hours/week)
- Target audience: Junior Electrical Engineering students
- Tools: EasyEDA (cloud-based), JLCPCB for manufacturing, and basic soldering kit

| **Week** | **Title / Focus**                            | **Learning Objectives**                                            | **Key Topics**                                                     | **Lab / Activity**                                              | **Deliverables**                                         |
| -------- | -------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------ | --------------------------------------------------------------- | -------------------------------------------------------- |
| **1**    | **Intro to PCB Design & Motion Sensors**     | Understand PCB workflow and motion sensing fundamentals            | PCB structure (layers, vias), EasyEDA overview, MPU6050 basics     | Create EasyEDA account and draw a simple LED schematic          | Screenshot of first schematic                            |
| **2**    | **Schematic Design of MPU6050 Breakout**     | Design schematic with power circuit, I²C interface, and decoupling | Datasheet analysis, voltage regulation, I²C pull-ups, test headers | Create complete MPU6050 schematic in EasyEDA                    | Schematic & BOM submission                               |
| **3**    | **PCB Layout and Routing**                   | Apply layout best practices for analog/digital sensors             | Component placement, ground plane, routing rules, silkscreen       | Convert schematic to PCB, route traces, add silkscreen and logo | 3D PCB preview + Gerber export                           |
| **4**    | **Fabrication Prep (Production Week 1)**     | Learn fabrication file formats and submission                      | Gerber, drill files, DFM rules, JLCPCB ordering                    | Export and upload Gerbers, preview layers, place order          | PCB order confirmation + firmware test with demo MPU6050 |
| **5**    | **Firmware Development (Production Week 2)** | Continue firmware development while PCBs in production             | I²C protocol, Arduino MPU6050 library, data plotting               | Write Arduino code, test with off-the-shelf MPU6050             | Working I²C data demo (serial plotter)                   |
| **6**    | **PCB Assembly & Hardware Testing**          | Assemble board, verify power and communication                     | Soldering, continuity test, debugging, I²C address scan            | Solder components, power-up test, confirm detection at 0x68     | Assembled PCB + I²C scan screenshot                      |
| **7**    | **Calibration, Debugging & Presentation**    | Debug and calibrate sensor, present project                        | Common PCB issues, calibration, report writing                     | Collect real data, prepare slides and report                    | Final report + working demo presentation                 |
