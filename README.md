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

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming








Developed by:S.RENUGA 
RegisterNumber: 22008594 


Logic symbol 

![LOGICSYMBOL](https://user-images.githubusercontent.com/119292258/211153062-37e74d24-0b67-4d13-b795-0c759a3a22c9.png)


RTL 

 Output:
 
 HALF ADDER
 
 ![Screenshot (23)](https://user-images.githubusercontent.com/119292258/211153219-96e71f0f-cb13-4a96-983f-a3fa9ce12b92.png)

FULL ADDER
 
 ![Screenshot (24)](https://user-images.githubusercontent.com/119292258/211153164-d64326b0-4499-48d6-b0b0-9c99d05884b9.png)
 
 
RTL
 TRUTH TABLE
 
 HALF ADDER 
 
 ![HALFADDER](https://user-images.githubusercontent.com/119292258/211153259-99999f9f-7f34-45a8-a2cd-4aa1d1f216e1.png)
 
 
 FULL ADDER
 
![FULLADDER](https://user-images.githubusercontent.com/119292258/211153262-9733a71c-5534-4055-9fc7-88d63cc78463.png)

 
 TIMING DIAGRAM
 
 HALF ADDER 
 
 ![HALFADDER TD](https://user-images.githubusercontent.com/119292258/211153319-0cd00ed4-50fd-4b93-94f9-f2f69f08db58.png)

FULL ADDER
 
 ![FULLADDER TD](https://user-images.githubusercontent.com/119292258/211153321-9019afc5-8ce5-4d9f-b195-8790f7015486.png)

 
Result:
Thus the implementation of half adder and full adder circiut are stuided and the truth table for different logic gates
