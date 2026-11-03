# Hi, I'm Sushmanth

C++ developer with 3+ years of experience, now focused on **CPU inference for large language models**.

### What I work on
- **KAI** at Ziroh Labs: a from-scratch C++ CPU inference engine for LLMs (Llama, Qwen2.5, Qwen3) with hand-written **ARM NEON / SVE2** kernels.
  - Qwen3-0.6B prefill **35% faster than llama.cpp** on a Raspberry Pi 5 (818 ms vs 1257 ms to first token)
  - Decode latency cut from **~148 to ~94 ms/token** (GEMV kernels, int8 W8A16 quantization, mmap weight loader)
  - Qwen2.5-7B time to first token from **0.6 s to 0.24 s** on a 72-core Arm Neoverse-V2 server
- Previously: 2+ years building Windows desktop apps in **C++ / VC++ / MFC** for Sony's CATALYST media software.

### Skills
- **Languages:** C, C++ (templates, constexpr, STL), Python, NumPy
- **Performance:** ARM NEON, SVE/SVE2, GEMM/GEMV micro-kernels, cache blocking, OpenMP, multithreading
- **ML systems:** LLM inference (prefill/decode, KV cache, GQA, RoPE, RMSNorm, SwiGLU), quantization (W8A16, W8A8), fp16/bf16
- **Windows:** Win32, MFC
- **Tools:** CMake, GCC / Clang, Visual Studio, Git, JIRA

### Education
B.Tech, Electronics and Communication Engineering, Sri Vasavi Engineering College (2023)

*Most of my professional work lives in private company codebases.*
