## NAME : GOKUL S
## REG NO : 212224230075


# JKFLIPFLOP-USING-IF-ELSE

**AIM:** 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**JK Flip-Flop**

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.


![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/a649c30b-232b-4558-b188-fd6c09845180)



This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![jk ](https://github.com/user-attachments/assets/5abe94e2-2f70-4cd4-a88b-870200e24afc)


 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 
![jk 1](https://github.com/user-attachments/assets/153d0c89-e2fb-4220-bb0a-5b51b7f79604)


By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.

![jk3](https://github.com/user-attachments/assets/eadbfd35-c194-412f-b0b4-fd8e5984fe5a)


The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

**Procedure**

1.Create a new project

2.Write a code

3.Excute the code without any error

4.Next open RTL to get logic diagram 

5.Next University Program VWF 

6.Next right click at white space and select node -> list  and select '>>' and ok

7.next give the run time and the wave form is created 

8. The code is executed successfully

**PROGRAM**

![Screenshot 2025-04-16 094041](https://github.com/user-attachments/assets/b3acd072-fc5c-49f9-9b7c-bf6fa091389c)


**RTL LOGIC FOR  FLIPFLOPS**


![Screenshot 2025-04-16 093935](https://github.com/user-attachments/assets/f16e8334-e085-42b1-9787-6645715c13b2)



**TIMING DIGRAMS FOR FLIP FLOPS**
![Screenshot 2025-04-16 094313](https://github.com/user-attachments/assets/de2b28ab-83d3-48db-9d5d-33ea447db61b)


**RESULTS**

THE OUTPUT IS EXECUTED SUCCESSFULLY
