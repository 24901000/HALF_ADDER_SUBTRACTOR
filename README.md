# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER
![Screenshot (19)](https://github.com/user-attachments/assets/01f43bd4-d074-4f88-ad11-2d12fab1e438)
**Half Subtractor**

ctor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

![Screenshot (23)](https://github.com/user-attachments/assets/584cb123-20f4-4a45-af9b-8bc6d8f45344)

**Truthtable**

half adder
![Screenshot (24)](https://github.com/user-attachments/assets/eb6b2274-1d38-4fe5-bd5b-99bb8b6ac440)
half subtractor
![Screenshot (25)](https://github.com/user-attachments/assets/ffcb9436-6530-46c5-b505-30f260bdca8c)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

 Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

![Screenshot (22)](https://github.com/user-attachments/assets/ecc44ffe-20d9-4881-8ffb-eb489e796146)


**RTL Schematic**
![Screenshot (21)](https://github.com/user-attachments/assets/7d6c959a-693f-46d6-a579-6fb87ed52db9)

**Output/TIMING Waveform**
![Screenshot 2024-12-04 160113](https://github.com/user-attachments/assets/767f6014-1ce6-4525-8c50-959bf8ffb3ce)

**Result:**
HALF ADDER AND SUBTRACT IS DESIGNED AND THE TRUTH TABLE IS VERIFIED
