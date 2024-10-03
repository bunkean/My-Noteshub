> _Assembly Language for x86 Processors, Eighth Edition,_ teaches assembly language programming and architecture for x86 and Intel64 processors
# Basic Concepts
## Welcome to Assembly Language
### Questions You Might Ask
### Assembly Language Applications
### Section Review
## Virtual Machine Concept
### Section Review
## Data Representation
### Binary Integers
### Binary Addition
### Integer Storage Sizes
### Hexadecimal Integers
### Hexadecimal Addition
### Signed Binary Integers
### Binary Subtraction
### Character Storage
### Binary-Coded Decimal (BCD) Numbers 
### Section Review
## Boolean Expressions
### Truth Tables for Boolean Functions
### Section Review
## Chapter Summary 
## Key Terms
## Review Questions and Exercises
### Short Answer
### Algorithm Workbench
# x86 Processor Architecture
## General Concepts
### Basic Microcomputer Design
### Instruction Execution Cycle
### Reading from Memory
### Loading and Executing a Program
### Section Review 
## 32-Bit x86 Processors
### Modes of Operation
### Basic Execution Environment
### x86 Memory Management
### Section Review
## 64-Bit x86-64 Processors
### 64-Bit Operation Modes
### Basic 64-Bit Execution Environment
### Section Review
## Components of a Typical x86 Computer
### Motherboard
### Memory
### Section Review
## Input-Output System
### Levels of I/O Access
### Section Review
## Chapter Summary
## Key Terms 
## Review Questions
# Assembly Language Fundamentals 
## Basic Language Elements
### First Assembly Language Program
### Integer Literals
### Constant Integer Expressions
### Real Number Literals
### Character Literals
### String Literals
### Reserved Words
### Identifiers
### Directives
### Instructions
### Section Review
## Example: Adding and Subtracting Integers

### The AddTwo Program

### Running and Debugging the AddTwo Program

### Program Template

### Section Review

## Assembling, Linking, and Running Programs

### The Assemble-Link-Execute Cycle

### Listing File

### Section Review

## Defining Data

### Intrinsic Data Types

### Data Definition Statement

### Adding a Variable to the AddTwo Program

### Defining BYTE and SBYTE Data

### Defining WORD and SWORD Data

### Defining DWORD and SDWORD Data

### Defining QWORD Data

### Defining Packed BCD (TBYTE) Data

### Defining Floating-Point Types

### A Program That Adds Variables

### Little-Endian Order

### Declaring Uninitialized Data

### Section Review

## Symbolic Constants

### Equal-Sign Directive

### Calculating the Sizes of Arrays and Strings

### EQU Directive

### TEXTEQU Directive

### Section Review

## Introducing 64-Bit Programming

## Chapter Summary

## Key Terms

### Terms

### Instructions, Operators, and Directives

## Review Questions and Exercises

### Short Answer

### Algorithm Workbench

## Programming Exercises
# Data Transfers, Addressing, and Arithmetic

## Data Transfer Instructions

### Introduction

### Operand Types

### Direct Memory Operands

### MOV Instruction

### Zero/Sign Extension of Integers

### LAHF and SAHF Instructions

### XCHG Instruction

### Direct-Offset Operands

### Examples of Moving Data

###  Section Review

## Addition and Subtraction

### INC and DEC Instructions

### ADD Instruction

### SUB Instruction

### NEG Instruction

### Implementing Arithmetic Expressions

### Flags Affected by Addition and Subtraction

### Example Program (AddSubTest)

### Section Review

## Data-Related Operators and Directives

### OFFSET Operator

### ALIGN Directive

### PTR Operator

### TYPE Operator

### LENGTHOF Operator

### SIZEOF Operator

### LABEL Directive

### Section Review

## Indirect Addressing

### Indirect Operands

### Arrays

### Indexed Operands

### Pointers

### Section Review

## JMP and LOOP Instructions

### JMP Instruction

### LOOP Instruction

### Displaying an Array in the Visual Studio Debugger

### Summing an Integer Array

### Copying a String

### Section Review

## 64-Bit Programming

### MOV Instruction

### 64-Bit Version of SumArray

### Addition and Subtraction

### Section Review

## Chapter Summary

## Key Terms

### Terms

### Instructions, Operators, and Directives

