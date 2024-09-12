JavaScript Notes

TOPICS OF JAVASCRIPT

# Let, Const and Var

# Data Types of ECMA Standards

# String to Number Conversion

# Comparison of Datatypes

# Datatypes in JavaScript

# Stack and Heap

# String in JavaScript

# Number and Math in Javascript

# Date and Time

# Array in JavaScript

# Object in JavaScript

# Object de-stracture and JSON Api Intro

# Function and Parameter in JavaScript

# Global and Local Scope in JavaScript

# Scope level and mini hoisting

# THIS and arrow function

# Immediately Invoke Function Expression (IIFE)

# How Javascript executes code+callstack

# Control flow in javascript

# for loop break and continue

# While and doWhile loop

# Higher order Array loops

# Filter Map and Reduce

# DOM introduction in javascript

# All DOM Selectors and HTMLCollection

# Edit and remove Elements in DOM

# Events in JavaScript

# Async JavaScript fundamentals

# Promise in JavaScript

# Object Oriented in JavaScript

# Class Constructor and Static

# Call, Apply and Bind

# Getter Setter and Stack OverFlow

# Lexical Scoping and Closure

==========================================================

# Let, Const and Var

-

# Datatype of ECMA Standards

- There are two types of datatype
  1.  Primitive Datatype
  2.  Non Primitive Datatype or Reference Datatype

1. Primitive Datatype

- These types hold Simple values and are stored directly in the memory location assign to the variable.
- This datatype are 'immutable', their values can not change.
- This primitive type data is copy by value.

Types of Primitive data.

- String
- Number
- Boolean
- Null
- Undefined
- Symbol
- BigInt

Example:

let x = 5;
let y = x; // y is a copy of x

y = 10;
console.log(x); // Output: 5 (x is not affected)
console.log(y); // Output: 10

2. Non Primitive Datatype or Reference Datatype

-
- In this datatype the data store by a reference, here we can change the value original datatype means it is a mutable.

Types of Non-Primitive

- Object
- Array
- Function

let arr1 = [1, 2, 3];
let arr2 = arr1; // arr2 references the same array as arr1

arr2.push(4);
console.log(arr1); // Output: [1, 2, 3, 4] (both arr1 and arr2 are affected)
console.log(arr2); // Output: [1, 2, 3, 4]
