# Introduction
==Since the invention== of the microprocessor, software developers have used assembly language to create innovative solutions for a wide variety of algorithmic challenges.

During the ==early days== of the microprocessor era, it was common practice to code large portions of a program or entire applications using assembly language.

Given the ==twenty-first-century== prevalence of high-level languages such as C++, C#, Java, and Python, it may be surprising to learn that many software developers still employ assembly language to code performance-critical sections of their programs.

And while compilers have improved remarkably ==over the years== in terms of generating machine code that is both spatially and temporally efficient, situations still exist where it makes sense for a software developer to exploit (or at least consider) the benefits of assembly language programming.

The single-instruction multiple-data (SIMD) architectures of modern microprocessors provide another explanation for the ==continued interest== in assembly language programming. A SIMD-capable processor contains computational resources that facilitate simultaneous calculations using multiple data values, which can ==significantly improve the performance== of applications that must deliver real-time responsiveness. SIMD architectures are also well suited for ==computationally intensive application== domains such as machine learning, image processing, audio and video encoding, computer-aided design, computer graphics, and data mining.

Unfortunately, many high-level languages and development tools are ==still unable== to fully exploit the SIMD capabilities of a modern processor. Assembly language, on the other hand, ==enables== the software developer to ==take full advantage== of a processor’s SIMD resources.
# Armv8-32 Architecture
==Armv8-32 Architecture== Chapter 1 introduces Armv8-A and the AArch32 execution state. It includes a discussion of fundamental data types, internal architecture, register sets, instruction operands, and memory addressing modes. Chapters 2, 3, and 4 explain the fundamentals of Armv8-32 assembly language programming using the A32 instruction set and common programming constructs including arrays and structures. The source code examples presented in these (and subsequent) chapters are packaged as working programs, which means that you can run, modify, or otherwise experiment with the code to enhance your learning experience.
Introduce Armv8 computing ==architecture== and the AArch32 ==execution== state as viewed from the perspective of an application program.
## Armv8 Overview
Provides a frame of reference for subsequent content

==Armv8-32 Floating-Point Programming== Chapter 5 examines the floating-point resources of the AArch32 execution state. It also covers important floating-point programming concepts. Chapter 6 explains how to perform scalar floating-point arithmetic using single-precision and double-precision values.

==Armv8-32 SIMD Programming== Chapter 7 describes Armv8-32 SIMD resources including register sets, data types, and the instruction set. It also includes a short primer on SIMD programming techniques. Chapters 8 and 9 cover Armv8-32 SIMD programming using packed integer and packed floating-point operands.

==Armv8-64 Architecture== Chapter 10 introduces the AArch64 execution state. This chapter expounds relevant data types, architectural features, general-purpose and SIMD register sets, and memory addressing modes. Chapters 11 and 12 describe the fundamentals of Armv8-64 assembly language programming using the A64 instruction set.

==Armv8-64 Floating-Point== Programming Chapter 13 demonstrates how to perform scalar floating-point arithmetic using the A64 instruction set.

==Armv8-64 SIMD Programming== Chapters 14 and 15 delve into the details of the Armv8-64 SIMD architecture. These chapters contain a variety of programming examples that illustrate how to use the A64 instruction set to carry out calculations using packed integer and packed floating-point operands.

==Armv8-64 Advanced Programming== Chapter 16 includes source code examples that illustrate how to perform sophisticated arithmetic calculations using the A64 SIMD instruction set. Chapter 17 outlines specific coding strategies and techniques that you can use to boost the performance of your Armv8 assembly language code.