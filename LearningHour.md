HiQ Leap CI Training
====================

Requirements
------------

* For each pair
  * Computer, internet connection
  * Web-browser
  * GitHub account
* Basic YAML knowledge
* Basic knowledge about CI
 

Agenda
------

* 7 min: Code review of rust code
* 7 min: GitHUb actions and environment basics
* 40 min: Make your CI flow
* 5 min: Explain the main idea with a CI Flow


Connect
-------

A quick code review of [lib.rs](src/lib.rs)

Open the lib.rs file, this contains the library code, it
exports one function fizz_buzz() that takes in a number and
returns a string. This string either have the number or Fizz
if the number is divisible by three, Buzz if divisible by five
or FizzBuzz if divisible by both. In short, it implements the
[FizzBuzz kata](https://www.sammancoaching.org/kata_descriptions/fizzbuzz.html).  

The end of the file have five tests cases for the code. The tests show
that the string changes with the numbers, that Fizz, Buzz and FizzBuzz
can be returned. But only on one sample point.

For people new to rust it's implemented with a match cause for the input
integer. It works like if the if part e.g. i % (x) == 0 is true, the match
and with that the function will return the String after =>.

Concepts
--------

* Introduce GitHub Actions
* Show how to create repo from template
* Set up codespaces for github
* Into to GitHub actions
* 


Concrete Practice
-----------------

* Clone and set up environment from [GitHub](https://github.com/balp/hiq-leap-fizzbuzz-template)
* Create a simple CI flow:
  * What steps are needed:
    * build?
      * release?
      * debug?
    * package?
      * docs?
      * cargo.io
    * run tests?
    * code analysis?
      * clippy?
      * code format?
      * 

Conclusions
-----------

Explain: What is the main idea behind a CI flow?

