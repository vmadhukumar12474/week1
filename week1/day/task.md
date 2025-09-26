# Madhu kumar
# VSD TOOL Usage 
## step1:
- change the current working directory in the terminal  
like using cd home,cd vsd,cd VLSI,cd vsdflow
## step2:
- accessing files from the host  
by using the command git clone https://github.com/kunalg123/sky130RTLDesignAndSynthesisWorkshop.git  
## step3:
- the new directive is created ie., sky130RTLANDsynthesisWorkshop  
to change the current working directory in the terminal by using cd sky130RTLANDsysnthesisWorkshop instruction   
to list the content in library the ls instuction is used    
by doing this the three files are seen they are lib,my_lib,verilog_files   
## step4:
- open verilog_model file in lib  
by doing this the libaries is show there   
<img width="1860" height="1002" alt="Screenshot from 2025-09-26 15-02-00" src="https://github.com/user-attachments/assets/7b722546-6d5a-4990-b6de-de653ddeb281" />  
<img width="1853" height="820" alt="Screenshot from 2025-09-26 15-02-14" src="https://github.com/user-attachments/assets/86f5830e-629f-4260-be51-a80f3965e8bb" />


# iverilog:   
key points as iverilog as simulator   
- Purpose: It compiles Verilog HDL (Hardware Description Language) code into an intermediate form for simulation and synthesis.  
- Functionality: Allows simulation of digital circuits described in Verilog, including functional verification and testbench running.  
- Cross-platform: Available on Linux, Windows, and macOS.  
- Output: Produces a simulation executable (VVP file) which you run with the vvp command to see waveform outputs or console prints.  
- Usage: Often paired with waveform viewers like GTKWave to visualize simulation results.  
Command example:  
<img width="1857" height="1001" alt="Screenshot from 2025-09-26 15-31-48" src="https://github.com/user-attachments/assets/514a275b-d859-4555-8be3-a95e71d66c80" />  
<img width="1851" height="1044" alt="Screenshot from 2025-09-26 15-30-37" src="https://github.com/user-attachments/assets/1b24b2a2-d81e-4cf0-abde-56d8706cf04a" />

# Gvim:  
GVim is the graphical version of Vim, a powerful text editor. Here’s some information about GVim:  
- GVim provides all the features of Vim but with a graphical user interface (GUI).  
- It offers menus, toolbar, and mouse support which are not available in the terminal version of Vim.  
- GVim supports better color schemes, fonts, and intuitive window resizing.  
- It is suitable for users who prefer a GUI over terminal-based editing.  
- You can launch GVim with the command gvim in the terminal.  
- The keyboard shortcuts and commands remain the same as Vim, so it combines Vim's power with GUI convenience.  
- GVim requires an X server or graphical environment to run.  
  by using gvim tb_good_mux.v -0 good_mux.v instruction the following window is opend  
  <img width="1861" height="1014" alt="Screenshot from 2025-09-26 15-49-36" src="https://github.com/user-attachments/assets/108ad711-77c9-4655-8c7e-db63a7f1e96f" />

# Yosys:
Key Points on Yosys as a Synthesizer:
- Function: Yosys converts high-level RTL (Register Transfer Level) Verilog code into lower-level gate-level netlists suitable for FPGA or ASIC implementation.
- Support: It understands most synthesizable Verilog-2005 constructs, including behavioral, dataflow, and structural coding styles.
- Synthesis Flow:
        Parse Verilog files into internal RTL representation.
        Perform logic optimizations and transformations.
        Technology mapping using standard cell libraries described in Liberty (.lib) format.
        Output netlists in formats like BLIF, Verilog, EDIF for further processing.
- Integration with ABC: Yosys can invoke ABC, an advanced open-source logic optimization and mapping tool, for further low-level optimizations and efficient logic minimization.
- Extensibility: Yosys’s modular architecture allows users to build custom synthesis flows by chaining synthesis passes and adding new plugins.
    
<img width="1651" height="749" alt="Screenshot from 2025-09-26 18-32-38" src="https://github.com/user-attachments/assets/7f37de7d-4c2b-4abd-b005-5bee64083937" />
<img width="1727" height="514" alt="Screenshot from 2025-09-26 18-33-34" src="https://github.com/user-attachments/assets/a798a86d-f030-43b3-9418-bd1c1a751288" />
<img width="1171" height="555" alt="Screenshot from 2025-09-26 18-44-19" src="https://github.com/user-attachments/assets/1159ff2b-7a2b-4d35-a9a4-6f216f36bc3c" />


<img width="1490" height="881" alt="Screenshot from 2025-09-26 18-41-15" src="https://github.com/user-attachments/assets/ba1b83aa-4070-4c0c-bec7-954dddc39531" />






