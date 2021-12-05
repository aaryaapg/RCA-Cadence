# RCA-Cadence
## Introduction
Ripple carry adder is a combinational logic circuit used for the purpose of adding two n-bit binary numbers. It is also known as n-bit parallel adder. It is constructed by cascading n full adders in series. The carry out of the first stage is fed to the carry in of the next stage. n-bit ripple carry adder requires N full adders.  
## Diagrams
**Block Diagram**

![image](https://user-images.githubusercontent.com/61982410/144753732-5bd5aa36-73a1-4b7f-a5c5-fde942969484.png)

**Truth Table**

![image](https://user-images.githubusercontent.com/61982410/144753710-b81ce173-710b-42ed-9841-47bbac2083a9.png)

## Implementation 
Following is the final implementation of a 4-bit Ripple Carry Adder in the Cadence® design environment. Four 4-bit full adders are cascaded to obtain 4-bit ripple carry adder. (a3,a2,a1,a0) & (b3,b2,b1,b0) are two 4-bit numbers that are to be added and (s3,s2,s1,s0) is the output obtained. Cout is the final carry.  

