# Introduction To Arrays Lab

## Objectives
1. Become comfortable with instantiating arrays in different ways
2. Become comfortable using indexes to return values from an array
3. Become comfortable using ruby methods to traverse an array
4. Become comfortable using the official documentation of the Ruby Language

## Array Review
**What is an array?**

Two very common data structures that you will use as a Ruby programmer are
arrays and hashes. Arrays are the focus of this lesson.

In previous lessons, you learnt about variables. An example of a variable:
```ruby
name = "Tim"
```
Variables can only store one item at a time and thus are not useful when we need to store a large amount of data (that is store information about multiple items).

Arrays, on the other hand, can store multiple items. These items are called elements of the array. Arrays can hold objects of any [data type](http://zetcode.com/lang/rubytutorial/datatypes/). 

**Creating Arrays**

Arrays can be created in various ways.[Head over to the documentation on Arrays Ruby Docs to learn more about how arrays are created](http://www.ruby-doc.org/core-2.1.3/Array.html). Make sure you have your terminal open so that you can try out the different ways arrays are created in Ruby.

An array is denoted by square brackets `[ ]`.  Inside the brackets you can
 create a list of elements separated by commas.
 
```ruby
list_of_names = ['Arel', 'Steven', 'Mitch', 'Tristan', 'Ian']
```

**Indexing**

Each element can be referred to by an index. Arrays are zero based, this means that index of the first element is zero. The elements of an array can be accessed by referencing the index of the element in question in conjunction with the sqaure bracket `[]` method. This is how we access the first and last elements of the array above called `list_of_names`:

Accessing Array Elements|
--- | ---
list_ of_names[0] = 'Arel' | 'Arel'
list_ of_names[4] = 'Ian' | 'Ian'


## Instructions

1. Fork and clone this repository. Then run `bundle install` in your command line to install the rspec and pry gems. 
2. Run the test suite with the `learn` command in your command line. 
3. The first set of tests will require you to build methods that instantiate and return arrays. Read the spec file to learn what is required of you and get the tests passing. 
4. The second set of tests requires you to use indexing to access certain array elements. Read the spec file to learn what is required of you and get the tests passing. 
5. The third and final set of tests requires you to use array methods to access array elements and preform other operations on arrays. Read the spec file to learn what is required of you and get the tests passing. 



## Resources

[Ruby Docs](http://www.ruby-doc.org/core-2.1.4/Array.html)
