### NAME : SACHIN.S
### REG NO.: 24900576
# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

# AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

# Equipments Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

# Full Adder and Full Subtractor

# Full Adder

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

# Figure -1 FULL ADDER

# Full Subtractor

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

# Truthtable
![WhatsApp Image 2024-11-28 at 2 16 54 PM](https://github.com/user-attachments/assets/bffe62d4-f457-491e-88ac-394a9b981e0c)

# Procedure
Implementing FULL ADDER AND SUBTRACTOR in Verilog HDL (Hardware Description Language) involves translating the simplified Boolean expressions into Verilog code to describe the behavior of digital circuits. The basic building blocks in Verilog is module. The module represent a combinational circuit. Use logical operators (&, |, ~, ^) to implement Boolean functions directly. Use built-in gate primitives for basic functions. Use University program VWF to verify the functionality of your Verilog modules. Create waveform and check outputs against expected results.

# Program:
![Screenshot 2024-11-28 141059](https://github.com/user-attachments/assets/21746069-ffb5-40c5-8b70-028463084459)


# RTL Schematic:
![Screenshot 2024-11-28 140803](https://github.com/user-attachments/assets/0dd0878a-4259-41a2-be20-9061a0554fcf)

# Output Timing Waveform:
![Screenshot 2024-11-28 141313](https://github.com/user-attachments/assets/0b09f08e-ec58-4a38-84b0-e78742e2a21b)

# Result:

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.
