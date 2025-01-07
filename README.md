NAME : B.BARKAVI

REFERENCE NO : 24901000

**EXPERIMENT NO : 3  IMPLEMENTATION OF  HALF ADDER AND HALF SUBTRACTOR**

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


![Screenshot (19)](https://github.com/user-attachments/assets/c3363e29-f37f-4503-bd21-aa1d971eea8e)

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor


![Screenshot (25)](https://github.com/user-attachments/assets/92f7b992-b63d-4169-b58f-009acb215e95)

**Truthtable**

Half adder


![Screenshot (24)](https://github.com/user-attachments/assets/d2f0cbc4-e855-4583-894f-340a9d4eb255)

Half subtractor


![Screenshot (23)](https://github.com/user-attachments/assets/28a0df73-9aa9-472b-9900-79635248f7b2)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

![Screenshot (22)](https://github.com/user-attachments/assets/1c1b8cca-4a63-42f1-be80-970b64881370)


**RTL Schematic**


![Screenshot (21)](https://github.com/user-attachments/assets/f9b96c82-3f2f-48b7-9e15-ef4ec8f9fa7a)

**Output/TIMING Waveform**


![Screenshot 2024-12-04 160113](https://github.com/user-attachments/assets/806d0099-eb89-470d-aee7-917fb1772359)

**Result:**
HALF ADDER AND HALF SUBTRACTER IS DESIGNED AND THE TRUTH TABLE IS VERIFIED
