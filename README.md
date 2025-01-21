# VHDL Counter with Overflow Handling
This repository demonstrates a common error in VHDL code:  counter overflow. The original code lacks explicit handling for when the counter reaches its maximum value.  The solution shows how to correctly implement overflow handling.

## Bug
The `bug.vhdl` file contains a simple counter.  However, when the counter reaches 15, it will overflow, leading to unpredictable behavior. 

## Solution
The `bugSolution.vhdl` file provides a corrected version.  It prevents the counter from overflowing by resetting the counter to 0 after reaching the maximum value (15).