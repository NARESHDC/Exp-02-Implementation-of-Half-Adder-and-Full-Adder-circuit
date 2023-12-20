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

i)HALF ADDER:

![Screenshot 2023-12-20 174850](https://github.com/NARESHDC/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149348388/1e214e70-dc3b-48ad-b8ac-5dc529678f09)

ii)FULL ADDER:


![Screenshot 2023-12-20 174956](https://github.com/NARESHDC/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149348388/e7006b2b-10ea-4d0c-96bc-259c74d84691)

/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: M.NARESH
RegisterNumber: 212223220064 
*/
Logic symbol & Truthtable
RTL realization

### Output:
### RTL:
i)HALF ADDER
![Screenshot 2023-12-20 175028](https://github.com/NARESHDC/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149348388/ed28ae15-3f03-4821-bf08-f8d9221a2ca4)

ii)FULL ADDER:

![image](https://github.com/NARESHDC/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149348388/f85d4113-ebae-4e8d-bb95-d98fc9e3ab25)

### TIMING DIAGRAM:

i)HALF ADDER:


![Screenshot 2023-12-20 175201](https://github.com/NARESHDC/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149348388/f9e4a67e-5379-42ee-9ea8-44d6435c0879)

ii)FULL ADDER:

![Screenshot 2023-12-20 175240](https://github.com/NARESHDC/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149348388/a78aecb4-2c79-47fd-a833-642a222d4c97)


### TRUTH TABLE:

i)HALF ADDER:

![Screenshot 2023-12-20 175315](https://github.com/NARESHDC/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149348388/7c725ed7-bf9d-493f-9c9a-b7cf81bcdbf7)


ii)FULL ADDER:

![Screenshot 2023-12-20 175352](https://github.com/NARESHDC/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149348388/3f1945a4-d4b0-4314-b8a8-f0b899303f8f)




### Result:

To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.
