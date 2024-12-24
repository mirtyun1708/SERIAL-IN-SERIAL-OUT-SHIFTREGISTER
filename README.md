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

Developed by: Mirtyunjay S RegisterNumber:24013065

![Screenshot 2024-12-24 100327](https://github.com/user-attachments/assets/318eebb4-fce6-48f2-814a-475b65669712)


*/

**RTL LOGIC FOR SISO Shift Register**

![Screenshot 2024-12-24 100343](https://github.com/user-attachments/assets/b32f7c1b-51c4-410f-a385-278136a6fa5e)


**TIMING DIGRAMS FOR SISO Shift Register**

![Screenshot 2024-12-24 100358](https://github.com/user-attachments/assets/15904180-8b26-4571-8863-2eb83c40fe24)
![Screenshot 2024-12-24 100411](https://github.com/user-attachments/assets/00344142-a4c3-4320-9db2-27850303ac94)



**RESULTS**
```
Thus, the Serial-In Serial-Out (SISO) Shift Register is implemented using Verilog, and its
functionality is validated with the truth table and timing diagrams.
```

