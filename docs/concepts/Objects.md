# Difference Between dots . and brackets [] (for calling)

* object.nameOfProperty  
-> returns the value of the property

* object[nameOfVariabla]  
-> will take the value of the variable and look if that is a property inside the object. If it is a property, it will return the value of that property.

* object["nameOfProperty"] (name of property need to be between quotes)  
-> returns the value of the roperty  
-> must use this notation if the property name has spaces in it

* object.nameOfAVariable  
-> does not work (returns undefined)

* Always when you check for a property of an object and it does not exist, it will return undefined

# For loops with Objects

* Construction for (let nameofvariable in nameOfObject)  
-> will iterate through each property of the object

# [Gist Examples](https://gist.github.com/colevandersWands/69ac68ffd4c8b2da53a8297f2937d74c)