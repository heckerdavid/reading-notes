## Text in HTML

- headings
  - `<h1>...<h6>`
- Paragraphs
  - `<p>`
- **Bold**
  - `<b>`
- *italic*
  - `<i>`
- superscript / subscript
  - `<sup>`
  - `<sub>`
- white space
  - Line break `<br />`
  - Horizontal rule `<hr />`

## CSS

CSS uses **selectors** and *declarations*. Declarations are made up of **property** and *value* pairs, separated by a colon. CSS attributes can be found [here](https://css-tricks.com/almanac/)

- CSS can be applied inline or by linking an external (style.css) file.
- if multiple style attributes are applied to a single element the applied style will be based on
  - specificity
  - which was written last
  - using important! to override other selectors

## JavaScript

- Variables
  - declared with
    - var
    - let
    - const
  - store info or reference other items
- Data types
  - strings
  - null
    - an object that represents nothing
  - numbers
    - int
    - floats  
  - boolean
    - True
    - False
- Arrays
  - created with Array() constructor function or by assigning [] to a variable
  - stores a list of values
  - can be indexed thru, arrayName[indexnumber]
  - can store **any** and/or *all* data types, as well as objects and functions
  - methods
    - .pop() removed last item from array
    - .push() adds item(s) to the end of the array
    - .shift() removes first item in the array
    - .unshift() adds item to first spot in array
    - .splice(n, x, y, y) break array at index n, can accept second argument x to deternmine how many items to splice, or y to add y 
- operators
  - mathematical operators
    - `+ - / * ++ -- %`
  - string operators
    - `"string" + variable + "string"`
- expressions
