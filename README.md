# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**Procedure**

/* write all the steps invloved */

**PROGRAM**

![bitprg](https://github.com/user-attachments/assets/af115e5d-fbfa-4939-a321-563b56c56779)

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

 Developed by:Hitheshhwaran A R RegisterNumber:24005439
*/

**RTL LOGIC FOR 4 Bit Ripple Counter**


![bitlogic](https://github.com/user-attachments/assets/fadb829e-07af-4699-8403-2980e55f32fc)

**TIMING DIGRAMS FOR 4 Bit Ripple Counter**


![bitwav](https://github.com/user-attachments/assets/8db669ac-69ae-40b5-a299-23257e4518e7)

**RESULTS**
Therefore 4-Bit-Ripple-Counter register in always @ method using verilog and validating their functionally using their functional tables is verify.
