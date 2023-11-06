# guessing_game 








[Rust Standard Library Documentation](https://doc.rust-lang.org/std/prelude/index.html)


By default, Rust has a set of items defined in the standard library that it brings intot he scope of every program. This set is called the prelude, and you can see everything in it in the stnadard library documentation.


If a type you want to use isn't in the prelude, you have to bring that type into scope explicitly with a use statment. Using the std::io library gives you witha number of useful features, including the ability to accept user input.


In Rust, variables are immutable by default, meaning once we give the variable a value, the value won’t change.


To make a variable mutable, we add mut before the variable name:

calling String::new, a function that returns a new instance of a String. String is a string type provided by the standard library that is a growable, UTF-8 encoded bit of text.


The :: syntax in the ::new line indicates that new is an associated function of the String type. An associated function is a function that’s implemented on a type, in this case String. This new function creates a new, empty string. You’ll find a new function on many types because it’s a common name for a function that makes a new value of some kind.
