# C
Ansi C from K&amp;R

Prperties of a Variable
-----------------------
**Name**	A unique identifier used to access the memory location. Names must follow specific rules (start with a letter or underscore, no spaces, not a reserved keyword, case-sensitive).
**Type**	Defines the kind of data the variable can store (e.g., int for integers, float for floating-point numbers, char for single characters), its size in memory, and the operations that can be performed on it.
**Value**	The actual data stored in the memory location at any given time. This value can change (vary) during program execution. If uninitialized, a variable contains a "garbage" value.
**Address**	The specific memory location where the value is stored. Programmers typically interact with the name, but the compiler manages the underlying address. The & operator can be used to retrieve this address.
**Scope**	Determines the visibility or accessibility of the variable within the program. Common scopes include local (within a function or block) and global (accessible throughout the program).
**Lifetime**	The duration for which the variable exists in memory during program execution. This is often tied to its scope; for example, a local variable's lifetime typically ends when the function it is in returns.
