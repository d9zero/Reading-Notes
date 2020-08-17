## Table of Contents

- [Day 1](class-01.md)
- [Day 2](class-02.md)
- [Day 3](class-03.md)
- [Day 4](class-04.md)
- [Day 5](class-05.md)
- [Day 6](class-06.md)
- [Day 7](class-07.md)
- [Day 8](class-08.md)
- [Day 9](class-09.md)
- [Day 10](class-10.md)
- [TBD]
- [TBD]
- [TBD]
- [TBD]
- [TBD]
- [TBD]



## Error Handling & Debugging


Order of Execution:

  To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete unitl another statement or function has been executed.



Execution Contexts:

  The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new exectuion context. They correspond to variable scope.


The Stack:

  The JavaScript interpreter processes one line of code at a time. When a statenebt beeds data from another function, it stacks (or piles) the new function on top the current task.



Execution Context & Hoisting:
