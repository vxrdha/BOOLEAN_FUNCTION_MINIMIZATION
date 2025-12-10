# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**


**Truth table**
![Truth table](https://github.com/user-attachments/assets/d918c739-5dcf-4aa3-b4cc-561bce96ed2d)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

module as2 (a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1 = ~a&~b&~c&~d | a&~c&~d | ~b&c&~d | ~a&b&c&d | b&~c&d;
assign f2 = x&~y&z | ~x&~y&z | ~w&x&y | w&~x&y | w&x&y;
endmodule

Developed by: AMSAVARADHAN M 

RegisterNumber:25011322


**RTL realization**
<img width="1920" height="1080" alt="Screenshot 2025-11-20 142704" src="https://github.com/user-attachments/assets/4b29a008-111d-4f7c-a2f6-e5396b9c5d12" />


**RTL**
<img width="1920" height="1080" alt="Screenshot 2025-11-20 152218" src="https://github.com/user-attachments/assets/875c81d0-3777-4d15-9427-bfb5c535cc48" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

