# HALF_SUBTRACTOR

**AIM:**

To simulate and synthesis Half Subtractor using vivado.

****Apparatus Required:**

vivado 2023.2 software.

**Procedure:**

STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 compare the output with truth table.

**Truth Table**

![301804926-d0d5980a-6bcf-4ede-a54e-6aae3fb5f5f2](https://github.com/pullurur/HALF_SUBTRACTOR/assets/161436550/42da00ca-95f6-43bb-9f4d-7bae2292a83a)

**Circuit Diagram**

![301805056-df70da69-5a12-4a0d-ab84-a98dad3f7e70](https://github.com/pullurur/HALF_SUBTRACTOR/assets/161436550/c7d69dfe-67a9-4fbd-a655-3208b504d0f0)

**verilog code:**

module halfsubtractor(a,b,diff,borrow);

input a,b;

output diff,borrow;

xor g1(diff,a,b);

and g2(borrow,~a,b);

endmodule

**output:**

![318193107-ed874774-4c75-466d-a162-75234925dc87](https://github.com/pullurur/HALF_SUBTRACTOR/assets/161436550/dc3d68d3-cd89-43cc-8e1d-e5af7f224586)


**Result:**

Thus,the verilog program for half subtractor has been simulated and verified successfully.
