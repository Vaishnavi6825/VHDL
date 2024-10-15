# VHDL
This repository contains Design and testing of basic Logic Gates using Verilog HDL and capture the waveforms.

`Aim`

To implement basic logic gates (AND, OR, NOT, NAND, XOR, NOR) using verilog and to analyze their functionality through simulation.

`Apparatus Required`

Hardware: <br>
Computer with Xilinx Vivado or any compatible Verilog simulator.
Software: <br>
-Xilinx Vivado (for synthesis and simulation)<br>
-Text editor (for writing Verilog code)<br>

`Code Implementation`

`module logic_gates(input a, input b, output or_gate, output and_gate, output not_gate, output nand_gate, output xor_gate, output nor_gate);
  assign or_gate = a | b;
  assign and_gate = a & b;
  assign not_gate = ~a;
  assign nand_gate = ~(a & b);
  assign xor_gate = a ^ b;
  assign nor_gate = ~(a | b);
endmodule`


![WhatsApp Image 2024-10-15 at 14 54 08_5ea07a82](https://github.com/user-attachments/assets/36256952-667e-42fa-8983-a1f36e010ecd)

`Output Waveform`

![WhatsApp Image 2024-10-15 at 14 54 33_c945bedb](https://github.com/user-attachments/assets/3ab5ebde-23ef-4a34-9d7f-cbe1777e9a79)

`Result`

After simulating the Verilog code for the logic gates using the provided models: <br>
<br>
Each logic gate outputs the expected result based on the inputs according to the truth table.<br>
The implementations confirm the functionality of the gates across all input combinations.<br>







