# object-helpers-js
A collection of functions helpful for working with 'immutable' objects in Javascript.

## Why? 
Redux-pattern libraries are all the rage right now.  But in a non-immutable language like Javascript, to ensure immutablity of the store, you end up with lots of spread operators to 'simulate' immutability.  This is less than ideal for two reasons

1. It produces verbose code
2. You have to constantly worry about the immutability of your store and whether you did correctly copy the store before modifying

