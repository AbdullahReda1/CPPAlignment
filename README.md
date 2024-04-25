# Alignment C++

## Introduction

This repository contains a C++ code example demonstrating the usage of the alignas and alignof keywords. The alignas keyword specifies the alignment requirement of a variable or a user-defined type, while the alignof keyword queries the alignment requirements of a type.

## Usage

- Compile the code using a C++ compiler.

- Run the compiled executable to observe the output.

- The output displays the alignment of `charBuffer`, `intBuffer`, and `AlignedStructure`.

## Description

1. **cppAlignment.cpp**: This file contains the `main` code demonstrating the usage of the `alignas` and `alignof` keywords.
2. The `main` function defines an array of characters with alignment of 2, an unsigned integer with alignment of 1, and a structure with custom alignment of 16.
3. Each alignment specification is followed by a print statement to display the alignment of the corresponding variable using both `alignas` and `alignof`.

## Example

```cpp
Alignment of char Buffer:		2
Alignment of int Buffer:		1
Value of int Buffer:			4294967295
Alignment of Aligned Structure: 16
```