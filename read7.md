# Read: 07 - Programming with JavaScript

## Operators:
There are many types of Operators that we can use in JS.
**Like:**

**1- Comparison Operators**

**<** : greater than.

**>** : less than.

**=** : equals.

**2- Logical Operators**

*And* / **&&** :  used to combain two or more conditions (and all  of them must be true to get true as a result any false value will effect the final result).

*or* / **||** :  unlike  &&  in order to get false in the final result all the valuse must be false , otherwise we will get true.

*not* / **!** : the opposite of the current value **ex:**
!true =false, !false=true.





## Loops:

**for loop**:

** syntax**:

number=5

 for (var i = 1; i < number ; i++) {
    **loop body**
 }

- its better to be used when the we know the loop should be excute for (n) times (specific times).





**while loop**:

** syntax**:

while(CONDITION)
{

**LOOP BODY**

  break;

}

 - its better to be used when we deal with a user input.




## Functions:
Functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.

**Functions in JS**:

** 1-**: keyword ->  function

funtion  F.name( ){

  function block 
  
  return ;

}


** 2-**:  called function expression

const getRectArea = function(width, height) {
  return width * height;
};

console.log(getRectArea(3, 4));


