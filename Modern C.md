# L0 ENCOUNTER
## Getting started
### Imperative programming
### Compiling and running
## The principle structure of a program
### Grammar
### Declarations
### Definitions
### Statements
- Iteration
- Function calls
- Function returns
# L1 ACQUAINTANCE
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
# L2 Cognition
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
# L3 Experience
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