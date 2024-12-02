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
Developed by:MOTTA KATTA MOUNIKA 
RegisterNumber:24010589
```
```
 module booleanfunction(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
 endmodule
```

**RTL realization**
![Screenshot 2024-12-03 000503](https://github.com/user-attachments/assets/528f6bc8-d74d-4f27-ad80-5ba736205928)

**Output:**
![Screenshot 2024-12-03 000855](https://github.com/user-attachments/assets/bed50dc2-00a5-48e9-864d-3e3b3f6ab606)

**RTL**

**Timing Diagram**
![Screenshot 2024-12-03 001004](https://github.com/user-attachments/assets/d45c41ec-7269-4fde-9cf2-a45f5cc59828)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

