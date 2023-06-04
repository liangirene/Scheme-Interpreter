# Scheme-Interpreter

This project aims to develop a Scheme interpreter and its read-eval-print loop. Scheme is a dialect of the Lisp programming language known for its simplicity and expressive power. The interpreter enables users to write and execute Scheme code, providing a platform for exploring and experimenting with Scheme programming.

Throughout the development process, I delved into the intricacies and challenges of programming language design, carefully considering the characteristics of the Scheme subset. I made design choices that prioritize compatibility within the defined boundaries of the subset. Although there might be slight variations in behavior compared to other implementations, my interpreter remains faithful to the specified subset.

In addition to building the interpreter, I also wrote small programs in Scheme. This exercise revealed the simplicity and power of the language, while highlighting the transferability of programming concepts across different languages, including Python.

By undertaking this project, I deepened my understanding of programming language concepts and honed my skills in interpreter development. It provided me with practical experience in working with Scheme, enhancing my ability to work with diverse programming languages. This project served as a valuable exploration of language interpretation and functional programming principles.


## Features

- Scheme expression evaluation: The interpreter supports the evaluation of Scheme expressions, including basic arithmetic operations, conditionals, and function calls.
- Environment management: The interpreter handles environment frames, allowing for variable bindings and scoping rules.
- Special forms: Special forms, such as `if`, `define`, `lambda`, and `let`, are implemented to handle control flow and define procedures.
- Built-in procedures: The interpreter includes a set of built-in procedures that provide additional functionality beyond basic arithmetic, such as string manipulation and list operations.
- Quasiquote and unquote: The interpreter supports quasiquote expressions and handles the evaluation of unquote expressions within quasiquote forms.

## Key Implementation Details

- Lexical scoping: The interpreter implements lexical scoping, enabling variables to be defined and accessed within their respective scopes.
- Environment frames: The project utilizes environment frames to manage variable bindings and handle variable lookup during expression evaluation.
- Recursive evaluation: The interpreter supports recursive evaluation, enabling the evaluation of nested expressions and function calls.
- Parsing and syntax analysis: The project includes a scheme_reader module that parses Scheme expressions and constructs an abstract syntax tree for evaluation.
- Symbol manipulation: The interpreter treats symbols as first-class objects, performing symbol lookup and binding during evaluation.
- Macro expansion: The project introduces a macro procedure for expanding macros, allowing for advanced code transformations.

