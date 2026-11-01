# Hi, I'm Adi 👋

Computer Engineering @ UIUC (May 2028). I work on systems software: OS internals, performance engineering, and data infrastructure.

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
C · C++ · Rust · CUDA · RISC-V · Linux · GDB · Python · Kotlin · AWS · Spark · Iceberg

## Contact
[LinkedIn](https://www.linkedin.com/in/adichalasani31/) · adic3@illinois.edu
