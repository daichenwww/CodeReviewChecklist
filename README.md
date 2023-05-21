## Introduction
This is a homework from NTHU CS Software Engineering.
In this homework, we try to use Chat-GPT for code review.
## Credit
The tool: https://github.com/anc95/ChatGPT-CodeReview


## Code Review Checklist

### 0. Error:
   - Syntax error
   - Name error
   - Type error
   - Others

### 1. Logic Problems:
   - Forgotten cases or steps
   - Duplicate logic
   - Neglecting extreme conditions
   - Unnecessary functions
   - Misinterpretation
   - Missing condition tests
   - Checking the wrong variable
   - Incorrect iteration in loops

### 2. Computational Problems:
   - Insufficient or incorrect equations
   - Missing computations
   - Incorrect operands or operators in equations
   - Incorrect usage of parentheses
   - Precision loss
   - Rounding or truncation faults
   - Mixed modes
   - Sign convention faults

### 3. Interface/Timing Problems:
   - Incorrect handling of interrupts
   - Incorrect I/O timing
   - Timing faults causing data loss
   - Subroutine/module mismatches
   - Calling the wrong subroutine
   - Incorrectly located subroutine calls
   - Calling nonexistent subroutines
   - Inconsistent subroutine arguments

### 4. Data-Handling Problems:
   - Incorrect initialization of data
   - Incorrect access or storage of data
   - Incorrectly setting flags or indexes
   - Incorrect packing/unpacking of data
   - Referencing the wrong data variable
   - Referencing data out of bounds
   - Incorrect scaling or units of data
   - Incorrect dimensioning of data
   - Incorrect variable types
   - Incorrect usage of subscripted variables
   - Incorrect scope of data

### 5. Data Problems:
   - Incorrect or missing sensor data
   - Incorrect or missing operator data
   - Incorrect or missing embedded data in tables
   - Incorrect or missing external data
   - Incorrect or missing output data
   - Incorrect or missing input data

### 6. Documentation Problems:
   - Ambiguous statements
   - Incomplete items
   - Incorrect items
   - Missing items
   - Conflicting items
   - Redundant items
   - Confusing items
   - Illogical items
   - Non-verifiable items
   - Unachievable items

### 7. Document Quality Problems:
   - Not meeting applicable standards
   - Lack of traceability
   - Not being up-to-date
   - Inconsistencies
   - Incompleteness
   - Lack of identification

### 8. Enhancement:
   - Changes in program requirements
   - Addition of new capabilities
   - Removal of unnecessary capabilities
   - Updating current capabilities
   - Improving comments
   - Enhancing code efficiency
   - Implementing editorial changes
   - Improving usability

### 9. Software Fix of Hardware Problems.

### 10. Other Enhancements.
