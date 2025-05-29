# Week 2 Assessment

## Section 1: Multiple Choice Questions


1. **What is the output of `list(map(lambda x: x*2, [1,2,3]))`?**

   A. [2,4,6]

   B. [1,2,3]

   C. [1,4,9]

   D. Error

   ANSWER (A)

2. **Which keyword is used to create a generator function?**

   A. gen

   B. yield

   C. return

   D. def

    ANSWER (B)


3. **What will be the output of: `def func(x=1): return x + 1; print(func())`?** 

   A. 1

   B. 2

   C. None

   D. Error

    ANSWER (B)


4. **Which function is used to reduce a list to a single value?**

   A. filter()

   B. map()

   C. reduce()

   D. zip()

    ANSWER (A)


5. **Which is NOT a Python built-in data type?**

   A. list

   B. tuple

   C. array

   D. set

    ANSWER (C)


6. **What is the result of `filter(lambda x: x%2==0, [1,2,3,4])`?**

   A. [1,3]

   B. [2,4]

   C. [1,2,3,4]

   D. [2]

    ANSWER (B)


7. **What will be printed: `a = [1,2,3]; b = iter(a); print(next(b))`?** 

   A. 1

   B. 2

   C. 3

   D. Error

    ANSWER (A)


8. **Which function combines two lists into tuples?**

   A. map()

   B. zip()

   C. filter()

   D. enumerate()

    ANSWER (B)


9. **What is the result of `sum(map(len, ['ab', 'cde']))`?**

   A. 3

   B. 5

   C. 6

   D. Error

    ANSWER (B)
  

10. **Which of the following is a decorator syntax in Python?**

    A. #decorator

    B. @decorator

    C. *decorator

    D. &decorator

    ANSWER (B)
  

11. **What happens if a function decorated by a decorator does not return a value?**

    A. Returns None

    B. Raises an error

    C. The original function runs

    D. Skips execution

    ANSWER (A)
  

12. **What is the output of `(lambda x: x**2)(3)`?**

    A. 6

    B. 9

    C. 3

    D. Error

    ANSWER (B)


13. **What is the output of `list(enumerate(['a','b']))`?**

     A. [(0, 'a'), (1, 'b')]

     B. [('a',0), ('b',1)]

     C. ['a', 'b']

     D. Error

    ANSWER (A)
   

14. **Which of these statements is True about recursion?**

    A. Recursion always terminates

    B. Recursion can replace loops

    C. Recursion cannot be used in Python

    D. Recursion requires no base case

     ANSWER (B)
   

15. **Which of these returns an iterator object?**

    A. list()

    B. iter()

    C. tuple()

    D. dict()

     ANSWER (B)
   

16. **What will be the output of this code:**

```bash

def foo():
    yield 1
    return 2
x = list(foo())
print(x)

```

    A. [1,2]

    B. [1]

    C. [2]

    D. Error

     ANSWER (B)
   

17. **Which of the following is NOT True for lambda functions?**

    A. They can have multiple expressions

    B. They can be assigned to a variable

    C. They return a function object

    D. They can be used as arguments

    ANSWER (A)


18. **What is the output of this code:

```bash
a = [1,2,3]
b = map(lambda x: x+1, a)
print(list(b))
print(list(b))

```
    A. [2,3,4] [2,3,4]

    B. [2,3,4] []

    C. [] []

    D. Error

    ANSWER (B)


19. **Which of these is a side effect of using recursion?**

    A. Increased performance

    B. Reduced stack depth

    C. Stack overflow risk

    D. Memory leak

    ANSWER (C)


20. **Which of the following about decorators is correct?**

    A. Decorators must always return the original function

    B. Decorators cannot modify arguments

    C. Decorators are applied at runtime

    D. Decorators are applied at function definition

    ANSWER (D)
