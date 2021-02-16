# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* 
We click 1, the button's onClick event calls dispatch, which calls our addOne function from the actions folder, which looks at ADD_ONE from our reducers, that makes a copy of state and adds one to the total.

* TotalDisplay shows the total plus 1.
