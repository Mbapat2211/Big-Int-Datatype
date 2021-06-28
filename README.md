# Big Int Datatype

Big Int is a custom datatype capable of storing integers uptill size 1024 bits. The following repository implements the Big Int datatype in C programming language.

## Background

The inbuild C datatypes allow only storing integers only upto size 16 bytes or 128 bits (long double). The Big Int datatype is capable of storing integers of size 128 bytes or 1024 bits. The range of this data type is from **(-2^1023) to (2^1023 - 1)**.

## Implementation

The Big Int datatype has been implemented using an array of characters of the size 310. 310 is the maximum number of digits for a number in the range of the Big Int Datatype. Each digit of the number is stored as a character in the large character array and therefore will consume only 1 byte of data.

## Operations

Since Big Int is not an inbuild datatype in the C programming language, therefore all the operations have to be customized on this datatype. The program consists of custom functions to enable the following basic operations on the Big Int datatype:

1. Addition (+)
2. Multiplication (*)
3. Subtraction (-)

The program allows the user to test each of these operations on 2 numbers of the Big Int datatype.
