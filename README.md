LINQER
======

An npm package to implement a .NET LINQ like queries for javascript

install
=======

With [npm](https://npmjs.org) do:

```
npm install linqer
```

license
=======

ISC

DOCS
====
Please get full details about the functinality here [DOCUMENTAION](https://github.com/crouch74/Linqer/blob/master/DOCUMENTATION.md)

contribution
============

Please read the [TODOs](#todo) and choose something to work on

Please add your test cases ,, make sure that all unit tests will pass

Run the command

```
grunt test
```

to run all test cases and create a units.html file with the result from karma/jasmine

run

```
grunt
```

to run all tests and generate a LINQ.min.js file if it passed

after all of that ,, please submit your PR and it will be reviewed and merged

Thanks for being interested in enhancing Linqer

TODO
====

-	Implement functions to support <ES5.1 ,, implement :
	-	Array.prototype.map
	-	Array.prototype.reduce
	-	Array.prototype.some
	-	Array.prototype.every
	-	Array.prototype.filter
-	Add more test cases
-	Hide private methods of evaluating queries and the list getter/setter
-	Add takeWhile,skipWhile functionality
-	Add thenBy functionality
