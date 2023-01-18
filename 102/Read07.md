
# Read: 07 - Programming with JavaScript


## Control flow 

*Control flow* is the order your processor reads and executes the statements you give it. 


Bad control flow - if you are to read it, can you understand what each of the statements do? Is it written 'well?'

## Functions

A function is some **code** that preforms a particular task. 

An algorithm is more broad term for a set of instructions, which don't have to be related to programming. 

**Expression**

---- Come back to this 

Anything that boils down to value?

**To declare a function:**

```
function myFunction(arguments) {
    return number*number;
}

```
If you give it an primitive (int,boolean,float,strings) it's passed by Value (It's value isn't changed)

array, ect are passed by reference. 

If you pass an object, it is passed by reference and can be changed, even if it has a primitive inside it. 

`object.property` = if you do this, even though it's an object, if the property is a primitive it will be passed by value. 

When the program reaches a `return` statement, the function stops executing. Functions will often have a return value. This is the result you may see in the console. 

Functions can be reused. `myFunction()` refers to the functions result. Variables declared inside the function are local to it, and cannot be used globally. 

## Operators

Types of operators: 

```
++i prefix operator
i* i infix operator
i++ postfix operator
```
some arthmetic:

```
** - Exponentiation
++ - Increment
-- - Decrement
```
some assignment operators
```
+= = adds value to variable
```
you can do the usual `+,*,%,**`with`=` in the same syntax. 

you can concatenate (combine) strings with `+`. `+=` also works on strings. 

---

**Comparison Operators**

== equal to
!= not equal
!== super not equal (in type either)

    ? - **No idea, look up**

**Logical Operators**
```
&& = AND
|| = OR
! = NOT
```
I remember doing truth tables! 

    typeof = what type of varible is it?

### Things I wanna learn more about 

Bitwise

