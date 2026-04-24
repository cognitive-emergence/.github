# Contributing to Cognitive Emergence Lab

Thank you for considering a contribution. This organization maintains both mathematical theory and engineering protocols. The contribution path differs slightly.

## For Protocol Repositories (JEP, COE, HJS, JAC)

- **Core invariant**: The four primitives (J/D/T/V) do not change.
- **Extensions**: New industry mappings, privacy modules, or consensus policies are welcome.
- **Required for new extensions**:
  1. Markdown specification
  2. JSON Schema
  3. Example event(s)
  4. Update to verifier script if validation logic changes
- **Prohibited**: Legal compliance guarantees, vendor lock-in, governance hierarchy definitions.

## For Theory Repositories (Whitepaper, Causal Observability)

- **Scope**: Mathematical proofs, finite causal event models, determinability lemmas.
- **Welcome**: Proof corrections, missing citations, boundary clarifications, translation improvements.
- **Not welcome**: New axioms that break the finite framework without justification, overclaims beyond proof capacity in physics or law.

## For All Repositories

1. Open an Issue first. Describe the gap or error.
2. Fork and branch. Name your branch `fix/xxx` or `feat/xxx`.
3. Keep commits atomic. One logical change per commit.
4. Synchronize Chinese and English versions if applicable.
5. Submit PR with a clear description.

## License

- Specifications and papers: CC0 1.0 Universal
- Code and implementations: MIT or Apache 2.0 (see individual repositories)
