# Static Typing in Python

There are two methods of typing in Python

1. Stubs -- support python2
2. Inline annotations -- python3

Reasons for setting the types for your function signatures (arguments and returns)?

1. Reduce the amount of test cases needed with type checking (mypy)

---

### Questions

1. What are generics and how do they relate to the mypy cli option `--disallow-any-generics`?

### NOTES

1. Generate dynamic annotations with `stubgen` from mypy -- then start writing annotations on top of that -- before getting more restrictive.
2. `Callable` any object can implement callable and beahve like a function
3. `___` 
4. ... replaces a list of arguments
5. callable cannot express variable type 

- TypeVar("T"), the callable will return the same arbitrary object.
- Not compariable to tests because it's not strictly enforced.
- Typecheckers change and could cause 
- generic self
- mypy has a relativly complex type system (comparible with haskell and scala)
- You can't look at a function and know what the bounds are.

