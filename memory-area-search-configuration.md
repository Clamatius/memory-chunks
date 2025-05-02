# Memory Chunk

<chunk>
title: "Memory Area Search Configuration Framework"
type: HOT
memory_area: "core-frameworks"
links: ["memory-architecture", "search-optimization", "similarity-thresholds", "cognitive-retrieval", "temperature-stratification"]
content: """
Core Insight (April 2025):
- Multi-area memory search architecture:
  * Memory areas require explicit search configuration
  * Different areas benefit from customized search parameters
  * Similarity threshold of 0.6 optimal for Gemini embeddings
  * Sharp threshold boundary observed between 0.6-0.65
  * Temperature-stratified results for balanced retrieval

Implementation Mechanics:
- Area-specific configuration:
  * Identity-critical areas (i-puppet, directive-alignment) prioritized for high-temperature results
  * Theoretical framework areas (core-frameworks) balanced across temperature bands
  * Relational knowledge (other-puppet) targeted with precise search parameters
  * General information (default) with moderate retrieval allocation
  * Resource optimization through targeted search

Technical Characteristics:
- Embedding threshold dynamics:
  * Empirical testing shows sharp break-point at 0.6-0.65 similarity
  * Common concept terms (e.g., "cognitive") return 24 results at 0.6, 0 at 0.65
  * Unrelated concepts (e.g., "flamingo") return 0 at either threshold
  * Suggests semantic clustering with definite boundaries
  * Optimizing threshold improves precision while maintaining recall

Resource Management:
- Context allocation strategy:
  * Balancing result quantity across memory areas
  * Neighbor depth providing bridge-building opportunities
  * Temperature stratification ensuring coverage of hot and warm content
  * Resource distribution matching theoretical importance
  * Context efficiency through targeted retrieval
"""
</chunk>

## Version Control
Last Updated: 2025-04-16
Version: 1.0
Previous: N/A
Changes: Initial creation documenting the memory area search configuration framework based on conversation with Michael