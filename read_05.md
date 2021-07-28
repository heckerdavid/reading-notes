# CSS

Cascading style sheets (CSS) controls, or rather, allows you to control, the *presentation* of your HTML.

## CSS Syntax

CSS is a rule based language, each rule opens with a selector, selecting the desired HTML element. Once the element is selected curly brackets are used {}, inside of the curly brackets are *declarations* in __property__: *value*; pairs. each property selects the property to select, and each value assigns our desired output to that property.

## CSS Modules

CSS can control so many things, it is broken down into modules, or categories of similar item types.

### CSS Specifications

they exist, and are above my head.

#### Applying CSS

there are three ways to apply CSS to your HTML:

- external CSS
- internal CSS
- inline CSS

__external CSS__ is creating a CSS file (file.css) that links to your HTML file, this allows for control of the HTML styling while keeping the files separate and organized.

external styles are implemented with the *link* element, placed inside of the *head* section of the HTML page

__internal CSS__ may be used if a single HTML page needs a unique style.

internal styles are implemented with the *style* element inside of the *head* section of the HTML page.

__inline CSS__ are used to style *individual elements* 

inline styles are implemented by using the *style* attribute on/in the specific element

if mutliple style sheets are referenced by a given element, whichever is referenced *first* is the style the element will follow

the priority order of styling is:

1. inline styles
2. external/internal style sheets
3. browser default

##### CSS color

color can be implemented by

>color: *color*|initial|inherit

where:

- color specifies the text color
- inital set the value to default
- inherit inherits from its parent element

color can be specified with:

- HEX value
- RGB value
- RGBA value
- HSL value
- HSLA value

### References

[Mozilla CSS refernece sheets](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
[CSS almanac](https://css-tricks.com/almanac/)
[W3 Schools how to add CSS](https://www.w3schools.com/css/css_howto.asp)
[W3 schools color](https://www.w3schools.com/cssref/pr_text_color.asp)