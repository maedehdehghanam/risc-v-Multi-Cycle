# Computer Architecture Course Project

This repository contains the course project for the Computer Architecture course. The project involves the design and implementation of a multi-cycle V-RISC processor and the execution of a machine language program. The project progresses through various stages, including synthesis, and assumes that the design for the 2-115DE board is complete. The basic state machine used in the project is a Moore machine that takes \[6:0\]op as input and produces sets of outputs.

## Project Description

The goal of this project is to design and implement a multi-cycle V-RISC processor capable of executing machine language programs. The processor will be designed for the 2-115DE board. The project progresses through different stages, starting from the design phase and culminating in the execution of a machine language program.

The design of the processor will involve defining the various stages of the multi-cycle architecture, including instruction fetch, decode, execution, memory access, and write-back. Each stage will be carefully designed to ensure correct operation and efficient execution of instructions.

The synthesis stage of the project will focus on translating the processor design into a circuit implementation suitable for the 2-115DE board. This stage will involve mapping the processor components to specific hardware resources and optimizing the design for performance and area constraints.

The processor's basic state machine will be implemented as a Moore machine. It will take \[6:0\]op, representing the opcode of the instruction, as input and produce sets of outputs. The outputs will be defined for each state, and any output not listed in any state will be implicitly set to zero.
![Uploading image.png…]()

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). You are free to modify and use the code for personal and educational purposes.
