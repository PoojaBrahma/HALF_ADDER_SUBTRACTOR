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

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

![Screenshot 2025-04-16 094632](https://github.com/user-attachments/assets/5a050495-c0e9-4a9c-81a5-af0d278f7721)



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Halfadder

![Screenshot 2025-04-15 112239](https://github.com/user-attachments/assets/dbbb828f-4f1e-4739-a9c9-7d4c6e8e763f)


Halfsubtractor

![Screenshot 2025-04-15 113219](https://github.com/user-attachments/assets/f4208bcf-39d6-4efb-846f-e6cd5d59062e)


**RTL Schematic**

Halfadder

![Screenshot 2025-04-15 112226](https://github.com/user-attachments/assets/e2146152-a8b4-456e-8c49-342c07eee708)

Halfsubtractor

![Screenshot 2025-04-15 113340](https://github.com/user-attachments/assets/2de9cf55-bd44-4972-b138-8fff70ffca8a)


**Output/TIMING Waveform**

![Screenshot 2025-04-15 112505](https://github.com/user-attachments/assets/8f913db4-c630-4366-b335-2de14bd7188d)

![Screenshot 2025-04-15 113555](https://github.com/user-attachments/assets/c6723d13-4ab2-484a-9eca-2670faf1b19b)


**Result:**

The code is executed successfully.
