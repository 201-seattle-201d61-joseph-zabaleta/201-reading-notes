# Reading Notes 06

# JS Book Readings

## Chapter 3: “Object Literals” (pp.100-105)

* What is an object?  
  - Objects group together a set of variables and functions to create a model of something you would recognize from the real world. In an object, variable and functions take on new names.  
  - In an object: Variables become known as properties
  - In an object: Functions become known as methods

Properties and methods have a name and a value.  
  - In an object, that name is called a key.  
  - An object cannot have two keys of the same name, each key accesses their corresponding values.  
  - A value of property can be any data type: string, number, boolean, array, or even another object.  
  - A value of a method is always a function  

## Chapter 5: “Document Object Model” (pp.183-242)

* Document object Model = DOM  
  - DOM is made of of objects  
  - DOM Tree is a model of a webpage  

Key notes  
 - The browswer represents the page using a DOM Tree.  
 - DOM Trees have four types of nodes:  
  - Document nodes  
  - element nodes  
  - attribute nodes  
  - text nodes  
- You can slect elemetn dnodes by their id or class attributes, by tag name, or using CSS selector syntax  
- Whenever a DOM query can return more than one node, it will always return a NodeList  
- From an element node, you can access and update its content using properties such as textContent and innerHTML or using DOM manipulation techniques  
- An element node can contain multiple text nodes and child elements that are siblings of each other.  
- In older browswers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery)  
- Browswers offer tools for viewing the DOM tree.  
