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
