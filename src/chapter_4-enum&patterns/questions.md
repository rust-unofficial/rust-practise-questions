# Chapter 4 - Enum & Patterns

* Create an enum that contains HTTP 4xx Client Errors.\
  `i.e.` `Not Found` Should have value `404` associated with it.

* Write an enum to store information of whether a person is a child or adult based on his/her age.

* Create a calculator with the help of an enum named `Operation` that as values such as `Add, Sub, Div, Multi`.\
  `hint:` For input like `2+5*10` it should first evaluate `5*10` and then add 2 to it.

* Use pattern matching to associate a enum of `Grade` type with a student based on his/her marks.

* Create an enum named `Json` that can work with arbitrary JSON data.

* Print what kind of input the user has given(numbers, letters, symbols) using pattern matching.\
  `hint:` Try using range for it e.g. `0 ... 100` or `'a' ... 'k'`

* Use pattern matching to find that whether a point lies on X-Axis, Y-Axis or on which quadrant.

* Create a struct that holds info about a gun(gun type, recoil time, magazine size, extra) where `gun type` and
  `extra` are enums and `extra` contains silencer, scope, extended mags nad `None`.\
  Based on user input change the value of extra (may cause change in recoil time and magazine size).

* Create a Binary tree and have a method `add` on it to add elements to it and `min` and `max` to find the minimum and
  maximum element in it.

* Create a `Regex` to extract dates from this string `It was on 2019-03-14, almost after a year from 2018-02-11` and
  store in a
  Struct with fields of `day`, `month` and `year`.\
  `hint:` Use `Regex` crate 
