# Semantic Rules

## Repository Interpretation

The repository is interpreted as a semantic graph.

- directories define semantic regions
- files define semantic nodes
- links define inference edges
- commits define graph transitions

## Canonical Separation

Canonical knowledge must remain isolated from experimental reasoning.

Allowed flow:

EXPERIMENT -> VALIDATION -> CANONICAL

Forbidden flow:

CANONICAL -> uncontrolled mutation

## Naming Convention

Format:

[TYPE]-[NUMBER]_[slug].md

Examples:

AX-001_observer_invariance.md
CAN-003_entropy_stability.md
EXP-014_recursive_collapse.md

## Edge Semantics

Allowed edge types:

- derives_from
- stabilizes
- contradicts
- compresses
- expands
- depends_on
- maps_to
- resolves
- approximates

## Ontology Priority

Ontology definitions supersede note-level interpretations.

Ontology nodes are treated as semantic anchors.

## Memory Policy

The repository is optimized for:

- long-horizon retrieval
- semantic compression
- inference reconstruction
- topology-aware navigation
