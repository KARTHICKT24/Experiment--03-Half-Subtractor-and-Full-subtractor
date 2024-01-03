# NAME : karthick kishore.T
# REF NO :212223220042
# Experiment--04-Half-Subtractor-and-Full-subtractor
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
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:
HAL SUBTRACTOR:
![291060477-0bbca9ef-e791-4bdc-9c95-0f5c42080a9a](https://github.com/KARTHICKT24/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149347526/90399895-e90b-49c6-b32a-f366f80cdd33)

FULL SUBTRACTOR:

![291060499-81cb63a7-e6b9-4a4a-84f0-9de13c026ab3](https://github.com/KARTHICKT24/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149347526/4f5e70e8-244c-4643-a2ba-911b0f78e18a)



## Truthtable:
HALF SUBTRACTOR:

![291060529-cf2977c3-e1e0-4f0c-bb78-3354672e5f29](https://github.com/KARTHICKT24/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149347526/09868b14-f71e-4805-a02e-c9d1ca36b1fb)

FULL SUBTRACTOR:
![291060551-1e82ad30-477d-406d-88a1-795a50c51fcd](https://github.com/KARTHICKT24/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149347526/4a280e42-8f03-4189-9c89-c814d85affcf)

# RTL:
HALF SUBTRACTOR:
![291060657-7a07d859-b19e-4967-ba0b-1f7bcb22929a](https://github.com/KARTHICKT24/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149347526/cd07aa73-4dc0-43dc-bbf6-4f72ae1575ce)

FULL SUBRACTOR:

![291060697-4906ce1f-1432-43f7-8f1e-77e099a78735](https://github.com/KARTHICKT24/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149347526/c90cd743-d1d9-47c1-bc0b-16f96a7f49e6)




## Timing diagram :
HALF SUBTRACTOR:

![291060630-82410179-f05f-455e-bb36-64f3d9e41280](https://github.com/KARTHICKT24/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149347526/7b0865fb-549a-4fdf-93d5-4288ed8c874c)


FULL SUBTRACTOR:

![291060617-1a2d26b8-ece2-4523-9248-211720c47f26](https://github.com/KARTHICKT24/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149347526/61220f7b-1958-4fd0-9efc-a77e8f4822ef)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
