Documentation for Homework 6
=====================================
    by NAMAN AVASTHI

+-------+
| BUILD |
+-------+

Comments: Works with all the commands given in the grading guidelines.
          
+-----------------+
| SKIP (Optional) |
+-----------------+

All the test cases given in the grading guidelines are working.
No test cases has to be skipped.

+---------+
| GRADING |
+---------+

Documentation    : +3 points (comments in code plus README)

(A) primes (+11 points, +1 points for each correct case)

(B) trialdiv (+20 points, +2 for each correct answer)
                
(C) millerrabin (+22 points, +2 for each correct answer)
                
(D) rndsearch (+22 points, +2 for each correct answer)
	
(E) maurer (+22 points, +2 for each correct answer)

+---------------+
| Minus points: |
+---------------+

Missing README file 	: No

Improper citation   	: No

Cannot compile      	: No

Compiler warnings   	: None

"make clean"			: Works Properly

Segmentation faults		: None

Separate compilation	: Works according to the grading guidelines

Malformed input			: Prints reasonable error message and quits

Too slow 				: No

Bad commandline 		: Works As Mentioned in Specs

Improper citation 		: No

+------+
| BUGS |
+------+

Comments	: When tested against the test cases given in grading guidelines, no bugs could be seen both on nunki.usc.edu or the local system.

+-------+
| OTHER |
+-------+

Comments on design decisions    : Modularized Code for Better Readability. 
								: GNU getopt was used to parse input arguments. I got knowledge of this library (getopt.h) from the class google group discussion titled “Parsing Arguments” posted by Nick Funk on Feb 3rd. The code used is learnt from the GNU getup page "http://www.gnu.org/software/libc/manual/html_node/Getopt-Long-Options.html#Getopt-Long-Options"
								: This HW does reuse code from the previous HW (HW4) a lot. The template for hw5.c many of the other functions

								: Links referred are as follows -
									https://www.cs.umd.edu/class/sum2003/cmsc311/Notes/Data/endian.html

									http://etutorials.org/Programming/secure+programming/Chapter+7.+Public+Key+Cryptography/7.4+Manipulating+Big+Numbers/

									https://www.safaribooksonline.com/library/view/network-security-with/059600270X/ch04s05.html

									https://linux.die.net/man/3/bn_rshift1

									https://linux.die.net/man/3/bn_is_zero

									https://www.openssl.org

Comments on deviation from spec :   The code is as per the spec given in the grading guidelines.
