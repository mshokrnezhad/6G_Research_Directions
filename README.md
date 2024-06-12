# 6G Research Directions

<div align="center">
  <img src="images/cover.jpg" alt="cover" width="600"/>
</div>

This document aims to outline a comprehensive guideline for selecting a promising research subject. The document comprises five sections: **directions**, **use cases**, **objectives**, **constraints**, and **approaches**. 

**Directions** discuss possible research trends for systems that go beyond the capabilities of 5G. Each direction is meticulously outlined by:
1. Highlighting potential **use cases** 
2. Addressing challenging problems within it by specifying clear **objectives** and **constraints** relevant to the subject matter.

Subsequently, all conceivable **use cases** introducing promising futuristic services, **objectives** delineating potential goals for addressing associated problems and subproblems, and **constraints** identifying limitations requiring consideration in problem-solving, are elaborated upon. Finally, various **approaches** are introduced to tackle these directions, incorporating promising techniques to effectively address the outlined **objectives** and **constraints**.

Irrespective of the specified directions, any combination ⟨u, o, c⟩ where u ∈ **use cases**, o ∈ **objectives**, and c ∈ **constraints** defines a research endeavor that can be addressed using the methods described in **approaches** by researchers (postdocs, Ph.D. candidates, or master's students, depending on the complexity of the combination) to yield scientific outcomes. It is indisputable that advanced scenarios can be generated by merging **directions**, and complex problems can be developed by taking into account joint **objectives** and multiple **constraints**.

Using this guideline, researchers can effectively identify and evaluate potential research subjects that align with their interests, expertise, and the broader objectives of their research endeavors.

## Table of Contents

2. [Directions](#directions)
3. [Use Cases](#use-cases)
4. [Objectives](#objectives)
5. [Constraints](#constraints)
6. [Approaches](#approaches)

## Directions

### Integrated Communications, Computing, and Sensing (CCS) in 6G

1. **Integrated Sensing And Communication (ISAC)**
   - ISAC for Unmanned Aerial Vehicles (UAVs)
   - ISAC for vehicular networks
   - Utilizing intelligent omni-surfaces with sensing capabilities.
2. **Integration of Internet of Everything (IoE) and 6G CCS**
3. **Integration of Internet of Intelligent Thing (IoIT) and 6G CCS**
4. **Integrated CCS for Internet of Robots (IoR)**
   - Robotics-as-a-Service towards "remote-controlled economy"
5. **Integrated CCS for Internet of Nano-Things (IoNT)**
   - Enabling nano-bio-sensing
6. **Integration of CCS and localization**
7. **Integrating Reconfigurable Intelligent Surface (RIS) and CCS**
8. **Serverless Computing or Function-as-a-Service (FaaS)**
   - Cloud computing model where cloud providers manage the infrastructure needed to run code, allowing developers to focus on writing and deploying functions without server management.
9. **Integrated space-air-ground networks**
   - Hierarchical communication system forming a constellation of Non-Terrestrial Networking (NTN) satellites, High Altitude Platforms (HAPs), and Terrestrial Networking (TN) domains.

### Spectrum Management in 6G

1. **Intelligent Multiple Access**
   - Multiple access considering Multiple-In Multiple-Out (MIMO) at both sender and receiver sides.
   - Multiple access considering RIS and Reconfigurable Holographic Surface (RHS).
2. **AI-native Air Interface**
3. **Computation Over-the-Air (OTA)**
4. **Handover Management for NTN**
5. **Rate Splitting Multiple Access (RSMA) in 6G**
   - RSMA for multi-user/multi-cell multi-antenna networks utilizing networked (massive) MIMO.
   - RSMA-based robust interference management.
   - RSMA to generalize existing multiple access strategies.
6. **Symbiotic Communications**

### 6G for AI/ML

1. **Orchestrating Big AI/ML Models**
   - Deploying large-scale AI/ML models to enable complex, emerging services faces numerous challenges.
2. **Integrating Network, Computing, and Learning**
   - Orchestrating 6G resources for AI/ML techniques through:
     - Choosing an appropriate AI/ML strategy (centralized, distributed, or federated learning).
     - Allocating computing nodes and capacity to execute AI/ML tasks efficiently.
     - Determining network paths to facilitate the exchange of necessary messages.

### Semantic Communications in 6G

1. **End-to-End (E2E) Semantic Communication System Design**
   - Resource management for semantic communications.
   - Efficient/scalable neural network architectures and training algorithms for semantic communications.
2. **Networking Aspects and Protocols for Goal-oriented Semantic Communications**
3. **Freshness vs. Value Perception Tradeoffs in Semantic Communications**
4. **Precision vs. Cost Tradeoffs in Semantic Communications**
5. **Semantics-empowered Resource Allocation and Management**
6. **Semantic Communications for Extended Reality (XR)/Holographic Communications**
7. **Semantic Communications to Enable the Metaverse**
8. **Social-aware Networking Algorithms, Techniques, and Social-aware Communication Systems**
9. **Cross-layer Communications and Network Management for Affective Sensing**

### Experimentation in Large-Scale Testbeds

1. **Constructing a Testbed for Experimental Investigation of Research Findings**
   - Validating research outcomes via theoretical analysis and computer simulations alone carries the risk of using models that fall short of capturing real-world circumstances.

### Quantum-based Systems

1. **Designing Quantum Internet (QI) Architectures**
2. **Resource Allocation Framework for QI**
   - Quantum routing
   - Distributed quantum computation over quantum cloud.
3. **Designing Hybrid Classical-Quantum Systems**
4. **Network Synchronization Solutions**
5. **Quantum AI/ML for QI**
6. **Integrated NTN and TN to Enable QI**
7. **Ad hoc Quantum UAV Network Design**
8. **Quantum Internet of Space Things (IoST)**
   - Satellite Quantum Key Distribution (QKD)
   - Ad hoc quantum satellite network design

### Energy/Power Harvesting/Transfer in 6G

1. **Designing Near-zero Energy Communication Systems**
   - Imagine a world of ambient Internet of Things (IoT) devices with ultra-low complexity and power consumption.
   - Address challenges related to energy harvesting time and transmission energy.

## Use Cases

1. **The Metaverse**
   - Redefining communication through immersive digital environments where individuals engage via virtual avatars in real-time.
2. **Ambient IoT**
   - Battery-less devices relying on harvesting energy from their environment.
3. **Internet of Everything (IoE)**
4. **Internet of Intelligent Thing (IoIT)**
5. **Internet of Robots (IoR)**
6. **Internet of Nano-Things (IoNT)**
7. **Vehicle to Everything (V2X)**
8. **Internet of Space Things (IoST)**
9. **Crowd Sourcing**

## Objectives

### Functional

1. Energy efficiency
2. Number/rate of supported users
3. Peak data rate
4. Spatial coverage
5. Load balancing
6. Coverage

### Non-functional

1. Architecture design
2. Performance evaluation
3. Admission/congestion control
4. Prediction
5. Sustainability
6. Localization

## Constraints

### System Parameters

1. Network: Terrestrial Networking (TN), High Altitude Platforms (HAPs), Non-Terrestrial Networking (NTN)
2. Computing: User-side, edge, and cloud computing resources
3. Dynamicity: Mobility and time-varying topology
4. Density: Ultra-dense networking
5. Spectrum: Multiple access technologies and protocols
6. Semantic-awareness
7. Quantum-enabled: Quantum Networks (QN)

### Resource Allocation

1. Channel (frequency band) assignment
2. Beamforming
3. Channel estimation
4. Transmit power control
5. Slicing
6. Congestion control
7. Multipath transmissions
8. Path selection
9. User/request/traffic prioritization
10. Migration (or roaming, handover, etc.)

### Performance Metrics

1. Latency or round-trip delay
2. Reliability/availability
3. Spectrum efficiency
4. Throughput
5. Energy efficiency
6. Age of Information (AoI)
7. Jitter
8. Task accomplishment metrics

### Capacity Limitation

1. Rate assignment over wireless links
2. Bandwidth allocation over wired links
3. Computing capacity allocation of computing resources
4. Battery power

## Approaches

### AI/ML

1. Learning Layers: Graph Neural Networks (GNNs)
2. Learning Techniques: Deep Reinforcement Learning (DRL), Generative AI, Explainable AI (XAI), Kolmogorov-Arnold Network (KAN), Neuro-Symbolic AI (NeSy AI)
3. Learning Strategies: Federated Learning (FL), Distributed Learning (DisL), Centralized Learning (CenL)
4. Key Considerations: Human-in-the-loop

### Optimization

1. Non-convex non-smooth optimization
2. Sparse optimization
3. Global optimization
4. Parallel and distributed optimization
5. Fractional programming
6. Robust and stochastic optimization
7. Integer and discrete optimization
8. Data-driven and model-based optimization
9. Bilevel optimization

### Game Theory

Further exploration of game-theoretic approaches can be beneficial in addressing the outlined challenges and optimizing the described objectives.

## Glossary

- **CCS**: Communications, Computing, and Sensing
- **ISAC**: Integrated Sensing And Communication

 
