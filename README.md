# PrivateVariable
CA_PrivateVariable
Accessing Private Variables
Although we cannot directly access private variables from outside the class, there is a way to get around this. We can define a public method that returns the value of a private variable.

Instructions
Here we have included similar code from last time, but here we have added a method getBalance. Modify getBalance so that it returns bankBalance.

Then on line 17, create a new variable named myBalance and set its value to John's bank balance. You can do this by calling your newly-defined getBalance method for john. Then print myBalance.

Line 14 should still print undefined!
