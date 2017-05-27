Documentation for Homework 4
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

Documentation    : +2 points (comments in code plus README)

(A) tablecheck (+20 points)
	1. good tablefile (+10 points, +1 points for each correct case)
	2. bad tablefile (+10 points, +1 points for each correct case)

(B) encrypt/decrypt (+48 points)
	1. standard DES testvector (+8 points, +1 for each correct case)
	2. encrypt (+10 points, +1 for each correct answer)
	3. encrypt from stdin (+10 points, +1 for each correct answer)
	4. decrypt (+10 points, +1 for each correct answer)
	5. decrypt from stdin (+10 points, +1 for each correct answer)
                
(C) encrypt, then decrypt using student's code (+10 points, +1 for each correct answer)
                
(D) encrypt3/decrypt3 (+20 points)
	1. encrypt3 (+10 points, +1 for each correct answer)
	2. decrypt3 (+10 points, +1 for each correct answer)

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
								: Next Homework I'd try to modular code into different files for much better readability from the start.

Comments on deviation from spec :   The code is as per the spec given in the grading guidelines.
