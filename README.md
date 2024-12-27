### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

Program for logic gates and verify its truth table in quartus using Verilog programming
'''module log_gat(a,b,c1,c2,c3,c4,c5,c6,c7);
input a,b;
output c1,c2,c3,c4,c5,c6,c7;
not g1(c1,a);
and g2(c2,a,b);
or g3(c3,a,b);
nand g4(c4,a,b);
nor g5(c5,a,b);
xor g6(c6,a,b);
xnor g7(c7,a,b);
endmodule
'''

 Developed by: RegisterNumber:212224040039 
 
**Logic symbol & Truthtable**
AND Gate:
![image](https://github.com/user-attachments/assets/aaa7db26-dc47-4f8f-8f8d-8e6ceefb5576)

NOT Gate:
![image](https://github.com/user-attachments/assets/b97929e2-5bc2-4be3-ab65-0e11c2d6b2bf)

OR Gate:
![image](https://github.com/user-attachments/assets/5df2ea58-51e2-4244-a56f-309a5c962eaa)

NAND Gate:
![image](https://github.com/user-attachments/assets/3f241f8d-b6f4-4438-89a6-dd5d0926939c)

NOR Gate:
![image](https://github.com/user-attachments/assets/17a5aef0-5678-4483-9c66-232ef88a639a)

XOR Gate:
![image](https://github.com/user-attachments/assets/d75a343f-371d-48ab-9219-2019c075be7b)

XNOR Gate:
![image](https://github.com/user-attachments/assets/54839c41-5221-4984-9b4f-18b66f5b92ef)


**RTL realization Output:** 
![exp 1](https://github.com/user-attachments/assets/0496f509-fa21-44b0-9fec-eaabda22cc88)


**RTL**
![ep 1 1](https://github.com/user-attachments/assets/2e48e689-bf33-4cc5-a712-3dd6fd6a7bdc)

**Result:**
 The truth tables of the logic gates were successfully studied and verified using Verilog programming in Quartus II. The implementation and simulation results matched the expected outcomes for each gate.

