# Python Math Interpreter
A simple math interpreter made in Python. Can do calculations like multiplying and dividing, as well as parenthetical equations. Weirdly, it can't do equations like this, `5 + 5(1 + 1)`, I don't know why, but I'm not fixing this.

## How to use
To use the math interpreter all you have to to have make sure you have Python 3.8+ installed and run the `main.py` file. Now, in the terminal, enter any mathematical equation, and you should get a response with the answer.

## Other important information
This is a semi-fork, I just copy-pasted the code to these files from David Callanan's [original repository](https://github.com/davidcallanan/py-simple-math-interpreter/). This repository does not include the `__pycache__` folder, and does not include the testing files. To use the testing files, go to the [original repository](https://github.com/davidcallanan/py-simple-math-interpreter/) and replace the source code of the `interpreter.py, lexer.py, and parser_.py` with the source code of `interpreter_test.py, lexer_test.py, and parser_test.py`.
