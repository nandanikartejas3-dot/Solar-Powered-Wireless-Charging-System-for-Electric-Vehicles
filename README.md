# Solar Powered Wireless Charging System for Electric Vehicles

## Project overview
The rapid adoption of electric vehicles (EVs) has created a growing demand for efficient and sustainable charging solutions. Traditional charging methods rely on physical connectors and grid electricity, which can be inconvenient.

This project demonstrates a **prototype for wireless charging of EVs using inductive power transfer**, powered by **solar energy**. The goal is to provide a clean, renewable, and user-friendly charging approach aligned with sustainability objectives.

## Proposed solution
- **Solar panel + battery storage** generate and store energy.
- A **high-frequency switching circuit** energizes the **transmitter coil**.
- A nearby **receiver coil** captures the magnetic field through **electromagnetic induction** and converts it back to electrical energy to charge a load **wirelessly**.
- An **Arduino-based control/monitoring** system supports voltage monitoring, switching, and indications.

## Project description
This project presents the design and development of a Solar Powered Wireless Charging System for Electric Vehicles (EVs) using inductive power transfer technology. The charging station uses a solar panel and battery storage system to generate and store electrical energy, which is then transferred wirelessly to the EV battery through coupled transmitter and receiver coils operating at resonant frequency.

An Arduino-based control system is implemented for voltage monitoring, switching operations, and system indication. The prototype demonstrates the practical application of renewable energy integration, wireless power transfer, embedded systems, and power electronics in modern EV infrastructure.

## Objectives
- Develop a wireless charging system for electric vehicles using inductive coupling.
- Utilize solar energy as the primary power source for EV charging.
- Eliminate physical charging connectors and improve user convenience.
- Design transmitter and receiver coils for efficient wireless power transfer.
- Implement resonance-based power transfer for improved efficiency.
- Monitor system voltage and charging conditions using Arduino.
- Analyze charging efficiency and power transfer characteristics.
- Promote sustainable and eco-friendly EV charging infrastructure.

## Major components (prototype)
- Solar panel
- Rechargeable battery (storage)
- High-frequency switching / driver circuit
- Transmitter coil and receiver coil (resonant inductive coupling)
- Arduino Nano (monitoring/control)
- Relay module (switching)
- LCD display (status/parameters)
- Buzzer (alerts such as low voltage / misalignment)

## Working principle (high-level)
1. Solar panel converts sunlight into electrical energy and charges the storage battery.
2. Stored DC power feeds a high-frequency switching circuit that energizes the transmitter coil.
3. The transmitter coil produces a time-varying magnetic field.
4. The receiver coil (placed near the transmitter) inductively captures this field and converts it back to electrical power.
5. Arduino Nano monitors voltage/conditions and provides display/relay/buzzer indications.

## Experimental results
The prototype successfully demonstrated wireless charging of an electrical load using solar energy as the primary source. The transmitter and receiver coils achieved stable power transfer across a small air gap using resonant inductive coupling. The system maintained reliable operation with proper voltage regulation and charging indication through the Arduino control unit.

## Conclusion
The Solar Powered Wireless Charging System for Electric Vehicles demonstrates the integration of renewable energy and wireless power transfer technology for future EV charging applications. The developed hardware prototype achieved contactless power transmission using resonant inductive coupling while utilizing solar energy as the primary power source.

This approach can improve user convenience, reduce dependency on grid-based charging, and eliminate issues related to physical connectors and cable wear. The Arduino-based monitoring and control system supports operational safety and real-time monitoring.

## Project files
- `Circuit Diagram.png` — circuit diagram
- `Structure of the Project.png` — system structure/block representation
- `Hardware Model Image1.jpg` — hardware prototype image
- `Hardware Model Image2.jpg` — hardware prototype image
- `Solar Project.docx` — source document used to create this README

## Images
### Circuit diagram
![Circuit Diagram](./Circuit%20Diagram.png)

### Structure of the project
![Structure of the Project](./Structure%20of%20the%20Project.png)

### Hardware prototype
![Hardware Model Image1](./Hardware%20Model%20Image1.jpg)
![Hardware Model Image2](./Hardware%20Model%20Image2.jpg)

## References
1. A. K. Panchal, R. K. Patel, "Wireless Power Transfer System for Electric Vehicle Charging Using Solar Energy," *International Journal for Research in Applied Science & Engineering Technology (IJRASET)*, Vol. 10, Issue IV, April 2022.
2. S. B. Thakare, P. S. Patil, "Solar Based Wireless Charging System for Electric Vehicles," *International Research Journal of Engineering and Technology (IRJET)*, Vol. 08, Issue 06, June 2021.
3. MATLAB & Simulink Documentation — Wireless Power Transfer and Power Electronics Applications: https://www.mathworks.com/solutions/power-electronics-control.html

