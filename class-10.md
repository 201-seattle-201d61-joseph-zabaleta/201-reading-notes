# Reading Notes 10

## JS Reading Notes

### JavaScript book, Ch. 10, “Error Handling & Debugging”

- To find the source of an error, it helps to know how scripts are processed.  The order in which statuements are executed can be coplex; some tasks cannot complete until another statement or function has been run.  
- The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.  
- The JS interpreter processes one line of code at a time. When a statement neeeds data from another function, it stacks (or piles) the new function on top of the current task.  
- 

* Debugging is the process of finding errors. It involes a process of deduction.  
* The console helps narrow down the area in which the error is located, so you can try to find the exact error.  
 - to be continued..