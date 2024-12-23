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


**Program:**<br>
module ex2(a,b,c,d,f1,w,x,y,z,f2);<br>
input a,b,c,d,w,x,y,z;<br>
output f1,f2;<br>
assign f1=((~b&~c)|(~a&b&d)|(a&b&~c));<br>
assign f2=((~y&z)|(x&y)|(w&y));<br>
endmodule<br>
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

Developed by:HARIHARASUDHAN N RegisterNumber:*/24900208


**RTL realization**<br>
![Screenshot 1](https://github.com/user-attachments/assets/e9f042e7-626d-451a-861b-69d36dd45feb)


**Output:**

**RTL**

**Timing Diagram**<br>
![image](https://github.com/user-attachments/assets/400e2338-9796-4a0d-bf29-5c6709466e69)


**Result:**<br>

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

