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
~~~
**Program:**
i)
i)
module EXPERIMENT2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule


ii)
module ex21(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(w&y)|(x&y));
endmodule

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:prabanjan r
RegisterNumber:24900174
~~~

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/


**RTL realization**
![389980393-7cd263ce-bd48-476e-922b-cc9bf1fc5a39](https://github.com/user-attachments/assets/7d630c9b-50ab-4822-8110-28a0768ca745)
![389980527-fc7668d6-9af6-416f-afc3-caf632850a3e](https://github.com/user-attachments/assets/f7ac4961-5408-4a38-8a64-bc1cbb3e9ad4)

**Output:**

**waveform**
![389980700-75afa2be-b08d-4134-8930-7c8de8679209](https://github.com/user-attachments/assets/58c267bf-42a5-41f2-b631-635f928fb634)
![389980889-2fa79445-ec9b-42cf-a2d7-af43beffcf66](https://github.com/user-attachments/assets/a47bfb4f-b946-4bfe-bcfc-5878bf170f64)

**Timing Diagram**

**Result:**
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

