## Understanding the JavaScript Call Stack

*What is a ‘call’?*

A call is a single function execution that is done one at a time.

*How many ‘calls’ can happen at once?*

As many as requested it is synchronous.

*What does LIFO mean?*

Last in First Out.

*Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.*

function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();

*What causes a Stack Overflow?*

'A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.'

## JavaScript error messages

*What is a ‘reference error’?*
When you attempt to use a variable that is not yet defined.

*What is a ‘syntax error’?*
This error occurs in when your syntax is incorrect and whatever you are trying to do cannot be parsed.

*What is a ‘range error’?*
Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

*What is a ‘type error’?*
When you try to access incompatible types of data! Such as an undefined variable or using numbers with string methods.

*What is a breakpoint?*

The breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.

*What does the word ‘debugger’ do in your code?*

[Back to Home](https://zusolaris.github.io/reading-notes/)
