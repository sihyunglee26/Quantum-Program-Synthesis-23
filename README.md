# Quantum-Program-Synthesis-23

This repository contains sample target programs and their implementations with 2 to 5 qubits. 

In the files, a target function in a matrix format is followed by a sample implementation by the proposed system.	The implementation shows operators in the same stage within curly brackets ({}) and the qubit numbers where operators are applied in square brackets ([]). For example, 

{'H':[[0],[1]], 'CNOT':[[2,3]]}

indicates a stage with 
(i) two H operators on qubits 0 and 1 and 
(ii) one CNOT operator on qubits 2 and 3. 

Operators Tct and Sct are conjugate transposes of T and S, respectively.
