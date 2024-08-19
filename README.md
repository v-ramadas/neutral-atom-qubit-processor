# Neutral Atom Qubit Processor

The Neutral Atom Qubit Processor is a simulator that models a quantum computing processor using a Cs neutral atom as its qubit. It models various interactions between the atom and pulses that result in gate operations. The simulator can either be used to study the interaction of the atoms with several aspects of its environment or to simulate behavior of quantum circuits. When simulating quantum circuits, the processor can be used as Qiskit's backend. 

## Dependencies

In order to use the neutral atom qubit processor, the following Python libraries need to be installed:
* qutip
* qutip-qip
* qiskit
* qiskit_experiments
* qiskit_
* numpy
* scipy
* matplotlib

## Files

* NeutralAtomProcessor.ipynb: Contains classes that model gate operations on Cs atoms and a processor contain RX, RZ, CZ gates.
* QuantumCircuits.ipynb: Contains examples that use the processor as a backend in Qiskit to simulate different circuits
* QCVV.ipynb: Contains examples that use randomized benchmarking which follow quantum characterization, verification, and validation (QCVV) protocols to measure fidelity of the processor
