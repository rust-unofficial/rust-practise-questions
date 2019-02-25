# Chapter 5 - Traits & Generics

* Derive a debug trait to print info about your struct that contains `name`, `c1ass` and `roll`.

* Create a generic function to get min of 2 values.\
`hint:` You might need to use `Ord` trait bound.

* Implement custom `Drop` trait for a struct name `Student` that contains your `name`, `age` and `roll number`. It
should return `Roll number <roll number> has name <name> with age <age> and is a <junior/senior>`. Being Junior or Senior depends
on age (18 or above).

* Implement a custom `Debug` message for the above Struct.

* Implement custom `Iterator` trait for a struct named `GeometricSeries` that has 
3 fields `first_number`, `current_number` and `ratio` of type `i32`. The iterator should return the
next 11 numbers in geometric progression.\
`hint:` Use `.take(11)` to get the next 11 in `for` loop.

* Implement the same as above for a `FibonacciSeries` struct.

* Implement a generic function name `sum` with additional parameter of `index: usize`
 that can take either `GeometricSeries` or `FibonacciSeries`  and returns the sum upto the given index.\
`hint:` use `T: Iterator<Item = i32>` where `T` is generic  
 
