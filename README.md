### Hi, I'm TANGBUDU

I contribute to ML infrastructure, with a focus on compiler correctness, GPU kernels, and quantized inference.

- **Open source:** contributions landed in PyTorch, Triton, and ONNX Runtime.
- **Research:** pixel-based thermal facial image analysis for emotion sensing.
- **Building:** personal AI agent systems and automation tools.

#### Selected upstream contributions

Six contributions merged or landed upstream as of September 29, 2026.

| Project | Contribution | Status |
| --- | --- | --- |
| PyTorch / TorchInductor | Prevent unsafe in-place `index_put` rewrites when indices or values share input storage; add graph-level and end-to-end regressions. [PR #198637](https://github.com/pytorch/pytorch/pull/198637) | [Landed on main](https://github.com/pytorch/pytorch/commit/dd806b6d43def42db89610cad528cb382603e3da) |
| PyTorch / TorchInductor | Correct select–cat rewrite matching, layout checks, and output aliasing semantics. [PR #198638](https://github.com/pytorch/pytorch/pull/198638) | [Landed on main](https://github.com/pytorch/pytorch/commit/a3eb338abdb8e090317a13fdee94332792ff6412) |
| Triton | Prevent loop pipelining from moving dependent loads ahead of in-loop grid dependency waits; add MLIR scheduling regressions. [PR #11906](https://github.com/triton-lang/triton/pull/11906) | Merged |
| ONNX Runtime | Fix silent INT2 per-axis quantization corruption when single-element scale intervals share packed bytes. [PR #32786](https://github.com/microsoft/onnxruntime/pull/32786) | Merged |
| Triton | Reject empty CGA layouts for two-CTA tensor memory with a verifier diagnostic instead of a compiler abort. [PR #11894](https://github.com/triton-lang/triton/pull/11894) | Merged |
| PyTorch / Autograd | Fix forward-mode AD `gradcheck` diagnostic indexing across filtered input/output domains. [PR #194991](https://github.com/pytorch/pytorch/pull/194991) | [Landed on main](https://github.com/pytorch/pytorch/commit/7b4f739ae84d496739c2a73f8da95e8e829fd5cc) |

#### Ongoing contributions

These pull requests are open and have not landed upstream as of September 29, 2026.

- **CUTLASS:** fix block-scaled GEMV K bounds and scalar tails, with stage-boundary and batch-isolation regressions. [#3567](https://github.com/NVIDIA/cutlass/pull/3567)
- **PyTorch / CUDA:** make expandable-segment IPC handles deterministic and cache IPC mappings per device. [#198990](https://github.com/pytorch/pytorch/pull/198990)
- **ONNX Runtime:** support independent quantization types and precision on CPU. [QuantizeLinear #32735](https://github.com/microsoft/onnxruntime/pull/32735) · [DequantizeLinear #32728](https://github.com/microsoft/onnxruntime/pull/32728)

#### Achievements

- **Kaggle Silver Medal** — AI Agent Security: Multi-Step Tool Attacks — **90 / 4,251**

#### Featured project

- [**thermal-face-analysis**](https://github.com/TANGBUDU/thermal-face-analysis) — thermal facial alignment & landmark detection.

