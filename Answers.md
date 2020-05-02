1. Describe the biggest difference between `.forEach` & `.map`.
    -- The ‘forEach’ method doesn’t return anything undefined because it simply calls a provided function in an element of the given array.

    -- Meanwhile, ‘map’ method also calls the provided function in an element of the array but it utilizes a return value and returns a new Array of the same size.

2. What is the difference between a function and a method?
    -- Methods and functions are basically the same except that ‘function’ is a group of codes that can be called anywhere in the program, eliminating writing the same codes repeatedly.  

    -- Meanwhile ‘method is a function which is a property of an object that we can simply describe an object using ‘this’ keyword.


3. What is closure?
    -- Closure is one feature in Javascript giving the inside function the ability to access the outside function of a given variable.

4. Describe the four rules of the 'this' keyword.
    -- Four Rules of the 'this' keywords:
        - 1. Window/Global Object Binding which means in a non-strict mode, the ‘this’ keyword will default to the global object referring to the whole scope of the window or console object.
        - 2. Implicit Binding means that the ‘this’ keyword will apply for the majority of the code and apply them when calling a method on an object and ‘this’ keyword is preceded with a dot call.
        - 3. New Binding means that the ‘this’ keyword is used when a function is invoked as a constructor function by using the ‘new’ keyword and the ‘this’ keyword points to a new object created.
        - 4. Explicit Binding means setting the ‘this’ keyword to a certain value using ‘call’, ‘apply’, or ‘bind’ methods which can be used to invoke a function and explicitly define an object.

5. Why do we need super() in an extended class?
    -- The ‘super’ keyword is used to call or access the function of the parent properties.