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

**PROGRAM**

![Screenshot 2024-12-27 111559](https://github.com/user-attachments/assets/90398be5-1d03-4927-acbd-c4420f039ead)


 Developed by: GUNASUNDARI B RegisterNumber: 24002680

**RTL LOGIC FOR 4 Bit Ripple Counter**

![Screenshot 2024-12-27 111606](https://github.com/user-attachments/assets/6e303252-08b9-47c7-b48c-eda7d5ef69c8)


**TIMING DIGRAMS FOR 4 Bit Ripple Counter**

![Screenshot 2024-12-27 111614](https://github.com/user-attachments/assets/9b1f0c05-a423-44e8-bd5b-74116d19f75c)


**RESULTS**

Hence the program was executed successfully.
