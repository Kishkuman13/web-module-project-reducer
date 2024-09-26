# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.

* OnClick event listener fires
* The Callback function is invoked and calls numberHandler and passes in the number 1
* Dispatch is invoked
* The addOne function is invoked, passing in the number 1 and returns an object with the type:ADD_ONE
* The returned object is passed to the reducer as the action
* The action is evaluated by the switch
* The matching action updates state, adding the current state total + 1

* TotalDisplay shows the total plus 1.
