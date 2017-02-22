#learning and notes on the Reactive Programming paradigm

##Reactive Programming

+----------------------------------------------------+---------------------------------------------------------+
| **Reactive Programming**                           | **Traditional Programming**                             |
+----------------------------------------------------+---------------------------------------------------------+
| The level of abstraction of your code is high,     | Lower level of abstraction, because you also have to    |
| allowing you to focus on core business rules.      | deal with the technology's intricacies.                 |
+----------------------------------------------------+---------------------------------------------------------+
| Usually, lower development times, since you're     | Usually, higher development times, because you also     |
| only focusing on the problem to solve, which       | have to workaround the limitations of the chosen        |
| translates into fewer lines of code.               | technology, which in turn translates into more lines of |
|                                                    | code needed.                                            |
+----------------------------------------------------+---------------------------------------------------------+
| Writes code describing the *what to do* instead    | Writes code describing *how to do it* instead of *what  |
| of the *how to do it*, This simplifies the code    | to do*, This adds extra complexity to the code.         |
| and makes maintenance much easier.                 |                                                         |
+----------------------------------------------------+---------------------------------------------------------+
| Values that depend on others are updated           | Values do not depend on each other dynamically.         |
| automatically without the need to use any logic.   | In the following line, the value of A is not changed    |
| In the following line, the value of A gets updated | unless manually updated by the developer.               |
| whenever B or C changes.                           |                                                         |
| A: = B + C                                         | A = B + C                                               |
+----------------------------------------------------+---------------------------------------------------------+

