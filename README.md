# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

![th](https://github.com/user-attachments/assets/0771c482-4c64-4b41-8663-cb0d0c98d590)


**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:V.KAILASH
RegisterNumber:24001383
 module exp2booleanfunctionminimization(a,b,c,d,f1,w,x,y,z,f2);
 input a,b,c,d,w,x,y,z;
 output f1,f2;
 assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
 assign f2=((~y&z)|(x&y)|(w&y));
 endmodule










*/


**RTL realization**

**Output:**

**RTL**

![Screenshot (38)](https://github.com/user-attachments/assets/6e3d4b47-6d9d-4ce3-b3b3-5548dbc9c3de)


**Timing Diagram**

![Screenshot (39)](https://github.com/user-attachments/assets/4e855260-62c2-48c4-ae5d-7e93e13033d4)


**Result:**
 Thus the given logic functions are implemented using and their operations are verified
 using Verilog programming.
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

