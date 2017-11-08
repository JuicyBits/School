- Diagrams Covered in class:
    - Use Case
    - Class
    - Sequence
    - ER

#### Rational Unified Process (RUP)
> iterative software development process framework

- Similar to SCRUM

#### Finite State Machine
**State** - A collection of variables with set values
```
                           *Event*
     ------>(State A) -----> (State B)
                    |      *Action*     | *Event*
                    |                     -------> (State C) <-
                    |                       *Action*               |
                    |                                                |
                    |                   *Event*                    |
                    ---------------------------------
                                        *Action*
 ```
- Initial State variables can have no (NULL) conditions, all other states must have conditions
- Actions occur during state shift
- Assumption: Time does not transpire during state transitions
