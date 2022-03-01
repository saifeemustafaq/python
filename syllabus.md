All the below syllabus is being fetched from https://pythoninstitute.org/certification/pcap-certification-associate/pcap-exam-syllabus/

# 1: Control and Evaluations

- basic concepts: interpreting and the interpreter, compilation and the compiler, language elements, lexis, syntax and semantics, Python keywords, instructions, indenting
- literals: Boolean, integer, floating-point numbers, scientific notation, strings
- operators: unary and binary, priorities and binding
- numeric operators: ** * / % // + –
- bitwise operators: ~ & ^ | << >>
- string operators: * +
- Boolean operators: not and or
- relational operators ( == != > >= < <= ), building complex Boolean expressions
- assignments and shortcut operators
- accuracy of floating-point numbers
- basic input and output: input(), print(), int(), float(), str() functions
- formatting print() output with end= and sep= arguments
- conditional statements: if, if-else, if-elif, if-elif-else
- the pass instruction
- simple lists: constructing vectors, indexing and slicing, the len() function
- simple strings: constructing, assigning, indexing, slicing comparing, immutability
- building loops: while, for, range(), in, iterating through sequences
- expanding loops: while-else, for-else, nesting loops and conditional statements
- controlling loop execution: break, continue


# 2: Data Aggregates

- strings in detail: ASCII, UNICODE, UTF-8, immutability, escaping using the \ character, quotes and apostrophes inside strings, multiline strings, copying vs. cloning, advanced slicing, string vs. string, string vs. non-string, basic string methods (upper(), lower(), isxxx(), capitalize(), split(), join(), etc.) and functions (len(), chr(), ord()), escape characters
- lists in detail: indexing, slicing, basic methods (append(), insert(), index()) and functions (len(), sorted(), etc.), del instruction, iterating lists with the for loop, initializing, in and not in operators, list comprehension, copying and cloning
- lists in lists: matrices and cubes
- tuples: indexing, slicing, building, immutability
- tuples vs. lists: similarities and differences, lists inside tuples and tuples inside lists
- dictionaries: building, indexing, adding and removing keys, iterating through dictionaries as well as their keys and values, checking key existence, keys(), items() and values() methods

# 3: Functions and Modules

- defining and invoking your own functions and generators
- return and yield keywords, returning results, the None keyword, recursion
- parameters vs. arguments, positional keyword and mixed argument passing, default parameter values
- converting generator objects into lists using the list() function
- name scopes, name hiding (shadowing), the global keyword
- lambda functions, defining and using
- map(), filter(), reduce(), reversed(), sorted() functions and the sort() method
- the if operator
- import directives, qualifying entities with module names, initializing modules
- writing and using modules, the \_\_name__ variable
- pyc file creation and usage
- constructing and distributing packages, packages vs. directories, the role of the \_\_init__.py file
- hiding module entities
- Python hashbangs, using multiline strings as module documentation

# 4: Classes, Objects, and Exceptions

- defining your own classes, superclasses, subclasses, inheritance, searching for missing class components, creating objects
- class attributes: class variables and instance variables, defining, adding and removing attributes, explicit constructor invocation
- class methods: defining and using, the self parameter meaning and usage
- inheritance and overriding, finding class/object components
- single inheritance vs. multiple inheritance
- name mangling
- invoking methods, passing and using the self argument/parameter
- the \_\_init__ method
- the role of the \_\_str__ method
- introspection: \_\_dict__, \_\_name__, \_\_module__, \_\_bases__ properties, examining class/object structure
- writing and using constructors
- hasattr(), type(), issubclass(), isinstance(), super() functions
- using predefined exceptions and defining your own ones
- the try-except-else-finally block, the raise statement, the except-as variant
- exceptions hierarchy, assigning more than one exception to one except branch
- adding your own exceptions to an existing hierarchy
- assertions
- the anatomy of an exception object
- input/output basics: opening files with the open() function, stream objects, binary vs. text files, newline character translation, reading and writing files, bytearray objects
- read(), readinto(), readline(), write(), close() methods

# 5: Modules and Packages

- import variants; advanced qualifiying for nested modules
- dir(); sys.path variable
- math: ceil(), floor(), trunc(), factorial(), hypot(), sqrt(); random: random(), seed(), choice(), sample()
- platform: platform(), machine(), processor(), system(), version(), python_implementation(), python_version_tuple()
- idea, \_\_pycache__, \_\_name__, public variables, \_\_init__.py
- searching for modules/packages; nested packages vs directory tree
 

# 6: Exceptions

- except, except:-except; except:-else:, except (e1,e2)
- the hierarchy of exceptions
- raise, raise ex, assert
- event classes, except E as e, arg property
- self-defined exceptions, defining and using
 

# 7: Strings

- ASCII, UNICODE, UTF-8, codepoints, escape sequences
- ord(), chr(), literals
- indexing, slicing, immutability
- iterating through,
- concatenating, multiplying, comparing (against strings and numbers)
- in, not in
- .isxxx(), .join(), .split()
- .sort(), sorted(), .index(), .find(), .rfind()
 
# 8: Object-Oriented Programming

- ideas: class, object, property, method, encapsulation, inheritance, grammar vs class, superclass, subclass
- instance vs class variables: declaring, initializing
- \_\_dict__ property (objects vs classes)
- private components (instance vs classes), name mangling
- methods: declaring, using, self parameter
- instrospection: hasattr() (objects vs classes), \_\_name__, \_\_module__, \_\_bases__ properties
- inheritance: single, multiple, isinstance(), overriding, not is and is operators
- inheritance: single, multiple, isinstance(), overriding, not is and is operators
- constructors: declaring and invoking
- polymorphism
- \_\_name__, \_\_module__, \_\_bases__ properties, \_\_str__() method
- multiple inheritance, diamonds
 

# 9: Miscellaneous (List Comprehensions, Lambdas, Closures, and I/O Operations)

- list comprehension: if operator, using list comprehensions
- lambdas: defining and using lambdas, self-defined functions taking lambda as as arguments; map(), filter();
- closures: meaning, defining, and using closures
- I/O Operations: I/O modes, predefined streams, handles; text/binary modes
- open(), errno and its values; close()
- .read(), .write(), .readline(); readlines() (along with bytearray())
