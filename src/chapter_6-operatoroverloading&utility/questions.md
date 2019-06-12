* Create a struct name `Set` that contains a `Vector` of chars and overload the `minus`
operator so that when 2 structs subtract it removes the chars of 2nd from 1st one.

* Create a struct named `ComplexNumber` that has 2 variables `re` & `im` and overload `minus`
and `plus` operator to add and subtract complex number.

* Overload the `!` operator to conjugate the complex number `!ComplexNumber` and `==` and `!=` for comparison.

* Create a struct named `Class` that contains the class size, section and grade. Overload
the `>`, `<`, `>=`, `<=`, `==` operators to compare class sizes of various Classes.

* Rust does not allow addition of `integer` and `float`. Overload `+` so that this is possible.

* Implement custom `Drop` for a struct `Hero` that contains a field `name` of type string.
The `drop` should print "Oh no !!! Our hero {name} is defeated". Run the program with just 
declaring a variable of type `Hero`.

* Create the struct named `World` that contains the previous named struct `Hero`, define `drop`
for it so that it prints "The world ends here !!!". Observe the order in which `World` and `Hero` 
contained by it are dropped.

* Create a struct named `Table` that has a generic field `legs_info` of type `T`. Create a function (not a method)
 named `show` that accepts function parameters `&Table<Display>` and displays `legs_info`. Create 2 variables one
 that contains `T` of type `String: "Work in progress..."` and `usize: 4`.\
 `hint:` use `?Sized`.
 
* Implement `From` trait for struct `ComplexNumber` given a tuple of type `(isize, isize)`. Form it using `from` 
and `into` respectively.

* Create a function that accepts either `ComplexNumber` or `(isize, isize)` to return the `mod` of ComplexNumber.
 