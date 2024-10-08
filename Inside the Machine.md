INSIDE THE MACHINE
_An Illustrated Introduction to Microprocessors and Computer Architecture_
Jon Stokes
“The purpose of computing is insight, not numbers.”
—Richard W. Hamming (1915–1998)
1962, the era of digital computing was still very much in its infancy:
- Only about 10,000 computers in existence worldwide
- *Large and expensive* 
- Each required *teams of engineers for maintenance and operation*
- *Laboriously* inputting long strings of numbers
- *Waiting* for the machine to perform its calculations and then *interpreting* the resulting mass of ones and zeros
> This tedious and pain staking process prompted Hamming to remind his colleagues the reams of numbers they worked with on a daily basis were only a means to a much higher and often non-numerical end: keener insight into the world around them.

In stark contrast to the way things were 40 years ago, the experience of using a computer to do math on large sets of numbers is fairly foreign to many users, who spend only a very small fraction of their computer time explicitly performing arithmetic operations. Calculator application is tucked away somewhere in a folder and accessed only infrequently. Calculator application is the perfect metaphor for the modern computer’s ==**hidden identity**== as a shuffler of numbers.
> This book is aimed at reintroducing the computer as a calculating device that performs layer upon layer of miraculous sleights of hand in order to hide from the user the rapid flow of numbers inside the machine.
# Introduction
Inside the Machine is an introduction to computers:
- ==**to fill the gap**== that exists between classic but more challenging introductions to computer architecture, like John L. Hennessy’s and David A. Patterson’s popular textbooks.
- ==**the growing mass of works**== that are simply too basic for motivated non-specialist readers.
- Readers with some experience using computers and with even the most minimal scripting or programming experience should finish Inside the Machine with a ==**thorough and advanced understanding**== of the high-level organization of modern computers.
# BASIC COMPUTING CONCEPTS
## The Calculator Model of Computing
## The File-Clerk Model of Computing
### The Stored-Program Computer
### Refining the File-Clerk Model
## The Register File
## RAM: When Registers Alone Won’t Cut It
### The File-Clerk Model Revisited and Expanded
### An Example: Adding Two Numbers
## A Closer Look at the Code Stream: The Program
### General Instruction Types
### The DLW-1’s Basic Architecture and Arithmetic Instruction Format
## A Closer Look at Memory Accesses: Register vs. Immediate
### Immediate Values
### Register-Relative Addressing
# THE MECHANICS OF PROGRAM EXECUTION
## Opcodes and Machine Language
### Machine Language on the DLW-1
### Binary Encoding of Arithmetic Instructions
### Binary Encoding of Memory Access Instructions
### Translating an Example Program into Machine Language
## The Programming Model and the ISA
### The Programming Model
### The Instruction Register and Program Counter
### The Instruction Fetch: Loading the Instruction Register
### Running a Simple Program: The Fetch-Execute Loop
## The Clock
## Branch Instructions
### Unconditional Branch
### Conditional Branch
## Excursus: Booting Up
# PIPELINED EXECUTION
## The Lifecycle of an Instruction
## Basic Instruction Flow
## Pipelining Explained
## Applying the Analogy
### A Non-Pipelined Processor
### A Pipelined Processor
### The Speedup from Pipelining
### Program Execution Time and Completion Rate
### The Relationship Between Completion Rate and Program Execution Time
### Instruction Throughput and Pipeline Stalls
### Instruction Latency and Pipeline Stalls
### Limits to Pipelining
# SUPERSCALAR EXECUTION
## Superscalar Computing and IPC
## Expanding Superscalar Processing with Execution Units
### Basic Number Formats and Computer Arithmetic
### Arithmetic Logic Units
### Memory-Access Units
## Microarchitecture and the ISA
### A Brief History of the ISA
### Moving Complexity from Hardware to Software
## Challenges to Pipelining and Superscalar Design
### Data Hazards
### Structural Hazards
### The Register File
### Control Hazards
# THE INTEL PENTIUM AND PENTIUM PRO
## The Original Pentium
### Caches
### The Pentium’s Pipeline
### The Branch Unit and Branch Prediction
### The Pentium’s Back End
### x86 Overhead on the Pentium
### Summary: The Pentium in Historical Context
## The Intel P6 Microarchitecture: The Pentium Pro
### Decoupling the Front End from the Back End
### The P6 Pipeline
### Branch Prediction on the P6
### The P6 Back End
### CISC, RISC, and Instruction Set Translation
### The P6 Microarchitecture’s Instruction Decoding Unit
### The Cost of x86 Legacy Support on the P6
### Summary: The P6 Microarchitecture in Historical Context
## Conclusion
# POWERPC PROCESSORS: 600 SERIES, 700 SERIES, AND 7400
## A Brief History of PowerPC
## The PowerPC 601
### The 601’s Pipeline and Front End
### The 601’s Back End
### Latency and Throughput Revisited
### Summary: The 601 in Historical Context
## The PowerPC 603 and 603e
### The 603e’s Back End
### The 603e’s Front End, Instruction Window, and Branch Prediction
### Summary: The 603 and 603e in Historical Context
## The PowerPC 604
### The 604’s Pipeline and Back End
### The 604’s Front End and Instruction Window
### Summary: The 604 in Historical Context
## The PowerPC 604e
## The PowerPC 750 (aka the G3)
### The 750’s Front End, Instruction Window, and Branch Instruction
### Summary: The PowerPC 750 in Historical Context
## The PowerPC 7400 (aka the G4)
### The G4’s Vector Unit
### Summary: The PowerPC G4 in Historical Context
## Conclusion
# INTEL’S PENTIUM 4 VS. MOTOROLA’S G4E: APPROACHES AND DESIGN PHILOSOPHIES
## The Pentium 4’s Speed Addiction
## The General Approaches and Design Philosophies of the Pentium 4 and G4e
## An Overview of the G4e’s Architecture and Pipeline
## Branch Prediction on the G4e and Pentium 4
## An Overview of the Pentium 4’s Architecture
## An Overview of the Pentium 4’s Pipeline
## The Pentium 4’s Instruction Window
# INTEL’S PENTIUM 4 VS. MOTOROLA’S G4E: THE BACK END
## Some Remarks About Operand Formats
## The Integer Execution Units
## The Floating-Point Units (FPUs)
## The Vector Execution Units
## Conclusions
# 64-BIT COMPUTING AND X86-64
## Intel’s IA-64 and AMD’s x86-64
## Why 64 Bits?
## What Is 64-Bit Computing?
## Current 64-Bit Applications
## The 64-Bit Alternative: x86-64
## Conclusion
# The G5: IBM’s PowerPC 970
## Overview: Design Philosophy
## Caches and Front End
## Branch Prediction
## The Trade-Off: Decode, Cracking, and Group Formation
## The PowerPC 970’s Back End
## Load-Store Units
## Front-Side Bus
## The Floating-Point Units
## Vector Computing on the PowerPC 970
## Floating-Point Issue Queues
## The Performance Implications of the 970’s Group Dispatch Scheme
## Conclusions
# Understanding Caching and Performance
## Caching Basics
## Locality of Reference
## Cache Organization: Blocks and Block Frames
## Tag RAM
## Fully Associative Mapping
## Direct Mapping
## N-Way Set Associative Mapping
## Temporal and Spatial Locality Revisited: Replacement/Eviction Policies and
## Block Sizes
## Write Policies: Write-Through vs. Write-Back
## Conclusions
# Intel’s Pentium M, Core Duo, and Core 2 Duo
## Code Names and Brand Names
## The Rise of Power-Efficient Computing
## Power Density
## The Pentium M