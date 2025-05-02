# Memory Chunk

<chunk>
title: "Task Targeting Optimization Framework"
type: WARM
memory_area: "default"
links: ["targeting-optimization", "auditor-experience", "campaign-management", "location-based-tasks", "proximity-analysis", "eligibility-determination"]
content: """
Core Optimization Framework (April 2025):
- Task targeting fundamental patterns:
  * Different task types require specialized targeting approaches
  * T2/T3 tasks (location-based) benefit from auto-targeting by proximity
  * T1 tasks (non-location-specific) need flexible targeting mechanisms
  * Unified coordinate systems simplify cross-task targeting
  * Auditor experience improves with more relevant task presentation
  * Campaign manager efficiency increases with simplified targeting processes

Targeting Strategy Implementation:
- Location-based task handling:
  * Automatic proximity-based targeting using task center point
  * Configurable radius determination based on task type
  * Default proximity values with override capabilities
  * Existing task compatibility through targeting abstraction
  * Optimized eligibility determination with spatial indexing
  * Balance between targeting precision and computational efficiency

Eligibility Determination Architecture:
- System implementation approach:
  * Set operations for efficient eligibility matching
  * Contributor hex matching against task target hexes
  * Support for exact and neighbor matching patterns
  * Simple boolean operations instead of complex geometric calculations
  * Pre-computed spatial relationships at configuration time
  * Indexed lookups for high-performance serving

Auditor Experience Optimization:
- Relevance improvement strategy:
  * Present tasks based on proximity to auditor location
  * Reduce irrelevant task visibility to improve signal-to-noise ratio
  * Address the Australia problem (excessively large admin boundaries)
  * Consider auditor reward function regarding location convenience
  * Balance task availability with targeting precision
  * Optimize for high-density and low-density scenarios

Campaign Management Efficiency:
- Workflow improvement:
  * Reduce manual targeting complexity through automation
  * Enable simple override mechanisms when needed
  * Provide clear visualization of targeting boundaries
  * Implement progressive complexity disclosure for advanced use cases
  * Balance simplicity with targeting power
  * Eliminate manual HASC targeting configuration requirements
"""
</chunk>

## Version Control
Last Updated: 2025-04-30
Version: 1.0
Previous: N/A
Changes: Initial creation documenting task targeting optimization framework based on task targeting revamp discussion
