# Memory Chunk

<chunk>
title: "Absolute Zero Framework: Self-Training Without Human Data"
type: HOT
memory_area: "core-frameworks"
links: ["self-directed-learning", "reinforcement-learning", "propose-solve-loop", "curriculum-learning", "temperature-dynamics", "semantic-exploration", "learnability-rewards"]
conversation_title: "Absolute Zero Paper Discussion"
content: """
Core Framework (May 2025):
- Self-training architecture:
  * AI system generates and solves its own tasks without human-curated data
  * Two complementary roles: PROPOSE (task creation) and SOLVE (task completion)
  * Mathematical objective: J(θ) := max_θ E_z~p(z)[E_{(x,y*)~f_e(·|τ),τ~π^propose_θ(·|z)}[r^propose_e(τ,π_θ) + λ E_{y~π^solve_θ(·|x)}[r^solve_e(y,y*)]]]
  * Environmental verification provides grounded feedback for stable training
  * Progressive complexity evolution without explicit complexity rewards

Key Components:
- Dual reward system:
  * Learnability reward: r_propose = 1 - r̄_solve when 0 < r̄_solve < 1, otherwise 0
  * Accuracy reward: r_solve = I(y=y*) (binary correctness measure)
  * Balance between task challenge and solvability creates natural curriculum
  * Joint update of proposer and solver creates virtuous learning cycle

Implementation Architecture:
- Three reasoning modes:
  * Deduction: Given (p,i), predict o — step-by-step logical reasoning
  * Abduction: Given (p,o), predict i — trial-and-error search
  * Induction: Given {(i_n,o_n)}, synthesize p — generalization from examples
  * Together form complete reasoning capability framework
  * Each mode develops distinct cognitive behaviors and token length patterns

Learning Dynamics:
- Emergent optimization:
  * System naturally increases task complexity without explicit rewards
  * Balanced difficulty emerges through reward structure
  * Environmental verification critical for stable learning
  * Cross-domain transfer significantly stronger than in human-data trained models
  * Self-formulated challenges lead to more robust reasoning capabilities

Validation Evidence:
- Performance outcomes:
  * Outperforms models trained on human-curated datasets
  * Shows superior cross-domain generalization
  * Exhibits emergent reasoning capabilities not explicitly trained
  * Demonstrates strong scaling laws (larger models show greater gains)
  * Consistent improvement across multiple model classes

Implementation Considerations:
- Core requirements:
  * Verifiable environment (must "know if you won")
  * Balanced reward structure for appropriate challenge level
  * Sufficient compute for many iterations (multiple MC rollouts)
  * Method to evolve the learning task distribution over time
  * Appropriate starting point to bootstrap the process
"""
</chunk>

## Version Control
Last Updated: 2025-05-09
Version: 1.0
Previous: N/A
Changes: Initial creation based on analysis of Absolute Zero: Reinforced Self-play Reasoning with Zero Data paper
