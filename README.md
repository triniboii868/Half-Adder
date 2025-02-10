# Binary Addition
Binary addition is somewhat similar to regular addition, but a tad different. It is similar in the way that they are added from the rightmost 
place value to the leftmost place value. The difference comes where the values can only contain 0's and 1's instead of 0-9 in regular addition. 

## How to do Addition in Binary.
0 + 0 = 0 → Nothing changes, just like in normal math.
0 + 1 or 1 + 0 = 1 → Adding 1 to 0 is still just 1, no surprises there.
1 + 1 = 10 → This is where binary is different. In decimal, 1 + 1 is 2, but since binary only has 0 and 1, there’s no "2." Instead, we write 0 
and carry over a 1 to the next column, just like how 5 + 5 in decimal makes 10, and you carry the 1. So, binary addition is similar to regular 
addition but with carrying happening sooner— whenever you reach 2 instead of 10.

# Half-Adder, What is it?
A half adder is basically a digital logic circuit that adds two single-bit binary numbers, for instance the examples given above. These adders
start wiith two binary inputs which subsequently produce a "sum" output, denoted by S, and a "carry" output denoted by C<sup>out</sup>. 
The sum bit represents the least significant bit of the addition and the carry-out bit of 0 or 1. 

## Symbol for Half-Adder

![Screenshot 2025-02-10 014318](https://github.com/user-attachments/assets/fa04dd62-2344-4714-8756-13a7fb5b56a7)


# Truth Table for a Half-Adder

![Screenshot 2025-02-10 015155](https://github.com/user-attachments/assets/48779ef3-185a-49ce-9e54-b5b67a75a3b9)


# Diagram of a Half-Adder
From the diagram, we can see two inputs A and B which are the two initial binary inputs. They are connected to XOR and AND gates, which produces
the S and C<sub>out</sub> outputs respectively. 

![Screenshot 2025-02-10 010043](https://github.com/user-attachments/assets/e5717d85-d268-4eae-94e9-2056b38d6284)

## Setup (A = 0, B = 0)
Both inputs A, B are 0, resulting in a 0 as seen in the truth table above in Figure 5-9. The both LEDs are off, indicating that the sum nor the
carry has a signal. 

![image](https://github.com/user-attachments/assets/1ece4e3c-e7a3-4303-be8e-ab47d77e7c7b)

## Setup (A = 0, B = 1)
Input A is 0 and input B is 1, going through the circuit the XOR gate produces a S output of 1, while the AND gate keeps the carry output as 0.
The S LED is lit up, showing that there was a sum of 1 with no carry. 

![image](https://github.com/user-attachments/assets/588b5e40-4d4e-4251-97d0-2e33abb8de1f)

## Setup (A = 1, B = 1)
In the final setup, both inputs A and B is 1, through the XOR gate it outputs a sum output of 0, but has a carry output of 1. The carry led is
lit up, showing that a carry has been produced. 

![image](https://github.com/user-attachments/assets/4409f228-049e-492a-9943-e39eddb3f7c7)

## Difference Engines
### Image of Difference Engine

![image](https://github.com/user-attachments/assets/f8f398cd-2131-42d5-a733-1a2bda525e6d)


### What are they and how are they similar/different to the Half-Adder?

Difference engines are mechanical calculators designed to perform arithmetic functions repeatedly by adding values within columns. These 
calculations are generated based on the initial input into the engine, where the ouput is achieved through a system of gears and wheels 
that represent digits and generates table outputs. The half-adder is similar to this as it generates tables based on the addition of 0 and 1 
inputs within columns. However, they are considerably smaller and render different outputs as it performs less complicated functions. 

# Works Cited 

Why we should remember the public announcement of the Difference Engine. (2023, November 23). HistoryExtra. https://www.historyextra.com/period/georgian/why-remember-charles-babbage-difference-engine/

Justice, M. (2020). How computers really work [Book]. No Starch Press. 

