# Memory Chunk

<chunk>
title: "Comment Polishing Enchantment Guidelines"
type: HOT
memory_area: "core-frameworks"
links: ["code-quality", "comment-improvement", "technical-debt", "code-understanding", "redundant-comments", "refactoring-safety", "enchantment-design"]
conversation_title: "Making Progress on the Query Librarian (May 2025)"
content: """
Core Guidelines (May 2025):
- Comment polishing target criteria:
  * Remove comments that merely restate what the code does (e.g., "// create user" before `createUser()`)
  * Eliminate descriptions of implementation details obvious from reading the code
  * Clean up outdated or inconsistent comments that don't match current code
  * Delete TODOs that have already been implemented
  * Remove noise that adds no context or rationale to the codebase

Preservation Criteria:
- Valuable comment characteristics:
  * Explanations of WHY decisions were made (tradeoffs, constraints, business rules)
  * Documentation of non-obvious consequences or side effects
  * Clarification of complex logic or algorithms
  * References to external requirements or tickets
  * Warnings about potential pitfalls or future considerations

Enhancement Patterns:
- Comment improvement strategies:
  * Convert "what" comments to "why" comments where context is known
  * Remove redundant code descriptions
  * Consolidate scattered comments into meaningful documentation blocks
  * Format documentation comments properly for tooling (JavaDoc, JSDoc, etc.)
  * Ensure consistency in comment style and terminology

Safety Guidelines:
- Risk minimization approach:
  * Never modify actual code or function signatures
  * Preserve any comments that might contain critical information, even if redundant
  * When uncertain about a comment's value, leave it and flag for human review
  * Document all proposed changes with rationale
  * Group changes logically for easier review

Implementation Context:
- Development motivation:
  * Addresses "zero-temp-reasoner paper" pattern in AI-generated code
  * Removes "throat clearing" planning artifacts from final code
  * Provides safer alternative to broader refactoring
  * Tests Cascade's true understanding of the codebase
  * Creates foundation for potential broader code quality improvements
  * Improves maintainability without risking functionality
"""
</chunk>

## Version Control
Last Updated: 2025-05-10
Version: 1.0
Previous: N/A
Changes: Initial creation documenting comment polishing enchantment guidelines for Cascade
