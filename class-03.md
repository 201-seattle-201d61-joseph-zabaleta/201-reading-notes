# Reading Notes 03

## HTML BOOK READINGS

### Chapter 3: "Lists" (pp.62-73)
Overview of lists:  
Simply put there are three types of html lists:  
  -Ordered <ol>  
  -Unordered <ul>  
  -Definition <dl>  
  
They all function the same by listing items on a list with bullet points.  
  
* Key Note
  -Lists can be nested inside other lists.

### Chapter 13: “Boxes” (pp.300-329)

Boxes surround all elements in html, visible with border properties or invisible by default.

CSS can control how we manipulate these boxes in html by controling the border, size, margins, padding and location in the browswer.

Highlights 

* Box Dimensions  
  -Top, right, bottom, left

* Limiting Width  
  -min-width and max-width

* Limiting Height  
  -min-height and max-height

* Overflowing Content  
  -overflow: hidden and overflow: scroll

* Border, Margin, Padding  
  -Border surrounds an element  
  -Margin is the buffer on the outside of border  
  -Padding is the space between the border and the content in the a box  

* White Space, Vertical Margin  
  -Space between items is refered to as White space  
  -Vertical margin top and bottom margins do not add but the largest one is used  

* Border Width, Style, and Color  
  -Border width: thin, medium, thick and can be expressed shorthand by 3px 3px 3px 3px , four values  
  -Style: controls the look of the border such as: solid, dotted, dashed......  
  -Color: border color on all sides or individual sides ... border-color: red;  

* Centering Content  
  -Can be tricky , but using auto in the margin along with setting the width of the box element. If you do not set the width, the element will not be able to auto adjust the left and right margins do center the object.

## JS BOOK READINGS 

### Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)
Continuing on from day 2's reading.... 
All 'switch' 'if' and 'else' statements run on conditions some of these conditions are booleans: True or False

Javascript will try and make sense of data types you give it in order to complete its operation. This mean it will work hard to determine what you were really trying to evaluate and will even change some code to do it. This is called 'type coercion'

As a result of 'type coercion' we can create values that can be treated funny and result in a true or false value these are called 'truthy' and 'falsy' values. 

To help eliminate errors and avoid unexpected truthy and falsy values its best to use stict equality operators '===' and '!=='.

'Unary operator' returns results with just one 'operand' this can be used to checking equality and existence.

Short Circuit values come into play when logical operators are processed and have a result. They do not continue the script once a condition has been met or satisfied.

-Looping
There are three types of loops 'for' 'while' and 'Do while' Loops run a code x amount of times per the conditions given
  -'for' loop runs x amount of times and is the most common loop
  -'while' loop will continue to run code as long as the condition is true.
  -'Do while' loop has key difference from the 'while' loop and that is, it will run all the code at least once even if the conditions result in false.

-'For' Loop
This loop uses a counter as a condition. Instructs the code to run x amount of times. The condition has three statements
  -Initilization
  -condition
  -update

* KEY LOOP CONCEPTS

-Keywords
  -break: this causes termination of the loop and moves onto the next statement outside the loop
  -continue: stops the current iteration and then update and check the condition again (if true the code continues to run)

-Performance Issues
  -If your condition never returns a false, you get what is called an infinite loop which will run until your browswer runs out of memory and breaks. (breaking your script)