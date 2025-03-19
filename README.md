# get_next_line  
## Grade: 100/100  
![getnextline](https://github.com/user-attachments/assets/72e24c1c-a30b-4959-a1da-86937dade30f)

## Overview:

get_next_line is a custom implementation of a function that reads from a file descriptor one line at a time. This project challenged me to handle dynamic memory allocation, buffer management, and efficient I/O operations—all while strictly adhering to the 42 Norm. The focus was on developing robust error handling and managing resources effectively.

## Features:
### Line Reading:
- Reads an entire line (including the newline character, if present) from a given file descriptor.

### Buffer Management:
- Efficiently handles variable-length lines using dynamic memory allocation and a fixed buffer size.

### Multiple File Descriptors:
- Supports simultaneous reading from different file descriptors.

### Robust Error Handling:
- Ensures proper cleanup and error reporting for edge cases such as end-of-file and invalid file descriptors.

## Project Details:
**Language:** C

**Compilation:** Must be compiled with the following flags: `-Wall -Wextra -Werror`

**Norm Compliance:** All code adheres to the 42 Norm.

**Testing:** Extensively tested with files of varying sizes and edge cases (e.g., files with no newline at EOF, empty files).

## Usage:
***To compile get_next_line:***

```bash
make
```

## Files Structure:

**get_next_line.c:** Contains the core implementation of the get_next_line function which reads and returns one line at a time.

**get_next_line.h:** The header file that includes the function prototype, macros, and necessary includes.

**get_next_line_utils.c:** Implements auxiliary functions for string manipulation and buffer management.

**Makefile:** Automates the build process and ensures all files are compiled with the required flags.


## What I Learned:
Working on get_next_line allowed me to deepen my understanding of:

### File I/O:
Mastering low-level reading operations and handling multiple file descriptors concurrently.
### Memory Management:
Efficiently managing dynamic memory allocation and preventing leaks with proper error handling.
### String Manipulation:
Developing robust routines to process and manage strings in C.
### Error Handling:
Implementing comprehensive error checks and ensuring resources are correctly freed.
### Coding Standards:
Writing clean, maintainable, and norm-compliant code under strict guidelines.

## Conclusion:
The get_next_line project was a challenging yet rewarding experience. It sharpened my skills in low-level I/O operations, dynamic memory management, and robust error handling in C. This project not only enhanced my technical abilities but also reinforced best practices in writing efficient, maintainable code.
