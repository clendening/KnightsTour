# Knights Tour
Designed an FPGA for controlling a robot to perform the "knight's tour" puzzle on a chess board. 
Design was done using System Verilog, with considerations for synthesizability such as area and meeting timing. 

# How to build the code
Prerequisites for building the code include questasim installation.
Run the command make to build the code.

# How to run automated testing of the code
Prerequisites for building the code include questasim installation.
Run the command make test to run the automated testing suite.
A message of "Yahoo! All tests passed :)" indicates a successful test run.

# How to synthesize the code to hardware
Prerequisites for synthesis include design_vision installation.
Run the command make synth to synthesize the systemverilog into hardware.
Outputs can be found in the synthesis/ directory.
