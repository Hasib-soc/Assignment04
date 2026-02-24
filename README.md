1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
getElementById:

These all are used for selecting element from DOM. But their actions amd features are different:
getElementById: it selects only a element by id.

getElementsByClassName: it selects more than one element by indefinite class.
querySelector: it takes 1st matching element by using css.
querySelectorAll: it takes all matching element by using css.



2. 
craeting new element by javascript to push into DOM , has three steps for instance
1.create new element
2.adding attribute
3.insert DOM


3. What is Event Bubbling? And how does it work?
Event Bubbling such a process whereas if event happens in child element, that event forwarding to parent → grandparent → document 

4. What is Event Delegation in JavaScript? Why is it useful?

Event Delegation as a "Smart Manager" strategy. Instead of giving instructions to every single employee (element). the instructions to the manager (parent element) and let them handle everything that happens in their department. it useful because 1. Better Performance. 2. Works for "Future" Elements
5. What is the difference between preventDefault() and stopPropagation() methods?
preventDefault() methods:

stops that specific "default" thing from happening, but the event still "bubbles up" the DOM tree. Common Use Case: Form validation or custom link behavior.
stopPropagation() methods:

stops that specific "default" thing and Don't let this event bubble up any further. Common Use Case:Preventing a child click from triggering a parent's "close" or "delete" function.