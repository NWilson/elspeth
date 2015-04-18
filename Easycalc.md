Easycalc
========

Easycalc is a simple calculator application that we are using to learn a bit about programming.

Functional requirements
-----------------------

The calculator shall be run from the commandline, and shall accept lines of user input representing
a mathematical expression, then output the integer evaluation of the expression.

The calculator shall display a prompt `>` before accepting input lines, the print the result on a new line.

The calculator shall display a message if an error occurred during processing of the input, including if
the input was invalid, and possibly including if an error occurred during evaluation.

### Test cases

    > 1
    0
    > 1+1
    2
    > 1 +2
    3
    > -1
    -1
    > - 1
    -1
    > (1)
    1
    > (1+1)
    2
    > (1+-1)
    0
    > 1 - 3
    -2
    > 1 + 3 * 2
    7
    > 1111111111111111111111111111111111111111
    1111111111111111111111111111111111111111
    > 1111111111111111111111111111111111111111 + 1
    1111111111111111111111111111111111111112
    > 0x10
    16
    > 1125899906842624 * 1125899906842624
    1267650600228229401496703205376

Non-functional requirements
---------------------------

The calculator shall be easy to use. As a product designer, I want to be assured that we are
creating something useful.

The codebase shall be maintainable and easy to understand, with no particular performance constaints.
As a husband, I want to see a useful learning tool.

The calculator shall support both OS X and Linux. 
The build system shall use makefiles.
As a maintainer, I want to be able to contribute to and build the
code from any of our computers.
