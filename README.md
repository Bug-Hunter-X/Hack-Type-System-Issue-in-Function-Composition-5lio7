# Hack Type System Issue in Function Composition

This repository demonstrates a subtle bug in the Hack type system related to function composition and unexpected type coercion. The bug arises from a situation where the type system doesn't explicitly enforce a check that would prevent an unexpected result.  The `baz` function, when composed with `foo` and `bar`, produces an incorrect output.  The `bugSolution.hack` file offers a possible fix.