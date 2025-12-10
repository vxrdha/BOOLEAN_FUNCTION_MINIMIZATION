# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)| (~a&b&d)| (a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule 

Developed by: AMSAVARADHAN M 

RegisterNumber:25011322


**RTL realization**
<img width="1452" height="995" alt="388818050-ea817c83-7e85-4640-8911-f60fdca9e002" src="https://github.com/user-attachments/assets/add17927-0c59-4c2e-90b6-7f6cc479e241" />

**RTL**
<img width="1921" height="1201" alt="388818646-5c6f025f-7632-4952-98fe-b057294c40b1" src="https://github.com/user-attachments/assets/4be6f409-06b3-4c43-a76f-11d307d68513" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

