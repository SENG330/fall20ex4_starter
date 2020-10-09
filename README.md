Please read thru the [overall exercises overview](https://github.com/SENG330/course/blob/master/exercises/Exercises.md).

## Exercise 4
1. Building on the work from Ex2, correct the code based on the TA feedback. 
2. Expand your code to show how we can:
    1. search through a
 list of whale observations, and 
    2. sort that list. 
3. Implement two different strategies for searching and two different strategies for sorting. Cf. page 54. 
4. Create a comparator (page 48) for whales. In your ADR document why the approach you chose is preferable over the
 other 2 approaches discussed in the book.
 3. Draw a Class diagram to show the structure of your solution. 

### Notes:
- the search/sort happen in memory. In practice this might be dangerous, if we had a huge number of objects and
 limited RAM.
 - Do NOT write your own search/sort algorithms. There are plenty in the Java standard library. Except for undergrad
  (225/226/320 etc), it would be a rare thing for a programmer to improve on the JDK implementations.
 
### Learning Objectives
- Fix code following the TA's code review.
- Learn to draw a basic class diagram.
- Use Iterator, strategy patterns in context.
- Use a Function object

### Deliverables

* An ADR capturing the class diagram and explaining the rationale. 
* Source code implementing the class diagram. Your source code must contain JUnit tests that show: 
    - a successful execution of the iterator and 
    - strategy patterns.
Capture your important decisions in the ADR template.

## Due
- We will mark the last commit made before **September 25 at 11:59pm**. If that last commit was a mess, let us know. Make sure your code compiles!
- By midnight September 27, submit your team peer review form (link to follow). We will discuss the peer rating form in class.