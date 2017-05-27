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

(A) keygen 			: 20/20 points

(B) invkey			: 10/10 points
                
(C) crypt/decrypt	: 20/20 points
                
(D) keygen, invkey, crypt, then decrypt using only student's data	: 10/10 points

(E) histo			: 20/20 points

(F) solve			: 20/20 points

(G) mystery 		: 01/10 extra credits

	(1) Mystery File 1

		1. ran the following command on the mystery file provided

		./hw3 solve -l=50 OG\ Files/mystery1.ct.txt

		here I observed through Kasiski Method that, same cipher text values reappeared on intervals of 469, 35, 1442, 231, 868, 42, ... and so on. Thus showing that similar cipher texts repeated at intervals which are all multiples of 7. Thus hinting that 7 could be one possible period which resulted in same plain text to be converted to same cipher text respectively.

		here I also observed the Auto-correlation values to figure out t*
			- as the method says, for values t that are multiples of t*, the count will be noticeably higher
			- now we can observe that to happen on multiples of 7
			- t = 07, count = 49
			- t = 14, count = 64
			- t = 21, count = 64
			- t = 28, count = 80
			- t = 35, count = 69
			- t = 42, count = 64
			- t = 49, count = 84

			- this showed spike in count values near multiples of 7
			- thus making it safe to assume that t (period) is 7

		2. I started to rearrange cipher text into 7 periods, placing one character into each of these 7 rows one at a time. This was then followed by plain english statistical analysis. After quite some tries of replacing most frequent characters and di-grams with plain text values I couldn't come up with anything that would solve the entire cipher text apart from a few words. 

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

Comments on design decisions    :   Modularized Code for Better Readability. 
								: GNU getopt was used to parse input arguments. I got knowledge of this library (getopt.h) from the class google group discussion titled “Parsing Arguments” posted by Nick Funk on Feb 3rd. The code used is learnt from the GNU getup page "http://www.gnu.org/software/libc/manual/html_node/Getopt-Long-Options.html#Getopt-Long-Options"
								: Next Homework I'd try to modular code into different files for much better readability from the start.

Comments on deviation from spec :   The code is as per the spec given in the grading guidelines.
