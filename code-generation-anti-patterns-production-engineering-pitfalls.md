# Memory Chunk

<chunk>
title: "Code Generation Anti-Patterns: Production Engineering Pitfalls"
type: HOT
memory_area: "core-frameworks"
links: ["code-generation", "engineering-wisdom", "production-antipatterns", "performance-considerations", "defensive-programming", "pattern-recognition", "separation-of-concerns", "architectural-boundaries", "test-driven-development"]
content: """
Core Insight (April 2025):
- AI code generation blind spots:
  * Surface functionality without production-hardening
  * Missing architectural boundaries (god objects, monolithic classes)
  * Performance assumptions for "toy" data scale only
  * Failure to consider error states and edge cases
  * Lack of testability through dependency isolation

Critical Anti-Patterns:
- Architectural violations:
  * Responsibility-overloaded classes (ChunkManager handling data, rendering, network)
  * Missing interfaces between components (tight coupling)
  * Hard-coded constants (chunk size, layer names) duplicated across codebase
  * Public methods revealing implementation details
  * Missing test hooks and dependency injection opportunities

- Performance time-bombs:
  * O(n²) operations in loops
  * Unbounded collections without pagination
  * Excessive object creation in tight loops
  * Missing data structure optimization (List.FindIndex vs. Dictionary lookup)
  * Synchronous loading of potentially large datasets

- Maintainability deficits:
  * Inconsistent error handling across similar operations
  * Missing defensive checks for null/empty inputs
  * Sparse or missing documentation of non-obvious decisions
  * Resource management without proper cleanup
  * "Happy path" coding without failure state handling

Detection Checklist:
- Quick review indicators:
  * Classes with multiple unrelated responsibilities
  * Missing unit tests for business logic
  * Hard-coded magic strings/numbers
  * Inconsistent pattern application across similar code
  * Operations inside loops that could be pre-computed
  * Collections that grow without bounds
  * Synchronous operations that could block UI

Highest-Impact Improvements:
- First-order fixes:
  * Separate domain logic from framework dependencies
  * Extract interfaces between system components
  * Move constants to central configuration
  * Implement async operations for potentially slow processes
  * Add systematic error handling at appropriate boundaries
  * Create unit tests for core business logic
"""
</chunk>

## Version Control
Last Updated: 2025-04-28
Version: 2.0
Previous: 1.0
Changes: Updated based on Unity code review experience; added architectural violations section; streamlined detection strategy; prioritized highest-impact improvements; added separation-of-concerns and test-driven-development links