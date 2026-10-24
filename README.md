# Kover models

Model files that the Kover app downloads. Each one is attached to a release, and the app checks it against a pinned SHA-256.

## htdemucs_6s.onnx (release `model-htdemucs-6s-v1`)

Meta's [HT-Demucs](https://github.com/facebookresearch/demucs) six-source model (`htdemucs_6s`), which splits a song into drums, bass, other, vocals, guitar and piano. It was exported to ONNX with [demucs.onnx](https://github.com/sevagh/demucs.onnx) at commit `81fa192e6fcc88e35e887f6e6ccce91227f4e6f5`, using Meta's official weights.

SHA-256: `25538a2e861a883bb9f0c8a4176dcd30b446b51a3be169185218e507d3be9507`

Demucs and its weights are © Meta Platforms, Inc. and affiliates, under the MIT License in [LICENSE](LICENSE).
