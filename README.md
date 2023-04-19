# Compiler-Design
## Tiny Compiler 

### Description 
A TinyL compiler consists mainly of two phases:
- Lexical Analysis ([Scanner.cs](https://github.com/abdozargina/Compiler-Design/blob/main/Tiny_Compiler_Project/Scanner.cs)) 
- Syntax Analysis ([Parser.cs](https://github.com/abdozargina/Compiler-Design/blob/main/Tiny_Compiler_Project/Parser.cs))
 
### Lexical Analysis Phase
It takes the TinyL code and scans it token by token. Then, it producues a DataGridView with every lexeme and its token type. Also, there is an error list which catches the lexemes which has no token type and generates it in a DataGridView. 

### Syntax Analysis Phase
It is a discovering structure phase in the code which determines whether a text follows the expected format.
- Obtain tokens from the lexical analyzer.
- Checks if the expression is syntactically correct or not.
- Report all syntax errors.
- Construct a hierarchical structure which is known as a parse tree.

### Developers
- **Hossam Hassan 180871**
- **Abdallah Hesham 179674**
- **Mostafa Mahfouz 182004**
- **Mirna Victor 190860**

### Snapshots
![image](https://user-images.githubusercontent.com/42946298/148419743-d307cac5-b0e8-4853-b313-acba8fb541a9.png)
![image](https://user-images.githubusercontent.com/42946298/148419923-edd71cfa-f2ad-43d8-a4d6-8135170dd103.png)
