# 8BitCalc
This is the repository for 8 Bit Calculator developed in Logisim using logic gates for additions, subtractions, multiplication and division operations.

1)In the multiplexer there are 3 options. 00 for Addition, 01 for Subtraction and 10 for Multiplication. After selecting the two 8 input bits, the output of the operation will be displayed on the 7 Segment Display on the right side of the calculator circuit in hexadecimal format. For division there is separate 7 segment display for quotient and remainder. The result of the division will be always displayed irrespective of the input to the multiplexer. The division and subtraction operations are with respect to B numbered bits. Wherever there is written "Keep this always on" next to a input button, make sure it is always on otherwise it will affect the result of the specific operation.

2)Set of Input Combination: There are two 8 bit inputs which are connected to all 4 circuits(addition, subtraction, multiplication, division). In multiplication circuit, multiplexers are used to take input and calculate the result. In addition, self made look ahead carry adder is used. In subtraction, same adder from addition is used which will calculate the subtraction using 2’s complement method. For division, multiple proceesing units are implemented, each processing units consists of a full adder and a 2:1 Multiplexer.

The output will be shown on the 7 Segment Display.
