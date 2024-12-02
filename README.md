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
```
Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
Developed by:Abisha Linu.L
RegisterNumber:24900028

```
```
module funct1(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
 endmodule
```
**RTL realization**

![Screenshot 2024-12-02 184511](https://github.com/user-attachments/assets/3fa9fcff-45e8-4c2b-8c12-67cefaa51abe)

**Output:**

![Screenshot 2024-12-02 185144](https://github.com/user-attachments/assets/2a822641-24ff-4a7e-acd2-98a4ac252426)

**RTL**

**Timing Diagram**

![Screenshot 2024-12-02 190104](https://github.com/user-attachments/assets/654bad7b-28c7-4dea-98d3-fbb35b9c7e1c)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

