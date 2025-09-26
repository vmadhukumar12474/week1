# Madhu Kumar
# VSD Tool Usage
Introduction to Optimisations Part 1
## circuit optimization in digital logic design:  
- optimizations are critical for reducing area, improving speed, and minimizing power consumption in synthesized circuits. 
- Basic techniques are covered, such as logic reduction (using Boolean algebra), gate minimization.
- The role of synthesis tools in automating these optimizations during RTL-to-gate-level translation.
  <img width="1849" height="222" alt="image" src="https://github.com/user-attachments/assets/051d91fc-6891-4ea9-9fe2-1b5f699187e1" />
  <img width="1849" height="1001" alt="image" src="https://github.com/user-attachments/assets/60ce5dfb-bfc7-45f5-a443-6d2d522aa529" />
## Introduction to Optimisations:  

- advanced optimization methods, including multi-level logic optimizations, technology mapping
- The use of standard cell libraries.
-  It explains how Yosys and similar synthesis tools apply transformations like algebraic factoring, constant propagation, dead code elimination, and path balancing to achieve practical, efficient netlists that are ready for physical implementation.
## Introduction to Optimisations:

- This part explores verification aspects of optimization and practical trade-offs.
- Topics include optimizing for timing closure, understanding the impact of optimization on critical path delay, and power dissipation.
- It also introduces optimization metrics (speed, area, power, testability), discusses script-driven optimization workflows, and may show examples of how changes in settings affect synthesized results, using Yosys command scripts.
 ## sequential logic optimization
- Optimize memory elements like flip-flops/latches along with combinational logic.

- Perform state minimization to reduce states and transitions in sequential machines.

- Use retiming to relocate registers for balanced timing and better clock rates.

- Apply clock gating to reduce power by disabling clocks to idle registers.

- Merge and share flip-flops to reduce area and simplify design.

- Remove redundant registers and optimize reset/set logic.

- Manage timing to meet setup and hold requirements for reliable operation.

- Balance tradeoffs between timing, area, and power in registers and logic.

- Employ algorithms to optimize sequential logic while preserving behavior.

- Tools like Yosys automate these optimizations during synthesis flow.
<img width="1305" height="495" alt="image" src="https://github.com/user-attachments/assets/c878c25a-8cf0-4c22-85d1-3078e9cea7e6" />

<img width="1266" height="438" alt="Screenshot from 2025-09-26 19-21-04" src="https://github.com/user-attachments/assets/55562f91-2f34-4c86-b75e-daad78c2ba65" />
<img width="359" height="315" alt="image" src="https://github.com/user-attachments/assets/3718cb6b-6e18-4aa1-9343-598236f0e0a0" />
<img width="1170" height="521" alt="image" src="https://github.com/user-attachments/assets/ddb05447-f75c-4599-80d1-987b466cea4d" />
<img width="1185" height="418" alt="image" src="https://github.com/user-attachments/assets/b4ad5267-ce71-4b9e-b3c6-4d862bf49da5" />
<img width="1178" height="584" alt="image" src="https://github.com/user-attachments/assets/b01384db-11fd-43c5-b9ca-4e8ad7a44479" />
## Seq optimisation unused outputs:  

<img width="1294" height="559" alt="image" src="https://github.com/user-attachments/assets/6cbb66a8-a2bd-4faf-a66b-1bebc6387437" />
<img width="1294" height="559" alt="image" src="https://github.com/user-attachments/assets/28547f98-8454-4e77-862a-f1e6fcac25eb" />








