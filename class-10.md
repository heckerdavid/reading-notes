# JavaScript Error handling and debugging

- the stack
  - since JS is interpreted one line at a time, if a line requires info from another line it *stacks* the new function on top of the current task

- exceptions
  - when errors occur in JS an exception is thrown
  - the interpreter then looks for exception handlers
  - if none are found the code stops execution
  - if an exception handler is present the code is run and the program continues

- error objects are created to help identify and solve errors for the developer
  - Error
    - generic error type, all other errors are based on this
  - SyntaxError
    - proper syntax was not used
  - ReferenceError
    - attempted to use an undefined/unavailable variable
  - TypeError
    - improper data type used, cannot be coerced
  - RangeError
    - numbers not in allowed range
  - URIError
    - `encodeURI()` `decodeURI()` improperly used
  - EvalError
    - `eval()` improperly used

## Exception handling

- Try
  - try this code
- catch
  - if this error happens, do this
- finally
  - after all that, do this
the above are used to catch errors and prevent your script from crashing, also to give the user feedback and what they are doing wrong