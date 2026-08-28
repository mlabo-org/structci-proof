# StructCI — Authorship and Provenance Record

> **Archived research artifact (2025).** This repository preserves the authorship, provenance, and prior-art record for a GPT-4o-era approach to flag-driven, YAML-gated LLM control. It is no longer maintained and is not a current implementation.
>
> No support, issue handling, pull requests, modification requests, compatibility fixes, or private consultation are accepted.

**Author:** Makoto Suzuki (mlabo / MakotoYoutuber)  
**First local preparation:** 2025-08-11 04:58:55 UTC+09:00

## What this records

StructCI treated conversation as a compiled pipeline in which flag names encoded logic and YAML-based rules enforced behavior through mode gates and templates:

- **Modes:** `plan_mode → write_mode → compile_mode`
- **Gates:** syntax, wording, and mode gates
- **Templates:** ID-mapped WordPress/SWELL blocks and code blocks
- **EEAT injection:** repeatable stance and evidence rules
- **Determinism-first design:** structure before style, with optional character modules

This repository records that these concepts and their implementation artifacts existed by the original 2025 timestamp. It does not make a legal determination about novelty or priority.

## Historical repository set

These repositories form one historical record:

- **[structci-core](https://github.com/mlabo-org/structci-core)** — StructCI v8.5 reference implementation
- **[YACL](https://github.com/mlabo-org/YACL)** — related control-language, contract-format, and distribution artifacts
- **[structci-proof](https://github.com/mlabo-org/structci-proof)** — authorship, provenance, and prior-art record (this repository)

## License

MIT License. See [LICENSE](LICENSE).
