This is the practical project we did in college, regarding Formal Languages, Automata and Compilers subject. 
Our task was to design an original programming language and provide a syntactic analyzer for it, using YACC. 
Besides the syntactic analysis of the program, we created a symbol table for every input source program in our language, which contains information regarding variabile identifiers such as type, scope, value or regarding functions, such as signature, whether it is a method in a class etc.
We also did a semantic analysis, including checking if:
- a variabile that appears in a program has been previously defined;
- a variabile is not declared more than once;
- the left side of an assignment has the same type as the right side.
