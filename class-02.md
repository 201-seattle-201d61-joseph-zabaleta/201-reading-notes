# Reading Notes 02

## HTML BOOK READINGS

### Chapter 2: “Text” (pp.40-61)
In chapter two it covers the "text" portion of a webpage. The elements / tags associated with text and how add text to our webpages.
Below are example tags used for text
    - <h1></h1> heading 1, there are headings 1 the largest to 6 the smallest
    - <p></p> for paragraphs
    - <b></b> bold
    - <i></i> italic
    - <sup></sup><sub></sub> superscripts and subscripts 
White space is something used to make code clearer to read and as well as for our text to be easier to read once displayed. Browswers ignore two white spaces next to each other and only displays one.

Along with all these tags to describe the structure of the webpage, there are also tags for quotations, acronyms, and ways to apply emphasis on specific parts of text.

### Chapter 10: “Introducing CSS” (pp.226-245)

Cascading Style Sheets, CSS. Each element on a webpage has its own space, its own box. This box maybe visable with a border or invisible. CSS allows us to manipulate these boxes, create rules, in order to achieve a desired outcome. Some examples would be width, height, borders, background color and images, and position.  Text can be changed by size, color, typeface, and upper/lower case.

CSS is associating rules with html elements. It has two parts: Selector and a declaration.
example:
  p {                                       <----- p for paragraph element is our selector
    font-family: Arial; }                   <----- and font-family: Arial is our declaration
    
Declarations are composed of a property and a value. Above we have a font-family property and Arial is our value given.

CSS Rules are usually stored in an external file but can appear in the HTML of a page.

Key Note: Last rule applys, if there are identical selectors the last one will be applied over the first one.


## JS BOOK READINGS 

### Chapter 2: “Basic JavaScript Instructions” (pp.53-84)

What is a variable? In JavaScript we use variables to store data. Like a container. Each variable will have a name and is assigned a specific value. The value can be a numeric data type, string data type, and boolean data type.  

Scripts are made up of statements which are linear and execute in order. Variables help us store data in smaller names or group large code into a single word, and arrays are a special variable that has multiple variables stored within.  JS using operators to calculate and return a value.


### Chapter 4: “Decisions and Loops” only up to the section on switch statements (pp.145-162)

In this chapter we talk about how our script can evaluate expressions and make a decision on which script to run next based on a certain value.  A flow chart is used to help identify the route your code should take, a yes or no can lead to script A or script B. This is the decision part. to be continued......

