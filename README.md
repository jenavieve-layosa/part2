# part2
Your program should accept all strings (opcodes, register names, and immediate operands) using upper or lower case. As a suggestion, you might want to convert all letters to upper or lower case to make it easier to parse the commands.

Your program will implement the registers r0-r7. These registers should be implemented using the uint32_t type and should be initialized to 0x0 before your code begins reading it’s input. Changes made to a register by one instruction should persist and be available in subsequent instructions.

Your code will read each input line, perform the specified instruction, and print the result. You may format the output in any way that makes the results easy to view. At a minimum, the output must show which register was changed by the instruction, the instruction, and the new value for that register; all of which is should be easily understood by anyone running the code.

You will not be given an input file for this part of the project. As part of the development, you will generate your own input file with appropriate test cases to ensure that your code correctly implements all the instructions. In addition, this code should be written in C/C++
