---
layout: post
title:      "Var(iable) hoisting and scope "
date:       2018-02-05 16:42:37 +0000
permalink:  var_iable_hoisting_and_scope
---


The keyword Var has been there since the genesis of Javascript. 

And because Javascript wasn’t initially created to be a “serious” language, it was made with many pesky mistakes and many still exist with ‘var’(iable). 

One pesky thing about 'Var' is that when using the keyword var, that variable gets a function scope. Which means that when you define a function and the variable, that variable is available throughout the function. Breaking it down even further--- 'var'  only respects function boundaries.  

Whenever you define a variable within the body of the function, the value is available from that point to the end of the function but before the variable, it gives you the variable, yet undefined, without value. So how do you get around this if you MUST use var? You simply hoist the variable manually, meaning, define the variable first, then assign a value to it.

To resolve this issues with ‘var’ , Javascript introduced two keywords: ‘let’ and ‘const’.
‘let’ is similar to ‘var’ , yet it has a block scope, rather than a function scope and it doesn’t do Hoisting. 
Const actually means that once the variable is assigned it cannot be assigned again and an attempt to do so will throw an error.
