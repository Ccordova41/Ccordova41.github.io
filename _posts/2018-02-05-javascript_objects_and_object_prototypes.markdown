---
layout: post
title:      "Javascript Objects and Object prototypes"
date:       2018-02-05 16:43:16 +0000
permalink:  javascript_objects_and_object_prototypes
---


Every object in javascript is created from a master object called, ’Object’. This master constructor is in a global scope and can be used directly.

Every constructor function has a property called prototype. You can add properties and methods to it. A benefit of using prototype object to add functions is that no matter how many objects you create, functions are loaded only once into memory. 

