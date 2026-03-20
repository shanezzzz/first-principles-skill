# first-principles

A reusable agent skill for applying first-principles reasoning to startup, product, content, operations, pricing, growth, workflow, strategy, and decision-making problems.

It helps an LLM move beyond analogy and default best practices by forcing a cleaner sequence:

1. **Deconstruct** the problem into real parts
2. **Challenge** stated constraints and assumptions
3. **Reconstruct** a better solution from verified facts and hard constraints

## What this skill does

This skill is designed to make agents:

- identify the user's real goal instead of accepting the initial framing
- expose hidden assumptions
- distinguish **hard constraints**, **soft constraints**, and **assumptions**
- reduce problems into mechanics like cost, time, incentives, behavior, and dependencies
- rebuild simpler, lower-cost, more testable solutions
- end with a recommendation, prioritization, or experiment

## Best use cases

Use this skill when the user asks things like:

- Does this really have to be this way?
- What are we assuming?
- What is the real bottleneck?
- Why is this so slow, expensive, or complex?
- What should we remove?
- If we started from zero, how would we design this?

It is especially useful for:

- startup strategy
- business model and pricing questions
- MVP and product scope decisions
- content and tutorial workflow design
- process simplification and operations redesign
- system and workflow redesign
- high-leverage decision-making

## Structure

```text
first-principles/
├── SKILL.md
├── Workflows/
│   ├── Challenge.md
│   ├── Deconstruct.md
│   └── Reconstruct.md
└── references/
    ├── anti-patterns.md
    ├── content.md
    ├── examples.md
    ├── operations.md
    ├── output-patterns.md
    ├── product.md
    ├── prompt-transforms.md
    └── startup.md
```

## Workflow model

### 1. Deconstruct
Break a system or problem into actual components, steps, costs, dependencies, and facts.

### 2. Challenge
Classify constraints into:

- **Hard constraints**: reality, physics, law, true technical limits
- **Soft constraints**: choices, conventions, inherited workflows
- **Assumptions**: beliefs that may not be validated

### 3. Reconstruct
Design the cleanest solution that preserves only the hard constraints and verified facts.

## Included references

- **startup.md** — business model, pricing, growth, moat, competition
- **product.md** — MVP, feature prioritization, user jobs, product scope
- **content.md** — creator workflows, tutorials, educational content systems
- **operations.md** — SOPs, workflow redesign, approvals, handoffs, efficiency
- **prompt-transforms.md** — convert vague questions into first-principles frames
- **examples.md** — concrete examples of the reasoning pattern in action
- **output-patterns.md** — structured response formats
- **anti-patterns.md** — guidance to avoid shallow contrarianism or empty abstraction

## Installation

### Option 1: Install from packaged `.skill`
Use the packaged release artifact:

```text
dist/first-principles.skill
```

### Option 2: Use the source skill directory
Use the `first-principles/` folder directly in environments that load skills from source directories.

## Repository contents

- `first-principles/` — source skill
- `dist/first-principles.skill` — packaged skill artifact

## Design goals

This skill is meant to be both:

- a **directly usable end-user skill** for practical reasoning
- a **reusable thinking primitive** other skills can build on

The goal is not to sound philosophical. The goal is to produce cleaner decisions and better next steps.
