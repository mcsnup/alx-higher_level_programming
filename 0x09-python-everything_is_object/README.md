0x09. Python - Everything is object
Description

What you should learn from this project:

    Why Python programming is awesome (don’t forget to tweet today, with the hashtag #pythoniscool :))
    What is an object
    What is the difference between a class and an object or instance
    What is the difference between immutable object and mutable object
    What is a reference
    What is an assignment
    What is an alias
    How to know if two variables are identical
    How to know if two variables are linked to the same object
    How to display the variable identifier (which is the memory address in the CPython implementation)
    What is mutable and immutable
    What are the built-in mutable types
    What are the built-in immutable types
    How does Python pass variables to functions

0. Who am I?

    What function would you use to print the type of an object?

1. Where are you?

    How do you get the variable identifier (which is the memory address in the CPython implementation)?

2. Right count

    In the following code, do a and b point to the same object? Answer with Yes or No.

3. Right count =

    In the following code, do a and b point to the same object? Answer with Yes or No.

4. Right count =

    In the following code, do a and b point to the same object? Answer with Yes or No.

5. Right count =+

    In the following code, do a and b point to the same object? Answer with Yes or No.

6. Is equal

    What do these 3 lines print?

7. Is the same

    What do these 3 lines print?

8. Is really equal

    What do these 3 lines print?

9. Is really the same

    What do these 3 lines print?

10. And with a list, is it equal

    What do these 3 lines print?

11. And with a list, is it the same

    What do these 3 lines print?

12. And with a list, is it really equal

    What do these 3 lines print?

13. And with a list, is it really the same

    What do these 3 lines print?

14. List append

    What does this script print?

15. List add

    What does this script print?

16. Integer incrementation

    What does this script print?

17. List incrementation

    What does this script print?

18. List assignation

    What does this script print?

19. Copy a list object

    Write a function def copy_list(l): that returns a copy of a list.

20. Tuple or not?

    a = ()

21. Tuple or not?

    a = (1, 2)

22. Tuple or not?

    a = (1)

23. Tuple or not?

    a = (1, )

24. Richard Sim's special #0

    What does this script print?

25. Richard Sim's special #1

    What does this script print?

26. Richard Sim's special #2

    What does this script print?

27. Richard Sim's special #3

    id(a)

139926795932424

a

[1, 2, 3, 4]

a = a + [5]

id(a)
28. Richard Sim's special #4

    a

[1, 2, 3]

id (a)

139926795932424 a += [4]

id(a)
30. #pythonic

    Write a function magic_string() that returns a string “Holberton” n times the number of the iteration (see code):

31. Low memory cost

    Write a class LockedClass with no class or object attribute, that prevents the user from dynamically creating new instance attributes, except if the new instance attribute is called first_name.

32. int 1/3

    julien@ubuntu:/python3$ cat int.py

a = 1

b = 1

julien@ubuntu:/python3$

How many int objects are created by the execution of the first line of the script?

How many int objects are created by the execution of the second line of the script
33. int 2/3

    julien@ubuntu:/python3$ cat int.py

a = 1024

b = 1024

del a

del b

c = 1024

julien@ubuntu:/python3$

How many int objects are created by the execution of the first line of the script?

How many int objects are created by the execution of the second line of the script

After the execution of line 3, is the int object pointed by a deleted? Answer with Yes or No

After the execution of line 4, is the int object pointed by b deleted? Answer with Yes or No

How many int objects are created by the execution of the last line of the script
34. int 3/3

    julien@twix:/tmp/so$ cat int.py

print("I")

print("Love")

print("Python")

julien@ubuntu:/tmp/so$

Before the execution of line 2 (print("Love")), how many int objects have been created and are still in memory?

Why?
35. Clear strings

    guillaume@ubuntu:/python3$ cat string.py

a = "HBTN"

b = "HBTN"

del a

del b

c = "HBTN"

guillaume@ubuntu:/python3$

How many string objects are created by the execution of the first line of the script?

How many string objects are created by the execution of the second line of the script

After the execution of line 3, is the string object pointed by a deleted? Answer with Yes or No

After the execution of line 4, is the string object pointed by b deleted? Answer with Yes or No

How many string objects are created by the execution of the last line of the script
Author

    Takpa Joseph - mcsnup
