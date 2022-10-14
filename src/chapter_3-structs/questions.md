# Chapter 3 - Structs

* Write a program to store and print the roll no., name , age and marks of a student using structures.

* Write a program to compare two dates entered by user. Make a structure named Date to store the elements day, month and
  year to store the dates. If the dates are equal, display "Dates are equal" otherwise display "Dates are not equal".

* Write a program to add, subtract and multiply two complex numbers using structures to function.

* Create a structure named Date having day, month and year as its elements. Store the current date in the structure. Now
  add 45 days to the current date and display the final date.

* Replicate constructor function with name `new()` returning type `Self`.

* Let us work on the menu of a library. Create a structure containing book information like accession number, name of
  author, book title and flag to know whether book is issued or not.
  Create a menu in which the following can be done.\
  1 - Display book information\
  2 - Add a new book\
  3 - Display all the books in the library of a particular author\
  4 - Display the number of books of a particular title\
  5 - Display the total number of books in the library\
  6 - Issue a book\
  (If we issue a book, then its number gets decreased by 1 and if we add a book, its number gets increased by 1)

* Create a generic struct for addition of numbers (they can be `integer` or `float`).

* Create a struct with `Copy, Clone, Debug, PartialEq` traits\
  `hint:` Use `#[derive]`

* Create an immutable struct with a mutable member.\
  `hint:` Use `Cell`, property known as interior mutability.

* Try making the above program with `RefCell` so that the struct stores details about a bank(balance, customer count,
  location, etc) with only customer count being mutable.