1. values added: 20
2. final result: 20
3. We should not use var to declare variables in programs because in the past it led to naming conflicts and scoping issues.
4. values added: 20
5. It gives error because result is declared using let, which has block scope, i.e it is only accessible in the block it is declared in. Thus we get ReferenceError.
6. We see error since result was declared using const. const variables cannot be reassigned so trying to assign new value to it in line 7 results in the error.
7. It gives no output as this line will not be executed because of the previous error caused by line 7. 
