# pure

**Purity** is term which originally came from functional programming.

A **pure function** typically has the following properties:

1. **Deterministic**: Given the same input, a pure
 function will always return the same output. This means
 that the function's output is solely determined by its
 input parameters, without any reliance on external state
 or variables.

2. **No Side Effects**: A pure function does not cause
 any side effects, meaning it does not modify any
 external state or variables, nor does it perform any
 observable actions (like writing to a file, modifying a
 global variable, or interacting with I/O). It only
 computes and returns a value based on its input.

For example, consider the following function:

```go
func add(a, b int) int {
    return a + b
}
```

This function is pure because it always returns the same
 result for the same inputs and does not modify any
 external state.

## Pure packages in GNO

**Pure packages** are stateless, i.e. nothing persists when they run, contrarily to [realms](realm.md). This makes them easy to interact with, and relatively safer (as it reduces the complexity).

**Pure packages** start with `/p`, for instance [/p/demo/ufmt](/p/demo/ufmt).

* See also [realms](realm.md).
