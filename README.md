# Ex-4-LETTER-FOLLOWED-BY-ANY-NUMBER-OF-LETTERS-OR-DIGITS-USING-YACC
RECOGNITION OF A VALID VARIABLE WHICH STARTS WITH A LETTER FOLLOWED BY ANY NUMBER OF LETTERS OR DIGITS USING YACC
# Date: 9.5.25
# Aim:
To write a YACC program to recognize a valid variable which starts with a letter followed by any number of letters or digits.
# ALGORITHM
1.	Start the program.
2.	Write a program in the vi editor and save it with .l extension.
3.	In the lex program, write the translation rules for the keywords int, float and double and for the identifier.
4.	Write a program in the vi editor and save it with .y extension.
5.	Compile the lex program with lex compiler to produce output file as lex.yy.c. eg $ lex filename.l
6.	Compile the yacc program with YACC compiler to produce output file as y.tab.c. eg $ yacc –d arith_id.y
7.	Compile these with the C compiler as gcc lex.yy.c y.tab.c
8.	Enter a statement as input and the valid variables are identified as output.
# PROGRAM

C: \Dev-Cpp\TDM-GCC-64\bin>flex expr3.l
C: \Dev-Cpp\TDM-GCC-64\bin>bison -dy expr3. y
C: \Dev-Cpp\TDM-GCC-64\bin>gcc y. tab.c lex. yy.c -w
C: \Dev-Cpp\TDM-GCC-64\bin>a. exe
# Output
![Screenshot (246)](https://github.com/user-attachments/assets/a5eb44f4-5b29-40f4-ba7f-2f3d0f6f92d2)



# Result
A YACC program to recognize a valid variable which starts with a letter followed by any number of letters or digits is executed successfully and the output is verified.
