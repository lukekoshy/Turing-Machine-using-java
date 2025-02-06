
# Turing Machine

## Description
The Turing Machine is a theoretical computing device that was introduced by Alan Turing in 1936. It is a simple yet powerful model that can simulate any algorithmic computation. The machine consists of an infinite tape divided into cells, a read/write head that can move along the tape, and a set of rules that determine its behavior.

## Purpose
The purpose of this project is to provide a basic implementation of a Turing Machine. It allows users to define their own set of rules and input, and observe the machine's behavior as it processes the input according to the rules.

## Features
- User-defined rules: Users can define their own set of rules that determine the machine's behavior. Each rule consists of a current state, a current symbol, an action (move left, move right, or stay), a new symbol to write, and a new state to transition to.
- Input tape: Users can input a sequence of symbols on the tape for the machine to process.
- Step-by-step execution: Users can observe the machine's execution step by step, seeing the current state, symbol, and action at each step.
- Visualization: The machine's tape and head position are visualized to provide a clear representation of its current state.

## Getting Started
To use the Turing Machine, follow these steps:
1. Define the set of rules for the machine.
2. Input the initial tape contents.
3. Start the machine and observe its execution.

## Example
Here's an example of how to use the Turing Machine:

1. Define the rules:
   - Rule 1: If the current state is A and the current symbol is 0, write 1, move right, and transition to state B.
   - Rule 2: If the current state is B and the current symbol is 1, write 0, move left, and transition to state A.
   - Rule 3: If the current state is B and the current symbol is 0, write 1, move right, and transition to state C.

2. Input the initial tape contents: 0101010

3. Start the machine and observe its execution:
   - Step 1: State A, Symbol 0, Action: Write 1, Move Right, Transition to state B. Tape: 1101010
   - Step 2: State B, Symbol 1, Action: Write 0, Move Left, Transition to state A. Tape: 1001010
   - Step 3: State A, Symbol 0, Action: Write 1, Move Right, Transition to state B. Tape: 1101010
   - Step 4: State B, Symbol 1, Action: Write 0, Move Left, Transition to state A. Tape: 1001010
   - Step 5: State A, Symbol 0, Action: Write 1, Move Right, Transition to state B. Tape: 1101010
   - Step 6: State B, Symbol 1, Action: Write 0, Move Left, Transition to state A. Tape: 1001010
   - Step 7: State A, Symbol 0, Action: Write 1, Move Right, Transition to state B. Tape: 1101010

## Contributions
Contributions to the Turing Machine project are welcome! If you have any ideas for improvements or new features, feel free to submit a pull request.

## Acknowledgments
- Alan Turing for his groundbreaking work on theoretical computation.
- The open-source community for providing valuable resources and inspiration.
