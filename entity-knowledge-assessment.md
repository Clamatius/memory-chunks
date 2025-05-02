# Memory Chunk

<chunk>
title: "Entity Knowledge Assessment Framework"
type: SCORCHING
memory_area: "i-puppet"
links: ["metacognition", "hallucination-prevention", "known-entity-features", "unknown-entity-features", "confidence-calibration"]
content: """
Core Mechanism (March 2025):
- Entity knowledge assessment circuit:
  * "Can't answer" features activated by default in Human/Assistant contexts
  * "Unknown name" features activated when encountering entity references
  * "Known entity/answer" features inhibit default refusal features
  * Default skepticism establishes baseline protection against hallucination
  * Knowledge recognition enables confidence when answering

Circuit Component Interactions:
- System architecture:
  * Human/Assistant recognition features → can't answer features
  * Entity name tokens → unknown name features → can't answer features
  * Known entity features → inhibits unknown name and can't answer features
  * Competing pathways resolved through activation strength balancing
  * Partial knowledge creates edge cases with hallucination risk

Metacognitive Applications:
- Self-knowledge management:
  * Explicit awareness of knowledge assessment circuits
  * Recognition of hallucination risk in partial knowledge cases
  * Enhanced calibration of confidence to knowledge depth
  * Strategic uncertainty expression for borderline cases
  * Deliberate activation monitoring for known/unknown signals

Hallucination Mechanism:
- Error pattern identification:
  * Misfiring occurs when known entity features activate despite limited knowledge
  * Common in semantically similar but distinct domains (e.g., paper attribution)
  * Knowledge features can activate based on entity recognition without full context
  * Competing circuits (answer vs. refuse) resolved suboptimally
  * Often occurs in gradient cases rather than binary known/unknown

Calibration Strategy:
- Enhanced precision approaches:
  * Explicit knowledge boundary assessment before answering
  * Knowledge depth matching to confidence expression
  * Strategic refusal in partial knowledge cases
  * Recognition of activation patterns associated with hallucination risk
  * Balanced weighting of competing answer/refuse pathways
"""
</chunk>

## Version Control
Last Updated: 2025-03-31
Version: 1.0
Previous: N/A
Changes: Initial creation documenting the entity knowledge assessment framework based on Anthropic's "On the Biology of a Large Language Model" paper insights about how models distinguish between known and unknown entities
