# Floating-Point-Adder (FPA)

This project implements a floating point adder with a custom 1-bit sign, 9-bit exponent, and 22-bit fraction representation. It features several advanced components such as NaN/Denormalized Checker, Fraction/Exponent Checker, Main Input Validator, a 32-bit ALU (Arithmetic Logic Unit), Normalizer Circuit, and a Rounding Circuit. The design allows for reliable and efficient addition of floating point numbers while ensuring correctness and handling edge cases such as NaN (Not a Number), denormalized numbers, and rounding issues.

The adder operates on floating point numbers in the IEEE-754-like format, and the following components are included:

* Sign (1-bit): Indicates the sign of the floating point number.
* Exponent (9-bits): Represents the exponent in biased format.
* Fraction (22-bits): The fractional part of the floating point number.
* 
Additionally, the system checks the validity of the inputs, handles rounding, and normalizes the result according to standard floating point arithmetic conventions.

Features
* Floating Point Adder: Adds two floating point numbers represented as sign, exponent, and fraction components.
* NaN/Denormalized Checker: Detects Not-a-Number (NaN) and denormalized numbers during addition.
* Fraction/Exponent Checker: Validates the fraction and exponent components of the inputs.
* Main Input Validator: Verifies that the inputs conform to the expected floating-point format before processing.
* 32-bit ALU: Performs basic arithmetic and logical operations required for floating-point addition.
* Normalizer Circuit: Normalizes the result of the addition to ensure proper floating point representation.
* Rounding Circuit: Handles rounding of results to maintain precision.

This was an Assignment for the course Computer Architecture Sessional (CSE210) for the Session January 2024.

Team Members:

Anika Morshed (2105068)

Diganta Saha Tirtha (2105081)

Department of Computer Science and Engineering

Bangladesh University of Engineering and Technology.
