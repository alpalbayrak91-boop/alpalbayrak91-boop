# Alp Albayrak — AlpLab Research

Independent researcher and builder working on **formal verification (Lean 4)**, **deterministic AI-agent auditing & memory architectures**, **computational extremal combinatorics (Erdős problems)**, and **zero-dependency verification tools**.

---

## Published Open-Source Tools & Formal Research (`MIT`)

| Project | Focus | Latest Release / Proof |
|---|---|---|
| [**ProofGate**](https://github.com/alpalbayrak91-boop/proofgate) ([Live Studio](https://alpalbayrak91-boop.github.io/proofgate/)) | Lean 4 specification-faithfulness gate, static Python AST sandbox verifier, RFC 8785 JCS + RFC 6962 Merkle receipts | [`v0.2.0`](https://github.com/alpalbayrak91-boop/proofgate/releases/tag/v0.2.0) · Empirical paper (`docs/PROOFGATE_PAPER.md`) · 22 Lean 4.35 theorems (`0 sorry`) |
| [**Erdős Small Values**](https://github.com/alpalbayrak91-boop/erdos-kucuk-degerler) | Exact small values, CP-SAT / C / Z3 CEGAR certified witnesses, and Lean 4 audits for Erdős problems `#600`, `#642`, `#934`, `#983` & OEIS `A032766`/`A380408` | [`v1.1.0`](https://github.com/alpalbayrak91-boop/erdos-kucuk-degerler/releases/tag/v1.1.0) · Zenodo DOI [`10.5281/zenodo.24457110`](https://doi.org/10.5281/zenodo.24457110) · OEIS draft [`A400028`](https://oeis.org/draft/A400028) |
| [**temporal-gaba-memory**](https://github.com/alpalbayrak91-boop/temporal-gaba-memory) | Temporal-Causal GABA inhibitory negative-knowledge gating & corpus-centered 3-channel Bochner-PSD RBF Vendi re-ranking for long-horizon AI agents | [`v0.1.0`](https://github.com/alpalbayrak91-boop/temporal-gaba-memory/releases/tag/v0.1.0) · Technical paper (`docs/PAPER.md`) · 22 companion Lean 4.35 theorems (`0 sorry`) |
| [**leakspec-cli**](https://github.com/alpalbayrak91-boop/leakspec-cli) | Zero-dependency 4-layer spectral causality lookahead-leakage CI/CD auditor (SARIF + JSON) for time-series models, quant backtests, and ML feature stores | [`v0.1.0`](https://github.com/alpalbayrak91-boop/leakspec-cli/releases/tag/v0.1.0) · Pure Python 3.10+ · `5/5` recall / `0/5` FP benchmark |

---

## Upstream Open-Mathematics Contributions

- [`google-deepmind/formal-conjectures#8289`](https://github.com/google-deepmind/formal-conjectures/pull/8289) — Formalization of **Erdős Problem #117** (abelian subgroup covers), CLA verified (`OPEN`, awaiting review)
- [`google-deepmind/formal-conjectures#8295`](https://github.com/google-deepmind/formal-conjectures/pull/8295) — Cycle-chord bounds and exact values `f(n)` for `n <= 5` on **Erdős Problem #642**, CLA verified (`OPEN`, awaiting review)

---

## Research Standards & Transparency

- **Zero-dependency reproducibility:** All core verification libraries are Pure Python 3.10+ standard library and/or Init-only Lean 4 (`--trust=0`, `0 sorry`, standard kernel axioms only).
- **AI-assisted workflow disclosure:** Computations, proof drafts, and engineering harnesses are developed with multi-model AI assistance under independent cross-model verification and deterministic test suites; final responsibility and verification rest with Alp Albayrak.
