# Buddy System Memory Allocator

## Project Overview

This project implements a memory allocator using the **Buddy System**, 
a dynamic memory allocation technique that splits memory into halves to 
fit the requested size efficiently. The allocator mimics the behavior of 
the `malloc()` function in the C standard library, but it uses custom 
memory management based on the buddy allocation algorithm.

## How to run
To compile and run the project, you will need a C compiler such as `gcc`.

## How to Compile and Run

## 1. Compilation

To compile the Buddy System memory allocator and the unit tests, use the following command:

```bash
gcc '-o allocator_test test_balloc.c balloc.c freelist.c utils.c -lm'

### Example Output 
Running test_bcreate_and_bdelete...
test_bcreate_and_bdelete passed.
Running test_balloc_and_bfree...
test_balloc_and_bfree passed.
Running test_bsize...
test_bsize passed.
Running test_bprint...
Initial state of allocator:
...
test_bprint passed.
Running test_balloc_large_request...
test_balloc_large_request passed.
Running test_balloc_small_request...
test_balloc_small_request passed.
Running test_balloc_exhaust_memory...
test_balloc_exhaust_memory passed.
All tests (including edge cases) passed successfully.




