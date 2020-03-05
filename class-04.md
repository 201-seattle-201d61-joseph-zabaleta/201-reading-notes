# Reading Notes 04

## HTML BOOK READINGS

### Chapter 4: Ch.4 “Links” (pp.74-93)  
  
* Writing Links  
  - Link are created using the anchor tag <a></a>  
  - Anchor tag utilizes the href attritube to  connect to page or path or id you choose.  

  - Linking to other sites uses "url"  
  - Linking to other pages on the same site "about-us.html"  
    - Relative paths can be same folder, child, grandparent, just specify the path  

  - Linking emails uses href=" 'mailto: email @here .com"
    -  This will open a users email program to initiate an email.  

  - Links can be opened in a new tab / new window utilizing a 'target' attribute.
    - target="_blank"

  - Linking to specific place on the current page  
    - jumps to specific id elements  
    - href="#---" or href="#idgoeshere"  

  - Linking to a specific place on another page  
    - Still utilizes id elements to jump too  
      - href="url/#someidhere"  


### Chapter 15: “Layout” (pp.358-404) This layout chapter is BIG. Focus your attention on understanding the core concepts presented on pp.358-364

## Key Concepts in Position Elements  
  
CSS Treats each HTML element as if it is in its own box. Building Blocks. This box will either be block-level box or inline box.  
  * Block-Level elements:  
    - Start on a new line  
    - Examples: <h1> <p> <ul> <li>  
    
  * Inline Elements  
    - Flow between surrounding text  
    - Examples: <img> <b> <i>  
  
Containing elements are those who contain a box within side its element. 
 - Example would be the <body> it contains the body of a webpage.

## Controlling the position of elements  
  
  There are a few position schemes that CSS uses: Normal flow, Relative Position, Absolute Positioning, Fixed Positioning and Floating elements.  
    - Box offset properties tell the browswer how far from the top or bottom, left or right it should be placed.  

* Normal Flow  
  - Each block-level element sits on top of each other on its own line.  
  
* Relative Positioning  
  - Moves an element in relation to where it would have been in normal flow  
  
* Absolute Positioning  
  - This takes the box out of normal flow and no longer affects the position of other elements on the page.
  
* Fixed Positioning  
  - This is a type of Absolute positioning  
  - It requires that position property to have a value of fixed  
  - Positions an element in relation to the browswer window  

## JS BOOK READINGS

### Chapter 3 (first part): “Functions, Methods, and Objects” (pp.86-99 ONLY)

  
### Article: “6 Reasons for Pair Programming”

Reasons as follows:  
  
* How does pair programming work?  
  - There are two roles: The Driver and the Navigator
    - The Driver: Does all the mechanical work, controls the input of the code, does the typing of all the code, manages version control, worker bee  
    - The Navigator: Guides the driver with words, sees the big picture, scans for typos and bugs, guides the project, and researches issues on personal lapop  

* Why pair programming?  
    - Touches the four learning skills: Listening, Speaking, Reading, and Writing.  
    -During lab sessions code fellow students work on all these language-specific skills. Which will help excel in completing assignments, interviews and better prepared for work.  

  * Greater efficiency  
      - Easier to catch mistakes with two sets of eyes on the same code base  
      - Takes longer to produce a product but is of higher quality code that requires less troubleshooting and debugging  
      - Enhances technical skills, communication, and develops an enjoyabality of a workplace  

  * Engaged collaboration  
      - Two programmers working together are more focused
      - Working as a group deters the act of distracting habits such as facebook scrollilng  
      - Asking for help is a big part of collaboration. Fifteen minutes rule.  

  * Learning from fellow students  
    - Different approaches to problem solving  
    - Different skill sets coming together  
    - less experienced vs experienced developers  
    - Defining topics in own words to learn  
  
  * Social skills
    - Improves social skills  
    - Communication is key in teamwork and workplace  
    - Develops interpesonal skills  
    - Learn to put words to mouth about about code  

  * Job interview readiness  
    - Interview processes include paired programming iwth employee and applicant  
    - Shows collaboration style to employers  
    - Ability to work with and learn from others is a desired trait in the workforce  

  * Work enviroment readiness
    - Many companies expect to train new hires how to actually operate and use pair programming  
    - Code fellows helps develop this skill before the real world  

    
