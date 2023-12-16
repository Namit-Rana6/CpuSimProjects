# Basic Arithmetic Operators in CPU Simulation

Welcome to the Basic Arithmetic Operators project within the Semester One CPU Simulator! This project focuses on implementing assembly programs for fundamental arithmetic operations using the specified CPU simulation tool.

## Arithmetic Operations Implemented

The following arithmetic operations have been implemented:

1. **ADD Operation**
   - Assembly program for simulating the ADD operation on two user-entered numbers.

2. **SUBTRACT Operation**
   - Assembly program for simulating the SUBTRACT operation on two user-entered numbers.

3. **MULTIPLY Operations**
  - Assembly program for simulating the MULTIPLY operation on two user-entered numbers.

4. **DIVISION Operations**
   - Assembly program for simulating the DIVISION operation on two user-entered numbers.

## How to Use

1. Download the assembly programs for the desired arithmetic operation.
2. Open your CPU simulation tool.

   [Link to CPU Simulation Tool](https://cs.colby.edu/djskrien/CPUSim/)

3. Load or import the assembly program into the CPU simulation tool.

4. Execute the program and observe the results in the CPU registers.

##Issues and Feedback
If you encounter any issues or have feedback regarding the arithmetic operators implementation, feel free to open an issue in this repository. 
Happy computing!

## Example Code

Here's an example snippet of the ADD operation assembly program:

Modify the code as needed for other arithmetic operations.
```assembly
START   INP  NUM1    ; Load first number into the accumulator
        ADD  NUM2    ; Add second number to the accumulator
        STA  RESULT  ; Store the result in memory
        HLT         ; Halt the CPU
NUM1    DEC  0       ; First number (modify as needed)
NUM2    DEC  0       ; Second number (modify as needed)
RESULT  DEC  0       ; Result variable

