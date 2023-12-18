# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
 
 
The half-subtractor is 
 a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
 

Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure

 
![Screenshot 2023-12-18 220306](https://github.com/23014287rithik/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150985832/d0897aa6-278f-47b8-b025-1dd73106e6f5)

Write the detailed procedure here 
 


## Program:

 ![Screenshot 2023-12-18 220316](https://github.com/23014287rithik/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150985832/26f807dd-0d1f-41de-a9e5-edcae0759c21)

![Screenshot 2023-12-18 220320](https://github.com/23014287rithik/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150985832/e3e88047-6ca5-4f64-b5cd-2deb09db5b1d)


/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: Rithik-V
RegisterNumber: 23014287
*/

## Output:

##  RTL realization

![Screenshot 2023-12-18 220325](https://github.com/23014287rithik/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150985832/6cb46c76-b8fb-41a3-84a0-08c8a4ffe48f)

![Screenshot 2023-12-18 220330](https://github.com/23014287rithik/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150985832/0c947341-bbff-4d52-bc49-43df7d852f98)

## Truthtable

![Screenshot 2023-12-18 220337](https://github.com/23014287rithik/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150985832/5e33d06c-4a9e-41a3-8a5b-4b177bb425ff)

![Screenshot 2023-12-18 220343](https://github.com/23014287rithik/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150985832/96fbe097-9957-4a90-b568-c5cfca995224)


## Timing diagram 

![Screenshot 2023-12-18 220350](https://github.com/23014287rithik/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150985832/d2f21ad4-00be-4930-8546-3cfd4f8ab95a)

![Screenshot 2023-12-18 220357](https://github.com/23014287rithik/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150985832/ab517e7f-a6f7-4fd6-af3f-41728c7ccead)



## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
