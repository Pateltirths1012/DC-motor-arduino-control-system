# DC-motor-arduino-control-system
This project implements a complete mechatronic control system for a DC gearmotor, bridging the gap between theoretical modeling and physical hardware implementation. The system utilizes MATLAB/Simulink for both physical modeling (Simscape) and real-time controller deployment (arduino-programming).

### Key objectives:
- **Mathematical Modeling**: Developed a physics-based simscape model including PWM dynamics. H-bridge behavior, and gearbox interia $(J = 0.00976 \ kg\cdot m^2)$ to predict motor response.
- **Hardware integration**: Constructed a custom circuit using an Arduino Uno R3, L293D Dual H-bridge, and a Polulu 172:1 metal Gearmotor with a 48 CPR quadrature encoder.
- **Closed-Loop Control**: Implemented real-time Proportional $(K_p)$ control algorithms for both **Speed** and **Position** tracking, reducing error between the potentiometer reference and encoder feedback.
- **System Identification**: Performed open-loop step response experiments to estimate the motor's transfer function, DC-gain, and time constant. 

---

[`Reports`](./Reports)

- Check the reports folder where each part of the project, its execution and its description is given in detail.

---
<video src="https://github.com/user-attachments/assets/bcb3e333-a1bb-4b9f-9ecb-d1aee6259156" controls width="100%"></video>





