# 4-Bit Logic Comparator on Basys 3 (VHDL)

A 4-bit digital magnitude comparator implemented in VHDL and tested directly on hardware using the Digilent Basys 3 FPGA board.

## How it works
The circuit takes two 4-bit numbers (`A` and `B`) from the board's switches and compares them:
- Lights up specific indicators for `A > B`, `A = B`, or `A < B`
- Maps input values to the 7-segment display using time-multiplexing to show real-time results
- Simulated in Vivado before writing the bitstream to the board to verify logic states and transitions

## Tools & Board
- **Language:** VHDL
- **Software:** Xilinx Vivado
- **Hardware:** Digilent Basys 3 FPGA (Artix-7)

## Project Files
- `Comparator.vhd` – Main VHDL logic and entity design
- `constr.xdc` – Pin mappings for Basys 3 switches and display
- `project_final.xpr` – Vivado project file
- `Project_documentation.pdf` – Full schematic diagrams and project details

## Authors
- Matei Postolache
- Maxim Cezar-Andrei
