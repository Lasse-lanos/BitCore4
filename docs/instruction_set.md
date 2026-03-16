#instruction set
#the opcode in hex is in the () afer the instruction, the # stand for the operand


LDI: Loads Value into register A(1#)

MOV: Moves value from Register A into Register B (4#)

Add: Adds values in Register A and B and stores the result in Register A (2#)

Sub: Subtracts the value in Register B from Registor B (3#)

JMP: Jumps to the Adress in the selected Rom section (6#)

JMPif0: Jumps only when the value of Register A is 0 (7#)

ChangeRomSec: Changes to one of the 16 Rom sections for the JMP instruction (8#)

ChangeRambank: Changes the currently selected RamBank to # (9#)

WriteAintoRam: Writes the value of Register A into Ram at the adress # in the selected Rambank (a#)

LoadRamIntoA: Loads the value of the selected adress # in the Rambank into Register A (b#)

WriteVRam: Writes Register A into VRam at adress # (c#)

