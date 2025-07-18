[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

# awesome-quantum-artificial-intelligence
Awesome Quantum Artificial Intelligence is a curated list of resources, research papers, books, tutorials, libraries, frameworks, open-source projects, and tools at the intersection of Quantum Computing and Artificial Intelligence.

# Awesome Quantum Artificial Intelligence

A curated list of the most important and actively maintained frameworks and libraries for Quantum Artificial Intelligence.

---

## Frameworks & Libraries

### General Quantum Computing

- [Qiskit](https://github.com/Qiskit/qiskit-terra)  
  An open-source framework by IBM for creating, simulating, and running quantum circuits. Includes modules for quantum machine learning and integrates with IBM Quantum hardware.

- [Cirq](https://github.com/quantumlib/Cirq)  
  Google’s Python framework for designing, simulating, and running quantum circuits, especially for NISQ (Noisy Intermediate-Scale Quantum) devices. Used as the backend for TensorFlow Quantum.

- [PyQuil](https://github.com/rigetti/pyquil)  
  A Python library for quantum programming using Rigetti’s Quil language. Allows development and simulation of quantum programs for Rigetti hardware and simulators.

- [Microsoft Quantum Development Kit (Q#)](https://github.com/microsoft/qsharp)  
  Microsoft’s platform and high-level programming language for quantum computing, with libraries for quantum algorithms and machine learning. Includes simulators and Azure Quantum integration.

- [ProjectQ](https://github.com/ProjectQ-Framework/ProjectQ)  
  Open-source quantum computing framework with a powerful compiler and simulator. Supports multiple hardware backends and allows writing quantum programs in Python.

- [tket (pytket)](https://github.com/CQCL/pytket)  
  A hardware-agnostic quantum circuit compiler and toolkit by Quantinuum. Offers advanced circuit optimization, qubit routing, and compatibility with many quantum backends.

---

### Quantum Machine Learning & Hybrid Frameworks

- [Qiskit Machine Learning](https://github.com/qiskit-community/qiskit-machine-learning)  
  An extension of Qiskit that provides tools, algorithms, and neural network primitives for quantum machine learning. Easily integrates quantum machine learning models with classical ML workflows.

- [PennyLane](https://github.com/PennyLaneAI/pennylane)  
  A cross-platform Python library for hybrid quantum-classical computation and quantum machine learning. Supports differentiable programming and works with PyTorch, TensorFlow, and JAX.

- [TensorFlow Quantum](https://github.com/tensorflow/quantum)  
  Extension of TensorFlow for quantum machine learning, enabling hybrid quantum-classical models using Cirq as a backend and standard TensorFlow/Keras workflows.

- [TorchQuantum](https://github.com/mit-han-lab/torchquantum)  
  PyTorch-based library for quantum machine learning and quantum neural networks. Allows building and training quantum-classical hybrid models within PyTorch.

- [MindQuantum](https://github.com/mindspore-ai/mindquantum)  
  Quantum machine learning library from Huawei MindSpore, focused on NISQ algorithms and quantum neural networks with a high-performance simulator.

- [Strawberry Fields](https://github.com/XanaduAI/strawberryfields)  
  Framework for photonic quantum computing and continuous-variable quantum circuits, with applications in quantum machine learning and quantum optics.

---

### Quantum Annealing & Optimization

- [D-Wave Ocean SDK](https://github.com/dwavesystems/dwave-ocean-sdk)  
  Python libraries from D-Wave for formulating and solving optimization problems on quantum annealers and hybrid solvers. Useful for QUBO/Ising models.

---

### Quantum Simulation & Specialized Libraries

- [QuTiP](https://github.com/qutip/qutip)  
  The Quantum Toolbox in Python, used for simulating quantum systems, dynamics, and open quantum systems. Widely used for algorithm prototyping and quantum neural network dynamics.

- [Qulacs](https://github.com/qulacs/qulacs)  
  High-performance quantum circuit simulator with C++ core and Python interface. Optimized for speed, multi-threading, and GPU support.

- [OpenFermion](https://github.com/quantumlib/OpenFermion)  
  Open-source library for quantum computing applications in chemistry and materials science. Integrates with Cirq and Qiskit for quantum chemistry and machine learning tasks.

---

*Feel free to contribute more frameworks and libraries to this list!*
