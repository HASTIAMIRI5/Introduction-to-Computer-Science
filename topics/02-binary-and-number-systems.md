# 2. Binary and Number Systems

## Core Question

How does a computer represent numbers and data using binary?

## Detailed Explanation

Humans usually use the decimal system, which is base 10. The decimal system uses digits 0 through 9.

A computer uses the binary system, which is base 2. It uses only two digits:

- 0
- 1

These digits are called bits.

### Why binary?

Computer hardware is built from electronic circuits that are either:

- off (0)
- on (1)

This makes binary natural and efficient for computing.

### Decimal system

In base 10:

- 10 is one group of ten plus zero units
- 245 means 2 hundreds + 4 tens + 5 ones

This is represented as:

245 = 2 x 10^2 + 4 x 10^1 + 5 x 10^0

### Binary system

In base 2:

1011 = 1 x 2^3 + 0 x 2^2 + 1 x 2^1 + 1 x 2^0

= 8 + 0 + 2 + 1 = 11

So binary 1011 equals decimal 11.

### Common number systems

1. Binary (base 2)
2. Decimal (base 10)
3. Hexadecimal (base 16)

Hexadecimal uses digits 0-9 and letters A-F.

Example:

- 10 in decimal = 1010 in binary
- 10 in decimal = A in hexadecimal

### Why hexadecimal is useful

Binary patterns are long. Hexadecimal gives a shorter and easier way to write them.

Example:

10110110 in binary
= B6 in hexadecimal

### Bits and bytes

- 1 bit = a single binary value (0 or 1)
- 8 bits = 1 byte

Examples:

- 1 byte can represent numbers from 0 to 255
- A character like 'A' is stored as a byte value in ASCII or Unicode

### ASCII and Unicode

Computers must represent text as numbers.

- ASCII uses 7 or 8 bits per character
- Unicode can represent many languages and symbols using more advanced encoding

Example:

- 'A' = 65 in ASCII
- 'B' = 66 in ASCII

### Data representation

Binary is not used only for numbers. It is used for:

- text
- images
- sound
- video
- instructions in programs

Everything in a computer is ultimately reduced to binary.

### Example: counting in binary

Decimal sequence:

0, 1, 2, 3, 4, 5, 6, 7

Binary sequence:

0, 1, 10, 11, 100, 101, 110, 111

This shows how binary grows by powers of two.

### In summary

Binary is the fundamental language of computers. By understanding how numbers are represented in base 2, we begin to understand how all digital information is stored and processed.

## Key Takeaways

- Computers use binary because electrical states are binary.
- Decimal is base 10; binary is base 2.
- Bits are the smallest units of information.
- Bytes group bits for practical data storage.

## Review Questions

1. What is the difference between decimal and binary?
2. How is binary 1011 interpreted?
3. Why is hexadecimal often used in computing?
4. What is a byte?
