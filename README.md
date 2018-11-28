# Programming language concepts summary
## Reasons for studying programming languages
...Write a captivating summary here...
## Von Nuemann architecture
![Von Nuemann architecture](https://proxy.duckduckgo.com/iu/?u=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2Fthumb%2Fe%2Fe5%2FVon_Neumann_Architecture.svg%2F1200px-Von_Neumann_Architecture.svg.png&f=1)

## Harvard architecture
- Seperate bus for instructions and data
- Seperate address space

## Modified Harvard architecture
- CPU cache
- Seperate buses for instructions and data to cache
- One bus towards main memory
- In wide use now

### Program counter


## Program design methodologies

## Programming methodologies influences
**1950's and early 1960's:** simple applications; worry about machine efficiency

**Late 1960's:** People efficiency became important' readability, better control structures

**Late 1970's:** Process-oriented to data-oriented

**Middle 1980's:** Object-oriented programming, Data abstraction + inheritance + polymorphism

## Language categories
**Imperative**
Central features are variables, assignment statements and iteration.
**Functional**
Main means of making computations is by applying functions to given parameters.
**Logic**
Rule-based (rules are specifiefd in no particular order).
**Markup programming hybrid**

## Programming paradigms
![Programming language paradigms](https://proxy.duckduckgo.com/iu/?u=https%3A%2F%2Fimage.slidesharecdn.com%2Fprogrammingparadigms-120517103615-phpapp02%2F95%2Fprogramming-paradigms-1-728.jpg%3Fcb%3D1337681177&f=1)


## Programming language design decisions
### Reliability vs. cost of execution
Read the book and write here
### Readability vs. writeability
Read the book and write here
### Writeability (flexibility vs. reliability)
Read the book and write here

## Implementation methods
### Compilation
Programs are translated into machine language: includes JIT systems. Used for large commercial applications.

### Pure interpretation
Programs are interpreted by another program know as an interpreter. Used for small programs or when efficiency is not an issue.

### Hybrid implementation systems
A compromise between compilers and purei interpreters. Used for small and medium systems when efficiency is not the first concern.

## Compilation
Translate high-level program (source language) into machine code (machine language). Slow translation but fast execution. Compilation process has several steps.

## Aditional compilation terminologies
Load module (executable image). The user and system code together.

## Von Nuemann bottleneck
Connection speed between a computers memory and its processor determines the speed of a computer

## Pure interpretation
No translation 

Translated into an intermediary language.

Easier implementation of programs.

Often requires more space.

Rare nowadays for traditional high-level languages.

Significant comeback with some web scripting languages such as Javascript and PHP.

## Hybrid implementation systems
A compromise between compilers and pure interpretation

## Just-in-time implementation systems
Initially translate programs to an intermediate language

## Preprocessors
Preprocessor macros are commonly used to specify that code from another file is to be included

A preprocessor processes a program immeditately before the program is compiled to expand embedded preprocessor macros.

A well-known example is the C preprocessor
- Expands #include, #define and similar macros

## Programming environments
A collection of tools used in software development

### UNIX
An older operating system and tool collection
Noawadays often used through a GUI that runs on top of UNIX

### Microsoft visual studio .net
A large complex visual environment

### Intellij IDEA

### Netbeans

## Fortran
One of the first programming languages.

### Fortran II

### Fortran IV

### Fortran 77
Variable declarations

### Fortant 90
Modules
Dynamic arrays
Pointers
Recursion
CASE statement
Parameter type checking

### Latest versions of fortran
#### Fortran 95
#### Fortran 2003
Support for OOP, procedure pointers, interoperability with C
#### Fortran 2008

### Fortran evaluation
Highly optimizing compilers (all versions before 90)
- Types and storage of all variables are fixed before runtime

Dramatically changed the way computers are used forever.

## LISP functional programming
LISt processing language designed at MIT by McCarthy. The first functional language. It is still the dominant language for AI. COMMON LISP and Scheme are contemporary dialects of LISP.

AI research needed a language to process data in lists.

## Scheme

## COMMON LISP

## ALGOL 58

## ALGOL 60
Standard way to publish algorithms for over 20 years.

Never widely used, especially in the U.S.

Reasons: No I/O, too flexible (hard to implement), Entrenchment of Fortran, Formal Syntax description, lack of support from IBM

## COBOL
First language with MACRO facilities.
### FLOW-MATIC

### Design process

### DoD influence

## BASIC: The beginning of timesharing
**First widely used language with ***time sharing*****

Simple programming language that was easy to learn and use for non-science students. Free and private access. User time was more important that ncomputer time.

The current popular dialect is Visual BASIC.

## Snobol

## APL

## Simula 67

## PASCAL
Designed for teaching structured programming. Small simple and nothing really new. Largest impact was on teaching programming.

## C
Designed for systems programming at Bell labs in 1972. Evolved primarily from BCLP and B, but also ALGOL 68. Powerful set of operators but poor type checking. C initially spread through UNIX. Although it was designed as a systems language, it has been used in many application areas.

## Prolog
Based on formal logic, non-procedural. Can be summarized as being an intelligent database system that uses an infering process to infer the truth of given queries. It is comparatively inefficient and has few application areas.

## Ada
Huge design effort involving hundreds of people, alot of money and about eight years. Named Ada after Augusta Ada Byron, the first programmer.

### Ada 95
Support for OOP through type derivation. Better control mechanisms for shared data

## Smalltalk
Developed at Xerox PARC. First full implementation of an object-oriented language (data abstraction, inheritance and dynamic binding). Pioneered the graphical UI design. Promoted OOP.

## C++
A large and complex language, in part because it supports both procedural and OO programming. Rapidly grew in popularity, along with OOP. Microsofts version was MC++ with properties, delegates, interfaces and no multiple inheritance.

## JAVA
Developed at SUN in the early 1990's C and C++ were not satisfactory for embedded devices.

Eliminated many unsafe features of C++.  Supports concurrency. Libraries for applets, GUI'S, database access.

## PERL

## JavasScript
A client-side HTML-embedded scripting language, often used to create dynamic HTML documents. Purely interpreted.

## PHP
Hypertext preprocessor, purely interpreted.

## LUA
An OO interpreted scripting language.

## Microsoft .NET C#
Part of the .NET development platform (2000). Based on C++, Java and Delphi. Includes pointers, delegates, properties, enumeration types. Rapidly evolving.

## Functional languages: Elixir
Builds on top of Erlang. Everything is an expression.