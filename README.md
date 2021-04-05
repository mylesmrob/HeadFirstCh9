Notes for Ch.9 of Head First Java:<br />
- Two important areas of memory to remember are the stack and heap. A stack
contains methods and local variables, while a a heap contains all objects used
within a program.<br />
- Local variables, also know as stack variables, are those declared within a
method, while instance variables are declared within a class.<br \>
- When a method is called, it is pushed onto the top of a stack in what is
called a stack frame. The frame is removed once it has completed its action(s).
<br \>
- Objects always go the heap, regardless of whether an instance or local
variables is used.<br />
- The instance variables of an object are pushed onto the heap, since they live
within it. If an object itself is created as an instance, such as in a HAS-A
relationship, it is simply called through reference.
- Having more than one constructor in a class means that you have overloaded
constructors. No two constructors within a class can be identical, but are
allowed to have differing orders (such as (String, int) and (int, String) being
dissimilar.
- 
