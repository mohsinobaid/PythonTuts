# Python Tutorials
[Python.org](https://docs.python.org/3/tutorial/index.html)

## Why Use Python?
- High-level data structures
- Dynamic Typing
- Interpreted nature

## Chapters
1. [x] Whetting Your appetite
2. [x] Using the Python Interpreter
3. [ ] An Informal Introduction to Python
4. [ ] More Control Flow Tools
5. [ ] Data Structures
6. [ ] Modules
7. [ ] Input and Output
8. [ ] Errors and Exceptions
9. [ ] Classes
10. [ ] Brief Tour of the Standard Library
11. [ ] Brief Tour of the Standard Library - Part II
12. [ ] Virtual Environments and Packages
13. [ ] What Now?
14. [ ] Interactive Input Editing and History Substitution
15. [ ] Floating Point Arithmetic: Issues and Limitations
16. [ ] Appendix

### 1.Whetting Your appetite
- Python allows you to split your program into modules that can be reused in other Python programs. (file I/O, system calls, sockets, and even intergaces to graphical user interface toolkits like Tk)

- Python is an interpreted language, which can save you considerable time during program development because no compilation and linking is necessary. The interpreter can be used interactively, which makes it easy to experiment with features of the language, to write throw-away programs, or to test functions during bottom-up programming development.

- Python is extensible: If you know how to program in C it is easy to add a new built-in function or module to the interpreter, either to perform critical operations at maximum speed, or to link Python programs to libraries that may only be available in binary form (such as a vendor-specific graphics library). Once you are really hooked, you can link the Python interpreter into an application written in C and use it as an extension or command language for that application.

### 2.Using the Python Interpreter

```
code
```
:+1:
1. First Item
   - First nested list item
      1. Second nested list item

- The interpreter operates somewhat like the Unix shell: when called with standard input connected to a tty device, it reads and executes commands interactively; when called with a file name argument or with a file as standard input, it reads and executes a script from that file.

- When a script file is used, it is sometimes useful to be able to run the script and enter interactive mode afterwards. This can be done by passing -i before the script.

### 3. An Information Introduction to Python

- Integer numbers have type int, the ones with a fractional part have type float. Division always returns a float.
- To do floor division and get an integer result you can use the  // operator.
- With Python, it is possible to use the ** operatory to calculate powers 5 ** 2 --> 25
- There is full support for floating point; operators with mixed type operands convert the integer operand to floating point:

```
>>> 4 * 3.75 -1
14.0
```




