## Assignment:

- HTML & CSS
chapter 3 page 62-73
chapter 13 page 300-329

- JS
page 70-73
page 162-182

## CSS Boxes

- each element is displayed is a box, with the content being the inner box

- padding
  - space between element contents and its border

- margin
  - space between elements

- border
  - styled or unstyled wrap around the element

- centering content
  - ???? situational

# JavaScript

## Arrays

- can use constructor function 'new Array()'
- can assign empty array to variable 'let newArray = []'
- all the other array things that apply to python

## Loops

- if...else
  - runs if, when conditions are met
  - runs else when they are not
  - can be if, else if... , else

- switch
  - apply code based on different cases
  - requires break statememnts
  - can use 'default' case
  - faster processing than if else

- **weak** *type*
  - data types are not required to be declared in JS, types can also change within variables.
  - JS will automatically change some data types if unapplicable operators are run on them

- Truthy
  - expressions that evaluate True

- Falsy
  - expressions that evaluate Flase

- type coercion
  - string will auto convert to int if mathematical operators are applied to it

- Equality
  - `==` checks for eqivalent return values
  - `===` checks for equivalent variable values

- short circuit
  - operation stops checking as soon as first required parameter is met
  - eg. `if (true || x = 1){}` x is not checked, as the first parameter completes the if statement requirements

## Loops

- for
  - run a specific number of times
  - has three parameters
    - initialization - starting point/counting variable, should be `i`
    - condition - the limiting factor `i < 100`
    - update - increment i
  - eg. `for (i=0; i<100; i++) {outputcode}

- while
  - run an unknown number of times

- do while
  - similar to while, but will run the code ALWAYS at least once
