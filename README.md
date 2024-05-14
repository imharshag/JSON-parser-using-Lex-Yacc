# JSON Parser using Lex & Yacc

### Overview
🔍📄 This project is a JSON parser implemented using Lex and Yacc on Ubuntu. The parser reads JSON data from input files or standard input, parses it, and displays the parsed data. Additionally, it highlights any errors and displays the word near the error for easy identification.

### Prerequisites
- Ubuntu operating system.
- Lex and Yacc installed (sudo apt install flex bison).

### Compilation
- Compile the Lex file (json.l): flex json.l
- This will generate a file named lex.yy.c.
- Compile the Yacc file (json.y): yacc -d json.y
- This will generate files named y.tab.c and y.tab.h.
- Compile the parser: gcc lex.yy.c y.tab.c -o json-parser -ll -ly
- This will generate an executable named json-parser.

### Usage Run the parser
- ./json-parser < input.json
Replace input.json with the path to your JSON input file.

### Document
Project documentation can be found [here!](https://drive.google.com/file/d/1uxOyHRdZt6acDpSJiHbNwzTORLxZTxuC/view?usp=drive_link).

### Contact Information
For inquiries or feedback, please contact **[Harsha G](mailto:harshag3106@gmail.com)**

### Contributing
🛠️ Contributions are welcome! Feel free to open an issue or submit a pull request with any improvements or bug fixes.
