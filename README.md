# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
![Screenshot 2024-11-04 133924](https://github.com/user-attachments/assets/2650b084-e90e-4506-9c72-5afa0ef2e677)![Screenshot 2024-11-04 133938](https://github.com/user-attachments/assets/779c8145-9bde-4921-a8a2-8d4b3ba7c1e7)


**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.![Screenshot 2024-11-04 132046](https://github.com/user-attachments/assets/564818f7-1f07-45fe-8cdb-c9e77e5c77fa)![Screenshot 2024-11-04 132650](https://github.com/user-attachments/assets/f0f8bbe5-41ef-4586-9c54-0c93eeab1063)

 Developed by:G.Ramanujam RegisterNumber:24000309
*/

**RTL Schematic**![Screenshot 2024-10-21 143302](https://github.com/user-attachments/assets/6317520a-8b92-4248-95fe-51105b76a255)![Screenshot 2024-10-21 143826](https://github.com/user-attachments/assets/689d9ec2-359a-4387-a9e0-a0d76c6bd2c0)



**Output Timing Waveform**![Screenshot 2024-10-21 143416](https://github.com/user-attachments/assets/fbf574ae-6f5d-463b-b1f8-97be834f0f54)![Screenshot 2024-10-21 143954](https://github.com/user-attachments/assets/58a5675e-e4a1-4d0d-b4ac-9aaf896cf890)



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



