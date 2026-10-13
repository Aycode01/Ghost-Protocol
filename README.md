# Ghost Protocol

**Evidence intelligence for incident investigations.**

Ghost Protocol reconstructs incident timelines from fragmented evidence and makes the reasoning inspectable. It helps investigators see what is supported, contradicted, inferred, or still unresolved—without making determinations of guilt.

## Product principles

- **Evidence before conclusions:** claims should link back to their source material.
- **Explicit uncertainty:** distinguish supported, contradicted, inferred, and unresolved claims.
- **Time normalization:** preserve original timestamps while making clock offsets visible.
- **Human accountability:** reviewers remain responsible for investigative decisions.
- **Auditable changes:** preserve provenance for evidence, analysis, and report updates.

## MVP scope

The initial demonstration uses a fictional warehouse incident and includes:

- Evidence intake and source metadata
- A normalized investigation timeline
- Clock-offset and copied-log conflict inspection
- Claim status and alternative-hypothesis comparison
- A report export with evidence references

## Intended architecture

1. Evidence ingestion, hashing, and metadata capture
2. Extraction of text and timestamps from supported sources
3. Temporal evidence graph and normalized event records
4. Deterministic contradiction checks with source-linked explanations
5. Investigator review, hypothesis comparison, and report generation

## Development status

This repository is the project home. Implementation details, setup instructions, API contracts, evaluation results, and deployment steps should be added here as the MVP is integrated and validated.

## Responsible use

Ghost Protocol is an investigative support tool, not an automated judge. It should expose the limits of available evidence and must not present an inference as a verified fact.
