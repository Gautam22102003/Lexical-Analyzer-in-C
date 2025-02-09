# Lexical-Analyzer-in-C
The lexical analyzer breaks the code into tokens, which are the smallest individual units in terms of programming. In the lexical analysis phase, we parse the input string, removing the whitespaces. Our main focus is to break down the code into small tokens.

A lexical token is a sequence of characters with a collective meaning in the grammar of programming languages. These tokens include Keyword, Identifier, Operator, Literal, and Punctuation.

### Explanation:

The code implements the following functions :

- 'bool delimiter (char chr): This function takes one parameter (character value). This function checks for the delimiter(separator that is responsible for separating a piece of code from the others) in the code.'
- 'bool isOperator(char chr)also: This function too accepts one parameter (character value). This function checks if the passed value is an operator or not.'
- 'bool isValidIdentifier(char* str) : This function accepts one parameter(character value). This function uses call by reference unlike the other two we saw in the first. This function checks if the passed value is - a valid identifier. A valid identifier should not start with any number or delimiter.'
- 'bool isKeyword(char *str) : This function accepts one parameter(character value). This function like the previous one uses call by reference. This function checks if the pass value is a keyword or not. Keywords are some reserved words in any programming language that we cannot use in naming variables or functions.'
- 'bool isInteger(char* str): This function accepts parameters like the other two previous functions. This function is used to check if the passed value is an integer or not.'
- 'char* getSubstring(char* str, int start, int end) : This functions accepts three parameters. It takes a string and two two integer values: start and end. It cuts the string from the start's value to the end's value. This function returns a substring.'
- 'int lexicalAnalyzer(char* input): This function accepts one parameter. This function is responsible for parsing the passed value and displaying the results accordingly.'

'Note:
- Syntax Errors are not evaluated in lexical analysis phase. It will be taken care of in the next compilation phase (syntax analysis phase).'

### Conclusion
- The above program is an implementation of a lexical analyzer program in C language. In the compilation process, the Lexical analysis phase is the first step. In this step, the lexical analyzer breaks down the input code into small units called tokens ( for example keywords, identifiers, operators, literals, and punctuation).

- The lexical Analyser function parses the input code and then prints all the tokens identified by the program with their corresponding values. The lexical analyzer's major focus is on breaking down the code and identifying the tokens.
