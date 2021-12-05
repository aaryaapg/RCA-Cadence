# RCA-Cadence
## Introduction
Ripple carry adder is a combinational logic circuit used for the purpose of adding two n-bit binary numbers. It is also known as n-bit parallel adder. It is constructed by cascading n full adders in series. The carry out of the first stage is fed to the carry in of the next stage. n-bit ripple carry adder requires N full adders.  
## Diagrams
**_Block Diagram:_**

![image](https://user-images.githubusercontent.com/61982410/144753732-5bd5aa36-73a1-4b7f-a5c5-fde942969484.png)

**_Truth Table:_**

![image](https://user-images.githubusercontent.com/61982410/144753710-b81ce173-710b-42ed-9841-47bbac2083a9.png)

## Implementation 
Following is the final implementation of a 4-bit Ripple Carry Adder in the Cadence® design environment. Four 4-bit full adders are cascaded to obtain 4-bit ripple carry adder. (a3,a2,a1,a0) & (b3,b2,b1,b0) are two 4-bit numbers that are to be added and (s3,s2,s1,s0) is the output obtained. Cout is the final carry.  

**_Final Schematic of 4-bit Ripple Carry Adder:_**

![image](https://user-images.githubusercontent.com/61982410/144754071-79586869-1563-44e2-82f3-159074416dc7.png)

## Results
**(a) When inputs are A(0001) & B(0011)**

![image](https://user-images.githubusercontent.com/61982410/144754247-a5696385-3ab1-4880-ad31-f142d8f921af.png)

**(b) When inputs are A(0011) & B(0011)**

![image](https://user-images.githubusercontent.com/61982410/144754260-3355919b-6a76-404d-a28d-e47af3da4256.png)

**(c) When inputs are A(0111) & B(0111)**

![image](https://user-images.githubusercontent.com/61982410/144754271-fa8ddb5c-22b3-4fc1-8d08-a3d2720e9b8d.png)

**(d) When inputs are A(1111) & B(0111)**

![image](https://user-images.githubusercontent.com/61982410/144754275-8dba6dd0-5c43-44d0-8998-6ab7e489b48d.png)
