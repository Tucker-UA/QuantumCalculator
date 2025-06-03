### Project 3

## Part of the Quantum Computing Bootcamp at the Erdos Institute.

The goal of this project is to implement a quantum calculator for $d$-qubit numbers using qiskit.
There are two main objectives:
1. Implement addition modulo $2^d$;
2. Implement multiplication modulo $2^d$.

These objectives are subject to the following constraints:
- Two $d$-qubit registers, $|x\rangle$ and $|y\rangle$, holding the two input numbers;
- One control qubit, $|z \rangle$, that implements addition if $z = 0$ and multiplication if $z = 1$;
- One $d$-qubit output register, which holds the result of the chosen operation;
- No gates other than arbitrary 1-qubit, control not, and Toffoli gates may be used

Finally, an analysis of the complexities and resources used is to be added at the end of the project.

---

Satisfying the above objectives and constraints would complete the project, but to make our calculator more useful, we would like to implement more operations.
As such, we list the following in order of implementation, where a strikethrough indicates that the operation was added successfully:
- Implement subtraction modulo $2^d$
- Implement modular exponentiation modulo $2^d$
