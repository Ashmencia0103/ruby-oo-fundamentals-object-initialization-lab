Highly Recommended Labs:
Anagram Detector
Email Parser (Optional lab: try to solve without regex, just do some console testing instead of rspec )
Person Lab
Cash Register
Count Sentences
Class Variables and Class Methods Lab (can skip if you understand already)
Advanced Class Methods Lab
OO TicTacToe (Super important for setting up CLI)
My Pets && Banking (if you have issues with these, walk through the has_many lab)
Has Many Through
Inheritance Lab
Modules Lab (Optional lab: just understand the difference between Modules and Classes)
Super Lab
Mass Assignments Lab
Triangle Lab (for fun)
Working with APIs && Remote Data
TicTacToe AI && Music Library CLI (really just go through the Phase 1 Final Projects Module)# Object Initialization Lab

## Objectives

1. Define a class with a custom initialize routine.
2. Set instance variable attributes from initialize.
3. Include a default argument for an initialize argument.

## Overview

You're going to be building a `Person` class that accepts a person's name when a
person is initialized. You're also going to be building a `Dog` class that
accepts a dog's name and breed on initialization. If no value for the dog's
breed is provided, it should default to `"Mutt"`

## Instructions

Open this lab by clicking the "Fork" button, cloning, and running the tests with `learn test`.

#### 1. `Person#initialize` with a Name

Define a `Person` class in `lib/person.rb` that provides an `#initialize` method
that accepts an argument for the person's name. That argument should be stored
within a `@name` instance variable.

#### 2. `Dog#initialize` with Name and Breed defaulting to "Mutt"

Define a `Dog` class in `lib/dog.rb` that provides an `#initialize` method that
accepts an argument for the dog's name. That argument should be stored within a
`@name` instance variable.

Additionally, `Dog#initialize` should accept a second optional argument for the
dog's breed stored in an instance variable `@breed`. When none is provided, it
should default to "Mutt".

Submit your solution with `learn submit`.
