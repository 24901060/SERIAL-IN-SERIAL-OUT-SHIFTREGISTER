# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Procedure**

/* write all the steps invloved */

**PROGRAM**

/* Program for flipflops and verify its truth table in quartus using Verilog programming.

Developed by:Praveen.S RegisterNumber:24901060

![393771871-81601a92-fe86-49b3-b809-0beb5bb6ef7b](https://github.com/user-attachments/assets/132f9953-e105-4412-be7e-0220d97f2c8e)


**RTL LOGIC FOR SISO Shift Register**
![393771928-e118159f-7e70-45fb-a2c0-8c91192b9422](https://github.com/user-attachments/assets/c3022c92-904d-45af-9f41-374f7276e136)

**TIMING DIGRAMS FOR SISO Shift Register**
![393772001-b2b85231-90a0-4055-a047-2bcfbb7f90db](https://github.com/user-attachments/assets/a6a6db0a-e909-4c12-8314-918d67f8eee4)

**RESULTS**
SISO Shift Register using verilog and validating their functionality using their functional tables has successful execution of the program.
