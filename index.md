# Bowen Zhang (张博文)

I am a third-year PhD student at Shanghai Jiao Tong University, advised by Prof. Hong Mei and Prof. Linpeng Huang. I received my bachelor's degree with Zhiyuan honors from Shanghai Jiao Tong University in 2021.

# Research

My research interests focus on designing storage systems (e.g., database systems, key-value stores, and file systems) for modern hardware (e.g., persistent memory, RDMA, CXL, SmartNIC) or architecture (e.g., resource disaggregation). My current projects including:

* **Persistent Memory-based Systems.** Emerging persistent memory provides many attractive features, such as byte addressability, DRAM-comparable performance, and data durability,  which motivates us to redesign existing systems to fully harness the benefits of persistent memory.
  * NBTree (VLDB 22): A persistent B+Tree that employs a two-layer leaf node structure to minimize the number of PM accesses and a lock-free concurrency protocol to enhance scalability.
  * Spash (ICDE 24): A persistent hash index that combines the benefits of HTM and persistent CPU cache to minimize write amplification and maximize concurrency.
  * Calloc (TPDS 24): A persistent memory allocator that fully exploits the persistent CPU cache to absorb PM writes during memory management.
* **Disaggregated Memory-based Systems.** Disaggregated memory systems disseminate the compute and memory resources of monolithic servers into two independent network-attached pools, offering
  high resource utilization, enhanced architectural elasticity, and fine-grained failure domain. These advantages have motivated our exploration into optimizing current systems for this innovative architecture.

# Publication

* **Exploiting Persistent CPU Cache for Scalable Persistent Hash Index**

  **Bowen Zhang**, Shengan Zheng*, Liangxu Nie, Zhenlin Qi, Linpeng Huang*, Hong Mei

  Published in *IEEE International Conference on Data Engineering (ICDE)*, 2024
* **Revisiting PM-based B+-Tree with Persistent CPU Cache**

  **Bowen Zhang**, Shengan Zheng*, Liangxu Nie, Zhenlin Qi, Hongyi Chen, Linpeng Huang*, Hong Mei

  Published in *IEEE Transactions on Parallel and Distributed Systems (TPDS)*, 2024
* **NBTree: a Lock-free PM-friendly Persistent B+-Tree for eADR-enabled PM Systems**

  **Bowen Zhang**, Shengan Zheng, Zhenlin Qi, Linpeng Huang

  Published in *Proceedings of the VLDB Endowment (VLDB)* , 2022
* **Conflux: Exploiting Persistent Memory and RDMA Bandwidth via Adaptive I/O Mode Selection**

  Zhenlin Qi, Shengan Zheng, Yifeng Hui, **Bowen Zhang**, Linpeng Huang

  Published in *International Conference on Parallel Processing (ICPP)* , 2023
* **Heart: A Scalable, High-performance ART for Persistent Memory**

  Liangxu Nie, Shengan Zheng, **Bowen Zhang**, Jinyan Xu, Linpeng Huang

  Published in  *IEEE International Conference on Computer Design (ICCD)* , 2023
