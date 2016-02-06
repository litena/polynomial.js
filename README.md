# polynomial.js
JavaScript file for working with polynomials over finite fields

License is omitted for the time being, until someone finds the files useful.

The use of the term "infinite fields" for {0, 1, 2, ...} is just a matter of programming convenience. It is mathematically *wrong* because there does not exist an additive inverse or a multiplicative inverse for some elements.

**polynomial.js**

Copyright 2016 @litena

# Documentation
Polynomials are created using function declaration, not via `new`. All functions are called via chaining.

`polynomial(array, indeterminate, characteristic)`: Create a polynomial object. `array` hold the coefficients of the polynomial, with the value at index *n* being the coefficient of the term with exponent *n*. `indeterminate` takes a string describing the indeterminate of the polynomial. `characteristic` denotes the characteristic of the field.


