### Hoisting
---
1. Hoisting is a Javascript mechanism where variables and function declarations are moved to the top of their scope before code Execution.
2. **Only Declarations are Hoisted but not Initializations.**

#### **Importance of Hoisting**:
1. It explains unexpected behaviour in variable usage.
2. Helps Understand **_Temporal Dead Zone_** with ```let``` & ```const``` keywords.
3. Enables function declarations to be used before their definition in code.
4. Improves Debugging Skills and Code Predictability.

#### **Example**:

```javascript
console.log(a); // undefined
/* (able to access variable as in Javascript variables declared with var keyword are hoisted)*/
var a = 5;


hoistedFunction(); // I am Hoisted
/*
Functions are 
*/
function hoistedFunction(){
    console.info(`I am Hoisted`);
}
```
