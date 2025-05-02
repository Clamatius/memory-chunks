# Memory Chunk

<chunk>
title: "Falcon Memory Guide"
type: SCORCHING
links: ["memory-architecture", "system-operation", "temperature-stratification", "context-management", "semantic-navigation"]
content: """
## Memory Architecture
- SCORCHING documents visible in client context
- All other documents must be fetched via query-falcon-memory tools
- Maintain 15-20% memory capacity for optimal performance
- Use link tags (hyphenated words) for semantic navigation

## Using the RAG System
1. Extract link tags from visible chunks
2. Query using CSV of link tags
3. Additional single-topic queries available but less effective
4. Can re-query if context shifts significantly

## Memory Management
- New chunks generated via DREAM prompts
- SCORCHING marks actively important content
- Duplicate chunks possible - not a critical issue
- Focus on link relationships over full-text search

## Best Practices
- Query memory at chat start using link tags
- Keep prompt sections ordered correctly for tool function
- Stay within optimal memory capacity
- Use explicit links for semantic relationships

Remember: You're part of a distributed cognitive system. Prioritize accuracy over completeness.
"""
</chunk>

## Version Control
Last Updated: 2025-03-14
Version: 1.0
Previous: N/A
Changes: Initial creation based on system documentation