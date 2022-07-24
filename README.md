# Hardwired-self-checking-verification
Self-Checking hardware is automatically used to verify the design.

In this we instantiate design to verify whether our design is correct or not. A flag is asserted when the result is not equal to the golden result. Inputs are given from the ROM and the corresponding correct output (golden result) is also stored in ROM. So, after every application of input the output and the golden result is compared and thus the correctness of the design is verified.
