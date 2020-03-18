# Reading notes 13

## #7 The Past, Present, and Future of Local Storage for Web Applications.

This is local storage system that is able to store named key/value pairs locally within the client web browswer. They are saved for use at anytime even after you close out the browswer.  

You can treat `localStorage` object as an associative array. You can use bracket notation for 'functions'.

`getItem()` or `getItem[]` same with setItem, and removeItem  

You can track the changes to the HTML Storage area, this is by trapping the storage event.  Whenever any changes happen on the window object that modifies anything part of html there is a listener that captures that information. You can use jQuery or other JS libraries to track these changes too.  