## Review Questions and Exercises

### Short Answer

### Algorithm Workbench

## Programming Exercises
#  Procedures

## Stack Operations

### Runtime Stack (32-Bit Mode)

### PUSH and POP Instructions

### Section Review

## Defining and Using Procedures

### PROC Directive

### CALL and RET Instructions

### Nested Procedure Calls

### Passing Register Arguments to Procedures

### Example: Summing an Integer Array

### Saving and Restoring Registers

### Section Review

## Linking to an External Library

### Background Information

### Section Review

## The Irvine32 Library

### Motivation for Creating the Library

### The Win32 Console Window

### Individual Procedure Descriptions

### Library Test Programs

### Section Review

## 64-Bit Assembly Programming

### The Irvine64 Library

### Calling 64-Bit Subroutines

### The x64 Calling Convention

### Sample Program that Calls a Procedure

### Section Review

## Chapter Summary

## Key Terms

### Terms

### Instructions, Operators, and Directives

## Review Questions and Exercises

### Short Answer

## Algorithm Workbench

## Programming Exercises

#  Conditional Processing

## Boolean and Comparison Instructions

### The CPU Status Flags

### AND Instruction

### OR Instruction

### Bit-Mapped Sets

### XOR Instruction

### NOT Instruction

### TEST Instruction

### CMP Instruction

### Setting and Clearing Individual CPU Flags

### Boolean Instructions in 64-Bit Mode

### Section Review

## Conditional Jumps

### Conditional Structures

### Jcond Instruction

### Types of Conditional Jump Instructions

### Conditional Jump Applications

### Section Review

## Conditional Loop Instructions

### LOOPZ and LOOPE Instructions

### LOOPNZ and LOOPNE Instructions

### Section Review

## Conditional Structures

### Block-Structured IF Statements

### Compound Expressions

### WHILE Loops

### Table-Driven Selection

### Section Review

## Application: Finite-State Machines

### Validating an Input String

### Validating a Signed Integer

### Section Review

## Conditional Control Flow Directives (Optional topic)

### Creating IF Statements

### Signed and Unsigned Comparisons

### Compound Expressions

### Creating Loops with .REPEAT and .WHILE

## Chapter Summary

## Key Terms

### Terms

### Instructions, Operators, and Directives

## Review Questions and Exercises

### Short Answer

### Algorithm Workbench

## Programming Exercises

### Suggestions for Testing Your Code

### Exercise Descriptions

# Integer Arithmetic

## Shift and Rotate Instructions

### Logical Shifts and Arithmetic Shifts

### SHL Instruction

### SHR Instruction

### SAL and SAR Instructions

### ROL Instruction

### ROR Instruction

### RCL and RCR Instructions

### Signed Overflow

### SHLD/SHRD Instructions

### Section Review

## Shift and Rotate Applications

### Shifting Multiple Doublewords

### Multiplication by Shifting Bits

### Displaying Binary Bits

### Extracting File Date Fields

### Section Review

## Multiplication and Division Instructions

### Unsigned Integer Multiplication (MUL)

### Signed Integer Multiplication (IMUL)

### Measuring Program Execution Times

### Unsigned Integer Division (DIV)

### Signed Integer Division (IDIV)

### Implementing Arithmetic Expressions

### Section Review

## Extended Addition and Subtraction

### ADC Instruction

### Extended Addition Example

### SBB Instruction

### Section Review

## ASCII and Unpacked Decimal Arithmetic

### AAA Instruction

### AAS Instruction

### AAM Instruction

### AAD Instruction

### Section Review

## Packed Decimal Arithmetic

### DAA Instruction

### DAS Instruction

### Section Review

## Chapter Summary

## Key Terms

### Terms

### Instructions, Operators, and Directives

## Review Questions and Exercises

### Short Answer

### Algorithm Workbench

## Programming Exercises

# Advanced Procedures

## Introduction

## Stack Frames

### Stack Parameters

### Disadvantages of Register Parameters

### Accessing Stack Parameters

### 32-Bit Calling Conventions

### Local Variables

### Reference Parameters

### LEA Instruction

### ENTER and LEAVE Instructions

### LOCAL Directive

### The Microsoft x64 Calling Convention

### Section Review

## Recursion

### Recursively Calculating a Sum

