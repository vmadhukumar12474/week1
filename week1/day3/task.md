# Madhu Kumar
# VSD Tool Analysis
## GLS Concepts and Flow Using Icarus Verilog
- Gate Level Simulation (GLS) validates the design after synthesis, ensuring both logical correctness and timing accuracy.  
- GLS uses the synthesized netlist as the Device Under Test (DUT), representing actual hardware behavior.
- Icarus Verilog compiles RTL and gate-level models, supporting functional checks and timing-aware simulations.

- GLS is crucial for verifying dynamic circuit behaviors not covered by static timing analysis.
## Synthesis-Simulation Mismatch

- Simulation-synthesis mismatches occur when the simulated RTL behavior diverges from synthesized hardware function due to coding style issues or synthesis optimization.

- Common causes include latch inference, incomplete case/if statements, uninitialized signals, and improper use of blocking vs. non-blocking assignments.

- Always check synthesis reports for unexpected logic removals or warnings and ensure all top-level ports are properly mapped.

- Periodically compare pre- and post-synthesis simulation results to catch mismatches early.
## Blocking and Non-Blocking Statements in Verilog

- Blocking assignments (=) execute sequentially and can cause race conditions if used incorrectly in sequential logic.

- Non-blocking assignments (<=) evaluate the right-hand side at the start of a time step and update the left-hand side at the end, modeling hardware registers more accurately.

- Use blocking assignments for combinational logic and non-blocking assignments for sequential logic to avoid simulation-synthesis mismatches.

- Mixing blocking and non-blocking assignments, especially in synchronous blocks, leads to unpredictable or nondeterministic behavior.
## Caveats with Blocking Statements

- Avoid blocking assignments in sequential (clocked) always blocks, as they can produce latch inference and unintended combinational feedback.

- Non-blocking assignments in sequential logic ensure proper data flow and prevent hazards that arise with blocking assignments.

- Coding guidelines recommend always favoring non-blocking assignments for flip-flop modeling and synchronous registers.
   ## GLS Synth Sim Mismatch:
  <img width="1640" height="811" alt="image" src="https://github.com/user-attachments/assets/43e7da05-ce64-458d-8e90-d6fabcd3cef9" />
  <img width="1672" height="792" alt="image" src="https://github.com/user-attachments/assets/67354f41-1180-428c-987d-35cac686f69c" />
  <img width="707" height="403" alt="image" src="https://github.com/user-attachments/assets/83c04bd4-ecda-4c1b-b0e5-864fc6aa60e4" />
  <img width="1281" height="473" alt="image" src="https://github.com/user-attachments/assets/797442e2-ad88-4f76-ae0b-b1404dd88f15" />
  <img width="1281" height="473" alt="image" src="https://github.com/user-attachments/assets/fff33d33-d254-4157-ad1a-a7cd56615881" />

  <img width="1856" height="839" alt="image" src="https://github.com/user-attachments/assets/32642461-2e61-42b9-bad8-352aa154123e" />
  <img width="1294" height="465" alt="image" src="https://github.com/user-attachments/assets/225e2e0b-343d-4b27-be08-399554107847" />
## Synth sim mismatch blocking statement:
<img width="1588" height="589" alt="image" src="https://github.com/user-attachments/assets/5c332f95-5470-43d4-9b9e-ca9426b2e72b" />
<img width="1287" height="592" alt="image" src="https://github.com/user-attachments/assets/747ed3fc-9365-4305-8074-b768eae91f6b" />
<img width="1287" height="592" alt="image" src="https://github.com/user-attachments/assets/69ef5a3d-730a-4117-91f0-451fbff9e60b" />


<img width="1287" height="592" alt="image" src="https://github.com/user-attachments/assets/0fd4011b-8c37-42cc-9625-93df59f2139f" />
<img width="1287" height="592" alt="image" src="https://github.com/user-attachments/assets/db3a32c3-20dc-4bf0-88b5-79f6363a5e1a" />







 





