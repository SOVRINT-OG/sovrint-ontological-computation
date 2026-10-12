# Research Program: Ontological Computation

**Status:** Proposed agenda for a documented draft. This file records questions and planned checks; it does not establish a completed ontology, theorem, implementation, or independent validation. The repository status remains authoritative in [RESEARCH_STATUS.yaml](./RESEARCH_STATUS.yaml).

## Scope

The README identifies entities, relations, states, transitions, constraints, observations, and corrections as candidate structural objects. This program studies whether selected public concepts can be defined and mapped consistently. Mapping to an existing ontology language is a translation exercise; it does not establish equivalence with SOVRINT formalisms.

## Questions

1. Can the public glossary define each primitive with examples, exclusions, and explicit relationships to neighboring terms?
2. Can a small public subset be represented in OWL 2 without changing the meaning of SOVRINT source terms?
3. Which competency questions distinguish a useful model from a vocabulary list?
4. Can deliberately inconsistent synthetic examples be detected and traced to conflicting assertions?
5. Which claims remain conceptual, and which have executable checks or independent evidence?

## Planned work

- Create a source-linked glossary; preserve terms and symbols as recorded in their source.
- Select a small synthetic example and document assumptions, entity identifiers, relations, and expected answers.
- Record OWL 2 mappings as crosswalks with source term, target construct, rationale, and known loss or ambiguity.
- Add consistency and competency-question fixtures only after definitions are stable.
- Record test results with tool/version, fixture hash, date, and limitations.

## Evidence and release gates

Keep literature background, proposed definitions, formal models, software checks, and empirical findings as separate evidence classes. A passing reasoner or schema check establishes only that the tested artifact satisfies that check; it does not validate the underlying theory. Do not publish protected equations, private datasets, credentials, or unpublished engine internals.

Before calling a component validated, publish its source map, explicit model boundaries, reproducible fixture, independent review record, and result limitations. Until those gates are met, describe it as a draft.

## References

- W3C, [OWL 2 Web Ontology Language Primer, Second Edition](https://www.w3.org/TR/owl-primer/) (W3C Recommendation, 11 December 2012). Technical reference for OWL 2, not endorsement or validation of this project.
- [Repository README](./README.md) for the project's stated scope and boundaries.
- [Research Validation Layer](https://github.com/SOVRINT-OG/sovrint-research-validation-layer) for separate synthetic-validation and schema context. Its tests do not validate this repository's theory.
