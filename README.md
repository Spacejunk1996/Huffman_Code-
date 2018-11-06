# Huffman_Code
Write a program that takes any input text and produces both a frequency table and the corresponding Huffman code.

Take approximately 360 words from any English document as your input text. Ignore all blanks, all punctuation marks, all special symbols. Create an input file with this input text.
Construct the frequency table according to the input text read from the file:
The frequency's must be listed, in order, from largest (at the top) to smallest (at the bottom)
Then, using the Huffman algorithm, construct the optimal prefix binary code for the table.
The Huffman codes will be sorted in the same manner as the one above i.e. frequency, highest to lowest.
Design your program to read the input from the input file "infile.dat". Your program must produce the output, in the file "outfile.dat",(Files must be named "infile.dat" and "outfile.dat" consisting of
the frequency table for the source text,
the Huffman code for each letter and digit in the source code, and
the length of the coded message in terms of number of bits, 
Final Output (Example Values Not Accurate) 

Symbol	frequency
    A,	15%
    m,	11%
    7,	6%
 

Symbol	Huffman Codes
     A,	       10101
     m,	        1101
     7,	         111
Total Bits: 16005
