# ENCOUNTER
## Getting started
### Imperative programming
- a link between us, the human programmers, and a machine, the computer, to tell it what to do: to give it “orders.”
### Compiling and running
- program text expresses what we want our computer to do
  - we have written and stored somewhere on our hard disk
  - as such cannot be understood by your computer
- special program, called a compiler, that translates the C text into something that your machine can understand
## The principle structure of a program
### Grammar
- Special words
- Punctuations
- Comments
- Literals (fixed values that are part of the program)
- Identifiers (main, printf, size_t, EXIT_SUCCESS)
  - Functions
  - Constants
  - Data objects
  - Types
- Functions
- Operators
### Declarations
- a particular identifier in a program, we have to give the compiler a declaration
- "declarations only,” look like this:
  ```c
  int main(void);
  double A[5];
  size_t i;
  ```
- size_t, and EXIT_SUCCESS, provided by stdlib.h, printf provided by stdio.h
  - they are predeclared identifiers
-  bound to the scope in which they appear
  -  block scope ({  })
  -  global (file scope)
### Definitions
- Declarations specify identifiers, whereas definitions specify objects
- An object is defined at the same time it is initialized
### Statements
- Iteration
  - for statement (for(initialization, before, after){loop body})
- Function calls
  - suspend the execution of the current function (at the beginning, this is usually main) and then hand over control to the named function
- Function returns
# ACQUAINTANCE
- C is a permissive language
## Everything is about control
### Conditional execution
### Iterations
### Multiple selection
## Expressing computations
### Arithmetic
- +, - and *
- Division and remainder
### Operators that modify objects
### Boolean context
- Comparison
- Logic
### The ternary or conditional operator
### Evaluation order
## Basics value and data
### The abstract state machine
- Values
- Types
- Binary representation and the abstract state machine
- Optimization
### Basic types
### Specifying values
- Complex constants
### Implicit conversions
### Initializers
### Named constants
- Read-only objects
- Enumerations
- Macros
- Compound literals
### Binary representations
- Unsigned integers
- Bit sets and bitwise operators
- Shift operators
- Boolean values
- Signed integers
- Fixed-width integer types
- Floating-point data
## Derived data types
### Arrays
### Pointers as opaque types
### Structures
### New names for types : type aliases
## Functions
### Simple functions
### main is special
### Recursion
## C library functions
### General properties of the C libraries and its funtions
- Headers
- Interfaces
- Error checking
- Bounds-checking interfaces
- Platform preconditions
### Mathematics
### Input, Output and file manipulation
- Unformatted text output
- Files and streams
- Text IO
- Formatted output
- Unformatted text input
### String processing and conversion
### Time
### Runtime environment settings
### Program termination and assertions
# Cognition
## Style
### Formatting
### Naming
## Organization and documentation
### Interface documentation
### Implementation
## Pointers
### Pointer operations
- Address-of and Object-of operators
- Pointer addition
- Pointer subtraction and difference
-  Pointer validity
-  Null pointers
### Pointers and structures
### Pointers and arrays
- Array and pointer access are the same
- Array and pointer parameter are the same
### Function pointers
## The C memory models
### A uniform memory model
### Unions
### Memory and state
### Pointers to unspecific objects
### Explicit conversions
### Effective types
### Alignment
## Storage
### malloc and friends
- A complete examples with varying array size
- Ensuring consistency with dynamic allocations
### Storage duration, lifetime, and visibility
- Static storage duration
- Automatic storage duration
### Digression: using object "before" their definition
### Initialization
### Digression: a machine model
## More involved processing and IO
### Text processing
### Formatted input
### Extended character sets
### Binary streams
### Error checking and cleanup
# Experience
## Performance
### Inline functions
### Using restrict qualifiers
### Measurement and inspection
## Function-like macros
### How  function-like macros work
### Argument checking
### Accessing the calling context
### Default arguments
### Variable-length argument lists
- Variadic macros
- A detour: variadic functions
### Type-generic programming
## Variation in control flow
### A complicated example
### Sequencing
### Short jumps
### Functions
### Long jumps
### Signal handlers
## Threads
### Simple inter-thread control
### Race-free initialization and destruction
### Thread-local data
### Critical data and critical section
### Communicating through condition variables
### More sophisticated thread management
## Atomic access and memory consistency
### The "happened before" relation
### C library call that provide synchronization
### Sequential consistency
### Other consistency models