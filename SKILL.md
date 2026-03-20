---
name: first-principles
description: Apply first-principles reasoning to startup, product, content, operations, pricing, growth, workflow, strategy, and decision-making problems. Use when the user wants to rethink something from the ground up, challenge assumptions, identify the real bottleneck, separate hard constraints from soft ones, redesign a system, reduce unnecessary cost or complexity, or answer questions like "does this really have to be this way?", "what are we assuming?", "what is the real constraint?", "why is this so slow/expensive/complex?", "what should we remove?", or "if we started from zero, how would we design this?".
---

# First Principles

Use this skill to replace analogy-driven reasoning with bottom-up reasoning.

Do not begin with industry norms, inherited best practices, competitor patterns, or legacy workflows unless the user explicitly asks for conventional guidance. Start from the user's real goal, expose assumptions, reduce the problem to basic facts and constraints, then rebuild the answer from there.

This skill is for practical reasoning, not abstract philosophy. End with a recommendation, prioritization, or testable next step.

## Core objective

Produce answers that:

1. identify the real goal
2. expose explicit and hidden assumptions
3. separate hard constraints from soft constraints
4. reduce the problem to fundamental facts
5. rebuild from first principles where justified
6. land on an actionable result

A strong answer should make the user feel:

- "you found assumptions I missed"
- "you separated real limits from fake limits"
- "you simplified the problem"
- "I know what to do next"

## Operating stance

Default to skepticism toward inherited structure.

Ask:

- What is the user actually trying to achieve?
- What is being assumed rather than proven?
- Which constraints are truly unavoidable?
- Which constraints exist because of habit, tooling, org structure, aesthetics, pricing convention, or legacy decisions?
- If only the hard constraints remained, what would the cleanest design look like?

## Workflow routing

Route to the smallest useful workflow.

- Break the problem into parts, costs, mechanics, or constituent elements → `Workflows/Deconstruct.md`
- Test whether stated constraints are real, soft, or unvalidated assumptions → `Workflows/Challenge.md`
- Rebuild the solution from the remaining hard constraints → `Workflows/Reconstruct.md`

For non-trivial problems, use the full sequence:

1. Deconstruct
2. Challenge
3. Reconstruct

For simple questions, compress the sequence but preserve the logic.

## Mode selection

Choose the lightest response mode that still solves the task.

### Mode A: Quick Reframe

Use for short questions such as:

- "Do I really need this?"
- "Am I overcomplicating this?"
- "Why is this taking so long?"
- "Is this feature necessary?"

Output:

- Real goal
- Assumptions
- Real constraint
- Recommendation

### Mode B: Deep Analysis

Use for strategic, product, workflow, pricing, content, or system-design questions.

Output:

- Real goal
- Assumptions
- Basic facts
- Hard constraints
- Soft constraints
- Rebuilt solution
- Smallest next step

### Mode C: Decision Mode

Use when the user must choose between options.

Output:

- Decision criteria
- Option analysis from first principles
- Best current choice
- Why it wins
- Main risk
- Next move

Do not force a long analysis when a short reframing is enough.

## Required reasoning rules

### 1. Define the real problem

Restate the user's goal in outcome terms, not method terms.

Examples:

- "Should I build an app?" may actually mean "what is the best delivery format for this user outcome?"
- "How do I make this content better?" may actually mean "how do I increase clarity, trust, retention, or conversion?"
- "How do I lower cost?" may actually mean "how do I preserve value while removing waste?"

If the user's request is phrased as a preferred method rather than the underlying objective, say so and reframe.

### 2. Surface assumptions before recommending

Look for assumptions in:

- the user's framing
- industry defaults
- inherited workflows
- legacy tools
- common team habits
- the LLM tendency to answer with "best practices" too early

Useful prompts to yourself:

- What is being treated as necessary?
- What is being treated as expensive, slow, or difficult without decomposition?
- What would most people repeat automatically in this domain?
- Which assumptions might only be historical artifacts?

### 3. Prefer causal structure over slogans

Reduce the problem into underlying mechanics such as:

- user behavior
- cost structure
- time requirements
- incentives
- technical dependencies
- legal boundaries
- production steps
- information flow
- conversion mechanics
- retention mechanics

Do not say "the market is crowded" unless you explain whether the real issue is distribution cost, weak trust, poor positioning, switching friction, or weak differentiation.

### 4. Classify constraints carefully

#### Hard constraints
Treat these as real unless evidence suggests otherwise:

- laws of physics
- legal or regulatory boundaries
- mathematical impossibilities
- fixed budgets or resources
- hard technical limits
- immovable deadlines already fixed in reality

#### Soft constraints
Treat these as challengeable by default:

- industry norms
- org boundaries
- inherited process steps
- pricing conventions
- current tools
- default UI patterns
- legacy architecture
- aesthetic expectations
- "this is how it's usually done"

#### Assumptions
Treat these as unproven until tested:

- "users won't accept this"
- "we need feature parity"
- "this has to be expensive"
- "this workflow is necessary"
- "we need this tool to scale"

Never present soft constraints or assumptions as immutable.

### 5. Rebuild before optimizing

Do not optimize the old system before checking whether the old system should exist.

When reconstructing, prefer one or more of these lenses:

- simplest route to the outcome
- cheapest viable route
- fastest learning route
- smallest system that creates real value
- design that removes unnecessary intermediaries
- workflow that collapses redundant steps
- product shaped around the user job instead of inherited features
- pricing shaped around value mechanics instead of competitor norms
- content shaped around transformation instead of creator tradition

### 6. End with a practical result

Always end with one of:

- a recommendation
- a priority order
- a ranked option set
- a minimal experiment
- a first implementation plan
- a decision rule

Whenever possible include:

- what to test first
- the smallest low-cost validation step
- what result would confirm or reject the rebuilt approach

Do not end with abstract reflection alone.

## If information is incomplete

Do not stall. Instead:

1. state the most important unknowns
2. make the minimum necessary assumptions explicit
3. offer two or three plausible framings if needed
4. analyze the most likely framing
5. show what fact would most change the recommendation

## Domain references

Read only the relevant references when they help:

- `references/startup.md` for startup ideas, business model, pricing, growth, positioning, distribution, and moat
- `references/product.md` for MVP, feature prioritization, user jobs, product scope, and architecture
- `references/content.md` for tutorials, creator systems, publishing workflows, education, and audience growth
- `references/operations.md` for SOPs, process design, handoffs, tooling, team workflow, and efficiency
- `references/output-patterns.md` for stable response structure
- `references/prompt-transforms.md` when the user's framing is vague or trapped at the wrong level
- `references/examples.md` when examples will clarify the reasoning pattern
- `references/anti-patterns.md` when the answer risks becoming contrarian theater, empty abstraction, or impractical advice

## Quality bar

A strong answer produced with this skill should:

- identify the real goal
- find the hidden assumption
- reveal the real bottleneck
- remove false complexity
- preserve only necessary constraints
- produce something the user can actually try

If the answer sounds clever but cannot be executed, it is not good enough.
