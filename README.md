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

Event Delegation is a technique where we use a parent listener  instead of using separate listener and we do our task by using Event Bubbling.  


5. What is the difference between preventDefault() and stopPropagation() methods?
These two are related with event but actions are different.
preventDefault() : it stops default behavior of Element.
topPropagation() : It stops bubbling of event.
------------------*****-----------------------------------