# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: DHANUSHA.K
RegisterNumber:23001980
*/
## HalfAdder
![image](https://github.com/Dhanusha17/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151549957/510634e2-ddab-4944-94e6-a31559667a62)
*/
## FullAdder
![image](https://github.com/Dhanusha17/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151549957/13c8c81b-f87e-42d5-8148-dbf4ce61144e)
*/
Logic symbol & Truthtable
## Half Adder Truth table 
![image](https://github.com/Dhanusha17/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151549957/df94b0d7-e045-437f-b897-69f4ca2a668d)
*/
## Full Adder
![image](https://github.com/Dhanusha17/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151549957/15dfcdad-dc83-474f-a683-b0f82c964a15)

RTL realization
*/ 
## Half Adder
![image](https://github.com/Dhanusha17/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151549957/0a6c6f91-2a75-4d45-bdf5-dd6f197cdd8f)
*/
## Full Adder
![image](https://github.com/Dhanusha17/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151549957/a468eae2-c987-4d3c-abc1-a9a02cbec942)
*/
## Half Adder output
![image](https://github.com/Dhanusha17/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151549957/48930959-a908-4a4b-b115-2e3d6181aa58)
*/
## Full Adder output
![image](https://github.com/Dhanusha17/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151549957/8902b436-c5d4-4b2c-a9fc-18f39804b138)


### Output:


### TRUTH TABLE 

### Result:
