In this assignment you will have to implement the algorithm described in the book as 4E: CYCLOPEPTIDE SEQUENCING.  You will submit your code through Gradescope here: https://www.gradescope.com/courses/358896/assignments/1822301 (Links to an external site.) .

Your code will expect a file called "input" that contains a list of masses corresponding to the perfect experimental spectrum of a peptide.  The masses will be provided all on one line as a string of integers separated by spaces:

0 113 114 128 129 227 242 242 257 355 356 370 371 484
Your code must create a file called "output" that contains all the peptides that are consistent with this experimental spectrum. Each peptide will be represented by an ordered string of amino-acid masses separated by a dash:

129-113-114-128 
The multiple peptides should be output on one single line, separated by spaces:

113-114-128-129 113-129-128-114 114-113-129-128 
The individual masses correspond to the mass values presented in the book for each of the amino-acids. For reference, you can assume that all the masses available as "building blocks" for your peptides are:

57 71 87 97 99 101 103 113 114 115 128 129 131 137 147 156 163 186
For more details and test data sets you can find this problem in Rosalind as problem BA4E: http://rosalind.info/problems/ba4e/
