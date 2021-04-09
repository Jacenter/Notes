# Notes
## S.O.L.I.D. Principles
---
### S = Single Responsibility
- Single Responsiblity is the concept that a class should only have 1 responsibility.
- A class only has 1 job and should only do that 1 job.
- A `'book` class is responsible for example for holding ``'author' , 'title' , 'numberOfPages`` and other things that would make sense for the book class to be reposnsible for.
- the `'book'` class should NOT be responsible for printing the books that responsibility should fall to another class.
- This ***Single Responsibility*** principle is applied to methods as a good example a method has one job and should only do that one job.
- If my ``'public int addTwoNumbers(int x, int y)`` subtracts two numbers instead then it isn't doing its job and violates the ***Single Responsibility*** principle.
---
### O = Open for Extension, Closed for Modification
- Classes should be opened for extension and closed for modification.
- the exception of this principle is when fixing bugs in the existing code.
- If I have a ``Guitar`` class 
    ``private String make;
    ``private String model;
    ``private int volume
 - and wanted to make a guitarWithFlamesPattern
 - do this
 ``public class SuperCoolGuitarWithFlames extends Guitar {
    ```private String flameColor;``
- instead of editing the existing code
