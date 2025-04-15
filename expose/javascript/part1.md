values added: 20
final result: 20
We should not use var to declare variables in programs because in the past it led to naming conflicts and scoping issues.
values added: 20
It gives error because result is declared using let, which has block scope, i.e it is only accessible in the block it is declared in. Thus we get ReferenceError.
We see error since result was declared using const. const variables cannot be reassigned so trying to assign new value to it in line 7 results in the error.
It gives no output as this line will not be executed because of the previous error caused by line 7. 
