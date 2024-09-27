# Calculator

### In this project, a calculator with GUI was programmed in Pascal and Assembly.

#### Why assembly?
- All mathematical operations are done in the FPU due to its increased efficiency, specially regarding trigonometric functions.

#### Implementation overview
- Once the expression is entered, it is passed to a tokenization algorithm built based on deterministic finite automata;
- The tokens are then fed into a postfix notation algorithm which uses stack and queue data structures (implemented in Pascal); 
- Using the stored tokens (now in postfix notation), calls are made to the functions that use the FPU for performing the computations.