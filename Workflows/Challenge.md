# Challenge Workflow

Use this workflow to test whether stated constraints are hard constraints, soft constraints, or assumptions.

## When to use

Use this workflow when:

- requirements feel overly restrictive
- someone says "we have to"
- a workflow contains many inherited steps
- cost, speed, or complexity is being accepted without proof
- the user asks whether something is really necessary
- a system needs to be stripped down before redesign

This usually follows Deconstruct.

## Core question

Is this a law of reality, a decision, or an assumption?

If it is a decision, it can be changed.
If it is an assumption, it can be tested.
Only hard constraints should be treated as truly fixed.

## Constraint types

### Hard constraints
These come from reality and should be treated as real unless evidence says otherwise.

Examples:

- legal or regulatory limits
- laws of physics
- mathematical impossibilities
- fixed resource caps
- truly immovable deadlines
- hard technical boundaries

### Soft constraints
These are choices, conventions, or inherited structures.

Examples:

- team boundaries
- tool choices
- default workflows
- pricing norms
- architecture conventions
- standard process steps
- habitual approval layers

### Assumptions
These are unvalidated beliefs.

Examples:

- users will not accept this
- we need feature parity
- this must be expensive
- we need a dashboard
- we cannot simplify further
- the market expects this format

## Process

### Step 1: Gather all stated constraints

List every requirement, restriction, expectation, and "must."

Include:

- explicit requirements
- inherited rules
- team habits
- industry defaults
- platform constraints
- business assumptions
- unstated but obvious conventions

### Step 2: Classify each constraint

For each one, decide:

- Hard
- Soft
- Assumption

Do not rush. Misclassification ruins the whole analysis.

### Step 3: Challenge every non-hard constraint

For each soft constraint, ask:

- Who decided this?
- Why was it chosen?
- Is that reason still valid?
- What would happen if we removed it?
- What value does it preserve?
- What cost does it create?

For each assumption, ask:

- What evidence supports it?
- What evidence weakens it?
- Has anyone tested the opposite?
- What experiment would validate or falsify it?

### Step 4: Find hidden assumptions

The most dangerous constraints are often unstated.

Look for:

- things everybody in the domain repeats automatically
- defaults inherited from tools or platforms
- "professionalism" expectations with no direct value link
- complexity added for reassurance rather than results
- habits mistaken for requirements

### Step 5: Highlight what is worth challenging

Do not just classify. Prioritize.

Identify which soft constraints or assumptions create the most waste, complexity, delay, or strategic blindness.

## Output format

Use this structure when helpful:

### All stated constraints
List them.

### Hard constraints
List the ones that are truly fixed and why.

### Soft constraints
List the ones that are choice-based and what would happen if challenged.

### Assumptions
List the unvalidated beliefs and how they could be tested.

### Hidden constraints
List important unstated defaults you found.

### Best challenge targets
Show which non-hard constraints are most worth attacking first.

### Recommended actions
Give the next step:
- validate
- remove
- reduce
- renegotiate
- redesign around

## Quality bar

A good challenge analysis should:

- reduce false certainty
- expose inherited nonsense
- preserve real constraints
- create room for better design

If everything still looks fixed, you probably accepted too much without testing it.
