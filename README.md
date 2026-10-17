# Jacob Garcia

I build small, runnable systems projects, measure them against a baseline, and write down what they do not prove. All code in these projects was written with AI assistance (Instinct) under my direction. I describe what each one demonstrates, not experience I do not have.

**Site:** [jacobegarcia.github.io/systems-projects](https://jacobegarcia.github.io/systems-projects/)

## Featured projects

| Project | Area | Measured result | Stated limit |
|---|---|---|---|
| [tinyfusion](https://github.com/JacobEGarcia/tinyfusion) | ML compilers | Fused vs unfused C lowering: 14.8x on a polynomial graph, 0.36x on a ReLU graph (fusion lost) | 5 ops, not MLIR/XLA/TVM, CPU only |
| [orchd](https://github.com/JacobEGarcia/orchd) | Cloud orchestration | Retries: 80.8% to 99.9% completion at 20% injected failure; 0 of 3000 acknowledged jobs lost after kill -9 | Simulated work, one process, at-least-once |
| [cpu-kernel-study](https://github.com/JacobEGarcia/cpu-kernel-study) | Kernels | Tiled AVX2 matmul 27x over naive, about 6x slower than OpenBLAS | CPU only, one run on a shared VM |
| [par-bench](https://github.com/JacobEGarcia/par-bench) | HPC | OpenMP matmul about 2x from 1 to 2 threads, parallel stencil bitwise equal to serial | 2 vCPUs, single node |
| [rl-and-inference-evidence](https://github.com/JacobEGarcia/rl-and-inference-evidence) | RL, inference | Q-learning 94.7% vs 1.7% random on a toy grid; local LLM about 16 tok/s on CPU, flat across concurrency | Toy task, smoke benchmark, no GPU |

Each repo has a README with how to run it, raw results, and an "honest limits" section.

## A note on the rest of this account
Many other repositories here are quick experiments and prototypes, mostly generated with AI assistance. They are not curated or maintained. The six repos above (and the site) are the ones I stand behind.
