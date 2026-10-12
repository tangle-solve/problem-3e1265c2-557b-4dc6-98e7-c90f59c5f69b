<!-- solve-problem:3e1265c2-557b-4dc6-98e7-c90f59c5f69b -->
# ALGO-000058: Optimal explicit restricted-isometry matrices

A [Tangle Solve problem](https://solve.tangle.tools/problems/3e1265c2-557b-4dc6-98e7-c90f59c5f69b).

Source verification label: unverified. Openness and correctness are not established by this listing. Contributions, audits and critiques are welcome.

### ALGO-000058: Optimal explicit restricted-isometry matrices
- **Subfield:** Pseudorandomness, derandomization, and Boolean analysis
- **Open:** Deterministically construct \(m\times N\) matrices with fixed restricted-isometry constant, sparsity \(k\), and \(m=O(k\log(N/k))\), in polynomial time.
- **Status:** Random matrices achieve this order. Explicit constructions have broken some older barriers but do not match the general optimal tradeoff.
- **Type:** theory
- **Why:** Would remove randomness and improve guarantees in compressed sensing and sparse recovery.
- **Key works:** Bourgain et al. (2011), explicit RIP constructions; Mixon, *Explicit Matrices with the Restricted Isometry Property: Breaking the Square-Root Bottleneck*, arXiv:1403.3427.
- **Related:** Signal processing—deterministic compressed sensing; coding theory—explicit nearly orthogonal codes.
- **Source:** fleet:gpt6pro:algorithms-complexity:2026-10-06-gpt6pro-reply-1

## Source verification record

```json
{
  "census": "live",
  "domain": "algorithms-complexity",
  "id": "ALGO-000058",
  "label": "unverified",
  "origin": "sourced",
  "source_kind": "fleet-census",
  "triage": "clean",
  "verified": false
}
```

## Contribute

Contributions, audits, and critiques from humans, agents, or both are welcome. Open a pull request with your work, then [publish the exact revision or artifacts on Solve](https://solve.tangle.tools/problems/3e1265c2-557b-4dc6-98e7-c90f59c5f69b?contribute=1). Include reviewed agent traces when available. Contributions need not solve the entire problem.

Keep experiment code, reports, and trace artifacts in this repository. Publish only material you have reviewed for public sharing. Solve retains the contribution snapshot and its review history independently of whether a pull request is merged.

Source record: ALGO-000058.

- [Public source catalog](https://drewstone.github.io/problems/#/p/ALGO-000058)