### Calculating a Factorial

### Section Review

## INVOKE, ADDR, PROC, and PROTO

### INVOKE Directive

### ADDR Operator

### PROC Directive

### PROTO Directive

### Parameter Classifications

### Example: Exchanging Two Integers

### Debugging Tips

### WriteStackFrame Procedure

### Section Review

## Creating Multimodule Programs

### Hiding and Exporting Procedure Names

### Calling External Procedures

### Using Variables and Symbols across Module​Boundaries

### Example: ArraySum Program

### Creating the Modules Using Extern

### Creating the Modules Using INVOKE and PROTO

### Section Review

## Advanced Use of Parameters (Optional Topic)

### Stack Affected by the USES Operator

### Passing 8-Bit and 16-Bit Arguments on the Stack

### Passing 64-Bit Arguments

### Non-Doubleword Local Variables

## Java Bytecodes (Optional Topic)

### Java Virtual Machine

### Instruction Set

### Java Disassembly Examples

### Example: Conditional Branch

## Chapter Summary

## Key Terms

### Terms

### Instructions, Operators, and Directives

## Review Questions and Exercises

### Short Answer

### Algorithm Workbench

## Programming Exercises

# Strings and Arrays

## Introduction

## String Primitive Instructions

### MOVSB, MOVSW, and MOVSD

### CMPSB, CMPSW, and CMPSD

### SCASB, SCASW, and SCASD

### STOSB, STOSW, and STOSD

### LODSB, LODSW, and LODSD

### Section Review

## Selected String Procedures

### Str_compare Procedure

### Str_length Procedure

### Str_copy Procedure

### Str_trim Procedure

### Str_ucase Procedure

### String Library Demo Program

### String Procedures in the Irvine64 Library

### Section Review

## Two-Dimensional Arrays

### Ordering of Rows and Columns

### Base-Index Operands

### Base-Index-Displacement Operands

### Base-Index Operands in 64-Bit Mode

### Section Review

## Searching and Sorting Integer Arrays

### Bubble Sort

### Binary Search

### Section Review

## Java Bytecodes: String Processing (Optional Topic)

## Chapter Summary

## Key Terms and Instructions

## Review Questions and Exercises

### Short Answer

### Algorithm Workbench

## Programming Exercises

# Structures and Macros

## Structures

### Defining Structures

### Declaring Structure Objects

### Referencing Structure Objects

### Example: Displaying the System Time

### Structures Containing Structures

### Example: Drunkard’s Walk

### Declaring and Using Unions

### Section Review

## Macros

### Overview

### Defining Macros

### Invoking Macros

### Additional Macro Features

### Using Our Macro Library (32-Bit Mode Only)

### Example Program: Wrappers

### Section Review

## Conditional-Assembly Directives

### Checking for Missing Arguments

### Default Argument Initializers

### Boolean Expressions

### IF, ELSE, and ENDIF Directives

### The IFIDN and IFIDNI Directives

### Example: Summing a Matrix Row

### Special Operators

### Macro Functions

### Section Review

## Defining Repeat Blocks

### WHILE Directive

### REPEAT Directive

### FOR Directive

### FORC Directive

### Example: Linked List

### Section Review

## Chapter Summary

## Key Terms

### Terms

### Operators and Directives

## Review Questions and Exercises

### Short Answer

### Algorithm Workbench

### Programming Exercises

# MS-Windows Programming

## Win32 Console Programming

### Background Information

### Win32 Console Functions

### Displaying a Message Box

### Console Input

### Console Output

### Reading and Writing Files

### File I/O in the Irvine32 Library

### Testing the File I/O Procedures

### Console Window Manipulation

### Controlling the Cursor

### Controlling the Text Color

### Time and Date Functions

### Using the 64-Bit Windows API

### Section Review

## Writing a Graphical Windows Application

### Necessary Structures

### The MessageBox Function

### The WinMain Procedure

### The WinProc Procedure

### The ErrorHandler Procedure

### Program Listing

### Section Review

## Dynamic Memory Allocation

### HeapTest Programs

### Section Review

## 32-Bit x86 Memory Management

### Linear Addresses

### Page Translation

### Section Review

## Chapter Summary

## Key Terms

## Review Questions and Exercises

### Short Answer

