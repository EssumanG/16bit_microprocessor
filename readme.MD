# Introduction
what is this project about?

What is Microprocessor(single Cycle Processor)?

What is the wordsize of the processor?

### The component of the processor

    1.Register File 
    2.ALU
    3.Control Unit
    4.Instruction Memory
(Explain the functions of each)

## Getting Started

### Technology used
What technology is used?

How to install this technology?



## Cloning the Repository

To clone the Legacy Game Engine repository, follow the steps below:

    """ repository-url """



 ## Instruction Set

#### R-Type Instructions
For R-Type instructions, the format is as follows:

    Opcode (5 bits)
    RS (Source Register, 4 bits)
    RD (Destination Register, 4 bits)
    Unused (3 bits)
The following R-Type instructions are implemented:

    ADD (Opcode: 2)
    SUB (Opcode: 6)
    NEG (Opcode: 10)
    AND (Opcode: 4)
    OR (Opcode: 8)


#### I-Type Instructions
For I-Type instructions, the format is as follows:

    Opcode (5 bits)
    RD (Destination Register, 4 bits)
    Immediate (Remaining bits)

The following I-Type instructions are implemented:

    LOAD (Opcode: 1)
    STORE (Opcode: 2)
    ORI (Opcode: 16)
    ANDI (Opcode: 15)
    SUBI (Opcode: 13)
    ADDI (Opcode: 11)
    


#### J-Type Instructions
For J-Type instructions, the format is as follows:

    Opcode (5 bits)
    Address to Jump To (Remaining bits)

The following J-Type instructions are implemented:
    JUMP (Opcode: 3)




## Example Instructions
Here are some examples of how instructions are encoded:

ADD R1, R2, R3 is encoded as 00100 0001 0010 000
LOAD R4, #42 is encoded as 00001 0100 00101010
JUMP 0x123 is encoded as 00011 0000 00000100 01000011

