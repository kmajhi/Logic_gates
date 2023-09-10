### Example 1: Truth Table

Let's create a truth table for a simple 2-input AND gate.

| Input A | Input B | Output (A AND B) |
| ------- | ------- | --------------- |
|   0     |   0     |       0         |
|   0     |   1     |       0         |
|   1     |   0     |       0         |
|   1     |   1     |       1         |

In this truth table, we have two input signals (A and B) and one output signal (A AND B). It shows all possible input combinations and the corresponding output based on the AND gate logic.

### Example 2: Karnaugh Map (K-Map)

Let's create a 2-variable Karnaugh Map for a Boolean function F(A, B) = A'B + AB'.

|   | 00 | 01 | 11 | 10 |
|---|---|---|---|---|
| 0 |  0 |  1 |  1 |  0 |
| 1 |  1 |  0 |  0 |  1 |

In this 2-variable K-Map, the rows represent the input combinations (00, 01, 11, 10), and the columns represent the opposite input combinations (00, 01, 11, 10). The entries in the K-Map correspond to the output of the Boolean function for each input combination.

For example, the cell at row 0 and column 01 (A=0, B=1) has a value of 1, indicating that F(0,1) = 1. Similarly, the cell at row 1 and column 10 (A=1, B=0) has a value of 1, indicating that F(1,0) = 1.

### Example 3: State Transition Diagram

Let's create a simple state transition diagram for a 2-bit binary counter.

```
State A, B | Next State A, B
-----------|-----------------
    00    |       01
    01    |       10
    10    |       11
    11    |       00
```

In this state transition diagram, we have a 2-bit binary counter with states represented by A and B. The "Next State A, B" column indicates the state transitions based on the current state. For example, when the counter is in state 00, it transitions to state 01, and so on.

These examples demonstrate different types of key maps used in logic design and digital systems to represent input-output relationships, simplify logic expressions, and describe state transitions.
