# Research Papers: Mechanical Docking & Interlocking Mechanisms

A collection of research papers exploring mechanical docking, latching, alignment and connection mechanisms for modular and self-reconfigurable robots. These papers serve as references for developing the docking interface of **T.E.T.R.I.S. (Tiny Entities That Reshape, Interlock and Snap)**, particularly for designing a connector that allows two independently moving modules to align, dock, lock, move as a connected structure and undock when required.

The focus is on understanding different mechanical coupling architectures, their actuation methods, alignment strategies, structural constraints and release mechanisms, to derive a practical connector design suitable for CAD modelling, fabrication and testing.

---

## 1. Design, Principles, and Testing of a Latching Modular Robot Connector (2014)

**Authors:** Nick Eckenstein & Mark Yim

**[Read the Paper (PDF)](https://www.modlabupenn.org/wp-content/uploads/latching_xface_overlay.pdf)**

### Overview

This paper explores the design and experimental evaluation of a latching connector for modular robotic systems. It focuses on the geometry and design principles required to establish reliable mechanical connections between robot modules while accommodating imperfections during docking.

The connector employs a passive, compliant latching mechanism, allowing modules to engage through physical interaction without requiring a dedicated active locking actuator for the latch itself. The design considers how connector geometry, engagement surfaces and mechanical compliance influence docking reliability and connection strength.

### Mechanism
- Passive, compliant mechanical latch.
- Connector geometry designed to facilitate engagement.
- Mechanical compliance helps accommodate imperfections during mating.

### What to Explore
- Connector geometry and the underlying latching principles.
- The role of compliance in tolerating docking misalignment.
- Engagement and disengagement forces.
- Connection strength and mechanical constraints.
- Experimental testing of the connector under different conditions.

### Relevance to T.E.T.R.I.S.

This is a particularly useful starting point for designing a mechanically simple and reliable docking interface. The connector principles can help develop a passive latch that is easy to fabricate, requires minimal additional actuation and can securely connect two modules during movement and reconfiguration.

---

## 2. An Active Connection Mechanism for Modular Self-Reconfigurable Robotic Systems Based on Physical Latching (2008)

**Authors:** Alexander Spröwitz, Masoud Asadpour, Yvan Bourquin & Auke Jan Ijspeert

**[Read the Paper (PDF)](https://infoscience.epfl.ch/record/130738/files/aSproewitz08.pdf)**

### Overview

This paper investigates an actively actuated physical latching mechanism for connecting and disconnecting modular self-reconfigurable robots. The mechanism is designed to provide a compact, mechanically secure connection while allowing modules to autonomously engage and release.

The design focuses on the physical latch architecture, actuation and the ability to maintain a locked connection without continuously consuming energy. Such mechanisms are particularly relevant in modular robots where connectors must be compact, reliable and integrated into the module structure.

### Mechanism
- Active physical latching mechanism.
- Actuated locking and unlocking.
- Designed to maintain the locked state without continuous energy consumption.

### What to Explore
- The latch architecture and its mechanical components.
- Actuation and release mechanisms.
- How the mechanism maintains a secure connection.
- Connector compactness and integration into robotic modules.
- Design considerations for repeated autonomous docking cycles.

### Relevance to T.E.T.R.I.S.

This paper provides a reference for designing an actuated docking mechanism that can actively lock and release modules. Its principles could be adapted to a servo-operated latch or retractable locking mechanism integrated into the docking faces of T.E.T.R.I.S., particularly if reliable autonomous undocking is a requirement.

---

## 3. A Multi-Sensory Autonomous Docking Approach for a Self-Reconfigurable Robot without Mechanical Guidance

**Platform:** UBot self-reconfigurable robot

**[Read the Paper](https://journals.sagepub.com/doi/10.5772/58867)**

### Overview

This work explores autonomous docking in a self-reconfigurable robotic system without relying on conventional physical guiding structures for alignment. The docking process uses sensing and control to achieve alignment between modules before establishing the mechanical connection.

The connector incorporates a hook-based mechanism, while the docking process relies on sensory information, including vision and Hall sensors, to guide the modules into the appropriate relative configuration.

### Mechanism
- Embedded hook-based mechanical connector.
- Sensor-assisted docking and alignment.
- Vision and Hall-sensor-based sensing approach.

### What to Explore
- The hook-based connector architecture.
- How the docking sequence is structured.
- Sensor integration for relative positioning.
- Alignment without conventional mechanical guides.
- The interaction between sensing, motion and connector engagement.

### Relevance to T.E.T.R.I.S.

This paper is useful for understanding how a hook-based connector can be combined with autonomous alignment. It provides inspiration for designing docking faces where modules approach and align using sensing, followed by mechanical engagement, rather than relying entirely on passive geometry to correct alignment.

---

## 4. A Novel Docking System for Modular Self-Reconfigurable Robots (2017)

**[Read the Paper](https://www.mdpi.com/2218-6581/6/4/25)**

### Overview

This paper proposes a docking mechanism that utilizes the existing locomotion actuators of modular robots to facilitate docking and undocking, reducing the need for a separate dedicated actuator for the docking mechanism.

The approach explores how robot motion and mechanical interaction can be used to drive the connection process. The docking mechanism and associated forces are analysed to understand the feasibility and performance of the proposed design.

### Mechanism
- Docking driven using existing locomotion actuation.
- Reduced dependence on dedicated docking actuators.
- Mechanical interaction used to facilitate connection and release.

### What to Explore
- How locomotion actuators are reused for docking.
- The mechanical geometry that enables the connection.
- Docking force analysis.
- The advantages and limitations of reducing dedicated actuators.
- The interaction between module movement and connector engagement.

### Relevance to T.E.T.R.I.S.

This is worth exploring if the modules have limited space, weight or actuator availability. Reusing existing actuators could simplify the module hardware and potentially reduce the overall complexity of the docking face, although the mechanical design and docking trajectory would need to be carefully evaluated.

---

## 5. A Reliable Docking Mechanism and Close-Range Docking Algorithm for Modular Reconfigurable Robots (2023)

**[Read the Paper](https://ieeexplore.ieee.org/abstract/document/10106592)**

### Overview

This work investigates a docking mechanism for modular reconfigurable robots, along with a close-range docking algorithm intended to improve the reliability of the docking process.

The approach combines mechanical coupling with close-range sensing and control, addressing the challenge of reliably connecting mobile modules. The mechanism is designed for modular mobile robot configurations where modules must establish a stable connection to operate as a connected structure.

### Mechanism
- Mechanical coupling for modular mobile robots.
- Close-range docking and alignment.
- Infrared-based sensing approach.

### What to Explore
- The mechanical structure of the docking interface.
- How the connector achieves a stable connection.
- Close-range alignment and docking control.
- The integration of sensing with the docking sequence.
- The reliability of docking under different approach conditions.

### Relevance to T.E.T.R.I.S.

This paper is particularly relevant to wheeled modular robots. It can provide insights into designing a compact coupling mechanism and understanding how close-range alignment and mechanical engagement can work together to achieve repeatable docking.

---

## 6. Autonomous Alignment and Docking Control for a Self-Reconfigurable Modular Mobile Robotic System (2024)

**Platform:** STORM

**[Read the Paper](https://www.mdpi.com/2218-6581/13/5/81)**

### Overview

This work studies autonomous alignment and docking within a self-reconfigurable modular mobile robotic system. It explores the relationship between module motion, alignment, docking control and the mechanical interface, with an emphasis on achieving autonomous connections between modules.

The STORM platform provides a reference for understanding the docking process as a combined mechanical and control problem rather than treating the connector as an isolated component.

### Mechanism
- Modular docking interface.
- Autonomous alignment and docking control.
- Integration of motion planning, control and docking.

### What to Explore
- The docking-interface architecture.
- Autonomous alignment strategies.
- How the robot approaches the docking configuration.
- The interaction between motion control and connector engagement.
- The overall docking sequence and its constraints.

### Relevance to T.E.T.R.I.S.

This paper can help guide the development of an autonomous docking pipeline for T.E.T.R.I.S. It is useful for understanding how the mechanical interface should be designed alongside the alignment and control algorithms to ensure that modules can reliably approach and connect.

---

## 7. Design and Dock Analysis for the Interactive Module of a Lattice-Based Self-Reconfigurable Robot (2007)

**[Read the Paper](https://doi.org/10.1016/j.robot.2006.07.006)**

### Overview

This paper investigates the design and docking mechanics of an interactive module in a lattice-based self-reconfigurable robotic system. The design incorporates mechanical features such as protruding pegs and docking holes, with rotating interfaces facilitating connections between modules.

The work examines the geometric constraints and mechanical interactions involved in docking, providing insight into how connector geometry affects engagement, structural constraints and docking forces.

### Mechanism
- Peg-and-hole mechanical connection.
- Rotating interfaces.
- Geometric constraints governing engagement.

### What to Explore
- Peg and socket geometry.
- The role of rotating interfaces in docking.
- Geometric constraints and relative motion.
- Docking-force analysis.
- The mechanical interaction between mating components.

### Relevance to T.E.T.R.I.S.

This paper is useful for studying the geometry of mating surfaces and how mechanical constraints are established when two robot modules connect. It can help guide the design of alignment features, engagement geometry and the structural arrangement of a docking face.

---

## 8. Study on Functional Extension of the Robot System by Connecting the Modular Robots: Design of the Robot Connector (2013)

**[Read the Paper](https://www.jstage.jst.go.jp/article/jsmermd/2013/0/2013__1A2-A05_1/_article/-char/en)**

### Overview

This work explores a connector design inspired by tight-lock couplers used in railway vehicles. The connector enables crawler-driven modular robots to physically connect and extend their capabilities through combined configurations.

The paper investigates the mechanical connector as a means of establishing a stable connection between separate robotic units, allowing them to operate together as a larger robotic system.

### Mechanism
- Tight-lock-inspired mechanical connector.
- Mechanical coupling between crawler-driven modules.
- Connection designed to support functional extension of the robot system.

### What to Explore
- The tight-lock-inspired connector architecture.
- The engagement and locking mechanism.
- Mechanical constraints established by the connection.
- The connector's structural role in combined robot configurations.
- How connecting modules changes the overall robot capability.

### Relevance to T.E.T.R.I.S.

This paper provides an alternative mechanical design perspective beyond small face latches and pin-based interfaces. The tight-lock-inspired approach could offer ideas for a connector that establishes a more rigid connection between modules and supports the movement of a combined structure.

---

## Suggested Reading Order

| Priority | Paper | Main focus |
|---|---|---|
| 1 | Design, Principles, and Testing of a Latching Modular Robot Connector (2014) | Passive compliant latching |
| 2 | An Active Connection Mechanism for Modular Self-Reconfigurable Robotic Systems Based on Physical Latching (2008) | Active physical latching |
| 3 | A Multi-Sensory Autonomous Docking Approach for a Self-Reconfigurable Robot without Mechanical Guidance | Hook-based docking and sensing |
| 4 | A Novel Docking System for Modular Self-Reconfigurable Robots (2017) | Docking using existing actuators |
| 5 | A Reliable Docking Mechanism and Close-Range Docking Algorithm for Modular Reconfigurable Robots (2023) | Rigid coupling and close-range docking |
| 6 | Autonomous Alignment and Docking Control for a Self-Reconfigurable Modular Mobile Robotic System (2024) | Autonomous alignment and docking |
| 7 | Design and Dock Analysis for the Interactive Module of a Lattice-Based Self-Reconfigurable Robot (2007) | Peg-and-hole geometry and force analysis |
| 8 | Study on Functional Extension of the Robot System by Connecting the Modular Robots: Design of the Robot Connector (2013) | Tight-lock-inspired coupling |

---

## Objective of This Research

The aim of studying these mechanisms is to identify a suitable mechanical docking architecture for T.E.T.R.I.S. that balances:

- **Reliable engagement:** Modules should connect consistently despite small alignment errors.
- **Mechanical strength:** The connector should withstand loads generated when connected modules move and reconfigure.
- **Compactness:** The mechanism should fit within the module's docking faces.
- **Ease of fabrication:** The design should be feasible to prototype using 3D printing and commonly available mechanical components.
- **Autonomous undocking:** The connection should be releasable when the modules need to separate.
- **Interchangeability:** The docking interface should ideally support connections across the module's different faces.

The eventual connector design can be developed by comparing the mechanisms in these papers, identifying useful features and adapting them to the geometric, mechanical and actuation constraints of T.E.T.R.I.S.


