# Hi, I'm Adi 👋

Computer Engineering @ UIUC (May 2028). I work on systems software (OS internals), performance engineering, and data infrastructure.

- 🛰️ Previously SWE intern at **Amazon Leo** (data infrastructure) and **State Farm** (observability)
- 📄 Co-authored a paper at the CV4Edu Workshop, CVPR 2026
- 🔧 Currently building a RISC-V OS kernel and learning everything about virtual memory

## Experience

- **Amazon Leo**, SWE Intern (Summer 2026): Event-driven ingestion into a partitioned Iceberg lake (500GB+); Iceberg sort redesign cut query latency 62%
- **TIMAN Lab, UIUC**, Undergraduate Researcher (2025–2026): Gaze-tracking browser extension with an MDP + VLM pipeline; paper at CV4Edu @ CVPR 2026
- **State Farm**, SWE Intern (Summer 2025): Metrics pipeline and OpenSearch observability for an internal data capture service
- **State Farm**, SWE Intern (Summer 2024): Serverless test data generation (EventBridge, Lambda) and Azure SSO for 100+ internal developers

## Projects

### [stm32-bignum-crypto](https://github.com/31adi31/stm32-bignum-crypto)
Arbitrary-precision arithmetic in C on an ARM Cortex-M4, used for 2048-bit Diffie-Hellman on-device. Montgomery reduction and sliding-window exponentiation for up to **2.83×** speedup, benchmarked cycle-by-cycle with the DWT counter.

### RISC-V OS Kernel *(course project, code private)*
Unix-like kernel in C with interrupt-driven VirtIO/UART drivers, a FAT-based file system, a concurrent block cache, an ELF loader, and Sv39 virtual memory with lazy allocation.

### GPT-2 CUDA Inference *(course project, code private)*
Custom CUDA kernels for GPT-2 inference: Flash Attention with register tiling (**7×** speedup) and a KV cache with prefill/decode kernels (**4.57×**), profiled with Nsight Compute.
## Tech

![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white)
![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=flat&logo=riscv&logoColor=white)
![ARM Cortex-M](https://img.shields.io/badge/ARM_Cortex--M-0091BD?style=flat&logo=arm&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)

## Contact
[LinkedIn](https://www.linkedin.com/in/adichalasani31/) · adic3@illinois.edu
