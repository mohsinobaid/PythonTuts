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

### 3. An Informal Introduction to Python

- Integer numbers have type int, the ones with a fractional part have type float. Division always returns a float.
- To do floor division and get an integer result you can use the  // operator.
- With Python, it is possible to use the ** operatory to calculate powers 5 ** 2 --> 25
- There is full support for floating point; operators with mixed type operands convert the integer operand to floating point:

```
>>> 4 * 3.75 -1
14.0
```

- In interactive mode, the last printed expression is  assigned to the variable _ This means that when you are using Python as a desl calculator, it is somewhat easier to continue calculations, for example:

```
>>> tax = 12.5/100
>>> price = 100.50
>>> price * tax
12.5625
>>> price + _
113.0625
>>> round(_,2)
113.06
```

### 3.1.2 Strings
- Can use either '' or ""
- Use \ to escape single quotes 'doesn\'t'
- Two or more string literals (i.e. the ones enclosed between quotes) next to each other are automatically concatenated.
- Strings can be indexed (subscripted), with the first character having index 0. There is no separate character type; a character is simply a string of size one.
- Indices may also be negative numbers, to start counting from the right.
(Note that since -0 is the same as 0, negative indices start from -1)
- In addition to indexing, slicing is also supported. While indexing is used to obtain individual characters, slicing allows you to obtain substring:
```
word[0:2] #characters from position 0 (included) to 2(excluded)
word[2:5] #characters from position 2 (included) to 5(excluded)
```
- Note how the start is always included, and the end is always excluded. This makes sure that s[:i] + s[i:] is always equal to s.








