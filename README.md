# Q-munity-2021-team15
Repo for the Q-Munity hackathon - May 2021

Team Members

- Ankith Mohan @ankith-mohan
- Sarath Reddy @sarathreddy55
- Vishal Sharathchandra Bajpe @mrvee-qC

### Problem Statement
  
The huge potential impact of the optimal physical layout design on the performance of Quantum chips is very well known, yet, Unlike semiconductor physical design methodology, the Quantum architecture design & Quantum physical layout design lacks enough research & development. The lack of a comprehensive & integrated EDA environment for the Physical layout design of quantum chips is the main reason behind low research in this area. Thanks to IBM, we now have access to QISKIT METAL an open-source Q-EDA tool for the purpose of Physical layout design of Superconducting based Quantum Chips. Under standardized Physical Design flow using QISKIT Metal for Quantum Chips, Individuals & Companies looks out for efficient re-usable designs, rather than creating each & every design from scratch. Soft & Hard IPs help bridge this gap. Quantum hardware being a young industry lacks such intellectual properties. We work to resolve this gap by creating more variety of optimized Hard IPs for various Quantum Architectures.
 
### Solution Statement
 
Our main goal is to physically design various building blocks of Quantum chips and make them available for the open-source community as Hard IPs. Such Hard IPs are physically hardened re-usable modules. As the Quantum hardware industry gets more & more standardized, one looks out for Hard IPs. Considering QISKIT Metal as the only Q-EDA tool for the Physical Layout design flow of Quantum Computers, we use the QISKIT Metal environment to design and publish various building blocks of quantum chips. The most commonly used architecture being LNN i.e Linearly nearest neighbour, Under this architecture, there are sub-categories based on connectivity i.e Fully connected(R1), R2, R3, R4, R5 etc from R1 to R5 the connectivity decreases, each of these architectures are an array of basic building blocks, which we choose to optimize & physically implement and publish as Hard IPs to open source community. We use QISKIT Metal's in-built renderers to integrate the physical layout with Ansys analysis tools and take the physical design process through numerous iterations to achieve desired specifications of the circuit.

Paper Referenced: Hu, W., Yang, Y., Pi, W.X., Huang, E., Zhang, X., Co, H.X., & University, S. (2021). Performance of Superconducting Quantum Computing Chips under Different Architecture Design. https://arxiv.org/abs/2105.06062 https://www.semanticscholar.org/paper/Performance-of-Superconducting-Quantum-Computing-Hu-Yang/26b52613fba7113605ab286b5e56ff82bc34762a
