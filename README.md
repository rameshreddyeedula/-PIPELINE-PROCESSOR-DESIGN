# -PIPELINE-PROCESSOR-DESIGN

COMPANY: CODTECH IT SOLUTIONS

NAME: EEDULAKANTI RAMESH REDDY

INTERN ID: COD123

DOMAIN: VLSI

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH


# DESCRIPTION OF MY TASK

This project is about creating a simple 4-stage pipelined processor in Verilog that can perform basic instructions like ADD, SUB, and LOAD. The pipeline has four stages: Instruction Fetch (IF), Instruction Decode (ID), Execute (EX), and Write Back (WB). Each instruction goes through these stages step by step, and thanks to pipelining, multiple instructions can be processed at the same time, each in a different stage. The processor reads instructions from memory, decodes them to find out what operation to do, performs the operation, and finally writes the result back into the register file. A testbench was used to check that everything works correctly, and the simulation waveform shows that instructions are flowing properly through all stages. The correct data appears in the right registers at the right time, proving that the processor design is working as expected. 

 The design uses pipeline registers between stages to hold data temporarily as it moves through the processor. A testbench was written to simulate the processor by loading instructions and initializing data. The simulation shows that the processor correctly fetches, decodes, executes, and writes back instructions. The waveform confirms that the pipeline stages work properly, with data and instructions updating at each clock cycle without conflict. The register file and memory update correctly, and the results match the expected values for each instruction. 
 
 Pipeline registers are used between each stage to hold the instruction and data as they pass through the processor. This allows each stage to operate independently and process a different instruction every cycle. For example, while one instruction is being executed in the EX stage, another one can be decoded in the ID stage, and a third can be fetched from memory in the IF stage. This overlapping of instruction execution is what makes pipelining efficient. A testbench was also written to simulate and verify the processor's behavior. The testbench loads instructions into memory, sets initial values in the registers, and runs the processor over several clock cycles. The simulation was observed using a waveform viewer, and it clearly showed how instructions move through each stage of the pipeline.

The waveform results confirmed that the pipeline works correctly. Instructions entered and exited each stage in order, the ALU performed the correct operations, and the register file was updated with the right results at the right time. The processor handled all three instruction types without errors or conflicts. This project demonstrates a solid understanding of pipelined processor architecture and how to implement it using Verilog. It provides a good foundation for learning more complex CPU design topics such as hazard detection, forwarding, branching, and control logic. 


<img width="327" alt="Image" src="https://github.com/user-attachments/assets/db0c6f9b-49d4-46e6-b8c8-94fa00b858db" />

<img width="286" alt="Image" src="https://github.com/user-attachments/assets/dbc52e8e-9051-4c1e-9df1-96e80468601e" />

<img width="953" alt="Image" src="https://github.com/user-attachments/assets/884a4f6d-22bc-4baf-8efc-b7517e0ff109" />
