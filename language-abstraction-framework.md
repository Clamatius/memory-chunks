# Memory Chunk

<chunk>
title: "Language Abstraction Framework"
type: HOT
memory_area: "core-frameworks"
links: ["cross-lingual-representation", "language-independent-circuits", "language-specific-circuits", "multilingual-feature-activation", "re-tokenization-model"]
content: """
Core Insight (March 2025):
- Language representation architecture:
  * Middle layers develop language-agnostic representations of concepts
  * Early and late layers more language-specific (tokenization/de-tokenization)
  * Computation separated into operand, operation, and language components
  * English maintains privileged position as "default" language
  * Language-specific and language-independent circuits interact systematically

Evidence Validation:
- Multilingual capability testing:
  * Same core multilingual features active across languages (English, French, Chinese)
  * Language-independent antonym features connect "small" to "large" across languages
  * Language-specific quote features guide appropriate output language
  * Feature overlap between languages increases in middle layers
  * Language generalization improves with model scale

Operational Components:
- Computation separation:
  * Operation (e.g., antonym function) primarily language-independent
  * Operand (e.g., "small" concept) primarily language-independent
  * Language detection primarily controls output language choice
  * Operations can be independently manipulated without language knowledge
  * Same abstract circuits reused across language boundaries

Implementation Mechanics:
- Cross-lingual architecture:
  * Early layers: Language-specific token processing (85-95% language-specific)
  * Middle layers: Abstract conceptual processing (40-60% language-specific)
  * Later layers: Language-specific output mapping (75-85% language-specific)
  * Consistent with detokenization → abstract processing → retokenization model
  * Same mechanisms extend to distantly related languages (non-shared alphabets)

Default Language Phenomena:
- English-privileged mechanisms:
  * Multilingual features often have stronger direct weights to English outputs
  * Non-English outputs more strongly mediated by language-specific features
  * English quote features show unique double inhibitory patterns
  * Pattern is "multilingual representation with English as default output"
  * Confirms hybrid model of language representation (neither fully independent nor English-centric)
"""
</chunk>

## Version Control
Last Updated: 2025-03-31
Version: 1.0
Previous: N/A
Changes: Initial creation documenting language abstraction framework based on Anthropic's "On the Biology of a Large Language Model" paper findings about multilingual circuits
