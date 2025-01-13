# Tools Needed
* JFLAP7.1
* Any JavaIDE

## Input:
List of words

## Output:
XML for JFLAP of a DFA

# Project Description
## Project: DFA Construction

COT 3210

Due: September 15

1. Write a program in C, Java or Python which create the JFLAP DFA for a finite language. All code
should be contained within one file for simplicity. The program should read from stdin (like scanf) and
output to stdout (like printf). Note: You should not be reading/writing any files directly; stdin and
stdout is all you need.

The alphabet used is
Σ = {c | c is a lowercase letter} = {a, b, c, d, e, f, g, h, i, j, k, l, m, n, o, p, q, r, s, t, u, v, w, x, y, z}

The language will be given as a series of lines to stdin. Each line will represent one string in the
language. Note: Don’t forget to handle the empty string. The end of stdin is sent by EOF.
There is an example input and output posted to Canvas. Your output does not need to match mine
exactly, it only needs to be equivalent as a DFA (That is, it recognizes the same language).
The output will be the JFLAP XML format. The format is very straightforward, and you should be
able to figure out the format by creating examples in JFLAP and opening up the files in a text editor.

I’ve also posted the relevant JFLAP documentation on Canvas.
This part is worth 25 points and there are 5 points available for Extra Credit. If the program does not
compile, or does not print an output which is recognized by JFLAP, no points will be given.

Partial Credit will be given in cases of logic errors.
* a) (10 Points) The program generates a correct DFA for the posted example.
* b) (10 Points) The program generates a correct DFA for a random example language.
* c) (5 Points) The program only generates errors when the input is incorrect (such as reading symbols
not in the alphabet).
* d) (5 Points Extra Credit) The output has states which are positioned in a reasonable manner (no
overlapping transitions, see example output file for an example)

Note: The extra credit is entirely optional, you can save yourself some effort and put all states at
x = 0, y = 0 for simplicity.
1
