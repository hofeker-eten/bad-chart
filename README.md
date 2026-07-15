# py-course
Lecture notes for a first-semester Python class.

Goals
1. Write Python that prepares you for machine learning work
2. Practise object-oriented design through small programs
3. Cover the exam syllabus for the analytics certification
4. Drill coding-test problems

## Hooking the IDE up to a remote repository
File menu -> version control -> project -> github -> pick the repository -> pick the target directory
-> hit **clone**

## Values and their types
Kinds of value
- whole numbers : int
 - fractional numbers : float
- text : str
 - truth values : bool
## Lists
One name holding an ordered bunch of values

- indexing and slicing

- arithmetic on lists — concatenation, repetition, append, insert, remove

## Branching
- if, else, elif

## Loops
- for
- while

## Exercise 1: estimating pi
Compute the constant and plot the convergence

![img.png](img%2Fimg.png)
```
series = []

pi=1

for n in range(1,1000):
    pi=pi*((2 * n + 1) ** 2 - 1) / (2*n + 1) ** 2
```