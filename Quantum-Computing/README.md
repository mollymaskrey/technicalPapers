# Quantum Computing & Optimization

**Molly Maskrey | Independent Technical Research & Applied Quantum Computing**

This collection presents selected technical papers exploring quantum computing, mathematical optimization, and hybrid quantum-classical approaches to practical problems in engineering, healthcare, finance, and computational biology.

My research interests span quantum annealing, gate-model computation, energy-based machine learning, and the formulation of complex decision problems for quantum-compatible optimization.

The papers include experimental investigations, mathematical frameworks, research proposals, and technical working notes. They are intended to demonstrate both the possibilities and the limitations of emerging quantum computing technologies.

---

## Research Papers

### 1. Investigating Quantum Computing for Astronomical Adaptive Optics: A Comparative Study

**July 2025 | Experimental Study | D-Wave | Adaptive Optics**

An investigation into the feasibility of applying quantum optimization to astronomical wavefront correction, comparing classical least-squares methods with D-Wave's hybrid Constrained Quadratic Model (CQM) solver.

The study incorporates Zernike wavefront distortions, deformable mirror actuator modeling, and comparative evaluation of correction accuracy and computational performance. Both approaches achieved comparable correction quality, although classical optimization demonstrated faster solution times in the tested configurations.

**Research contribution:** An implemented comparison connecting adaptive optics engineering with quantum-classical optimization and establishing a foundation for further benchmarking.

**[Read Paper (PDF)](AO_Paper.pdf)**

### 2. Inferring Hidden Competitive Intelligence in Pharmaceutical Negotiations: Quantum-Trained Boltzmann Machines for Strategic Advantage in PBM Rebate Contracts

**August 2025 | Research Framework | Quantum Machine Learning | Healthcare Economics**

A proposed framework for applying quantum-assisted Restricted Boltzmann Machines (RBMs) to pharmaceutical rebate negotiations, where incomplete information about competitors, pricing, and contractual arrangements creates substantial strategic uncertainty.

The research explores learning latent market structures from observable data, including formulary positioning, market-share movements, and pricing behavior. It examines how D-Wave quantum annealing could contribute to the sampling and training of energy-based probabilistic models.

**Research contribution:** An interdisciplinary framework combining probabilistic machine learning, quantum annealing, and pharmaceutical market economics to investigate hidden competitive relationships. Quantum-specific performance benefits remain hypotheses requiring experimental validation.

**[Read Paper (PDF)](Pharmaceutical_PBM_Rebate_Analysis.pdf)**

### 3. TEMPO-Q: Temporal Path Optimization via Quantum — A Time-Variant Energy Minimization Framework

**July 2025 | Conceptual Research | Temporal Optimization | Energy Landscapes**

TEMPO-Q explores optimization problems in which decisions, costs, and constraints evolve over time.

Rather than seeking an optimal solution to a static problem, the framework models trajectories through temporal state spaces. It introduces nonlocal transitions, dynamic constraints, and the importance of intermediate-state feasibility when evaluating alternative strategies.

Potential applications include healthcare treatment pathways, pharmaceutical negotiations, logistics, and resource planning.

**Research contribution:** A proposed temporal optimization framework connecting sequential decision-making, energy landscape navigation, and potential hybrid quantum-classical solution methods.

**[Read Paper (PDF)](TEMPOQ.pdf)**

### 4. A General Framework for Encoding Financial Decision Structures into QUBO Models

**November 2025 | Technical Whitepaper | QUBO | D-Wave Ocean SDK**

A systematic approach to translating financial and operational decisions into Quadratic Unconstrained Binary Optimization (QUBO) formulations.

The paper presents six worked examples across retail pricing, airline revenue management, manufacturing allocation, portfolio optimization, and pharmaceutical benefit contracting.

Topics include binary variable encoding, objective construction, constraint penalties, QUBO assembly, and Python implementation using the D-Wave Ocean SDK.

**Research contribution:** A reusable modeling methodology for translating conventional business decision variables into optimization formulations suitable for classical annealing and quantum-hybrid experimentation.

**[Read Paper (PDF)](financial_to_quantum.pdf)**

### 5. Quantum Noise: Why Near-Term Quantum Hardware Is Hard to Use and What That Means for Real Problems

**September 2026 | Technical Working Notes | Quantum Hardware | QAOA**

A technical examination of the noise and hardware limitations affecting near-term superconducting quantum processors, particularly IBM transmon architectures.

The paper distinguishes noise associated with circuit depth from limitations associated with qubit count and connectivity. Topics include T1 relaxation, T2 dephasing, gate errors, crosstalk, SWAP overhead, error mitigation, and quantum error correction.

The analysis also considers the practical implications of these constraints for Quantum Approximate Optimization Algorithm (QAOA) implementations.

**Research contribution:** A hardware-aware assessment of the challenges involved in translating theoretically valid quantum optimization algorithms into executable circuits on noisy processors.

**[Read Paper (PDF)](quantum_noise.pdf)**

### 6. Quantum Annealing for Predictive Viral Mutation Analysis: A SARS-CoV-2 Spike Protein Case Study

**September2025 | Research Proposal | Quantum Annealing | Computational Biology**

A proposed application of quantum annealing to the exploration of viral protein mutation landscapes.

The research outlines a QUBO formulation incorporating protein folding energetics, receptor-binding affinity, immune interaction, and structural stability. The SARS-CoV-2 spike protein serves as a proposed case study for investigating the computational feasibility of identifying candidate mutation configurations.

The paper addresses model parameterization, quantum hardware limitations, problem decomposition, and possible validation strategies.

**Research contribution:** An exploratory framework connecting quantum optimization with computational biology and viral mutation modeling. Predictive effectiveness and quantum computational advantage have not yet been established.

**[Read Paper (PDF)](viral_mutation.pdf)**

---

## Research Approach

Across these investigations, several common principles guide my work:

- **Problem formulation first:** Express real-world problems in mathematically meaningful terms before selecting a computational platform.
- **Classical benchmarking:** Evaluate emerging quantum methods against established classical algorithms and optimization approaches.
- **Hardware awareness:** Account for connectivity, noise, computational overhead, solver constraints, and resource requirements.
- **Interdisciplinary application:** Explore opportunities to apply computational ideas across engineering, healthcare, economics, and scientific research.
- **Transparent limitations:** Distinguish conceptual frameworks, proposed experiments, implemented systems, and empirically demonstrated results.

Quantum computing research should not begin with an assumption of quantum advantage. It should begin with a problem worth solving and a rigorous method for determining whether quantum resources offer measurable value.

---

## About This Collection

These documents represent selected independently authored technical work, including exploratory research and investigations conducted at different stages of development.

They are not all peer-reviewed publications. Experimental findings, research proposals, conceptual frameworks, and working notes are identified accordingly.

**Author:** Molly Maskrey

**Contact:** mollymaskrey@gmail.com

[Return to Technical Papers Repository](../README.md)

---

*The objective is not to prove that quantum computing is always superior. It is to discover where, why, and under what conditions it might be useful.*
