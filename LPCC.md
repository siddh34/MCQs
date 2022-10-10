# Very Important 

## Please see the drive

https://drive.google.com/drive/folders/11CcPlX-VAKegRTCOT1SPGGLyPHQuC8oO?usp=sharing

## Unit 1 Assembler 

> Q1. An interpreter is ................

      1. It is a program that appears to 
         execute a source program as if it 
         were machine language
      2. A program that automate the 
         translation of assembly language 
         into machine language
      3. Program that accepts a program 
         written in a high level language 
         and produces an object program
      4. A program that places programs 
         into memory and prepares them 
         for execution

**Answer :**  Option 1

*Explanation : Interpreter reads and excutes code line to line*

> Q2. A translator that read program in HL language and converts the code into low level language called?

    1. compiler
    2. translator
    3. assembler
    4. system software

**Answer :**  Option 1

*Explanation : A complier converts HL code to machine language*

> Q3. The symbol table implementation is based on the property of locality of reference?

    1. Linear tree
    2. Search tree 
    3. Hash table
    4. None

**Answer :**  Option 1

*Explanation : The aim of a self-organizing list is to improve efficiency of linear search by moving more frequently accessed items towards the head of the list. The property of frequently accessing same values, or related storage locations is termed as Locality of Reference.*

> Q4. A compiler for a high-level language that runs on one machine and produces code for a different machine is called ............................

      1. optimizing compiler
      2. one pass compiler
      3. cross compiler
      4. multipass compiler

**Answer :**  Option 3

*Explanation : A cross compiler is a compiler capable of creating executable code for a platform other than the one on which the compiler is running. In paravirtualization, one computer runs multiple operating systems and a cross compiler could generate an executable for each of them from one main source.* 

>Q5. An assembly program contains...

    1. Imperative statements and assembler directives
    2. Imperative and declarative statement
    3. Imperative and declarative statement as well as assembler directive
    4. Declarative statements and assembler directive

**Answer :** Option 3

*Explanation : There is something always missing in options 1,2 and 4*

>Q6 The assembler directives which are the hints using some predefined alphabetical strings are given to .....

    1. processor
    2. memory
    3. assembler
    4. processor & assembler

**Answer :**  Option 3

*Explanation : These directives help the assembler to correctly understand the assembly language programs to prepare the codes.*

> Q7. In two pass assembler the object code generation is done in ....... pass

    1. Second pass
    2. First pass
    3. Zeroth pass
    4. Third pass

**Answer :** Option 2

*Explanation : First pass generate object code*

> Q8. What is the result of complier?

      1. Assembly Code
      2. Machine Code
      3. Result
      4. None 

**Answer** : Option 1 

*Explanation : Result of complier is Assembly Code*


> Q9. Which of the following system program foregoes the production of object code to generate absolute machine code and load it into the physical main storage location from which it will be executed immediately upon completion of the assembly?

      1. Macro processor
      2. load and go assembler
      3. Two pass assembler
      4. complier

**Answer :**  Option 2

*Explanation : Two pass assembler also does the same work but doesn't provide ability to load quickly and run the code*

## Unit 2 Macroprocessors

>Q1. In which way(s) can a macro processor for assembly language be implemented ?

    1. independent one-pass processor
    2. independent two-pass processor
    3. processor incorporated into pass 
       of a standard two-pass assembler
    4. all of the above

**Answer :** Option 4

*Explanation : We can use all the above ways for making a macroprocessor*

> Q2. The advantage(s) of incorporating the macro processor into pass 1 is/ are:
<br>

      1. Many functions do not have to be 
         implemented twice
      2. Functions are combined and it is 
         not necessary to create 
         intermediate files as output from 
         the macro processor and input to 
         the assembler 
      3. more flexibility is available to 
         the programmer in which he/she may 
         use all the features of the 
         assembler in conjunction with 
         macros
      4. All of the above

**Answer :**  Option 4

*Explanation : The implementation of the macro-processor within pass 1 eliminates the over-head of intermediate files and we can improve this integration of macro-processor and assembler by combining similar functions. This gives us the above advantages*

>Q3. A self-relocating program is one which?

    1. cannot be made to execute in any 
       area of storage other than the one 
       designated for it at the time of its 
       coding or translation
    2. consists of a program and relevant 
       information for its relocation
    3. can itself perform the relocation of 
       its address-sensitive portions
    4. All of the above

   **Answer :** Option 3

*Explanation : The program performs its own relocation and does not require a linker is called as self-relocating program*

> Q4 fill in the blanks

<img src="./Images/lppccode1.jpg">

    1. READ X, MOVEM, MEND, #2
    2. ONE Y, MOVER, THREE, ='1' 
    3. lc = 100, MOVER, MEND, #2
    4. ONE X, MOVEM, THREE, #1'+

**Answer :**  Option 1

*Explanation : It is clear that at third position there should MEND,\ and one next element is #1 then two's next element will be #2*

> Q5 Select the correct options with respect to statements i) 2 modules cannot have the same load address ii) Overlays are used to reduce memory usage

      1. Only (i) are correct
      2. Both (i) and (ii) are correct
      3. Both (i) and (ii) are incorrect
      4. Only (ii) is correct

**Answer :** Option 2

*Explanation : Programmers have to see that no same address is allocated to 2 modules. The concept of overlays is that whenever a process is running it will not use the complete program at the same time, it will use only some part of it. Then overlays concept says that whatever part you required, you load it and once the part is done, then you just unload it, means just pull it back and get the new part you required and run it.*

## Unit 3

