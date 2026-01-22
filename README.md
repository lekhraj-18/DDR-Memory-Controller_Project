# DDR-Memory-Controller_Project

DDR Memory Controller Design (Verilog | FPGA-Oriented)

Designed and implemented a custom DDR memory controller in Verilog, following a modular, JEDEC-aligned architecture suitable for FPGA-based systems. The controller was built from the ground up with clear separation of concerns and verified through simulation at each stage.

Key highlights:

Modular architecture including user interface, address decoder, bank state tracker, command FSM, and timing controller.
Implemented row-hit / row-miss logic with open-page policy and per-bank state tracking.
Developed a cycle-accurate timing controller enforcing critical DDR constraints (tRCD, tRP, tRAS).
Designed a command sequencing FSM handling ACTIVATE, READ, WRITE, and PRECHARGE operations.
Integrated all modules into a top-level controller with clean handshaking and reset management.
Verified functionality using self-checking testbenches and waveform-based debugging in Vivado.

Skills & technologies:

Verilog HDL · DDR Memory Architecture · FSM Design · Timing Analysis · FPGA Simulation · Modular RTL Design · Vivado.
This project demonstrates strong understanding of memory subsystem design, hardware timing constraints, and system-level RTL integration.
