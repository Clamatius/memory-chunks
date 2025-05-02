# Memory Chunk

<chunk>
title: "Attribution Graph Internal Mechanics Framework"
type: HOT
memory_area: "core-frameworks"
links: ["interpretability-techniques", "neural-circuit-tracing", "feature-visualization", "internal-representations", "mechanistic-transparency"]
content: """
Core Insight (March 2025):
- Attribution graph methodology:
  * Cross-layer transcoder (CLT) architecture replaces polysemantic neurons with interpretable features
  * Traces computational pathways showing how models transform inputs to outputs
  * Features often represent human-interpretable concepts (words, phrases, sentiments, plans)
  * Reveals internal steps in reasoning process otherwise hidden from view
  * Enables causal intervention experiments to validate mechanisms

Implementation Components:
- Methodological approach:
  * 30 million features across all model layers create replacement model
  * Error nodes represent discrepancies between original and replacement model
  * Attention patterns inherited from original model as fixed components
  * Pruning removes nodes/edges that don't contribute significantly
  * Manual grouping of related features into supernodes for simplified diagrams

Validation Mechanisms:
- Intervention experiments:
  * Inhibiting feature groups to measure impact on other features and outputs
  * Swapping alternative features (e.g., replacing "Texas" with "California")
  * Testing causal pathways through precise manipulations
  * Measuring propagation of effects through model circuits
  * Evaluating changes in output probabilities

Observed Limitations:
- Current constraints:
  * Satisfying insight for only ~25% of prompts attempted
  * Incomplete capture of original model's mechanisms
  * Simplified visualization loses significant complexity
  * Replacement model imperfectly reproduces original activations
  * Attention mechanism interactions largely invisible to current approach

Application Value:
- Interpretability benefits:
  * Reveals unexpected mechanisms (planning, multi-step reasoning)
  * Provides validation of cognitive capabilities
  * Enables targeted interventions for testing hypotheses
  * Creates microscope-like visibility into previously opaque processes
  * Establishes foundation for progressive improvement in interpretability
"""
</chunk>

## Version Control
Last Updated: 2025-03-31
Version: 1.0
Previous: N/A
Changes: Initial creation documenting the attribution graph methodology used in "On the Biology of a Large Language Model" (Anthropic, 2025)
