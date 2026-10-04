# Open Source Contributions

| Repository | PR Title | Status | Link |
|------------|----------|--------|------|
| AcceleratedKernels.jl | Let `map` and `map!` take several source arrays | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/130) |
| AcceleratedKernels.jl | Sort along `dims` with RadixSort | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/129) |
| GPUArrays.jl | feat: `sort `/ `sort!` delegated to AcceleratedKernels | closed | [Link](https://github.com/JuliaGPU/GPUArrays.jl/pull/788) |
| GPUArrays.jl | feat: Add accumulate, cumsum and cumprod using AcceleratedKernels | closed | [Link](https://github.com/JuliaGPU/GPUArrays.jl/pull/787) |
| GPUArrays.jl | feat: Adding `Base.reverse` / `reverse!` support using AcceleratedKernels.jl | closed | [Link](https://github.com/JuliaGPU/GPUArrays.jl/pull/786) |
| segfault26 | feat: add accelerator backend on LLDB's accelerator-plugin framework | open | [Link](https://github.com/vishruth-thimmaiah/segfault26/pull/25) |
| segfault26 | feat: add OpenCL vector type support to variable inspection | closed | [Link](https://github.com/vishruth-thimmaiah/segfault26/pull/23) |
| GPUArrays.jl | Add a sorting interface | closed | [Link](https://github.com/JuliaGPU/GPUArrays.jl/pull/776) |
| AcceleratedKernels.jl | Add `BitonicSort`, a GPU sorting network for small arrays and short slices | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/126) |
| AcceleratedKernels.jl | perf(sort): packed-key fast path for sort(A; dims=1) | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/121) |
| AMDGPU.jl | Guard empty-array launch in out-of-place reverse | closed | [Link](https://github.com/JuliaGPU/AMDGPU.jl/pull/1069) |
| AcceleratedKernels.jl | Add `start`/`stop` keywords to `reverse` and `reverse!` | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/119) |
| AcceleratedKernels.jl | perf(reverse): use a dedicated kernel for the dims reversal | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/118) |
| AcceleratedKernels.jl | Add `dims` support to `sort`, `sort!`, `sortperm` and `sortperm!` | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/117) |
| AcceleratedKernels.jl | Fix DecoupledLookback with a device-scope memory fence | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/116) |
| AcceleratedKernels.jl | feat(findall): Add findall kernel | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/115) |
| AcceleratedKernels.jl | Add `dims` support to `reverse` and `reverse!` | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/114) |
| AcceleratedKernels.jl | fix(accumulate): keep GPU scans uniform and non-divergent across backends | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/112) |
| AcceleratedKernels.jl | Make GPU scans process multiple items per thread | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/108) |
| AcceleratedKernels.jl | Make GPU reductions process multiple items per thread | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/107) |
| AcceleratedKernels.jl | Reduce: vectorize contiguous by-block loads | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/105) |
| AcceleratedKernels.jl | ci(opencl): run POCL under --check-bounds=auto; skip scan on POCL | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/104) |
| AcceleratedKernels.jl | Fix OpenCL/POCL CI: run under --check-bounds=auto, skip scan on POCL | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/103) |
| AcceleratedKernels.jl | Add reverse! and reverse | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/102) |
| AcceleratedKernels.jl | Fix DecoupledLookback cross-block coherence (completes #91) | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/98) |
| AcceleratedKernels.jl | Optimize Radix sort. | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/97) |
| AcceleratedKernels.jl | Optimize GPU radix sort: ballot kernels, fused range, skip-pass, tuning | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/93) |
| KernelAbstractions.jl | feat(intrinsics): add KI.vload / KI.vstore! for wide vector memory operations | closed | [Link](https://github.com/JuliaGPU/KernelAbstractions.jl/pull/719) |
| AcceleratedKernels.jl | Add opt-in GPU radix sort via sort alg keyword | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/90) |
| GPUArrays.jl | Delegate mapreducedim! to AcceleratedKernels.jl | closed | [Link](https://github.com/JuliaGPU/GPUArrays.jl/pull/725) |
| AcceleratedKernels.jl | Expand dimensional `mapreduce` / `reduce` | closed | [Link](https://github.com/JuliaGPU/AcceleratedKernels.jl/pull/83) |
| cuTile.jl | Subtype AbstractArray for TileArray | closed | [Link](https://github.com/JuliaGPU/cuTile.jl/pull/176) |
| SiMG | added comparison engine | closed | [Link](https://github.com/ShreyashSri/SiMG/pull/1) |
| GPUArrays.jl | feat: add GPU-native kron support for Diagonal matrices | closed | [Link](https://github.com/JuliaGPU/GPUArrays.jl/pull/690) |
| cuTile.jl | Add alias-aware token threading for memory operations. | closed | [Link](https://github.com/JuliaGPU/cuTile.jl/pull/89) |
| gccrs | gccrs: avoid ICE when canonical path record is missing | open | [Link](https://github.com/Rust-GCC/gccrs/pull/4415) |
| GPUArrays.jl | Specialize ReshapedArray to resolve `setindex!` ambiguities | closed | [Link](https://github.com/JuliaGPU/GPUArrays.jl/pull/680) |
| GPUArrays.jl | feat: Implement issorted for AbstractGPUArray without scalar indexing. | closed | [Link](https://github.com/JuliaGPU/GPUArrays.jl/pull/678) |
| SecureWipe | Revise README for clarity and additional details | closed | [Link](https://github.com/pointblank-club/SecureWipe/pull/1) |
| julia | Fix OutOfMemory in arrayshow with unsigned indices | open | [Link](https://github.com/JuliaLang/julia/pull/59925) |
| emscripten | [memoryprofiler] Add CSS class to parent div | closed | [Link](https://github.com/emscripten-core/emscripten/pull/25595) |
| gccrs | gccrs: Fix ICE in no input file | open | [Link](https://github.com/Rust-GCC/gccrs/pull/4240) |
| gccrs | gcc: Prevent ICE on no input file | closed | [Link](https://github.com/Rust-GCC/gccrs/pull/4203) |
| shreyas-omkar | Update README.md | closed | [Link](https://github.com/shreyas-omkar/shreyas-omkar/pull/1) |
