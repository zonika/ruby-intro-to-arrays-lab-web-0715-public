---
tags: arrays, micro, introduction
languages: ruby
resources: 1
---
# Introduction To Arrays

## Objectives

1. Become comfortable with instantiating arrays in different ways
2. Become comfortable using indexes to return values from an array
3. Become comfortable using ruby methods to traverse an array
4. Become comfortable using the official documentation of the Ruby Language

## Instructions

Open `spec/intro_to_arrays_spec.rb` and go through each test sequentially. Be sure to read each test very carefully.

You will be filling out your answers in the spec.  For example:

```ruby
 expect(__).to be_a(Array)
 ```

 In the above example, you will place your programmatic solution in the space with the underscores like so:

 `expect(programmatic_solution).to be_a(Array)`

What is a programmatic solution? Good Question!
Let's say you're asked to create a string amanda and store it in a variable called name. We expect a solution that looks something like this:

```ruby
name = "amanda"
```

And let's say we had a test that checks that the value of the variable name was set to a string amanda.  We expect a completed test that looks something like this:

```ruby
expect(name).to eq("amanda")
```

What we don't expect is a completed test that looks something like this:

```ruby
expect("amanda").to eq("amanda")
```

Because even though the test will pass, it is not the right programmatic solution. Can you guess why?

## Resources

[Ruby Docs](http://www.ruby-doc.org/core-2.1.4/Array.html)
