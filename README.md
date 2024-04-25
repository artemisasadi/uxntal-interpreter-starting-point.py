Status report
(Artemis Asadivand : 2882797A)

Program Overview:
The program is an assembly interpreter for a custom architecture called Uxn. It reads a program file with a .tal extension, tokenizes it, populates memory with the tokens, resolves labels, and executes the instructions.

Completed Tasks:

Implemented command-line flags for verbosity, debugging, and warnings (WW, V, VV, DBG).
Handled file existence check and extension validation for the input file.
Implemented tokenization of the program text.
Developed functions to populate memory, build a symbol table, and resolve labels.
Created functions for executing instructions, including memory operations, control operations, stack manipulation operations, and ALU operations.
Completed implementations for various stack operations (STH, DUP, SWP, OVR, NIP, POP, ROT).
Added ALU operations: ADD, SUB, MUL, DIV, INC, EQU, NEQ, LTH, GTH.
Implemented printing instructions (DEO).

Pending Tasks:
Implement POP function.
Review and finalize the stripComments function to ensure it properly removes comments.
Debug and finalize the resolveSymbols function to replace label references with addresses.
Ensure all implemented functions adhere to specifications and handle edge cases appropriately.
Note that comments spanning more than 2 lines aren't parsed correctly because of a bug.
