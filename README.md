# tall.language.models.v2

UDPipe 2 language models (Universal Dependencies 2.17) re-packaged as per-model
archives for the TALL desktop app, plus the shared mBERT TF checkpoint.

- Source: [LINDAT/CLARIAH-CZ](http://hdl.handle.net/11234/1-6046) — Straka (2025),
  Universal Dependencies 2.17 models for UDPipe 2.
- **License: CC BY-NC-SA 4.0** (non-commercial). mBERT: Apache-2.0
  ([google-bert/bert-base-multilingual-uncased](https://huggingface.co/google-bert/bert-base-multilingual-uncased)).
- Distribution: GitHub Release assets, one `tar.gz` per model directory +
  `models.json` manifest (name, treebanks, sha256, size, per-treebank accuracy).
- Consumed by the TALL engine model manager (download on demand, checksum
  verification, license notice on first use). Models are never bundled in
  TALL installers.
