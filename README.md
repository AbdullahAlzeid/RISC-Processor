# RISC Processor Design

## Overview
This repository contains the design and implementation of a Reduced Instruction Set Computer (RISC) processor. The project is developed using Logisim, a tool for designing and simulating digital logic circuits. It includes various components like ALU, Register File, and Control Unit, essential for a functional RISC processor.

## Features
- **ALU (Arithmetic Logic Unit)**: Performs arithmetic and logical operations.
- **Register File**: Stores data temporarily while operations are executed.
- **Control Unit**: Manages the operations of the processor and its data flow.
- **Single Cycle Processor**: Executes one instruction per clock cycle.
- **Test Files**: Includes assembly and hexadecimal test files for validating processor functionality.

## Components
- **CPU Circuit**: The central processing unit design. ([CPU.circ](https://github.com/AbdullahAlzeid/RISC-processor/blob/main/Project/202_ICS233_53_COE301_52_Group1_SingleCycle/Circuts/CPU.circ))
- **Register File Circuit**: Manages the registers in the processor. ([RegisterFile.circ](https://github.com/AbdullahAlzeid/RISC-processor/blob/main/Project/202_ICS233_53_COE301_52_Group1_SingleCycle/Circuts/RegisterFile.circ))
- Other essential circuits like ALU, Full Adder, and various control units.

## How to Use
1. **Install Logisim**: Download and install Logisim from [Logisim's official website](http://www.cburch.com/logisim/).
2. **Clone the Repository**: git clone https://github.com/AbdullahAlzeid/RISC-processor.git
3. **Open the Circuit Files**: Navigate to the `Circuts` folder and open the `.circ` files using Logisim.

## Testing
- Load the provided test files (`.asm` and `.hex`) in the processor simulation to validate its functionality.
- Test files include examples like BubbleSort and Count1s.

## Project Report
- A detailed project report is available, explaining the design and implementation aspects. ([Project Report.pdf](https://github.com/AbdullahAlzeid/RISC-processor/blob/main/Project/202_ICS233_53_COE301_52_Group1_SingleCycle/Project%20Report.pdf))


## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


