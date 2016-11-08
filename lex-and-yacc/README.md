# Lex and Yacc
Lex and yacc enables one to write programs that transform structured input.
A program is usually divided into units knowns as **tokens** through a process
known as **lexical anaysis**. Lex takes in a set of descriptions of tokens and 
produces a C routine known as a **lexical analyser** / **lexer** or **scanner**.
**Lex specification** is the set of tokens you give to a lex.  
The token descriptions are known as **regular expressions**. The relationship among the tokens
is established by a process known as **parsing**. The list of rules that define the relationships 
that the program understands is known as **grammar**. Yacc takes a concise description of a 
grammar and produces a C routine that can parse that grammar, a *parser*.
