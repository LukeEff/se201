### 1.

The functions in this style are idempotent and have no side effects in the
observable world. This is because the functions take one input value and produce
one output value. Also because there is no state outside the functions and will
always produce the same output for a given input.

### 2.

It is tricky to tell what is exactly being passed into the other. Most notably,
the parts where [0:25] is since it's hard to follow what that means in this
context. 

### 3.

Functional programming is about writing pure functions without side effects,
where code with functions might do that, but also might have side effects and
interact with outside variables and what not.
