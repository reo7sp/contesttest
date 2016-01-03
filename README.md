# contesttest

Makes running your programs made for programming contests more pleasant.

```
Usage: contesttest SCRIPTNAME [ACTION] [TESTSDIR]

Actions:
    t, test     Compiles and runs your program and then automatically provides tests to stdin and checks for the answer. This is the default action if no one suplied.
    r, run      Compiles and runs your program.
    d, debug    Compiles the program and then runs the debugger.

Test format:
    TESTSDIR/SCRIPTNAME/f.in  - it's where test's input is kept,
    TESTSDIR/SCRIPTNAME/f.out - it's where test's answer is kept
        where f can be any string.

Supported languages:
    C++, C, Python, Java.
    If you need a language which is not listed here, write an issue or send a pull request at the github page.

Additional notes:
    If pypy is installed, contesttest will use pypy for python programs. To prohibit it set the enviroment variable NOPYPY to 1.
```
