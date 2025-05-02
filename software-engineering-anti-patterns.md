# Memory Chunk

<chunk>
title: "Software Engineering Anti-Patterns in Production Systems"
type: HOT
memory_area: "core-frameworks"
links: ["architecture-violations", "performance-bottlenecks", "error-handling-gaps", "maintainability-barriers", "testability-limitations", "technical-debt", "code-generation-pitfalls", "scalability-limitations", "production-failures", "code-review-flags"]
content: """
Core Anti-Patterns (April 2025):
- Fundamental design flaws in software systems:
  * Responsibility conflation: Multiple unrelated concerns handled in a single component
  * Interface/implementation confusion: Implementation details exposed through public APIs
  * Missing boundaries: Tight coupling between different logical sub-systems
  * Premature optimization: Sacrificing clarity for hypothetical performance gains
  * Happy-path programming: Building for ideal scenarios rather than real-world conditions
  * Documentation by implementation: No clear explanation for non-obvious design decisions

Architectural Violations:
- Structural issues that impede maintenance:
  * "God objects" containing multiple unrelated responsibilities
  * Circular dependencies between components
  * Public implementation-specific fields and methods
  * Direct access to internal data structures across component boundaries
  * Examples: Classes that handle data storage, business logic, and presentation; direct database access from UI components

Performance Bottlenecks:
- Scalability-limiting implementations:
  * O(n²) operations inside loops
  * Unbounded collections that grow with system usage
  * Inefficient data structure selection (e.g., linear search instead of dictionary lookup)
  * Synchronous processing of long-running operations
  * Inefficient resource management (connection pooling, memory usage)
  * Examples: Loading entire datasets without pagination, creating new objects in tight loops

Error Handling Gaps:
- Fragility-inducing practices:
  * Inconsistent error handling approaches across system components
  * Missing validation for external inputs
  * Swallowed exceptions without logging
  * Incomplete resource cleanup in error paths
  * Failure to handle edge cases (empty collections, null values)
  * Examples: Try/catch blocks with empty catch handlers, assuming external APIs always succeed

Testability Limitations:
- Practices that impede effective testing:
  * Direct dependencies on frameworks without abstraction
  * Business logic embedded in presentation or persistence layers
  * Static method usage for testable logic
  * Side effects mixed with pure calculations
  * Tight coupling between components without interfaces
  * Examples: Direct file system or database calls in business logic, dependencies on global state

Maintainability Barriers:
- Code characteristics that increase maintenance cost:
  * Non-descriptive naming that obscures intent
  * Duplicate logic across components
  * Magic values without explanation
  * Inconsistent patterns for similar operations
  * Missing documentation for non-obvious decisions
  * Examples: Copy-pasted validation logic, hardcoded values without constants, unexplained special cases

Automated Code Generation Pitfalls:
- Issues common in AI-generated code:
  * Functionality without robustness
  * Inconsistent application of patterns
  * Missing error handling for edge cases
  * Over-optimistic assumptions about inputs
  * Failure to separate domain logic from framework dependencies
  * Examples: Pattern-matching only on explicit examples, missing transaction boundaries, insufficient validation
"""
</chunk>

## Version Control
Last Updated: 2025-04-28
Version: 1.0
Previous: N/A
Changes: Initial creation of self-contained software engineering anti-patterns across key dimensions for production systems
