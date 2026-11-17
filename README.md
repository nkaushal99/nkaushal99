# Hey, I'm Nikhil Kaushal 👋

**Software Engineer | High-Performance Computing & Distributed Systems**

Java · Python · C++ · OpenMP · MPI · Linux · AWS · Docker · Distributed Systems · Performance Engineering

I’m a software engineer with experience building **backend systems, cloud-native services, distributed applications, and AI infrastructure**, and I’m now expanding that foundation into **high-performance computing, parallel programming, GPU systems, and compute infrastructure**.

My professional background includes **Java, Python, Spring Boot, AWS, Docker, event-driven systems, concurrency, and AI workloads**, while my current hands-on work focuses on **C++, OpenMP, MPI, cache-aware optimization, Linux, and performance benchmarking**.

I’m particularly interested in the intersection of **HPC software, distributed compute, GPU infrastructure, and AI inference systems**.

[Portfolio](https://nkaushal99.github.io/) · [LinkedIn](https://www.linkedin.com/in/kaushalnikhil99) · [Email](mailto:kaushalnikhil99@gmail.com)

## Current focus: HPC & systems

- **Parallel programming:** C++17, OpenMP threading, MPI rank-based decomposition, reductions, and collective communication.
- **Performance engineering:** loop reordering, memory locality, cache blocking, benchmarking and scalability comparisons.
- **Linux & infrastructure:** Linux administration and RHCSA preparation; interested in cluster operations, scheduling, observability and GPU server infrastructure.
- **Next frontier:** CUDA/GPU programming, heterogeneous compute and AI inference infrastructure. *(Learning goals, not claimed production experience.)*

### Featured HPC project: [Parallel Matrix Engine](https://github.com/nkaushal99/parallel-matrix-engine)

Built five stages of C++17 matrix multiplication to isolate the effects of memory access, cache locality and parallel execution: **naive → loop-reordered → cache-blocked → OpenMP → MPI**. Includes CMake builds, benchmark collection, repeat-run summaries, plots, and numerical-result checks.

| Implementation | Configuration | Reported median (512×512) | Relative to naive |
| --- | --- | ---: | ---: |
| Naive | 1 worker | 2285.159 ms | 1.00× |
| Loop-reordered | 1 worker | 1593.818 ms | 1.43× |
| Cache-blocked | 32×32 tiles, 1 worker | 1463.679 ms | 1.56× |
| OpenMP | 2 threads | 680.567 ms | 3.36× |
| MPI | 2 ranks | 577.418 ms | 3.96× |

*Reported project measurements: 110 runs per variant. The OpenMP/MPI figures reflect their documented environments; they are not a controlled, hardware-equivalent MPI-vs-OpenMP comparison. See the [project README](https://github.com/nkaushal99/parallel-matrix-engine#readme) for methodology and plots.*

## Production engineering experience

I bring practical experience in **distributed backend and AI systems**, including resilience, asynchronous coordination, workload processing and cost-aware execution:

- Developed a production **multi-agent orchestration platform** handling **10K+ weekly requests**, with routing, validation, guardrails and multi-step workflow control.
- Built event-driven **RAG ingestion infrastructure** for parsing, chunking, indexing and stateful failure recovery.
- Developed an asynchronous **LLM-as-Judge evaluation pipeline**, reducing evaluation cost **50%** using batch inference.
- Improved sentence-level TTS throughput **3×** while lowering inference cost **70%** through batched parallel synthesis.
- Designed SQS FIFO and DynamoDB concurrency controls to preserve ordering and prevent lost updates.

**Relevant bridge:** the same engineering disciplines—measuring throughput, handling concurrency, controlling resource use, and building reliable distributed services—also matter when moving from application-level distribution to HPC and AI compute infrastructure.

## Selected systems and AI projects

| Project | What it demonstrates |
| --- | --- |
| [Parallel Matrix Engine](https://github.com/nkaushal99/parallel-matrix-engine) | **Primary current project:** C++, OpenMP, MPI, cache locality, performance optimization and benchmarking |
| [VibeSense Agent](https://github.com/nkaushal99/vibesense-agent) | Applied AI agent integrating live signals with downstream services |
| [One RAG](https://github.com/nkaushal99/one-rag) | RAG experimentation, document retrieval and AI data pipelines |

## Technology

**HPC / systems (hands-on):** C++17 · OpenMP · MPI · CMake · Linux · cache-aware optimization · benchmarking  
**Backend / distributed systems (professional):** Java · Python · Spring Boot · Kafka · SQS · DynamoDB · REST · microservices · fault tolerance  
**AI / cloud (professional):** Python · LangGraph · RAG · LLM evaluation · AWS · Docker  
**Currently developing:** CUDA · GPU compute · Linux server operations · cluster management

## Education & credentials

- B.E. Computer Engineering — Thapar Institute of Engineering & Technology, CGPA 9.3
- AWS Certified Developer – Associate (2026–2029)
- AWS Certified Solutions Architect – Associate
- **Red Hat Certified System Administrator (RHCSA):** preparing for examination; certification not yet earned

---

**Interested in:** HPC software engineering · distributed compute systems · GPU infrastructure · Linux systems engineering · AI inference infrastructure.

I value measurable performance improvements and reliable systems, and I document both what works and what still needs validation.
