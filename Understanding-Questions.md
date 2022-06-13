# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* the handleAddOne function is called.
* the dispatch is invoked with (addone())
* addone() returns {type:ADD_ONE} as the argument to dispatch()
* dispatch passes {type:ADD_ONE} to the reducer fuction which returns a new state with an updated state total +1
* the new state total is set to state and the new data renders on to the screen

* TotalDisplay shows the total plus 1.
