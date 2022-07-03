# CMP1010_Logic-Design_arithmetic-unit_project

In this project, students are required to design and implement an arithmetic unit that is capable of
adding, subtracting and multiplying two signed magnitude numbers, and displays the result of the operation
performed along with some additional flags regarding the operation and the result.

![image](https://user-images.githubusercontent.com/88630231/177048893-65e0d46e-7445-4a58-b11e-083f9a95c9d2.png)


**Description**
The arithmetic unit takes two 5-bits signed magnitude inputs, A and B, and an additional input called Mode

of Operation, which informs the arithmetic unit which function to perform on A and B:

 Addition: Result = A + B

During the addition A, B and Result are all 6-bits signed numbers.

 Subtraction: Result = A - B

During the subtraction A, B and Result are all 5-bits signed numbers.

 Multiplication: Result = A * B

During the multiplication A and B are 5-bits signed number and Result is 9-bits signed number.

The multiplication of 4-bits by 4-bits yields a result of 8-bits, therefore Result is composed of 8-bits

for the value and 1-bit for the sign.

The multiplication of 15 x -15 = -225, which in binary is (01111)2 x (11111)2 = (111100001)2

 Division: Result = A / B

During the division A, B and Result are all 5-bits signed numbers.

Our division is integer division, so we neglect the fraction part of the result.

The division of 15 / -2 = -7, which in binary is (01111)2 / (10010)2 = (10111)2

**Flags**

o Sign Flag:

The sign flag indicates if the result is negative. The flag is set to 1 if the result is negative and
0 otherwise.

o Zero Flag:
The zero flag indicates if the result is zero. The flag is set to 1 if the result is zero and 0
otherwise.

o Div by Zero Flag:
The divide by zero flag indicates if we divide by zero. The flag is set to 1 if B operand equal
zero in division operation and 0 otherwise.

**Notes**
o The outputs (Result and sign flag should be displayed on 3 seven segments and the other
outputs should be displayed on leds)

o The input can be entered through switches

o You need to implement circuit which can be used to convert from BCD to seven segments,
you can use it in converting result to be displayed on seven segments.

o You need to implement circuit which convert from binary to BCD





**Deliverables**

o For each team member: Name, ID and work done in the project.

o Block Diagram.

o Inputs and Outputs.

o All logisim files.

o Demo video

1. The deadline is 9/1/2021 midnight on classroom
2. The discussion will be in the tutorial time (it will be online) from 10/1/2021 to 14/1/2021)
3. Each group consist of 4 members from the same lab tutorial.

a. Two of them is responsible for Addition and subtraction operation
b. one implement multiplication and binary to BCD circuit
c. one implement integer division and BCD to seven segments circuit
d. All the team members cooperate in integration of different components
e. You need to make the design hierarchy by implement the different circuits in separate
files to facilitate the debugging operation
f. If the integration does not work, then the team will lose the integration grade only and
each member will be graded upon his part in the project.
g. The deadline to join your team is 31/12/2020
