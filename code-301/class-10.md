# Class 10 Reading Notes

## Understanding the JavaScript Call Stack

1) A call in a function invocation.

2)only one function maybe called at a time, however they are called in synchronous order.

3)LIFO means Last In First Out 

4)function firstFunction(){
  console.log('Hello')
}
function secondFunction(){
  firstFunction();
  console.log('Goodbye')
}
secondFunction();

5)Stack Overflow is when a function is in a continuous loop and doesnt have an end, so the browser can only call so many times before it crash's.

## JavaScript error messages

1)A reference error is when you try to use a variable that hasnt been declared yet

2)A syntax error is when something cannot be parsed in terms of syntax

3)range error occurs when you try to manipulate an object that has a length with an invalid range.

4)a type error occurs when you try to access a property with a undefined type or variable.

5)A breakpoint is a starting or stopping point when you are debugging your code.

6)Debugger allows a break point in your code when you are trying to debug your code
