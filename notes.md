* # Undefined reference to XX

Meaning: Have a reference to a function/variable, but linker cannot find the definition.

Cause: 1. Usually happens when we have multiple files,it might be a problem with liker. 2. Dont have definition

Solution: 1. Check Makefile if missing any file 2. check if any function has only prototype but does not have definition



* # Passing xxx as 'this' argument of xxx discards qualifiers



Meaning:

Cause: calling a non-const function which is belonged by a const object

Solution: add 'const' for that function

Ex. :  int get_area() const;

