---
layout: post
title:      "Javascript Objects and Object prototypes"
date:       2018-02-05 11:43:17 -0500
permalink:  javascript_objects_and_object_prototypes
---


While flying through the Javascript lessons, I seemed to have slightly forgotten the basics of Javascript languages. Therefore, I went back and made a little refresher note on the basics and am sharing with you now! 

Sooo, let's get down to the very basic- what is a Javascript Object? Well, it's a collection of values, which can be of many different types(string, array, function, date). 

Within Javascript, you can define these properties by simply assigning it a value. You can create an object through different ways- you can use the keyword 'new', use object literal notation, or object.create. 

1) keyword 'new'
const obj1 = new Object();

2) literal notation (most common way) 
const obj2 = {}; 

3) Object.create
const obj3 = Object.create(null); 


**Another Importance concept...**
Another important concept to grasp while learning Javascript is Object prototypes.

Every constructor function has a property called prototype. You can add properties and methods to it. A benefit of using prototype object to add functions is that no matter how many objects you create, functions are loaded only once into memory. 


**Extra gold nugget **

Every object in Javascript is created from a master object called, **’Object’**. This master constructor is in a global scope and can be used directly.




