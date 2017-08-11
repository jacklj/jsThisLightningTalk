### 7 engine and sh*t

- when a function is invoked, an *activation record* (a.k.a. an *execution context*) is created.
- this contains info about:
   - where the function was called from (call stack)
   - how the function was invoked
   - what parameters were passed
   - the `this` reference (used for the duration of the function's execution)
