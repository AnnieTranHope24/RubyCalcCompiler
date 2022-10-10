Annie Tran

Differences between C++ and Ruby:
- C++ is statically typed, Ruby is dynamically typed. Thus,
I didn't have to specify the type of variables when working
with Ruby.
- I didn't need inheritance to perform polymorphism.
- Ruby code is much shorter. I didn't need separate header
files for Ruby classes.
- Because of attr_reader, getting access to fields in Ruby is much simpler.
- When having type errors, it is not until runtime that Ruby can detect them.

EWE code works for Multiply, Divide, Store, Recall, and Input
- Using stack.
- For Multiply, Divide, I did the same as for Add and Subtract 
- For Store, write "memory:= A" in the ewe file. A is the last
value we get to.
- For Recall, write "A:= memory" in the ewe file. Now we use A to get
the memory.
- For Input, readInt(prompt), and store prompt in A.