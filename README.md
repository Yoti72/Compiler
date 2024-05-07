Yoti to C Compiler

This is a compiler written in Python that converts Yoti programming language code into C code. When the user runs the script, it generates a .c file corresponding to the input .yoti file.


Introduction

Yoti is a simple programming language designed to facilitate learning programming concepts. This compiler translates Yoti code into C code, making it executable on platforms with a C compiler. This basic implementation of a compiler consist of three parts: Lexer, Parser, Emitter. The lexer toxenizes the lines of code, the parser parses through the tokens, and the emitter emits the corresponding C code.


Features

    Converts Yoti code to C code
    Generates a .c file for each input .yoti file
    Simple and easy-to-understand syntax
    
It supports:

    Numerical variables
    Basic arithmetic
    If statements
    While loops
    Print text and numbers
    Input numbers
    Labels and goto
    Comments


Installation

1. Clone this repository:
    git clone https://github.com/your-username/compiler.git

2. Navigate to the repository directory:
    cd src

3. Ensure you have Python 3 installed.


Usage 
1. Give permissions to the script:
      "chmod +x build.sh"
   
2. Run script
      "./build.sh hello.yoti"

3. Enjoy output in hello.c


Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.
     
