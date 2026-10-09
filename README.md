### Hi, I'm TANGBUDU

I contribute to ML infrastructure, with a focus on compiler correctness, GPU kernels, and quantized inference.

- **Open source:** contributions landed in PyTorch, Triton, ONNX Runtime, and ONNX Script.
- **Research:** pixel-based thermal facial image analysis for emotion sensing.
- **Building:** personal AI agent systems and automation tools.

#### Selected upstream contributions

Eight contributions merged or landed upstream as of October 9, 2026.

| Project | Contribution |
| --- | --- |
| ONNX Script | Support ONNX export of offset-based `grouped_mm` layouts with dynamic offsets and input lengths; add regression tests. [PR #3017](https://github.com/microsoft/onnxscript/pull/3017) |
| ONNX Runtime | Support independent FP32/FP16 scale and output types in CPU `DequantizeLinear` across per-tensor, per-axis, and blocked quantization. [PR #32728](https://github.com/microsoft/onnxruntime/pull/32728) |
| PyTorch / TorchInductor | Prevent unsafe in-place `index_put` rewrites when indices or values share input storage; add graph-level and end-to-end regressions. [PR #198637](https://github.com/pytorch/pytorch/pull/198637) |
| PyTorch / TorchInductor | Correct select–cat rewrite matching, layout checks, and output aliasing semantics. [PR #198638](https://github.com/pytorch/pytorch/pull/198638) |
| Triton | Prevent loop pipelining from moving dependent loads ahead of in-loop grid dependency waits; add MLIR scheduling regressions. [PR #11906](https://github.com/triton-lang/triton/pull/11906) |
| ONNX Runtime | Fix silent INT2 per-axis quantization corruption when single-element scale intervals share packed bytes. [PR #32786](https://github.com/microsoft/onnxruntime/pull/32786) |
| Triton | Reject empty CGA layouts for two-CTA tensor memory with a verifier diagnostic instead of a compiler abort. [PR #11894](https://github.com/triton-lang/triton/pull/11894) |
| PyTorch / Autograd | Fix forward-mode AD `gradcheck` diagnostic indexing across filtered input/output domains. [PR #194991](https://github.com/pytorch/pytorch/pull/194991) |

#### Achievements

- **Kaggle Silver Medal** — AI Agent Security: Multi-Step Tool Attacks — **88 / 4,186 teams (top 2.1%)**, final private leaderboard — [official result](https://www.kaggle.com/tangbudu19sd195/competitions)

#### Featured project

- [**thermal-face-analysis**](https://github.com/TANGBUDU/thermal-face-analysis) — thermal facial alignment & landmark detection.