>Q1. What is the action of parsing the source program into proper syntactic classes known as

      1. Interpretation analysis
      2. General syntax analysis
      3. Syntax analysis
      4. Lexical analysis

**ANS: 3. Syntax analysis** 

*Explaination: The action of parsing the source program into the proper syntactic classes is known as syntax analysis. A syntax analyzer or parser takes the input from a lexical analyzer in the form of token streams. The parser analyzes the source code (token stream) against the production rules to detect any errors in the code. The output of this phase is a parse tree.
In syntactic analysis, parse trees are used to show the structure of the sentence, but they often contain redundant information due to implicit definitions.Parsing, syntax analysis or syntactic analysis is the process of analyzing a string of symbols, either in natural language, computer languages or data structures, conforming to the rules of a formal grammar.*

>Q2. Which of the following is definition of compiler?

       1.  Acceptance of a program written in a high-level language and produces an object pr
       ogram
       2. Program is put into memory and execut
       es it
       3. Translation of assembly language into machine
        language
       4. None of the mentioned

**ANS: 1. Acceptance of a program written in a high-level language and produces an object program**

*Explaination: A compiler is a software (or combination of programs) that converts source code written in one programming language (the source language) into code written in another programming language (the target language) (the target language, often having a binary form known as object code).*

>Q3. Which of the following does an address code involve?

       1. No unary operators
       2. Exactly 3 address
       3. At most Three address
       4. None of the mentioned

**ANS: 4. None of the mentioned**

*Explaination: In computer science, three-address is an intermediate code used by optimizing compilers to aid in the implementation of code-improving transformations.*

>Q4. In which of the following phase of the compiler is Lexical Analyser?

      1. Second
      2. Third
      3. First
      4. All of the mentioned

**ANS: 3. First**

*Explaination: Lexical Analyzer is the First Phase of the Compiler.*

>Q5. What is the linker?

       1. It is always used before program execution
       2. It is required to create load module
       3. It is same as the loader
       4. None of the above

**ANS: 2. It is required to create load module**

*Expaination:  Linker is a program in the compiler which is required to create a load module.*

6. In compiler Lexical analyzer is used for?

       1. removing comments
       2. removing whitespaces
       3. breaking the synatxes into set of tokens
       4. All of the mentioned

**ANS: 4. All of the mentioned**

*Explaination: Lexical analyzer is used in the compiler for removing the Whitespace and comments. It is also used in breaking the syntaxes into the set of tokens.*

7. Which is considered as the sequence of characters in a token?

       1. Mexeme
       2. Lexeme 
       3. Texeme
       4. Pattern

**ANS: 2.Lexeme**

*Explaination:  Lexemes are the string of alphanumeric characters in a single token. In the source program, lexemes are characters which are identified by the pattern for a token.*

>Q8. Which of the following component is important for semantic analysis?

       1. Yay
       2. Lex
       3. Type checking
       4. Symbol table

**ANS: 3. Type checking**

*Explaination: In the semantic analysis, type checking is an important component because it verifies the program's operations from the semantic conventions.*

>Q9. Which phase of the compiler is also known as Scanner?

      1. Syntax Analysis
      2. Lexical Analysis
      3. Semantic Analysis
      4. Code generation

**ANS: 2. Lexical Analysis**

*Explaination: The first part of the compiler (lexical analysis) is also known as a scanner. It scans the characters from the source program and implements them to produce tokens.*

>Q10. Which phase of the compiler is also known as Parser?

      1. Code Optimization
      2. Semantic Analysis
      3. Synatx Analysis
      4. Lexical Analysis

**ANS: 3. System Analysis**

*Explaination: The phase of the compiler next to the lexical analysis phase is also known as Parser.
Syntax analysis or parser accepts the tokens produced by the lexical analysis and gives the parse tree in the output.*

>Q11. The full form of YACC is:

      1. Yet Another Computer Computer
      2. Yet Another Computer Compiler
      3. Yet Another Compiler Computer
      4. Yet Another Compiler Compiler

**ANS: 4. Yet Another Compiler Compiler**

*Explaination: The full form of YACC is Yet Another Compiler Compiler, which produces the LALR (1) grammar parser.*

>Q12. What is the output of lexical analyzer?

      1. A set of RE
      2. Syntax Tree
      3. Set of Tokens
      4. String Character

**ANS: 3. Set of tokens**

*Explaination:A lexical analyzer coverts character sequences to set of tokens.*

>Q13. If the lexical analyser finds a lexeme with the same name as that of a reserved word,it

       1. overwrites the word
       2. overwrites the functionality
       3. generates an error 
       4. something else

**ANS: 3. generates an error**

*Explaination: Reserved words are known as keywords and they are specific and reserved with its functionality to a language. Thus, getting an input with the same name by the analyzer will generate an error.*

>Q14. A lexical analyzer reads the source code line by line.

       1. True
       2. False

**ANS: 2. False**

*Explaination: A lexical analyzer reads the source code letter by letter and when it encounters a space or an operator or any special character, it decides that the word is completed.*

>Q15. A program that performs lexical analysis is termed as:

       1. scanner
       2. lexer
       3. tokenizer
       4. all of the mentioned

**ANS: 4. all of the mentioned**

*Explaination: A program which performs lexical analysis is called lexer, scanner or lexer. Nowadays, lexer is combined with a parser which allows syntactic analysis.*

>Q16. Which of the following can detect an error if a programmer by mistake writes multiplication instead of division

       1. Intrepreter
       2. Compiler or Intrepreter test
       3. Compiler
       4. None of the mentioned

**ANS: 4. None of the mentioned**

*Explaination: No Logical errors can’t be detected.*