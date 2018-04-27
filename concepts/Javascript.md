# Inbuild functions

* nameofstring.repeat (argument - a number) (repeats the string a given number of times)

* alert
 * displays an error message in a separate box ("outside of your site" like)
 * syntax: alert("the Message You Want To Show")

# Constructios

* try catch (tries something and if it does not work throuws('catches') error)
syntax:  
try{function (or operation)}
catch{}

* ternary operator
(some condition to check) ?  (something to evaluate or execute - if the condition evaluates to true): something to do if condition evaluates to false

* eval()
eval (some condition to check or execute)  
very dangerous opration for it will do whatever is inside the parenthesis

# General Notions

## Pure Vs. Inpure functions
 * pure does not modify any variable which is not passed to or declared within the function
 * inpure - modifies variables in another scope (higher function or global scope) - Bad practice!

## State-based applications
* store the "state" of the data at a given point in time / after some (user or program) interaction has taken place

# Operators

## exclamation mark !
 * means 'not'
 * x = !x (for booleans: sets x to a different value than x was previously. For other variables/data types it will return false (because the truth value of a given variable is true))

# Arrays

* Deleting an item .splice method - allows to specify a range of array items to delete
nameOfArray.splice (index of first item to be deleted, number indicating how many items you want to delete starting from that indez)  
e.g. array.splice (3, 1) will delete item at index 3
array.splice (3, 2) will delete items at index 3 and 4