# Simple-Processor
This is a simple 8-bit single-cycle processor  which  includes  an ALU, a register file and control logic, using Verilog HDL. This was designed as a part of CO224 Computer Architecture course. 

## Part1 -ALU
In this part we designed 8-bit ALU.It can perform four different functions to  support  the instructions add,  sub,  and,  or, mov, and loadi 

![alu](https://github.com/PiyumaliSandunika/Simple-Processor/assets/73444543/d85e7aa6-5786-4da7-bfc3-fa6bbcdab1d3)


## Part2 -Register File 
For this part a simple 8×8 register file was designed. The purpose of the register file is to store output values generated by the ALU, and to supply the ALU's inputs with operands

![mem](https://github.com/PiyumaliSandunika/Simple-Processor/assets/73444543/4e33f87c-e2f2-4b14-87a5-5e31393b87ce)


## Part 3 –Integration & Control

Here we composed a working CPU using our ALU and Register File, supporting the instructions add, sub, and, or, mov, and loadi. To  do  this, control logic of the CPU was implemented. 

![ctrl](https://github.com/PiyumaliSandunika/Simple-Processor/assets/73444543/676999cf-d741-4ce7-998f-08168d8d1d3a)

## Part 4–Flow Control Instructions

Here we added  microarchitectural support  for  the  flow  control instructions j and beq.

## Part 5–Extended ISA

Here we added some additional instruction supported by our CPU 
