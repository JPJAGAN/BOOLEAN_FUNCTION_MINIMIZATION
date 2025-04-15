# EXPERIMENT 2 : IMPLEMENTATION OF BOOLEAN_FUNCTION_MINIMIZATION

# NAME : JAGAN JP
# REG NO : 212224230099

AIM:

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

THEORY:

In this experiment, combinational logic functions are implemented using Verilog HDL and verified through simulation in Quartus software. The given functions F1 and F2 are in Sum of Products (SOP) form, which are combinations of AND, OR, and NOT gates.

F1 is a 4-variable logic function with inputs A, B, C, D.
F2 is a 4-variable logic function with inputs w, x, y, z.
Using Verilog, the Boolean expressions are coded using assign statements, which create combinational circuits. The design is then compiled and simulated in Quartus, where input combinations are applied, and outputs F1 and F2 are observed in the waveform to verify correctness.

This process helps in understanding digital circuit design and simulation using HDL and FPGA tools.

PROCEDURE:

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


PROGRAM:

![WhatsApp Image 2025-03-19 at 9 28 20 AM](https://github.com/user-attachments/assets/ef7fa114-a4fb-4afa-bc9a-7a9a9004bd7e)

TRUTH TABLE:

![WhatsApp Image 2024-11-21 at 11 34 59_158c6d9f](https://github.com/user-attachments/assets/180440d0-631d-45bf-a85a-4508c9f41e65)

![WhatsApp Image 2024-11-21 at 11 34 59_05329a2a](https://github.com/user-attachments/assets/e7443311-e06d-405a-9194-a60e492f0585)

RTL REALIZATION:

![WhatsApp Image 2025-03-19 at 9 28 15 AM](https://github.com/user-attachments/assets/c233ac40-2b9f-4663-b3b6-2044ec65a68f)



WAVE FORM:
![WhatsApp Image 2025-03-19 at 9 28 20 AM (1)](https://github.com/user-attachments/assets/55f67c9d-02c6-41c8-a2cb-e91394415035)


RESULT:

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

