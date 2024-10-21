# Siddharth-Vijaymurugan-s-Portfolio

## RXXPulseImplementation:

This code is the result of a quantum computing research project. Built from IBM's open-source quantum computing Python package, Qiskit, this code helps to generate instructions for optimized quantum bit operations. This applies specifically to the superconducting qubits found on IBM's quantum computers. The optimizations arise from the Echoed Cross Resonance Pulse implemented on IBM's hardware. It is known that these pulses' parameters can be scaled to change the area of the pulse, which leads to the scaling of the amount of rotation. For instance, doubling the area of the pulse also doubles the amount of rotation (i.e. doubles the angle of rotation) applied by the pulse. Further specifics regarding Pulse-Scaling are described here (https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.3.033171).

This form of optimization was applied in a circuit that models the evolution of the magnetization of a particular quantum system. In that, the evolution was more accurate when modeled with the optimization. The circuit was also executed in a shorter time.

This optimization is particularly helpful in applications of Trotterization. This is because Trotterization approximates qubit operations with a series of small rotations, and this type of pulse-scaling optimization is most effective with small rotations.

## Grover's Algorithm:

This code helps to show the effect of noise in quantum computation. Here, Grover's Algorithm was run on an ideal simulation of a quantum computer, a noisy simulation, and a noisy simulation with Error Handling Techniques applied. This was done with the help of the qasm_simulator provided by IBM through their Python package, Qiskit.

## Multivariate Solar Angle Calculator:

This was developed with the need to calculate the angle at which to orientate a mirror to reflect sunlight to a predetermined point. This program reads a .txt file including the locations of about 20 individual mirrors and the position of the Sun. With these details, the two angles required to determine the orientation of each mirror were calculated.
