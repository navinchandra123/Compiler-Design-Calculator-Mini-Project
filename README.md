# MINI PROJECT OF COMPILER DESIGN "CALCULATOR" USING FLEX , YACC AND C LANGUAGE  

We have created a calculator (Mini project of compiler design).
In this application if we write a valid math expression it gives us the final answer.Usually in this 
application we implement the type of operation given below

1. Addition 
2. Subtraction
3. Multiplication 
4. Division
5. Modulo
6. Power 

# How to compile it
### Prerequisities
- lex (Flex)
- yacc (Bison)

If you don't have them, please install flex and bison by using apt-get(for Ubuntu/Debian) or from GnuWin Packages(For windows users)

### Compile
>lex calc.l

>yacc calc.y

>gcc lex.yy.c y.tab.c -o calc



