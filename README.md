# PB - Classes - Basics

This task is all about practicing the very basic concepts of classes. Let's practice using the `Date` class that is built into JavaScript!

Add your answers directly into this file.

```js
    const now = new Date();
    const test = new Date();
```

1. In the code above, what is the `now` variable? 
    - an instance that contains the data and behavior described by Date class. 

2. What is the type of the `now` variable? 
    - type Object 

3. In the code above, what is the `Date`?
    - `Date` is a class

4. What is the type of `Date`? 
    - type Object 

5. What do you get when you do `console.log(now)`?
    - we get the information stored in Date --> Date { ... }
    }

6. What do you get when you do `console.log(Date)`?
    - --> [class Date]

 
7. What do you get when you do `console.log(new Date())`?
    - --> Date { ... }

8. Is `now` truthy? 
    - no?!
 
9. What do you get when you do `console.log(now === test)`? Why?
    - False 

10. What do you get when you do `console.log(now === Date)`?
    - False 
 
11. What do you get when you do `console.log(now === new Date())`?
    - false 

12. What do you get when you do `console.log(new Date() === new Date())`? Why?
    - false