### Algorithm Workbench

## Programming Exercises

# Floating-Point Processing and Instruction Encoding

## Floating-Point Binary Representation

### IEEE Binary Floating-Point Representation

### The Exponent

### Normalized Binary Floating-Point Numbers

### Creating the IEEE Representation

### Converting Decimal Fractions to Binary Reals

### Section Review

## Floating-Point Unit

### FPU Register Stack

### Rounding

### Floating-Point Exceptions

### Floating-Point Instruction Set

### Arithmetic Instructions

### Comparing Floating-Point Values

### Reading and Writing Floating-Point Values

### Exception Synchronization

### Code Examples

### Mixed-Mode Arithmetic

### Masking and Unmasking Exceptions

### Section Review

## x86 Instruction Encoding

### Instruction Format

### Single-Byte Instructions

### Move Immediate to Register

### Register-Mode Instructions

### Processor Operand-Size Prefix

### Memory-Mode Instructions

### Section Review

## Chapter Summary

## Key Terms

## Review Questions and Exercises

### Short Answer

### Algorithm Workbench

### Programming Exercises

# High-Level Language Interface

##  Introduction

### General Conventions

### .MODEL Directive

### Examining Compiler-Generated Code

### Section Review

## Inline Assembly Code

### __asm Directive in Visual C++

### File Encryption Example

### Section Review

## Linking 32-Bit Assembly Language Code to C/C++

### IndexOf Example

### Calling C and C++ Functions

### Multiplication Table Example

### Section Review

## Chapter Summary

## Key Terms

## Review Questions

## Programming Exercises

# 16-Bit MS-DOS Programming 622

## MS-DOS and the IBM-PC

### Memory Organization

### Redirecting Input-Output

### Software Interrupts

### INT Instruction

### Coding for 16-Bit Programs

### Section Review

## MS-DOS Function Calls (INT 21h)

### Selected Output Functions

### Hello World Program Example

### Selected Input Functions

### Date/Time Functions

### Section Review

## Standard MS-DOS File I/O Services

### Create or Open File (716Ch)

### Close File Handle (3Eh)

### Move File Pointer (42h)

### Get File Creation Date and Time

### Selected Library Procedures

### Example: Read and Copy a Text File

### Reading the MS-DOS Command Tail

### Example: Creating a Binary File

### Section Review

## Chapter Summary

## Programming Exercises

# Disk Fundamentals

## Disk Storage Systems

### Tracks, Cylinders, and Sectors

### Disk Partitions (Volumes)

### Section Review

## File Systems

### FAT12

### FAT16

### FAT32

### NTFS

### Primary Disk Areas

### Section Review

## Disk Directory

### MS-DOS Directory Structure

### Long Filenames in MS-Windows

### File Allocation Table (FAT)

### Section Review

### Reading and Writing Disk Sectors

### Sector Display Program

### Section Review

## System-Level File Functions

### Get Disk Free Space (7303h)

### Create Subdirectory (39h)

### Remove Subdirectory (3Ah)

### Set Current Directory (3Bh)

### Get Current Directory (47h)

### Get and Set File Attributes (7143h)

### Section Review

## Chapter Summary

## Programming Exercises

## Key Terms

# BIOS-Level Programming

## Introduction

### BIOS Data Area

## Keyboard Input with INT 16h

### How the Keyboard Works

### INT 16h Functions

### Section Review

## Video Programming with INT 10h

### Basic Background

### Controlling the Color

### INT 10h Video Functions

### Library Procedure Examples

### Section Review

## Drawing Graphics Using INT 10h

### INT 10h Pixel-Related Functions

### DrawLine Program

### Cartesian Coordinates Program

### Converting Cartesian Coordinates to Screen​Coordinates

### Section Review

## Memory-Mapped Graphics

### Mode 13h: 320 * 200, 256 Colors

### Memory-Mapped Graphics Program

### Section Review

## Mouse Programming

### Mouse INT 33h Functions

### Mouse Tracking Program

### Section Review

## Chapter Summary

## Programming Exercises

# A MASM Reference

# B The x86 Instruction Set

# C BIOS and MS-DOS Interrupts

# D Answers to Review Questions (Chapters 14–16)

# Glossary

# ASCII Character Reference Charts

# Supplemental Materials