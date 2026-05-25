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


i) 
module boolean(a,b,c,d,f1);

input a,b,c,d;

output f1; 

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule 

ii) 
module bool(w,x,y,z,f2); 

input w,x,y,z; 

output f2; 

assign f2=((~y & z)|( w & y )|(x & y)); 

endmodule
*/



Developed by: K NIVEDHA RegisterNumber: 212225230204

**RTL realization**
<img width="1467" height="810" alt="Screenshot 2026-05-25 140409" src="https://github.com/user-attachments/assets/e4fc8147-954d-4d08-8416-7e42f850ddc6" />


**Output:**
<img width="1600" height="852" alt="WhatsApp Image 2026-05-21 at 14 43 57" src="https://github.com/user-attachments/assets/aaa9ae18-8253-4434-b2c7-6317f54f38e9" />

**RTL**
<img width="1337" height="854" alt="Screenshot 2026-05-25 140747" src="https://github.com/user-attachments/assets/7e746d3f-ad7b-4363-9326-e315fdbc629a" />

**Timing Diagram**
<img width="1600" height="852" alt="WhatsApp Image 2026-05-21 at 14 43 57 (1)" src="https://github.com/user-attachments/assets/06f0dd1d-aab9-408b-8743-5ccdd886718c" />








**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

