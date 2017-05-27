Documentation for Warmup Assignment 1
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

(A) stream	: 10/10 points

(B) encrypt	: 24/24 points
                
(C) merge	: 24/24 points
                
(D) decrypt	: 24/24 points

(E) do the whole thing with student's code	: 15/15 points
	(1) small.pbm: +5 points
	(2) hello.pbm: +5 points
	(3) bowtie.pbm: +5 points

+---------------+
| Minus points: |
+---------------+

Missing README file 	: No

Improper citation   	: No

Cannot compile      	: No

Compiler warnings   	: None

"make clean"		: Works Properly

Segmentation faults	: None

Separate compilation	: Works according to the grading guidelines

Too slow 		: No

Bad commandline 	: Works As Mentioned in Specs

Improper citation 	: No

+------+
| BUGS |
+------+

Comments	: When tested against the test cases given in grading guidelines, no bugs could be seen both on nunki.usc.edu or the local system.

+-------+
| OTHER |
+-------+

Comments on design decisions    :   Modularized Code for Better Readability. Function usability wasn’t incorporated dude to the different cases to be handled for merge and encrypt.
				: GNU getopt was used to parse input arguments. I got knowledge of this library (getopt.h) from the class google group discussion titled “Parsing Arguments” posted by Nick Funk on Feb 3rd. The code used is learnt from the GNU getup page "http://www.gnu.org/software/libc/manual/html_node/Getopt-Long-Options.html#Getopt-Long-Options"

Comments on deviation from spec :   The code is as per the spec given in the grading guidelines.
